#### Test 50650278cd699a4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/C8326539-31FB-4064-BD4F-517CEEB0D330/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C8326539-31FB-4064-BD4F-517CEEB0D330/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cd699a4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FCD79787-F8B5-4CA9-837E-9011FE8B1E95/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58480"
,(lldb)     command script import "/tmp/C8326539-31FB-4064-BD4F-517CEEB0D330/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 05:36:17.349 ThaliTest[270:50646] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/56010F2E-9F94-484B-A739-91E0D53D057D/Library/Cookies/Cookies.binarycookies
,2015-12-16 05:36:17.692 ThaliTest[270:50646] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 05:36:17.692 ThaliTest[270:50646] Multi-tasking -> Device: YES, App: YES
,2015-12-16 05:36:17.701 ThaliTest[270:50646] Unlimited access to network resources
,2015-12-16 05:36:17.713 ThaliTest[270:50646] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 05:36:27.059 ThaliTest[270:50646] Resetting plugins due to page load.
,2015-12-16 05:36:30.843 ThaliTest[270:50646] Finished load of: file:///var/mobile/Containers/Bundle/Application/FCD79787-F8B5-4CA9-837E-9011FE8B1E95/ThaliTest.app/www/index.html
,2015-12-16 05:36:31.022 ThaliTest[270:50646] JXcore Cordova plugin initializing
,2015-12-16 05:36:31.023 ThaliTest[270:50833] JXcore instance initializing
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
,2015-12-16 05:36:32.114 ThaliTest[270:50646] THREAD WARNING: ['JXcore'] took '81.744141' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-16 05:41:40.192 ThaliTest[270:50833] jxcore: startBroadcasting
,2015-12-16 05:41:40.208 ThaliTest[270:50833] server: starting Apple-Iphone6-1_PT4432.Ya3H6w==
,2015-12-16 05:41:40.211 ThaliTest[270:50833] multipeer session: start timer: 0x194633a0
2015-12-16 05:41:40.211 ThaliTest[270:50833] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4432
2015-12-16 05:41:40.213 ThaliTest[270:50833] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-16 05:41:43.526 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.9FcBSA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1441.9FcBSA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT1441.9FcBSA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-16 05:41:43.690 ThaliTest[270:50833] jxcore: stopBroadcasting
2015-12-16 05:41:43.690 ThaliTest[270:50833] THEMultipeerSession stopping peer
2015-12-16 05:41:43.691 ThaliTest[270:50833] multipeer session: stop timer
2015-12-16 05:41:43.691 Thali,Test[270:50833] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":2}bt-address length : 0
,daya100000
check server
,serverPort is 50103
,2015-12-16 05:41:44.165 ThaliTest[270:50833] jxcore: startBroadcasting
,2015-12-16 05:41:44.168 ThaliTest[270:50833] server: starting Apple-Iphone6-1_PT4432.nDL3Zg==
2015-12-16 05:41:44.170 ThaliTest[270:50833] multipeer session: start timer: 0x19470030
2015-12-16 05:41:44.171 ThaliTest[270:50833] THEMultipeerSession initial,ized peer Apple-Iphone6-1_PT4432
2015-12-16 05:41:44.171 ThaliTest[270:50833] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-16T04:41:44.177Z SendDataTCPServer.js: TCP/IP server is bound to port: 50103
,2015-12-16 05:41:45.466 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1441.VYOaAw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,device[1]: Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16T04:41:45.471Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16T04:41:45.473Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16T04:41:45.473Z SendDataConnector.js: do connect now
2015-12-16 05:41:45.474 ThaliTest[270:50833] jxcore: connect Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:41:45.475 ThaliTest[270:50833] client session: connect
2015-12-16 05:41:45.475 ThaliTest[270:50833] client session: stateChange:0->1 Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:41:45.607 ThaliTest[270:50646] multipeer session: reset timer
,2015-12-16 05:41:45.608 ThaliTest[270:50646] multipeer session: stop timer
2015-12-16 05:41:45.609 ThaliTest[270:50646] multipeer session: start timer: 0x19470030
,2015-12-16 05:41:45.611 ThaliTest[270:50646] server session: connect
2015-12-16 05:41:45.612 ThaliTest[270:50646] server session: stateChange:0->1 Apple-Iphone5-1_PT1441
,2015-12-16 05:41:45.620 ThaliTest[270:50646] server: accepting invitation Apple-Iphone5-1_PT1441
,2015-12-16 05:41:48.172 ThaliTest[270:51336] client session: connected
2015-12-16 05:41:48.175 ThaliTest[270:51336] client session: stateChange:1->2 Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16 05:41:48.177 ThaliTest[270:51334] server session: connected
2,015-12-16 05:41:48.178 ThaliTest[270:51334] server session: stateChange:1->2 Apple-Iphone5-1_PT1441
,2015-12-16 05:41:48.296 ThaliTest[270:51325] client session: fireConnectCallback: Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16 05:41:48.297 ThaliTest[270:51325] jxcore: connect: success
2015-12-16T04:41:48.300Z SendDataConnector.js: CLIENT connected to 50106, error: null
2015-12-16T04:41:48.300Z SendDataConnector.js: CLIENT starting client 
,2015-12-16 05:41:48.303 ThaliTest[270:50646] client: relay established
2015-12-16 05:41:48.304 ThaliTest[270:50646] client: new accepted socket: 0x193a1c30
,2015-12-16 05:41:48.308 ThaliTest[270:50646] server relay: connected (to port: 50103)
,2015-12-16T04:41:48.320Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-16T04:41:48.322Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-16T04:41:48.763Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-16T04:41:48.776Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-16T04:41:48.809Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-16T04:41:48.811Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-16T04:41:48.811Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-16T04:41:48.813Z SendDataConnector.js: CLIENT Stop now
2015-12-16T04:41:48.813Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-16 05:41:48.814 ThaliTest[270:50833] jxcore: disconnect
2015-12-16 05:41:48.814 ThaliTest[270,:50833] client session: disconnectFromPeer: Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16 05:41:48.814 ThaliTest[270:50833] client session: disconnect
,2015-12-16 05:41:48.814 ThaliTest[270:50833] client session: stateChange:2->0 Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:41:48.884 ThaliTest[270:50833] jxcore: disconnect: success
2015-12-16T04:41:48.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1441.VYOaAw==
---- round done--------
,startWithNextDevice
,2015-12-16T04:41:48.898Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-16 05:41:48.945 ThaliTest[270:51325] server session: not connected Apple-Iphone5-1_PT1441
,2015-12-16 05:42:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:42:15.649 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:42:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:42:45.646 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:43:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:43:15.647 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:43:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:43:45.650 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:44:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:44:15.648 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:44:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:45:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:45:15.639 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:45:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:45:45.641 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:46:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:46:15.640 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:46:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:46:45.641 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:47:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:47:15.641 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:47:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:47:45.638 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:48:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:48:15.642 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:48:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:49:15.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:49:15.643 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:49:45.611 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:49:45.641 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:50:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:50:15.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:50:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:50:45.590 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:51:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:51:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:51:45.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:51:46.275 ThaliTest[270:50646] client: lost peer: Apple-Iphone5-1_PT1441.VYOaAw==
2015-12-16 05:51:46.275 ThaliTest[270:50646] client session: onPeerLost: Apple-Iphone5-1_PT1441.VYOaAw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1441.VYOaAw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-16 05:51:53.142 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1441.VYOaAw==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-16 05:52:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:52:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:52:45.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:53:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:53:15.590 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:53:45.559 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:53:45.590 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:54:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:54:15.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:54:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:54:45.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:55:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:55:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:55:45.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:56:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:56:15.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:56:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:57:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:57:15.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:57:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:57:46.243 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:58:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:58:15.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,timeout now
,weAreDoneNow, resultArray.length: 1
,sendReportNow
,done, now sending data to server
,2015-12-16T04:58:24.135Z SendDataConnector.js: CLIENT Stop now
,2015-12-16 05:58:45.557 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:59:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:59:15.586 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 05:59:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 05:59:45.590 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 06:00:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:00:15.589 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 06:00:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:00:45.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 06:01:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:01:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:01:45.588 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 06:02:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:02:16.312 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==
,2015-12-16 06:02:45.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:03:15.558 ThaliTest[270:50646] multipeer session: restart
,2015-12-16 06:03:15.587 ThaliTest[270:50646] client: found peer: Apple-Iphone5-1_PT1441.VYOaAw==

```
