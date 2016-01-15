#### Test 56204092c98eeae_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4CEC8B8A-F3A9-445C-AA47-5736B3B54FE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4CEC8B8A-F3A9-445C-AA47-5736B3B54FE0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4BFFC14F-8636-443D-BA6A-BEF69E6BFEDE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56552"
,(lldb)     command script import "/tmp/4CEC8B8A-F3A9-445C-AA47-5736B3B54FE0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 19:42:59.869 ThaliTest[2030:4260063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4FA3044F-47EE-4852-95AE-08015EBF1889/Library/Cookies/Cookies.binarycookies
,2016-01-15 19:43:00.125 ThaliTest[2030:4260063] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 19:43:00.126 ThaliTest[2030:4260063] Multi-tasking -> Device: YES, App: YES
,2016-01-15 19:43:00.130 ThaliTest[2030:4260063] Unlimited access to network resources
,2016-01-15 19:43:00.137 ThaliTest[2030:4260063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 19:43:04.351 ThaliTest[2030:4260063] Resetting plugins due to page load.
,2016-01-15 19:43:05.882 ThaliTest[2030:4260063] Finished load of: file:///var/mobile/Containers/Bundle/Application/4BFFC14F-8636-443D-BA6A-BEF69E6BFEDE/ThaliTest.app/www/index.html
,2016-01-15 19:43:06.055 ThaliTest[2030:4260063] JXcore Cordova plugin initializing
2016-01-15 19:43:06.056 ThaliTest[2030:4260226] JXcore instance initializing
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
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-15 19:48:22.180 ThaliTest[2030:4260226] jxcore: startBroadcasting
,2016-01-15 19:48:22.190 ThaliTest[2030:4260226] server: starting Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:22.190 ThaliTest[2030:4260226] multipeer session: start timer: 0x18b8f4d0
2016-01-15 19:48:22.191 ThaliTest[2030:4260226] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3224
2016-01-15 19:48:22.191 ThaliTest[2030:4260226] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-15 19:48:23.275 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT5004.158h0w==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-15 19:48:24.998 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
,teardown
testFindPeers stopped
,2016-01-15 19:48:29.535 ThaliTest[2030:4260226] jxcore: stopBroadcasting
2016-01-15 19:48:29.535 ThaliTest[2030:4260226] THEMultipeerSession stopping peer
2016-01-15 19:48:29.536 ThaliTest[2030:4260226] multipeer session: stop timer
2016-01-15 19:48:29.536 ThaliTest[2030:4260226] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
daya100000
check server
serverPort is 52047
2016-01-15 19:48:29.555 ThaliTest[2030:4260226] jxcore: startBroadcasting
,2016-01-15 19:48:29.558 ThaliTest[2030:4260226] server: starting Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:48:29.558 ThaliTest[2030:4260226] multipeer session: start timer: 0x18c6c810
2016-01-15 19:48:29.558 ThaliTest[2030:4260226] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT3224
2016-01-15 19:48:29.558 ThaliTest[2030:4260226] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-15T18:48:29.559Z SendDataTCPServer.js: TCP/IP server is bound to port: 52047
,2016-01-15 19:48:29.578 ThaliTest[2030:4260063] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:29.578 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:29.578 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_P,T3224.cXLr/Q==
2016-01-15T18:48:29.579Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:29.579Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:29.580Z SendDataConnector.js: do connect now
,2016-01-15 19:48:29.580 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:29.587 ThaliTest[2030:4260226] client session: connect
,2016-01-15 19:48:29.588 ThaliTest[2030:4260226] client session: stateChange:0->1 Apple-Iphone6-1_PT3224.cXLr/Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-15 19:48:29.940 ThaliTest[2030:4260063] client: found peer: Apple-IpadAir2-1_PT6810.+fMbbA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2016-01-15 19:48:30.792 ThaliTest[2030:4260063] client: lost peer: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:30.792 ThaliTest[2030:4260063] client session: onPeerLost: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:30.792 ThaliTest[2030:4260063] client session: onLinkFailure: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:30.792 ThaliTest[2030:4260063] client session: disconnect
2016-01-15 19:48:30.792 ThaliTest[2030:4260063] client session: stateChange:1->0 Apple-Iphone6-1_PT3224.cXLr/Q==
2,016-01-15 19:48:30.793 ThaliTest[2030:4260063] client session: fireConnectCallback: Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:30.793 ThaliTest[2030:4260063] jxcore: connect: fail: Peer disconnected
2016-01-15T18:48:30.794Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-15T18:48:30.794Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-15T18:48:30.794Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":false}]
,2016-01-15 19:48:30.944 ThaliTest[2030:4260063] client: lost peer: Apple-IpadAir2-1_PT6810.+fMbbA==
2016-01-15 19:48:30.944 ThaliTest[2030:4260063] client session: onPeerLost: Apple-IpadAir2-1_PT6810.+fMbbA==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-IpadAir2-1_PT6810.+fMbbA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-15 19:48:31.363 ThaliTest[2030:4260063] client: lost peer: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:31.363 ThaliTest[2030:4260063] client session: onPeerLost: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:31.364 ThaliTest[2030:426006,3] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:48:31.364 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)",,"peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6810.kDDcMw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.rhpQQw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:31.391 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.TN0Czw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:33.057 ThaliTest[2030:4260063] client: lost peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:33.057 ThaliTest[2030:4260063] client session: onPeerLost: Apple-Iphone5-1_PT5004.158h0w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-15T18:48:35.801Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15T18:48:35.801Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:40.807 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:48:40.808 ThaliTest[2030:4260226] jxcore: disconnect: fail
2016-01-15T18:48:40.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.cXLr/,Q==
2016-01-15T18:48:40.808Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT3224.cXLr/Q== with availability status: true
2016-01-15T18:48:40.808Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:40.808Z SendDataConnector.js: do connect now
,2016-01-15 19:48:40.808 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:40.809 ThaliTest[2030:4260226] client: connect: unreachable Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:40.809 ThaliTest[2030:4260226] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:40.809Z SendDataConnector.js: CLIENT con,nected to 0, error: Peer unreachable
2016-01-15T18:48:40.809Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:48:40.809Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:45.813Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:45.814Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:50.822 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:48:50.822 ThaliTest[2030:4260226] jxcore: disconnect: fail
2016-01-15T18:48:50.822Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:50.822Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT3224.cXLr/Q== with availability status: true
2016-01-15T18:48:50.822Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:50.822Z SendDataConnector.js: do connect now
2016-01-15 19:48:50.823 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:48:50.823 ThaliTest[2030:4260226] client: connect: unreachable Apple-Iphone6-1_PT32,24.cXLr/Q==
2016-01-15 19:48:50.823 ThaliTest[2030:4260226] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:50.823Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:50.823Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer unreachable
2016-01-15T18:48:50.824Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:55.829Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:48:55.829Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:48:59.571 ThaliTest[2030:4260063] multipeer session: restart
,2016-01-15 19:48:59.591 ThaliTest[2030:4260063] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:48:59.591 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:48:59.591 ThaliTest[2030:4260063] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:00.839 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:00.839 ThaliTest[2030:4260226] jxcore: disconnect: fail
2016-01-15T18:49:00.840Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.cXLr/,Q==
2016-01-15T18:49:00.840Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT3224.cXLr/Q== with availability status: true
2016-01-15T18:49:00.840Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:49:00.840Z SendDataConnector.js: do connect now
,2016-01-15 19:49:00.841 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:49:00.841 ThaliTest[2030:4260226] client: connect: unreachable Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:49:00.841 ThaliTest[2030:4260226] jxcore: connect: fail: Peer unreachable
2016-01-15T18:49:00.841Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:49:00.841Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:49:00.841Z SendDat,aConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:49:05.843Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15T18:49:05.844Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15 19:49:10.844 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:10.845 ThaliTest[2030:4260226] jxcore: disconnect: fail
2016-01-15T18:49:10.845Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.cXLr/,Q==
2016-01-15T18:49:10.845Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT3224.cXLr/Q== with availability status: true
2016-01-15T18:49:10.845Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.cXLr/Q==
,2016-01-15T18:49:10.845Z SendDataConnector.js: do connect now
,2016-01-15 19:49:10.846 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:49:10.846 ThaliTest[2030:4260226] client: connect: unreachable Apple-Iphone6-1_PT3224.cXLr/Q==
2016-01-15 19:49:10.846 ThaliTest[2030:4260226] j,xcore: connect: fail: Peer unreachable
2016-01-15T18:49:10.846Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:49:10.846Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-15T18:49:10.847Z SendDataConnector.js: CLIENT Stop now
,2016-01-15 19:49:10.848 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:10.848 ThaliTest[2030:4260226] jxcore: disconnect: fail
2016-01-15T18:49:10.848Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.cXLr/Q==
---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:10.849Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:10.849Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:10.849Z SendDataConnector.js: do connect now
,2016-01-15 19:49:10.850 ThaliTest[2030:4260226] jxcore: connect Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:10.850 ThaliTest[2030:4260226] client session: connect
2016-01-15 19:49:10.850 ThaliTest[2030:4260226] client session: stateChange:0->1 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:11.046 ThaliTest[2030:4260063] multipeer session: reset timer
2016-01-15 19:49:11.046 ThaliTest[2030:4260063] multipeer session: stop timer
2016-01-15 19:49:11.046 ThaliTest[2030:4260063] multipeer session: start timer: 0x18c6c810
2016-01-15 19:49:11.046 ThaliTest[2030:4260063] server session: connect
2016-01-15 19:49:11.046 ThaliTest[2030:4260063] server session: stateChange:0->1 Apple-IpadAir2-1_PT6810
2016-01-15 19:49:11.048 ThaliTest[2030:4260063] server: accepting invitation Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:11.427 ThaliTest[2030:4260063] multipeer session: reset timer
2016-01-15 19:49:11.427 ThaliTest[2030:4260063] multipeer session: stop timer
,2016-01-15 19:49:11.427 ThaliTest[2030:4260063] multipeer session: start timer: 0x18c6c810
2016-01-15 19:49:11.427 ThaliTest[2030:4260063] server session: connect
2016-01-15 19:49:11.427 ThaliTest[2030:4260063] server session: stateChange:0->1 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:11.430 ThaliTest[2030:4260063] server: accepting invitation Apple-Iphone5-1_PT5004
,2016-01-15 19:49:13.887 ThaliTest[2030:4260892] server session: connected
2016-01-15 19:49:13.887 ThaliTest[2030:4260892] server session: stateChange:1->2 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:13.920 ThaliTest[2030:4260063] server relay: connected (to port: 52047)
,2016-01-15T18:49:13.924Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:14.417Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-15T18:49:14.440Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-15T18:49:14.454Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:14.902 ThaliTest[2030:4260908] server session: not connected Apple-Iphone5-1_PT5004
,2016-01-15 19:49:14.909 ThaliTest[2030:4260891] server session: connected
2016-01-15 19:49:14.909 ThaliTest[2030:4260891] server session: stateChange:1->2 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:14.933 ThaliTest[2030:4260063] server relay: connected (to port: 52047)
,2016-01-15T18:49:14.939Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15 19:49:14.962 ThaliTest[2030:4260892] client session: connected
2016-01-15 19:49:14.962 ThaliTest[2030:4260892] client session: stateChange:1->2 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:14.967 ThaliTest[2030:4260921] client session: fireConnectCallback: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:14.967 ThaliTest[2030:4260921] jxcore: connect: success
2016-01-15T18:49:14.968Z SendDataConnector.js: CLIENT connected to 52058, error: null
,2016-01-15T18:49:14.968Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:14.970 ThaliTest[2030:4260063] client: relay established
,2016-01-15 19:49:14.971 ThaliTest[2030:4260063] client: new accepted socket: 0x18c8ad90
,2016-01-15T18:49:14.981Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:15.195Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:15.503 ThaliTest[2030:4260908] server session: not connected Apple-IpadAir2-1_PT6810
2016-01-15T18:49:15.505Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:15.505Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-15T18:49:15.505Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:15.505Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-15 19:49:15.506 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:15.506 ThaliT,est[2030:4260226] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:15.506 ThaliTest[2030:4260226] client session: disconnect
2016-01-15 19:49:15.506 ThaliTest[2030:4260226] client session: stateChange:2->0 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:15.512 ThaliTest[2030:4260226] jxcore: disconnect: success
2016-01-15T18:49:15.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.kDDcMw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15T18:49:15.513Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15T18:49:15.513Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15T18:4,9:15.513Z SendDataConnector.js: do connect now
2016-01-15 19:49:15.513 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:15.513 ThaliTest[2030:4260226] client session: connect
2016-01-15 19:49:15.513 ThaliTest[2030:4260226] client session: stateChange:0->1 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:17.136 ThaliTest[2030:4260063] multipeer session: reset timer
2016-01-15 19:49:17.136 ThaliTest[2030:4260063] multipeer session: stop timer
2016-01-15 19:49:17.137 ThaliTest[2030:4260063] multipeer session: start timer: 0x18c6c810
2016-01-15 19:49:17.137 ThaliTest[2030:4260063] server session: connect
2016-01-15 19:49:17.137 ThaliTest[2030:4260063] server session: stateChange:0->1 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:17.140 ThaliTest[2030:4260063] server: accepting invitation Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:18.224 ThaliTest[2030:4260891] client session: connected
2016-01-15 19:49:18.224 ThaliTest[2030:4260891] client session: stateChange:1->2 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:18.241 ThaliTest[2030:4260921] client session: fireConnectCallback: Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:18.242 ThaliTest[2030:4260921] jxcore: connect: success
2016-01-15T18:49:18.242Z SendDataConnector.js: CLIENT connected ,to 52061, error: null
2016-01-15T18:49:18.242Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:18.244 ThaliTest[2030:4260063] client: relay established
2016-01-15 19:49:18.244 ThaliTest[2030:4260063] client: new accepted socket: 0x18ba5600
,2016-01-15T18:49:18.256Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:18.617Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-15T18:49:18.629Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:18.629Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:18.630Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:18.630Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:18.630 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:18.631 ThaliTest[2030:4260226] client session: disconnectFromPeer: Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:18.631 ThaliTest[2030:4260226] client session: disconnect
2016-01-15 19:49:18.631 ThaliTest[2030:4260226] client session: stateChange:2->0 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:18.635 ThaliTest[2030:4260226] jxcore: disconnect: success
2016-01-15T18:49:18.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.rhpQQw==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18:49:18.635Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15T18:49:18.636Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15T18:49:18.637Z SendDataConnector.js: do connect now
2016-01-15 19:49:18.637 ThaliTest[2030:4260226] jxcore: connect Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:18.637 ThaliTest[2030:4260226] client session: connect
2016-01-15 19:49:18.637 ThaliTest[2030:4260226] client session: stateChange:0->1 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:19.762 ThaliTest[2030:4260921] server session: connected
2016-01-15 19:49:19.762 ThaliTest[2030:4260921] server session: stateChange:1->2 Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:19.781 ThaliTest[2030:4260063] server relay: connected (to port: 52047)
2016-01-15T18:49:19.784Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:20.211Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-15T18:49:20.224Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:20.275 ThaliTest[2030:4260893] server session: not connected Apple-Iphone5s-1_PT6477
,2016-01-15 19:49:21.330 ThaliTest[2030:4260892] client session: connected
2016-01-15 19:49:21.331 ThaliTest[2030:4260892] client session: stateChange:1->2 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:21.333 ThaliTest[2030:4260891] client session: fireConnectCallback: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:21.333 ThaliTest[2030:4260891] jxcore: connect: success
2016-01-15T18:49:21.333Z SendDataConnector.js: CLIENT connected, to 52065, error: null
2016-01-15T18:49:21.334Z SendDataConnector.js: CLIENT starting client 
2016-01-15 19:49:21.335 ThaliTest[2030:4260063] client: relay established
,2016-01-15 19:49:21.336 ThaliTest[2030:4260063] client: new accepted socket: 0x18c90a70
,2016-01-15T18:49:21.346Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:21.791Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-15T18:49:21.860Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:21.860Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-15T18:49:21.860Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:2,1.860Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-15 19:49:21.860 ThaliTest[2030:4260226] jxcore: disconnect
2016-01-15 19:49:21.860 ThaliTest[2030:4260226] client session: disconnectFromPeer: Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:49:21.860 ThaliTest[2030:4260226] client session: disconnect
2016-01-15 19:49:21.861 ThaliTest[2030:4260226] client session: stateChange:2->0 Apple-Iphone5s-1_PT6477.TN0Czw==
,2016-01-15 19:49:21.870 ThaliTest[2030:4260226] jxcore: disconnect: success
2016-01-15T18:49:21.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT6477.TN0Czw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-15T18:49:21.883Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:21.883Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
testSendData stopped
2016-01-15 19:49:24.313 ThaliTest[2030:4260226] jxcore: stopBroadcasting
2016-01-15 19:49:24.313 ThaliTest[2030:4260226] THEMultipeerSession stopping peer
2016-01-15 19:49:24.313 ThaliTest[2030:4260226] multipeer session: stop timer
2016-01-15 19:49:24.314 ThaliTest[2030:4260226] server session: disconnect
2016-01-15 19:49:24.314 ThaliTest[2030:4260226] server session: stateChange:2->0 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:24.317 ThaliTest[2030:4260226] server session: disconnect
2016-01-15 19:49:24.317 ThaliTest[2030:4260226] server session: stateChange:2->0 Apple-Iphone5s-1_PT6477
2016-01-15 19:49:24.319 ThaliTest[2030:4260226] server session: disconnect
2016-01-15 19:49:24.319 ThaliTest[2030:4260226] server session: stateChange:2->0 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:24.328 ThaliTest[2030:4260226] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
