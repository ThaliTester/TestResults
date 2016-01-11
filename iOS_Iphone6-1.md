#### Test 55613145e2b298d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4900E4BC-F258-44EF-A5CF-40248B604494/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4900E4BC-F258-44EF-A5CF-40248B604494/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/46E9B625-72E9-4B1C-B0E4-FB72290202B4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52470"
,(lldb)     command script import "/tmp/4900E4BC-F258-44EF-A5CF-40248B604494/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 15:38:08.650 ThaliTest[1742:3677565] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5C0BC221-87B0-41E6-A8C9-66C9A6927EDA/Library/Cookies/Cookies.binarycookies
,2016-01-11 15:38:08.896 ThaliTest[1742:3677565] Apache Cordova native platform version 3.9.2 is starting.
2016-01-11 15:38:08.897 ThaliTest[1742:3677565] Multi-tasking -> Device: YES, App: YES
,2016-01-11 15:38:08.904 ThaliTest[1742:3677565] Unlimited access to network resources
,2016-01-11 15:38:08.912 ThaliTest[1742:3677565] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 15:38:13.076 ThaliTest[1742:3677565] Resetting plugins due to page load.
,2016-01-11 15:38:14.435 ThaliTest[1742:3677565] Finished load of: file:///var/mobile/Containers/Bundle/Application/46E9B625-72E9-4B1C-B0E4-FB72290202B4/ThaliTest.app/www/index.html
,2016-01-11 15:38:14.596 ThaliTest[1742:3677565] JXcore Cordova plugin initializing
,2016-01-11 15:38:14.597 ThaliTest[1742:3677729] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-11 15:38:15.742 ThaliTest[1742:3677565] THREAD WARNING: ['JXcore'] took '64.122070' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-11 15:43:41.562 ThaliTest[1742:3677729] jxcore: startBroadcasting
,2016-01-11 15:43:41.568 ThaliTest[1742:3677729] server: starting Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:41.569 ThaliTest[1742:3677729] multipeer session: start timer: 0x18464f50
2016-01-11 15:43:41.569 ThaliTest[1742:3677729] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-11 15:43:41.569 ThaliTest[1742:3677729] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-11 15:43:42.602 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:42.603 ThaliTest[1742:3677565] client: found peer: Apple-IpadAir2-1.aUvv7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ=,=","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.oKqzPQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-11 15:43:47.517 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5s-1.IqfRAg==
,teardown
,testFindPeers stopped
,2016-01-11 15:43:48.755 ThaliTest[1742:3677729] jxcore: stopBroadcasting
2016-01-11 15:43:48.755 ThaliTest[1742:3677729] THEMultipeerSession stopping peer
2016-01-11 15:43:48.755 ThaliTest[1742:3677729] multipeer session: stop timer
2016-01-11 15:43:48.756 ThaliTest[1742:3677729] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
serverPort is 49904
,2016-01-11 15:43:49.235 ThaliTest[1742:3677729] jxcore: startBroadcasting
,2016-01-11 15:43:49.238 ThaliTest[1742:3677729] server: starting Apple-Iphone6-1.wtwmkg==
2016-01-11 15:43:49.238 ThaliTest[1742:3677729] multipeer session: start timer: 0x183f9bc0
2016-01-11 15:43:49.238 ThaliTest[1742:3677729] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-11 15:43:49.238 ThaliTest[1742:3677729] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-11T14:43:49.240Z SendDataTCPServer.js: TCP/IP server is bound to port: 49904
,2016-01-11 15:43:49.908 ThaliTest[1742:3677565] client: found peer: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:43:49.908 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5-1.FPpLTg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.3/8jow,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1.3/8jow==
2016-01-11T14:43:49.909Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:43:49.910Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:43:49.910Z SendDataConnector.js: do connect now
2016-01-11 15:43:49.910 ThaliTest[1742:3677729] jxcore: connect Apple-IpadAir2-1.3/8jow==
2016-01-11 15:4,3:49.910 ThaliTest[1742:3677729] client session: connect
2016-01-11 15:43:49.910 ThaliTest[1742:3677729] client session: stateChange:0->1 Apple-IpadAir2-1.3/8jow==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.FPpLTg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:49.937 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5s-1./+n+RQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1./+n+RQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:53.163 ThaliTest[1742:3678250] client session: connected
2016-01-11 15:43:53.164 ThaliTest[1742:3678250] client session: stateChange:1->2 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:43:53.166 ThaliTest[1742:3678250] client session: fireConnectCallback: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:43:53.166 ThaliTest[1742:3678250] jxcore: connect: success
,2016-01-11T14:43:53.167Z SendDataConnector.js: CLIENT connected to 49907, error: null
2016-01-11T14:43:53.167Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:43:53.169 ThaliTest[1742:3677565] client: relay established
2016-01-11 15:43:53.169 ThaliTest[1742:3677565] client: new accepted socket: 0x18324500
,2016-01-11T14:43:53.181Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:43:53.879Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T14:43:53.879Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T14:43:53.880Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:43:53.880Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:43:53.881 ThaliTest[1742:3677729] jxcore: disconnect
,2016-01-11 15:43:53.881 ThaliTest[1742:3677729] client session: disconnectFromPeer: Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:43:53.882 ThaliTest[1742:3677729] client session: disconnect
,2016-01-11 15:43:53.882 ThaliTest[1742:3677729] client session: stateChange:2->0 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:43:53.953 ThaliTest[1742:3677729] jxcore: disconnect: success
2016-01-11T14:43:53.953Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.3/8jow==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:43:53.954Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:43:53.955Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:43:53.955Z SendDataConnector.js: do connect now
,2016-01-11 15:43:53.955 ThaliTest[1742:3677729] jxcore: connect Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:43:53.956 ThaliTest[1742:3677729] client session: connect
,2016-01-11 15:43:53.956 ThaliTest[1742:3677729] client session: stateChange:0->1 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:43:56.965 ThaliTest[1742:3678239] client session: connected
2016-01-11 15:43:56.965 ThaliTest[1742:3678239] client session: stateChange:1->2 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:43:57.015 ThaliTest[1742:3678250] client session: fireConnectCallback: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:43:57.015 ThaliTest[1742:3678250] jxcore: connect: success
2016-01-11T14:43:57.015Z SendDataConnector.js: CLIENT connected to 49910, error: null
2016-01-11T14:43:57.015Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:43:57.017 ThaliTest[1742:3677565] client: relay established
2016-01-11 15:43:57.017 ThaliTest[1742:3677565] client: new accepted socket: 0x16da1070
,2016-01-11T14:43:57.027Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:43:57.872Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T14:43:57.887Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:43:57.941Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:43:57.941Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T14:43:57.942Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:43:57.942Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:43:57.942 ThaliTest[1742:3677729] jxcore: disconnect
,2016-01-11 15:43:57.943 ThaliTest[1742:3677729] client session: disconnectFromPeer: Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:43:57.943 ThaliTest[1742:3677729] client session: disconnect
,2016-01-11 15:43:57.943 ThaliTest[1742:3677729] client session: stateChange:2->0 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:43:57.957 ThaliTest[1742:3677729] jxcore: disconnect: success
,2016-01-11T14:43:57.959Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.FPpLTg==
---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1./+n+RQ==
,2016-01-11T14:43:57.961Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1./+n+RQ==
2016-01-11T14:43:57.962Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1./+n+RQ==
,2016-01-11T14:43:57.962Z SendDataConnector.js: do connect now
,2016-01-11 15:43:57.963 ThaliTest[1742:3677729] jxcore: connect Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:43:57.963 ThaliTest[1742:3677729] client session: connect
,2016-01-11 15:43:57.963 ThaliTest[1742:3677729] client session: stateChange:0->1 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:00.829 ThaliTest[1742:3678239] client session: connected
2016-01-11 15:44:00.829 ThaliTest[1742:3678239] client session: stateChange:1->2 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:00.849 ThaliTest[1742:3678250] client session: fireConnectCallback: Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:44:00.849 ThaliTest[1742:3678250] jxcore: connect: success
2016-01-11T14:44:00.850Z SendDataConnector.js: CLIENT connected to 49913, error: null
2016-01-11T14:44:00.850Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:00.851 ThaliTest[1742:3677565] client: relay established
2016-01-11 15:44:00.851 ThaliTest[1742:3677565] client: new accepted socket: 0x18481970
,2016-01-11T14:44:00.864Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:01.489Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-11T14:44:01.543Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:44:01.559Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:01.559Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T14:44:01.560Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:44:01.560Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:01.561 ThaliTest[1742:3677729] jxcore: disconnect
,2016-01-11 15:44:01.561 ThaliTest[1742:3677729] client session: disconnectFromPeer: Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:01.562 ThaliTest[1742:3677729] client session: disconnect
,2016-01-11 15:44:01.570 ThaliTest[1742:3677729] client session: stateChange:2->0 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:01.576 ThaliTest[1742:3677729] jxcore: disconnect: success
,2016-01-11T14:44:01.580Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1./+n+RQ==
,---- round done--------
,startWithNextDevice
,2016-01-11 15:44:19.239 ThaliTest[1742:3677565] multipeer session: restart
,2016-01-11 15:44:19.258 ThaliTest[1742:3677565] client: found peer: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:44:19.258 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:19.258 ThaliTest[1742:3677565] client: found peer:, Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:40.001 ThaliTest[1742:3677565] multipeer session: reset timer
2016-01-11 15:44:40.001 ThaliTest[1742:3677565] multipeer session: stop timer
2016-01-11 15:44:40.002 ThaliTest[1742:3677565] multipeer session: start timer: 0x183f9bc0
2016-,01-11 15:44:40.002 ThaliTest[1742:3677565] server session: connect
2016-01-11 15:44:40.002 ThaliTest[1742:3677565] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-11 15:44:40.005 ThaliTest[1742:3677565] server: accepting invitation Apple-Iphone5s-1
,2016-01-11 15:44:40.307 ThaliTest[1742:3677565] multipeer session: reset timer
2016-01-11 15:44:40.307 ThaliTest[1742:3677565] multipeer session: stop timer
2016-01-11 15:44:40.307 ThaliTest[1742:3677565] multipeer session: start timer: 0x183f9bc0
2016-01-11 15:44:40.307 ThaliTest[1742:3677565] server session: connect
,2016-01-11 15:44:40.308 ThaliTest[1742:3677565] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-11 15:44:40.312 ThaliTest[1742:3677565] server: accepting invitation Apple-IpadAir2-1
,2016-01-11 15:44:42.058 ThaliTest[1742:3677565] multipeer session: reset timer
2016-01-11 15:44:42.058 ThaliTest[1742:3677565] multipeer session: stop timer
2016-01-11 15:44:42.058 ThaliTest[1742:3677565] multipeer session: start timer: 0x183f9bc0
2016-,01-11 15:44:42.059 ThaliTest[1742:3677565] server session: connect
2016-01-11 15:44:42.059 ThaliTest[1742:3677565] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-11 15:44:42.062 ThaliTest[1742:3677565] server: accepting invitation Apple-Iphone5-1
,2016-01-11 15:44:42.306 ThaliTest[1742:3678396] server session: connected
2016-01-11 15:44:42.306 ThaliTest[1742:3678396] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 15:44:42.363 ThaliTest[1742:3677565] server relay: connected (to port: 49904)
,2016-01-11T14:44:42.369Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:42.817Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-11T14:44:42.829Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-11T14:44:42.854Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-11T14:44:42.891Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-11T14:44:42.905Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-11T14:44:42.952Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-11T14:44:42.963Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:43.012 ThaliTest[1742:3678399] server session: not connected Apple-Iphone5s-1
,2016-01-11 15:44:43.280 ThaliTest[1742:3678396] server session: connected
,2016-01-11 15:44:43.280 ThaliTest[1742:3678396] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11 15:44:43.283 ThaliTest[1742:3677565] server relay: connected (to port: 49904)
,2016-01-11T14:44:43.286Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:43.688Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-11T14:44:43.739Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-11T14:44:43.752Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-11T14:44:43.789Z SendDataTCPServer.js: TCP/IP server has received 77745 bytes of data
,2016-01-11T14:44:43.801Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-11T14:44:43.815Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:43.833 ThaliTest[1742:3678396] server session: not connected Apple-IpadAir2-1
,2016-01-11 15:44:44.468 ThaliTest[1742:3678399] server session: connected
2016-01-11 15:44:44.468 ThaliTest[1742:3678399] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 15:44:44.519 ThaliTest[1742:3677565] server relay: connected (to port: 49904)
,2016-01-11T14:44:44.523Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:45.575Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-11T14:44:45.588Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-11T14:44:45.599Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-11T14:44:45.612Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-11T14:44:45.638Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-11T14:44:45.651Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-11T14:44:45.699Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-11T14:44:45.711Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:45.896 ThaliTest[1742:3678396] server session: not connected Apple-Iphone5-1
,2016-01-11 15:45:12.060 ThaliTest[1742:3677565] multipeer session: restart
,2016-01-11 15:45:12.074 ThaliTest[1742:3677565] client: found peer: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:45:12.075 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:45:12.075 ThaliTest[1742:3677565] client: found peer: Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:45:23.091 ThaliTest[1742:3677565] client: lost peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:45:23.091 ThaliTest[1742:3677565] client session: onPeerLost: Apple-Iphone5-1.FPpLTg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.FPpLTg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2016-01-11T14:45:29.255Z SendDataConnector.js: CLIENT Stop now
,teardown
,testSendData stopped
,2016-01-11 15:45:29.513 ThaliTest[1742:3677729] jxcore: stopBroadcasting
2016-01-11 15:45:29.513 ThaliTest[1742:3677729] THEMultipeerSession stopping peer
2016-01-11 15:45:29.513 ThaliTest[1742:3677729] multipeer session: stop timer
2016-01-11 15:45:29.,514 ThaliTest[1742:3677729] server session: disconnect
2016-01-11 15:45:29.514 ThaliTest[1742:3677729] server session: stateChange:2->0 Apple-Iphone5-1
2016-01-11 15:45:29.516 ThaliTest[1742:3677729] server session: disconnect
2016-01-11 15:45:29.516 ThaliTest[1742:3677729] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-11 15:45:29.520 ThaliTest[1742:3677729] server session: disconnect
2016-01-11 15:45:29.520 ThaliTest[1742:3677729] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-11 15:45:29.523 ThaliTest[1742:3677729] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-11T14:45:29.537Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:29.538Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:29.539Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:29.539Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
