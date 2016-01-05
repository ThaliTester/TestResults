#### Test 54968200254eab2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F349ED67-613C-43AA-8B8A-E94CD9BD2AA0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F349ED67-613C-43AA-8B8A-E94CD9BD2AA0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54968200254eab2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6B984F48-5EA1-4F0C-ACAF-0AFCAA106A47/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64618"
,(lldb)     command script import "/tmp/F349ED67-613C-43AA-8B8A-E94CD9BD2AA0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 01:37:57.936 ThaliTest[1253:2696083] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E86CB7D5-D8C3-4BF7-BBC1-249AB92E6413/Library/Cookies/Cookies.binarycookies
,2016-01-05 01:37:58.318 ThaliTest[1253:2696083] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 01:37:58.319 ThaliTest[1253:2696083] Multi-tasking -> Device: YES, App: YES
,2016-01-05 01:37:58.329 ThaliTest[1253:2696083] Unlimited access to network resources
,2016-01-05 01:37:58.342 ThaliTest[1253:2696083] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 01:38:06.796 ThaliTest[1253:2696083] Resetting plugins due to page load.
,2016-01-05 01:38:10.713 ThaliTest[1253:2696083] Finished load of: file:///var/mobile/Containers/Bundle/Application/6B984F48-5EA1-4F0C-ACAF-0AFCAA106A47/ThaliTest.app/www/index.html
,2016-01-05 01:38:10.927 ThaliTest[1253:2696083] JXcore Cordova plugin initializing
,2016-01-05 01:38:10.929 ThaliTest[1253:2696324] JXcore instance initializing
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
,2016-01-05 01:38:12.260 ThaliTest[1253:2696083] THREAD WARNING: ['JXcore'] took '90.635742' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 01:43:29.542 ThaliTest[1253:2696324] jxcore: startBroadcasting
,2016-01-05 01:43:29.563 ThaliTest[1253:2696324] server: starting Apple-Iphone5s-1_PT7515.h6ypXg==
2016-01-05 01:43:29.564 ThaliTest[1253:2696324] multipeer session: start timer: 0x1843a6b0
2016-01-05 01:43:29.565 ThaliTest[1253:2696324] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT7515
2016-01-05 01:43:29.565 ThaliTest[1253:2696324] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-05 01:43:29.884 ThaliTest[1253:2696083] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:29.885 ThaliTest[1253:2696083] client: found peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iph,one6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT4820.GNbylA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2016-01-05 01:43:30.019 ThaliTest[1253:2696324] jxcore: stopBroadcasting
2016-01-05 01:43:30.020 ThaliTest[1253:2696324] THEMultipeerSession stopping peer
2016-01-05 01:43:30.020 ThaliTest[1253:2696324] multipeer session: stop timer
2016-01-05 01:43:30.,021 ThaliTest[1253:2696324] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 54744
,2016-01-05 01:43:30.089 ThaliTest[1253:2696324] jxcore: startBroadcasting
,2016-01-05 01:43:30.094 ThaliTest[1253:2696324] server: starting Apple-Iphone5s-1_PT7515.viE/5Q==
2016-01-05 01:43:30.096 ThaliTest[1253:2696324] multipeer session: start timer: 0x183acfd0
,2016-01-05 01:43:30.096 ThaliTest[1253:2696324] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT7515
,2016-01-05 01:43:30.097 ThaliTest[1253:2696324] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-05T00:43:30.102Z SendDataTCPServer.js: TCP/IP server is bound to port: 54744
,2016-01-05 01:43:30.605 ThaliTest[1253:2696083] client: found peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":true}]
2016-01-05 01:43:30.610 ThaliTes,t[1253:2696083] client: found peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:30.611 ThaliTest[1253:2696083] client: found peer: Apple-Iphone5-1_PT4002.tre7Iw==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:43:30.616Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05T00:43:30.617Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05T00:43:30.618Z SendDataConnector.j,s: do connect now
2016-01-05 01:43:30.619 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:30.620 ThaliTest[1253:2696324] client session: connect
2016-01-05 01:43:30.621 ThaliTest[1253:2696324] client session: st,ateChange:0->1 Apple-IpadAir2-1_PT3239.C7DKtQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 01:43:31.272 ThaliTest[1253:2696083] client: lost peer: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:31.272 ThaliTest[1253:2696083] client session: onPeerLost: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:31.273 ThaliTest[1253:269608,3] client session: onLinkFailure: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:31.273 ThaliTest[1253:2696083] client session: disconnect
2016-01-05 01:43:31.273 ThaliTest[1253:2696083] client session: stateChange:1->0 Apple-IpadAir2-1_PT3239.C7DKtQ=,=
2016-01-05 01:43:31.274 ThaliTest[1253:2696083] client session: fireConnectCallback: Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:31.274 ThaliTest[1253:2696083] jxcore: connect: fail: Peer disconnected
2016-01-05T00:43:31.276Z SendDataConnector.j,s: CLIENT connected to 0, error: Peer disconnected
2016-01-05T00:43:31.277Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T00:43:31.277Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier",:"Apple-IpadAir2-1_PT3239.C7DKtQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-05 01:43:31.949 ThaliTest[1253:2696083] client: lost peer: Apple-Iphone5-1_PT4002.tre7Iw==
2016-01-05 01:43:31.950 ThaliTest[1253:2696083] client session: onPeerLost: Apple-Iphone5-1_PT4002.tre7Iw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5-1_PT4002.tre7Iw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 01:43:32.342 ThaliTest[1253:2696083] client: lost peer: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.342 ThaliTest[1253:2696083] client session: onPeerLost: Apple-Iphone6-1_PT4820.GNbylA==
2016-01-05 01:43:32.343 ThaliTest[1253:2696083], client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:43:32.343 ThaliTest[1253:2696083] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4820.GNbylA==","peerName":"(null)","pe,erAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIden,tifier":"Apple-Iphone6-1_PT4820.TWfskw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05 01:43:32.367 ThaliTest[1253:2696083] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4002.r/utkA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05T00:43:36.283Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:43:36.284Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:43:41.294 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:43:41.295 ThaliTest[1253:2696324] jxcore: disconnect: fail
2016-01-05T00:43:41.296Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.C7DK,tQ==
2016-01-05T00:43:41.296Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT3239.C7DKtQ== with availability status: true
2016-01-05T00:43:41.297Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:43:41.297Z SendDataConnector.js: do connect now
,2016-01-05 01:43:41.299 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:41.300 ThaliTest[1253:2696324] client: connect: unreachable Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:41.300 ThaliTest[1253:2696324], jxcore: connect: fail: Peer unreachable
2016-01-05T00:43:41.301Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:43:41.301Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:41.301Z SendD,ataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:46.303Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:43:46.304Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:43:51.314 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:43:51.314 ThaliTest[1253:2696324] jxcore: disconnect: fail
2016-01-05T00:43:51.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.C7DK,tQ==
2016-01-05T00:43:51.315Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT3239.C7DKtQ== with availability status: true
2016-01-05T00:43:51.315Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==,
2016-01-05T00:43:51.316Z SendDataConnector.js: do connect now
,2016-01-05 01:43:51.317 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:43:51.318 ThaliTest[1253:2696324] client: connect: unreachable Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:43:51.318 ThaliTest[1253:2696324] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:43:51.319Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-05T00:43:51.321Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:43:51.321Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:43:56.322Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:43:56.323Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:44:00.097 ThaliTest[1253:2696083] multipeer session: restart
,2016-01-05 01:44:00.149 ThaliTest[1253:2696083] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:00.149 ThaliTest[1253:2696083] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:44:00.149 ThaliTest[1253:2696083] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:01.336 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:44:01.337 ThaliTest[1253:2696324] jxcore: disconnect: fail
2016-01-05T00:44:01.337Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.C7DK,tQ==
2016-01-05T00:44:01.338Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT3239.C7DKtQ== with availability status: true
2016-01-05T00:44:01.338Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:44:01.338Z SendDataConnector.js: do connect now
,2016-01-05 01:44:01.340 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:44:01.341 ThaliTest[1253:2696324] client: connect: unreachable Apple-IpadAir2-1_PT3239.C7DKtQ==
2016-01-05 01:44:01.342 ThaliTest[1253:2696324], jxcore: connect: fail: Peer unreachable
2016-01-05T00:44:01.342Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:01.343Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T00:44:01.343Z SendD,ataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T00:44:06.355Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:44:06.356Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:44:11.361 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:44:11.361 ThaliTest[1253:2696324] jxcore: disconnect: fail
2016-01-05T00:44:11.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.C7DK,tQ==
2016-01-05T00:44:11.362Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT3239.C7DKtQ== with availability status: true
2016-01-05T00:44:11.363Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05T00:44:11.363Z SendDataConnector.js: do connect now
2016-01-05 01:44:11.364 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:44:11.365 ThaliTest[1253:2696324] client: connect: unreachable Apple-IpadAir2-1_PT3239.C7DKtQ==
,2016-01-05 01:44:11.366 ThaliTest[1253:2696324] jxcore: connect: fail: Peer unreachable
,2016-01-05T00:44:11.366Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T00:44:11.367Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-05T00:44:11.369Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 01:44:11.370 ThaliTest[1253:2696324] jxcore: disconnect
,2016-01-05 01:44:11.371 ThaliTest[1253:2696324] jxcore: disconnect: fail
,2016-01-05T00:44:11.373Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.C7DKtQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:11.376Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:11.377Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05T00:44:11.378Z SendDataConnector.js: do connect now
,2016-01-05 01:44:11.379 ThaliTest[1253:2696324] jxcore: connect Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:11.380 ThaliTest[1253:2696324] client session: connect
2016-01-05 01:44:11.380 ThaliTest[1253:2696324] client session: stateChange:0->1 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:16.079 ThaliTest[1253:2696996] client session: connected
2016-01-05 01:44:16.079 ThaliTest[1253:2696996] client session: stateChange:1->2 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:16.112 ThaliTest[1253:2696953] client session: fireConnectCallback: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:16.113 ThaliTest[1253:2696953] jxcore: connect: success
,2016-01-05T00:44:16.114Z SendDataConnector.js: CLIENT connected to 54748, error: null
,2016-01-05T00:44:16.115Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:16.119 ThaliTest[1253:2696083] client: relay established
2016-01-05 01:44:16.119 ThaliTest[1253:2696083] client: new accepted socket: 0x18453c00
,2016-01-05T00:44:16.136Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:16.469Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:16.965Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:44:16.965Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T00:44:16.967Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:16.967Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:16.970 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:44:16.971 ThaliTest[1253:2696324] client session: disconnectFromPeer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:16.971 ThaliTest[1253:2696324] client session: discon,nect
2016-01-05 01:44:16.972 ThaliTest[1253:2696324] client session: stateChange:2->0 Apple-IpadAir2-1_PT3239.85RfWg==
,2016-01-05 01:44:17.061 ThaliTest[1253:2696324] jxcore: disconnect: success
2016-01-05T00:44:17.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT3239.85RfWg==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05T00:44:17.063Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05T00:44:17.064Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05T00:44:17.064Z SendDataConnector.js: do connect now
,2016-01-05 01:44:17.066 ThaliTest[1253:2696324] jxcore: connect Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:17.066 ThaliTest[1253:2696324] client session: connect
2016-01-05 01:44:17.067 ThaliTest[1253:2696324] client session: stateChange:0->1 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:17.648 ThaliTest[1253:2696083] multipeer session: reset timer
2016-01-05 01:44:17.648 ThaliTest[1253:2696083] multipeer session: stop timer
2016-01-05 01:44:17.649 ThaliTest[1253:2696083] multipeer session: start timer: 0x183acfd0
2016-,01-05 01:44:17.649 ThaliTest[1253:2696083] server session: connect
2016-01-05 01:44:17.649 ThaliTest[1253:2696083] server session: stateChange:0->1 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:17.662 ThaliTest[1253:2696083] server: accepting invitation Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:20.224 ThaliTest[1253:2696952] client session: connected
2016-01-05 01:44:20.224 ThaliTest[1253:2696952] client session: stateChange:1->2 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:20.266 ThaliTest[1253:2696995] client session: fireConnectCallback: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:20.267 ThaliTest[1253:2696995] jxcore: connect: success
2016-01-05T00:44:20.268Z SendDataConnector.js: CLIENT connected to 54751, error: null
2016-01-05T00:44:20.268Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:20.274 ThaliTest[1253:2696083] client: relay established
2016-01-05 01:44:20.274 ThaliTest[1253:2696083] client: new accepted socket: 0x183c19f0
,2016-01-05T00:44:20.287Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:20.630Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:20.925Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T00:44:20.925Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T00:44:20.926Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T00:44:20.926Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:20.927 ThaliTest[1253:2696324] jxcore: disconnect
2016-01-05 01:44:20.928 ThaliTest[1253:2696324] client session: disconnectFromPeer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:44:20.928 ThaliTest[1253:2696324] client session: disconnect
2016-01-05 01:44:20.928 ThaliTest[1253:2696324] client session: stateChange:2->0 Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:20.936 ThaliTest[1253:2696324] jxcore: disconnect: success
2016-01-05T00:44:20.937Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4820.TWfskw==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5-1_PT4002.r/utkA==
2016-01-05T00:44:20.937Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05T00:44:20.938Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05T00:44:20.938Z SendDataConnector.js: do connect now
2016-01-05 01:44:20.940 ThaliTest[1253:2696324] jxcore: connect Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:44:20.941 ThaliTest[1253:2696324] client session: connect
2016-01-05 01:44:20.941 ThaliTest[1253:2696324] client session: stateChange:0->1 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:21.169 ThaliTest[1253:2696953] server session: connected
2016-01-05 01:44:21.169 ThaliTest[1253:2696953] server session: stateChange:1->2 Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:21.203 ThaliTest[1253:2696083] server relay: connected (to port: 54744)
,2016-01-05T00:44:21.213Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:21.472Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
2016-01-05T00:44:21.488Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
2016-01-05T00:44:21.522Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-05T00:44:21.538Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-05T00:44:21.554Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:21.615 ThaliTest[1253:2696996] server session: not connected Apple-IpadAir2-1_PT3239
,2016-01-05 01:44:21.710 ThaliTest[1253:2696083] multipeer session: reset timer
2016-01-05 01:44:21.711 ThaliTest[1253:2696083] multipeer session: stop timer
2016-01-05 01:44:21.712 ThaliTest[1253:2696083] multipeer session: start timer: 0x183acfd0
,2016-01-05 01:44:21.712 ThaliTest[1253:2696083] server session: connect
,2016-01-05 01:44:21.713 ThaliTest[1253:2696083] server session: stateChange:0->1 Apple-Iphone5-1_PT4002
,2016-01-05 01:44:21.722 ThaliTest[1253:2696083] server: accepting invitation Apple-Iphone5-1_PT4002
,2016-01-05 01:44:23.886 ThaliTest[1253:2696951] client session: connected
2016-01-05 01:44:23.886 ThaliTest[1253:2696951] client session: stateChange:1->2 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:23.945 ThaliTest[1253:2696952] client session: fireConnectCallback: Apple-Iphone5-1_PT4002.r/utkA==
2016-01-05 01:44:23.945 ThaliTest[1253:2696952] jxcore: connect: success
,2016-01-05T00:44:23.948Z SendDataConnector.js: CLIENT connected to 54755, error: null
,2016-01-05T00:44:23.948Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 01:44:23.952 ThaliTest[1253:2696083] client: relay established
2016-01-05 01:44:23.952 ThaliTest[1253:2696083] client: new accepted socket: 0x183b8d60
,2016-01-05T00:44:23.965Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T00:44:24.369Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T00:44:24.383Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T00:44:24.396Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05 01:44:24.414 ThaliTest[1253:2696951] server session: connected
2016-01-05 01:44:24.414 ThaliTest[1253:2696951] server session: stateChange:1->2 Apple-Iphone5-1_PT4002
,2016-01-05T00:44:24.410Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05 01:44:24.427 ThaliTest[1253:2696083] server relay: connected (to port: 54744)
,2016-01-05T00:44:24.430Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T00:44:24.431Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-05T00:44:24.432Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:24.432Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 01:44:24.433 ThaliTest[1253:2696324] jxcore: disconnect
,2016-01-05 01:44:24.434 ThaliTest[1253:2696324] client session: disconnectFromPeer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:24.434 ThaliTest[1253:2696324] client session: disconnect
,2016-01-05 01:44:24.435 ThaliTest[1253:2696324] client session: stateChange:2->0 Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:24.503 ThaliTest[1253:2696324] jxcore: disconnect: success
,2016-01-05T00:44:24.504Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4002.r/utkA==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T00:44:24.507Z SendDataConnector.js: CLIENT Stop now
2016-01-05T00:44:24.507Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05T00:44:24.508Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:44:24.956Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-05T00:44:24.988Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-05T00:44:25.006Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-05T00:44:25.025Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-05T00:44:25.041Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-05T00:44:25.057Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-05T00:44:25.074Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:44:25.136 ThaliTest[1253:2696996] server session: not connected Apple-Iphone5-1_PT4002
,2016-01-05 01:44:51.713 ThaliTest[1253:2696083] multipeer session: restart
,2016-01-05 01:44:51.772 ThaliTest[1253:2696083] client: found peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:44:51.772 ThaliTest[1253:2696083] client: found peer: Apple-Iphone6-1_PT4820.TWfskw==
,2016-01-05 01:44:51.784 ThaliTest[1253:2696083] client: found peer: Apple-Iphone5-1_PT4002.r/utkA==
,2016-01-05 01:44:57.397 ThaliTest[1253:2696083] multipeer session: reset timer
2016-01-05 01:44:57.398 ThaliTest[1253:2696083] multipeer session: stop timer
2016-01-05 01:44:57.398 ThaliTest[1253:2696083] multipeer session: start timer: 0x183acfd0
2016-,01-05 01:44:57.398 ThaliTest[1253:2696083] server session: connect
2016-01-05 01:44:57.399 ThaliTest[1253:2696083] server session: stateChange:0->1 Apple-Iphone6-1_PT4820
,2016-01-05 01:44:57.410 ThaliTest[1253:2696083] server: accepting invitation Apple-Iphone6-1_PT4820
,2016-01-05 01:45:00.177 ThaliTest[1253:2697087] server session: connected
2016-01-05 01:45:00.177 ThaliTest[1253:2697087] server session: stateChange:1->2 Apple-Iphone6-1_PT4820
,2016-01-05 01:45:00.953 ThaliTest[1253:2696083] server relay: connected (to port: 54744)
2016-01-05T00:45:00.954Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T00:45:01.018Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-05T00:45:01.035Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-05T00:45:01.049Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-05T00:45:01.065Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 01:45:01.098 ThaliTest[1253:2697017] server session: not connected Apple-Iphone6-1_PT4820
,2016-01-05 01:45:10.968 ThaliTest[1253:2696083] client: lost peer: Apple-Iphone6-1_PT4820.TWfskw==
2016-01-05 01:45:10.968 ThaliTest[1253:2696083] client session: onPeerLost: Apple-Iphone6-1_PT4820.TWfskw==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT4820.TWfskw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-05 01:45:11.487 ThaliTest[1253:2696083] client: lost peer: Apple-IpadAir2-1_PT3239.85RfWg==
2016-01-05 01:45:11.487 ThaliTest[1253:2696083] client session: onPeerLost: Apple-IpadAir2-1_PT3239.85RfWg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT3239.85RfWg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
2016-01-05 01:45:12.571 ThaliTest[1253:2696324] jxcore: stopBroadcasting
,2016-01-05 01:45:12.572 ThaliTest[1253:2696324] THEMultipeerSession stopping peer
,2016-01-05 01:45:12.572 ThaliTest[1253:2696324] multipeer session: stop timer
2016-01-05 01:45:12.574 ThaliTest[1253:2696324] server session: disconnect
2016-01-05 01:45:12.575 ThaliTest[1253:2696324] server session: stateChange:2->0 Apple-IpadAir2-1_PT3239
,2016-01-05 01:45:12.585 ThaliTest[1253:2696324] server session: disconnect
2016-01-05 01:45:12.586 ThaliTest[1253:2696324] server session: stateChange:2->0 Apple-Iphone6-1_PT4820
2016-01-05 01:45:12.590 ThaliTest[1253:2696324] server session: disconnect,
2016-01-05 01:45:12.590 ThaliTest[1253:2696324] server session: stateChange:2->0 Apple-Iphone5-1_PT4002
,2016-01-05 01:45:12.606 ThaliTest[1253:2696324] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T00:45:12.643Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.648Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.659Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T00:45:12.661Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
