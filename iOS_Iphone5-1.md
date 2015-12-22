#### Test 543122982543be8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/36180D86-14B6-4BC5-8133-7EAC3A3E035B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/36180D86-14B6-4BC5-8133-7EAC3A3E035B/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122982543be8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AC508E59-BDD5-4115-87BA-7597F2508F4E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61972"
,(lldb)     command script import "/tmp/36180D86-14B6-4BC5-8133-7EAC3A3E035B/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-22 01:48:14.779 ThaliTest[583:924295] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F41050FB-9E7A-4BAA-8D17-DC18489CF207/Library/Cookies/Cookies.binarycookies
,2015-12-22 01:48:15.334 ThaliTest[583:924295] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-22 01:48:15.335 ThaliTest[583:924295] Multi-tasking -> Device: YES, App: YES
,2015-12-22 01:48:15.342 ThaliTest[583:924295] Unlimited access to network resources
,2015-12-22 01:48:15.353 ThaliTest[583:924295] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-22 01:48:25.694 ThaliTest[583:924295] Resetting plugins due to page load.
,2015-12-22 01:48:29.284 ThaliTest[583:924295] Finished load of: file:///var/mobile/Containers/Bundle/Application/AC508E59-BDD5-4115-87BA-7597F2508F4E/ThaliTest.app/www/index.html
,2015-12-22 01:48:29.496 ThaliTest[583:924295] JXcore Cordova plugin initializing
,2015-12-22 01:48:29.498 ThaliTest[583:924482] JXcore instance initializing
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
,found test : ./testSendData2.js
,2015-12-22 01:48:31.970 ThaliTest[583:924295] THREAD WARNING: ['JXcore'] took '167.135010' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-22 01:54:50.001 ThaliTest[583:924482] jxcore: startBroadcasting
,2015-12-22 01:54:50.015 ThaliTest[583:924482] server: starting Apple-Iphone5-1_PT5195.3svwkg==
,2015-12-22 01:54:50.016 ThaliTest[583:924482] multipeer session: start timer: 0x194332e0
,2015-12-22 01:54:50.016 ThaliTest[583:924482] THEMultipeerSession initialized peer Apple-Iphone5-1_PT5195
,2015-12-22 01:54:50.017 ThaliTest[583:924482] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-22 01:54:51.134 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT8764.Y1JJAA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-22 01:54:51.193 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
,teardown
,testFindPeers stopped
,2015-12-22 01:54:52.513 ThaliTest[583:924482] jxcore: stopBroadcasting
2015-12-22 01:54:52.513 ThaliTest[583:924482] THEMultipeerSession stopping peer
2015-12-22 01:54:52.514 ThaliTest[583:924482] multipeer session: stop timer
2015-12-22 01:54:52.514 Th,aliTest[583:924482] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56321
,2015-12-22 01:54:52.578 ThaliTest[583:924482] jxcore: startBroadcasting
,2015-12-22 01:54:52.580 ThaliTest[583:924482] server: starting Apple-Iphone5-1_PT5195.x5+2Tg==
2015-12-22 01:54:52.581 ThaliTest[583:924482] multipeer session: start timer: 0x193c8670
2015-12-22 01:54:52.581 ThaliTest[583:924482] THEMultipeerSession init,ialized peer Apple-Iphone5-1_PT5195
2015-12-22 01:54:52.582 ThaliTest[583:924482] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-22T00:54:52.584Z SendDataTCPServer.js: TCP/IP server is bound to port: 56321
,2015-12-22 01:54:53.050 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:53.050 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.4oKZxQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:53.054 ThaliTest[583:924295] client: found peer: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22T00:54:53.054Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22,T00:54:53.055Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22T00:54:53.055Z SendDataConnector.js: do connect now
2015-12-22 01:54:53.056 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2,015-12-22 01:54:53.056 ThaliTest[583:924482] client session: connect
2015-12-22 01:54:53.057 ThaliTest[583:924482] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.4oKZxQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.3svwkg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:53.635 ThaliTest[583:924295] client: lost peer: Apple-Iphone5-1_PT5195.3svwkg==
2015-12-22 01:54:53.636 ThaliTest[583:924295] client session: onPeerLost: Apple-Iphone5-1_PT5195.3svwkg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5195.3svwkg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22 01:54:53.822 ThaliTest[583:924295] client: lost peer: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.822 ThaliTest[583:924295] client session: onPeerLost: Apple-IpadAir2-1_PT8764.Y1JJAA==
2015-12-22 01:54:53.822 ThaliTest[583:924295] cli,ent: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Y1JJAA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:53.836 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:53.841 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8764.Ptw77g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-22 01:54:54.717 ThaliTest[583:924295] client: lost peer: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.717 ThaliTest[583:924295] client session: onPeerLost: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.717 ThaliTest[583:924295] clien,t session: onLinkFailure: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.717 ThaliTest[583:924295] client session: disconnect
2015-12-22 01:54:54.718 ThaliTest[583:924295] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 ,01:54:54.718 ThaliTest[583:924295] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:54:54.718 ThaliTest[583:924295] jxcore: connect: fail: Peer disconnected
2015-12-22T00:54:54.719Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-22T00:54:54.720Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-22T00:54:54.720Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_P,T4682.4oKZxQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-22T00:54:59.729Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:54:59.730Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:04.733 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:04.734 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:55:04.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==,
2015-12-22T00:55:04.735Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
2015-12-22T00:55:04.736Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:04.736Z SendDataConnector.js: do connect now
2015-12-22 01:55:04.737 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:04.737 ThaliTest[583:924482] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:04.737 ThaliTest[583:924482] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:04.738Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:04.738Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:04.738Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:09.750Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:09.751Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:14.754 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:14.755 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:55:14.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==,
2015-12-22T00:55:14.756Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
2015-12-22T00:55:14.756Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22T00:55:14.756Z SendDataConnector.js: do connect now
,2015-12-22 01:55:14.757 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:14.758 ThaliTest[583:924482] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:14.758 ThaliTest[583:924482] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:14.758Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:14.759Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-22T00:55:14.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:55:19.759Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:19.760Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:22.582 ThaliTest[583:924295] multipeer session: restart
,2015-12-22 01:55:22.621 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:22.622 ThaliTest[583:924295] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:22.623 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:24.767 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:24.768 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:55:24.768Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==,
2015-12-22T00:55:24.769Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
2015-12-22T00:55:24.769Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
2015-,12-22T00:55:24.770Z SendDataConnector.js: do connect now
,2015-12-22 01:55:24.770 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:24.770 ThaliTest[583:924482] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:24.771 ThaliTest[583:924482] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:24.771Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:24.771Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-22T00:55:24.772Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22 01:55:29.350 ThaliTest[583:924295] client: lost peer: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:29.350 ThaliTest[583:924295] client session: onPeerLost: Apple-Iphone6-1_PT4682.uK405g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22T00:55:29.775Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22T00:55:29.775Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,2015-12-22 01:55:33.014 ThaliTest[583:924295] client: lost peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:33.014 ThaliTest[583:924295] client session: onPeerLost: Apple-Iphone5s-1_PT9511.iUx4mA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-22 01:55:34.788 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:34.788 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:55:34.789Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==,
2015-12-22T00:55:34.789Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4682.4oKZxQ== with availability status: true
2015-12-22T00:55:34.789Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.4oKZxQ==
2015-,12-22T00:55:34.790Z SendDataConnector.js: do connect now
,2015-12-22 01:55:34.791 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:34.792 ThaliTest[583:924482] client: connect: unreachable Apple-Iphone6-1_PT4682.4oKZxQ==
2015-12-22 01:55:34.792 ThaliTest[583:924482] jxcore: connect: fail: Peer unreachable
,2015-12-22T00:55:34.792Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-22T00:55:34.793Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-22T00:55:34.794Z SendDataConnector.js: CLIENT Stop now
,2015-12-22 01:55:34.795 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:34.795 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:55:34.795Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.4oKZxQ==
,---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:55:34.797Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:55:34.797Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22T00:55:34.797Z SendDataConnector.js: do connect now
,2015-12-22 01:55:34.798 ThaliTest[583:924482] jxcore: connect Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:55:34.798 ThaliTest[583:924482] client session: connect
2015-12-22 01:55:34.799 ThaliTest[583:924482] client session: stateChange:0->1 Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:35.276 ThaliTest[583:924295] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9511.iUx4mA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
2015-12-22 01:55:35.279 ThaliTest[583:924295] multipeer session: reset timer
2015-12-22 01:55:35.279 ThaliTest[583:924295] multipeer session: stop timer
2015-12-22 01:55:35.279 ThaliTest[583:924295] multipeer session: start timer: 0x193c8670
2015-12,-22 01:55:35.280 ThaliTest[583:924295] server session: connect
2015-12-22 01:55:35.280 ThaliTest[583:924295] server session: stateChange:0->1 Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:35.287 ThaliTest[583:924295] server: accepting invitation Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:38.856 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4682.uK405g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-22 01:55:38.895 ThaliTest[583:925446] client session: connected
2015-12-22 01:55:38.895 ThaliTest[583:925446] client session: stateChange:1->2 Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:38.904 ThaliTest[583:925460] server session: connected
,2015-12-22 01:55:38.904 ThaliTest[583:925460] server session: stateChange:1->2 Apple-IpadAir2-1_PT8764
,2015-12-22 01:55:38.917 ThaliTest[583:925460] client session: fireConnectCallback: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:55:38.920 ThaliTest[583:925460] jxcore: connect: success
2015-12-22T00:55:38.921Z SendDataConnector.js: CLIENT connected to 56326, error: null
2015-12-22T00:55:38.921Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:55:38.927 ThaliTest[583:924295] client: relay established
2015-12-22 01:55:38.927 ThaliTest[583:924295] client: new accepted socket: 0x193de870
,2015-12-22 01:55:38.933 ThaliTest[583:924295] server relay: connected (to port: 56321)
2015-12-22T00:55:38.938Z SendDataTCPServer.js: TCP/IP server connected
2015-12-22T00:55:38.941Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:55:39.470Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-22T00:55:39.477Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-22T00:55:39.490Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-22T00:55:39.504Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-22 01:55:39.512 ThaliTest[583:925445] server session: not connected Apple-IpadAir2-1_PT8764
,2015-12-22T00:55:39.528Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-22T00:55:39.541Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-22T00:55:39.555Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-22T00:55:39.556Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-22T00:55:39.557Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:55:39.558Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:55:39.559 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:39.560 ThaliTest[583:924482] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:55:39.560 ThaliTest[583:924482] client session: disconnect
,2015-12-22 01:55:39.560 ThaliTest[583:924482] client session: stateChange:2->0 Apple-IpadAir2-1_PT8764.Ptw77g==
,2015-12-22 01:55:39.568 ThaliTest[583:924482] jxcore: disconnect: success
2015-12-22T00:55:39.569Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8764.Ptw77g==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22T00:55:39.570Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:55:39.571Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22T00:55:39.571Z SendDataConnector.j,s: do connect now
,2015-12-22 01:55:39.572 ThaliTest[583:924482] jxcore: connect Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:39.574 ThaliTest[583:924482] client session: connect
,2015-12-22 01:55:39.583 ThaliTest[583:924482] client session: stateChange:0->1 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:42.509 ThaliTest[583:925459] client session: connected
2015-12-22 01:55:42.509 ThaliTest[583:925459] client session: stateChange:1->2 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:42.557 ThaliTest[583:925460] client session: fireConnectCallback: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:42.557 ThaliTest[583:925460] jxcore: connect: success
2015-12-22T00:55:42.558Z SendDataConnector.js: CLIENT connected to 56330, error: null
2015-12-22T00:55:42.558Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:55:42.560 ThaliTest[583:924295] client: relay established
2015-12-22 01:55:42.560 ThaliTest[583:924295] client: new accepted socket: 0x1945f5e0
,2015-12-22T00:55:42.573Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:55:43.122Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-22T00:55:43.138Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-22T00:55:43.152Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-22T00:55:43.166Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-22T00:55:43.167Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-22T00:55:43.170Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:55:43.170Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:55:43.171 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:55:43.171 ThaliTest[583:924482] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:55:43.172 ThaliTest[583:924482] client session: disconnect
,2015-12-22 01:55:43.172 ThaliTest[583:924482] client session: stateChange:2->0 Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:55:43.180 ThaliTest[583:924482] jxcore: disconnect: success
2015-12-22T00:55:43.181Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9511.iUx4mA==
---- round done--------
startWithNextDevice
device[4]: Appl,e-Iphone6-1_PT4682.uK405g==
2015-12-22T00:55:43.182Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4682.uK405g==
2015-12-22T00:55:43.182Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
2015-12-22T00:55:,43.182Z SendDataConnector.js: do connect now
2015-12-22 01:55:43.182 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:55:43.183 ThaliTest[583:924482] client session: connect
2015-12-22 01:55:43.183 ThaliTest[583:924482] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:05.281 ThaliTest[583:924295] multipeer session: restart
,2015-12-22 01:56:05.316 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:05.318 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:05.318 ThaliTest[583:924295] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
,2015-12-22 01:56:16.197 ThaliTest[583:925543] client session: not connected Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:16.197 ThaliTest[583:925543] client session: onLinkFailure: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:16.198 ThaliTest[583,:925543] client session: disconnect
2015-12-22 01:56:16.198 ThaliTest[583:925543] client session: stateChange:1->0 Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:16.199 ThaliTest[583:925543] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.u,K405g==
2015-12-22 01:56:16.199 ThaliTest[583:925543] jxcore: connect: fail: Peer disconnected
2015-12-22T00:56:16.200Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-22T00:56:16.201Z SendDataConnector.js: CLIENT Can not C,onnect: Peer disconnected
2015-12-22T00:56:16.201Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-22T00:56:21.208Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22T00:56:21.209Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:26.210 ThaliTest[583:924482] jxcore: disconnect
2015-12-22 01:56:26.211 ThaliTest[583:924482] jxcore: disconnect: fail
2015-12-22T00:56:26.211Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==,
2015-12-22T00:56:26.212Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4682.uK405g== with availability status: true
2015-12-22T00:56:26.212Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4682.uK405g==
2015-12-22T00:56:26.212Z SendDataConnector.js: do connect now
,2015-12-22 01:56:26.214 ThaliTest[583:924482] jxcore: connect Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:26.214 ThaliTest[583:924482] client session: connect
2015-12-22 01:56:26.214 ThaliTest[583:924482] client session: stateChange:0->1 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:29.196 ThaliTest[583:925619] client session: connected
2015-12-22 01:56:29.197 ThaliTest[583:925619] client session: stateChange:1->2 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:29.202 ThaliTest[583:925622] client session: fireConnectCallback: Apple-Iphone6-1_PT4682.uK405g==
2015-12-22 01:56:29.202 ThaliTest[583:925622] jxcore: connect: success
,2015-12-22T00:56:29.205Z SendDataConnector.js: CLIENT connected to 56337, error: null
2015-12-22T00:56:29.205Z SendDataConnector.js: CLIENT starting client 
,2015-12-22 01:56:29.208 ThaliTest[583:924295] client: relay established
2015-12-22 01:56:29.209 ThaliTest[583:924295] client: new accepted socket: 0x193dd170
,2015-12-22T00:56:29.221Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-22T00:56:29.750Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-22T00:56:29.778Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-22T00:56:29.793Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-22T00:56:29.793Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-22T00:56:29.794Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:56:29.794Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:56:29.795 ThaliTest[583:924482] jxcore: disconnect
,2015-12-22 01:56:29.796 ThaliTest[583:924482] client session: disconnectFromPeer: Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:29.797 ThaliTest[583:924482] client session: disconnect
,2015-12-22 01:56:29.798 ThaliTest[583:924482] client session: stateChange:2->0 Apple-Iphone6-1_PT4682.uK405g==
,2015-12-22 01:56:29.874 ThaliTest[583:924482] jxcore: disconnect: success
2015-12-22T00:56:29.875Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4682.uK405g==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
,done, now sending data to server
,2015-12-22T00:56:29.881Z SendDataConnector.js: CLIENT Stop now
,2015-12-22T00:56:29.881Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-22 01:56:35.281 ThaliTest[583:924295] multipeer session: restart
,2015-12-22 01:56:35.315 ThaliTest[583:924295] client: found peer: Apple-Iphone5s-1_PT9511.iUx4mA==
2015-12-22 01:56:35.315 ThaliTest[583:924295] client: found peer: Apple-IpadAir2-1_PT8764.Ptw77g==
2015-12-22 01:56:35.317 ThaliTest[583:924295] client: found peer: Apple-Iphone6-1_PT4682.uK405g==
,teardown
,testSendData stopped
,2015-12-22 01:56:35.894 ThaliTest[583:924482] jxcore: stopBroadcasting
2015-12-22 01:56:35.895 ThaliTest[583:924482] THEMultipeerSession stopping peer
2015-12-22 01:56:35.895 ThaliTest[583:924482] multipeer session: stop timer
,2015-12-22 01:56:35.895 ThaliTest[583:924482] server session: disconnect
,2015-12-22 01:56:35.896 ThaliTest[583:924482] server session: stateChange:2->0 Apple-IpadAir2-1_PT8764
,2015-12-22 01:56:35.901 ThaliTest[583:924482] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-22T00:56:35.917Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-22T00:56:35.917Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
