#### Test 50650278e3ff7c2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/58F5745F-2226-4234-A8C3-A7C5E9C23F7F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/58F5745F-2226-4234-A8C3-A7C5E9C23F7F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D3A8762E-9209-4F47-812A-3203712B4286/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55105"
,(lldb)     command script import "/tmp/58F5745F-2226-4234-A8C3-A7C5E9C23F7F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 14:36:57.098 ThaliTest[884:1152893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9C30BCE6-F3FF-4222-8F37-D088F502DCAB/Library/Cookies/Cookies.binarycookies
,2015-12-14 14:36:57.436 ThaliTest[884:1152893] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 14:36:57.436 ThaliTest[884:1152893] Multi-tasking -> Device: YES, App: YES
,2015-12-14 14:36:57.441 ThaliTest[884:1152893] Unlimited access to network resources
,2015-12-14 14:36:57.448 ThaliTest[884:1152893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 14:37:05.471 ThaliTest[884:1152893] Resetting plugins due to page load.
,2015-12-14 14:37:08.245 ThaliTest[884:1152893] Finished load of: file:///var/mobile/Containers/Bundle/Application/D3A8762E-9209-4F47-812A-3203712B4286/ThaliTest.app/www/index.html
,2015-12-14 14:37:08.445 ThaliTest[884:1152893] JXcore Cordova plugin initializing
,2015-12-14 14:37:08.446 ThaliTest[884:1153290] JXcore instance initializing
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
,2015-12-14 14:37:09.525 ThaliTest[884:1152893] THREAD WARNING: ['JXcore'] took '79.047363' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 14:43:59.216 ThaliTest[884:1153290] jxcore: startBroadcasting
,2015-12-14 14:43:59.235 ThaliTest[884:1153290] server: starting Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:43:59.247 ThaliTest[884:1153290] multipeer session: start timer: 0x18398f70
,2015-12-14 14:43:59.257 ThaliTest[884:1153290] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4340
,2015-12-14 14:43:59.259 ThaliTest[884:1153290] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 14:44:01.855 ThaliTest[884:1152893] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT3867.cSCWVA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-14 14:44:02.149 ThaliTest[884:1152893] client: found peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:02.151 ThaliTest[884:1152893] client: found peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
,teardown
,testFindPeers stopped
,2015-12-14 14:44:02.182 ThaliTest[884:1153290] jxcore: stopBroadcasting
2015-12-14 14:44:02.183 ThaliTest[884:1153290] THEMultipeerSession stopping peer
2015-12-14 14:44:02.183 ThaliTest[884:1153290] multipeer session: stop timer
2015-12-14 14:44:02.183 ThaliTest[884:1153290] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57316
,2015-12-14 14:44:02.253 ThaliTest[884:1153290] jxcore: startBroadcasting
,2015-12-14 14:44:02.257 ThaliTest[884:1153290] server: starting Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:02.258 ThaliTest[884:1153290] multipeer session: start timer: 0x1847a2f0
,2015-12-14 14:44:02.265 ThaliTest[884:1153290] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4340
,2015-12-14 14:44:02.273 ThaliTest[884:1153290] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-14 14:44:02.283 ThaliTest[884:1152893] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
null
,2015-12-14T13:44:02.285Z SendDataTCPServer.js: TCP/IP server is bound to port: 57316
,2015-12-14 14:44:02.285 ThaliTest[884:1152893] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
,2015-12-14 14:44:02.287 ThaliTest[884:1152893] client: found peer: Apple-IpadAir2-1_PT6041.yRvsxw==
,2015-12-14 14:44:02.288 ThaliTest[884:1152893] client: found peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:02.296Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:02.296Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:02.297Z SendDataConnector.js: do connect now
,2015-12-14 14:44:02.297 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:02.298 ThaliTest[884:1153290] client session: connect
,2015-12-14 14:44:02.299 ThaliTest[884:1153290] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.cSCWVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.I4GUOQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 14:44:03.308 ThaliTest[884:1152893] client: lost peer: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:03.309 ThaliTest[884:1152893] client session: onPeerLost: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 14:44:03.967 ThaliTest[884:1152893] client: lost peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:03.969 ThaliTest[884:1152893] client session: onPeerLost: Apple-IpadAir2-1_PT6041.yRvsxw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 14:44:04.283 ThaliTest[884:1152893] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.byADbw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-14 14:44:04.521 ThaliTest[884:1152893] client: lost peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:04.521 ThaliTest[884:1152893] client session: onPeerLost: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:04.521 ThaliTest[884:1152893] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:04.521 ThaliTest[884:1152893] client session: disconnect
2015-12-14 14:44:04.522 ThaliTest[884:1152893] client session: stateChange:1->0 Apple-Iphone5-1_PT3867.cSCWVA==
2015-1,2-14 14:44:04.523 ThaliTest[884:1152893] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:04.523 ThaliTest[884:1152893] jxcore: connect: fail: Peer disconnected
2015-12-14 14:44:04.523 ThaliTest[884:1152893] client: f,ound peer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14T13:44:04.525Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-14T13:44:04.526Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T13:44:04.526Z S,endDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.0mupng==","peerName":,"(null)","peerAvailable":true}]
2015-12-14 14:44:04.534 ThaliTest[884:1152893] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.aZvv+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:09.110 ThaliTest[884:1152893] client: lost peer: Apple-Iphone5s-1_PT4136.I4GUOQ==
2015-12-14 14:44:09.110 ThaliTest[884:1152893] client session: onPeerLost: Apple-Iphone5s-1_PT4136.I4GUOQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT4136.I4GUOQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T13:44:09.536Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:09.538Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:14.543 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:14.543 ThaliTest[884:1153290] jxcore: disconnect: fail
2015-12-14T13:44:14.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:14.544Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:14.544Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:14.545Z SendDataConnector.js: do connect now
,2015-12-14 14:44:14.546 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:14.547 ThaliTest[884:1153290] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:14.547 ThaliTest[884:1153290] jxco,re: connect: fail: Peer unreachable
2015-12-14T13:44:14.548Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:14.548Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:14.548Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:19.557Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:19.558Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:24.565 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:24.566 ThaliTest[884:1153290] jxcore: disconnect: fail
2015-12-14T13:44:24.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:24.567Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:24.567Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:24.567Z SendDataConnector.js: do connect now
,2015-12-14 14:44:24.568 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:24.569 ThaliTest[884:1153290] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:24.569 ThaliTest[884:1153290] jxco,re: connect: fail: Peer unreachable
2015-12-14T13:44:24.570Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:24.570Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:24.571Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:29.576Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:29.576Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:32.261 ThaliTest[884:1152893] multipeer session: restart
,2015-12-14 14:44:32.304 ThaliTest[884:1152893] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:32.305 ThaliTest[884:1152893] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:32.307 ThaliTest[884:1152893] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:44:34.578 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:34.578 ThaliTest[884:1153290] jxcore: disconnect: fail
2015-12-14T13:44:34.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:34.579Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:34.580Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:34.580Z SendDataConnector.js: do connect now
2015-12-14 14:44:34.581 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:34.582 ThaliTest[884:1153290] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:34.583 ThaliTest[884:1153290] jxcore: connect: fail: Peer unreachable
2015-12-14T13:44:34.584Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:34.584Z SendDataConnector.js: CLIENT Can not Connect: Pe,er unreachable
2015-12-14T13:44:34.585Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:39.595Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:39.596Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:44.594 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:44.595 ThaliTest[884:1153290] jxcore: disconnect: fail
2015-12-14T13:44:44.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:44.596Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:44.596Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
201,5-12-14T13:44:44.596Z SendDataConnector.js: do connect now
,2015-12-14 14:44:44.597 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:44.598 ThaliTest[884:1153290] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:44.599 ThaliTest[884:1153290] jxcore: connect: fail: Peer unreachable
2015-12-14T13:44:44.599Z SendDataConnector.js: CLIENT conne,cted to 0, error: Peer unreachable
2015-12-14T13:44:44.600Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-14T13:44:44.602Z SendDataConnector.js: CLIENT Stop now
,2015-12-14 14:44:44.603 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:44.604 ThaliTest[884:1153290] jxcore: disconnect: fail
2015-12-14T13:44:44.604Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14T13:44:44.607Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14T13:44:44.608Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14T13:44:44.608Z SendDataConnector.js: do connect now
,2015-12-14 14:44:44.609 ThaliTest[884:1153290] jxcore: connect Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:44.610 ThaliTest[884:1153290] client session: connect
2015-12-14 14:44:44.610 ThaliTest[884:1153290] client session: stateChange:0->1 Apple-I,padAir2-1_PT6041.byADbw==
,2015-12-14 14:44:47.762 ThaliTest[884:1154078] client session: connected
2015-12-14 14:44:47.762 ThaliTest[884:1154078] client session: stateChange:1->2 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:47.780 ThaliTest[884:1154112] client session: fireConnectCallback: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:47.780 ThaliTest[884:1154112] jxcore: connect: success
2015-12-14T13:44:47.782Z SendDataConnector.js: CLIENT connected t,o 57320, error: null
2015-12-14T13:44:47.782Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:47.787 ThaliTest[884:1152893] client: relay established
2015-12-14 14:44:47.787 ThaliTest[884:1152893] client: new accepted socket: 0x18487cd0
,2015-12-14T13:44:47.801Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:48.091Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-14T13:44:48.102Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:44:48.102Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:44:48.102Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:48.103Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:48.104 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:48.104 ThaliTest[884:1153290] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:44:48.104 ThaliTest[884:1153290] client session: disconnec,t
2015-12-14 14:44:48.104 ThaliTest[884:1153290] client session: stateChange:2->0 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:44:48.109 ThaliTest[884:1153290] jxcore: disconnect: success
2015-12-14T13:44:48.109Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6041.byADbw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14T13:44:48.109Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3867.0mupng==
2015-12-14T13:44:48.109Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.0mupng==
2015-12-14T13:44:48.109Z SendDataConnector.js: do connect now
2015-12-14 14:44:48.110 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:48.110 ThaliTest[884:1153290] client session: connect
2015-12-14 14:44:48.110 ThaliTest[884:115,3290] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:50.902 ThaliTest[884:1154078] client session: connected
2015-12-14 14:44:50.902 ThaliTest[884:1154078] client session: stateChange:1->2 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:50.964 ThaliTest[884:1154112] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:50.965 ThaliTest[884:1154112] jxcore: connect: success
,2015-12-14T13:44:50.966Z SendDataConnector.js: CLIENT connected to 57323, error: null
2015-12-14T13:44:50.967Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:44:50.970 ThaliTest[884:1152893] client: relay established
2015-12-14 14:44:50.971 ThaliTest[884:1152893] client: new accepted socket: 0x18489e90
,2015-12-14T13:44:50.983Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:51.276Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T13:44:51.287Z SendDataConnector.js: CLIENT is data received : 80000
,oneRoundDownNow
2015-12-14T13:44:51.300Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-14T13:44:51.300Z SendDataConnector.js: got all data for this round
,2015-12-14T13:44:51.301Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:44:51.301Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:51.301 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:51.301 ThaliTest[884:1153290] client session: disconnectFromPeer: Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:51.302 ThaliTest[884:1153290] client session: disconnect
2015-12-14 14:44:51.302 ThaliTest[884:1153290] client session: stateChange:2->0 Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:44:51.306 ThaliTest[884:1153290] jxcore: disconnect: success
2015-12-14T13:44:51.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.0mupng==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:44:51.307Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:44:51.307Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:,44:51.307Z SendDataConnector.js: do connect now
2015-12-14 14:44:51.307 ThaliTest[884:1153290] jxcore: connect Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:44:51.307 ThaliTest[884:1153290] client session: connect
2015-12-14 14:44:51.309 ThaliTest[884:1153290] client session: stateChange:0->1 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:44:51.397 ThaliTest[884:1152893] multipeer session: reset timer
2015-12-14 14:44:51.397 ThaliTest[884:1152893] multipeer session: stop timer
2015-12-14 14:44:51.397 ThaliTest[884:1152893] multipeer session: start timer: 0x1847a2f0
2015-12-14 14:44:51.398 ThaliTest[884:1152893] server session: connect
2015-12-14 14:44:51.398 ThaliTest[884:1152893] server session: stateChange:0->1 Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:51.401 ThaliTest[884:1152893] server: accepting invitation Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:53.453 ThaliTest[884:1152893] multipeer session: reset timer
2015-12-14 14:44:53.453 ThaliTest[884:1152893] multipeer session: stop timer
2015-12-14 14:44:53.453 ThaliTest[884:1152893] multipeer session: start timer: 0x1847a2f0
2015-12-,14 14:44:53.454 ThaliTest[884:1152893] server session: connect
2015-12-14 14:44:53.454 ThaliTest[884:1152893] server session: stateChange:0->1 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:53.463 ThaliTest[884:1152893] server: accepting invitation Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:54.031 ThaliTest[884:1154078] server session: connected
2015-12-14 14:44:54.034 ThaliTest[884:1154078] server session: stateChange:1->2 Apple-Iphone5s-1_PT4136
,2015-12-14T13:44:54.045Z SendDataTCPServer.js: TCP/IP server connected
2015-12-14 14:44:54.047 ThaliTest[884:1152893] server relay: connected (to port: 57316)
,2015-12-14 14:44:54.433 ThaliTest[884:1154112] client session: connected
2015-12-14 14:44:54.433 ThaliTest[884:1154112] client session: stateChange:1->2 Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:44:54.436 ThaliTest[884:1154112] client session: fireConnectCallback: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:44:54.437 ThaliTest[884:1154112] jxcore: connect: success
2015-12-14T13:44:54.438Z SendDataConnector.js: CLIENT connected to 57327, error: null
2015-12-14T13:44:54.438Z SendDataConnector.js:, CLIENT starting client 
2015-12-14 14:44:54.441 ThaliTest[884:1152893] client: relay established
2015-12-14 14:44:54.441 ThaliTest[884:1152893] client: new accepted socket: 0x183b6610
,2015-12-14T13:44:54.454Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:44:54.832Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-14T13:44:55.032Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-14T13:44:55.045Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-14T13:44:55.314Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T13:44:55.317Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14T13:44:55.368Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:44:55.369Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:44:55.370Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:44:55.371Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:55.372 ThaliTest[884:1153290] jxcore: disconnect
2015-12-14 14:44:55.373 ThaliTest[884:1153290] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:44:55.373 ThaliTest[884:1153290] client session: disconnec,t
2015-12-14 14:44:55.373 ThaliTest[884:1153290] client session: stateChange:2->0 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:44:55.387 ThaliTest[884:1153290] jxcore: disconnect: success
2015-12-14T13:44:55.387Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4136.aZvv+w==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T13:44:55.394Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:44:55.394Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:44:55.424 ThaliTest[884:1154063] server session: not connected Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:56.240 ThaliTest[884:1154112] server session: connected
2015-12-14 14:44:56.240 ThaliTest[884:1154112] server session: stateChange:1->2 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:56.256 ThaliTest[884:1152893] server relay: connected (to port: 57316)
,2015-12-14T13:44:56.265Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:56.522Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-14T13:44:56.537Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-14T13:44:56.555Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-14T13:44:56.572Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T13:44:56.588Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:56.634 ThaliTest[884:1154112] server session: not connected Apple-IpadAir2-1_PT6041
,2015-12-14 14:45:23.455 ThaliTest[884:1152893] multipeer session: restart
,2015-12-14 14:45:23.498 ThaliTest[884:1152893] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:23.499 ThaliTest[884:1152893] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:45:23.499 ThaliTest[884:1152893] client: found peer: Apple-Iphone5-1_PT3867.0mupng==
,2015-12-14 14:45:24.392 ThaliTest[884:1152893] multipeer session: reset timer
2015-12-14 14:45:24.392 ThaliTest[884:1152893] multipeer session: stop timer
2015-12-14 14:45:24.393 ThaliTest[884:1152893] multipeer session: start timer: 0x1847a2f0
2015-12-,14 14:45:24.393 ThaliTest[884:1152893] server session: connect
2015-12-14 14:45:24.393 ThaliTest[884:1152893] server session: stateChange:0->1 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:24.404 ThaliTest[884:1152893] server: accepting invitation Apple-Iphone5-1_PT3867
,2015-12-14 14:45:27.301 ThaliTest[884:1154212] server session: connected
2015-12-14 14:45:27.301 ThaliTest[884:1154212] server session: stateChange:1->2 Apple-Iphone5-1_PT3867
,2015-12-14 14:45:27.331 ThaliTest[884:1152893] server relay: connected (to port: 57316)
,2015-12-14T13:45:27.339Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:45:27.827Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-14T13:45:27.846Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-14T13:45:27.862Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T13:45:27.881Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-14T13:45:27.897Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T13:45:27.912Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:45:28.289 ThaliTest[884:1154200] server session: not connected Apple-Iphone5-1_PT3867
,teardown
,testSendData stopped
,2015-12-14 14:45:43.777 ThaliTest[884:1153290] jxcore: stopBroadcasting
,2015-12-14 14:45:43.779 ThaliTest[884:1153290] THEMultipeerSession stopping peer
2015-12-14 14:45:43.780 ThaliTest[884:1153290] multipeer session: stop timer
2015-12-14 14:45:43.780 ThaliTest[884:1153290] server session: disconnect
2015-12-14 14:45:43.781 ThaliTest[884:1153290] server session: stateChange:2->0 Apple-Iphone5s-1_PT4136
,2015-12-14 14:45:43.788 ThaliTest[884:1153290] server session: disconnect
2015-12-14 14:45:43.789 ThaliTest[884:1153290] server session: stateChange:2->0 Apple-IpadAir2-1_PT6041
2015-12-14 14:45:43.796 ThaliTest[884:1153290] server session: disconnect
2,015-12-14 14:45:43.796 ThaliTest[884:1153290] server session: stateChange:2->0 Apple-Iphone5-1_PT3867
2015-12-14 14:45:43.803 ThaliTest[884:1153290] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T13:45:43.822Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-14T13:45:43.823Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-14T13:45:43.825Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-14T13:45:43.825Z SendDataTCPServer.,js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
