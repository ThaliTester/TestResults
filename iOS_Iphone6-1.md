#### Test 506502785223c58_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/BF7C498C-F2A7-46B0-B756-84967BC0F88D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BF7C498C-F2A7-46B0-B756-84967BC0F88D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/090156B8-553D-4509-AE66-5E1BD670BC51/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59088"
,(lldb)     command script import "/tmp/BF7C498C-F2A7-46B0-B756-84967BC0F88D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 01:37:12.865 ThaliTest[336:157677] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3EC00903-B803-4CAE-85B4-1E3D6E6A269B/Library/Cookies/Cookies.binarycookies
,2015-12-17 01:37:13.296 ThaliTest[336:157677] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 01:37:13.297 ThaliTest[336:157677] Multi-tasking -> Device: YES, App: YES
,2015-12-17 01:37:13.307 ThaliTest[336:157677] Unlimited access to network resources
,2015-12-17 01:37:13.318 ThaliTest[336:157677] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 01:37:22.328 ThaliTest[336:157677] Resetting plugins due to page load.
,2015-12-17 01:37:25.772 ThaliTest[336:157677] Finished load of: file:///var/mobile/Containers/Bundle/Application/090156B8-553D-4509-AE66-5E1BD670BC51/ThaliTest.app/www/index.html
,2015-12-17 01:37:25.952 ThaliTest[336:157677] JXcore Cordova plugin initializing
,2015-12-17 01:37:25.953 ThaliTest[336:157881] JXcore instance initializing
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
,2015-12-17 01:37:27.050 ThaliTest[336:157677] THREAD WARNING: ['JXcore'] took '77.387207' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-17 01:42:48.223 ThaliTest[336:157881] jxcore: startBroadcasting
,2015-12-17 01:42:48.240 ThaliTest[336:157881] server: starting Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:42:48.241 ThaliTest[336:157881] multipeer session: start timer: 0x17bc1e10
,2015-12-17 01:42:48.244 ThaliTest[336:157881] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4129
2015-12-17 01:42:48.245 ThaliTest[336:157881] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17 01:42:48.277 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6761.1E6mhw==
2015-12-17 01:42:48.280 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5,-1_PT6761.1E6mhw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT6761.1E6mhw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-17 01:42:49.279 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.GOF+uA==
,teardown
,testFindPeers stopped
,2015-12-17 01:42:49.720 ThaliTest[336:157881] jxcore: stopBroadcasting
2015-12-17 01:42:49.721 ThaliTest[336:157881] THEMultipeerSession stopping peer
2015-12-17 01:42:49.721 ThaliTest[336:157881] multipeer session: stop timer
2015-12-17 01:42:49.722 Th,aliTest[336:157881] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51043
,2015-12-17 01:42:49.816 ThaliTest[336:157881] jxcore: startBroadcasting
,2015-12-17 01:42:49.819 ThaliTest[336:157881] server: starting Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:42:49.827 ThaliTest[336:157881] multipeer session: start timer: 0x17bc72c0
,2015-12-17 01:42:49.831 ThaliTest[336:157881] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4129
,2015-12-17 01:42:49.832 ThaliTest[336:157881] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-17 01:42:49.842 ThaliTest[336:157677] client: found peer: Apple-Iphone6-1_PT4129.8JQKBA==
null
2015-12-17T00:42:49.843Z SendDataTCPServer.js: TCP/IP server is bound to port: 51043
2015-12-17 01:42:49.844 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.GOF+uA==
2015-12-17 01:42:49.845 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT5378.J91vGA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.8JQKBA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:42:49.850Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:42:49.851Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:42:49.851Z SendDataConnector.js: do connect now
,2015-12-17 01:42:49.851 ThaliTest[336:157881] jxcore: connect Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:42:49.852 ThaliTest[336:157881] client session: connect
,2015-12-17 01:42:49.853 ThaliTest[336:157881] client session: stateChange:0->1 Apple-Iphone6-1_PT4129.8JQKBA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.GOF+uA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 01:42:50.852 ThaliTest[336:157677] client: lost peer: Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:42:50.852 ThaliTest[336:157677] client session: onPeerLost: Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:42:50.853 ThaliTest[336:157677] clien,t session: onLinkFailure: Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:42:50.853 ThaliTest[336:157677] client session: disconnect
2015-12-17 01:42:50.853 ThaliTest[336:157677] client session: stateChange:1->0 Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 ,01:42:50.854 ThaliTest[336:157677] client session: fireConnectCallback: Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:42:50.854 ThaliTest[336:157677] jxcore: connect: fail: Peer disconnected
2015-12-17 01:42:50.855 ThaliTest[336:157677] client: found pee,r: Apple-Iphone5-1_PT6883.tl0S1A==
2015-12-17T00:42:50.856Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-17T00:42:50.857Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-17T00:42:50.857Z SendDataC,onnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.8JQKBA==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.tl0S1A==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:51.158 ThaliTest[336:157677] client: lost peer: Apple-Iphone5-1_PT6883.tl0S1A==
2015-12-17 01:42:51.159 ThaliTest[336:157677] client session: onPeerLost: Apple-Iphone5-1_PT6883.tl0S1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.tl0S1A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 01:42:51.749 ThaliTest[336:157677] client: lost peer: Apple-IpadAir2-1_PT2260.GOF+uA==
2015-12-17 01:42:51.749 ThaliTest[336:157677] client session: onPeerLost: Apple-IpadAir2-1_PT2260.GOF+uA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT2260.GOF+uA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 01:42:51.838 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-17 01:42:52.347 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
2015-12-17 01:42:52.350 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17T00:42:55.868Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:42:55.870Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:42:56.479 ThaliTest[336:157677] multipeer session: reset timer
2015-12-17 01:42:56.480 ThaliTest[336:157677] multipeer session: stop timer
2015-12-17 01:42:56.480 ThaliTest[336:157677] multipeer session: start timer: 0x17bc72c0
2015-12-17 01:42:56.480 ThaliTest[336:157677] server session: connect
,2015-12-17 01:42:56.481 ThaliTest[336:157677] server session: stateChange:0->1 Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:56.491 ThaliTest[336:157677] server: accepting invitation Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:59.125 ThaliTest[336:158423] server session: connected
2015-12-17 01:42:59.126 ThaliTest[336:158423] server session: stateChange:1->2 Apple-Iphone5s-1_PT4765
,2015-12-17 01:42:59.135 ThaliTest[336:157677] server relay: connected (to port: 51043)
,2015-12-17T00:42:59.144Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:42:59.591Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-17T00:42:59.608Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-17T00:42:59.625Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-17T00:42:59.642Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-17T00:42:59.656Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:42:59.693 ThaliTest[336:158406] server session: not connected Apple-Iphone5s-1_PT4765
,2015-12-17 01:43:00.037 ThaliTest[336:157677] client: lost peer: Apple-IpadAir2-1_PT5378.J91vGA==
2015-12-17 01:43:00.037 ThaliTest[336:157677] client session: onPeerLost: Apple-IpadAir2-1_PT5378.J91vGA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT5378.J91vGA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 01:43:00.879 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:00.880 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:00.880Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.8JQKBA==,
2015-12-17T00:43:00.881Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4129.8JQKBA== with availability status: true
2015-12-17T00:43:00.881Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:00.881Z SendDataConnector.js: do connect now
,2015-12-17 01:43:00.882 ThaliTest[336:157881] jxcore: connect Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:00.883 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:43:00.884 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
2015-12-17T00:43:00.884Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-17T00:43:00.885Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:00.885Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:05.891Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:05.891Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:10.903 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:10.904 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:10.904Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.8JQKBA==,
2015-12-17T00:43:10.905Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4129.8JQKBA== with availability status: true
2015-12-17T00:43:10.905Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:10.905Z SendDataConnector.js: do connect now
2015-12-17 01:43:10.906 ThaliTest[336:157881] jxcore: connect Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:10.907 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:10.907 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
2015-12-17T00:43:10.909Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:10.909Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:10.910Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:15.916Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:15.916Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:20.927 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:20.928 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:20.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.8JQKBA==,
2015-12-17T00:43:20.929Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4129.8JQKBA== with availability status: true
2015-12-17T00:43:20.929Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:20.929Z SendDataConnector.js: do connect now
2015-12-17 01:43:20.930 ThaliTest[336:157881] jxcore: connect Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:20.932 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:43:20.932 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
2015-12-17T00:43:20.933Z SendDataConnector.js: CLIENT connect,ed to 0, error: Peer unreachable
2015-12-17T00:43:20.933Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:20.933Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:25.934Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17T00:43:25.934Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:26.481 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:43:26.527 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:26.530 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:43:30.939 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:30.939 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:30.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.8JQKBA==,
2015-12-17T00:43:30.940Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4129.8JQKBA== with availability status: true
2015-12-17T00:43:30.940Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.8JQKBA==
2015-,12-17T00:43:30.941Z SendDataConnector.js: do connect now
,2015-12-17 01:43:30.941 ThaliTest[336:157881] jxcore: connect Apple-Iphone6-1_PT4129.8JQKBA==
2015-12-17 01:43:30.942 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone6-1_PT4129.8JQKBA==
,2015-12-17 01:43:30.942 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:30.944Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:30.944Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-17T00:43:30.946Z SendDataConnector.js: CLIENT Stop now
,2015-12-17 01:43:30.948 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:30.948 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:30.949Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.8JQKBA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:30.952Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:30.953Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:30.954Z SendDataConnector.js: do connect now
,2015-12-17 01:43:30.955 ThaliTest[336:157881] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.955 ThaliTest[336:157881] client session: connect
2015-12-17 01:43:30.956 ThaliTest[336:157881] client session: stateChange:0->1 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:30.968 ThaliTest[336:157677] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.968 ThaliTest[336:157677] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.969 ThaliTest[336:157677] cli,ent session: onLinkFailure: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.969 ThaliTest[336:157677] client session: disconnect
2015-12-17 01:43:30.969 ThaliTest[336:157677] client session: stateChange:1->0 Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12,-17 01:43:30.970 ThaliTest[336:157677] client session: fireConnectCallback: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:30.970 ThaliTest[336:157677] jxcore: connect: fail: Peer disconnected
2015-12-17T00:43:30.971Z SendDataConnector.js: CLIENT conn,ected to 0, error: Peer disconnected
2015-12-17T00:43:30.972Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-17T00:43:30.972Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
,2015-12-17 01:43:32.152 ThaliTest[336:157677] multipeer session: reset timer
2015-12-17 01:43:32.153 ThaliTest[336:157677] multipeer session: stop timer
2015-12-17 01:43:32.153 ThaliTest[336:157677] multipeer session: start timer: 0x17bc72c0
,2015-12-17 01:43:32.153 ThaliTest[336:157677] server session: connect
,2015-12-17 01:43:32.155 ThaliTest[336:157677] server session: stateChange:0->1 Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:32.164 ThaliTest[336:157677] server: accepting invitation Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:32.353 ThaliTest[336:157677] multipeer session: reset timer
,2015-12-17 01:43:32.353 ThaliTest[336:157677] multipeer session: stop timer
2015-12-17 01:43:32.354 ThaliTest[336:157677] multipeer session: start timer: 0x17bc72c0
,2015-12-17 01:43:32.354 ThaliTest[336:157677] server session: connect
,2015-12-17 01:43:32.355 ThaliTest[336:157677] server session: stateChange:0->1 Apple-Iphone5-1_PT6883
,2015-12-17 01:43:32.360 ThaliTest[336:157677] server: accepting invitation Apple-Iphone5-1_PT6883
,2015-12-17 01:43:34.916 ThaliTest[336:158529] server session: connected
2015-12-17 01:43:34.917 ThaliTest[336:158529] server session: stateChange:1->2 Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:34.942 ThaliTest[336:157677] server relay: connected (to port: 51043)
,2015-12-17T00:43:34.950Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17 01:43:34.976 ThaliTest[336:158505] server session: connected
2015-12-17 01:43:34.977 ThaliTest[336:158505] server session: stateChange:1->2 Apple-Iphone5-1_PT6883
,2015-12-17 01:43:35.042 ThaliTest[336:157677] server relay: connected (to port: 51043)
,2015-12-17T00:43:35.051Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:43:35.214Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-17T00:43:35.275Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17T00:43:35.894Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-17T00:43:35.908Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-17T00:43:35.926Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-17T00:43:35.940Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-17T00:43:35.956Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-17T00:43:35.971Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17T00:43:35.985Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:35.986Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:36.338 ThaliTest[336:158504] server session: not connected Apple-Iphone5-1_PT6883
,2015-12-17 01:43:40.990 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:40.991 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:40.992Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==,
2015-12-17T00:43:40.992Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1_PT4765.ZBlg+A== with availability status: true
2015-12-17T00:43:40.993Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
20,15-12-17T00:43:40.993Z SendDataConnector.js: do connect now
,2015-12-17 01:43:40.993 ThaliTest[336:157881] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:40.994 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:40.995 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
,2015-12-17T00:43:40.996Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:43:40.997Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:40.997Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17T00:43:46.005Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:46.005Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:46.337 ThaliTest[336:158504] server session: not connected Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:46.833 ThaliTest[336:157677] client: lost peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:46.833 ThaliTest[336:157677] client session: onPeerLost: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-17 01:43:51.011 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:43:51.012 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:43:51.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==,
2015-12-17T00:43:51.013Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1_PT4765.ZBlg+A== with availability status: true
2015-12-17T00:43:51.013Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:51.013Z SendDataConnector.js: do connect now
2015-12-17 01:43:51.014 ThaliTest[336:157881] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:43:51.015 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:43:51.016 ThaliTest[336:157881] jxcore: connect: fail: Peer unreachable
2015-12-17T00:43:51.016Z SendDataConnector.js: CLIENT connec,ted to 0, error: Peer unreachable
2015-12-17T00:43:51.017Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:43:51.017Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-17 01:43:55.573 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,2015-12-17T00:43:56.017Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:43:56.018Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:01.026 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:44:01.027 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:44:01.028Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17T00:44:01.028Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1_PT4765.ZBlg+A== with availability status: true
,2015-12-17T00:44:01.029Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:44:01.030Z SendDataConnector.js: do connect now
,2015-12-17 01:44:01.032 ThaliTest[336:157881] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:01.032 ThaliTest[336:157881] client: connect: unreachable Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:01.033 ThaliTest[336:157881] jxcor,e: connect: fail: Peer unreachable
2015-12-17T00:44:01.033Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-17T00:44:01.033Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-17T00:44:01.034Z SendDataCon,nector.js: tryAgain afer: 5000 ms.
,2015-12-17 01:44:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:44:02.397 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:44:02.397 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
,2015-12-17T00:44:06.040Z SendDataConnector.js: re-try now : Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:44:06.040Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:11.042 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:44:11.043 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:44:11.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==,
2015-12-17T00:44:11.043Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1_PT4765.ZBlg+A== with availability status: true
2015-12-17T00:44:11.044Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:44:11.044Z SendDataConnector.js: do connect now
2015-12-17 01:44:11.045 ThaliTest[336:157881] jxcore: connect Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:11.046 ThaliTest[336:157881] client session: connect
2015-12-17 01:44:11.046 ThaliTest[336:157881] client session: stateChange:0->1 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:14.630 ThaliTest[336:158685] client session: connected
2015-12-17 01:44:14.630 ThaliTest[336:158685] client session: stateChange:1->2 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:14.636 ThaliTest[336:158648] client session: fireConnectCallback: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:14.636 ThaliTest[336:158648] jxcore: connect: success
,2015-12-17T00:44:14.638Z SendDataConnector.js: CLIENT connected to 51054, error: null
2015-12-17T00:44:14.638Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:44:14.641 ThaliTest[336:157677] client: relay established
2015-12-17 01:44:14.642 ThaliTest[336:157677] client: new accepted socket: 0x17be0d30
,2015-12-17T00:44:14.658Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:44:15.127Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T00:44:15.138Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T00:44:15.151Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T00:44:15.172Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-17T00:44:15.186Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:44:15.186Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-17T00:44:15.186Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:44:15.186Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:15.187 ThaliTest[336:157881] jxcore: disconnect
,2015-12-17 01:44:15.188 ThaliTest[336:157881] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:15.188 ThaliTest[336:157881] client session: disconnect
,2015-12-17 01:44:15.189 ThaliTest[336:157881] client session: stateChange:2->0 Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:44:15.254 ThaliTest[336:157881] jxcore: disconnect: success
,2015-12-17T00:44:15.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4765.ZBlg+A==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:15.256Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:15.257Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:15.257Z SendDataConnector.js: do connect now
,2015-12-17 01:44:15.257 ThaliTest[336:157881] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:15.258 ThaliTest[336:157881] client session: connect
,2015-12-17 01:44:15.259 ThaliTest[336:157881] client session: stateChange:0->1 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:15.264 ThaliTest[336:157677] client: lost peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:15.264 ThaliTest[336:157677] client session: onPeerLost: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:15.264 ThaliTest[336:157677] cli,ent session: onLinkFailure: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:15.264 ThaliTest[336:157677] client session: disconnect
2015-12-17 01:44:15.264 ThaliTest[336:157677] client session: stateChange:1->0 Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12,-17 01:44:15.264 ThaliTest[336:157677] client session: fireConnectCallback: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:15.265 ThaliTest[336:157677] jxcore: connect: fail: Peer disconnected
,2015-12-17T00:44:15.268Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-17T00:44:15.268Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-17T00:44:15.269Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":false}]
,2015-12-17T00:44:20.271Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:20.271Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:23.768 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
,2015-12-17 01:44:25.278 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:44:25.278 ThaliTest[336:157881] jxcore: disconnect: fail
2015-12-17T00:44:25.279Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==,
2015-12-17T00:44:25.279Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT2260.gQiHGg== with availability status: true
2015-12-17T00:44:25.280Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:44:25.280Z SendDataConnector.js: do connect now
,2015-12-17 01:44:25.281 ThaliTest[336:157881] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:25.282 ThaliTest[336:157881] client session: connect
2015-12-17 01:44:25.283 ThaliTest[336:157881] client session: stateChange:0->1 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:28.456 ThaliTest[336:158745] client session: connected
,2015-12-17 01:44:28.456 ThaliTest[336:158745] client session: stateChange:1->2 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:28.495 ThaliTest[336:158753] client session: fireConnectCallback: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:28.495 ThaliTest[336:158753] jxcore: connect: success
2015-12-17T00:44:28.496Z SendDataConnector.js: CLIENT connected to 51057, error: null
2015-12-17T00:44:28.497Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:44:28.501 ThaliTest[336:157677] client: relay established
2015-12-17 01:44:28.502 ThaliTest[336:157677] client: new accepted socket: 0x17be3940
,2015-12-17T00:44:28.517Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:44:28.779Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T00:44:28.792Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T00:44:28.805Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T00:44:28.828Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-17T00:44:28.828Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-17T00:44:28.829Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:44:28.829Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:28.830 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:44:28.830 ThaliTest[336:157881] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:28.830 ThaliTest[336:157881] client session: disconnect
,2015-12-17 01:44:28.831 ThaliTest[336:157881] client session: stateChange:2->0 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:28.897 ThaliTest[336:157881] jxcore: disconnect: success
,2015-12-17T00:44:28.897Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:44:28.898Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:44:28.898Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:44:28.899Z SendDataConnector.js: do connect now
,2015-12-17 01:44:28.899 ThaliTest[336:157881] jxcore: connect Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:28.900 ThaliTest[336:157881] client session: connect
,2015-12-17 01:44:28.900 ThaliTest[336:157881] client session: stateChange:0->1 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:31.943 ThaliTest[336:158745] client session: connected
,2015-12-17 01:44:31.943 ThaliTest[336:158745] client session: stateChange:1->2 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:31.979 ThaliTest[336:158756] client session: fireConnectCallback: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:44:31.979 ThaliTest[336:158756] jxcore: connect: success
,2015-12-17T00:44:31.981Z SendDataConnector.js: CLIENT connected to 51060, error: null
2015-12-17T00:44:31.982Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:44:31.986 ThaliTest[336:157677] client: relay established
2015-12-17 01:44:31.986 ThaliTest[336:157677] client: new accepted socket: 0x17c6b1a0
,2015-12-17T00:44:31.998Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17 01:44:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:44:32.376 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:32.376 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:32.377 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17T00:44:32.409Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17T00:44:32.424Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:44:32.436Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T00:44:32.449Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:44:32.449Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-17T00:44:32.449Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:44:3,2.449Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-17 01:44:32.450 ThaliTest[336:157881] jxcore: disconnect
2015-12-17 01:44:32.451 ThaliTest[336:157881] client session: disconnectFromPeer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:44:32.451 ThaliTest[336:157881] client session: disconnect
2015-12-17 01:44:32.451 ThaliTest[336:157881] client session: stateChange:2->0 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:44:32.459 ThaliTest[336:157881] jxcore: disconnect: success
2015-12-17T00:44:32.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6883.KeEEhw==
---- round done--------
startWithNextDevice
weAreDoneNow, re,sultArray.length: 4
sendReportNow
done, now sending data to server
2015-12-17T00:44:32.461Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:44:32.461Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:44:45.914 ThaliTest[336:157677] client: lost peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:44:45.915 ThaliTest[336:157677] client session: onPeerLost: Apple-Iphone5s-1_PT4765.ZBlg+A==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-17 01:44:47.010 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4765.ZBlg+A==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-17 01:45:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:45:02.399 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:45:02.402 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:45:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:46:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:46:02.393 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:46:02.394 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:46:02.394 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:46:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:46:32.399 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:46:32.401 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:46:32.401 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:47:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:47:02.398 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:47:02.399 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:47:02.400 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:47:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:47:32.397 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:47:32.398 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:47:32.398 ThaliTest[336:157677] client: fo,und peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:48:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:48:02.397 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:48:02.397 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:48:02.398 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:48:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:49:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:49:02.396 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:49:02.396 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:49:02.396 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:49:32.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:50:02.355 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:50:02.399 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:50:02.400 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:50:02.400 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:50:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:50:32.343 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:50:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:50:32.345 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:51:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:51:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:51:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:51:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:51:32.345 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:52:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:52:02.342 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:52:02.344 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:52:02.344 ThaliTest[336:157677] client: fo,und peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:52:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:52:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:52:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:52:32.345 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:53:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:53:02.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:53:02.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:53:02.344 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:53:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:53:32.347 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:53:32.348 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:53:32.348 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:54:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:54:02.342 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:54:02.343 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:54:02.347 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:54:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:55:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:55:02.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:55:02.345 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:55:02.345 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:55:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:55:32.343 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:55:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:55:32.344 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:56:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:56:02.342 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:56:02.342 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:56:02.343 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:56:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:56:33.078 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:56:33.079 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:56:33.079 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:57:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:57:02.338 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:57:02.339 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:57:02.340 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:57:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:58:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:58:02.337 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:58:02.337 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:58:02.343 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:58:32.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:58:32.337 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:58:32.340 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:58:32.341 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,2015-12-17 01:59:02.302 ThaliTest[336:157677] multipeer session: restart
,2015-12-17 01:59:02.345 ThaliTest[336:157677] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:59:02.346 ThaliTest[336:157677] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:59:02.346 ThaliTest[336:157677] client: found peer: Apple-Iphone5s-1_PT4765.ZBlg+A==
,teardown
,testSendData stopped
,2015-12-17 01:59:30.644 ThaliTest[336:157881] jxcore: stopBroadcasting
,2015-12-17 01:59:30.645 ThaliTest[336:157881] THEMultipeerSession stopping peer
2015-12-17 01:59:30.645 ThaliTest[336:157881] multipeer session: stop timer
2015-12-17 01:59:30.646 ThaliTest[336:157881] server session: disconnect
2015-12-17 01:59:30.646 ,ThaliTest[336:157881] server session: stateChange:2->0 Apple-IpadAir2-1_PT2260
,2015-12-17 01:59:30.653 ThaliTest[336:157881] server session: disconnect
2015-12-17 01:59:30.653 ThaliTest[336:157881] server session: stateChange:2->0 Apple-Iphone5-1_PT6883
,2015-12-17 01:59:30.666 ThaliTest[336:157881] server session: disconnect
2015-12-17 01:59:30.666 ThaliTest[336:157881] server session: stateChange:2->0 Apple-Iphone5s-1_PT4765
,2015-12-17 01:59:30.736 ThaliTest[336:157881] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-17T00:59:30.754Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:30.756Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:30.758Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:30.759Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
