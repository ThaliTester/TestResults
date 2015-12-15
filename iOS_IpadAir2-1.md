#### Test 506502782ddd83f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/EC9A6AE9-ACC4-431E-BC5A-9E43AB041DB7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EC9A6AE9-ACC4-431E-BC5A-9E43AB041DB7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782ddd83f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1CB2738-050E-44CE-917D-B2DBDCC547B9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56414"
,(lldb)     command script import "/tmp/EC9A6AE9-ACC4-431E-BC5A-9E43AB041DB7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 05:41:37.271 ThaliTest[1154:1232768] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CB67E92A-C1CA-4AFC-8BFA-6FEDDC882986/Library/Cookies/Cookies.binarycookies
,2015-12-15 05:41:37.640 ThaliTest[1154:1232768] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 05:41:37.641 ThaliTest[1154:1232768] Multi-tasking -> Device: YES, App: YES
,2015-12-15 05:41:37.649 ThaliTest[1154:1232768] Unlimited access to network resources
,2015-12-15 05:41:37.658 ThaliTest[1154:1232768] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 05:41:46.639 ThaliTest[1154:1232768] Resetting plugins due to page load.
,2015-12-15 05:41:49.915 ThaliTest[1154:1232768] Finished load of: file:///var/mobile/Containers/Bundle/Application/B1CB2738-050E-44CE-917D-B2DBDCC547B9/ThaliTest.app/www/index.html
,2015-12-15 05:41:49.929 ThaliTest[1154:1232768] JXcore Cordova plugin initializing
,2015-12-15 05:41:49.931 ThaliTest[1154:1232976] JXcore instance initializing
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
,2015-12-15 05:41:51.011 ThaliTest[1154:1232768] THREAD WARNING: ['JXcore'] took '71.092041' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 05:46:57.985 ThaliTest[1154:1232976] jxcore: startBroadcasting
,2015-12-15 05:46:58.002 ThaliTest[1154:1232976] server: starting Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:46:58.004 ThaliTest[1154:1232976] multipeer session: start timer: 0x14792b30
2015-12-15 05:46:58.004 ThaliTest[1154:1232976] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2678
,2015-12-15 05:46:58.005 ThaliTest[1154:1232976] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-15 05:46:59.096 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT356.zzR6Ww==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-15 05:47:00.627 ThaliTest[1154:1232768] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
,teardown
,testFindPeers stopped
,2015-12-15 05:47:00.994 ThaliTest[1154:1232976] jxcore: stopBroadcasting
,2015-12-15 05:47:00.994 ThaliTest[1154:1232976] THEMultipeerSession stopping peer
,2015-12-15 05:47:00.995 ThaliTest[1154:1232976] multipeer session: stop timer
,2015-12-15 05:47:00.996 ThaliTest[1154:1232976] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 58618
,2015-12-15 05:47:01.056 ThaliTest[1154:1232976] jxcore: startBroadcasting
,2015-12-15 05:47:01.059 ThaliTest[1154:1232976] server: starting Apple-IpadAir2-1_PT2678.ad0lIQ==
,2015-12-15 05:47:01.061 ThaliTest[1154:1232976] multipeer session: start timer: 0x14796240
2015-12-15 05:47:01.061 ThaliTest[1154:1232976] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT2678
2015-12-15 05:47:01.062 ThaliTest[1154:1232976] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
2015-12-15T04:47:01.068Z SendDataTCPServer.js: TCP/IP server is bound to port: 58618
,2015-12-15 05:47:01.082 ThaliTest[1154:1232768] client: found peer: Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:01.082 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:01.083 ThaliTest[1154:1232768] client: found peer: Apple-Iphone6-1_PT7824.Q97KpQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:01.088Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:01.088Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15T04:47:01.088Z SendDataConnector.js: do connect now
,2015-12-15 05:47:01.089 ThaliTest[1154:1232976] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:01.089 ThaliTest[1154:1232976] client session: connect
,2015-12-15 05:47:01.090 ThaliTest[1154:1232976] client session: stateChange:0->1 Apple-IpadAir2-1_PT2678.RP+Etw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 05:47:02.874 ThaliTest[1154:1232768] client: lost peer: Apple-Iphone6-1_PT7824.Q97KpQ==
2015-12-15 05:47:02.875 ThaliTest[1154:1232768] client session: onPeerLost: Apple-Iphone6-1_PT7824.Q97KpQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.Q97KpQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-15 05:47:03.082 ThaliTest[1154:1232768] client: lost peer: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:03.082 ThaliTest[1154:1232768] client session: onPeerLost: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:03.082 ThaliTest[1154:1232768] client session: onLinkFailure: Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:03.082 ThaliTest[1154:1232768] client session: disconnect
2015-12-15 05:47:03.083 ThaliTest[1154:1232768] client session: stateChange:1->0 Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:03.083 ThaliTest[1154:1232768] client session: fireConnectCallback: Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15 05:47:03.084 ThaliTest[1154:1232768] jxcore: connect: fail: Peer disconnected
,2015-12-15 05:47:03.084 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:47:03.086Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-15T04:47:03.087Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-15T04:47:03.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2678.RP+Etw==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4162.hYB3TQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 05:47:03.270 ThaliTest[1154:1232768] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:03.270 ThaliTest[1154:1232768] client: lost peer: Apple-Iphone5-1_PT356.zzR6Ww==
,2015-12-15 05:47:03.271 ThaliTest[1154:1232768] client session: onPeerLost: Apple-Iphone5-1_PT356.zzR6Ww==
2015-12-15 05:47:03.271 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7824.jNC0Kw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.zzR6Ww==","peerName":"(null)",",peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT356.aa89HA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15T04:47:08.097Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:08.097Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:13.102 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:13.103 ThaliTest[1154:1232976] jxcore: disconnect: fail
,2015-12-15T04:47:13.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:13.104Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
,2015-12-15T04:47:13.105Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:13.106Z SendDataConnector.js: do connect now
,2015-12-15 05:47:13.107 ThaliTest[1154:1232976] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:13.107 ThaliTest[1154:1232976] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:13.108 ThaliTest[1154:1232976] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:13.109Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:47:13.109Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:47:13.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:18.113Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:18.114Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:23.117 ThaliTest[1154:1232976] jxcore: disconnect
2015-12-15 05:47:23.118 ThaliTest[1154:1232976] jxcore: disconnect: fail
,2015-12-15T04:47:23.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:23.119Z SendDataConnector.js: Connect (retry count 2) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
,2015-12-15T04:47:23.120Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:23.121Z SendDataConnector.js: do connect now
,2015-12-15 05:47:23.122 ThaliTest[1154:1232976] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:23.122 ThaliTest[1154:1232976] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:23.123 ThaliTest[1154:1232976] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:23.124Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:47:23.124Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:47:23.125Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:28.132Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:28.132Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:31.062 ThaliTest[1154:1232768] multipeer session: restart
,2015-12-15 05:47:31.093 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:47:31.094 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:31.094 ThaliTest[1154:1232768] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:33.137 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:33.138 ThaliTest[1154:1232976] jxcore: disconnect: fail
,2015-12-15T04:47:33.139Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:33.139Z SendDataConnector.js: Connect (retry count 3) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
,2015-12-15T04:47:33.140Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:33.140Z SendDataConnector.js: do connect now
,2015-12-15 05:47:33.142 ThaliTest[1154:1232976] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:33.142 ThaliTest[1154:1232976] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:33.143 ThaliTest[1154:1232976] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:33.144Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-15T04:47:33.145Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-15T04:47:33.145Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T04:47:38.157Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15T04:47:38.157Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:43.169 ThaliTest[1154:1232976] jxcore: disconnect
2015-12-15 05:47:43.169 ThaliTest[1154:1232976] jxcore: disconnect: fail
,2015-12-15T04:47:43.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15T04:47:43.171Z SendDataConnector.js: Connect (retry count 4) to peer Apple-IpadAir2-1_PT2678.RP+Etw== with availability status: true
,2015-12-15T04:47:43.171Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2678.RP+Etw==
2015-12-15T04:47:43.171Z SendDataConnector.js: do connect now
,2015-12-15 05:47:43.173 ThaliTest[1154:1232976] jxcore: connect Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:43.173 ThaliTest[1154:1232976] client: connect: unreachable Apple-IpadAir2-1_PT2678.RP+Etw==
,2015-12-15 05:47:43.174 ThaliTest[1154:1232976] jxcore: connect: fail: Peer unreachable
,2015-12-15T04:47:43.175Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T04:47:43.175Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-15T04:47:43.178Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 05:47:43.179 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:43.179 ThaliTest[1154:1232976] jxcore: disconnect: fail
,2015-12-15T04:47:43.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2678.RP+Etw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:47:43.184Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:47:43.184Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15T04:47:43.185Z SendDataConnector.js: do connect now
,2015-12-15 05:47:43.186 ThaliTest[1154:1232976] jxcore: connect Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:43.187 ThaliTest[1154:1232976] client session: connect
,2015-12-15 05:47:43.187 ThaliTest[1154:1232976] client session: stateChange:0->1 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:43.307 ThaliTest[1154:1232768] multipeer session: reset timer
,2015-12-15 05:47:43.307 ThaliTest[1154:1232768] multipeer session: stop timer
,2015-12-15 05:47:43.308 ThaliTest[1154:1232768] multipeer session: start timer: 0x14796240
,2015-12-15 05:47:43.308 ThaliTest[1154:1232768] server session: connect
2015-12-15 05:47:43.309 ThaliTest[1154:1232768] server session: stateChange:0->1 Apple-Iphone5-1_PT356
,2015-12-15 05:47:43.316 ThaliTest[1154:1232768] server: accepting invitation Apple-Iphone5-1_PT356
,2015-12-15 05:47:45.869 ThaliTest[1154:1234392] server session: connected
2015-12-15 05:47:45.870 ThaliTest[1154:1234392] server session: stateChange:1->2 Apple-Iphone5-1_PT356
,2015-12-15 05:47:45.897 ThaliTest[1154:1232768] server relay: connected (to port: 58618)
,2015-12-15T04:47:45.907Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:47:46.415Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-15T04:47:46.431Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-15 05:47:46.436 ThaliTest[1154:1234392] client session: connected
,2015-12-15 05:47:46.437 ThaliTest[1154:1234392] client session: stateChange:1->2 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:46.440 ThaliTest[1154:1234392] client session: fireConnectCallback: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:47:46.441 ThaliTest[1154:1234392] jxcore: connect: success
,2015-12-15T04:47:46.442Z SendDataConnector.js: CLIENT connected to 58626, error: null
,2015-12-15T04:47:46.443Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:47:46.449 ThaliTest[1154:1232768] client: relay established
2015-12-15 05:47:46.449 ThaliTest[1154:1232768] client: new accepted socket: 0x16556de0
,2015-12-15T04:47:46.467Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
2015-12-15T04:47:46.470Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:47:46.724Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T04:47:46.813Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-15 05:47:46.839 ThaliTest[1154:1234401] server session: not connected Apple-Iphone5-1_PT356
,2015-12-15T04:47:46.850Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-15T04:47:46.863Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:47:46.864Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T04:47:46.864Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:46.864Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:46.865 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:46.865 ThaliTest[1154:1232976] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:46.865 ThaliTest[1154:1232976] client session: disconnect
,2015-12-15 05:47:46.866 ThaliTest[1154:1232976] client session: stateChange:2->0 Apple-Iphone5s-1_PT4162.hYB3TQ==
,2015-12-15 05:47:46.929 ThaliTest[1154:1232976] jxcore: disconnect: success
,2015-12-15T04:47:46.929Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4162.hYB3TQ==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15T04:47:46.930Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15T04:47:46.930Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15T04:47:46.930Z SendDataConnector.js: do connect now
,2015-12-15 05:47:46.931 ThaliTest[1154:1232976] jxcore: connect Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:46.931 ThaliTest[1154:1232976] client session: connect
,2015-12-15 05:47:46.931 ThaliTest[1154:1232976] client session: stateChange:0->1 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:50.055 ThaliTest[1154:1234392] client session: connected
2015-12-15 05:47:50.055 ThaliTest[1154:1234392] client session: stateChange:1->2 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:50.059 ThaliTest[1154:1234392] client session: fireConnectCallback: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:47:50.060 ThaliTest[1154:1234392] jxcore: connect: success
2015-12-15T04:47:50.061Z SendDataConnector.js: CLIENT connected to 58629, error: null
,2015-12-15T04:47:50.062Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:47:50.064 ThaliTest[1154:1232768] client: relay established
2015-12-15 05:47:50.065 ThaliTest[1154:1232768] client: new accepted socket: 0x1655c6a0
,2015-12-15T04:47:50.079Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:47:50.410Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T04:47:50.423Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T04:47:50.447Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T04:47:50.447Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-15T04:47:50.447Z SendDataConnector.js: CLIENT Stop now
2015-12-15T04:47:50.447Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:50.448 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:50.448 ThaliTest[1154:1232976] client session: disconnectFromPeer: Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:50.448 ThaliTest[1154:1232976] client session: disconnect
2015-12-15 05:47:50.448 ThaliTest[1154:1232976] client session: stateChange:2->0 Apple-Iphone6-1_PT7824.jNC0Kw==
,2015-12-15 05:47:50.509 ThaliTest[1154:1232976] jxcore: disconnect: success
2015-12-15T04:47:50.509Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7824.jNC0Kw==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:50.510Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:50.510Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15T04:47:50.511Z SendDataConnector.js: do connect now
,2015-12-15 05:47:50.511 ThaliTest[1154:1232976] jxcore: connect Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:50.511 ThaliTest[1154:1232976] client session: connect
,2015-12-15 05:47:50.511 ThaliTest[1154:1232976] client session: stateChange:0->1 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:53.275 ThaliTest[1154:1234373] client session: connected
,2015-12-15 05:47:53.275 ThaliTest[1154:1234373] client session: stateChange:1->2 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:53.298 ThaliTest[1154:1234392] client session: fireConnectCallback: Apple-Iphone5-1_PT356.aa89HA==
2015-12-15 05:47:53.298 ThaliTest[1154:1234392] jxcore: connect: success
,2015-12-15T04:47:53.300Z SendDataConnector.js: CLIENT connected to 58632, error: null
,2015-12-15T04:47:53.300Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 05:47:53.303 ThaliTest[1154:1232768] client: relay established
2015-12-15 05:47:53.303 ThaliTest[1154:1232768] client: new accepted socket: 0x16556570
,2015-12-15T04:47:53.317Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T04:47:53.662Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-15T04:47:53.676Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T04:47:53.676Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-15T04:47:53.676Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:53.676Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:47:53.677 ThaliTest[1154:1232976] jxcore: disconnect
,2015-12-15 05:47:53.677 ThaliTest[1154:1232976] client session: disconnectFromPeer: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:53.677 ThaliTest[1154:1232976] client session: disconnect
,2015-12-15 05:47:53.677 ThaliTest[1154:1232976] client session: stateChange:2->0 Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:47:53.680 ThaliTest[1154:1232976] jxcore: disconnect: success
,2015-12-15T04:47:53.680Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT356.aa89HA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2015-12-15T04:47:53.683Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T04:47:53.683Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 05:48:13.309 ThaliTest[1154:1232768] multipeer session: restart
,2015-12-15 05:48:13.339 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5s-1_PT4162.hYB3TQ==
2015-12-15 05:48:13.340 ThaliTest[1154:1232768] client: found peer: Apple-Iphone6-1_PT7824.jNC0Kw==
2015-12-15 05:48:13.340 ThaliTest[1154:1232768] client: found peer: Apple-Iphone5-1_PT356.aa89HA==
,2015-12-15 05:48:27.205 ThaliTest[1154:1232768] multipeer session: reset timer
2015-12-15 05:48:27.205 ThaliTest[1154:1232768] multipeer session: stop timer
2015-12-15 05:48:27.206 ThaliTest[1154:1232768] multipeer session: start timer: 0x14796240
,2015-12-15 05:48:27.206 ThaliTest[1154:1232768] server session: connect
2015-12-15 05:48:27.206 ThaliTest[1154:1232768] server session: stateChange:0->1 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:27.213 ThaliTest[1154:1232768] server: accepting invitation Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:29.925 ThaliTest[1154:1234503] server session: connected
,2015-12-15 05:48:29.925 ThaliTest[1154:1234503] server session: stateChange:1->2 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:29.941 ThaliTest[1154:1232768] server relay: connected (to port: 58618)
,2015-12-15T04:48:29.942Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:48:30.362Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-15T04:48:30.379Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-15T04:48:30.433Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-15T04:48:30.497Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-15T04:48:30.515Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-15T04:48:30.554Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-15T04:48:30.569Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:48:30.683 ThaliTest[1154:1234502] server session: not connected Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:31.206 ThaliTest[1154:1232768] multipeer session: reset timer
2015-12-15 05:48:31.207 ThaliTest[1154:1232768] multipeer session: stop timer
2015-12-15 05:48:31.207 ThaliTest[1154:1232768] multipeer session: start timer: 0x14796240
2015-12-15 05:48:31.208 ThaliTest[1154:1232768] server session: connect
2015-12-15 05:48:31.208 ThaliTest[1154:1232768] server session: stateChange:0->1 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:31.216 ThaliTest[1154:1232768] server: accepting invitation Apple-Iphone6-1_PT7824
,2015-12-15 05:48:33.836 ThaliTest[1154:1234502] server session: connected
2015-12-15 05:48:33.837 ThaliTest[1154:1234502] server session: stateChange:1->2 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:33.854 ThaliTest[1154:1232768] server relay: connected (to port: 58618)
,2015-12-15T04:48:33.859Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T04:48:34.547Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-15T04:48:34.561Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-15T04:48:34.577Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-15T04:48:34.593Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 05:48:34.622 ThaliTest[1154:1234521] server session: not connected Apple-Iphone6-1_PT7824
,teardown
,testSendData stopped
,2015-12-15 05:48:35.385 ThaliTest[1154:1232976] jxcore: stopBroadcasting
,2015-12-15 05:48:35.386 ThaliTest[1154:1232976] THEMultipeerSession stopping peer
,2015-12-15 05:48:35.386 ThaliTest[1154:1232976] multipeer session: stop timer
,2015-12-15 05:48:35.388 ThaliTest[1154:1232976] server session: disconnect
2015-12-15 05:48:35.388 ThaliTest[1154:1232976] server session: stateChange:2->0 Apple-Iphone6-1_PT7824
,2015-12-15 05:48:35.397 ThaliTest[1154:1232976] server session: disconnect
2015-12-15 05:48:35.398 ThaliTest[1154:1232976] server session: stateChange:2->0 Apple-Iphone5-1_PT356
,2015-12-15 05:48:35.413 ThaliTest[1154:1232976] server session: disconnect
2015-12-15 05:48:35.413 ThaliTest[1154:1232976] server session: stateChange:2->0 Apple-Iphone5s-1_PT4162
,2015-12-15 05:48:35.419 ThaliTest[1154:1232976] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-15T04:48:35.436Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:35.438Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:35.439Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-15T04:48:35.440Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
