#### Test 50650278e3ff7c2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0D91B6CE-D19A-4D35-98BB-F8C01D55358D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/0D91B6CE-D19A-4D35-98BB-F8C01D55358D/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e3ff7c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FBF2AEDB-5CB8-4B96-838C-CA8425D1F158/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55067"
,(lldb)     command script import "/tmp/0D91B6CE-D19A-4D35-98BB-F8C01D55358D/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-14 14:35:37.541 ThaliTest[739:1257821] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7395C914-D09E-4A0A-98A0-BE326DB81341/Library/Cookies/Cookies.binarycookies
,2015-12-14 14:35:37.698 ThaliTest[739:1257821] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-14 14:35:37.700 ThaliTest[739:1257821] Multi-tasking -> Device: YES, App: YES
,2015-12-14 14:35:37.707 ThaliTest[739:1257821] Unlimited access to network resources
,2015-12-14 14:35:37.722 ThaliTest[739:1257821] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-14 14:35:47.596 ThaliTest[739:1257821] Resetting plugins due to page load.
,2015-12-14 14:35:51.807 ThaliTest[739:1257821] Finished load of: file:///var/mobile/Containers/Bundle/Application/FBF2AEDB-5CB8-4B96-838C-CA8425D1F158/ThaliTest.app/www/index.html
,2015-12-14 14:35:52.026 ThaliTest[739:1257821] JXcore Cordova plugin initializing
,2015-12-14 14:35:52.028 ThaliTest[739:1258420] JXcore instance initializing
Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-14 14:35:54.480 ThaliTest[739:1257821] THREAD WARNING: ['JXcore'] took '153.968018' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-14 14:43:59.248 ThaliTest[739:1258420] jxcore: startBroadcasting
,2015-12-14 14:43:59.260 ThaliTest[739:1258420] server: starting Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:43:59.261 ThaliTest[739:1258420] multipeer session: start timer: 0x1dc928f0
2015-12-14 14:43:59.261 ThaliTest[739:1258420] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT3867
2015-12-14 14:43:59.262 ThaliTest[739:1258420] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-14 14:44:00.308 ThaliTest[739:1257821] client: found peer: Apple-IpadAir2-1_PT6041.yRvsxw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT6,041.yRvsxw==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-14 14:44:01.397 ThaliTest[739:1257821] client: found peer: Apple-Iphone6-1_PT4340.mBVNng==
,teardown
,testFindPeers stopped
,2015-12-14 14:44:02.273 ThaliTest[739:1258420] jxcore: stopBroadcasting
2015-12-14 14:44:02.274 ThaliTest[739:1258420] THEMultipeerSession stopping peer
2015-12-14 14:44:02.274 ThaliTest[739:1258420] multipeer session: stop timer
2015-12-14 14:44:02.274 ThaliTest[739:1258420] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57888
,2015-12-14 14:44:02.340 ThaliTest[739:1258420] jxcore: startBroadcasting
,2015-12-14 14:44:02.344 ThaliTest[739:1258420] server: starting Apple-Iphone5-1_PT3867.0mupng==
2015-12-14 14:44:02.345 ThaliTest[739:1258420] multipeer session: start timer: 0x1dbcb9b0
2015-12-14 14:44:02.346 ThaliTest[739:1258420] THEMultipeerSession initialized peer Apple-Iphone5-1_PT3867
2015-12-14 14:44:02.346 ThaliTest[739:1258420] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-14T13:44:02.350Z SendDataTCPServer.js: TCP/IP server is bound to port: 57888
,2015-12-14 14:44:02.817 ThaliTest[739:1257821] client: found peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:02.817 ThaliTest[739:1257821] client: found peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:02.818 ThaliTest[739:1257821] client: ,found peer: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:02.821Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:02.821Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:02.822Z SendDataConnector.js:, do connect now
2015-12-14 14:44:02.823 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:02.823 ThaliTest[739:1258420] client session: connect
,2015-12-14 14:44:02.824 ThaliTest[739:1258420] client session: stateChange:0->1 Apple-Iphone5-1_PT3867.cSCWVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:03.395 ThaliTest[739:1257821] client: lost peer: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.395 ThaliTest[739:1257821] client session: onPeerLost: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.395 ThaliTest[739:1257821] cl,ient session: onLinkFailure: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.396 ThaliTest[739:1257821] client session: disconnect
2015-12-14 14:44:03.396 ThaliTest[739:1257821] client session: stateChange:1->0 Apple-Iphone5-1_PT3867.cSCWVA==
2015-1,2-14 14:44:03.397 ThaliTest[739:1257821] client session: fireConnectCallback: Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:03.397 ThaliTest[739:1257821] jxcore: connect: fail: Peer disconnected
2015-12-14T13:44:03.398Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-14T13:44:03.398Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-14T13:44:03.398Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne5-1_PT3867.cSCWVA==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 14:44:04.070 ThaliTest[739:1257821] client: lost peer: Apple-IpadAir2-1_PT6041.yRvsxw==
2015-12-14 14:44:04.070 ThaliTest[739:1257821] client session: onPeerLost: Apple-IpadAir2-1_PT6041.yRvsxw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-IpadAir2-1_PT6041.yRvsxw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14 14:44:04.075 ThaliTest[739:1257821] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.nJo87Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-14 14:44:04.107 ThaliTest[739:1257821] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6041.byADbw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-12-14 14:44:04.178 ThaliTest[739:1257821] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4136.aZvv+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-12-14 14:44:07.661 ThaliTest[739:1257821] client: lost peer: Apple-Iphone6-1_PT4340.mBVNng==
2015-12-14 14:44:07.661 ThaliTest[739:1257821] client session: onPeerLost: Apple-Iphone6-1_PT4340.mBVNng==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.mBVNng==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-14T13:44:08.411Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:08.412Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:13.424 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:13.424 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:13.425Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:13.425Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:13.426Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
201,5-12-14T13:44:13.426Z SendDataConnector.js: do connect now
,2015-12-14 14:44:13.427 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:13.428 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:13.428 ThaliTest[739:1258420] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:13.428Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:13.428Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-14T13:44:13.429Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:18.432Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:18.433Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:23.438 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:23.439 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:23.440Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:23.440Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:23.440Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14T13:44:23.441Z SendDataConnector.js: do connect now
,2015-12-14 14:44:23.441 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:23.442 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:23.442 ThaliTest[739:1258420] jxco,re: connect: fail: Peer unreachable
2015-12-14T13:44:23.443Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:23.444Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:23.444Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:28.457Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:28.457Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:32.347 ThaliTest[739:1257821] multipeer session: restart
,2015-12-14 14:44:33.467 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:33.468 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:33.468Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:33.469Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:33.470Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
201,5-12-14T13:44:33.470Z SendDataConnector.js: do connect now
,2015-12-14 14:44:33.471 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:33.471 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:33.472 ThaliTest[739:1258420] jxco,re: connect: fail: Peer unreachable
2015-12-14T13:44:33.472Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:44:33.472Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:33.473Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:38.476Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:38.477Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14 14:44:43.486 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:43.487 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:43.487Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA=,=
2015-12-14T13:44:43.488Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT3867.cSCWVA== with availability status: true
2015-12-14T13:44:43.489Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3867.cSCWVA==
,2015-12-14T13:44:43.489Z SendDataConnector.js: do connect now
2015-12-14 14:44:43.490 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5-1_PT3867.cSCWVA==
2015-12-14 14:44:43.490 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone5-1_PT386,7.cSCWVA==
2015-12-14 14:44:43.490 ThaliTest[739:1258420] jxcore: connect: fail: Peer unreachable
,2015-12-14T13:44:43.491Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:43.491Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-14T13:44:43.493Z SendDataConnector.js: CLIENT Stop now
2015-12-14 14:44:43.493 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:43.493 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:43.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3867.cSCWVA==
---- round done--------
,startWithNextDevice
device[2]: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:43.495Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:43.495Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:44:43.496Z SendDataConnector.js: do connect now
,2015-12-14 14:44:43.496 ThaliTest[739:1258420] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:43.498 ThaliTest[739:1258420] client session: connect
,2015-12-14 14:44:43.499 ThaliTest[739:1258420] client session: stateChange:0->1 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:43.508 ThaliTest[739:1257821] client: lost peer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:43.508 ThaliTest[739:1257821] client session: onPeerLost: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:43.508 ThaliTest[739:1257821] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:43.508 ThaliTest[739:1257821] client session: disconnect
2015-12-14 14:44:43.509 ThaliTest[739:1257821] client session: stateChange:1->0 Apple-Iphone6-1_PT4340.nJo87Q==
2015-1,2-14 14:44:43.509 ThaliTest[739:1257821] client session: fireConnectCallback: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:43.509 ThaliTest[739:1257821] jxcore: connect: fail: Peer disconnected
,2015-12-14T13:44:43.515Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-14T13:44:43.516Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-14T13:44:43.516Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.nJo87Q==","peerName":"(null)","peerAvailable":false}]
,2015-12-14 14:44:44.023 ThaliTest[739:1257821] multipeer session: reset timer
2015-12-14 14:44:44.023 ThaliTest[739:1257821] multipeer session: stop timer
2015-12-14 14:44:44.024 ThaliTest[739:1257821] multipeer session: start timer: 0x1dbcb9b0
2015-12-14 14:44:44.024 ThaliTest[739:1257821] server session: connect
2015-12-14 14:44:44.024 ThaliTest[739:1257821] server session: stateChange:0->1 Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:44.030 ThaliTest[739:1257821] server: accepting invitation Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:46.980 ThaliTest[739:1259440] server session: connected
2015-12-14 14:44:46.981 ThaliTest[739:1259440] server session: stateChange:1->2 Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:47.034 ThaliTest[739:1257821] server relay: connected (to port: 57888)
,2015-12-14T13:44:47.041Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:47.446Z SendDataTCPServer.js: TCP/IP server has received 23806 bytes of data
,2015-12-14T13:44:47.463Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-14T13:44:47.480Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
,2015-12-14T13:44:47.497Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:47.564 ThaliTest[739:1259452] server session: not connected Apple-Iphone5s-1_PT4136
,2015-12-14 14:44:48.179 ThaliTest[739:1257821] multipeer session: reset timer
2015-12-14 14:44:48.179 ThaliTest[739:1257821] multipeer session: stop timer
2015-12-14 14:44:48.179 ThaliTest[739:1257821] multipeer session: start timer: 0x1dbcb9b0
2015-12-14 14:44:48.179 ThaliTest[739:1257821] server session: connect
2015-12-14 14:44:48.179 ThaliTest[739:1257821] server session: stateChange:0->1 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:48.186 ThaliTest[739:1257821] server: accepting invitation Apple-Iphone6-1_PT4340
,2015-12-14T13:44:48.520Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:44:48.521Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:44:50.052 ThaliTest[739:1257821] multipeer session: reset timer
2015-12-14 14:44:50.052 ThaliTest[739:1257821] multipeer session: stop timer
2015-12-14 14:44:50.053 ThaliTest[739:1257821] multipeer session: start timer: 0x1dbcb9b0
2015-12-14 14:44:50.053 ThaliTest[739:1257821] server session: connect
2015-12-14 14:44:50.053 ThaliTest[739:1257821] server session: stateChange:0->1 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:50.061 ThaliTest[739:1257821] server: accepting invitation Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:50.913 ThaliTest[739:1259442] server session: connected
2015-12-14 14:44:50.914 ThaliTest[739:1259442] server session: stateChange:1->2 Apple-Iphone6-1_PT4340
,2015-12-14 14:44:50.956 ThaliTest[739:1257821] server relay: connected (to port: 57888)
,2015-12-14T13:44:50.968Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:51.230Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-14T13:44:51.245Z SendDataTCPServer.js: TCP/IP server has received 21616 bytes of data
,2015-12-14T13:44:51.261Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-14T13:44:51.278Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-14T13:44:51.294Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:51.334 ThaliTest[739:1259442] server session: not connected Apple-Iphone6-1_PT4340
,2015-12-14 14:44:52.994 ThaliTest[739:1259442] server session: connected
2015-12-14 14:44:52.995 ThaliTest[739:1259442] server session: stateChange:1->2 Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:53.004 ThaliTest[739:1257821] server relay: connected (to port: 57888)
,2015-12-14T13:44:53.006Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-14T13:44:53.292Z SendDataTCPServer.js: TCP/IP server has received 23664 bytes of data
,2015-12-14T13:44:53.308Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-14T13:44:53.328Z SendDataTCPServer.js: TCP/IP server has received 84984 bytes of data
,2015-12-14T13:44:53.345Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-14 14:44:53.388 ThaliTest[739:1259442] server session: not connected Apple-IpadAir2-1_PT6041
,2015-12-14 14:44:53.530 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:44:53.531 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:44:53.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q=,=
2015-12-14T13:44:53.532Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4340.nJo87Q== with availability status: true
2015-12-14T13:44:53.532Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:44:53.533Z SendDataConnector.js: do connect now
,2015-12-14 14:44:53.534 ThaliTest[739:1258420] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:53.535 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:44:53.536 ThaliTest[739:1258420] jxco,re: connect: fail: Peer unreachable
2015-12-14T13:44:53.536Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:44:53.536Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:44:53.536Z SendDataCo,nnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:44:58.549Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:44:58.550Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:03.555 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:03.555 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:45:03.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q=,=
2015-12-14T13:45:03.556Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4340.nJo87Q== with availability status: true
2015-12-14T13:45:03.557Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
201,5-12-14T13:45:03.557Z SendDataConnector.js: do connect now
,2015-12-14 14:45:03.558 ThaliTest[739:1258420] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:03.558 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:03.559 ThaliTest[739:1258420] jxcore: connect: fail: Peer unreachable
2015-12-14T13:45:03.559Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-14T13:45:03.560Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:45:03.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:45:08.573Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:45:08.573Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:13.585 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:13.585 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:45:13.586Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q=,=
2015-12-14T13:45:13.586Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4340.nJo87Q== with availability status: true
2015-12-14T13:45:13.587Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:45:13.587Z SendDataConnector.js: do connect now
,2015-12-14 14:45:13.588 ThaliTest[739:1258420] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:13.589 ThaliTest[739:1258420] client: connect: unreachable Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:13.589 ThaliTest[739:1258420] jxco,re: connect: fail: Peer unreachable
,2015-12-14T13:45:13.589Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-14T13:45:13.589Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-14T13:45:13.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-14T13:45:18.591Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14T13:45:18.592Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:20.054 ThaliTest[739:1257821] multipeer session: restart
,2015-12-14 14:45:20.084 ThaliTest[739:1257821] client: found peer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:20.084 ThaliTest[739:1257821] client: found peer: Apple-Iphone6-1_PT4340.nJo87Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4340.nJo87Q==","peerName":"(null)","peerAvailable":true}]
2015-12-14 14:45:20.085 ThaliTest[739:1257821] client: found peer: Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:23.594 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:23.594 ThaliTest[739:1258420] jxcore: disconnect: fail
2015-12-14T13:45:23.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14T13:45:23.595Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4340.nJo87Q== with availability status: true
2015-12-14T13:45:23.595Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4340.nJo87Q==
201,5-12-14T13:45:23.596Z SendDataConnector.js: do connect now
,2015-12-14 14:45:23.597 ThaliTest[739:1258420] jxcore: connect Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:23.597 ThaliTest[739:1258420] client session: connect
2015-12-14 14:45:23.597 ThaliTest[739:1258420] client session: stateChange:0->1 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:27.316 ThaliTest[739:1259569] client session: connected
2015-12-14 14:45:27.317 ThaliTest[739:1259569] client session: stateChange:1->2 Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:27.319 ThaliTest[739:1259569] client session: fireCo,nnectCallback: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:27.320 ThaliTest[739:1259569] jxcore: connect: success
2015-12-14T13:45:27.320Z SendDataConnector.js: CLIENT connected to 57903, error: null
2015-12-14T13:45:27.320Z SendDataConnector.js: C,LIENT starting client 
2015-12-14 14:45:27.322 ThaliTest[739:1257821] client: relay established
2015-12-14 14:45:27.322 ThaliTest[739:1257821] client: new accepted socket: 0x1dcb29a0
,2015-12-14T13:45:27.336Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:45:27.860Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-14T13:45:27.925Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T13:45:27.940Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:45:27.942Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:45:27.942Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:45:27.943Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:45:27.944 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:27.944 ThaliTest[739:1258420] client session: disconnectFromPeer: Apple-Iphone6-1_PT4340.nJo87Q==
2015-12-14 14:45:27.945 ThaliTest[739:1258420] client session: disconnect,
2015-12-14 14:45:27.945 ThaliTest[739:1258420] client session: stateChange:2->0 Apple-Iphone6-1_PT4340.nJo87Q==
,2015-12-14 14:45:27.955 ThaliTest[739:1258420] jxcore: disconnect: success
2015-12-14T13:45:27.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4340.nJo87Q==
---- round done--------
startWithNextDevice
device[3]: Appl,e-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:45:27.959Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:45:27.959Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14T13:,45:27.959Z SendDataConnector.js: do connect now
2015-12-14 14:45:27.959 ThaliTest[739:1258420] jxcore: connect Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:27.960 ThaliTest[739:1258420] client session: connect
2015-12-14 14:45:27.960 ThaliTest[739:,1258420] client session: stateChange:0->1 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:45:38.434 ThaliTest[739:1259570] client session: connected
2015-12-14 14:45:38.434 ThaliTest[739:1259570] client session: stateChange:1->2 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:45:38.769 ThaliTest[739:1259617] client session: fireConnectCallback: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:38.769 ThaliTest[739:1259617] jxcore: connect: success
2015-12-14T13:45:38.770Z SendDataConnector.js: CLIENT connected to 57906, error: null
2015-12-14T13:45:38.770Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:45:38.773 ThaliTest[739:1257821] client: relay established
2015-12-14 14:45:38.773 ThaliTest[739:1257821] client: new accepted socket: 0x1dbde050
,2015-12-14T13:45:38.786Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:45:39.338Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T13:45:39.365Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:45:39.365Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:45:39.367Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:45:39.368Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:45:39.369 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:39.369 ThaliTest[739:1258420] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6041.byADbw==
2015-12-14 14:45:39.369 ThaliTest[739:1258420] client session: disconnect
2015-12-14 14:45:39.369 ThaliTest[739:1258420] client session: stateChange:2->0 Apple-IpadAir2-1_PT6041.byADbw==
,2015-12-14 14:45:39.378 ThaliTest[739:1258420] jxcore: disconnect: success
2015-12-14T13:45:39.378Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6041.byADbw==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:45:39.379Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13:45:39.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14T13,:45:39.379Z SendDataConnector.js: do connect now
2015-12-14 14:45:39.379 ThaliTest[739:1258420] jxcore: connect Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:45:39.380 ThaliTest[739:1258420] client session: connect
2015-12-14 14:45:39.380 ThaliTest[739,:1258420] client session: stateChange:0->1 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:42.517 ThaliTest[739:1259619] client session: connected
2015-12-14 14:45:42.517 ThaliTest[739:1259619] client session: stateChange:1->2 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:42.536 ThaliTest[739:1259613] client session: fireConnectCallback: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:45:42.537 ThaliTest[739:1259613] jxcore: connect: success
2015-12-14T13:45:42.537Z SendDataConnector.js: CLIENT connected to 57909, error: null
2015-12-14T13:45:42.538Z SendDataConnector.js: CLIENT starting client 
,2015-12-14 14:45:42.540 ThaliTest[739:1257821] client: relay established
2015-12-14 14:45:42.540 ThaliTest[739:1257821] client: new accepted socket: 0x1dcb2e70
,2015-12-14T13:45:42.553Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-14T13:45:43.101Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-14T13:45:43.115Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-14T13:45:43.129Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-14T13:45:43.169Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-14T13:45:43.231Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-14T13:45:43.232Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-14T13:45:43.234Z SendDataConnector.js: CLIENT Stop now
,2015-12-14T13:45:43.234Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-14 14:45:43.235 ThaliTest[739:1258420] jxcore: disconnect
2015-12-14 14:45:43.235 ThaliTest[739:1258420] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4136.aZvv+w==
2015-12-14 14:45:43.235 ThaliTest[739:1258420] client session: disconnect
2015-12-14 14:45:43.236 ThaliTest[739:1258420] client session: stateChange:2->0 Apple-Iphone5s-1_PT4136.aZvv+w==
,2015-12-14 14:45:43.244 ThaliTest[739:1258420] jxcore: disconnect: success
2015-12-14T13:45:43.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4136.aZvv+w==
---- round done--------
startWithNextDevice
weAreDoneNow, ,resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-14T13:45:43.249Z SendDataConnector.js: CLIENT Stop now
2015-12-14T13:45:43.249Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-14 14:45:43.924 ThaliTest[739:1258420] jxcore: stopBroadcasting
2015-12-14 14:45:43.925 ThaliTest[739:1258420] THEMultipeerSession stopping peer
2015-12-14 14:45:43.925 ThaliTest[739:1258420] multipeer session: stop timer
2015-12-14 14:45:43.925, ThaliTest[739:1258420] server session: disconnect
2015-12-14 14:45:43.926 ThaliTest[739:1258420] server session: stateChange:2->0 Apple-Iphone5s-1_PT4136
,2015-12-14 14:45:43.930 ThaliTest[739:1258420] server session: disconnect
,2015-12-14 14:45:43.930 ThaliTest[739:1258420] server session: stateChange:2->0 Apple-IpadAir2-1_PT6041
2015-12-14 14:45:43.934 ThaliTest[739:1258420] server session: disconnect
2015-12-14 14:45:43.935 ThaliTest[739:1258420] server session: stateChange:2->0 Apple-Iphone6-1_PT4340
,2015-12-14 14:45:43.945 ThaliTest[739:1258420] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-14T13:45:43.968Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:43.971Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:43.972Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-14T13:45:43.973Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
