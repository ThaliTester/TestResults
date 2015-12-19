#### Test 5065027869d93ea_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2F6957CB-DEE0-4950-819F-2EB58774C2AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/2F6957CB-DEE0-4950-819F-2EB58774C2AD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4EA0D990-C174-4DA9-9963-5238F96A0AFE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60509"
,(lldb)     command script import "/tmp/2F6957CB-DEE0-4950-819F-2EB58774C2AD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 01:21:46.861 ThaliTest[493:415535] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D8A71516-F7D1-4B79-82B2-0B94474F3934/Library/Cookies/Cookies.binarycookies
,2015-12-19 01:21:47.319 ThaliTest[493:415535] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 01:21:47.320 ThaliTest[493:415535] Multi-tasking -> Device: YES, App: YES
,2015-12-19 01:21:47.331 ThaliTest[493:415535] Unlimited access to network resources
,2015-12-19 01:21:47.344 ThaliTest[493:415535] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 01:21:56.383 ThaliTest[493:415535] Resetting plugins due to page load.
,2015-12-19 01:21:59.967 ThaliTest[493:415535] Finished load of: file:///var/mobile/Containers/Bundle/Application/4EA0D990-C174-4DA9-9963-5238F96A0AFE/ThaliTest.app/www/index.html
,2015-12-19 01:22:00.158 ThaliTest[493:415535] JXcore Cordova plugin initializing
,2015-12-19 01:22:00.159 ThaliTest[493:415755] JXcore instance initializing
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
,2015-12-19 01:22:01.256 ThaliTest[493:415535] THREAD WARNING: ['JXcore'] took '77.761963' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 53341
,2015-12-19 01:26:56.288 ThaliTest[493:415755] jxcore: startBroadcasting
,2015-12-19 01:26:56.307 ThaliTest[493:415755] server: starting Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:26:56.308 ThaliTest[493:415755] multipeer session: start timer: 0x15bac190
,2015-12-19 01:26:56.309 ThaliTest[493:415755] THEMultipeerSession initialized peer Apple-Iphone6-1_PT3810
,2015-12-19 01:26:56.310 ThaliTest[493:415755] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-19T00:26:56.316Z SendDataTCPServer.js: TCP/IP server is bound to port: 53341
,2015-12-19 01:26:57.379 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:26:57.382 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6779.RtEaKg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:26:57.386Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19T00:26:57.387Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19T00:26:57.387Z SendDataConnector.j,s: do connect now
2015-12-19 01:26:57.388 ThaliTest[493:415755] jxcore: connect Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:26:57.389 ThaliTest[493:415755] client session: connect
,2015-12-19 01:26:57.390 ThaliTest[493:415755] client session: stateChange:0->1 Apple-IpadAir2-1_PT6779.RtEaKg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 01:26:58.468 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 01:27:00.262 ThaliTest[493:416237] client session: connected
2015-12-19 01:27:00.262 ThaliTest[493:416237] client session: stateChange:1->2 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:00.316 ThaliTest[493:416242] client session: fireConnectCallback: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:27:00.317 ThaliTest[493:416242] jxcore: connect: success
2015-12-19T00:27:00.319Z SendDataConnector.js: CLIENT connected to 53344, error: null
,2015-12-19T00:27:00.319Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:00.324 ThaliTest[493:415535] client: relay established
2015-12-19 01:27:00.324 ThaliTest[493:415535] client: new accepted socket: 0x15bb9b50
,2015-12-19T00:27:00.340Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:00.682Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-19T00:27:00.695Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:00.709Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-19T00:27:00.855Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:00.855Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T00:27:00.857Z SendDataConnector.js: CLIENT Stop now
2015-12-19T00:27:00.857Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:00.858 ThaliTest[493:415755] jxcore: disconnect
2015-12-19 01:27:00.858 ThaliTest[493:415755] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:00.858 ThaliTest[493:415755] client session: disconnect
,2015-12-19 01:27:00.859 ThaliTest[493:415755] client session: stateChange:2->0 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:00.927 ThaliTest[493:415755] jxcore: disconnect: success
,2015-12-19T00:27:00.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6779.RtEaKg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:00.929Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:00.930Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:00.930Z SendDataConnector.js: do connect now
,2015-12-19 01:27:00.930 ThaliTest[493:415755] jxcore: connect Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:00.931 ThaliTest[493:415755] client session: connect
,2015-12-19 01:27:00.931 ThaliTest[493:415755] client session: stateChange:0->1 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:01.059 ThaliTest[493:415535] multipeer session: reset timer
2015-12-19 01:27:01.059 ThaliTest[493:415535] multipeer session: stop timer
2015-12-19 01:27:01.060 ThaliTest[493:415535] multipeer session: start timer: 0x15bac190
2015-12-19 01:27:01.060 ThaliTest[493:415535] server session: connect
2015-12-19 01:27:01.060 ThaliTest[493:415535] server session: stateChange:0->1 Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:01.066 ThaliTest[493:415535] server: accepting invitation Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:03.613 ThaliTest[493:416233] client session: connected
2015-12-19 01:27:03.613 ThaliTest[493:416233] client session: stateChange:1->2 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:03.673 ThaliTest[493:416232] client session: fireConnectCallback: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:03.673 ThaliTest[493:416232] jxcore: connect: success
2015-12-19T00:27:03.674Z SendDataConnector.js: CLIENT connected to ,53347, error: null
2015-12-19T00:27:03.675Z SendDataConnector.js: CLIENT starting client 
2015-12-19 01:27:03.677 ThaliTest[493:415535] client: relay established
2015-12-19 01:27:03.678 ThaliTest[493:415535] client: new accepted socket: 0x15cac630
,2015-12-19T00:27:03.691Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 01:27:03.800 ThaliTest[493:416232] server session: connected
2015-12-19 01:27:03.801 ThaliTest[493:416232] server session: stateChange:1->2 Apple-IpadAir2-1_PT6779
,2015-12-19T00:27:03.994Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-19T00:27:04.006Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:04.068Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-19T00:27:04.081Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T00:27:04.081Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:04.082Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:04.082Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:04.082 ThaliTest[493:415755] jxcore: disconnect
2015-12-19 01:27:04.083 ThaliTest[493:415755] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:04.083 ThaliTest[493:415755] client session: disconnect
2015-12-19 01:27:04.083 ThaliTest[493:415755] client session: stateChange:2->0 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:04.086 ThaliTest[493:415755] jxcore: disconnect: success
2015-12-19T00:27:04.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7601.1oUnQA==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5-1_PT7806.b8v14g==
2015-12-19T00:27:04.087Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19T00:27:04.087Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19T00:27:04.089Z SendDataConnector.js: do connect now
,2015-12-19 01:27:04.089 ThaliTest[493:415755] jxcore: connect Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:27:04.090 ThaliTest[493:415755] client session: connect
,2015-12-19 01:27:04.091 ThaliTest[493:415755] client session: stateChange:0->1 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:04.232 ThaliTest[493:415535] server relay: connected (to port: 53341)
,2015-12-19T00:27:04.244Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:04.257Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-19T00:27:04.270Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-19T00:27:04.285Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:04.333 ThaliTest[493:416237] server session: not connected Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:04.921 ThaliTest[493:415535] multipeer session: reset timer
2015-12-19 01:27:04.922 ThaliTest[493:415535] multipeer session: stop timer
2015-12-19 01:27:04.922 ThaliTest[493:415535] multipeer session: start timer: 0x15bac190
2015-12-19 01:27:04.922 ThaliTest[493:415535] server session: connect
2015-12-19 01:27:04.923 ThaliTest[493:415535] server session: stateChange:0->1 Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:04.934 ThaliTest[493:415535] server: accepting invitation Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:05.185 ThaliTest[493:415535] multipeer session: reset timer
2015-12-19 01:27:05.185 ThaliTest[493:415535] multipeer session: stop timer
2015-12-19 01:27:05.185 ThaliTest[493:415535] multipeer session: start timer: 0x15bac190
2015-12-19 01:27:05.186 ThaliTest[493:415535] server session: connect
,2015-12-19 01:27:05.186 ThaliTest[493:415535] server session: stateChange:0->1 Apple-Iphone5-1_PT7806
,2015-12-19 01:27:05.195 ThaliTest[493:415535] server: accepting invitation Apple-Iphone5-1_PT7806
,2015-12-19 01:27:06.719 ThaliTest[493:416242] client session: connected
2015-12-19 01:27:06.719 ThaliTest[493:416242] client session: stateChange:1->2 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:06.750 ThaliTest[493:416237] client session: fireConnectCallback: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:27:06.750 ThaliTest[493:416237] jxcore: connect: success
2015-12-19T00:27:06.751Z SendDataConnector.js: CLIENT connected to 53351, error: null
2015-12-19T00:27:06.752Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:06.755 ThaliTest[493:415535] client: relay established
2015-12-19 01:27:06.756 ThaliTest[493:415535] client: new accepted socket: 0x15ca9f50
,2015-12-19T00:27:06.769Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:07.074Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T00:27:07.146Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-19T00:27:07.208Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:07.208Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:07.209Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:07.209Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:07.209 ThaliTest[493:415755] jxcore: disconnect
,2015-12-19 01:27:07.210 ThaliTest[493:415755] client session: disconnectFromPeer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:07.210 ThaliTest[493:415755] client session: disconnect
,2015-12-19 01:27:07.210 ThaliTest[493:415755] client session: stateChange:2->0 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:07.274 ThaliTest[493:415755] jxcore: disconnect: success
,2015-12-19T00:27:07.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7806.b8v14g==
,---- round done--------
,startWithNextDevice
,2015-12-19 01:27:07.518 ThaliTest[493:416237] server session: connected
2015-12-19 01:27:07.519 ThaliTest[493:416237] server session: stateChange:1->2 Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:07.738 ThaliTest[493:416237] server session: connected
,2015-12-19 01:27:07.739 ThaliTest[493:416237] server session: stateChange:1->2 Apple-Iphone5-1_PT7806
,2015-12-19 01:27:07.741 ThaliTest[493:415535] server relay: connected (to port: 53341)
,2015-12-19T00:27:07.749Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 01:27:07.795 ThaliTest[493:415535] server relay: connected (to port: 53341)
,2015-12-19T00:27:07.807Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:07.908Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-19T00:27:07.999Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-19T00:27:08.017Z SendDataTCPServer.js: TCP/IP server has received 41468 bytes of data
,2015-12-19T00:27:08.033Z SendDataTCPServer.js: TCP/IP server has received 67180 bytes of data
,2015-12-19T00:27:08.049Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-19T00:27:08.064Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:08.118 ThaliTest[493:416237] server session: not connected Apple-Iphone5s-1_PT7601
,2015-12-19T00:27:08.314Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-19T00:27:08.332Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-19T00:27:08.349Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-19T00:27:08.365Z SendDataTCPServer.js: TCP/IP server has received 83078 bytes of data
,2015-12-19T00:27:08.379Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:08.452 ThaliTest[493:416233] server session: not connected Apple-Iphone5-1_PT7806
,2015-12-19 01:27:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:27:35.231 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:35.231 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:36.209 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:28:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:28:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:28:35.224 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:28:35.224 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:28:35.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:29:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:29:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:29:35.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:29:35.226 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:29:35.227 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,appEnteredForeground wasn't registered
,2015-12-19 01:30:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:30:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:30:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:30:05.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:30:17.571 ThaliTest[493:415535] client: lost peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:30:17.572 ThaliTest[493:415535] client session: onPeerLost: Apple-Iphone5s-1_PT7601.1oUnQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 01:30:22.767 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-19 01:30:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:30:35.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:30:35.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:30:35.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:31:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:31:05.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:31:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:31:06.151 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:31:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:32:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:32:05.222 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:32:05.222 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:32:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:32:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:33:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:33:05.219 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:33:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:33:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:33:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:33:35.229 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:33:35.229 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:33:36.163 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:34:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:34:05.224 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:34:05.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:34:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:34:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:34:35.229 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:34:35.229 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:34:36.178 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:35:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:35:05.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:35:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:35:06.135 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:35:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:35:35.220 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:35:35.222 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:35:35.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:36:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:36:05.225 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:36:05.230 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:36:05.231 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:36:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:36:35.225 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:36:35.226 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:36:35.228 ThaliTest[493:415535] client: fo,und peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:37:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:37:05.227 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:37:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:37:05.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:37:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:37:35.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:37:35.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:37:36.128 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:38:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:38:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:38:35.224 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:38:35.224 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:38:35.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:39:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:39:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:39:35.222 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:39:35.223 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:39:35.224 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:40:05.186 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:40:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:40:35.222 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:40:35.223 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:40:35.224 ThaliTest[493:415535] client: fo,und peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:41:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:41:05.225 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:41:05.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:41:06.158 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:41:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:42:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:42:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:42:05.224 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:42:05.225 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:42:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:43:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:43:05.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:43:05.226 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:43:05.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:43:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:43:35.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:43:35.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:43:35.230 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T00:43:36.331Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 01:44:05.186 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:44:05.225 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:44:05.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:44:05.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:44:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:45:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:45:05.223 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:05.224 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:45:06.113 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:45:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:45:35.224 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:35.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:45:36.208 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:46:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:46:35.186 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:46:35.225 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:46:35.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:46:35.231 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:46:57.906 ThaliTest[493:415535] client: lost peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:46:57.906 ThaliTest[493:415535] client session: onPeerLost: Apple-IpadAir2-1_PT6779.RtEaKg==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT6779.RtEaKg==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-19 01:46:58.027 ThaliTest[493:415535] client: lost peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:58.027 ThaliTest[493:415535] client session: onPeerLost: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:58.028 ThaliTest[493:415535] clien,t: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
2015-12-19 01:46:58.028 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerName":"(null)","peerAvaila,ble":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.jHAIjw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier,":"Apple-IpadAir2-1_PT6779.Eyppcg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-19 01:47:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:47:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:47:35.226 ThaliTest[493:415535] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:47:35.227 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:47:35.228 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:48:05.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:48:35.187 ThaliTest[493:415535] multipeer session: restart
,2015-12-19 01:48:35.225 ThaliTest[493:415535] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:48:35.225 ThaliTest[493:415535] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
2015-12-19 01:48:35.226 ThaliTest[493:415535] client: fou,nd peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:49:05.187 ThaliTest[493:415535] multipeer session: restart

```
