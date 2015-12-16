#### Test 50650278b44f053_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1C6DEB27-7618-4C0F-9F43-7869401ACA97/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1C6DEB27-7618-4C0F-9F43-7869401ACA97/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b44f053/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CA0497B4-A136-4286-9F23-E2FFAF26E05A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58801"
,(lldb)     command script import "/tmp/1C6DEB27-7618-4C0F-9F43-7869401ACA97/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 18:41:15.786 ThaliTest[308:119976] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9E0CBCFA-527D-4F27-8B6B-542C057C00F6/Library/Cookies/Cookies.binarycookies
,2015-12-16 18:41:16.132 ThaliTest[308:119976] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 18:41:16.133 ThaliTest[308:119976] Multi-tasking -> Device: YES, App: YES
,2015-12-16 18:41:16.142 ThaliTest[308:119976] Unlimited access to network resources
,2015-12-16 18:41:16.153 ThaliTest[308:119976] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 18:41:24.847 ThaliTest[308:119976] Resetting plugins due to page load.
,2015-12-16 18:41:28.252 ThaliTest[308:119976] Finished load of: file:///var/mobile/Containers/Bundle/Application/CA0497B4-A136-4286-9F23-E2FFAF26E05A/ThaliTest.app/www/index.html
,2015-12-16 18:41:28.431 ThaliTest[308:119976] JXcore Cordova plugin initializing
,2015-12-16 18:41:28.432 ThaliTest[308:120163] JXcore instance initializing
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
,2015-12-16 18:41:29.523 ThaliTest[308:119976] THREAD WARNING: ['JXcore'] took '78.206055' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 18:46:33.896 ThaliTest[308:120163] jxcore: startBroadcasting
,2015-12-16 18:46:33.915 ThaliTest[308:120163] server: starting Apple-Iphone6-1_PT3143.XZF93A==
,2015-12-16 18:46:33.924 ThaliTest[308:120163] multipeer session: start timer: 0x15b2f5d0
,2015-12-16 18:46:33.938 ThaliTest[308:120163] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3143
,2015-12-16 18:46:33.941 ThaliTest[308:120163] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-16 18:46:35.477 ThaliTest[308:119976] client: found peer: Apple-Iphone5-1_PT6761.ad6Xvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.ad6Xvw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT6761.ad6Xvw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 18:46:36.332 ThaliTest[308:120163] jxcore: stopBroadcasting
2015-12-16 18:46:36.333 ThaliTest[308:120163] THEMultipeerSession stopping peer
2015-12-16 18:46:36.333 ThaliTest[308:120163] multipeer session: stop timer
2015-12-16 18:46:36.334 Th,aliTest[308:120163] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 50641
,2015-12-16 18:46:36.399 ThaliTest[308:120163] jxcore: startBroadcasting
,2015-12-16 18:46:36.404 ThaliTest[308:120163] server: starting Apple-Iphone6-1_PT3143.YUb0wA==
,2015-12-16 18:46:36.406 ThaliTest[308:120163] multipeer session: start timer: 0x15b2b940
,2015-12-16 18:46:36.415 ThaliTest[308:120163] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3143
,2015-12-16 18:46:36.419 ThaliTest[308:120163] jxcore: startBroadcasting: success
,2015-12-16 18:46:36.424 ThaliTest[308:119976] client: found peer: Apple-Iphone5-1_PT6761.ad6Xvw==
StartBroadcasting started ok
null
2015-12-16T17:46:36.426Z SendDataTCPServer.js: TCP/IP server is bound to port: 50641
2015-12-16 18:46:36.426 ThaliTest[3,08:119976] client: found peer: Apple-Iphone6-1_PT3143.XZF93A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.ad6Xvw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:36.431Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:36.431Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:36.431Z SendDataConnector.js: do connect now
,2015-12-16 18:46:36.432 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:46:36.433 ThaliTest[308:120163] client session: connect
,2015-12-16 18:46:36.434 ThaliTest[308:120163] client session: stateChange:0->1 Apple-Iphone5-1_PT6761.ad6Xvw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 18:46:37.460 ThaliTest[308:119976] client: lost peer: Apple-Iphone6-1_PT3143.XZF93A==
2015-12-16 18:46:37.461 ThaliTest[308:119976] client session: onPeerLost: Apple-Iphone6-1_PT3143.XZF93A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT3143.XZF93A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-16 18:46:37.780 ThaliTest[308:119976] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-16 18:46:38.197 ThaliTest[308:119976] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 18:46:39.739 ThaliTest[308:119976] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6682.xKUG+w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-16 18:46:40.868 ThaliTest[308:119976] client: lost peer: Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:40.868 ThaliTest[308:119976] client session: onPeerLost: Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:40.868 ThaliTest[308:119976] clien,t session: onLinkFailure: Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:40.869 ThaliTest[308:119976] client session: disconnect
2015-12-16 18:46:40.869 ThaliTest[308:119976] client session: stateChange:1->0 Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 ,18:46:40.870 ThaliTest[308:119976] client session: fireConnectCallback: Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:40.870 ThaliTest[308:119976] jxcore: connect: fail: Peer disconnected
2015-12-16T17:46:40.871Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-16T17:46:40.872Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T17:46:40.872Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_P,T6761.ad6Xvw==","peerName":"(null)","peerAvailable":false}]
,2015-12-16T17:46:45.883Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:45.884Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:46:50.888 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:46:50.889 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:46:50.890Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.ad6Xvw==,
2015-12-16T17:46:50.890Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6761.ad6Xvw== with availability status: true
2015-12-16T17:46:50.890Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:50.891Z SendDataConnector.js: do connect now
,2015-12-16 18:46:50.892 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:50.893 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:46:50.893 ThaliTest[308:120163] jxcore:, connect: fail: Peer unreachable
2015-12-16T17:46:50.894Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:46:50.894Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:46:50.894Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:46:55.897Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:46:55.898Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:00.905 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:00.905 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:00.906Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.ad6Xvw==,
2015-12-16T17:47:00.906Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6761.ad6Xvw== with availability status: true
2015-12-16T17:47:00.906Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:47:00.907Z SendDataConnector.js: do connect now
2015-12-16 18:47:00.907 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:00.908 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:00.909 ThaliTest[308:120163] jxcore: connect: fail: Peer unreachable
2015-12-16T17:47:00.910Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:00.910Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
2015-12-16T17:47:00.910Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:05.917Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16T17:47:05.917Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:06.415 ThaliTest[308:119976] multipeer session: restart
,2015-12-16 18:47:10.927 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:10.928 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:10.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.ad6Xvw==,
2015-12-16T17:47:10.929Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6761.ad6Xvw== with availability status: true
2015-12-16T17:47:10.929Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
2015-,12-16T17:47:10.929Z SendDataConnector.js: do connect now
,2015-12-16 18:47:10.931 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:47:10.932 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16 18:47:10.932 ThaliTest[308:120163] jxcore:, connect: fail: Peer unreachable
2015-12-16T17:47:10.933Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:10.934Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:10.934Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:15.944Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.ad6Xvw==
2015-12-16T17:47:15.945Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:20.953 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:20.953 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:20.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.ad6Xvw==,
2015-12-16T17:47:20.954Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6761.ad6Xvw== with availability status: true
2015-12-16T17:47:20.954Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.ad6Xvw==
2015-,12-16T17:47:20.955Z SendDataConnector.js: do connect now
,2015-12-16 18:47:20.955 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:20.956 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.ad6Xvw==
,2015-12-16 18:47:20.957 ThaliTest[308:120163] jxcore: connect: fail: Peer unreachable
2015-12-16T17:47:20.958Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:20.959Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-16T17:47:20.961Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 18:47:20.962 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:20.963 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:20.963Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.ad6Xvw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:20.967Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:20.967Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:20.968Z SendDataConnector.js: do connect now
,2015-12-16 18:47:20.969 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:20.970 ThaliTest[308:120163] client session: connect
2015-12-16 18:47:20.970 ThaliTest[308:120163] client session: stateChange:0->1 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:20.983 ThaliTest[308:119976] client: lost peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:20.983 ThaliTest[308:119976] client session: onPeerLost: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:20.984 ThaliTest[308:119976] clien,t session: onLinkFailure: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:20.984 ThaliTest[308:119976] client session: disconnect
2015-12-16 18:47:20.984 ThaliTest[308:119976] client session: stateChange:1->0 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:21.039 ThaliTest[308:119976] client session: fireConnectCallback: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:21.039 ThaliTest[308:119976] jxcore: connect: fail: Peer disconnected
2015-12-16T17:47:21.040Z SendDataConnector.js: CLIEN,T connected to 0, error: Peer disconnected
,2015-12-16T17:47:21.042Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-16T17:47:21.042Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":false}]
,2015-12-16 18:47:25.020 ThaliTest[308:119976] multipeer session: reset timer
2015-12-16 18:47:25.020 ThaliTest[308:119976] multipeer session: stop timer
2015-12-16 18:47:25.020 ThaliTest[308:119976] multipeer session: start timer: 0x15b2b940
,2015-12-16 18:47:25.022 ThaliTest[308:119976] server session: connect
2015-12-16 18:47:25.022 ThaliTest[308:119976] server session: stateChange:0->1 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:25.032 ThaliTest[308:119976] server: accepting invitation Apple-Iphone5-1_PT6761
,2015-12-16T17:47:26.044Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:26.045Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:27.970 ThaliTest[308:120830] server session: connected
2015-12-16 18:47:27.971 ThaliTest[308:120830] server session: stateChange:1->2 Apple-Iphone5-1_PT6761
,2015-12-16 18:47:28.035 ThaliTest[308:119976] server relay: connected (to port: 50641)
,2015-12-16T17:47:28.044Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:28.567Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-16T17:47:28.581Z SendDataTCPServer.js: TCP/IP server has received 27760 bytes of data
,2015-12-16T17:47:28.596Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-16T17:47:28.635Z SendDataTCPServer.js: TCP/IP server has received 66044 bytes of data
,2015-12-16T17:47:28.652Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 18:47:29.028 ThaliTest[308:120909] server session: not connected Apple-Iphone5-1_PT6761
,2015-12-16 18:47:29.196 ThaliTest[308:119976] multipeer session: reset timer
2015-12-16 18:47:29.196 ThaliTest[308:119976] multipeer session: stop timer
2015-12-16 18:47:29.197 ThaliTest[308:119976] multipeer session: start timer: 0x15b2b940
2015-12-16 ,18:47:29.197 ThaliTest[308:119976] server session: connect
2015-12-16 18:47:29.198 ThaliTest[308:119976] server session: stateChange:0->1 Apple-IpadAir2-1_PT5378
2015-12-16 18:47:29.206 ThaliTest[308:119976] server: accepting invitation Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:31.056 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:31.056 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:31.057Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:31.057Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:31.057Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
2015-,12-16T17:47:31.058Z SendDataConnector.js: do connect now
2015-12-16 18:47:31.058 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:31.059 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mh,w==
2015-12-16 18:47:31.059 ThaliTest[308:120163] jxcore: connect: fail: Peer unreachable
2015-12-16T17:47:31.059Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:31.059Z SendDataConnector.js: CLIENT Can not Connect,: Peer unreachable
,2015-12-16T17:47:31.063Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16 18:47:31.947 ThaliTest[308:120827] server session: connected
2015-12-16 18:47:31.947 ThaliTest[308:120827] server session: stateChange:1->2 Apple-IpadAir2-1_PT5378
,2015-12-16 18:47:31.964 ThaliTest[308:119976] server relay: connected (to port: 50641)
,2015-12-16T17:47:31.975Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T17:47:32.219Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-16T17:47:32.236Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-16T17:47:32.251Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-16T17:47:32.267Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-16T17:47:32.282Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-16T17:47:32.295Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16T17:47:36.075Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:36.076Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:41.080 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:41.081 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:41.081Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:41.082Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:41.082Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16T17:47:41.082Z SendDataConnector.js: do connect now
,2015-12-16 18:47:41.083 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:41.084 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:41.085 ThaliTest[308:120163] jxcore:, connect: fail: Peer unreachable
2015-12-16T17:47:41.086Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T17:47:41.086Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:41.086Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16 18:47:43.369 ThaliTest[308:120827] server session: not connected Apple-IpadAir2-1_PT5378
,2015-12-16T17:47:46.096Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:46.097Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:51.104 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:47:51.104 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:47:51.105Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:47:51.105Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:47:51.106Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
2015-,12-16T17:47:51.106Z SendDataConnector.js: do connect now
,2015-12-16 18:47:51.107 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:51.107 ThaliTest[308:120163] client: connect: unreachable Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:47:51.109 ThaliTest[308:120163] jxcore: connect: fail: Peer unreachable
2015-12-16T17:47:51.109Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-16T17:47:51.110Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T17:47:51.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T17:47:56.112Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:47:56.113Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:47:59.198 ThaliTest[308:119976] multipeer session: restart
,2015-12-16 18:47:59.236 ThaliTest[308:119976] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:47:59.236 ThaliTest[308:119976] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
,2015-12-16 18:47:59.241 ThaliTest[308:119976] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:48:01.116 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:48:01.117 ThaliTest[308:120163] jxcore: disconnect: fail
2015-12-16T17:48:01.117Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==,
2015-12-16T17:48:01.117Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6761.1E6mhw== with availability status: true
2015-12-16T17:48:01.118Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16T17:48:01.118Z SendDataConnector.js: do connect now
,2015-12-16 18:48:01.119 ThaliTest[308:120163] jxcore: connect Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:48:01.120 ThaliTest[308:120163] client session: connect
2015-12-16 18:48:01.121 ThaliTest[308:120163] client session: stateChange:0->1 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:04.728 ThaliTest[308:121018] client session: connected
2015-12-16 18:48:04.728 ThaliTest[308:121018] client session: stateChange:1->2 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:04.772 ThaliTest[308:121016] client session: fireConnectCallback: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:48:04.773 ThaliTest[308:121016] jxcore: connect: success
2015-12-16T17:48:04.774Z SendDataConnector.js: CLIENT connected to 50648, error: null
2015-12-16T17:48:04.774Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:48:04.779 ThaliTest[308:119976] client: relay established
2015-12-16 18:48:04.779 ThaliTest[308:119976] client: new accepted socket: 0x14600660
,2015-12-16T17:48:04.794Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:48:05.153Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-16T17:48:05.176Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-16T17:48:05.188Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:48:05.189Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T17:48:05.189Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:48:05.189Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:05.190 ThaliTest[308:120163] jxcore: disconnect
,2015-12-16 18:48:05.191 ThaliTest[308:120163] client session: disconnectFromPeer: Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:05.191 ThaliTest[308:120163] client session: disconnect
,2015-12-16 18:48:05.192 ThaliTest[308:120163] client session: stateChange:2->0 Apple-Iphone5-1_PT6761.1E6mhw==
,2015-12-16 18:48:05.255 ThaliTest[308:120163] jxcore: disconnect: success
2015-12-16T17:48:05.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6761.1E6mhw==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:48:05.256Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16T17:48:05.256Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16T17:48:05.256Z SendDataConnector.js: do connect now
,2015-12-16 18:48:05.257 ThaliTest[308:120163] jxcore: connect Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-16 18:48:05.257 ThaliTest[308:120163] client session: connect
2015-12-16 18:48:05.257 ThaliTest[308:120163] client session: stateChange:0->1 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:08.448 ThaliTest[308:121015] client session: connected
2015-12-16 18:48:08.449 ThaliTest[308:121015] client session: stateChange:1->2 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:08.464 ThaliTest[308:121017] client session: fireConnectCallback: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:08.465 ThaliTest[308:121017] jxcore: connect: success
,2015-12-16T17:48:08.466Z SendDataConnector.js: CLIENT connected to 50651, error: null
,2015-12-16T17:48:08.467Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:48:08.470 ThaliTest[308:119976] client: relay established
2015-12-16 18:48:08.471 ThaliTest[308:119976] client: new accepted socket: 0x15b209c0
,2015-12-16T17:48:08.484Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:48:08.763Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16T17:48:08.796Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-16T17:48:08.810Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-16T17:48:08.823Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:48:08.823Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-16T17:48:08.823Z SendDataConnector.js: CLIENT Stop now
,2015-12-16T17:48:08.824Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:08.824 ThaliTest[308:120163] jxcore: disconnect
,2015-12-16 18:48:08.824 ThaliTest[308:120163] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:08.825 ThaliTest[308:120163] client session: disconnect
,2015-12-16 18:48:08.826 ThaliTest[308:120163] client session: stateChange:2->0 Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:08.891 ThaliTest[308:120163] jxcore: disconnect: success
2015-12-16T17:48:08.892Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5378.J91vGA==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:48:08.893Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:48:08.893Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16T17:48:08.893Z SendDataConnector.js: do connect now
,2015-12-16 18:48:08.894 ThaliTest[308:120163] jxcore: connect Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:48:08.894 ThaliTest[308:120163] client session: connect
,2015-12-16 18:48:08.895 ThaliTest[308:120163] client session: stateChange:0->1 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:48:11.531 ThaliTest[308:121017] client session: connected
2015-12-16 18:48:11.531 ThaliTest[308:121017] client session: stateChange:1->2 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:48:11.540 ThaliTest[308:121017] client session: fireConnectCallback: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:48:11.541 ThaliTest[308:121017] jxcore: connect: success
2015-12-16T17:48:11.543Z SendDataConnector.js: CLIENT connected to 50654, error: null
2015-12-16T17:48:11.544Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 18:48:11.548 ThaliTest[308:119976] client: relay established
2015-12-16 18:48:11.548 ThaliTest[308:119976] client: new accepted socket: 0x14605560
,2015-12-16T17:48:11.560Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T17:48:11.838Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-16T17:48:11.851Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-16T17:48:11.864Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-16T17:48:11.899Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-16T17:48:12.021Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-16T17:48:12.021Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-16T17:48:12.021Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:48:12.021Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:12.022 ThaliTest[308:120163] jxcore: disconnect
2015-12-16 18:48:12.022 ThaliTest[308:120163] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6682.xKUG+w==
2015-12-16 18:48:12.022 ThaliTest[308:120163] client session: disconnect
2015-12-16 18:48:12.022 ThaliTest[308:120163] client session: stateChange:2->0 Apple-Iphone5s-1_PT6682.xKUG+w==
,2015-12-16 18:48:12.027 ThaliTest[308:120163] jxcore: disconnect: success
2015-12-16T17:48:12.027Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6682.xKUG+w==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-16T17:48:12.030Z SendDataConnector.js: CLIENT Stop now
2015-12-16T17:48:12.030Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-16 18:48:29.198 ThaliTest[308:119976] multipeer session: restart
,2015-12-16 18:48:29.235 ThaliTest[308:119976] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
,2015-12-16 18:48:29.240 ThaliTest[308:119976] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-16 18:48:29.243 ThaliTest[308:119976] client: found peer: Apple-Iphone5s-1_PT6682.xKUG+w==
,teardown
,testSendData stopped
2015-12-16 18:48:54.991 ThaliTest[308:120163] jxcore: stopBroadcasting
2015-12-16 18:48:54.991 ThaliTest[308:120163] THEMultipeerSession stopping peer
2015-12-16 18:48:54.992 ThaliTest[308:120163] multipeer session: stop timer
2015,-12-16 18:48:54.992 ThaliTest[308:120163] server session: disconnect
2015-12-16 18:48:54.992 ThaliTest[308:120163] server session: stateChange:2->0 Apple-IpadAir2-1_PT5378
,2015-12-16 18:48:55.000 ThaliTest[308:120163] server session: disconnect
2015-12-16 18:48:55.001 ThaliTest[308:120163] server session: stateChange:2->0 Apple-Iphone5-1_PT6761
2015-12-16 18:48:55.008 ThaliTest[308:120163] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T17:48:55.029Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-16T17:48:55.031Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-16T17:48:55.032Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
