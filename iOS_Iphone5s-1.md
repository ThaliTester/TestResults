#### Test 506502781a07ac8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/00D413C0-C4AF-403A-8E95-775AA983CF57/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/00D413C0-C4AF-403A-8E95-775AA983CF57/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/993A18AE-689F-4DCA-8DD3-D2A08CDE20B6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59797"
,(lldb)     command script import "/tmp/00D413C0-C4AF-403A-8E95-775AA983CF57/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 12:24:38.867 ThaliTest[408:330172] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9EED47A0-696E-438D-9349-27C78F47AEEE/Library/Cookies/Cookies.binarycookies
,2015-12-18 12:24:39.244 ThaliTest[408:330172] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 12:24:39.246 ThaliTest[408:330172] Multi-tasking -> Device: YES, App: YES
,2015-12-18 12:24:39.255 ThaliTest[408:330172] Unlimited access to network resources
,2015-12-18 12:24:39.268 ThaliTest[408:330172] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 12:24:48.334 ThaliTest[408:330172] Resetting plugins due to page load.
,2015-12-18 12:24:52.139 ThaliTest[408:330172] Finished load of: file:///var/mobile/Containers/Bundle/Application/993A18AE-689F-4DCA-8DD3-D2A08CDE20B6/ThaliTest.app/www/index.html
,2015-12-18 12:24:52.341 ThaliTest[408:330172] JXcore Cordova plugin initializing
,2015-12-18 12:24:52.343 ThaliTest[408:330365] JXcore instance initializing
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
,2015-12-18 12:24:53.669 ThaliTest[408:330172] THREAD WARNING: ['JXcore'] took '89.286133' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 12:31:21.330 ThaliTest[408:330365] jxcore: startBroadcasting
,2015-12-18 12:31:21.351 ThaliTest[408:330365] server: starting Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:31:21.354 ThaliTest[408:330365] multipeer session: start timer: 0x163d7b90
2015-12-18 12:31:21.355 ThaliTest[408:330365] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8285
2015-12-18 12:31:21.356 ThaliTest[408:330365] jxcore: star,tBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 12:31:22.439 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:22.443 ThaliTest[408:330172] client: found peer: Apple-Iphone5-1_PT6300.vmgLvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT6115.H3bAHA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2015-12-18 12:31:24.173 ThaliTest[408:330172] client: lost peer: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:24.174 ThaliTest[408:330172] client session: onPeerLost: Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:25.190 ThaliTest[408:330172] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:31:25.477 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:31:25.902 ThaliTest[408:330172] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:31:27.491 ThaliTest[408:330172] client: lost peer: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:27.492 ThaliTest[408:330172] client session: onPeerLost: Apple-IpadAir2-1_PT6115.H3bAHA==
,teardown
,testFindPeers stopped
,2015-12-18 12:31:29.289 ThaliTest[408:330365] jxcore: stopBroadcasting
2015-12-18 12:31:29.290 ThaliTest[408:330365] THEMultipeerSession stopping peer
2015-12-18 12:31:29.290 ThaliTest[408:330365] multipeer session: stop timer
2015-12-18 12:31:29.291 Th,aliTest[408:330365] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50746
,2015-12-18 12:31:29.401 ThaliTest[408:330365] jxcore: startBroadcasting
,2015-12-18 12:31:29.405 ThaliTest[408:330365] server: starting Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:31:29.407 ThaliTest[408:330365] multipeer session: start timer: 0x16476f00
,2015-12-18 12:31:29.417 ThaliTest[408:330365] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT8285
,2015-12-18 12:31:29.421 ThaliTest[408:330365] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 12:31:29.429 ThaliTest[408:330172] client: found peer: Apple-Iphone5s-1_PT8285.POBncQ==
,null
,2015-12-18T11:31:29.432Z SendDataTCPServer.js: TCP/IP server is bound to port: 50746
,2015-12-18 12:31:29.433 ThaliTest[408:330172] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:31:29.434 ThaliTest[408:330172] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:31:29.435 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:29.445Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:29.446Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:29.446Z SendDataConnector.js: do connect now
,2015-12-18 12:31:29.447 ThaliTest[408:330365] jxcore: connect Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:31:29.448 ThaliTest[408:330365] client session: connect
,2015-12-18 12:31:29.448 ThaliTest[408:330365] client session: stateChange:0->1 Apple-Iphone5s-1_PT8285.POBncQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 12:31:30.426 ThaliTest[408:330172] client: lost peer: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.427 ThaliTest[408:330172] client session: onPeerLost: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.427 ThaliTest[408:330172] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.428 ThaliTest[408:330172] client session: disconnect
2015-12-18 12:31:30.429 ThaliTest[408:330172] client session: stateChange:1->0 Apple-Iphone5s-1_PT8285.POBncQ==
2015-12,-18 12:31:30.430 ThaliTest[408:330172] client session: fireConnectCallback: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.430 ThaliTest[408:330172] jxcore: connect: fail: Peer disconnected
2015-12-18T11:31:30.432Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-18T11:31:30.432Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-18T11:31:30.433Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-18T11:31:35.444Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:35.445Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:31:40.059 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:40.452 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:31:40.452 ThaliTest[408:330365] jxcore: disconnect: fail
2015-12-18T11:31:40.453Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.POBncQ==,
2015-12-18T11:31:40.454Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT8285.POBncQ== with availability status: true
2015-12-18T11:31:40.454Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:40.454Z SendDataConnector.js: do connect now
,2015-12-18 12:31:40.456 ThaliTest[408:330365] jxcore: connect Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:40.457 ThaliTest[408:330365] client: connect: unreachable Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:40.457 ThaliTest[408:330365] jxcor,e: connect: fail: Peer unreachable
2015-12-18T11:31:40.458Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:40.458Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:40.459Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:45.460Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:45.461Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:31:46.118 ThaliTest[408:330172] client: lost peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-18 12:31:46.118 ThaliTest[408:330172] client session: onPeerLost: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:50.467 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:31:50.467 ThaliTest[408:330365] jxcore: disconnect: fail
2015-12-18T11:31:50.468Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.POBncQ==,
2015-12-18T11:31:50.468Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT8285.POBncQ== with availability status: true
2015-12-18T11:31:50.469Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.POBncQ==
20,15-12-18T11:31:50.469Z SendDataConnector.js: do connect now
,2015-12-18 12:31:50.470 ThaliTest[408:330365] jxcore: connect Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:50.471 ThaliTest[408:330365] client: connect: unreachable Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:50.471 ThaliTest[408:330365] jxcor,e: connect: fail: Peer unreachable
2015-12-18T11:31:50.472Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:31:50.472Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:31:50.473Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:55.476Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:31:55.476Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:31:59.415 ThaliTest[408:330172] multipeer session: restart
,2015-12-18 12:31:59.478 ThaliTest[408:330172] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:31:59.478 ThaliTest[408:330172] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:31:59.480 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:00.480 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:32:00.481 ThaliTest[408:330365] jxcore: disconnect: fail
2015-12-18T11:32:00.481Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.POBncQ==,
2015-12-18T11:32:00.482Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT8285.POBncQ== with availability status: true
2015-12-18T11:32:00.482Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:32:00.482Z SendDataConnector.js: do connect now
2015-12-18 12:32:00.483 ThaliTest[408:330365] jxcore: connect Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:32:00.484 ThaliTest[408:330365] client: connect: unreachable Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:32:00.485 ThaliTest[408:330365] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:32:00.486Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T11:32:00.486Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-18T11:32:00.487Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:05.496Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18T11:32:05.496Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT8285.POBncQ==
,2015-12-18 12:32:10.499 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:32:10.499 ThaliTest[408:330365] jxcore: disconnect: fail
2015-12-18T11:32:10.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.POBncQ==,
2015-12-18T11:32:10.500Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT8285.POBncQ== with availability status: true
2015-12-18T11:32:10.500Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18T11:32:10.500Z SendDataConnector.js: do connect now
,2015-12-18 12:32:10.500 ThaliTest[408:330365] jxcore: connect Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:32:10.501 ThaliTest[408:330365] client: connect: unreachable Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:32:10.501 ThaliTest[408:330365] jxcore: connect: fail: Peer unreachable
2015-12-18T11:32:10.502Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-18T11:32:10.502Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-18T11:32:10.503Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 12:32:10.503 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:32:10.504 ThaliTest[408:330365] jxcore: disconnect: fail
2015-12-18T11:32:10.504Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.POBncQ==
---- round done--------
,startWithNextDevice
device[2]: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:10.506Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18T11:32:10.506Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:10.506Z SendDataConnector.js: do connect now
,2015-12-18 12:32:10.507 ThaliTest[408:330365] jxcore: connect Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:10.507 ThaliTest[408:330365] client session: connect
2015-12-18 12:32:10.507 ThaliTest[408:330365] client session: stateChange:0->1 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:12.296 ThaliTest[408:330172] multipeer session: reset timer
2015-12-18 12:32:12.296 ThaliTest[408:330172] multipeer session: stop timer
2015-12-18 12:32:12.297 ThaliTest[408:330172] multipeer session: start timer: 0x16476f00
2015-12-18 ,12:32:12.297 ThaliTest[408:330172] server session: connect
2015-12-18 12:32:12.298 ThaliTest[408:330172] server session: stateChange:0->1 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:12.310 ThaliTest[408:330172] server: accepting invitation Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:13.932 ThaliTest[408:331282] client session: connected
2015-12-18 12:32:13.933 ThaliTest[408:331282] client session: stateChange:1->2 Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:13.937 ThaliTest[408:331282] client session: fireConne,ctCallback: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:13.938 ThaliTest[408:331282] jxcore: connect: success
2015-12-18T11:32:13.939Z SendDataConnector.js: CLIENT connected to 50760, error: null
2015-12-18T11:32:13.940Z SendDataConnector.js: CLIEN,T starting client 
,2015-12-18 12:32:13.948 ThaliTest[408:330172] client: relay established
,2015-12-18 12:32:13.950 ThaliTest[408:330172] client: new accepted socket: 0x163f0aa0
,2015-12-18T11:32:13.962Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:14.726Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T11:32:14.726Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:14.728Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:14.728Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:14.731 ThaliTest[408:330365] jxcore: disconnect
2015-12-18 12:32:14.732 ThaliTest[408:330365] client session: disconnectFromPeer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:14.732 ThaliTest[408:330365] client session: disconnect
2015-12-18 12:32:14.732 ThaliTest[408:330365] client session: stateChange:2->0 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:14.750 ThaliTest[408:330365] jxcore: disconnect: success
,2015-12-18T11:32:14.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.t11aeg==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:14.768Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:14.768Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:14.770Z SendDataConnector.js: do connect now
,2015-12-18 12:32:14.772 ThaliTest[408:330365] jxcore: connect Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:14.773 ThaliTest[408:330365] client session: connect
,2015-12-18 12:32:14.774 ThaliTest[408:330365] client session: stateChange:0->1 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:15.184 ThaliTest[408:330172] multipeer session: reset timer
2015-12-18 12:32:15.186 ThaliTest[408:330172] multipeer session: stop timer
2015-12-18 12:32:15.187 ThaliTest[408:330172] multipeer session: start timer: 0x16476f00
,2015-12-18 12:32:15.188 ThaliTest[408:330172] server session: connect
,2015-12-18 12:32:15.189 ThaliTest[408:330172] server session: stateChange:0->1 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:15.207 ThaliTest[408:330172] server: accepting invitation Apple-Iphone5-1_PT6300
,2015-12-18 12:32:15.327 ThaliTest[408:331108] server session: connected
,2015-12-18 12:32:15.328 ThaliTest[408:331108] server session: stateChange:1->2 Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:15.337 ThaliTest[408:330172] server relay: connected (to port: 50746)
,2015-12-18T11:32:15.344Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:15.779Z SendDataTCPServer.js: TCP/IP server has received 69632 bytes of data
,2015-12-18T11:32:15.795Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:15.840 ThaliTest[408:331282] server session: not connected Apple-IpadAir2-1_PT6115
,2015-12-18 12:32:17.939 ThaliTest[408:331282] server session: connected
2015-12-18 12:32:17.944 ThaliTest[408:331282] server session: stateChange:1->2 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:17.954 ThaliTest[408:330172] server relay: connected (to port: 50746)
,2015-12-18T11:32:17.961Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 12:32:18.152 ThaliTest[408:331107] client session: connected
2015-12-18 12:32:18.152 ThaliTest[408:331107] client session: stateChange:1->2 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:18.156 ThaliTest[408:331107] client session: fireConnectCallback: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:18.156 ThaliTest[408:331107] jxcore: connect: success
,2015-12-18T11:32:18.158Z SendDataConnector.js: CLIENT connected to 50765, error: null
2015-12-18T11:32:18.159Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:18.166 ThaliTest[408:330172] client: relay established
2015-12-18 12:32:18.167 ThaliTest[408:330172] client: new accepted socket: 0x164941f0
,2015-12-18T11:32:18.177Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:18.471Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-18T11:32:18.488Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T11:32:18.501Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T11:32:18.501Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-18T11:32:18.519Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T11:32:18.537Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T11:32:18.561Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T11:32:18.612Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:18.613Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T11:32:18.613Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:18.613Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:18.614 ThaliTest[408:330365] jxcore: disconnect
,2015-12-18 12:32:18.615 ThaliTest[408:330365] client session: disconnectFromPeer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:18.615 ThaliTest[408:330365] client session: disconnect
,2015-12-18 12:32:18.615 ThaliTest[408:330365] client session: stateChange:2->0 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:18.640 ThaliTest[408:331107] server session: not connected Apple-Iphone5-1_PT6300
,2015-12-18 12:32:18.684 ThaliTest[408:330365] jxcore: disconnect: success
,2015-12-18T11:32:18.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3077.TwkGOQ==
---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:18.686Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:18.686Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18T11:32:18.686Z SendDataConnector.js: do connect now
,2015-12-18 12:32:18.687 ThaliTest[408:330365] jxcore: connect Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:18.688 ThaliTest[408:330365] client session: connect
,2015-12-18 12:32:18.688 ThaliTest[408:330365] client session: stateChange:0->1 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:21.870 ThaliTest[408:331021] client session: connected
2015-12-18 12:32:21.871 ThaliTest[408:331021] client session: stateChange:1->2 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:21.884 ThaliTest[408:331282] client session: fireConnectCallback: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:21.884 ThaliTest[408:331282] jxcore: connect: success
2015-12-18T11:32:21.886Z SendDataConnector.js: CLIENT connected to 50771, error: null
2015-12-18T11:32:21.886Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:21.891 ThaliTest[408:330172] client: relay established
2015-12-18 12:32:21.891 ThaliTest[408:330172] client: new accepted socket: 0x163fb410
,2015-12-18T11:32:21.904Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:22.233Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:22.248Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T11:32:22.259Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T11:32:22.271Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:22.271Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T11:32:22.272Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:22.272Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:22.272 ThaliTest[408:330365] jxcore: disconnect
,2015-12-18 12:32:22.273 ThaliTest[408:330365] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:22.274 ThaliTest[408:330365] client session: disconnect
,2015-12-18 12:32:22.274 ThaliTest[408:330365] client session: stateChange:2->0 Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:32:22.344 ThaliTest[408:330365] jxcore: disconnect: success
,2015-12-18T11:32:22.344Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6115.GXbC4w==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-18T11:32:22.348Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:22.348Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:34.450 ThaliTest[408:330172] client: lost peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:34.451 ThaliTest[408:330172] client session: onPeerLost: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:34.452 ThaliTest[408:330172] clien,t: lost peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:34.452 ThaliTest[408:330172] client session: onPeerLost: Apple-IpadAir2-1_PT6115.GXbC4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","pe,erAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 12:32:40.572 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.GXbC4w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 12:32:44.418 ThaliTest[408:330172] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 12:32:45.189 ThaliTest[408:330172] multipeer session: restart
,2015-12-18 12:32:45.267 ThaliTest[408:330172] client: found peer: Apple-IpadAir2-1_PT6115.GXbC4w==
2015-12-18 12:32:45.268 ThaliTest[408:330172] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:45.279 ThaliTest[408:330172] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:53.050 ThaliTest[408:330172] multipeer session: reset timer
2015-12-18 12:32:53.050 ThaliTest[408:330172] multipeer session: stop timer
2015-12-18 12:32:53.051 ThaliTest[408:330172] multipeer session: start timer: 0x16476f00
2015-12-18 ,12:32:53.051 ThaliTest[408:330172] server session: connect
2015-12-18 12:32:53.052 ThaliTest[408:330172] server session: stateChange:0->1 Apple-Iphone6-1_PT3077
2015-12-18 12:32:53.060 ThaliTest[408:330172] server: accepting invitation Apple-Iphone6-1_PT,3077
,2015-12-18 12:32:55.686 ThaliTest[408:331671] server session: connected
2015-12-18 12:32:55.687 ThaliTest[408:331671] server session: stateChange:1->2 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:55.702 ThaliTest[408:330172] server relay: connected (to port: 50746)
2015-12-18T11:32:55.705Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:55.959Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-18T11:32:55.975Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-18T11:32:55.990Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T11:32:56.008Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-18T11:32:56.026Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-18T11:32:56.045Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-18T11:32:56.064Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-18T11:32:56.080Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:56.126 ThaliTest[408:331645] server session: not connected Apple-Iphone6-1_PT3077
,2015-12-18 12:32:58.203 ThaliTest[408:330172] client: lost peer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:58.203 ThaliTest[408:330172] client session: onPeerLost: Apple-Iphone5-1_PT6300.t11aeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
,2015-12-18 12:32:58.479 ThaliTest[408:330365] jxcore: stopBroadcasting
2015-12-18 12:32:58.481 ThaliTest[408:330365] THEMultipeerSession stopping peer
2015-12-18 12:32:58.481 ThaliTest[408:330365] multipeer session: stop timer
2015-12-18 12:32:58.482 Th,aliTest[408:330365] server session: disconnect
2015-12-18 12:32:58.482 ThaliTest[408:330365] server session: stateChange:2->0 Apple-Iphone6-1_PT3077
2015-12-18 12:32:58.490 ThaliTest[408:330365] server session: disconnect
2015-12-18 12:32:58.490 ThaliTe,st[408:330365] server session: stateChange:2->0 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:58.508 ThaliTest[408:330365] server session: disconnect
2015-12-18 12:32:58.509 ThaliTest[408:330365] server session: stateChange:2->0 Apple-IpadAir2-1_PT6115
2015-12-18 12:32:58.519 ThaliTest[408:330365] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-18T11:32:58.556Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:58.560Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:58.564Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:58.565Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
