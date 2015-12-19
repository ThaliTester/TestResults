#### Test 5065027869d93ea_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A8C388E5-705D-4EDD-B714-F206541F3E4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A8C388E5-705D-4EDD-B714-F206541F3E4C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB2CE713-D2C0-4B17-8D57-086593FD9FA2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60507"
,(lldb)     command script import "/tmp/A8C388E5-705D-4EDD-B714-F206541F3E4C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 01:21:47.805 ThaliTest[493:426900] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A89B1079-AD68-4434-ABAC-A57C9968DDC8/Library/Cookies/Cookies.binarycookies
,2015-12-19 01:21:48.192 ThaliTest[493:426900] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 01:21:48.194 ThaliTest[493:426900] Multi-tasking -> Device: YES, App: YES
,2015-12-19 01:21:48.202 ThaliTest[493:426900] Unlimited access to network resources
,2015-12-19 01:21:48.211 ThaliTest[493:426900] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 01:21:57.350 ThaliTest[493:426900] Resetting plugins due to page load.
,2015-12-19 01:22:01.091 ThaliTest[493:426900] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB2CE713-D2C0-4B17-8D57-086593FD9FA2/ThaliTest.app/www/index.html
,2015-12-19 01:22:01.231 ThaliTest[493:426900] JXcore Cordova plugin initializing
,2015-12-19 01:22:01.231 ThaliTest[493:427148] JXcore instance initializing
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
,2015-12-19 01:22:02.216 ThaliTest[493:426900] THREAD WARNING: ['JXcore'] took '69.371826' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 53196
,2015-12-19 01:26:57.152 ThaliTest[493:427148] jxcore: startBroadcasting
,2015-12-19 01:26:57.165 ThaliTest[493:427148] server: starting Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:26:57.166 ThaliTest[493:427148] multipeer session: start timer: 0x19532350
2015-12-19 01:26:57.166 ThaliTest[493:427148] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6779
2015-12-19 01:26:57.166 ThaliTest[493:427148] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-19T00:26:57.172Z SendDataTCPServer.js: TCP/IP server is bound to port: 53196
,2015-12-19 01:26:58.312 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19T00:26:58.319Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19T00:26:58.320Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19T00:26:58.321Z SendDataConnector.js: do connect now
2015-12-19 01:26:58.322 ThaliTest[493:427148] jxcore: connect Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:26:58.323 ThaliTest[493:427148] client session: connect
2015-12-19 01:26:58.323 Tha,liTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:26:58.323 ThaliTest[493:427148] client session: stateChange:0->1 Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:26:58.323 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3810.9x5b9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 01:26:58.519 ThaliTest[493:426900] multipeer session: reset timer
2015-12-19 01:26:58.520 ThaliTest[493:426900] multipeer session: stop timer
2015-12-19 01:26:58.520 ThaliTest[493:426900] multipeer session: start timer: 0x19532350
2015-12-19 01:26:58.520 ThaliTest[493:426900] server session: connect
,2015-12-19 01:26:58.521 ThaliTest[493:426900] server session: stateChange:0->1 Apple-Iphone6-1_PT3810
,2015-12-19 01:26:58.530 ThaliTest[493:426900] server: accepting invitation Apple-Iphone6-1_PT3810
,2015-12-19 01:26:58.530 ThaliTest[493:426900] multipeer session: reset timer
,2015-12-19 01:26:58.531 ThaliTest[493:426900] multipeer session: stop timer
,2015-12-19 01:26:58.532 ThaliTest[493:426900] multipeer session: start timer: 0x19532350
,2015-12-19 01:26:58.533 ThaliTest[493:426900] server session: connect
,2015-12-19 01:26:58.534 ThaliTest[493:426900] server session: stateChange:0->1 Apple-Iphone5-1_PT7806
,2015-12-19 01:26:58.545 ThaliTest[493:426900] server: accepting invitation Apple-Iphone5-1_PT7806
,2015-12-19 01:27:01.206 ThaliTest[493:427748] server session: connected
2015-12-19 01:27:01.206 ThaliTest[493:427748] server session: stateChange:1->2 Apple-Iphone6-1_PT3810
,2015-12-19 01:27:01.216 ThaliTest[493:426900] server relay: connected (to port: 53196)
2015-12-19 01:27:01.217 ThaliTest[493:427781] client session: connected
2015-12-19 01:27:01.217 ThaliTest[493:427781] client session: stateChange:1->2 Apple-Iphone5-1_,PT7806.b8v14g==
2015-12-19T00:27:01.218Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 01:27:01.227 ThaliTest[493:427749] client session: fireConnectCallback: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:01.228 ThaliTest[493:427749] jxcore: connect: success
2015-12-19T00:27:01.230Z SendDataConnector.js: CLIENT connected to 53200, error: null
2015-12-19T00:27:01.230Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:01.237 ThaliTest[493:426900] client: relay established
2015-12-19 01:27:01.237 ThaliTest[493:426900] client: new accepted socket: 0x1953fbd0
,2015-12-19 01:27:01.239 ThaliTest[493:427749] server session: connected
2015-12-19 01:27:01.240 ThaliTest[493:427749] server session: stateChange:1->2 Apple-Iphone5-1_PT7806
,2015-12-19 01:27:01.245 ThaliTest[493:426900] server relay: connected (to port: 53196)
,2015-12-19T00:27:01.247Z SendDataTCPServer.js: TCP/IP server connected
2015-12-19T00:27:01.250Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:01.544Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-19T00:27:01.570Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-19T00:27:01.580Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-19T00:27:01.593Z SendDataTCPServer.js: TCP/IP server has received 38852 bytes of data
,2015-12-19T00:27:01.607Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-19T00:27:01.787Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:01.815 ThaliTest[493:427748] server session: not connected Apple-Iphone6-1_PT3810
,2015-12-19T00:27:01.861Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-19T00:27:01.887Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:01.901Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-19T00:27:01.914Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T00:27:01.915Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T00:27:01.917Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:01.917Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:01.920 ThaliTest[493:427148] jxcore: disconnect
2015-12-19 01:27:01.920 ThaliTest[493:427148] client session: disconnectFromPeer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:27:01.920 ThaliTest[493:427148] client session: disconnect
,2015-12-19 01:27:01.921 ThaliTest[493:427148] client session: stateChange:2->0 Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:01.931 ThaliTest[493:427148] jxcore: disconnect: success
2015-12-19T00:27:01.932Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT7806.b8v14g==
---- round done--------
startWithNextDevice
device[2]: Apple,-Iphone6-1_PT3810.9x5b9w==
2015-12-19T00:27:01.935Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19T00:27:01.935Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19T00:27:01.935Z SendDataConnector.js: do connect now
,2015-12-19 01:27:01.937 ThaliTest[493:427148] jxcore: connect Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:01.940 ThaliTest[493:427148] client session: connect
,2015-12-19 01:27:01.941 ThaliTest[493:427148] client session: stateChange:0->1 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:01.960Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:02.051 ThaliTest[493:427781] server session: not connected Apple-Iphone5-1_PT7806
,2015-12-19 01:27:02.403 ThaliTest[493:426900] multipeer session: reset timer
2015-12-19 01:27:02.403 ThaliTest[493:426900] multipeer session: stop timer
,2015-12-19 01:27:02.403 ThaliTest[493:426900] multipeer session: start timer: 0x19532350
2015-12-19 01:27:02.403 ThaliTest[493:426900] server session: connect
2015-12-19 01:27:02.403 ThaliTest[493:426900] server session: stateChange:0->1 Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:02.406 ThaliTest[493:426900] server: accepting invitation Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:04.741 ThaliTest[493:427781] client session: connected
,2015-12-19 01:27:04.742 ThaliTest[493:427781] client session: stateChange:1->2 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:04.747 ThaliTest[493:427781] client session: fireConnectCallback: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:27:04.747 ThaliTest[493:427781] jxcore: connect: success
,2015-12-19T00:27:04.748Z SendDataConnector.js: CLIENT connected to 53204, error: null
,2015-12-19T00:27:04.748Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:04.751 ThaliTest[493:426900] client: relay established
2015-12-19 01:27:04.751 ThaliTest[493:426900] client: new accepted socket: 0x1943f930
,2015-12-19T00:27:04.765Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 01:27:04.911 ThaliTest[493:427748] server session: connected
2015-12-19 01:27:04.911 ThaliTest[493:427748] server session: stateChange:1->2 Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:04.938 ThaliTest[493:426900] server relay: connected (to port: 53196)
,2015-12-19T00:27:05.008Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:05.202Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-19T00:27:05.240Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:05.253Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T00:27:05.254Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:05.254Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:05.254Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:05.255 ThaliTest[493:427148] jxcore: disconnect
,2015-12-19 01:27:05.255 ThaliTest[493:427148] client session: disconnectFromPeer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:05.256 ThaliTest[493:427148] client session: disconnect
,2015-12-19 01:27:05.256 ThaliTest[493:427148] client session: stateChange:2->0 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:05.261 ThaliTest[493:427148] jxcore: disconnect: success
,2015-12-19T00:27:05.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3810.9x5b9w==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:05.265Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:05.265Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:05.265Z SendDataConnector.js: do connect now
,2015-12-19 01:27:05.265 ThaliTest[493:427148] jxcore: connect Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:05.266 ThaliTest[493:427148] client session: connect
,2015-12-19 01:27:05.266 ThaliTest[493:427148] client session: stateChange:0->1 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:05.370Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-19T00:27:05.384Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-19T00:27:05.395Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-19T00:27:05.410Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-19T00:27:05.424Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-19T00:27:05.461Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:05.528 ThaliTest[493:427758] server session: not connected Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:08.276 ThaliTest[493:427781] client session: connected
,2015-12-19 01:27:08.276 ThaliTest[493:427781] client session: stateChange:1->2 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:08.281 ThaliTest[493:427781] client session: fireConnectCallback: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:08.281 ThaliTest[493:427781] jxcore: connect: success
,2015-12-19T00:27:08.282Z SendDataConnector.js: CLIENT connected to 53208, error: null
,2015-12-19T00:27:08.283Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:08.286 ThaliTest[493:426900] client: relay established
2015-12-19 01:27:08.286 ThaliTest[493:426900] client: new accepted socket: 0x19536d30
,2015-12-19T00:27:08.299Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:08.935Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:08.936Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T00:27:08.936Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:08.937Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:08.938 ThaliTest[493:427148] jxcore: disconnect
2015-12-19 01:27:08.938 ThaliTest[493:427148] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:08.938 ThaliTest[493:427148] client session: disconnect
,2015-12-19 01:27:08.938 ThaliTest[493:427148] client session: stateChange:2->0 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:08.945 ThaliTest[493:427148] jxcore: disconnect: success
2015-12-19T00:27:08.945Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7601.1oUnQA==
---- round done--------
startWithNextDevice
,2015-12-19 01:27:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:27:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:27:32.434 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:28:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:28:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:28:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:28:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:28:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:28:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:28:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:28:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:29:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:29:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:29:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:29:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:29:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:29:32.435 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:29:32.435 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:29:32.436 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,appEnteredForeground wasn't registered
,2015-12-19 01:30:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:30:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:30:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:30:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,appEnteringBackground wasn't registered
,2015-12-19 01:30:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:30:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:30:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:30:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:31:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:31:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:31:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:31:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:31:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:31:32.434 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:31:32.435 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:31:32.435 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:32:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:32:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:32:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:32:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:32:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:32:32.433 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:32:32.433 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:32:32.434 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:33:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:33:02.433 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:33:02.433 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:33:02.435 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:33:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:33:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:33:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:33:32.432 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:34:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:34:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:34:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:34:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:34:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:34:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:34:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:34:32.433 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:35:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:35:02.433 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:35:02.433 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:35:02.434 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:35:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:35:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:35:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:35:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:36:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:36:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:36:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:36:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:36:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:36:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:36:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:36:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:37:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:37:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:37:32.428 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:37:32.428 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:37:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:38:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:38:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:38:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:38:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:38:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:38:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:38:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:38:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:39:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:39:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:39:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:39:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:39:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:39:32.427 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:39:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:39:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:40:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:40:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:40:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:40:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:40:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:40:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:41:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:41:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:41:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:41:02.433 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:41:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:41:32.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:41:32.433 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:41:32.433 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:42:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:42:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:42:32.427 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:42:32.428 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:42:32.429 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:43:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:43:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:43:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:43:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:43:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:43:32.428 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:43:32.428 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:43:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,timeout now
weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T00:43:37.178Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 01:44:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:44:02.429 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:44:02.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:44:02.430 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:44:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:44:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:44:32.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:44:32.432 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:45:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:45:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:45:02.432 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:45:32.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:45:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:45:32.430 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:46:02.404 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:46:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:02.431 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:46:02.431 ThaliTest[493:426900] client: foun,d peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:46:32.404 ThaliTest[493:426900] multipeer session: restart
,teardown
,testSendData stopped
,2015-12-19 01:46:57.296 ThaliTest[493:427148] jxcore: stopBroadcasting
,2015-12-19 01:46:57.297 ThaliTest[493:427148] THEMultipeerSession stopping peer
2015-12-19 01:46:57.298 ThaliTest[493:427148] multipeer session: stop timer
,2015-12-19 01:46:57.299 ThaliTest[493:427148] server session: disconnect
2015-12-19 01:46:57.300 ThaliTest[493:427148] server session: stateChange:2->0 Apple-Iphone6-1_PT3810
,2015-12-19 01:46:57.309 ThaliTest[493:427148] server session: disconnect
2015-12-19 01:46:57.309 ThaliTest[493:427148] server session: stateChange:2->0 Apple-Iphone5-1_PT7806
,2015-12-19 01:46:57.318 ThaliTest[493:427148] server session: disconnect
2015-12-19 01:46:57.318 ThaliTest[493:427148] server session: stateChange:2->0 Apple-Iphone5s-1_PT7601
,2015-12-19 01:46:57.396 ThaliTest[493:427148] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-19T00:46:57.413Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:57.414Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:57.416Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:57.416Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-19 01:46:57.464 ThaliTest[493:427148] jxcore: startBroadcasting
,2015-12-19 01:46:57.467 ThaliTest[493:427148] server: starting Apple-IpadAir2-1_PT6779.Eyppcg==
,2015-12-19 01:46:57.469 ThaliTest[493:427148] multipeer session: start timer: 0x19542260
2015-12-19 01:46:57.470 ThaliTest[493:427148] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6779
2015-12-19 01:46:57.470 ThaliTest[493:427148] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-19 01:46:58.435 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":true}]
2015-12-19 01:46:58.438 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
Found peer : Apple-Iphone5s-1_PT7601.1oUnQA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-19 01:46:58.893 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:47:27.471 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:47:27.479 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:47:27.479 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:47:27.480 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:47:57.471 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:47:57.480 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:47:57.480 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:47:57.480 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:48:27.471 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:48:27.479 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:48:27.479 ThaliTest[493:426900] client: found peer: Apple-Iphone5-1_PT7806.jHAIjw==
2015-12-19 01:48:27.479 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:48:57.471 ThaliTest[493:426900] multipeer session: restart
,2015-12-19 01:48:57.479 ThaliTest[493:426900] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:48:57.479 ThaliTest[493:426900] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:48:57.479 ThaliTest[493:426900] client: fou,nd peer: Apple-Iphone5-1_PT7806.jHAIjw==

```
