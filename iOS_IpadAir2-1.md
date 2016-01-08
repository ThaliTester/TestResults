#### Test 55431344e5dd625_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/12E92D08-CDA7-408A-A6D1-618434047C23/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/12E92D08-CDA7-408A-A6D1-618434047C23/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DB2C8942-AAA9-4FFA-8B62-662B49C95843/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49847"
,(lldb)     command script import "/tmp/12E92D08-CDA7-408A-A6D1-618434047C23/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 08:25:09.214 ThaliTest[1496:3284766] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/60F13C3E-8FF4-422A-82E5-45A0C506626E/Library/Cookies/Cookies.binarycookies
,2016-01-08 08:25:09.604 ThaliTest[1496:3284766] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 08:25:09.605 ThaliTest[1496:3284766] Multi-tasking -> Device: YES, App: YES
,2016-01-08 08:25:09.614 ThaliTest[1496:3284766] Unlimited access to network resources
,2016-01-08 08:25:09.623 ThaliTest[1496:3284766] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 08:25:18.753 ThaliTest[1496:3284766] Resetting plugins due to page load.
,2016-01-08 08:25:22.420 ThaliTest[1496:3284766] Finished load of: file:///var/mobile/Containers/Bundle/Application/DB2C8942-AAA9-4FFA-8B62-662B49C95843/ThaliTest.app/www/index.html
,2016-01-08 08:25:22.578 ThaliTest[1496:3284766] JXcore Cordova plugin initializing
,2016-01-08 08:25:22.578 ThaliTest[1496:3285038] JXcore instance initializing
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
,2016-01-08 08:25:23.671 ThaliTest[1496:3284766] THREAD WARNING: ['JXcore'] took '69.085205' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 08:30:19.055 ThaliTest[1496:3285038] jxcore: startBroadcasting
,2016-01-08 08:30:19.071 ThaliTest[1496:3285038] server: starting Apple-IpadAir2-1.SM1CRQ==
,2016-01-08 08:30:19.072 ThaliTest[1496:3285038] multipeer session: start timer: 0x195950c0
2016-01-08 08:30:19.073 ThaliTest[1496:3285038] THEMultipeerSession initialized peer Apple-IpadAir2-1
2016-01-08 08:30:19.073 ThaliTest[1496:3285038] jxcore: start,Broadcasting: success
StartBroadcasting started ok
,2016-01-08 08:30:20.118 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5-1.8yAUdA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1.8yAUdA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 08:30:20.213 ThaliTest[1496:3284766] client: found peer: Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:20.879 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5s-1.NE8BAA==
,teardown
,testFindPeers stopped
,2016-01-08 08:30:21.061 ThaliTest[1496:3285038] jxcore: stopBroadcasting
,2016-01-08 08:30:21.061 ThaliTest[1496:3285038] THEMultipeerSession stopping peer
,2016-01-08 08:30:21.062 ThaliTest[1496:3285038] multipeer session: stop timer
,2016-01-08 08:30:21.066 ThaliTest[1496:3285038] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 64620
,2016-01-08 08:30:21.096 ThaliTest[1496:3285038] jxcore: startBroadcasting
,2016-01-08 08:30:21.100 ThaliTest[1496:3285038] server: starting Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:30:21.101 ThaliTest[1496:3285038] multipeer session: start timer: 0x194b2bd0
2016-01-08 08:30:21.101 ThaliTest[1496:3285038] THEMultipeerSession init,ialized peer Apple-IpadAir2-1
2016-01-08 08:30:21.102 ThaliTest[1496:3285038] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-08T07:30:21.110Z SendDataTCPServer.js: TCP/IP server is bound to port: 64620
,2016-01-08 08:30:21.610 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:21.611 ThaliTest[1496:3284766] client: found peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:21.611 ThaliTest[1496:3284766] client: found peer:, Apple-Iphone5-1.8yAUdA==
2016-01-08 08:30:21.612 ThaliTest[1496:3284766] client: found peer: Apple-IpadAir2-1.SM1CRQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:21.617Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.NE8BAA==
2016-01-08T07:30:21.618Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:21.618Z SendDataConnector.js: do connect now
2016-01-08 08:30:21.619 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:21.619 ThaliTest[1496:3285038] client session: connect
2016-01-08 08:30:21.619 ThaliTest[1496:3285038] client session: stateChange:0->1 Apple-Iphone5s-1.NE8BAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:22.229 ThaliTest[1496:3284766] client: lost peer: Apple-IpadAir2-1.SM1CRQ==
2016-01-08 08:30:22.230 ThaliTest[1496:3284766] client session: onPeerLost: Apple-IpadAir2-1.SM1CRQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 08:30:22.328 ThaliTest[1496:3284766] client: lost peer: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.329 ThaliTest[1496:3284766] client session: onPeerLost: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.329 ThaliTest[1496:3284766] client sess,ion: onLinkFailure: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.329 ThaliTest[1496:3284766] client session: disconnect
2016-01-08 08:30:22.329 ThaliTest[1496:3284766] client session: stateChange:1->0 Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.330 T,haliTest[1496:3284766] client session: fireConnectCallback: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.330 ThaliTest[1496:3284766] jxcore: connect: fail: Peer disconnected
,2016-01-08T07:30:22.332Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T07:30:22.333Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2016-01-08T07:30:22.334Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 08:30:22.783 ThaliTest[1496:3284766] client: lost peer: Apple-Iphone5-1.8yAUdA==
2016-01-08 08:30:22.784 ThaliTest[1496:3284766] client session: onPeerLost: Apple-Iphone5-1.8yAUdA==
2016-01-08 08:30:22.784 ThaliTest[1496:3284766] client: lost ,peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.784 ThaliTest[1496:3284766] client session: onPeerLost: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.785 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5-1.kpUZpA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kpUZpA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:23.196 ThaliTest[1496:3284766] client: found peer: Apple-Iphone6-1.O1yvYA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.O1yvYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:23.213 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5s-1.WrRjQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.WrRjQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T07:30:27.337Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:27.338Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:32.344 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:30:32.345 ThaliTest[1496:3285038] jxcore: disconnect: fail
,2016-01-08T07:30:32.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:32.347Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.NE8BAA== with availability status: true
,2016-01-08T07:30:32.347Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:32.348Z SendDataConnector.js: do connect now
,2016-01-08 08:30:32.349 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:32.349 ThaliTest[1496:3285038] client: connect: unreachable Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:32.350 ThaliTest[1496:3285038] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:32.350Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:32.351Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:32.352Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:37.359Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.NE8BAA==
2016-01-08T07:30:37.360Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:42.368 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:30:42.369 ThaliTest[1496:3285038] jxcore: disconnect: fail
,2016-01-08T07:30:42.370Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:42.371Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.NE8BAA== with availability status: true
,2016-01-08T07:30:42.371Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:42.371Z SendDataConnector.js: do connect now
,2016-01-08 08:30:42.372 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:42.373 ThaliTest[1496:3285038] client: connect: unreachable Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:42.374 ThaliTest[1496:3285038] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:42.374Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T07:30:42.375Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:42.376Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:47.379Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:47.379Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:51.103 ThaliTest[1496:3284766] multipeer session: restart
,2016-01-08 08:30:51.131 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:30:51.131 ThaliTest[1496:3284766] client: found peer: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:30:51.131 ThaliTest[1496:3284766] client: found peer: Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:30:52.382 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:30:52.383 ThaliTest[1496:3285038] jxcore: disconnect: fail
,2016-01-08T07:30:52.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:52.385Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.NE8BAA== with availability status: true
,2016-01-08T07:30:52.385Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:52.386Z SendDataConnector.js: do connect now
,2016-01-08 08:30:52.387 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:52.387 ThaliTest[1496:3285038] client: connect: unreachable Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:52.388 ThaliTest[1496:3285038] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:52.389Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T07:30:52.389Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:52.390Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:57.393Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.NE8BAA==
2016-01-08T07:30:57.394Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:31:02.397 ThaliTest[1496:3285038] jxcore: disconnect
2016-01-08 08:31:02.397 ThaliTest[1496:3285038] jxcore: disconnect: fail
,2016-01-08T07:31:02.398Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:31:02.399Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.NE8BAA== with availability status: true
,2016-01-08T07:31:02.399Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.NE8BAA==
2016-01-08T07:31:02.400Z SendDataConnector.js: do connect now
,2016-01-08 08:31:02.401 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:31:02.401 ThaliTest[1496:3285038] client: connect: unreachable Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:31:02.401 ThaliTest[1496:3285038] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:31:02.402Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T07:31:02.403Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T07:31:02.405Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 08:31:02.406 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:31:02.406 ThaliTest[1496:3285038] jxcore: disconnect: fail
,2016-01-08T07:31:02.407Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.NE8BAA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.411Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.412Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.413Z SendDataConnector.js: do connect now
,2016-01-08 08:31:02.414 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:02.414 ThaliTest[1496:3285038] client session: connect
,2016-01-08 08:31:02.415 ThaliTest[1496:3285038] client session: stateChange:0->1 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:03.070 ThaliTest[1496:3284766] multipeer session: reset timer
2016-01-08 08:31:03.071 ThaliTest[1496:3284766] multipeer session: stop timer
2016-01-08 08:31:03.071 ThaliTest[1496:3284766] multipeer session: start timer: 0x194b2bd0
2016-,01-08 08:31:03.071 ThaliTest[1496:3284766] server session: connect
2016-01-08 08:31:03.072 ThaliTest[1496:3284766] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 08:31:03.079 ThaliTest[1496:3284766] server: accepting invitation Apple-Iphone5-1
,2016-01-08 08:31:06.972 ThaliTest[1496:3285677] client session: connected
2016-01-08 08:31:06.972 ThaliTest[1496:3285677] client session: stateChange:1->2 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:06.976 ThaliTest[1496:3285719] server session: connected
2016-01-08 08:31:06.977 ThaliTest[1496:3285719] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 08:31:07.011 ThaliTest[1496:3285720] client session: fireConnectCallback: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:07.011 ThaliTest[1496:3285720] jxcore: connect: success
,2016-01-08 08:31:07.014 ThaliTest[1496:3284766] server relay: connected (to port: 64620)
2016-01-08T07:31:07.015Z SendDataTCPServer.js: TCP/IP server connected
2016-01-08T07:31:07.017Z SendDataConnector.js: CLIENT connected to 64624, error: null
,2016-01-08T07:31:07.019Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:07.022 ThaliTest[1496:3284766] client: relay established
2016-01-08 08:31:07.022 ThaliTest[1496:3284766] client: new accepted socket: 0x195a9f10
,2016-01-08T07:31:07.038Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:08.277Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-08T07:31:08.290Z SendDataTCPServer.js: TCP/IP server has received 18615 bytes of data
,2016-01-08T07:31:08.306Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-08T07:31:08.346Z SendDataTCPServer.js: TCP/IP server has received 28328 bytes of data
,2016-01-08T07:31:08.361Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-08T07:31:08.425Z SendDataTCPServer.js: TCP/IP server has received 50299 bytes of data
,2016-01-08T07:31:08.428Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T07:31:08.442Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T07:31:08.444Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T07:31:08.485Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T07:31:08.486Z SendDataTCPServer.js: TCP/IP server has received 60225 bytes of data
,2016-01-08T07:31:08.511Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-08T07:31:08.538Z SendDataTCPServer.js: TCP/IP server has received 66795 bytes of data
,2016-01-08T07:31:08.540Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T07:31:08.554Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-08T07:31:08.557Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:08.558Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T07:31:08.559Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:08.560Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:08.562 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:31:08.562 ThaliTest[1496:3285038] client session: disconnectFromPeer: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:08.563 ThaliTest[1496:3285038] client session: disconnect
,2016-01-08 08:31:08.564 ThaliTest[1496:3285038] client session: stateChange:2->0 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:08.575 ThaliTest[1496:3285038] jxcore: disconnect: success
2016-01-08T07:31:08.576Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kpUZpA==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipho,ne6-1.O1yvYA==
2016-01-08T07:31:08.577Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.578Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.578Z SendDataConnector.j,s: do connect now
2016-01-08 08:31:08.579 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:08.579 ThaliTest[1496:3285038] client session: connect
2016-01-08 08:31:08.579 ThaliTest[1496:3285038] client session: stateChang,e:0->1 Apple-Iphone6-1.O1yvYA==
,2016-01-08T07:31:08.823Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T07:31:08.834Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:08.905 ThaliTest[1496:3285691] server session: not connected Apple-Iphone5-1
,2016-01-08 08:31:12.018 ThaliTest[1496:3284766] multipeer session: reset timer
2016-01-08 08:31:12.018 ThaliTest[1496:3284766] multipeer session: stop timer
2016-01-08 08:31:12.019 ThaliTest[1496:3284766] multipeer session: start timer: 0x194b2bd0
2016-,01-08 08:31:12.019 ThaliTest[1496:3284766] server session: connect
2016-01-08 08:31:12.019 ThaliTest[1496:3284766] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-08 08:31:12.026 ThaliTest[1496:3284766] server: accepting invitation Apple-Iphone6-1
,2016-01-08 08:31:12.536 ThaliTest[1496:3285691] client session: connected
2016-01-08 08:31:12.536 ThaliTest[1496:3285691] client session: stateChange:1->2 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:12.605 ThaliTest[1496:3285690] client session: fireConnectCallback: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:12.605 ThaliTest[1496:3285690] jxcore: connect: success
,2016-01-08T07:31:12.606Z SendDataConnector.js: CLIENT connected to 64628, error: null
2016-01-08T07:31:12.606Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:12.607 ThaliTest[1496:3284766] client: relay established
2016-01-08 08:31:12.607 ThaliTest[1496:3284766] client: new accepted socket: 0x195a7960
,2016-01-08T07:31:12.620Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 08:31:13.001 ThaliTest[1496:3284766] multipeer session: reset timer
2016-01-08 08:31:13.001 ThaliTest[1496:3284766] multipeer session: stop timer
,2016-01-08 08:31:13.001 ThaliTest[1496:3284766] multipeer session: start timer: 0x194b2bd0
2016-01-08 08:31:13.001 ThaliTest[1496:3284766] server session: connect
2016-01-08 08:31:13.001 ThaliTest[1496:3284766] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 08:31:13.003 ThaliTest[1496:3284766] server: accepting invitation Apple-Iphone5s-1
,2016-01-08T07:31:13.135Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T07:31:13.195Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T07:31:13.256Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:13.257Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-08T07:31:13.257Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:13.257Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:13.258 ThaliTest[1496:3285038] jxcore: disconnect
2016-01-08 08:31:13.258 ThaliTest[1496:3285038] client session: disconnectFromPeer: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:13.258 ThaliTest[1496:3285038] client session: disconnect
2016-01-08 08:31:13.258 ThaliTest[1496:3285038] client session: stateChange:2->0 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:13.262 ThaliTest[1496:3285038] jxcore: disconnect: success
2016-01-08T07:31:13.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.O1yvYA==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5s-1.WrRjQQ==
,2016-01-08T07:31:13.264Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:13.264Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:13.264Z SendDataConnector.js: do connect now
2016-01-08 08:31:13.264 ThaliTest[1496:3285038] jxcore: connect Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:13.264 ThaliTest[1496:3285038] client session: connect
2016-01-08 08:31:13.264 ThaliTest[1496:3285038] client session: stateChange:0->1 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:15.688 ThaliTest[1496:3285751] server session: connected
2016-01-08 08:31:15.688 ThaliTest[1496:3285751] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 08:31:15.717 ThaliTest[1496:3284766] server relay: connected (to port: 64620)
,2016-01-08T07:31:15.724Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:16.212Z SendDataTCPServer.js: TCP/IP server has received 3143 bytes of data
,2016-01-08T07:31:16.229Z SendDataTCPServer.js: TCP/IP server has received 30518 bytes of data
,2016-01-08T07:31:16.246Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T07:31:16.262Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-08T07:31:16.275Z SendDataTCPServer.js: TCP/IP server has received 68985 bytes of data
,2016-01-08 08:31:16.284 ThaliTest[1496:3285690] server session: connected
2016-01-08 08:31:16.285 ThaliTest[1496:3285690] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08T07:31:16.288Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T07:31:16.302Z SendDataTCPServer.js: TCP/IP server has received 82125 bytes of data
,2016-01-08T07:31:16.341Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T07:31:16.353Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-08T07:31:16.368Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:16.396 ThaliTest[1496:3284766] server relay: connected (to port: 64620)
,2016-01-08T07:31:16.403Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 08:31:16.470 ThaliTest[1496:3285691] server session: not connected Apple-Iphone6-1
,2016-01-08 08:31:16.741 ThaliTest[1496:3285690] client session: connected
,2016-01-08 08:31:16.741 ThaliTest[1496:3285690] client session: stateChange:1->2 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:16.758 ThaliTest[1496:3285691] client session: fireConnectCallback: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:16.759 ThaliTest[1496:3285691] jxcore: connect: success
,2016-01-08T07:31:16.759Z SendDataConnector.js: CLIENT connected to 64633, error: null
,2016-01-08T07:31:16.760Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:16.762 ThaliTest[1496:3284766] client: relay established
2016-01-08 08:31:16.763 ThaliTest[1496:3284766] client: new accepted socket: 0x194c6360
,2016-01-08T07:31:16.776Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:17.231Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T07:31:17.233Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T07:31:17.247Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T07:31:17.259Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08 08:31:17.307 ThaliTest[1496:3285720] server session: not connected Apple-Iphone5s-1
,2016-01-08T07:31:17.345Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T07:31:17.358Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T07:31:17.358Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-08T07:31:17.358Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:17.359Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-08 08:31:17.359 ThaliTest[1496:3285038] jxcore: disconnect
,2016-01-08 08:31:17.359 ThaliTest[1496:3285038] client session: disconnectFromPeer: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:17.359 ThaliTest[1496:3285038] client session: disconnect
2016-01-08 08:31:17.359 ThaliTest[1496:3285038] client session: state,Change:2->0 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:17.362 ThaliTest[1496:3285038] jxcore: disconnect: success
2016-01-08T07:31:17.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.WrRjQQ==
---- round done--------
startWithNextDevice
,weAreDoneNow, resultArray.length: 4
sendReportNow
,done, now sending data to server
,2016-01-08T07:31:17.374Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:17.374Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-08 08:31:17.611 ThaliTest[1496:3285038] jxcore: stopBroadcasting
,2016-01-08 08:31:17.612 ThaliTest[1496:3285038] THEMultipeerSession stopping peer
,2016-01-08 08:31:17.612 ThaliTest[1496:3285038] multipeer session: stop timer
,2016-01-08 08:31:17.613 ThaliTest[1496:3285038] server session: disconnect
,2016-01-08 08:31:17.613 ThaliTest[1496:3285038] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 08:31:17.621 ThaliTest[1496:3285038] server session: disconnect
2016-01-08 08:31:17.621 ThaliTest[1496:3285038] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 08:31:17.686 ThaliTest[1496:3285038] server session: disconnect
2016-01-08 08:31:17.687 ThaliTest[1496:3285038] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 08:31:17.689 ThaliTest[1496:3285038] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-08T07:31:17.704Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.705Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.707Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.707Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
