#### Test 55467363832a26e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/78B185BA-52A6-4169-927E-021F136A83C8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/78B185BA-52A6-4169-927E-021F136A83C8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55467363832a26e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6FE995F7-C698-46F2-AF78-62C138B12B70/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50689"
,(lldb)     command script import "/tmp/78B185BA-52A6-4169-927E-021F136A83C8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 17:51:42.012 ThaliTest[1538:3258897] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F8B032C0-0798-4B3C-8CAD-7A4E0A15FE25/Library/Cookies/Cookies.binarycookies
,2016-01-08 17:51:42.382 ThaliTest[1538:3258897] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 17:51:42.384 ThaliTest[1538:3258897] Multi-tasking -> Device: YES, App: YES
,2016-01-08 17:51:42.395 ThaliTest[1538:3258897] Unlimited access to network resources
,2016-01-08 17:51:42.410 ThaliTest[1538:3258897] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 17:51:51.292 ThaliTest[1538:3258897] Resetting plugins due to page load.
,2016-01-08 17:51:54.914 ThaliTest[1538:3258897] Finished load of: file:///var/mobile/Containers/Bundle/Application/6FE995F7-C698-46F2-AF78-62C138B12B70/ThaliTest.app/www/index.html
,2016-01-08 17:51:55.095 ThaliTest[1538:3258897] JXcore Cordova plugin initializing
,2016-01-08 17:51:55.096 ThaliTest[1538:3259116] JXcore instance initializing
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
,2016-01-08 17:51:56.307 ThaliTest[1538:3258897] THREAD WARNING: ['JXcore'] took '74.631836' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 17:57:04.496 ThaliTest[1538:3259116] jxcore: startBroadcasting
,2016-01-08 17:57:04.513 ThaliTest[1538:3259116] server: starting Apple-Iphone6-1.3GMDyQ==
,2016-01-08 17:57:04.513 ThaliTest[1538:3259116] multipeer session: start timer: 0x16422580
2016-01-08 17:57:04.514 ThaliTest[1538:3259116] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-08 17:57:04.515 ThaliTest[1538:3259116] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 17:57:06.212 ThaliTest[1538:3258897] client: found peer: Apple-IpadAir2-1.hiitZQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.hiitZQ==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2016-01-08 17:57:06.222 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:06.352 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.kFnM8A==
,teardown
,testFindPeers stopped
,2016-01-08 17:57:06.521 ThaliTest[1538:3259116] jxcore: stopBroadcasting
2016-01-08 17:57:06.522 ThaliTest[1538:3259116] THEMultipeerSession stopping peer
2016-01-08 17:57:06.523 ThaliTest[1538:3259116] multipeer session: stop timer
2016-01-08 17:57:06.,523 ThaliTest[1538:3259116] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64899
,2016-01-08 17:57:06.566 ThaliTest[1538:3259116] jxcore: startBroadcasting
,2016-01-08 17:57:06.571 ThaliTest[1538:3259116] server: starting Apple-Iphone6-1.g6FFQA==
2016-01-08 17:57:06.572 ThaliTest[1538:3259116] multipeer session: start timer: 0x163e8930
2016-01-08 17:57:06.573 ThaliTest[1538:3259116] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-08 17:57:06.573 ThaliTest[1538:3259116] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-08T16:57:06.577Z SendDataTCPServer.js: TCP/IP server is bound to port: 64899
,2016-01-08 17:57:07.085 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:07.086 ThaliTest[1538:3258897] client: found peer: Apple-IpadAir2-1.hiitZQ==
2016-01-08 17:57:07.086 ThaliTest[1538:3258897] client: found peer:, Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:07.089 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.kFnM8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null),, Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:07.092Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:07.095Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:07.095Z SendDataConnector.js: do connect no,w
2016-01-08 17:57:07.096 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:07.097 ThaliTest[1538:3259116] client session: connect
2016-01-08 17:57:07.097 ThaliTest[1538:3259116] client session: stateChange:0->1 Apple-Iphone5-1.vqNzbw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailabl,e":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.kFnM8A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:07.777 ThaliTest[1538:3258897] client: lost peer: Apple-Iphone5s-1.kFnM8A==
2016-01-08 17:57:07.778 ThaliTest[1538:3258897] client session: onPeerLost: Apple-Iphone5s-1.kFnM8A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.kFnM8A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:07.838 ThaliTest[1538:3258897] client: lost peer: Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:07.838 ThaliTest[1538:3258897] client session: onPeerLost: Apple-IpadAir2-1.hiitZQ==
,2016-01-08 17:57:07.839 ThaliTest[1538:3258897] client: found peer: Apple-IpadAir2-1.lYAIVQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hiitZQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.lYAIVQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:07.946 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.PGcCxg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 17:57:08.050 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5-1.kBkHjQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kBkHjQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:08.512 ThaliTest[1538:3258897] client: lost peer: Apple-Iphone6-1.3GMDyQ==
2016-01-08 17:57:08.512 ThaliTest[1538:3258897] client session: onPeerLost: Apple-Iphone6-1.3GMDyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.3GMDyQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:13.802 ThaliTest[1538:3258897] client: lost peer: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.802 ThaliTest[1538:3258897] client session: onPeerLost: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.802 ThaliTest[1538:3258897] client sessio,n: onLinkFailure: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.802 ThaliTest[1538:3258897] client session: disconnect
2016-01-08 17:57:13.803 ThaliTest[1538:3258897] client session: stateChange:1->0 Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.804 Thali,Test[1538:3258897] client session: fireConnectCallback: Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:13.804 ThaliTest[1538:3258897] jxcore: connect: fail: Peer disconnected
2016-01-08T16:57:13.806Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-08T16:57:13.806Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T16:57:13.807Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.vqNzbw==","peerName":"(null)","peerAvailable":false}]
,2016-01-08T16:57:18.812Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:18.813Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:23.819 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:23.820 ThaliTest[1538:3259116] jxcore: disconnect: fail
2016-01-08T16:57:23.821Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
20,16-01-08T16:57:23.821Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
2016-01-08T16:57:23.821Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:23.822Z SendDataConnector.js: do connect now
,2016-01-08 17:57:23.823 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:23.824 ThaliTest[1538:3259116] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:23.824 ThaliTest[1538:3259116] jxcore: connect: fail: Peer unreachable
2016-01-08T16:57:23.825Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T16:57:23.825Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:23.825Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T16:57:28.826Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:28.827Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:33.830 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:33.830 ThaliTest[1538:3259116] jxcore: disconnect: fail
2016-01-08T16:57:33.831Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
20,16-01-08T16:57:33.831Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
2016-01-08T16:57:33.831Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:33.832Z SendDataConnector.js: do connect now
,2016-01-08 17:57:33.832 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:33.833 ThaliTest[1538:3259116] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:33.834 ThaliTest[1538:3259116] jxcore: connect,: fail: Peer unreachable
2016-01-08T16:57:33.834Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:33.835Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:33.835Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08 17:57:36.573 ThaliTest[1538:3258897] multipeer session: restart
,2016-01-08 17:57:36.615 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:57:36.616 ThaliTest[1538:3258897] client: found peer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:36.616 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.PGcCxg==
,2016-01-08T16:57:38.836Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:38.836Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:43.502 ThaliTest[1538:3258897] client: lost peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:43.502 ThaliTest[1538:3258897] client session: onPeerLost: Apple-Iphone5s-1.PGcCxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 17:57:43.842 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:43.842 ThaliTest[1538:3259116] jxcore: disconnect: fail
2016-01-08T16:57:43.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
20,16-01-08T16:57:43.843Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
2016-01-08T16:57:43.843Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:43.844Z SendDataConnector.js: do connect now
,2016-01-08 17:57:43.845 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:43.845 ThaliTest[1538:3259116] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:43.846 ThaliTest[1538:3259116] jxcore: connect,: fail: Peer unreachable
2016-01-08T16:57:43.846Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:43.847Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T16:57:43.847Z SendDataConnector.js:, tryAgain afer: 5000 ms.
,2016-01-08T16:57:48.853Z SendDataConnector.js: re-try now : Apple-Iphone5-1.vqNzbw==
,2016-01-08T16:57:48.854Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.vqNzbw==
,2016-01-08 17:57:49.100 ThaliTest[1538:3258897] multipeer session: reset timer
2016-01-08 17:57:49.100 ThaliTest[1538:3258897] multipeer session: stop timer
2016-01-08 17:57:49.100 ThaliTest[1538:3258897] multipeer session: start timer: 0x163e8930
2016-,01-08 17:57:49.101 ThaliTest[1538:3258897] server session: connect
2016-01-08 17:57:49.101 ThaliTest[1538:3258897] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 17:57:49.111 ThaliTest[1538:3258897] server: accepting invitation Apple-Iphone5-1
,2016-01-08 17:57:50.651 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.PGcCxg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.PGcCxg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 17:57:51.902 ThaliTest[1538:3260502] server session: connected
,2016-01-08 17:57:51.902 ThaliTest[1538:3260502] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 17:57:51.937 ThaliTest[1538:3258897] server relay: connected (to port: 64899)
,2016-01-08T16:57:51.947Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:57:52.950Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T16:57:52.965Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-08T16:57:52.985Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-08T16:57:52.999Z SendDataTCPServer.js: TCP/IP server has received 44895 bytes of data
,2016-01-08T16:57:53.013Z SendDataTCPServer.js: TCP/IP server has received 52489 bytes of data
,2016-01-08T16:57:53.029Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-08T16:57:53.045Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T16:57:53.058Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T16:57:53.075Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-08T16:57:53.088Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:57:53.171 ThaliTest[1538:3260518] server session: not connected Apple-Iphone5-1
,2016-01-08 17:57:53.798 ThaliTest[1538:3258897] multipeer session: reset timer
2016-01-08 17:57:53.798 ThaliTest[1538:3258897] multipeer session: stop timer
2016-01-08 17:57:53.799 ThaliTest[1538:3258897] multipeer session: start timer: 0x163e8930
2016-,01-08 17:57:53.799 ThaliTest[1538:3258897] server session: connect
2016-01-08 17:57:53.799 ThaliTest[1538:3258897] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 17:57:53.809 ThaliTest[1538:3258897] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 17:57:53.859 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:53.862 ThaliTest[1538:3259116] jxcore: disconnect: fail
2016-01-08T16:57:53.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
20,16-01-08T16:57:53.863Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.vqNzbw== with availability status: true
2016-01-08T16:57:53.863Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.vqNzbw==
2016-01-08T16:57:53.86,3Z SendDataConnector.js: do connect now
2016-01-08 17:57:53.864 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:53.864 ThaliTest[1538:3259116] client: connect: unreachable Apple-Iphone5-1.vqNzbw==
2016-01-08 17:57:53.86,4 ThaliTest[1538:3259116] jxcore: connect: fail: Peer unreachable
2016-01-08T16:57:53.868Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T16:57:53.869Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRo,undDownNow
2016-01-08T16:57:53.872Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 17:57:53.873 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:53.874 ThaliTest[1538:3259116] jxcore: disconnect: fail
2016-01-08T16:57:53.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.vqNzbw==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:53.877Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:53.877Z SendDataConnector.js: doConnect called with peer App,le-IpadAir2-1.lYAIVQ==
2016-01-08T16:57:53.878Z SendDataConnector.js: do connect now
,2016-01-08 17:57:53.878 ThaliTest[1538:3259116] jxcore: connect Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:53.880 ThaliTest[1538:3259116] client session: connect
2016-01-08 17:57:53.880 ThaliTest[1538:3259116] client session: stateChange:0->1 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:54.329 ThaliTest[1538:3258897] multipeer session: reset timer
2016-01-08 17:57:54.329 ThaliTest[1538:3258897] multipeer session: stop timer
2016-01-08 17:57:54.329 ThaliTest[1538:3258897] multipeer session: start timer: 0x163e8930
2016-,01-08 17:57:54.330 ThaliTest[1538:3258897] server session: connect
2016-01-08 17:57:54.330 ThaliTest[1538:3258897] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 17:57:54.339 ThaliTest[1538:3258897] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 17:57:56.415 ThaliTest[1538:3260518] server session: connected
2016-01-08 17:57:56.415 ThaliTest[1538:3260518] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 17:57:56.422 ThaliTest[1538:3258897] server relay: connected (to port: 64899)
,2016-01-08T16:57:56.431Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:57:56.924Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-08T16:57:56.937Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-08T16:57:56.953Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-08T16:57:56.968Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-08T16:57:56.984Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2016-01-08T16:57:56.998Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-08T16:57:57.014Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2016-01-08T16:57:57.030Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-08T16:57:57.043Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-08T16:57:57.054Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-08T16:57:57.069Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:57:57.120 ThaliTest[1538:3260503] server session: not connected Apple-Iphone5s-1
,2016-01-08 17:57:57.680 ThaliTest[1538:3260503] client session: connected
2016-01-08 17:57:57.681 ThaliTest[1538:3260503] client session: stateChange:1->2 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:57.685 ThaliTest[1538:3260503] client session: fireConnectCallback: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:57.685 ThaliTest[1538:3260503] jxcore: connect: success
2016-01-08T16:57:57.686Z SendDataConnector.js: CLIENT connected to 649,05, error: null
2016-01-08T16:57:57.687Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:57:57.690 ThaliTest[1538:3258897] client: relay established
2016-01-08 17:57:57.691 ThaliTest[1538:3258897] client: new accepted socket: 0x16444960
,2016-01-08T16:57:57.707Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 17:57:58.064 ThaliTest[1538:3260502] server session: connected
,2016-01-08 17:57:58.064 ThaliTest[1538:3260502] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 17:57:58.069 ThaliTest[1538:3258897] server relay: connected (to port: 64899)
,2016-01-08T16:57:58.177Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T16:57:58.508Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-08T16:57:58.522Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2016-01-08T16:57:58.525Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:57:58.527Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T16:57:58.527Z SendDataConnector.js: CLIENT Stop now
2016-01-08T16:57:5,8.527Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:57:58.529 ThaliTest[1538:3259116] jxcore: disconnect
2016-01-08 17:57:58.529 ThaliTest[1538:3259116] client session: disconnectFromPeer: Apple-IpadAir2-1.lYAIVQ==
2016-01-08 17:57:58.530 ThaliTest[1538:3259116] client session: disconnect
2,016-01-08 17:57:58.530 ThaliTest[1538:3259116] client session: stateChange:2->0 Apple-IpadAir2-1.lYAIVQ==
,2016-01-08 17:57:58.546 ThaliTest[1538:3259116] jxcore: disconnect: success
2016-01-08T16:57:58.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.lYAIVQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5s-1.PGcCxg==
2016-01-08T16:57:58.547Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.PGcCxg==
2016-01-08T16:57:58.548Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.PGcCxg==
2016-01-08T16:57:58.548Z SendDataConnector.js: do connect now
2016-01-08 17:57:58.548 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:57:58.548 ThaliTest[1538:3259116] client session: connect
2016-01-08 17:57:58.548 ThaliTest[1538:3259116] client session: state,Change:0->1 Apple-Iphone5s-1.PGcCxg==
,2016-01-08T16:57:58.578Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 17:57:58.600 ThaliTest[1538:3260501] server session: not connected Apple-IpadAir2-1
,2016-01-08 17:58:01.351 ThaliTest[1538:3260546] client session: connected
2016-01-08 17:58:01.351 ThaliTest[1538:3260546] client session: stateChange:1->2 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:01.367 ThaliTest[1538:3260560] client session: fireConnectCallback: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:58:01.367 ThaliTest[1538:3260560] jxcore: connect: success
2016-01-08T16:58:01.368Z SendDataConnector.js: CLIENT connected to 64909, error: null
2016-01-08T16:58:01.369Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:01.372 ThaliTest[1538:3258897] client: relay established
2016-01-08 17:58:01.373 ThaliTest[1538:3258897] client: new accepted socket: 0x16454950
,2016-01-08T16:58:01.386Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:58:02.070Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T16:58:02.121Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T16:58:02.121Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T16:58:02.122Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:58:02.122Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:02.122 ThaliTest[1538:3259116] jxcore: disconnect
,2016-01-08 17:58:02.123 ThaliTest[1538:3259116] client session: disconnectFromPeer: Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:02.123 ThaliTest[1538:3259116] client session: disconnect
,2016-01-08 17:58:02.124 ThaliTest[1538:3259116] client session: stateChange:2->0 Apple-Iphone5s-1.PGcCxg==
,2016-01-08 17:58:02.191 ThaliTest[1538:3259116] jxcore: disconnect: success
,2016-01-08T16:58:02.192Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.PGcCxg==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:58:02.194Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:58:02.194Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kBkHjQ==
,2016-01-08T16:58:02.194Z SendDataConnector.js: do connect now
,2016-01-08 17:58:02.195 ThaliTest[1538:3259116] jxcore: connect Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:02.195 ThaliTest[1538:3259116] client session: connect
,2016-01-08 17:58:02.196 ThaliTest[1538:3259116] client session: stateChange:0->1 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:04.950 ThaliTest[1538:3260503] client session: connected
2016-01-08 17:58:04.951 ThaliTest[1538:3260503] client session: stateChange:1->2 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:05.014 ThaliTest[1538:3260546] client session: fireConnectCallback: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:05.014 ThaliTest[1538:3260546] jxcore: connect: success
2016-01-08T16:58:05.016Z SendDataConnector.js: CLIENT connected to 64912, error: null
,2016-01-08T16:58:05.016Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 17:58:05.020 ThaliTest[1538:3258897] client: relay established
2016-01-08 17:58:05.021 ThaliTest[1538:3258897] client: new accepted socket: 0x1630d070
,2016-01-08T16:58:05.033Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T16:58:05.608Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T16:58:05.659Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T16:58:05.803Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T16:58:05.803Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T16:58:05.804Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:58:05.804Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:05.804 ThaliTest[1538:3259116] jxcore: disconnect
,2016-01-08 17:58:05.805 ThaliTest[1538:3259116] client session: disconnectFromPeer: Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:05.805 ThaliTest[1538:3259116] client session: disconnect
,2016-01-08 17:58:05.806 ThaliTest[1538:3259116] client session: stateChange:2->0 Apple-Iphone5-1.kBkHjQ==
,2016-01-08 17:58:05.873 ThaliTest[1538:3259116] jxcore: disconnect: success
,2016-01-08T16:58:05.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kBkHjQ==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T16:58:05.891Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T16:58:05.891Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 17:58:24.331 ThaliTest[1538:3258897] multipeer session: restart
,2016-01-08 17:58:24.376 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5-1.kBkHjQ==
2016-01-08 17:58:24.376 ThaliTest[1538:3258897] client: found peer: Apple-Iphone5s-1.PGcCxg==
2016-01-08 17:58:24.377 ThaliTest[1538:3258897] client: found peer: Apple-IpadAir2-1.lYAIVQ==
,teardown
,testSendData stopped
,2016-01-08 17:58:37.550 ThaliTest[1538:3259116] jxcore: stopBroadcasting
2016-01-08 17:58:37.551 ThaliTest[1538:3259116] THEMultipeerSession stopping peer
2016-01-08 17:58:37.552 ThaliTest[1538:3259116] multipeer session: stop timer
2016-01-08 17:58:37.,552 ThaliTest[1538:3259116] server session: disconnect
2016-01-08 17:58:37.553 ThaliTest[1538:3259116] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 17:58:37.561 ThaliTest[1538:3259116] server session: disconnect
2016-01-08 17:58:37.561 ThaliTest[1538:3259116] server session: stateChange:2->0 Apple-Iphone5-1
2016-01-08 17:58:37.568 ThaliTest[1538:3259116] server session: disconnect
,2016-01-08 17:58:37.568 ThaliTest[1538:3259116] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 17:58:37.590 ThaliTest[1538:3259116] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
