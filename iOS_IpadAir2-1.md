#### Test 5546736337bcedb_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5D365187-5125-42F9-8D44-491A06366FB1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5D365187-5125-42F9-8D44-491A06366FB1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97D8F915-73C4-40D1-B104-C79B50AE1254/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50278"
,(lldb)     command script import "/tmp/5D365187-5125-42F9-8D44-491A06366FB1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 15:48:21.859 ThaliTest[1534:3332576] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0897E2F3-951B-4006-8E90-FAB9D711C5A4/Library/Cookies/Cookies.binarycookies
,2016-01-08 15:48:22.281 ThaliTest[1534:3332576] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 15:48:22.282 ThaliTest[1534:3332576] Multi-tasking -> Device: YES, App: YES
,2016-01-08 15:48:22.291 ThaliTest[1534:3332576] Unlimited access to network resources
,2016-01-08 15:48:22.300 ThaliTest[1534:3332576] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 15:48:31.259 ThaliTest[1534:3332576] Resetting plugins due to page load.
,2016-01-08 15:48:34.460 ThaliTest[1534:3332576] Finished load of: file:///var/mobile/Containers/Bundle/Application/97D8F915-73C4-40D1-B104-C79B50AE1254/ThaliTest.app/www/index.html
,2016-01-08 15:48:34.620 ThaliTest[1534:3332576] JXcore Cordova plugin initializing
,2016-01-08 15:48:34.621 ThaliTest[1534:3332831] JXcore instance initializing
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
,2016-01-08 15:48:35.709 ThaliTest[1534:3332576] THREAD WARNING: ['JXcore'] took '69.138916' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 15:53:15.965 ThaliTest[1534:3332831] jxcore: startBroadcasting
,2016-01-08 15:53:15.983 ThaliTest[1534:3332831] server: starting Apple-IpadAir2-1.xmg6Nw==
,2016-01-08 15:53:15.984 ThaliTest[1534:3332831] multipeer session: start timer: 0x16405530
,2016-01-08 15:53:15.984 ThaliTest[1534:3332831] THEMultipeerSession initialized peer Apple-IpadAir2-1
,2016-01-08 15:53:15.986 ThaliTest[1534:3332831] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-08 15:53:18.157 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5-1.oJtw2A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1.oJtw2A==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 15:53:19.019 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5s-1.MP5wlA==
,teardown
,testFindPeers stopped
,2016-01-08 15:53:19.822 ThaliTest[1534:3332831] jxcore: stopBroadcasting
,2016-01-08 15:53:19.823 ThaliTest[1534:3332831] THEMultipeerSession stopping peer
2016-01-08 15:53:19.823 ThaliTest[1534:3332831] multipeer session: stop timer
2016-01-08 15:53:19.824 ThaliTest[1534:3332831] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64931
,2016-01-08 15:53:19.854 ThaliTest[1534:3332831] jxcore: startBroadcasting
,2016-01-08 15:53:19.857 ThaliTest[1534:3332831] server: starting Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:53:19.859 ThaliTest[1534:3332831] multipeer session: start timer: 0x166450f0
2016-01-08 15:53:19.859 ThaliTest[1534:3332831] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-08 15:53:19.859 ThaliTest[1534:3332831] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-08T14:53:19.865Z SendDataTCPServer.js: TCP/IP server is bound to port: 64931
,2016-01-08 15:53:19.884 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:19.884 ThaliTest[1534:3332576] client: found peer: Apple-IpadAir2-1.xmg6Nw==
,2016-01-08 15:53:19.886 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5s-1.MP5wlA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:19.897Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:19.898Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:19.898Z SendDataConnector.js: do connect now
,2016-01-08 15:53:19.899 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:19.899 ThaliTest[1534:3332831] client session: connect
,2016-01-08 15:53:19.900 ThaliTest[1534:3332831] client session: stateChange:0->1 Apple-Iphone5-1.oJtw2A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 15:53:20.080 ThaliTest[1534:3332576] client: found peer: Apple-Iphone6-1.j1bF8Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 15:53:21.051 ThaliTest[1534:3332576] client: lost peer: Apple-IpadAir2-1.xmg6Nw==
2016-01-08 15:53:21.051 ThaliTest[1534:3332576] client session: onPeerLost: Apple-IpadAir2-1.xmg6Nw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 15:53:21.082 ThaliTest[1534:3332576] client: lost peer: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:21.082 ThaliTest[1534:3332576] client session: onPeerLost: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:21.082 ThaliTest[1534:3332576] client sessio,n: onLinkFailure: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:21.083 ThaliTest[1534:3332576] client session: disconnect
2016-01-08 15:53:21.083 ThaliTest[1534:3332576] client session: stateChange:1->0 Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:21.084 Thali,Test[1534:3332576] client session: fireConnectCallback: Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:21.084 ThaliTest[1534:3332576] jxcore: connect: fail: Peer disconnected
,2016-01-08T14:53:21.086Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2016-01-08T14:53:21.086Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T14:53:21.088Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 15:53:21.607 ThaliTest[1534:3332576] client: lost peer: Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:21.608 ThaliTest[1534:3332576] client session: onPeerLost: Apple-Iphone6-1.j1bF8Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 15:53:21.672 ThaliTest[1534:3332576] client: lost peer: Apple-Iphone5s-1.MP5wlA==
2016-01-08 15:53:21.673 ThaliTest[1534:3332576] client session: onPeerLost: Apple-Iphone5s-1.MP5wlA==
2016-01-08 15:53:21.673 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:53:21.675 ThaliTest[1534:3332576] client: found peer: Apple-Iphone6-1.bICwVA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":false}]
Found peer ,: (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.ziR9IQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.bICwVA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:22.312 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5s-1.zHt1vQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.zHt1vQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T14:53:26.095Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:26.097Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:31.105 ThaliTest[1534:3332831] jxcore: disconnect
,2016-01-08 15:53:31.105 ThaliTest[1534:3332831] jxcore: disconnect: fail
,2016-01-08T14:53:31.106Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:31.107Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
,2016-01-08T14:53:31.107Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:31.108Z SendDataConnector.js: do connect now
,2016-01-08 15:53:31.109 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.oJtw2A==
2016-01-08 15:53:31.110 ThaliTest[1534:3332831] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:31.110 ThaliTest[1534:3332831] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:31.111Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:53:31.112Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T14:53:31.112Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:36.120Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:36.120Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:41.126 ThaliTest[1534:3332831] jxcore: disconnect
,2016-01-08 15:53:41.126 ThaliTest[1534:3332831] jxcore: disconnect: fail
,2016-01-08T14:53:41.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:41.128Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
,2016-01-08T14:53:41.128Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:41.129Z SendDataConnector.js: do connect now
,2016-01-08 15:53:41.130 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:41.131 ThaliTest[1534:3332831] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:41.131 ThaliTest[1534:3332831] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:41.132Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:53:41.133Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T14:53:41.134Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:46.134Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:46.135Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:49.864 ThaliTest[1534:3332576] multipeer session: restart
,2016-01-08 15:53:49.892 ThaliTest[1534:3332576] client: found peer: Apple-Iphone6-1.bICwVA==
2016-01-08 15:53:49.892 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:53:49.893 ThaliTest[1534:3332576] client: found peer: Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:53:51.144 ThaliTest[1534:3332831] jxcore: disconnect
,2016-01-08 15:53:51.144 ThaliTest[1534:3332831] jxcore: disconnect: fail
,2016-01-08T14:53:51.145Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:51.146Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
,2016-01-08T14:53:51.146Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:51.147Z SendDataConnector.js: do connect now
,2016-01-08 15:53:51.148 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:51.148 ThaliTest[1534:3332831] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:51.149 ThaliTest[1534:3332831] jxcore: connect: fail: Peer unreachable
2016-01-08T14:53:51.150Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:53:51.150Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T14:53:51.150Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:56.162Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:53:56.162Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:54:01.164 ThaliTest[1534:3332831] jxcore: disconnect
,2016-01-08 15:54:01.165 ThaliTest[1534:3332831] jxcore: disconnect: fail
,2016-01-08T14:54:01.165Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
,2016-01-08T14:54:01.166Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.oJtw2A== with availability status: true
,2016-01-08T14:54:01.167Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oJtw2A==
2016-01-08T14:54:01.168Z SendDataConnector.js: do connect now
,2016-01-08 15:54:01.169 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.oJtw2A==
2016-01-08 15:54:01.170 ThaliTest[1534:3332831] client: connect: unreachable Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:54:01.170 ThaliTest[1534:3332831] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:54:01.171Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:54:01.171Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T14:54:01.174Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 15:54:01.174 ThaliTest[1534:3332831] jxcore: disconnect
2016-01-08 15:54:01.175 ThaliTest[1534:3332831] jxcore: disconnect: fail
,2016-01-08T14:54:01.176Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oJtw2A==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.ziR9IQ==
,2016-01-08T14:54:01.179Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.ziR9IQ==
,2016-01-08T14:54:01.180Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.ziR9IQ==
,2016-01-08T14:54:01.180Z SendDataConnector.js: do connect now
,2016-01-08 15:54:01.181 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:01.182 ThaliTest[1534:3332831] client session: connect
2016-01-08 15:54:01.183 ThaliTest[1534:3332831] client session: stateChange:0->1 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:01.539 ThaliTest[1534:3332576] multipeer session: reset timer
2016-01-08 15:54:01.539 ThaliTest[1534:3332576] multipeer session: stop timer
2016-01-08 15:54:01.539 ThaliTest[1534:3332576] multipeer session: start timer: 0x166450f0
2016-01-08 15:54:01.540 ThaliTest[1534:3332576] server session: connect
,2016-01-08 15:54:01.540 ThaliTest[1534:3332576] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 15:54:01.547 ThaliTest[1534:3332576] server: accepting invitation Apple-Iphone5-1
,2016-01-08 15:54:01.869 ThaliTest[1534:3332576] multipeer session: reset timer
2016-01-08 15:54:01.869 ThaliTest[1534:3332576] multipeer session: stop timer
2016-01-08 15:54:01.869 ThaliTest[1534:3332576] multipeer session: start timer: 0x166450f0
2016-,01-08 15:54:01.870 ThaliTest[1534:3332576] server session: connect
2016-01-08 15:54:01.870 ThaliTest[1534:3332576] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 15:54:01.873 ThaliTest[1534:3332576] server: accepting invitation Apple-Iphone6-1
,2016-01-08 15:54:01.981 ThaliTest[1534:3332576] multipeer session: reset timer
,2016-01-08 15:54:01.981 ThaliTest[1534:3332576] multipeer session: stop timer
,2016-01-08 15:54:01.982 ThaliTest[1534:3332576] multipeer session: start timer: 0x166450f0
,2016-01-08 15:54:01.983 ThaliTest[1534:3332576] server session: connect
,2016-01-08 15:54:01.984 ThaliTest[1534:3332576] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 15:54:01.990 ThaliTest[1534:3332576] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 15:54:07.746 ThaliTest[1534:3333460] client session: connected
2016-01-08 15:54:07.747 ThaliTest[1534:3333460] client session: stateChange:1->2 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:07.832 ThaliTest[1534:3333460] server session: connected
2016-01-08 15:54:07.832 ThaliTest[1534:3333460] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 15:54:07.860 ThaliTest[1534:3332576] server relay: connected (to port: 64931)
,2016-01-08T14:54:07.871Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:07.877 ThaliTest[1534:3333513] server session: connected
2016-01-08 15:54:07.878 ThaliTest[1534:3333513] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 15:54:07.897 ThaliTest[1534:3332576] server relay: connected (to port: 64931)
,2016-01-08T14:54:07.908Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:07.919 ThaliTest[1534:3333519] client session: fireConnectCallback: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:07.919 ThaliTest[1534:3333519] jxcore: connect: success
,2016-01-08T14:54:07.921Z SendDataConnector.js: CLIENT connected to 64938, error: null
,2016-01-08T14:54:07.921Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:07.923 ThaliTest[1534:3332576] client: relay established
,2016-01-08 15:54:07.924 ThaliTest[1534:3332576] client: new accepted socket: 0x166521d0
,2016-01-08T14:54:07.940Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 15:54:08.481 ThaliTest[1534:3333519] server session: connected
2016-01-08 15:54:08.481 ThaliTest[1534:3333519] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08T14:54:08.510Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:08.531 ThaliTest[1534:3332576] server relay: connected (to port: 64931)
,2016-01-08T14:54:08.534Z SendDataTCPServer.js: TCP/IP server has received 3072 bytes of data
,2016-01-08T14:54:08.547Z SendDataTCPServer.js: TCP/IP server has received 68608 bytes of data
,2016-01-08T14:54:08.548Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:08.587 ThaliTest[1534:3333486] server session: not connected Apple-Iphone6-1
,2016-01-08T14:54:09.079Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T14:54:09.092Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T14:54:09.143Z SendDataTCPServer.js: TCP/IP server has received 25185 bytes of data
,2016-01-08T14:54:09.159Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-08T14:54:09.174Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-08T14:54:09.189Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2016-01-08T14:54:09.208Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-08T14:54:09.222Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:09.260 ThaliTest[1534:3333519] server session: not connected Apple-Iphone5s-1
,2016-01-08T14:54:09.992Z SendDataTCPServer.js: TCP/IP server has received 10879 bytes of data
,2016-01-08T14:54:10.009Z SendDataTCPServer.js: TCP/IP server has received 31755 bytes of data
,2016-01-08T14:54:10.012Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:10.013Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T14:54:10.014Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:10.014Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:10.019 ThaliTest[1534:3332831] jxcore: disconnect
2016-01-08 15:54:10.020 ThaliTest[1534:3332831] client session: disconnectFromPeer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:10.020 ThaliTest[1534:3332831] client session: disconnect
2016-01-08 15:54:10.021 ThaliTest[1534:3332831] client session: stateChange:2->0 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:10.033 ThaliTest[1534:3332831] jxcore: disconnect: success
2016-01-08T14:54:10.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.ziR9IQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:10.035Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:10.035Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.bICwVA==
,2016-01-08T14:54:10.036Z SendDataConnector.js: do connect now
,2016-01-08 15:54:10.037 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:10.037 ThaliTest[1534:3332831] client session: connect
2016-01-08 15:54:10.038 ThaliTest[1534:3332831] client session: stateChange:0->1 Apple-Iphone6-1.bICwVA==
,2016-01-08T14:54:10.064Z SendDataTCPServer.js: TCP/IP server has received 55774 bytes of data
,2016-01-08T14:54:10.086Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T14:54:10.102Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T14:54:10.116Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-08T14:54:10.191Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:10.330 ThaliTest[1534:3333485] server session: not connected Apple-Iphone5-1
,2016-01-08 15:54:13.533 ThaliTest[1534:3333514] client session: connected
2016-01-08 15:54:13.533 ThaliTest[1534:3333514] client session: stateChange:1->2 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:13.589 ThaliTest[1534:3333485] client session: fireConnectCallback: Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:13.589 ThaliTest[1534:3333485] jxcore: connect: success
,2016-01-08T14:54:13.590Z SendDataConnector.js: CLIENT connected to 64942, error: null
,2016-01-08T14:54:13.591Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:13.594 ThaliTest[1534:3332576] client: relay established
,2016-01-08 15:54:13.595 ThaliTest[1534:3332576] client: new accepted socket: 0x16654b10
,2016-01-08T14:54:13.609Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:14.107Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T14:54:14.133Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T14:54:14.146Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T14:54:14.183Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:14.183Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T14:54:14.184Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:14.184Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:14.184 ThaliTest[1534:3332831] jxcore: disconnect
2016-01-08 15:54:14.185 ThaliTest[1534:3332831] client session: disconnectFromPeer: Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:14.185 ThaliTest[1534:3332831] client session: disconnect
,2016-01-08 15:54:14.185 ThaliTest[1534:3332831] client session: stateChange:2->0 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:14.247 ThaliTest[1534:3332831] jxcore: disconnect: success
2016-01-08T14:54:14.247Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.bICwVA==
---- round done--------
,startWithNextDevice
device[4]: Apple-Iphone5s-1.zHt1vQ==
,2016-01-08T14:54:14.248Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.zHt1vQ==
,2016-01-08T14:54:14.248Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.zHt1vQ==
2016-01-08T14:54:14.248Z SendDataConnector.js: do connect now
,2016-01-08 15:54:14.248 ThaliTest[1534:3332831] jxcore: connect Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:14.248 ThaliTest[1534:3332831] client session: connect
,2016-01-08 15:54:14.249 ThaliTest[1534:3332831] client session: stateChange:0->1 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:17.783 ThaliTest[1534:3333460] client session: connected
,2016-01-08 15:54:17.783 ThaliTest[1534:3333460] client session: stateChange:1->2 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:17.847 ThaliTest[1534:3333460] client session: fireConnectCallback: Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:54:17.847 ThaliTest[1534:3333460] jxcore: connect: success
,2016-01-08T14:54:17.850Z SendDataConnector.js: CLIENT connected to 64945, error: null
,2016-01-08T14:54:17.850Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:17.852 ThaliTest[1534:3332576] client: relay established
2016-01-08 15:54:17.853 ThaliTest[1534:3332576] client: new accepted socket: 0x16656170
,2016-01-08T14:54:17.867Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:18.382Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T14:54:18.393Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T14:54:18.517Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T14:54:18.552Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T14:54:18.563Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T14:54:18.649Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T14:54:18.710Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:18.710Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T14:54:18.711Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:18.711Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:18.712 ThaliTest[1534:3332831] jxcore: disconnect
,2016-01-08 15:54:18.712 ThaliTest[1534:3332831] client session: disconnectFromPeer: Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:18.712 ThaliTest[1534:3332831] client session: disconnect
,2016-01-08 15:54:18.713 ThaliTest[1534:3332831] client session: stateChange:2->0 Apple-Iphone5s-1.zHt1vQ==
,2016-01-08 15:54:18.717 ThaliTest[1534:3332831] jxcore: disconnect: success
2016-01-08T14:54:18.718Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.zHt1vQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2016-01-08T14:54:18.738Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:18.738Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-08 15:54:19.626 ThaliTest[1534:3332831] jxcore: stopBroadcasting
2016-01-08 15:54:19.627 ThaliTest[1534:3332831] THEMultipeerSession stopping peer
,2016-01-08 15:54:19.627 ThaliTest[1534:3332831] multipeer session: stop timer
,2016-01-08 15:54:19.628 ThaliTest[1534:3332831] server session: disconnect
2016-01-08 15:54:19.629 ThaliTest[1534:3332831] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 15:54:19.710 ThaliTest[1534:3332831] server session: disconnect
,2016-01-08 15:54:19.711 ThaliTest[1534:3332831] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 15:54:19.715 ThaliTest[1534:3332831] server session: disconnect
,2016-01-08 15:54:19.718 ThaliTest[1534:3332831] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 15:54:19.780 ThaliTest[1534:3332831] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
