#### Test 5507315224df3aa_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4DDD4EF1-4E94-4373-B2B6-8BF5CEAEFFAE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4DDD4EF1-4E94-4373-B2B6-8BF5CEAEFFAE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/ED712EC3-2C3A-4E88-8DE7-BE414D2579D0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65054"
,(lldb)     command script import "/tmp/4DDD4EF1-4E94-4373-B2B6-8BF5CEAEFFAE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 16:43:37.601 ThaliTest[1314:2818893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9E4A331-8D99-43EC-B624-31B403BF0C81/Library/Cookies/Cookies.binarycookies
,2016-01-05 16:43:38.012 ThaliTest[1314:2818893] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 16:43:38.014 ThaliTest[1314:2818893] Multi-tasking -> Device: YES, App: YES
,2016-01-05 16:43:38.025 ThaliTest[1314:2818893] Unlimited access to network resources
,2016-01-05 16:43:38.039 ThaliTest[1314:2818893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 16:43:47.165 ThaliTest[1314:2818893] Resetting plugins due to page load.
,2016-01-05 16:43:50.807 ThaliTest[1314:2818893] Finished load of: file:///var/mobile/Containers/Bundle/Application/ED712EC3-2C3A-4E88-8DE7-BE414D2579D0/ThaliTest.app/www/index.html
,2016-01-05 16:43:50.988 ThaliTest[1314:2818893] JXcore Cordova plugin initializing
,2016-01-05 16:43:50.989 ThaliTest[1314:2819104] JXcore instance initializing
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
,2016-01-05 16:43:52.074 ThaliTest[1314:2818893] THREAD WARNING: ['JXcore'] took '79.941895' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 16:48:38.839 ThaliTest[1314:2819104] jxcore: startBroadcasting
,2016-01-05 16:48:38.855 ThaliTest[1314:2819104] server: starting Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:38.856 ThaliTest[1314:2819104] multipeer session: start timer: 0x15c7ed70
,2016-01-05 16:48:38.858 ThaliTest[1314:2819104] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-05 16:48:38.858 ThaliTest[1314:2819104] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 16:48:39.895 ThaliTest[1314:2818893] client: found peer: Apple-IpadAir2-1.S4dItg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.S4dItg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.S4dItg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-05 16:48:42.039 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5-1.uykjrA==
,2016-01-05 16:48:43.179 ThaliTest[1314:2818893] multipeer session: reset timer
2016-01-05 16:48:43.180 ThaliTest[1314:2818893] multipeer session: stop timer
2016-01-05 16:48:43.180 ThaliTest[1314:2818893] multipeer session: start timer: 0x15c7ed70
,2016-01-05 16:48:43.180 ThaliTest[1314:2818893] server session: connect
,2016-01-05 16:48:43.181 ThaliTest[1314:2818893] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 16:48:43.193 ThaliTest[1314:2818893] server: accepting invitation Apple-IpadAir2-1
,teardown
,testFindPeers stopped
,2016-01-05 16:48:43.421 ThaliTest[1314:2819104] jxcore: stopBroadcasting
2016-01-05 16:48:43.421 ThaliTest[1314:2819104] THEMultipeerSession stopping peer
2016-01-05 16:48:43.421 ThaliTest[1314:2819104] multipeer session: stop timer
2016-01-05 16:48:43.,422 ThaliTest[1314:2819104] server session: disconnect
2016-01-05 16:48:43.422 ThaliTest[1314:2819104] server session: stateChange:1->0 Apple-IpadAir2-1
2016-01-05 16:48:43.423 ThaliTest[1314:2819104] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 63188
,2016-01-05 16:48:43.498 ThaliTest[1314:2819104] jxcore: startBroadcasting
,2016-01-05 16:48:43.501 ThaliTest[1314:2819104] server: starting Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:48:43.503 ThaliTest[1314:2819104] multipeer session: start timer: 0x15b53930
,2016-01-05 16:48:43.503 ThaliTest[1314:2819104] THEMultipeerSession initialized peer Apple-Iphone6-1
,2016-01-05 16:48:43.504 ThaliTest[1314:2819104] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-05T15:48:43.510Z SendDataTCPServer.js: TCP/IP server is bound to port: 63188
,2016-01-05 16:48:43.588 ThaliTest[1314:2818893] client: found peer: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:43.589 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==,","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1.DocMgw==
2016-01-05T15:48:43.591Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DocMgw==
2016-01-05T15:48:4,3.592Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
2016-01-05T15:48:43.592Z SendDataConnector.js: do connect now
2016-01-05 16:48:43.593 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:43.5,93 ThaliTest[1314:2819104] client session: connect
2016-01-05 16:48:43.593 ThaliTest[1314:2819104] client session: stateChange:0->1 Apple-Iphone6-1.DocMgw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:43.626 ThaliTest[1314:2818893] client: found peer: Apple-IpadAir2-1.xC8Jhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:43.944 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5s-1.lzdGtw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.lzdGtw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:44.553 ThaliTest[1314:2818893] client: lost peer: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.553 ThaliTest[1314:2818893] client session: onPeerLost: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.553 ThaliTest[1314:2818893] client sessio,n: onLinkFailure: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.554 ThaliTest[1314:2818893] client session: disconnect
2016-01-05 16:48:44.554 ThaliTest[1314:2818893] client session: stateChange:1->0 Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.554 Thali,Test[1314:2818893] client session: fireConnectCallback: Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:44.555 ThaliTest[1314:2818893] jxcore: connect: fail: Peer disconnected
2016-01-05T15:48:44.556Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-05T15:48:44.557Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T15:48:44.557Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DocMgw==","peerName":",(null)","peerAvailable":false}]
,2016-01-05 16:48:44.647 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5-1.cnOsew==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.cnOsew==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 16:48:47.844 ThaliTest[1314:2818893] client: lost peer: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:47.845 ThaliTest[1314:2818893] client session: onPeerLost: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.u,ykjrA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05T15:48:49.562Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:49.563Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:54.566 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:48:54.566 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:48:54.567Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
20,16-01-05T15:48:54.568Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:48:54.568Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:54.568Z SendDataConnector.js: do connect now
,2016-01-05 16:48:54.569 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone6-1.DocMgw==
,2016-01-05 16:48:54.571 ThaliTest[1314:2819104] client: connect: unreachable Apple-Iphone6-1.DocMgw==
2016-01-05 16:48:54.572 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
2016-01-05T15:48:54.572Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-05T15:48:54.573Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:48:54.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:48:59.581Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:48:59.581Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:04.592 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:04.593 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:04.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
20,16-01-05T15:49:04.594Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:49:04.594Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
2016-01-05T15:49:04.59,5Z SendDataConnector.js: do connect now
,2016-01-05 16:49:04.595 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:04.596 ThaliTest[1314:2819104] client: connect: unreachable Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:04.596 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:04.598Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:04.598Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:04.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:09.601Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:09.602Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:13.504 ThaliTest[1314:2818893] multipeer session: restart
,2016-01-05 16:49:14.612 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:14.612 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:14.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
20,16-01-05T15:49:14.613Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:49:14.614Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:14.614Z SendDataConnector.js: do connect now
,2016-01-05 16:49:14.615 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:14.616 ThaliTest[1314:2819104] client: connect: unreachable Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:14.617 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:14.617Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:14.618Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:14.619Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:19.622Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:19.623Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05 16:49:24.635 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:24.636 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:24.636Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
20,16-01-05T15:49:24.636Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.DocMgw== with availability status: true
2016-01-05T15:49:24.637Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DocMgw==
,2016-01-05T15:49:24.637Z SendDataConnector.js: do connect now
,2016-01-05 16:49:24.638 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:24.640 ThaliTest[1314:2819104] client: connect: unreachable Apple-Iphone6-1.DocMgw==
2016-01-05 16:49:24.640 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:24.640Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:24.641Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-05T15:49:24.644Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 16:49:24.645 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:24.645 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:24.646Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DocMgw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:24.650Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:24.651Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:24.652Z SendDataConnector.js: do connect now
,2016-01-05 16:49:24.653 ThaliTest[1314:2819104] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.654 ThaliTest[1314:2819104] client session: connect
2016-01-05 16:49:24.654 ThaliTest[1314:2819104] client session: stateChange:0->1 Apple-IpadA,ir2-1.xC8Jhw==
,2016-01-05 16:49:24.667 ThaliTest[1314:2818893] client: lost peer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.667 ThaliTest[1314:2818893] client session: onPeerLost: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.667 ThaliTest[1314:2818893] client sess,ion: onLinkFailure: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.667 ThaliTest[1314:2818893] client session: disconnect
2016-01-05 16:49:24.668 ThaliTest[1314:2818893] client session: stateChange:1->0 Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.668 T,haliTest[1314:2818893] client session: fireConnectCallback: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:24.669 ThaliTest[1314:2818893] jxcore: connect: fail: Peer disconnected
2016-01-05T15:49:24.670Z SendDataConnector.js: CLIENT connected to 0, error: Pe,er disconnected
2016-01-05T15:49:24.670Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T15:49:24.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerN,ame":"(null)","peerAvailable":false}]
,2016-01-05T15:49:29.677Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:29.678Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:30.220 ThaliTest[1314:2818893] multipeer session: reset timer
2016-01-05 16:49:30.221 ThaliTest[1314:2818893] multipeer session: stop timer
2016-01-05 16:49:30.221 ThaliTest[1314:2818893] multipeer session: start timer: 0x15b53930
2016-,01-05 16:49:30.221 ThaliTest[1314:2818893] server session: connect
2016-01-05 16:49:30.222 ThaliTest[1314:2818893] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-05 16:49:30.229 ThaliTest[1314:2818893] server: accepting invitation Apple-IpadAi,r2-1
,2016-01-05 16:49:31.796 ThaliTest[1314:2818893] multipeer session: reset timer
,2016-01-05 16:49:31.796 ThaliTest[1314:2818893] multipeer session: stop timer
2016-01-05 16:49:31.796 ThaliTest[1314:2818893] multipeer session: start timer: 0x15b53930
2016-01-05 16:49:31.797 ThaliTest[1314:2818893] server session: connect
2016-01-05 1,6:49:31.797 ThaliTest[1314:2818893] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 16:49:31.807 ThaliTest[1314:2818893] server: accepting invitation Apple-Iphone5s-1
,2016-01-05 16:49:33.484 ThaliTest[1314:2818893] multipeer session: reset timer
2016-01-05 16:49:33.485 ThaliTest[1314:2818893] multipeer session: stop timer
2016-01-05 16:49:33.485 ThaliTest[1314:2818893] multipeer session: start timer: 0x15b53930
2016-01-05 16:49:33.486 ThaliTest[1314:2818893] server session: connect
2016-01-05 16:49:33.486 ThaliTest[1314:2818893] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 16:49:33.495 ThaliTest[1314:2818893] server: accepting invitation Apple-Iphone5-1
,2016-01-05 16:49:34.435 ThaliTest[1314:2819714] server session: connected
2016-01-05 16:49:34.435 ThaliTest[1314:2819714] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 16:49:34.457 ThaliTest[1314:2818893] server relay: connected (to port: 63188)
2016-01-05T15:49:34.459Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 16:49:34.684 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:34.685 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:34.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
2,016-01-05T15:49:34.686Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.xC8Jhw== with availability status: true
2016-01-05T15:49:34.686Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:34.686Z SendDataConnector.js: do connect now
2016-01-05 16:49:34.687 ThaliTest[1314:2819104] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:34.688 ThaliTest[1314:2819104] client: connect: unreachable Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:34.688 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:34.689Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:34.690Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:34.690Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:34.934Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-05T15:49:34.948Z SendDataTCPServer.js: TCP/IP server has received 19284 bytes of data
,2016-01-05T15:49:34.969Z SendDataTCPServer.js: TCP/IP server has received 41326 bytes of data
,2016-01-05T15:49:34.990Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2016-01-05 16:49:34.998 ThaliTest[1314:2819729] server session: connected
2016-01-05 16:49:34.998 ThaliTest[1314:2819729] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05T15:49:35.007Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
2016-01-05 16:49:35.011 ThaliTest[1314:2818893] server relay: connected (to port: 63188)
,2016-01-05T15:49:35.023Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 16:49:35.054 ThaliTest[1314:2819714] server session: not connected Apple-IpadAir2-1
,2016-01-05T15:49:35.310Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-05T15:49:35.323Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-05T15:49:35.339Z SendDataTCPServer.js: TCP/IP server has received 48038 bytes of data
,2016-01-05T15:49:35.357Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-05T15:49:35.374Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-05T15:49:35.392Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
,2016-01-05T15:49:35.409Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:35.485 ThaliTest[1314:2819731] server session: not connected Apple-Iphone5s-1
,2016-01-05 16:49:36.023 ThaliTest[1314:2819731] server session: connected
2016-01-05 16:49:36.024 ThaliTest[1314:2819731] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05 16:49:36.031 ThaliTest[1314:2818893] server relay: connected (to port: 63188)
2016-01-05T15:49:36.036Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:36.534Z SendDataTCPServer.js: TCP/IP server has received 21474 bytes of data
,2016-01-05T15:49:36.548Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-05T15:49:36.566Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-05T15:49:36.579Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-05T15:49:36.594Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-05T15:49:36.608Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:36.655 ThaliTest[1314:2819714] server session: not connected Apple-Iphone5-1
,2016-01-05T15:49:39.637Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:39.638Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:44.643 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:44.644 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:44.644Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
2,016-01-05T15:49:44.645Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.xC8Jhw== with availability status: true
2016-01-05T15:49:44.645Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:44.645Z SendDataConnector.js: do connect now
,2016-01-05 16:49:44.646 ThaliTest[1314:2819104] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:44.647 ThaliTest[1314:2819104] client: connect: unreachable Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:44.648 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:44.649Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2016-01-05T15:49:44.649Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:44.649Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:49.654Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:49.655Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:54.657 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:49:54.658 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:49:54.658Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
2,016-01-05T15:49:54.659Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.xC8Jhw== with availability status: true
2016-01-05T15:49:54.659Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:54.659Z SendDataConnector.js: do connect now
,2016-01-05 16:49:54.660 ThaliTest[1314:2819104] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:54.660 ThaliTest[1314:2819104] client: connect: unreachable Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:54.661 ThaliTest[1314:2819104] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:49:54.662Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:54.663Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:54.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:59.673Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:49:59.674Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:03.433 ThaliTest[1314:2818893] multipeer session: restart
,2016-01-05 16:50:03.472 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5-1.cnOsew==
2016-01-05 16:50:03.473 ThaliTest[1314:2818893] client: found peer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:03.473 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5s-1.lzdGtw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerName":"(null)","peerAvailable":true}]
,2016-01-05 16:50:04.682 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:50:04.682 ThaliTest[1314:2819104] jxcore: disconnect: fail
2016-01-05T15:50:04.683Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
2,016-01-05T15:50:04.683Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.xC8Jhw== with availability status: true
2016-01-05T15:50:04.684Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
,2016-01-05T15:50:04.684Z SendDataConnector.js: do connect now
,2016-01-05 16:50:04.685 ThaliTest[1314:2819104] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:04.687 ThaliTest[1314:2819104] client session: connect
2016-01-05 16:50:04.687 ThaliTest[1314:2819104] client session: stateChange:0->1 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:07.964 ThaliTest[1314:2820094] client session: connected
,2016-01-05 16:50:07.964 ThaliTest[1314:2820094] client session: stateChange:1->2 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:07.971 ThaliTest[1314:2820094] client session: fireConnectCallback: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:07.972 ThaliTest[1314:2820094] jxcore: connect: success
2016-01-05T15:50:07.973Z SendDataConnector.js: CLIENT connected to 63199, error: null
2016-01-05T15:50:07.973Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:50:07.977 ThaliTest[1314:2818893] client: relay established
2016-01-05 16:50:07.977 ThaliTest[1314:2818893] client: new accepted socket: 0x15c9a460
,2016-01-05T15:50:07.993Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:50:08.276Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T15:50:08.313Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T15:50:08.325Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:50:08.325Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T15:50:08.326Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:50:08.326Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:50:08.327 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:50:08.327 ThaliTest[1314:2819104] client session: disconnectFromPeer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:08.327 ThaliTest[1314:2819104] client session: disconnect
,2016-01-05 16:50:08.328 ThaliTest[1314:2819104] client session: stateChange:2->0 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:08.392 ThaliTest[1314:2819104] jxcore: disconnect: success
,2016-01-05T15:50:08.393Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1.lzdGtw==
,2016-01-05T15:50:08.394Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.lzdGtw==
,2016-01-05T15:50:08.394Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.lzdGtw==
,2016-01-05T15:50:08.394Z SendDataConnector.js: do connect now
,2016-01-05 16:50:08.395 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:08.395 ThaliTest[1314:2819104] client session: connect
,2016-01-05 16:50:08.396 ThaliTest[1314:2819104] client session: stateChange:0->1 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:11.084 ThaliTest[1314:2820094] client session: connected
2016-01-05 16:50:11.085 ThaliTest[1314:2820094] client session: stateChange:1->2 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:11.096 ThaliTest[1314:2820092] client session: fireConnectCallback: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:50:11.096 ThaliTest[1314:2820092] jxcore: connect: success
2016-01-05T15:50:11.098Z SendDataConnector.js: CLIENT connected to 632,02, error: null
2016-01-05T15:50:11.098Z SendDataConnector.js: CLIENT starting client 
2016-01-05 16:50:11.102 ThaliTest[1314:2818893] client: relay established
2016-01-05 16:50:11.103 ThaliTest[1314:2818893] client: new accepted socket: 0x15b5a240
,2016-01-05T15:50:11.114Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:50:11.580Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T15:50:11.591Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T15:50:11.617Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:50:11.630Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:50:11.630Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T15:50:11.631Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:50:11.631Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:50:11.632 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:50:11.632 ThaliTest[1314:2819104] client session: disconnectFromPeer: Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:50:11.632 ThaliTest[1314:2819104] client session: disconnect
2016-01-05 16:50:11.632 ThaliTest[1314:2819104] client session: stateChange:2->0 Apple-Iphone5s-1.lzdGtw==
,2016-01-05 16:50:11.636 ThaliTest[1314:2819104] jxcore: disconnect: success
2016-01-05T15:50:11.636Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.lzdGtw==
---- round done--------
startWithNextDevice
device[4]: Apple-Iph,one5-1.cnOsew==
2016-01-05T15:50:11.636Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.cnOsew==
2016-01-05T15:50:11.637Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.cnOsew==
2016-01-05T15:50:11.637Z SendDataConnector.js: do connect now
2016-01-05 16:50:11.637 ThaliTest[1314:2819104] jxcore: connect Apple-Iphone5-1.cnOsew==
2016-01-05 16:50:11.637 ThaliTest[1314:2819104] client session: connect
2016-01-05 16:50:11.637 ThaliTest[1314:2819104] client session: stateChange:0->1 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:50:13.884 ThaliTest[1314:2820094] client session: connected
2016-01-05 16:50:13.885 ThaliTest[1314:2820094] client session: stateChange:1->2 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:50:13.893 ThaliTest[1314:2820093] client session: fireConnectCallback: Apple-Iphone5-1.cnOsew==
2016-01-05 16:50:13.893 ThaliTest[1314:2820093] jxcore: connect: success
2016-01-05T15:50:13.896Z SendDataConnector.js: CLIENT connected to 6320,5, error: null
2016-01-05T15:50:13.897Z SendDataConnector.js: CLIENT starting client 
2016-01-05 16:50:13.901 ThaliTest[1314:2818893] client: relay established
2016-01-05 16:50:13.901 ThaliTest[1314:2818893] client: new accepted socket: 0x15b40630
,2016-01-05T15:50:13.913Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:50:14.198Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T15:50:14.220Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T15:50:14.232Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T15:50:14.245Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:50:14.257Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:50:14.258Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-05T15:50:14.258Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:50:14.258Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:50:14.259 ThaliTest[1314:2819104] jxcore: disconnect
2016-01-05 16:50:14.259 ThaliTest[1314:2819104] client session: disconnectFromPeer: Apple-Iphone5-1.cnOsew==
2016-01-05 16:50:14.259 ThaliTest[1314:2819104] client session: disconnect
2016-01-05 16:50:14.259 ThaliTest[1314:2819104] client session: stateChange:2->0 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:50:14.263 ThaliTest[1314:2819104] jxcore: disconnect: success
2016-01-05T15:50:14.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.cnOsew==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2016-01-05T15:50:14.266Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:50:14.266Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:50:33.433 ThaliTest[1314:2818893] multipeer session: restart
,2016-01-05 16:50:33.473 ThaliTest[1314:2818893] client: found peer: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:50:33.473 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5-1.cnOsew==
,2016-01-05 16:50:33.475 ThaliTest[1314:2818893] client: found peer: Apple-Iphone5s-1.lzdGtw==
,teardown
,testSendData stopped
2016-01-05 16:50:38.901 ThaliTest[1314:2819104] jxcore: stopBroadcasting
,2016-01-05 16:50:38.902 ThaliTest[1314:2819104] THEMultipeerSession stopping peer
2016-01-05 16:50:38.903 ThaliTest[1314:2819104] multipeer session: stop timer
2016-01-05 16:50:38.903 ThaliTest[1314:2819104] server session: disconnect
2016-01-05 16:50:38.903 ThaliTest[1314:2819104] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-05 16:50:38.915 ThaliTest[1314:2819104] server session: disconnect
2016-01-05 16:50:38.915 ThaliTest[1314:2819104] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-05 16:50:38.934 ThaliTest[1314:2819104] server session: disconnect
2016-01-05 16:50:38.935 ThaliTest[1314:2819104] server session: stateChange:2->0 Apple-Iphone5s-1
2016-01-05 16:50:38.942 ThaliTest[1314:2819104] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T15:50:38.961Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:38.963Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:38.965Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-05T15:50:38.966Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
