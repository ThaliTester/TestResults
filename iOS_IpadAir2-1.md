#### Test 55467363832a26e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/74EC9BF9-ED2C-4E58-8648-C692964B4D5D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/74EC9BF9-ED2C-4E58-8648-C692964B4D5D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/650762C4-C69C-4AA3-917C-AF16B9BA8786/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50688"
,(lldb)     command script import "/tmp/74EC9BF9-ED2C-4E58-8648-C692964B4D5D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:51:42.615 ThaliTest[1567:3349486] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5C2060B7-9D78-489B-A404-3F2CB707434C/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:51:42.934 ThaliTest[1567:3349486] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:51:42.935 ThaliTest[1567:3349486] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:51:42.942 ThaliTest[1567:3349486] Unlimited access to network resources
,2016-01-08 17:51:42.949 ThaliTest[1567:3349486] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:51:51.961 ThaliTest[1567:3349486] Resetting plugins due to page load.
,2016-01-08 17:51:55.786 ThaliTest[1567:3349486] Finished load of: file:///var/mobile/Containers/Bundle/Application/650762C4-C69C-4AA3-917C-AF16B9BA8786/ThaliTest.app/www/index.html
,2016-01-08 17:51:55.944 ThaliTest[1567:3349486] JXcore Cordova plugin initializing
,2016-01-08 17:51:55.945 ThaliTest[1567:3349733] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-08 17:51:57.030 ThaliTest[1567:3349486] THREAD WARNING: ['JXcore'] took '69.553955' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 17:57:05.534 ThaliTest[1567:3349733] jxcore: startBroadcasting
,2016-01-08 17:57:05.552 ThaliTest[1567:3349733] server: starting Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:05.554 ThaliTest[1567:3349733] multipeer session: start timer: 0x17495d20
2016-01-08 17:57:05.555 ThaliTest[1567:3349733] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-08 17:57:05.555 ThaliTest[1567:3349733] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-08 17:57:06.220 ThaliTest[1567:3349486] client: found peer: Apple-Iphone6-1.3GMDyQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.3GMDyQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 17:57:07.111 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:07.244 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.kFnM8A==
,teardown
,testFindPeers stopped
,2016-01-08 17:57:07.435 ThaliTest[1567:3349733] jxcore: stopBroadcasting
,2016-01-08 17:57:07.435 ThaliTest[1567:3349733] THEMultipeerSession stopping peer
,2016-01-08 17:57:07.436 ThaliTest[1567:3349733] multipeer session: stop timer
,2016-01-08 17:57:07.437 ThaliTest[1567:3349733] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 65294
,2016-01-08 17:57:07.466 ThaliTest[1567:3349733] jxcore: startBroadcasting
,2016-01-08 17:57:07.471 ThaliTest[1567:3349733] server: starting Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:07.472 ThaliTest[1567:3349733] multipeer session: start timer: 0x17495ee0
2016-01-08 17:57:07.472 ThaliTest[1567:3349733] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-08 17:57:07.473 ThaliTest[1567:3349733] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-08T16:57:07.479Z SendDataTCPServer.js: TCP/IP server is bound to port: 65294
,2016-01-08 17:57:07.544 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:07.545 ThaliTest[1567:3349486] client: found peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:07.545 ThaliTest[1567:3349486] client: found peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.546 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.kFnM8A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:07.556Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:07.557Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:07.558Z SendDataConnector.js: do connect now
,2016-01-08 17:57:07.559 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:07.559 ThaliTest[1567:3349733] client session: connect
,2016-01-08 17:57:07.560 ThaliTest[1567:3349733] client session: stateChange:0->1 Apple-Iphone5-1.vqNzbw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:08.698 ThaliTest[1567:3349486] client: lost peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:08.698 ThaliTest[1567:3349486] client session: onPeerLost: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:08.699 ThaliTest[1567:3349486] client: los,t peer: Apple-Iphone5s-1.kFnM8A==
2016-01-08 17:57:08.699 ThaliTest[1567:3349486] client session: onPeerLost: Apple-Iphone5s-1.kFnM8A==
2016-01-08 17:57:08.699 ThaliTest[1567:3349486] client: found peer: Apple-Iphone6-1.g6FFQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.g6FFQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:08.801 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.PGcCxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:08.905 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5-1.kBkHjQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kBkHjQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:09.691 ThaliTest[1567:3349486] client: lost peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:09.691 ThaliTest[1567:3349486] client session: onPeerLost: Apple-Iphone6-1.3GMDyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 17:57:13.872 ThaliTest[1567:3349486] client: lost peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.873 ThaliTest[1567:3349486] client session: onPeerLost: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.873 ThaliTest[1567:3349486] client sessio,n: onLinkFailure: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.873 ThaliTest[1567:3349486] client session: disconnect
2016-01-08 17:57:13.874 ThaliTest[1567:3349486] client session: stateChange:1->0 Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.874 Thali,Test[1567:3349486] client session: fireConnectCallback: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.875 ThaliTest[1567:3349486] jxcore: connect: fail: Peer disconnected
,2016-01-08T16:57:13.877Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-08T16:57:13.878Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T16:57:13.879Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":false}]
,2016-01-08T16:57:18.884Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:18.885Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:23.899 ThaliTest[1567:3349733] jxcore: disconnect
2016-01-08 17:57:23.899 ThaliTest[1567:3349733] jxcore: disconnect: fail
,2016-01-08T16:57:23.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:23.901Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
,2016-01-08T16:57:23.901Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:23.902Z SendDataConnector.js: do connect now
,2016-01-08 17:57:23.903 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:23.904 ThaliTest[1567:3349733] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:23.904 ThaliTest[1567:3349733] jxcore: connect: fail: Peer unreachable
2016-01-08T16:57:23.904Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T16:57:23.905Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:23.905Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:28.916Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:28.916Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:33.917 ThaliTest[1567:3349733] jxcore: disconnect
2016-01-08 17:57:33.918 ThaliTest[1567:3349733] jxcore: disconnect: fail
,2016-01-08T16:57:33.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:33.919Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
,2016-01-08T16:57:33.920Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:33.920Z SendDataConnector.js: do connect now
,2016-01-08 17:57:33.921 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:33.922 ThaliTest[1567:3349733] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:33.923 ThaliTest[1567:3349733] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:33.924Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T16:57:33.924Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T16:57:33.925Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 17:57:37.474 ThaliTest[1567:3349486] multipeer session: restart
,2016-01-08 17:57:37.503 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:37.504 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:37.504 ThaliTest[1567:3349486] client: found peer: Apple-Iphone6-1.g6FFQA==
,2016-01-08T16:57:38.927Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:38.927Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:43.937 ThaliTest[1567:3349733] jxcore: disconnect
2016-01-08 17:57:43.937 ThaliTest[1567:3349733] jxcore: disconnect: fail
,2016-01-08T16:57:43.938Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:43.939Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
,2016-01-08T16:57:43.940Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:43.940Z SendDataConnector.js: do connect now
,2016-01-08 17:57:43.941 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:43.942 ThaliTest[1567:3349733] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:43.942 ThaliTest[1567:3349733] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:43.943Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:43.944Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:43.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 17:57:44.950 ThaliTest[1567:3349486] client: lost peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:44.950 ThaliTest[1567:3349486] client session: onPeerLost: Apple-Iphone5s-1.PGcCxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08T16:57:48.955Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:48.956Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:52.093 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.PGcCxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:53.958 ThaliTest[1567:3349733] jxcore: disconnect
2016-01-08 17:57:53.958 ThaliTest[1567:3349733] jxcore: disconnect: fail
,2016-01-08T16:57:53.959Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:53.960Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
,2016-01-08T16:57:53.960Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:53.961Z SendDataConnector.js: do connect now
,2016-01-08 17:57:53.962 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:53.962 ThaliTest[1567:3349733] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:53.963 ThaliTest[1567:3349733] jxcore: connect: fail: Peer unreachable
,2016-01-08T16:57:53.963Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:53.964Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T16:57:53.966Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 17:57:53.967 ThaliTest[1567:3349733] jxcore: disconnect
,2016-01-08 17:57:53.968 ThaliTest[1567:3349733] jxcore: disconnect: fail
,2016-01-08T16:57:53.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1.g6FFQA==
,2016-01-08T16:57:53.972Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.g6FFQA==
,2016-01-08T16:57:53.972Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.g6FFQA==
,2016-01-08T16:57:53.973Z SendDataConnector.js: do connect now
,2016-01-08 17:57:53.974 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:53.975 ThaliTest[1567:3349733] client session: connect
,2016-01-08 17:57:53.975 ThaliTest[1567:3349733] client session: stateChange:0->1 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:54.375 ThaliTest[1567:3349486] multipeer session: reset timer
,2016-01-08 17:57:54.375 ThaliTest[1567:3349486] multipeer session: stop timer
,2016-01-08 17:57:54.376 ThaliTest[1567:3349486] multipeer session: start timer: 0x17495ee0
,2016-01-08 17:57:54.376 ThaliTest[1567:3349486] server session: connect
,2016-01-08 17:57:54.377 ThaliTest[1567:3349486] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 17:57:54.383 ThaliTest[1567:3349486] server: accepting invitation Apple-Iphone5-1
,2016-01-08 17:57:54.859 ThaliTest[1567:3349486] multipeer session: reset timer
2016-01-08 17:57:54.859 ThaliTest[1567:3349486] multipeer session: stop timer
2016-01-08 17:57:54.859 ThaliTest[1567:3349486] multipeer session: start timer: 0x17495ee0
2016-01-08 17:57:54.859 ThaliTest[1567:3349486] server session: connect
2016-01-08 17:57:54.859 ThaliTest[1567:3349486] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 17:57:54.862 ThaliTest[1567:3349486] server: accepting invitation Apple-Iphone6-1
,2016-01-08 17:57:58.173 ThaliTest[1567:3351402] server session: connected
2016-01-08 17:57:58.173 ThaliTest[1567:3351402] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 17:57:58.224 ThaliTest[1567:3349486] server relay: connected (to port: 65294)
,2016-01-08T16:57:58.231Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 17:57:58.311 ThaliTest[1567:3349486] multipeer session: reset timer
2016-01-08 17:57:58.312 ThaliTest[1567:3349486] multipeer session: stop timer
2016-01-08 17:57:58.312 ThaliTest[1567:3349486] multipeer session: start timer: 0x17495ee0
2016-01-08 17:57:58.312 ThaliTest[1567:3349486] server session: connect
,2016-01-08 17:57:58.312 ThaliTest[1567:3349486] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 17:57:58.320 ThaliTest[1567:3349486] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 17:57:58.562 ThaliTest[1567:3351402] server session: connected
2016-01-08 17:57:58.562 ThaliTest[1567:3351402] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 17:57:58.635 ThaliTest[1567:3349486] server relay: connected (to port: 65294)
,2016-01-08T16:57:58.639Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 17:57:58.950 ThaliTest[1567:3351384] client session: connected
2016-01-08 17:57:58.950 ThaliTest[1567:3351384] client session: stateChange:1->2 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:58.961 ThaliTest[1567:3351399] client session: fireConnectCallback: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:58.961 ThaliTest[1567:3351399] jxcore: connect: success
2016-01-08T16:57:58.961Z SendDataConnector.js: CLIENT connected to 65300, error: null
2016-01-08T16:57:58.962Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:57:58.963 ThaliTest[1567:3349486] client: relay established
2016-01-08 17:57:58.963 ThaliTest[1567:3349486] client: new accepted socket: 0x157ce350
,2016-01-08T16:57:58.976Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:57:59.401Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T16:57:59.402Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T16:57:59.403Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T16:57:59.406Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T16:57:59.443Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08 17:57:59.452 ThaliTest[1567:3351351] server session: not connected Apple-Iphone6-1
,2016-01-08 17:57:59.477 ThaliTest[1567:3351384] server session: not connected Apple-Iphone5-1
,2016-01-08T16:57:59.478Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:57:59.478Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T16:57:59.478Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:57:59.478Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:59.479 ThaliTest[1567:3349733] jxcore: disconnect
,2016-01-08 17:57:59.480 ThaliTest[1567:3349733] client session: disconnectFromPeer: Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:59.480 ThaliTest[1567:3349733] client session: disconnect
,2016-01-08 17:57:59.480 ThaliTest[1567:3349733] client session: stateChange:2->0 Apple-Iphone6-1.g6FFQA==
,2016-01-08 17:57:59.541 ThaliTest[1567:3349733] jxcore: disconnect: success
,2016-01-08T16:57:59.542Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.g6FFQA==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1.PGcCxg==
,2016-01-08T16:57:59.543Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.PGcCxg==
,2016-01-08T16:57:59.543Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.PGcCxg==
,2016-01-08T16:57:59.543Z SendDataConnector.js: do connect now
,2016-01-08 17:57:59.543 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:57:59.544 ThaliTest[1567:3349733] client session: connect
,2016-01-08 17:57:59.544 ThaliTest[1567:3349733] client session: stateChange:0->1 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:01.915 ThaliTest[1567:3351351] server session: connected
,2016-01-08 17:58:01.915 ThaliTest[1567:3351351] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 17:58:02.034 ThaliTest[1567:3349486] server relay: connected (to port: 65294)
,2016-01-08T16:58:02.040Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:58:02.616Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-08T16:58:02.630Z SendDataTCPServer.js: TCP/IP server has received 23948 bytes of data
,2016-01-08T16:58:02.647Z SendDataTCPServer.js: TCP/IP server has received 47085 bytes of data
,2016-01-08T16:58:02.664Z SendDataTCPServer.js: TCP/IP server has received 55845 bytes of data
,2016-01-08T16:58:02.703Z SendDataTCPServer.js: TCP/IP server has received 66795 bytes of data
,2016-01-08T16:58:02.717Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-08T16:58:02.730Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-08T16:58:02.743Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T16:58:02.828Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T16:58:02.842Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-08T16:58:02.856Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:58:02.963 ThaliTest[1567:3351351] server session: not connected Apple-Iphone5s-1
,2016-01-08 17:58:03.673 ThaliTest[1567:3351401] client session: connected
2016-01-08 17:58:03.674 ThaliTest[1567:3351401] client session: stateChange:1->2 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:03.704 ThaliTest[1567:3351351] client session: fireConnectCallback: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:58:03.704 ThaliTest[1567:3351351] jxcore: connect: success
,2016-01-08T16:58:03.705Z SendDataConnector.js: CLIENT connected to 65304, error: null
,2016-01-08T16:58:03.706Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:03.708 ThaliTest[1567:3349486] client: relay established
,2016-01-08 17:58:03.709 ThaliTest[1567:3349486] client: new accepted socket: 0x1759c3d0
,2016-01-08T16:58:03.722Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:58:04.199Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T16:58:04.336Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T16:58:04.423Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T16:58:04.437Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:58:04.437Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:58:04.437Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:58:04.438Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:04.438 ThaliTest[1567:3349733] jxcore: disconnect
,2016-01-08 17:58:04.438 ThaliTest[1567:3349733] client session: disconnectFromPeer: Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:04.439 ThaliTest[1567:3349733] client session: disconnect
,2016-01-08 17:58:04.439 ThaliTest[1567:3349733] client session: stateChange:2->0 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:04.442 ThaliTest[1567:3349733] jxcore: disconnect: success
2016-01-08T16:58:04.442Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.PGcCxg==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one5-1.kBkHjQ==
2016-01-08T16:58:04.443Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kBkHjQ==
2016-01-08T16:58:04.443Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kBkHjQ==
2016-01-08T16:58:04.443Z SendDataConnector.js: do connect now
2016-01-08 17:58:04.443 ThaliTest[1567:3349733] jxcore: connect Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:04.443 ThaliTest[1567:3349733] client session: connect
,2016-01-08 17:58:04.444 ThaliTest[1567:3349733] client session: stateChange:0->1 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:08.030 ThaliTest[1567:3351399] client session: connected
2016-01-08 17:58:08.031 ThaliTest[1567:3351399] client session: stateChange:1->2 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:08.093 ThaliTest[1567:3351384] client session: fireConnectCallback: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:08.093 ThaliTest[1567:3351384] jxcore: connect: success
2016-01-08T16:58:08.095Z SendDataConnector.js: CLIENT connected to 65307, error: null
2016-01-08T16:58:08.095Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:08.099 ThaliTest[1567:3349486] client: relay established
2016-01-08 17:58:08.099 ThaliTest[1567:3349486] client: new accepted socket: 0x174afe80
,2016-01-08T16:58:08.112Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:58:08.586Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T16:58:08.609Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T16:58:08.620Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T16:58:08.631Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T16:58:08.668Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T16:58:08.693Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:58:08.693Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T16:58:08.694Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:58:08.694Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:08.694 ThaliTest[1567:3349733] jxcore: disconnect
,2016-01-08 17:58:08.695 ThaliTest[1567:3349733] client session: disconnectFromPeer: Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:08.695 ThaliTest[1567:3349733] client session: disconnect
2016-01-08 17:58:08.695 ThaliTest[1567:3349733] client session: stateChange:2->0 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:08.698 ThaliTest[1567:3349733] jxcore: disconnect: success
,2016-01-08T16:58:08.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kBkHjQ==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T16:58:08.709Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:58:08.709Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:28.313 ThaliTest[1567:3349486] multipeer session: restart
,2016-01-08 17:58:28.342 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:28.342 ThaliTest[1567:3349486] client: found peer: Apple-Iphone6-1.g6FFQA==
2016-01-08 17:58:28.344 ThaliTest[1567:3349486] client: found peer: Apple-Iphone5s-1.PGcCxg==
,teardown
,testSendData stopped
,2016-01-08 17:58:38.450 ThaliTest[1567:3349733] jxcore: stopBroadcasting
,2016-01-08 17:58:38.450 ThaliTest[1567:3349733] THEMultipeerSession stopping peer
,2016-01-08 17:58:38.451 ThaliTest[1567:3349733] multipeer session: stop timer
,2016-01-08 17:58:38.452 ThaliTest[1567:3349733] server session: disconnect
2016-01-08 17:58:38.453 ThaliTest[1567:3349733] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 17:58:38.528 ThaliTest[1567:3349733] server session: disconnect
,2016-01-08 17:58:38.530 ThaliTest[1567:3349733] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 17:58:38.535 ThaliTest[1567:3349733] server session: disconnect
,2016-01-08 17:58:38.539 ThaliTest[1567:3349733] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 17:58:38.603 ThaliTest[1567:3349733] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
