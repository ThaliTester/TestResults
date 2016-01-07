#### Test 55311151a2306df_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4AAB917D-27BA-4413-B6B1-FFA63DCFA0B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4AAB917D-27BA-4413-B6B1-FFA63DCFA0B9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55311151a2306df/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CD74FAF8-6308-424B-87E1-D244B366D3A3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49482"
,(lldb)     command script import "/tmp/4AAB917D-27BA-4413-B6B1-FFA63DCFA0B9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-01-07 09:36:51.487 ThaliTest[1441:3142802] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5D96685B-0C25-4913-A7B4-EF8299E5A7C3/Library/Cookies/Cookies.binarycookies
,2016-01-07 09:36:51.811 ThaliTest[1441:3142802] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 09:36:51.811 ThaliTest[1441:3142802] Multi-tasking -> Device: YES, App: YES
,2016-01-07 09:36:51.819 ThaliTest[1441:3142802] Unlimited access to network resources
,2016-01-07 09:36:51.824 ThaliTest[1441:3142802] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 09:37:00.851 ThaliTest[1441:3142802] Resetting plugins due to page load.
,2016-01-07 09:37:04.379 ThaliTest[1441:3142802] Finished load of: file:///var/mobile/Containers/Bundle/Application/CD74FAF8-6308-424B-87E1-D244B366D3A3/ThaliTest.app/www/index.html
,2016-01-07 09:37:04.546 ThaliTest[1441:3142802] JXcore Cordova plugin initializing
2016-01-07 09:37:04.547 ThaliTest[1441:3143036] JXcore instance initializing
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
,2016-01-07 09:37:05.522 ThaliTest[1441:3142802] THREAD WARNING: ['JXcore'] took '70.749023' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 09:41:52.066 ThaliTest[1441:3143036] jxcore: startBroadcasting
,2016-01-07 09:41:52.083 ThaliTest[1441:3143036] server: starting Apple-IpadAir2-1.ujszBw==
,2016-01-07 09:41:52.084 ThaliTest[1441:3143036] multipeer session: start timer: 0x1561db10
2016-01-07 09:41:52.085 ThaliTest[1441:3143036] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-07 09:41:52.085 ThaliTest[1441:3143036] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-07 09:41:53.144 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.Xe0AvA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1.Xe0AvA==, peerAvailable: true
,2016-01-07 09:41:54.190 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.qqPEfA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.qqPEfA==, peerAvailable: true
,2016-01-07 09:41:54.355 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5s-1.TWDlRQ==, peerAvailable: true
,2016-01-07 09:42:22.089 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:42:22.113 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.qqPEfA==
,2016-01-07 09:42:22.115 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:42:22.115 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:42:52.089 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:42:52.116 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:42:52.116 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 09:42:52.117 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:43:22.089 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:43:22.114 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:43:22.114 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.Xe0AvA==
,timeout now
,weAreDoneNow
,done, now sending data to server
,2016-01-07 09:43:33.559 ThaliTest[1441:3142802] client: lost peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 09:43:33.560 ThaliTest[1441:3142802] client session: onPeerLost: Apple-Iphone6-1.qqPEfA==
,teardown
,testFindPeers stopped
,2016-01-07 09:43:51.992 ThaliTest[1441:3143036] jxcore: stopBroadcasting
,2016-01-07 09:43:51.993 ThaliTest[1441:3143036] THEMultipeerSession stopping peer
,2016-01-07 09:43:51.993 ThaliTest[1441:3143036] multipeer session: stop timer
,2016-01-07 09:43:51.995 ThaliTest[1441:3143036] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 4
,daya100000
,check server
,serverPort is 64272
,2016-01-07 09:43:52.131 ThaliTest[1441:3143036] jxcore: startBroadcasting
,2016-01-07 09:43:52.135 ThaliTest[1441:3143036] server: starting Apple-IpadAir2-1.LQugrg==
,2016-01-07 09:43:52.136 ThaliTest[1441:3143036] multipeer session: start timer: 0x15615ca0
,2016-01-07 09:43:52.142 ThaliTest[1441:3143036] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-07 09:43:52.143 ThaliTest[1441:3143036] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,[ { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 },
  { address: '', tryCount: 0 } ]
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:43:52.152Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:43:52.153Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:43:52.153Z SendDataConnector.js: do connect now
,2016-01-07 09:43:52.154 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:43:52.154 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:43:52.155 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:43:52.156Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:43:52.156Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:43:52.156Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:43:52.157Z SendDataTCPServer.js: TCP/IP server is bound to port: 64272
,2016-01-07 09:43:53.122 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:43:53.608 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.4D8zyg==
,2016-01-07T08:43:57.157Z SendDataConnector.js: re-try now : 
2016-01-07T08:43:57.158Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:00.121 ThaliTest[1441:3142802] client: lost peer: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:44:00.122 ThaliTest[1441:3142802] client session: onPeerLost: Apple-Iphone5-1.Xe0AvA==
,2016-01-07 09:44:02.170 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:44:02.170 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:02.172Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:02.173Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
,2016-01-07T08:44:02.173Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:02.174Z SendDataConnector.js: do connect now
,2016-01-07 09:44:02.175 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:02.175 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:02.176 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:02.176Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:02.177Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:02.178Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:07.184Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:07.185Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:09.755 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:44:09.891 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.I/6L8w==
,2016-01-07 09:44:12.190 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:44:12.191 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:12.192Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:12.193Z SendDataConnector.js: Connect (retry count 2) to peer  with availability status: true
,2016-01-07T08:44:12.193Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:12.194Z SendDataConnector.js: do connect now
,2016-01-07 09:44:12.195 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:12.196 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:12.196 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:12.197Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:12.197Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:12.198Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:17.207Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:17.207Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:22.143 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:44:22.172 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.4D8zyg==
2016-01-07 09:44:22.173 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.I/6L8w==
,2016-01-07 09:44:22.174 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:44:22.210 ThaliTest[1441:3143036] jxcore: disconnect
2016-01-07 09:44:22.210 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:22.211Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:22.212Z SendDataConnector.js: Connect (retry count 3) to peer  with availability status: true
,2016-01-07T08:44:22.213Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:22.213Z SendDataConnector.js: do connect now
,2016-01-07 09:44:22.214 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:22.215 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:22.215 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
2016-01-07T08:44:22.216Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:22.216Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:22.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:27.219Z SendDataConnector.js: re-try now : 
,2016-01-07T08:44:27.220Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:32.227 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:44:32.228 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:32.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:32.230Z SendDataConnector.js: Connect (retry count 4) to peer  with availability status: true
,2016-01-07T08:44:32.231Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:32.231Z SendDataConnector.js: do connect now
,2016-01-07 09:44:32.232 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:32.233 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:32.233 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:32.234Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:32.235Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,oneRoundDownNow
,2016-01-07T08:44:32.237Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:44:32.238 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:44:32.238 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:32.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,---- round done--------
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:44:32.243Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:44:32.243Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:32.244Z SendDataConnector.js: do connect now
,2016-01-07 09:44:32.245 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:32.245 ThaliTest[1441:3143036] client: unknown peer 
2016-01-07 09:44:32.246 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:32.247Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
2016-01-07T08:44:32.247Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:32.248Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:37.248Z SendDataConnector.js: re-try now : 
2016-01-07T08:44:37.249Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:42.258 ThaliTest[1441:3143036] jxcore: disconnect
2016-01-07 09:44:42.258 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:42.258Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:42.260Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
2016-01-07T08:44:42.260Z SendDataConnector.js: doConnect called with peer 
2016-01-07T08:44:42.261Z SendDataConnector.js: do connect now
,2016-01-07 09:44:42.262 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:42.262 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:42.263 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:42.263Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:42.264Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:42.265Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:47.273Z SendDataConnector.js: re-try now : 
2016-01-07T08:44:47.273Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:44:52.143 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:44:52.168 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.I/6L8w==
2016-01-07 09:44:52.168 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.4D8zyg==
2016-01-07 09:44:52.170 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:44:52.283 ThaliTest[1441:3143036] jxcore: disconnect
2016-01-07 09:44:52.284 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:44:52.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:44:52.285Z SendDataConnector.js: Connect (retry count 2) to peer  with availability status: true
,2016-01-07T08:44:52.286Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:44:52.286Z SendDataConnector.js: do connect now
,2016-01-07 09:44:52.287 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:44:52.288 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:44:52.288 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:44:52.289Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:44:52.290Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:44:52.290Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:44:57.303Z SendDataConnector.js: re-try now : 
2016-01-07T08:44:57.304Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:02.317 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:45:02.317 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:02.318Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:02.319Z SendDataConnector.js: Connect (retry count 3) to peer  with availability status: true
,2016-01-07T08:45:02.319Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:02.320Z SendDataConnector.js: do connect now
,2016-01-07 09:45:02.321 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:45:02.321 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:45:02.322 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:02.323Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:02.323Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:02.324Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:07.331Z SendDataConnector.js: re-try now : 
2016-01-07T08:45:07.332Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:12.345 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:45:12.346 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:12.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:12.347Z SendDataConnector.js: Connect (retry count 4) to peer  with availability status: true
,2016-01-07T08:45:12.348Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:12.349Z SendDataConnector.js: do connect now
,2016-01-07 09:45:12.350 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:45:12.350 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:45:12.351 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
2016-01-07T08:45:12.351Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:12.352Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,oneRoundDownNow
,2016-01-07T08:45:12.353Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:12.354 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:45:12.354 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:12.355Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,---- round done--------
,startWithNextDevice
,do fake peer & start
,Connect to fake peer: 
,2016-01-07T08:45:12.358Z SendDataConnector.js: Start called with peer 
,2016-01-07T08:45:12.358Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:12.359Z SendDataConnector.js: do connect now
,2016-01-07 09:45:12.360 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:45:12.361 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:45:12.361 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:12.362Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:12.363Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:12.363Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:17.373Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:17.374Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:22.143 ThaliTest[1441:3142802] multipeer session: restart
,2016-01-07 09:45:22.170 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.4D8zyg==
2016-01-07 09:45:22.171 ThaliTest[1441:3142802] client: found peer: Apple-Iphone6-1.I/6L8w==
2016-01-07 09:45:22.171 ThaliTest[1441:3142802] client: found peer: ,Apple-Iphone5s-1.TWDlRQ==
,2016-01-07 09:45:22.384 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:45:22.385 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:22.386Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:22.387Z SendDataConnector.js: Connect (retry count 1) to peer  with availability status: true
,2016-01-07T08:45:22.388Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:22.388Z SendDataConnector.js: do connect now
,2016-01-07 09:45:22.389 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:45:22.389 ThaliTest[1441:3143036] client: unknown peer 
2016-01-07 09:45:22.390 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:22.391Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:22.392Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:22.392Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:27.395Z SendDataConnector.js: re-try now : 
2016-01-07T08:45:27.395Z SendDataConnector.js: ReStart called with peer 
,timeout now
,weAreDoneNow, resultArray.length: 0
,sendReportNow
,done, now sending data to server
,2016-01-07T08:45:32.178Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 09:45:32.179 ThaliTest[1441:3143036] jxcore: disconnect
,2016-01-07 09:45:32.179 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:32.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07 09:45:32.404 ThaliTest[1441:3143036] jxcore: disconnect
2016-01-07 09:45:32.405 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:32.406Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:32.407Z SendDataConnector.js: Connect (retry count 2) to peer  with availability status: true
,2016-01-07T08:45:32.407Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:32.408Z SendDataConnector.js: do connect now
,2016-01-07 09:45:32.409 ThaliTest[1441:3143036] jxcore: connect 
2016-01-07 09:45:32.409 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:45:32.410 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:32.410Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:32.411Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:32.412Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:37.418Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:37.419Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:42.423 ThaliTest[1441:3143036] jxcore: disconnect
2016-01-07 09:45:42.424 ThaliTest[1441:3143036] jxcore: disconnect: fail
,2016-01-07T08:45:42.425Z SendDataConnector.js: Mobile.Disconnect() callback with peer 
,2016-01-07T08:45:42.425Z SendDataConnector.js: Connect (retry count 3) to peer  with availability status: true
,2016-01-07T08:45:42.426Z SendDataConnector.js: doConnect called with peer 
,2016-01-07T08:45:42.427Z SendDataConnector.js: do connect now
,2016-01-07 09:45:42.428 ThaliTest[1441:3143036] jxcore: connect 
,2016-01-07 09:45:42.428 ThaliTest[1441:3143036] client: unknown peer 
,2016-01-07 09:45:42.429 ThaliTest[1441:3143036] jxcore: connect: fail: Unknown peer
,2016-01-07T08:45:42.430Z SendDataConnector.js: CLIENT connected to 0, error: Unknown peer
,2016-01-07T08:45:42.431Z SendDataConnector.js: CLIENT Can not Connect: Unknown peer
,2016-01-07T08:45:42.431Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T08:45:47.434Z SendDataConnector.js: re-try now : 
,2016-01-07T08:45:47.435Z SendDataConnector.js: ReStart called with peer 
,2016-01-07 09:45:52.143 ThaliTest[1441:3142802] multipeer session: restart
,teardown
,2016-01-07 09:45:52.173 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5-1.4D8zyg==
testSendData stopped
2016-01-07 09:45:52.173 ThaliTest[1441:3142802] client: found peer: Apple-Iphone5s-1.TWDlRQ==
2016-01-07 09:45:52.174 ThaliTest[1441:314280,2] client: found peer: Apple-Iphone6-1.I/6L8w==
2016-01-07 09:45:52.174 ThaliTest[1441:3143036] jxcore: stopBroadcasting
2016-01-07 09:45:52.174 ThaliTest[1441:3143036] THEMultipeerSession stopping peer
2016-01-07 09:45:52.175 ThaliTest[1441:3143036] multipeer session: stop timer
,2016-01-07 09:45:52.178 ThaliTest[1441:3143036] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-07T08:45:52.184Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
