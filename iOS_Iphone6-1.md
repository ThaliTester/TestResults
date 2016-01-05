#### Test 550731521dbc378_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BE1A278D-70EF-4C48-8F40-A24C41C4559B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BE1A278D-70EF-4C48-8F40-A24C41C4559B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9AD641B6-49BD-4780-9CCE-DB3D7CBB1921/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64909"
,(lldb)     command script import "/tmp/BE1A278D-70EF-4C48-8F40-A24C41C4559B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 11:17:20.152 ThaliTest[1298:2784202] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/15A3FF69-D770-4F5A-AD9F-AF42FD8E674E/Library/Cookies/Cookies.binarycookies
,2016-01-05 11:17:20.483 ThaliTest[1298:2784202] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 11:17:20.484 ThaliTest[1298:2784202] Multi-tasking -> Device: YES, App: YES
,2016-01-05 11:17:20.493 ThaliTest[1298:2784202] Unlimited access to network resources
,2016-01-05 11:17:20.502 ThaliTest[1298:2784202] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 11:17:29.489 ThaliTest[1298:2784202] Resetting plugins due to page load.
,2016-01-05 11:17:33.083 ThaliTest[1298:2784202] Finished load of: file:///var/mobile/Containers/Bundle/Application/9AD641B6-49BD-4780-9CCE-DB3D7CBB1921/ThaliTest.app/www/index.html
,2016-01-05 11:17:33.268 ThaliTest[1298:2784202] JXcore Cordova plugin initializing
,2016-01-05 11:17:33.270 ThaliTest[1298:2784400] JXcore instance initializing
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
,2016-01-05 11:17:34.374 ThaliTest[1298:2784202] THREAD WARNING: ['JXcore'] took '81.146240' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 11:23:09.684 ThaliTest[1298:2784400] jxcore: startBroadcasting
,2016-01-05 11:23:09.702 ThaliTest[1298:2784400] server: starting Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:09.704 ThaliTest[1298:2784400] multipeer session: start timer: 0x19487170
2016-01-05 11:23:09.704 ThaliTest[1298:2784400] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-05 11:23:09.705 ThaliTest[1298:2784400] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 11:23:11.923 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1.Jzs4Xw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-05 11:23:12.024 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5-1.+hwmKw==
,teardown
,testFindPeers stopped
2016-01-05 11:23:12.231 ThaliTest[1298:2784400] jxcore: stopBroadcasting
,2016-01-05 11:23:12.231 ThaliTest[1298:2784400] THEMultipeerSession stopping peer
2016-01-05 11:23:12.232 ThaliTest[1298:2784400] multipeer session: stop timer
2016-01-05 11:23:12.233 ThaliTest[1298:2784400] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63037
,2016-01-05 11:23:12.325 ThaliTest[1298:2784400] jxcore: startBroadcasting
,2016-01-05 11:23:12.328 ThaliTest[1298:2784400] server: starting Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:23:12.331 ThaliTest[1298:2784400] multipeer session: start timer: 0x193f2520
2016-01-05 11:23:12.334 ThaliTest[1298:2784400] THEMultipeerSession initialized peer Apple-Iphone6-1
,2016-01-05 11:23:12.335 ThaliTest[1298:2784400] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 11:23:12.345 ThaliTest[1298:2784202] client: found peer: Apple-Iphone6-1.1MqlgA==
null
2016-01-05T10:23:12.346Z SendDataTCPServer.js: TCP/IP server is bound to port: 63037
2016-01-05 11:23:12.346 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:12.347 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.1MqlgA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:12.354Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:12.355Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:12.356Z SendDataConnector.js: do connect now
,2016-01-05 11:23:12.356 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:12.357 ThaliTest[1298:2784400] client session: connect
,2016-01-05 11:23:12.357 ThaliTest[1298:2784400] client session: stateChange:0->1 Apple-Iphone6-1.1MqlgA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:13.360 ThaliTest[1298:2784202] client: lost peer: Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:13.361 ThaliTest[1298:2784202] client session: onPeerLost: Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:13.361 ThaliTest[1298:2784202] client sessio,n: onLinkFailure: Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:13.361 ThaliTest[1298:2784202] client session: disconnect
,2016-01-05 11:23:13.362 ThaliTest[1298:2784202] client session: stateChange:1->0 Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:13.362 ThaliTest[1298:2784202] client session: fireConnectCallback: Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:13.363 ThaliTest[1298:2784202] jxcore: connect: fail: Peer disconnected
2016-01-05T10:23:13.365Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-05T10:23:13.365Z SendDataConnector.js: CLIENT Can not Connect:, Peer disconnected
2016-01-05T10:23:13.366Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.1MqlgA==","peerName":"(null)","peerAvailable":false}]
,2016-01-05 11:23:13.737 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5-1.GgrI3w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.GgrI3w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:14.750 ThaliTest[1298:2784202] client: lost peer: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.751 ThaliTest[1298:2784202] client session: onPeerLost: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.751 ThaliTest[1298:2784202] client: found peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:14.752 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.C4KP1Q==","peerName":"(null)","peerAvail,able":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.R3Z2qA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 11:23:15.737 ThaliTest[1298:2784202] client: lost peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:15.738 ThaliTest[1298:2784202] client session: onPeerLost: Apple-Iphone5-1.+hwmKw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05T10:23:18.373Z SendDataConnector.js: re-try now : Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:18.373Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:23.377 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:23.378 ThaliTest[1298:2784400] jxcore: disconnect: fail
2016-01-05T10:23:23.379Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.1MqlgA==
20,16-01-05T10:23:23.379Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.1MqlgA== with availability status: true
2016-01-05T10:23:23.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.1MqlgA==
2016-01-05T10:23:23.380Z SendDataConnector.js: do connect now
,2016-01-05 11:23:23.381 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:23.382 ThaliTest[1298:2784400] client: connect: unreachable Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:23.382 ThaliTest[1298:2784400] jxcore: connect: fail: Peer unreachable
2016-01-05T10:23:23.383Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:23.384Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:23.384Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:28.391Z SendDataConnector.js: re-try now : Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:28.391Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:33.401 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:33.401 ThaliTest[1298:2784400] jxcore: disconnect: fail
2016-01-05T10:23:33.402Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.1MqlgA==
20,16-01-05T10:23:33.402Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.1MqlgA== with availability status: true
2016-01-05T10:23:33.402Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.1MqlgA==
2016-01-05T10:23:33.403Z SendDataConnector.js: do connect now
,2016-01-05 11:23:33.403 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:33.404 ThaliTest[1298:2784400] client: connect: unreachable Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:33.406 ThaliTest[1298:2784400] jxcore: connect: fail: Peer unreachable
2016-01-05T10:23:33.406Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:33.407Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2016-01-05T10:23:33.407Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:38.420Z SendDataConnector.js: re-try now : Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:38.420Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:42.345 ThaliTest[1298:2784202] multipeer session: restart
,2016-01-05 11:23:42.391 ThaliTest[1298:2784202] client: found peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:42.393 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:42.393 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:23:43.430 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:43.430 ThaliTest[1298:2784400] jxcore: disconnect: fail
2016-01-05T10:23:43.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.1MqlgA==
20,16-01-05T10:23:43.431Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.1MqlgA== with availability status: true
2016-01-05T10:23:43.432Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:43.432Z SendDataConnector.js: do connect now
2016-01-05 11:23:43.433 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:43.433 ThaliTest[1298:2784400] client: connect: unreachable Apple-Iphone6-1.1MqlgA==
2016-01-05 11:23:43.434 ThaliTest[1298:2784400] jxcore: connect: fail: Peer unreachable
2016-01-05T10:23:43.435Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-05T10:23:43.435Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:43.435Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:48.447Z SendDataConnector.js: re-try now : Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:48.448Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:53.449 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:53.450 ThaliTest[1298:2784400] jxcore: disconnect: fail
2016-01-05T10:23:53.450Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.1MqlgA==
20,16-01-05T10:23:53.450Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.1MqlgA== with availability status: true
2016-01-05T10:23:53.451Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.1MqlgA==
,2016-01-05T10:23:53.451Z SendDataConnector.js: do connect now
,2016-01-05 11:23:53.452 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:53.453 ThaliTest[1298:2784400] client: connect: unreachable Apple-Iphone6-1.1MqlgA==
,2016-01-05 11:23:53.454 ThaliTest[1298:2784400] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:53.454Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:53.455Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-05T10:23:53.457Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 11:23:53.458 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:53.458 ThaliTest[1298:2784400] jxcore: disconnect: fail
2016-01-05T10:23:53.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.1MqlgA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:53.462Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:53.463Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.GgrI3w==
,2016-01-05T10:23:53.463Z SendDataConnector.js: do connect now
,2016-01-05 11:23:53.465 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:53.465 ThaliTest[1298:2784400] client session: connect
2016-01-05 11:23:53.465 ThaliTest[1298:2784400] client session: stateChange:0->1 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:23:56.267 ThaliTest[1298:2785070] client session: connected
2016-01-05 11:23:56.267 ThaliTest[1298:2785070] client session: stateChange:1->2 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:23:56.317 ThaliTest[1298:2785097] client session: fireConnectCallback: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:56.317 ThaliTest[1298:2785097] jxcore: connect: success
2016-01-05T10:23:56.320Z SendDataConnector.js: CLIENT connected to 63044, error: null
2016-01-05T10:23:56.320Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:23:56.326 ThaliTest[1298:2784202] client: relay established
2016-01-05 11:23:56.326 ThaliTest[1298:2784202] client: new accepted socket: 0x1949cc60
,2016-01-05T10:23:56.341Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:23:56.774Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:23:56.774Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-05T10:23:56.775Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:23:56.775Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:23:56.776 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:23:56.776 ThaliTest[1298:2784400] client session: disconnectFromPeer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:56.776 ThaliTest[1298:2784400] client session: disconnect
2016-01-05 11:23:56.776 ThaliTest[1298:2784400] client session: stateChange:2->0 Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:23:56.840 ThaliTest[1298:2784400] jxcore: disconnect: success
2016-01-05T10:23:56.840Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.GgrI3w==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:23:56.841Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:56.841Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
,2016-01-05T10:23:56.841Z SendDataConnector.js: do connect now
,2016-01-05 11:23:56.841 ThaliTest[1298:2784400] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:56.842 ThaliTest[1298:2784400] client session: connect
2016-01-05 11:23:56.842 ThaliTest[1298:2784400] client session: stateChange:0->1 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:58.695 ThaliTest[1298:2784202] multipeer session: reset timer
2016-01-05 11:23:58.696 ThaliTest[1298:2784202] multipeer session: stop timer
2016-01-05 11:23:58.696 ThaliTest[1298:2784202] multipeer session: start timer: 0x193f2520
2016-,01-05 11:23:58.697 ThaliTest[1298:2784202] server session: connect
2016-01-05 11:23:58.697 ThaliTest[1298:2784202] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 11:23:58.708 ThaliTest[1298:2784202] server: accepting invitation Apple-Iphone5-1
,2016-01-05 11:23:58.750 ThaliTest[1298:2784202] multipeer session: reset timer
2016-01-05 11:23:58.750 ThaliTest[1298:2784202] multipeer session: stop timer
2016-01-05 11:23:58.751 ThaliTest[1298:2784202] multipeer session: start timer: 0x193f2520
2016-01-05 11:23:58.751 ThaliTest[1298:2784202] server session: connect
2016-01-05 11:23:58.752 ThaliTest[1298:2784202] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 11:23:58.773 ThaliTest[1298:2784202] server: accepting invitation Apple-IpadAir2-1
,2016-01-05 11:24:00.332 ThaliTest[1298:2785097] client session: connected
,2016-01-05 11:24:00.332 ThaliTest[1298:2785097] client session: stateChange:1->2 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:00.340 ThaliTest[1298:2785097] client session: fireConnectCallback: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:00.340 ThaliTest[1298:2785097] jxcore: connect: success
,2016-01-05T10:24:00.343Z SendDataConnector.js: CLIENT connected to 63047, error: null
,2016-01-05T10:24:00.343Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:00.347 ThaliTest[1298:2784202] client: relay established
2016-01-05 11:24:00.347 ThaliTest[1298:2784202] client: new accepted socket: 0x194b8aa0
,2016-01-05T10:24:00.362Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:00.633Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T10:24:00.684Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T10:24:00.697Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T10:24:00.710Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:24:00.711Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T10:24:00.711Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:00.711Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:00.712 ThaliTest[1298:2784400] jxcore: disconnect
,2016-01-05 11:24:00.712 ThaliTest[1298:2784400] client session: disconnectFromPeer: Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:00.713 ThaliTest[1298:2784400] client session: disconnect
,2016-01-05 11:24:00.713 ThaliTest[1298:2784400] client session: stateChange:2->0 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:24:00.779 ThaliTest[1298:2784400] jxcore: disconnect: success
,2016-01-05T10:24:00.780Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:00.781Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:00.781Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:00.781Z SendDataConnector.js: do connect now
,2016-01-05 11:24:00.782 ThaliTest[1298:2784400] jxcore: connect Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:00.782 ThaliTest[1298:2784400] client session: connect
,2016-01-05 11:24:00.783 ThaliTest[1298:2784400] client session: stateChange:0->1 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:01.446 ThaliTest[1298:2785070] server session: connected
2016-01-05 11:24:01.447 ThaliTest[1298:2785070] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05 11:24:01.454 ThaliTest[1298:2784202] server relay: connected (to port: 63037)
,2016-01-05T10:24:01.459Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 11:24:01.902 ThaliTest[1298:2785106] server session: connected
2016-01-05 11:24:01.902 ThaliTest[1298:2785106] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 11:24:01.919 ThaliTest[1298:2784202] server relay: connected (to port: 63037)
,2016-01-05T10:24:01.930Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:01.969Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-05T10:24:01.984Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-05T10:24:01.999Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-05T10:24:02.027Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-05T10:24:02.042Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-05T10:24:02.061Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:02.130 ThaliTest[1298:2785084] server session: not connected Apple-Iphone5-1
,2016-01-05T10:24:02.203Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-05T10:24:02.230Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2016-01-05T10:24:02.245Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:02.300 ThaliTest[1298:2785070] server session: not connected Apple-IpadAir2-1
,2016-01-05 11:24:03.468 ThaliTest[1298:2785070] client session: connected
2016-01-05 11:24:03.468 ThaliTest[1298:2785070] client session: stateChange:1->2 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:03.514 ThaliTest[1298:2785106] client session: fireConnectCallback: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:03.515 ThaliTest[1298:2785106] jxcore: connect: success
2016-01-05T10:24:03.516Z SendDataConnector.js: CLIENT connected to 63052, error: null
2016-01-05T10:24:03.516Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:03.520 ThaliTest[1298:2784202] client: relay established
2016-01-05 11:24:03.520 ThaliTest[1298:2784202] client: new accepted socket: 0x194a7800
,2016-01-05T10:24:03.530Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:03.850Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T10:24:03.861Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T10:24:03.924Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:24:03.925Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T10:24:03.925Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:03.925Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:03.926 ThaliTest[1298:2784400] jxcore: disconnect
2016-01-05 11:24:03.926 ThaliTest[1298:2784400] client session: disconnectFromPeer: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:03.926 ThaliTest[1298:2784400] client session: disconnect
2016-01-05 11:24:03.926 ThaliTest[1298:2784400] client session: stateChange:2->0 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:03.931 ThaliTest[1298:2784400] jxcore: disconnect: success
2016-01-05T10:24:03.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.R3Z2qA==
---- round done--------
startWithNextDevice
weAreDoneNow, result,Array.length: 4
sendReportNow
done, now sending data to server
,2016-01-05T10:24:03.934Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:03.934Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:28.752 ThaliTest[1298:2784202] multipeer session: restart
,2016-01-05 11:24:28.793 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5-1.GgrI3w==
,2016-01-05 11:24:29.096 ThaliTest[1298:2784202] client: found peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:29.097 ThaliTest[1298:2784202] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:45.330 ThaliTest[1298:2784202] multipeer session: reset timer
2016-01-05 11:24:45.330 ThaliTest[1298:2784202] multipeer session: stop timer
2016-01-05 11:24:45.330 ThaliTest[1298:2784202] multipeer session: start timer: 0x193f2520
2016-,01-05 11:24:45.331 ThaliTest[1298:2784202] server session: connect
2016-01-05 11:24:45.331 ThaliTest[1298:2784202] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 11:24:45.342 ThaliTest[1298:2784202] server: accepting invitation Apple-Iphone5s-1
,2016-01-05 11:24:48.220 ThaliTest[1298:2785201] server session: connected
2016-01-05 11:24:48.220 ThaliTest[1298:2785201] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05 11:24:48.251 ThaliTest[1298:2784202] server relay: connected (to port: 63037)
2016-01-05T10:24:48.251Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:48.999Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-05T10:24:49.015Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-05T10:24:49.032Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2016-01-05T10:24:49.049Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-05T10:24:49.066Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-05T10:24:49.080Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:49.187 ThaliTest[1298:2785201] server session: not connected Apple-Iphone5s-1
,2016-01-05 11:24:51.209 ThaliTest[1298:2784202] client: lost peer: Apple-Iphone5-1.GgrI3w==
2016-01-05 11:24:51.210 ThaliTest[1298:2784202] client session: onPeerLost: Apple-Iphone5-1.GgrI3w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.G,grI3w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 11:24:51.317 ThaliTest[1298:2784202] client: lost peer: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:51.318 ThaliTest[1298:2784202] client session: onPeerLost: Apple-Iphone5s-1.R3Z2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.R3Z2qA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 11:24:58.056 ThaliTest[1298:2784202] client: lost peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:24:58.057 ThaliTest[1298:2784202] client session: onPeerLost: Apple-IpadAir2-1.C4KP1Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.C4KP1Q==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
,2016-01-05 11:25:05.494 ThaliTest[1298:2784400] jxcore: stopBroadcasting
2016-01-05 11:25:05.495 ThaliTest[1298:2784400] THEMultipeerSession stopping peer
2016-01-05 11:25:05.495 ThaliTest[1298:2784400] multipeer session: stop timer
2016-01-05 11:25:05.496 ThaliTest[1298:2784400] server session: disconnect
2016-01-05 11:25:05.496 ThaliTest[1298:2784400] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-05 11:25:05.505 ThaliTest[1298:2784400] server session: disconnect
2016-01-05 11:25:05.506 ThaliTest[1298:2784400] server session: stateChange:2->0 Apple-Iphone5-1
2016-01-05 11:25:05.515 ThaliTest[1298:2784400] server session: disconnect
2016-01-05 11:25:05.515 ThaliTest[1298:2784400] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-05 11:25:05.526 ThaliTest[1298:2784400] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T10:25:05.548Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-05T10:25:05.549Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:25:05.551Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:25:05.552Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
