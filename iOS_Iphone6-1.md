#### Test 5531115118861c0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1A178C6F-B713-42DB-BBFB-ED1F5E025052/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1A178C6F-B713-42DB-BBFB-ED1F5E025052/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5AC5372E-F89B-4492-8CE6-19AFA6EBBE26/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49607"
,(lldb)     command script import "/tmp/1A178C6F-B713-42DB-BBFB-ED1F5E025052/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 10:42:31.068 ThaliTest[1432:3069378] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB86F767-3CB1-4BE3-91ED-FEE67CC782F8/Library/Cookies/Cookies.binarycookies
,2016-01-07 10:42:31.506 ThaliTest[1432:3069378] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 10:42:31.508 ThaliTest[1432:3069378] Multi-tasking -> Device: YES, App: YES
,2016-01-07 10:42:31.518 ThaliTest[1432:3069378] Unlimited access to network resources
,2016-01-07 10:42:31.531 ThaliTest[1432:3069378] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 10:42:40.514 ThaliTest[1432:3069378] Resetting plugins due to page load.
,2016-01-07 10:42:44.334 ThaliTest[1432:3069378] Finished load of: file:///var/mobile/Containers/Bundle/Application/5AC5372E-F89B-4492-8CE6-19AFA6EBBE26/ThaliTest.app/www/index.html
,2016-01-07 10:42:44.523 ThaliTest[1432:3069378] JXcore Cordova plugin initializing
,2016-01-07 10:42:44.525 ThaliTest[1432:3069600] JXcore instance initializing
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
,2016-01-07 10:42:45.603 ThaliTest[1432:3069378] THREAD WARNING: ['JXcore'] took '81.124023' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 10:47:29.720 ThaliTest[1432:3069600] jxcore: startBroadcasting
,2016-01-07 10:47:29.735 ThaliTest[1432:3069600] server: starting Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:29.736 ThaliTest[1432:3069600] multipeer session: start timer: 0x1942c500
2016-01-07 10:47:29.737 ThaliTest[1432:3069600] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-07 10:47:29.737 ThaliTest[1432:3069600] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-07 10:47:29.752 ThaliTest[1432:3069378] client: found peer: Apple-Iphone6-1.qqPEfA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.qqPEfA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-07 10:47:30.904 ThaliTest[1432:3069378] client: found peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:30.906 ThaliTest[1432:3069378] client: found peer: Apple-Iphone5-1.kLcgag==
,teardown
,testFindPeers stopped
,2016-01-07 10:47:33.326 ThaliTest[1432:3069600] jxcore: stopBroadcasting
2016-01-07 10:47:33.327 ThaliTest[1432:3069600] THEMultipeerSession stopping peer
2016-01-07 10:47:33.327 ThaliTest[1432:3069600] multipeer session: stop timer
2016-01-07 10:47:33.,328 ThaliTest[1432:3069600] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64040
,2016-01-07 10:47:33.375 ThaliTest[1432:3069600] jxcore: startBroadcasting
,2016-01-07 10:47:33.381 ThaliTest[1432:3069600] server: starting Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:47:33.382 ThaliTest[1432:3069600] multipeer session: start timer: 0x19374340
2016-01-07 10:47:33.383 ThaliTest[1432:3069600] THEMultipeerSession initi,alized peer Apple-Iphone6-1
2016-01-07 10:47:33.383 ThaliTest[1432:3069600] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-07T09:47:33.390Z SendDataTCPServer.js: TCP/IP server is bound to port: 64040
,2016-01-07 10:47:33.408 ThaliTest[1432:3069378] client: found peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:33.408 ThaliTest[1432:3069378] client: found peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 10:47:33.409 ThaliTest[1432:3069378] client: found peer:, Apple-Iphone6-1.W/Fi/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:,33.411Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:33.412Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:33.412Z SendDataConnector.js: do connect now
2016-01-07 1,0:47:33.412 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:33.413 ThaliTest[1432:3069600] client session: connect
2016-01-07 10:47:33.413 ThaliTest[1432:3069600] client session: stateChange:0->1 Apple-IpadAir2-1.1I3u2,A==
2016-01-07 10:47:33.416 ThaliTest[1432:3069378] client: found peer: Apple-Iphone5-1.kLcgag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:34.619 ThaliTest[1432:3069378] client: lost peer: Apple-Iphone6-1.W/Fi/g==
2016-01-07 10:47:34.619 ThaliTest[1432:3069378] client session: onPeerLost: Apple-Iphone6-1.W/Fi/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.W/Fi/g==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07 10:47:35.056 ThaliTest[1432:3069378] client: lost peer: Apple-Iphone5-1.kLcgag==
2016-01-07 10:47:35.058 ThaliTest[1432:3069378] client session: onPeerLost: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.k,Lcgag==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07 10:47:35.091 ThaliTest[1432:3069378] client: found peer: Apple-IpadAir2-1.CdHxkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.CdHxkA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:35.098 ThaliTest[1432:3069378] client: found peer: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:47:35.100 ThaliTest[1432:3069378] client: found peer: Apple-Iphone5-1.XzilZw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.XzilZw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:35.664 ThaliTest[1432:3069378] client: lost peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.665 ThaliTest[1432:3069378] client session: onPeerLost: Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:35.665 ThaliTest[1432:3069378] client session: onLinkFailure: Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:35.666 ThaliTest[1432:3069378] client session: disconnect
,2016-01-07 10:47:35.667 ThaliTest[1432:3069378] client session: stateChange:1->0 Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:35.670 ThaliTest[1432:3069378] client session: fireConnectCallback: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.670 ThaliTest[1432:3069378] jxcore: connect: fail: Peer disconnected
2016-01-07T09:47:35.672Z SendDataConnector.js: CLIENT ,connected to 0, error: Peer disconnected
2016-01-07T09:47:35.672Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:47:35.673Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ip,adAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":false}]
,2016-01-07T09:47:40.681Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:40.683Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:45.686 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:47:45.686 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:47:45.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:47:45.687Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:47:45.688Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:45.688Z SendDataConnector.js: do connect now
,2016-01-07 10:47:45.689 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:45.690 ThaliTest[1432:3069600] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:45.691 ThaliTest[1432:3069600] jxcore: connect: fail: Peer unreachable
2016-01-07T09:47:45.691Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2016-01-07T09:47:45.691Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:47:45.692Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:47:50.702Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:47:50.702Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:55.714 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:47:55.714 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:47:55.715Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:47:55.715Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:47:55.715Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:47:55.716Z SendDataConnector.js: do connect now
,2016-01-07 10:47:55.716 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:55.717 ThaliTest[1432:3069600] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:55.718 ThaliTest[1432:3069600] jxcore: conne,ct: fail: Peer unreachable
2016-01-07T09:47:55.718Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:47:55.719Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:47:55.719Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:00.724Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:00.725Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:03.384 ThaliTest[1432:3069378] multipeer session: restart
,2016-01-07 10:48:05.728 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:05.728 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:05.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:48:05.729Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:48:05.730Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:05.730Z SendDataConnector.js: do connect now
,2016-01-07 10:48:05.731 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:05.732 ThaliTest[1432:3069600] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:05.733 ThaliTest[1432:3069600] jxcore: connect: fail: Peer unreachable
2016-01-07T09:48:05.733Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2016-01-07T09:48:05.733Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:05.734Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:10.745Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.1I3u2A==
,2016-01-07T09:48:10.746Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:48:15.756 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:15.757 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:15.757Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
2,016-01-07T09:48:15.758Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1.1I3u2A== with availability status: true
2016-01-07T09:48:15.758Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.1I3u2A==
2016-01-07T09:48:15.758Z SendDataConnector.js: do connect now
,2016-01-07 10:48:15.759 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:15.760 ThaliTest[1432:3069600] client: connect: unreachable Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:48:15.761 ThaliTest[1432:3069600] jxcore: conne,ct: fail: Peer unreachable
2016-01-07T09:48:15.761Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:15.761Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-07T09:48:15.764Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 10:48:15.765 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:15.766 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:15.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.1I3u2A==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:15.770Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:15.771Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:15.771Z SendDataConnector.js: do connect now
,2016-01-07 10:48:15.772 ThaliTest[1432:3069600] jxcore: connect Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.773 ThaliTest[1432:3069600] client session: connect
2016-01-07 10:48:15.773 ThaliTest[1432:3069600] client session: stateChange:0->1 Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:15.786 ThaliTest[1432:3069378] client: lost peer: Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.786 ThaliTest[1432:3069378] client session: onPeerLost: Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.786 ThaliTest[1432:3069378] client sessio,n: onLinkFailure: Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.786 ThaliTest[1432:3069378] client session: disconnect
2016-01-07 10:48:15.787 ThaliTest[1432:3069378] client session: stateChange:1->0 Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.787 Thali,Test[1432:3069378] client session: fireConnectCallback: Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:15.788 ThaliTest[1432:3069378] jxcore: connect: fail: Peer disconnected
2016-01-07T09:48:15.789Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-07T09:48:15.789Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:48:15.790Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerName":"(null)","peerAvailable":false}]
,2016-01-07T09:48:20.794Z SendDataConnector.js: re-try now : Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:20.795Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:25.803 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:25.804 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:25.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.qqPEfA==
20,16-01-07T09:48:25.805Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.qqPEfA== with availability status: true
2016-01-07T09:48:25.805Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.qqPEfA==
2016-01-07T09:48:25.80,5Z SendDataConnector.js: do connect now
,2016-01-07 10:48:25.806 ThaliTest[1432:3069600] jxcore: connect Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:25.807 ThaliTest[1432:3069600] client: connect: unreachable Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:25.808 ThaliTest[1432:3069600] jxcore: connect: fail: Peer unreachable
2016-01-07T09:48:25.809Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:25.809Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:25.809Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:30.815Z SendDataConnector.js: re-try now : Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:30.816Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:31.710 ThaliTest[1432:3069378] multipeer session: reset timer
2016-01-07 10:48:31.711 ThaliTest[1432:3069378] multipeer session: stop timer
2016-01-07 10:48:31.711 ThaliTest[1432:3069378] multipeer session: start timer: 0x19374340
2016-01-07 10:48:31.712 ThaliTest[1432:3069378] server session: connect
2016-01-07 10:48:31.712 ThaliTest[1432:3069378] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-07 10:48:31.721 ThaliTest[1432:3069378] server: accepting invitation Apple-Iphone5-1
,2016-01-07 10:48:34.388 ThaliTest[1432:3070247] server session: connected
2016-01-07 10:48:34.389 ThaliTest[1432:3070247] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-07 10:48:34.411 ThaliTest[1432:3069378] server relay: connected (to port: 64040)
,2016-01-07T09:48:34.418Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:35.442Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-07T09:48:35.457Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-07T09:48:35.472Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-07T09:48:35.490Z SendDataTCPServer.js: TCP/IP server has received 40515 bytes of data
,2016-01-07T09:48:35.503Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-07T09:48:35.518Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-07T09:48:35.533Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-07T09:48:35.549Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-07T09:48:35.562Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-07T09:48:35.576Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:35.747 ThaliTest[1432:3070245] server session: not connected Apple-Iphone5-1
,2016-01-07 10:48:35.824 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:35.825 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:35.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.qqPEfA==
20,16-01-07T09:48:35.826Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.qqPEfA== with availability status: true
2016-01-07T09:48:35.827Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.qqPEfA==
2016-01-07T09:48:35.82,7Z SendDataConnector.js: do connect now
,2016-01-07 10:48:35.828 ThaliTest[1432:3069600] jxcore: connect Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:35.829 ThaliTest[1432:3069600] client: connect: unreachable Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:35.829 ThaliTest[1432:3069600] jxcore: connect,: fail: Peer unreachable
2016-01-07T09:48:35.830Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:35.830Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:35.830Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:40.843Z SendDataConnector.js: re-try now : Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:40.843Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:42.286 ThaliTest[1432:3069378] multipeer session: reset timer
2016-01-07 10:48:42.287 ThaliTest[1432:3069378] multipeer session: stop timer
2016-01-07 10:48:42.287 ThaliTest[1432:3069378] multipeer session: start timer: 0x19374340
2016-,01-07 10:48:42.287 ThaliTest[1432:3069378] server session: connect
2016-01-07 10:48:42.288 ThaliTest[1432:3069378] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-07 10:48:42.297 ThaliTest[1432:3069378] server: accepting invitation Apple-Iphone5s-1
,2016-01-07 10:48:44.894 ThaliTest[1432:3070286] server session: connected
2016-01-07 10:48:44.894 ThaliTest[1432:3070286] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-07 10:48:44.930 ThaliTest[1432:3069378] server relay: connected (to port: 64040)
,2016-01-07T09:48:44.942Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:45.405Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-07T09:48:45.418Z SendDataTCPServer.js: TCP/IP server has received 16425 bytes of data
,2016-01-07T09:48:45.435Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-07T09:48:45.535Z SendDataTCPServer.js: TCP/IP server has received 31755 bytes of data
,2016-01-07T09:48:45.550Z SendDataTCPServer.js: TCP/IP server has received 40515 bytes of data
,2016-01-07T09:48:45.564Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-07T09:48:45.582Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-07T09:48:45.600Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-07T09:48:45.615Z SendDataTCPServer.js: TCP/IP server has received 90885 bytes of data
,2016-01-07T09:48:45.632Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:45.698 ThaliTest[1432:3070286] server session: not connected Apple-Iphone5s-1
,2016-01-07 10:48:45.849 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:45.850 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:45.850Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:45.851Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.qqPEfA== with availability status: true
2016-01-07T09:48:45.852Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:45.852Z SendDataConnector.js: do connect now
,2016-01-07 10:48:45.854 ThaliTest[1432:3069600] jxcore: connect Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:45.854 ThaliTest[1432:3069600] client: connect: unreachable Apple-Iphone6-1.qqPEfA==
2016-01-07 10:48:45.854 ThaliTest[1432:3069600] jxcore: connect,: fail: Peer unreachable
2016-01-07T09:48:45.855Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:45.855Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:45.855Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07 10:48:48.552 ThaliTest[1432:3069378] multipeer session: reset timer
2016-01-07 10:48:48.552 ThaliTest[1432:3069378] multipeer session: stop timer
2016-01-07 10:48:48.553 ThaliTest[1432:3069378] multipeer session: start timer: 0x19374340
,2016-01-07 10:48:48.553 ThaliTest[1432:3069378] server session: connect
,2016-01-07 10:48:48.555 ThaliTest[1432:3069378] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-07 10:48:48.565 ThaliTest[1432:3069378] server: accepting invitation Apple-IpadAir2-1
,2016-01-07T09:48:50.864Z SendDataConnector.js: re-try now : Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:50.865Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:51.760 ThaliTest[1432:3070287] server session: connected
2016-01-07 10:48:51.760 ThaliTest[1432:3070287] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-07 10:48:52.281 ThaliTest[1432:3069378] server relay: connected (to port: 64040)
,2016-01-07T09:48:52.299Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:52.313Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2016-01-07T09:48:52.329Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-07T09:48:52.450Z SendDataTCPServer.js: TCP/IP server has received 35709 bytes of data
,2016-01-07T09:48:52.470Z SendDataTCPServer.js: TCP/IP server has received 99645 bytes of data
,2016-01-07 10:48:52.523 ThaliTest[1432:3070279] server session: not connected Apple-IpadAir2-1
,2016-01-07 10:48:55.867 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:55.868 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:55.868Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.qqPEfA==
20,16-01-07T09:48:55.869Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.qqPEfA== with availability status: true
2016-01-07T09:48:55.869Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.qqPEfA==
,2016-01-07T09:48:55.869Z SendDataConnector.js: do connect now
2016-01-07 10:48:55.870 ThaliTest[1432:3069600] jxcore: connect Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:55.871 ThaliTest[1432:3069600] client: connect: unreachable Apple-Iphone6-1.qqPEfA==
,2016-01-07 10:48:55.872 ThaliTest[1432:3069600] jxcore: connect: fail: Peer unreachable
2016-01-07T09:48:55.873Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:55.873Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
oneRoundDownNow
2016-01-07T09:48:55.874Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 10:48:55.874 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:48:55.875 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:48:55.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.qqPEfA==
---- round done--------
startWithNextDevice
,device[3]: Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:55.877Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:55.879Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:55.879Z SendDataConnector.js: do connect now
,2016-01-07 10:48:55.880 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.881 ThaliTest[1432:3069600] client session: connect
2016-01-07 10:48:55.881 ThaliTest[1432:3069600] client session: stateChange:0->1 Apple-IpadA,ir2-1.CdHxkA==
,2016-01-07 10:48:55.892 ThaliTest[1432:3069378] client: lost peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.892 ThaliTest[1432:3069378] client session: onPeerLost: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.893 ThaliTest[1432:3069378] client sess,ion: onLinkFailure: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.893 ThaliTest[1432:3069378] client session: disconnect
2016-01-07 10:48:55.893 ThaliTest[1432:3069378] client session: stateChange:1->0 Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.894 T,haliTest[1432:3069378] client session: fireConnectCallback: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:55.894 ThaliTest[1432:3069378] jxcore: connect: fail: Peer disconnected
2016-01-07T09:48:55.896Z SendDataConnector.js: CLIENT connected to 0, error: Pe,er disconnected
2016-01-07T09:48:55.897Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:48:55.897Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.CdHxkA==","peerName":"(null)","peerAvailable":false}]
,2016-01-07T09:49:00.905Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:49:00.906Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:49:05.914 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:49:05.914 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:49:05.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.CdHxkA==
2,016-01-07T09:49:05.915Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1.CdHxkA== with availability status: true
2016-01-07T09:49:05.916Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.CdHxkA==
2016-01-07T09:49:05,.916Z SendDataConnector.js: do connect now
,2016-01-07 10:49:05.916 ThaliTest[1432:3069600] jxcore: connect Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:49:05.917 ThaliTest[1432:3069600] client: connect: unreachable Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:49:05.919 ThaliTest[1432:3069600] jxcore: connect: fail: Peer unreachable
2016-01-07T09:49:05.919Z SendDataConnector.js: CLIENT connected, to 0, error: Peer unreachable
2016-01-07T09:49:05.919Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:49:05.920Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:49:10.932Z SendDataConnector.js: re-try now : Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:49:10.933Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1.CdHxkA==
,timeout now
,weAreDoneNow, resultArray.length: 2
,sendReportNow
,done, now sending data to server
,2016-01-07T09:49:13.422Z SendDataConnector.js: CLIENT Stop now
,2016-01-07 10:49:13.423 ThaliTest[1432:3069600] jxcore: disconnect
2016-01-07 10:49:13.423 ThaliTest[1432:3069600] jxcore: disconnect: fail
2016-01-07T09:49:13.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.CdHxkA==
,teardown
,testSendData stopped
,2016-01-07 10:49:14.084 ThaliTest[1432:3069600] jxcore: stopBroadcasting
,2016-01-07 10:49:14.085 ThaliTest[1432:3069600] THEMultipeerSession stopping peer
2016-01-07 10:49:14.086 ThaliTest[1432:3069600] multipeer session: stop timer
2016-01-07 10:49:14.087 ThaliTest[1432:3069600] server session: disconnect
2016-01-07 10:49:1,4.087 ThaliTest[1432:3069600] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-07 10:49:14.093 ThaliTest[1432:3069600] server session: disconnect
2016-01-07 10:49:14.093 ThaliTest[1432:3069600] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-07 10:49:14.103 ThaliTest[1432:3069600] server session: disconnect
2016-01-07 10:49:14.104 ThaliTest[1432:3069600] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-07 10:49:14.126 ThaliTest[1432:3069600] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
