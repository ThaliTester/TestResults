#### Test 55311151a2306df_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/FF65FD17-1842-4EDD-A14D-B818B72F75AA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/FF65FD17-1842-4EDD-A14D-B818B72F75AA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B805EBCB-1D87-4191-9E8A-E30E96387EBD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49449"
,(lldb)     command script import "/tmp/FF65FD17-1842-4EDD-A14D-B818B72F75AA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 09:35:23.205 ThaliTest[1030:3385868] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/574A05D5-E1F8-4C6E-9539-F094474AF56C/Library/Cookies/Cookies.binarycookies
,2016-01-07 09:35:23.345 ThaliTest[1030:3385868] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 09:35:23.347 ThaliTest[1030:3385868] Multi-tasking -> Device: YES, App: YES
,2016-01-07 09:35:23.353 ThaliTest[1030:3385868] Unlimited access to network resources
,2016-01-07 09:35:23.370 ThaliTest[1030:3385868] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 09:35:33.763 ThaliTest[1030:3385868] Resetting plugins due to page load.
,2016-01-07 09:35:38.112 ThaliTest[1030:3385868] Finished load of: file:///var/mobile/Containers/Bundle/Application/B805EBCB-1D87-4191-9E8A-E30E96387EBD/ThaliTest.app/www/index.html
,2016-01-07 09:35:38.321 ThaliTest[1030:3385868] JXcore Cordova plugin initializing
,2016-01-07 09:35:38.324 ThaliTest[1030:3386056] JXcore instance initializing
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
,2016-01-07 09:35:40.742 ThaliTest[1030:3385868] THREAD WARNING: ['JXcore'] took '154.518799' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 09:41:49.816 ThaliTest[1030:3386056] jxcore: startBroadcasting
,2016-01-07 09:41:49.830 ThaliTest[1030:3386056] server: starting Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:41:49.831 ThaliTest[1030:3386056] multipeer session: start timer: 0x1bb94e60
2016-01-07 09:41:49.831 ThaliTest[1030:3386056] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-07 09:41:49.831 ThaliTest[1030:3386056] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-07 09:41:53.014 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.ujszBw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.ujszBw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-IpadAir2-1.ujszBw==, peerAvailable: true
,2016-01-07 09:41:53.596 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1.TWDlRQ==, peerAvailable: true
,2016-01-07 09:41:54.554 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.qqPEfA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.qqPEfA==, peerAvailable: true
,2016-01-07 09:42:19.832 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:42:19.866 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:42:19.867 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:42:19.869 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.qqPEfA==
,2016-01-07 09:42:49.832 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:42:49.866 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:42:49.866 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:42:49.868 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.qqPEfA==
,2016-01-07 09:43:19.618 ThaliTest[1030:3385868] client: lost peer: Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:43:19.618 ThaliTest[1030:3385868] client session: onPeerLost: Apple-Iphone5s-1.TWDlRQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.TWDlRQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-07 09:43:19.832 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:43:19.862 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.ujszBw==
2016-01-07 09:43:19.863 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.qqPEfA==
,timeout now
,weAreDoneNow
,done, now sending data to server
,2016-01-07 09:43:30.498 ThaliTest[1030:3385868] client: lost peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:43:30.498 ThaliTest[1030:3385868] client session: onPeerLost: Apple-Iphone6-1.qqPEfA==
,2016-01-07 09:43:49.832 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:43:49.866 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.ujszBw==
,teardown
,testFindPeers stopped
,2016-01-07 09:43:50.180 ThaliTest[1030:3386056] jxcore: stopBroadcasting
,2016-01-07 09:43:50.181 ThaliTest[1030:3386056] THEMultipeerSession stopping peer
2016-01-07 09:43:50.182 ThaliTest[1030:3386056] multipeer session: stop timer
2016-01-07 09:43:50.182 ThaliTest[1030:3386056] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 4
,daya100000
check server
,serverPort is 64873
,2016-01-07 09:43:50.241 ThaliTest[1030:3386056] jxcore: startBroadcasting
,2016-01-07 09:43:50.244 ThaliTest[1030:3386056] server: starting Apple-Iphone5-1.4D8zyg==
2016-01-07 09:43:50.245 ThaliTest[1030:3386056] multipeer session: start timer: 0x1bc1d120
2016-01-07 09:43:50.245 ThaliTest[1030:3386056] THEMultipeerSession initialized peer Apple-Iphone5-1
2016-01-07 09:43:50.245 ThaliTest[1030:3386056] jxcore: startBroadcasting: success
StartBroadcasting started ok
,[ { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 } ]
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:43:50.264Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:43:50.266Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:43:50.266Z SendDataConnector.js: do connect now
,2016-01-07 09:43:50.267 ThaliTest[1030:3386056] jxcore: connect 
,2016-01-07 09:43:50.268 ThaliTest[1030:3386056] client: unknown peer 
,2016-01-07 09:43:50.269 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:43:50.271Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:43:50.272Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:43:50.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:43:50.275Z SendDataTCPServer.js: TCP/IP server is bound to port: 64873
,2016-01-07 09:43:51.246 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:43:51.289 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.LQugrg==
,2016-01-07T08:43:55.280Z SendDataConnector.js: re-try now : 
,2016-01-07T08:43:55.281Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:00.293 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:00.293 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:00.294Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:00.295Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:44:00.295Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:00.295Z SendDataConnector.js: do connect now
2016-01-07 09:44:00.296 ThaliTest[1030:3386056] jxcore: connect 
,2016-01-07 09:44:00.297 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:00.297 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:00.297Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:00.298Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:00.298Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:05.299Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:05.299Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:07.190 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:44:07.190 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.I/6L8w==
,2016-01-07 09:44:10.305 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:10.306 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:10.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:10.307Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:44:10.307Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:10.307Z SendDataConnector.js: do connect now
,2016-01-07 09:44:10.308 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:44:10.309 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:10.309 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:10.309Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:10.310Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:10.310Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:15.314Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:15.314Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:20.245 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:44:20.284 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.LQugrg==
2016-01-07 09:44:20.285 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:44:20.285 ThaliTest[1030:3385868] client: found peer,: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:44:20.286 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.I/6L8w==
,2016-01-07 09:44:20.320 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:20.321 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:20.322Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:20.323Z SendDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:44:20.323Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:20.323Z SendDataConnector.js: do connect now
2016-01-07 09:44:20.324 ThaliTest[1030:3386056] jxcore: connect 
,2016-01-07 09:44:20.325 ThaliTest[1030:3386056] client: unknown peer 
,2016-01-07 09:44:20.325 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:20.326Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:20.326Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:20.326Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:25.333Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:25.333Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:30.347 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:30.347 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:30.348Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:30.348Z SendDataConnector.js: Connect (retry count 4) to peer  with availability status: true
2016-01-07T08:44:30.349Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:30.349Z SendDataConnector.js: do connect now
,2016-01-07 09:44:30.350 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:44:30.350 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:30.351 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:30.351Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:30.351Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,oneRoundDownNow
2016-01-07T08:44:30.353Z SendDataConnector.js: CLIENT Stop now
2016-01-07 09:44:30.353 ThaliTest[1030:3386056] jxcore: disconnect
,2016-01-07 09:44:30.353 ThaliTest[1030:3386056] jxcore: disconnect: fail
,2016-01-07T08:44:30.354Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
---- round done--------
startWithNextDevice
do fake peer & start
Connect to fake peer: 
,2016-01-07T08:44:30.356Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:44:30.356Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:30.357Z SendDataConnector.js: do connect now
,2016-01-07 09:44:30.357 ThaliTest[1030:3386056] jxcore: connect 
,2016-01-07 09:44:30.358 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:30.358 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:30.358Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:30.359Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:44:30.359Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:35.361Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:35.361Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:40.369 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:40.370 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:40.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:40.371Z S,endDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:44:40.371Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:40.372Z SendDataConnector.js: do connect now
,2016-01-07 09:44:40.372 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:44:40.373 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:40.373 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:40.374Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:40.374Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:40.375Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:45.381Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:45.381Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:50.246 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:44:50.283 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:44:50.287 ThaliTest[1030:3385868] client: found peer: Apple-Iphone6-1.I/6L8w==
,2016-01-07 09:44:50.394 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:44:50.395 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:44:50.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:44:50.396Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:44:50.396Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:50.396Z SendDataConnector.js: do connect now
,2016-01-07 09:44:50.397 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:44:50.398 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:44:50.398 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:50.398Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:50.399Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:50.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07 09:44:50.532 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:44:51.038 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.LQugrg==
,2016-01-07T08:44:55.405Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:55.406Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:00.410 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:00.410 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:00.411Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:00.411Z S,endDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:45:00.412Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:00.412Z SendDataConnector.js: do connect now
,2016-01-07 09:45:00.413 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:45:00.413 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:45:00.414 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:00.414Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:00.414Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:00.415Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:05.418Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:05.419Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:10.432 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:10.433 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:10.433Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:10.434Z SendDataConnector.js: Connect (retry count 4) to peer  with availability status: true
2016-01-07T08:45:10.434Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:10.435Z SendDataConnector.js: do connect now
2016-01-07 09:45:10.436 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:45:10.436 ThaliTest[1030:3386056] client: unknown peer 
,2016-01-07 09:45:10.436 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:10.437Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:10.438Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
oneRoundDownNow
2016-01-07T08:45:10.438Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:10.438 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:10.439 ThaliTest[1030:3386056] jxcore: disconnect: fail
,2016-01-07T08:45:10.439Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
---- round done--------
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:45:10.441Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:45:10.441Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:10.441Z SendDataConnector.js: do connect now
,2016-01-07 09:45:10.442 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:45:10.442 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:45:10.443 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:10.443Z SendDataC,onnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:10.443Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:10.443Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:15.454Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:15.455Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:20.246 ThaliTest[1030:3385868] multipeer session: restart
,2016-01-07 09:45:20.286 ThaliTest[1030:3385868] client: found peer: Apple-IpadAir2-1.LQugrg==
2016-01-07 09:45:20.287 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:45:20.287 ThaliTest[1030:3385868] client: found peer:, Apple-Iphone6-1.I/6L8w==
2016-01-07 09:45:20.288 ThaliTest[1030:3385868] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:45:20.459 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:20.459 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:20.460Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:20.461Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:45:20.461Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:20.462Z SendDataConnector.js: do connect now
2016-01-07 09:45:20.462 ThaliTest[1030:3386056] jxcore: connect 
,2016-01-07 09:45:20.463 ThaliTest[1030:3386056] client: unknown peer 
,2016-01-07 09:45:20.463 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:20.464Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:45:20.464Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
2016-01-07T08:45:20.464Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:25.472Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:25.473Z SendDataConnector.js: ReStart called with peer 
,timeout now
,weAreDoneNow, resultArray.length: 0
,sendReportNow
,done, now sending data to server
,2016-01-07T08:45:30.289Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:30.289 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:30.290 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:30.290Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07 09:45:30.479 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:30.479 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:30.480Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:30.480Z S,endDataConnector.js: Connect (retry count 2) to peer  with availability status: true
2016-01-07T08:45:30.481Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:30.481Z SendDataConnector.js: do connect now
,2016-01-07 09:45:30.482 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:45:30.482 ThaliTest[1030:3386056] client: unknown peer 
2016-01-07 09:45:30.483 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:30.483Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:30.483Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:30.484Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:35.488Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:35.489Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:40.492 ThaliTest[1030:3386056] jxcore: disconnect
2016-01-07 09:45:40.492 ThaliTest[1030:3386056] jxcore: disconnect: fail
2016-01-07T08:45:40.493Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
2016-01-07T08:45:40.493Z S,endDataConnector.js: Connect (retry count 3) to peer  with availability status: true
2016-01-07T08:45:40.494Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:45:40.494Z SendDataConnector.js: do connect now
,2016-01-07 09:45:40.495 ThaliTest[1030:3386056] jxcore: connect 
2016-01-07 09:45:40.495 ThaliTest[1030:3386056] client: unknown peer 
,2016-01-07 09:45:40.496 ThaliTest[1030:3386056] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:40.496Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:40.497Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:40.497Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:45.506Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:45.506Z SendDataConnector.js: ReStart called with peer 
,teardown
,testSendData stopped
2016-01-07 09:45:50.187 ThaliTest[1030:3386056] jxcore: stopBroadcasting
2016-01-07 09:45:50.187 ThaliTest[1030:3386056] THEMultipeerSession stopping peer
,2016-01-07 09:45:50.187 ThaliTest[1030:3386056] multipeer session: stop timer
,2016-01-07 09:45:50.188 ThaliTest[1030:3386056] jxcore: stopBroadcasting: success
StopBroadcasting went ok
2016-01-07T08:45:50.189Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
