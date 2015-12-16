#### Test 506502783fcf234_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7AECA9BA-B6D4-44F5-9867-C689714A8430/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7AECA9BA-B6D4-44F5-9867-C689714A8430/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502783fcf234/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5FBB0114-5172-4CB6-ACA8-58FEE954D294/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58317"
,(lldb)     command script import "/tmp/7AECA9BA-B6D4-44F5-9867-C689714A8430/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 04:54:47.622 ThaliTest[226:50752] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B4D534AF-F53D-489A-9090-219068E89828/Library/Cookies/Cookies.binarycookies
,2015-12-16 04:54:47.740 ThaliTest[226:50752] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 04:54:47.742 ThaliTest[226:50752] Multi-tasking -> Device: YES, App: YES
,2015-12-16 04:54:47.749 ThaliTest[226:50752] Unlimited access to network resources
,2015-12-16 04:54:47.761 ThaliTest[226:50752] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 04:54:57.402 ThaliTest[226:50752] Resetting plugins due to page load.
,2015-12-16 04:55:01.230 ThaliTest[226:50752] Finished load of: file:///var/mobile/Containers/Bundle/Application/5FBB0114-5172-4CB6-ACA8-58FEE954D294/ThaliTest.app/www/index.html
,2015-12-16 04:55:01.441 ThaliTest[226:50752] JXcore Cordova plugin initializing
,2015-12-16 04:55:01.442 ThaliTest[226:50922] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-16 04:55:03.906 ThaliTest[226:50752] THREAD WARNING: ['JXcore'] took '157.841797' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 05:01:17.743 ThaliTest[226:50922] jxcore: startBroadcasting
,2015-12-16 05:01:17.756 ThaliTest[226:50922] server: starting Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:01:17.759 ThaliTest[226:50922] multipeer session: start timer: 0x1aa11330
2015-12-16 05:01:17.759 ThaliTest[226:50922] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8849
2015-12-16 05:01:17.759 ThaliTest[226:50922] jxcore: startBro,adcasting: success
StartBroadcasting started ok
,2015-12-16 05:01:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:02:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:02:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:03:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:03:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:04:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:04:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:05:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:05:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:06:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:06:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:07:17.759 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:07:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:08:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:08:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:09:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:09:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:10:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:10:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:11:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:11:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:12:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:12:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:13:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:13:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:14:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:14:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:15:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:15:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:16:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:16:47.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:17:17.760 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:17:47.760 ThaliTest[226:50752] multipeer session: restart
,timeout now
,weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 05:17:58.010 ThaliTest[226:50922] jxcore: stopBroadcasting
2015-12-16 05:17:58.010 ThaliTest[226:50922] THEMultipeerSession stopping peer
2015-12-16 05:17:58.010 ThaliTest[226:50922] multipeer session: stop timer
2015-12-16 05:17:58.011 ThaliTest[226:50922] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":1}bt-address length : 0
,daya100000
check server
serverPort is 49833
2015-12-16 05:17:58.073 ThaliTest[226:50922] jxcore: startBroadcasting
,2015-12-16 05:17:58.079 ThaliTest[226:50922] server: starting Apple-Iphone5-1_PT8849.jfCjsw==
,2015-12-16 05:17:58.080 ThaliTest[226:50922] multipeer session: start timer: 0x1ac2ebf0
,2015-12-16 05:17:58.090 ThaliTest[226:50922] THEMultipeerSession initialized peer Apple-Iphone5-1_PT8849
,2015-12-16 05:17:58.093 ThaliTest[226:50922] jxcore: startBroadcasting: success
2015-12-16 05:17:58.095 ThaliTest[226:50752] client: found peer: Apple-Iphone5-1_PT8849.8OxAFA==
StartBroadcasting started ok
null
,2015-12-16T04:17:58.099Z SendDataTCPServer.js: TCP/IP server is bound to port: 49833
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8849.8OxAFA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:17:58.109Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:17:58.110Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:17:58.111Z SendDataConnector.js: do connect now
,2015-12-16 05:17:58.112 ThaliTest[226:50922] jxcore: connect Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:17:58.114 ThaliTest[226:50922] client session: connect
,2015-12-16 05:17:58.115 ThaliTest[226:50922] client session: stateChange:0->1 Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:17:59.137 ThaliTest[226:50752] client: lost peer: Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:17:59.137 ThaliTest[226:50752] client session: onPeerLost: Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:17:59.138 ThaliTest[226:50752] client s,ession: onLinkFailure: Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:17:59.138 ThaliTest[226:50752] client session: disconnect
2015-12-16 05:17:59.138 ThaliTest[226:50752] client session: stateChange:1->0 Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:17,:59.139 ThaliTest[226:50752] client session: fireConnectCallback: Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:17:59.139 ThaliTest[226:50752] jxcore: connect: fail: Peer disconnected
2015-12-16T04:17:59.140Z SendDataConnector.js: CLIENT connected to 0, ,error: Peer disconnected
2015-12-16T04:17:59.140Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-16T04:17:59.140Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT8849.8,OxAFA==","peerName":"(null)","peerAvailable":false}]
,2015-12-16T04:18:04.146Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:18:04.147Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:18:09.157 ThaliTest[226:50922] jxcore: disconnect
2015-12-16 05:18:09.158 ThaliTest[226:50922] jxcore: disconnect: fail
2015-12-16T04:18:09.158Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8849.8OxAFA==
2,015-12-16T04:18:09.159Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT8849.8OxAFA== with availability status: true
2015-12-16T04:18:09.159Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:18:09.160Z SendDataConnector.js: do connect now
2015-12-16 05:18:09.161 ThaliTest[226:50922] jxcore: connect Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:09.161 ThaliTest[226:50922] client: connect: unreachable Apple-Iphone5-1_PT8849.8O,xAFA==
2015-12-16 05:18:09.161 ThaliTest[226:50922] jxcore: connect: fail: Peer unreachable
,2015-12-16T04:18:09.162Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T04:18:09.162Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T04:18:09.162Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T04:18:14.165Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:18:14.166Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:18:19.178 ThaliTest[226:50922] jxcore: disconnect
2015-12-16 05:18:19.179 ThaliTest[226:50922] jxcore: disconnect: fail
2015-12-16T04:18:19.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8849.8OxAFA==
2,015-12-16T04:18:19.180Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT8849.8OxAFA== with availability status: true
2015-12-16T04:18:19.180Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8849.8OxAFA==
2015-12,-16T04:18:19.181Z SendDataConnector.js: do connect now
,2015-12-16 05:18:19.181 ThaliTest[226:50922] jxcore: connect Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:19.182 ThaliTest[226:50922] client: connect: unreachable Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:19.182 ThaliTest[226:50922] jxcore: co,nnect: fail: Peer unreachable
2015-12-16T04:18:19.182Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T04:18:19.183Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-16T04:18:19.183Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T04:18:24.185Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:18:24.186Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:18:28.094 ThaliTest[226:50752] multipeer session: restart
,2015-12-16 05:18:29.191 ThaliTest[226:50922] jxcore: disconnect
2015-12-16 05:18:29.192 ThaliTest[226:50922] jxcore: disconnect: fail
2015-12-16T04:18:29.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8849.8OxAFA==
2,015-12-16T04:18:29.193Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT8849.8OxAFA== with availability status: true
2015-12-16T04:18:29.193Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8849.8OxAFA==
2015-12,-16T04:18:29.194Z SendDataConnector.js: do connect now
,2015-12-16 05:18:29.195 ThaliTest[226:50922] jxcore: connect Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:29.195 ThaliTest[226:50922] client: connect: unreachable Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:29.195 ThaliTest[226:50922] jxcore: connect: fail: Peer unreachable
,2015-12-16T04:18:29.196Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T04:18:29.196Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-16T04:18:29.196Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-16T04:18:34.203Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16T04:18:34.204Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT8849.8OxAFA==
,2015-12-16 05:18:39.206 ThaliTest[226:50922] jxcore: disconnect
2015-12-16 05:18:39.207 ThaliTest[226:50922] jxcore: disconnect: fail
2015-12-16T04:18:39.207Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8849.8OxAFA==
2,015-12-16T04:18:39.208Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT8849.8OxAFA== with availability status: true
2015-12-16T04:18:39.208Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT8849.8OxAFA==
2015-12,-16T04:18:39.208Z SendDataConnector.js: do connect now
,2015-12-16 05:18:39.209 ThaliTest[226:50922] jxcore: connect Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:39.210 ThaliTest[226:50922] client: connect: unreachable Apple-Iphone5-1_PT8849.8OxAFA==
2015-12-16 05:18:39.210 ThaliTest[226:50922] jxcore: connect: fail: Peer unreachable
,2015-12-16T04:18:39.211Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-16T04:18:39.211Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2015-12-16T04:18:39.213Z SendDataConnector.js: CLIENT Stop now
2015-12-16 05:18:39.213 ThaliTest[226:50922] jxcore: disconnect
2015-12-16 05:18:39.213 ThaliTest[226:50922] jxcore: disconnect: fail
2015-12-16T04:18:39.214Z SendDataConnec,tor.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT8849.8OxAFA==
,---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 1
,sendReportNow
,done, now sending data to server
,2015-12-16T04:18:39.218Z SendDataConnector.js: CLIENT Stop now
,teardown
,testSendData stopped
,2015-12-16 05:18:39.918 ThaliTest[226:50922] jxcore: stopBroadcasting
,2015-12-16 05:18:39.919 ThaliTest[226:50922] THEMultipeerSession stopping peer
2015-12-16 05:18:39.919 ThaliTest[226:50922] multipeer session: stop timer
2015-12-16 05:18:39.919 ThaliTest[226:50922] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-16T04:18:39.921Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
