#### Test 50650278161ce7f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E2F613E4-C4FA-43A2-94BF-CD6963B97523/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E2F613E4-C4FA-43A2-94BF-CD6963B97523/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278161ce7f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BECBAB7-AA72-430C-AA0D-5BCC782B49FE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60633"
,(lldb)     command script import "/tmp/E2F613E4-C4FA-43A2-94BF-CD6963B97523/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 02:30:01.430 ThaliTest[508:435983] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/03FA2E25-12CB-40B6-BEA6-01F89CE69943/Library/Cookies/Cookies.binarycookies
,2015-12-19 02:30:01.813 ThaliTest[508:435983] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 02:30:01.814 ThaliTest[508:435983] Multi-tasking -> Device: YES, App: YES
,2015-12-19 02:30:01.823 ThaliTest[508:435983] Unlimited access to network resources
,2015-12-19 02:30:01.831 ThaliTest[508:435983] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 02:30:10.719 ThaliTest[508:435983] Resetting plugins due to page load.
,2015-12-19 02:30:14.471 ThaliTest[508:435983] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BECBAB7-AA72-430C-AA0D-5BCC782B49FE/ThaliTest.app/www/index.html
,2015-12-19 02:30:14.625 ThaliTest[508:435983] JXcore Cordova plugin initializing
,2015-12-19 02:30:14.625 ThaliTest[508:436208] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-19 02:30:15.621 ThaliTest[508:435983] THREAD WARNING: ['JXcore'] took '70.095215' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53385
,2015-12-19 02:35:02.051 ThaliTest[508:436208] jxcore: startBroadcasting
,2015-12-19 02:35:02.066 ThaliTest[508:436208] server: starting Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:35:02.067 ThaliTest[508:436208] multipeer session: start timer: 0x177c89f0
,2015-12-19 02:35:02.070 ThaliTest[508:436208] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4132
,2015-12-19 02:35:02.071 ThaliTest[508:436208] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-19T01:35:02.087Z SendDataTCPServer.js: TCP/IP server is bound to port: 53385
,2015-12-19 02:35:03.561 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19T01:35:03.567Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19T01:35:03.568Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19T01:35:03.568Z SendDataConnector.js: do connect now
,2015-12-19 02:35:03.569 ThaliTest[508:436208] jxcore: connect Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:03.570 ThaliTest[508:436208] client session: connect
,2015-12-19 02:35:03.571 ThaliTest[508:436208] client session: stateChange:0->1 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:03.601 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9396.+XAJIw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:03.735 ThaliTest[508:435983] multipeer session: reset timer
2015-12-19 02:35:03.735 ThaliTest[508:435983] multipeer session: stop timer
,2015-12-19 02:35:03.736 ThaliTest[508:435983] multipeer session: start timer: 0x177c89f0
,2015-12-19 02:35:03.736 ThaliTest[508:435983] server session: connect
2015-12-19 02:35:03.737 ThaliTest[508:435983] server session: stateChange:0->1 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:03.744 ThaliTest[508:435983] server: accepting invitation Apple-Iphone6-1_PT3166
,2015-12-19 02:35:04.021 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3166.5e8qRw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 02:35:06.361 ThaliTest[508:436793] server session: connected
2015-12-19 02:35:06.361 ThaliTest[508:436793] server session: stateChange:1->2 Apple-Iphone6-1_PT3166
,2015-12-19 02:35:06.403 ThaliTest[508:435983] server relay: connected (to port: 53385)
,2015-12-19T01:35:06.413Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 02:35:06.690 ThaliTest[508:436792] client session: connected
,2015-12-19 02:35:06.690 ThaliTest[508:436792] client session: stateChange:1->2 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:06.709 ThaliTest[508:436792] client session: fireConnectCallback: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:35:06.709 ThaliTest[508:436792] jxcore: connect: success
,2015-12-19T01:35:06.711Z SendDataConnector.js: CLIENT connected to 53389, error: null
,2015-12-19T01:35:06.711Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:06.714 ThaliTest[508:435983] client: relay established
2015-12-19 02:35:06.714 ThaliTest[508:435983] client: new accepted socket: 0x19671ea0
,2015-12-19T01:35:06.730Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:07.029Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:07.133 ThaliTest[508:436798] server session: not connected Apple-Iphone6-1_PT3166
,2015-12-19T01:35:07.217Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T01:35:07.217Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-19T01:35:07.218Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:07.218Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:07.219 ThaliTest[508:436208] jxcore: disconnect
,2015-12-19 02:35:07.219 ThaliTest[508:436208] client session: disconnectFromPeer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:07.219 ThaliTest[508:436208] client session: disconnect
,2015-12-19 02:35:07.219 ThaliTest[508:436208] client session: stateChange:2->0 Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:07.223 ThaliTest[508:436208] jxcore: disconnect: success
2015-12-19T01:35:07.223Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9897.wDmYaQ==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:07.224Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19T01:35:07.224Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19T01:35:07.224Z SendDataConnector.js: do connect now
2015-12-19 02:35:07.224 ThaliTest[508:436208] jxcore: connect Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:07.224 ThaliTest[508:436208] client session: connect
2015-12-19 02:35:07.224 ThaliTest[508:436208] client session: stateChange:0->1 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:07.738 ThaliTest[508:435983] multipeer session: reset timer
2015-12-19 02:35:07.738 ThaliTest[508:435983] multipeer session: stop timer
2015-12-19 02:35:07.739 ThaliTest[508:435983] multipeer session: start timer: 0x177c89f0
,2015-12-19 02:35:07.739 ThaliTest[508:435983] server session: connect
2015-12-19 02:35:07.739 ThaliTest[508:435983] server session: stateChange:0->1 Apple-Iphone5-1_PT9897
,2015-12-19 02:35:07.745 ThaliTest[508:435983] server: accepting invitation Apple-Iphone5-1_PT9897
,2015-12-19 02:35:10.362 ThaliTest[508:436793] server session: connected
2015-12-19 02:35:10.362 ThaliTest[508:436793] server session: stateChange:1->2 Apple-Iphone5-1_PT9897
,2015-12-19 02:35:10.377 ThaliTest[508:435983] server relay: connected (to port: 53385)
,2015-12-19T01:35:10.386Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 02:35:10.772 ThaliTest[508:435983] multipeer session: reset timer
,2015-12-19 02:35:10.773 ThaliTest[508:435983] multipeer session: stop timer
,2015-12-19 02:35:10.773 ThaliTest[508:435983] multipeer session: start timer: 0x177c89f0
,2015-12-19 02:35:10.773 ThaliTest[508:435983] server session: connect
2015-12-19 02:35:10.774 ThaliTest[508:435983] server session: stateChange:0->1 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:10.780 ThaliTest[508:435983] server: accepting invitation Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:11.076 ThaliTest[508:436850] client session: connected
2015-12-19 02:35:11.077 ThaliTest[508:436850] client session: stateChange:1->2 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:11.212 ThaliTest[508:436798] client session: fireConnectCallback: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:11.212 ThaliTest[508:436798] jxcore: connect: success
,2015-12-19T01:35:11.213Z SendDataConnector.js: CLIENT connected to 53393, error: null
,2015-12-19T01:35:11.214Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:11.216 ThaliTest[508:435983] client: relay established
2015-12-19 02:35:11.217 ThaliTest[508:435983] client: new accepted socket: 0x1966c230
,2015-12-19T01:35:11.230Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:11.467Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19T01:35:11.529Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T01:35:11.542Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-19T01:35:11.591Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-19 02:35:11.653 ThaliTest[508:436853] server session: not connected Apple-Iphone5-1_PT9897
,2015-12-19T01:35:11.653Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:11.653Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-19T01:35:11.654Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T01:35:11.654Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-19 02:35:11.654 ThaliTest[508:436208] jxcore: disconnect
2015-12-19 02:35:11.654 ThaliTest[508:436208] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:11.654 ThaliTest[508:436208] client session: disconnect
,2015-12-19 02:35:11.655 ThaliTest[508:436208] client session: stateChange:2->0 Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:35:11.657 ThaliTest[508:436208] jxcore: disconnect: success
2015-12-19T01:35:11.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9396.+XAJIw==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19T01:35:11.658Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:11.658Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19T01:35:11.658Z SendDataConnector.js: do connect now
2015-12-19 02:35:11.658 ThaliTest[508:436208] jxcore: connect Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:11.659 ThaliTest[508:436208] client session: connect
2015-12-19 02:35:11.659 ThaliTest[508:436208] client session: stateChange:0->1 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:13.806 ThaliTest[508:436793] server session: connected
2015-12-19 02:35:13.806 ThaliTest[508:436793] server session: stateChange:1->2 Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:13.851 ThaliTest[508:435983] server relay: connected (to port: 53385)
,2015-12-19T01:35:13.856Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T01:35:14.133Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-19T01:35:14.159Z SendDataTCPServer.js: TCP/IP server has received 25570 bytes of data
,2015-12-19T01:35:14.175Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-19T01:35:14.190Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 02:35:14.269 ThaliTest[508:436853] server session: not connected Apple-Iphone5s-1_PT9396
,2015-12-19 02:35:14.396 ThaliTest[508:436853] client session: connected
,2015-12-19 02:35:14.397 ThaliTest[508:436853] client session: stateChange:1->2 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:14.416 ThaliTest[508:436798] client session: fireConnectCallback: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:35:14.417 ThaliTest[508:436798] jxcore: connect: success
,2015-12-19T01:35:14.418Z SendDataConnector.js: CLIENT connected to 53397, error: null
2015-12-19T01:35:14.419Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 02:35:14.421 ThaliTest[508:435983] client: relay established
2015-12-19 02:35:14.421 ThaliTest[508:435983] client: new accepted socket: 0x19673bf0
,2015-12-19T01:35:14.435Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T01:35:14.687Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-19T01:35:14.738Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T01:35:14.738Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-19T01:35:14.739Z SendDataConnector.js: CLIENT Stop now
2015-12-19T01:35:14.739Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 02:35:14.739 ThaliTest[508:436208] jxcore: disconnect
,2015-12-19 02:35:14.739 ThaliTest[508:436208] client session: disconnectFromPeer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:14.740 ThaliTest[508:436208] client session: disconnect
,2015-12-19 02:35:14.740 ThaliTest[508:436208] client session: stateChange:2->0 Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:35:14.742 ThaliTest[508:436208] jxcore: disconnect: success
2015-12-19T01:35:14.743Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3166.5e8qRw==
,---- round done--------
startWithNextDevice
,2015-12-19 02:35:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:35:40.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:35:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:35:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:36:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:36:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:36:10.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:36:10.805 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:36:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:36:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:36:41.441 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:36:41.443 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:37:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:37:10.799 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:37:10.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:37:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:37:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:37:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:37:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:37:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:38:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:38:10.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:38:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:38:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:38:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:38:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:38:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:38:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:39:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:39:10.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:39:10.804 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:39:10.805 ThaliTest[508:435983] client: foun,d peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:39:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:39:40.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:39:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:39:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:40:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:40:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:40:10.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:40:10.807 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:40:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:40:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:40:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:40:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:41:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:41:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:41:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:41:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:41:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:41:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:41:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:41:40.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:42:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:42:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:42:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:42:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:42:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:42:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:42:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:42:40.805 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:43:10.774 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:43:10.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:43:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:43:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:43:40.774 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:43:40.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:43:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:43:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:44:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:44:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:44:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:44:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:44:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:44:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:44:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:44:40.804 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:45:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:45:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:45:10.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:45:10.805 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:45:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:45:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:45:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:45:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:46:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:46:10.805 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:46:10.805 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:46:10.806 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:46:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:46:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:46:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:46:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:47:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:47:10.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:47:10.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:47:10.801 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:47:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:47:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:47:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:47:40.803 ThaliTest[508:435983] client: fou,nd peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:48:10.774 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:48:10.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:48:10.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:48:10.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:48:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:48:40.801 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:48:40.802 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:48:40.803 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:49:10.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:49:11.550 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:49:11.550 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:49:11.551 ThaliTest[508:435983] client: foun,d peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:49:40.775 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:49:40.800 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:49:40.804 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:49:40.804 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:50:10.761 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:50:10.792 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:50:10.794 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:50:10.794 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:50:40.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:51:10.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:51:10.783 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:51:10.784 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
,2015-12-19 02:51:10.785 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:51:40.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:51:40.785 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:51:40.785 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:51:40.785 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T01:51:42.090Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 02:52:10.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:52:10.784 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:52:10.785 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:52:10.785 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:52:40.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:52:40.786 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:52:40.786 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:52:40.789 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:53:10.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:53:10.786 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:53:10.787 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:53:10.787 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:53:40.760 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:53:40.787 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:53:40.787 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:53:40.787 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:54:10.759 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:54:10.784 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:54:10.784 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:54:11.376 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:54:40.759 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:54:40.787 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:54:40.787 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:54:40.788 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,teardown
,testSendData stopped
,2015-12-19 02:55:01.908 ThaliTest[508:436208] jxcore: stopBroadcasting
,2015-12-19 02:55:01.908 ThaliTest[508:436208] THEMultipeerSession stopping peer
,2015-12-19 02:55:01.909 ThaliTest[508:436208] multipeer session: stop timer
,2015-12-19 02:55:01.912 ThaliTest[508:436208] server session: disconnect
2015-12-19 02:55:01.912 ThaliTest[508:436208] server session: stateChange:2->0 Apple-Iphone6-1_PT3166
,2015-12-19 02:55:01.923 ThaliTest[508:436208] server session: disconnect
2015-12-19 02:55:01.924 ThaliTest[508:436208] server session: stateChange:2->0 Apple-Iphone5-1_PT9897
,2015-12-19 02:55:01.933 ThaliTest[508:436208] server session: disconnect
2015-12-19 02:55:01.933 ThaliTest[508:436208] server session: stateChange:2->0 Apple-Iphone5s-1_PT9396
,2015-12-19 02:55:01.938 ThaliTest[508:436208] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-19T01:55:01.957Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.960Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.961Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T01:55:01.962Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-19 02:55:01.993 ThaliTest[508:436208] jxcore: startBroadcasting
,2015-12-19 02:55:01.996 ThaliTest[508:436208] server: starting Apple-IpadAir2-1_PT4132.TB3Mww==
,2015-12-19 02:55:01.997 ThaliTest[508:436208] multipeer session: start timer: 0x177db0c0
2015-12-19 02:55:01.998 ThaliTest[508:436208] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT4132
2015-12-19 02:55:01.999 ThaliTest[508:436208] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-19 02:55:02.017 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:55:02.017 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:55:02.018 ThaliTest[508:435983] client: found peer: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:55:02.019 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.5e8qRw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9897.wDmYaQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT9897.wDmYaQ==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-19 02:55:03.031 ThaliTest[508:435983] client: lost peer: Apple-IpadAir2-1_PT4132.HrCdVA==
2015-12-19 02:55:03.031 ThaliTest[508:435983] client session: onPeerLost: Apple-IpadAir2-1_PT4132.HrCdVA==
,2015-12-19 02:55:03.695 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:55:05.746 ThaliTest[508:435983] client: lost peer: Apple-Iphone6-1_PT3166.5e8qRw==
2015-12-19 02:55:05.747 ThaliTest[508:435983] client session: onPeerLost: Apple-Iphone6-1_PT3166.5e8qRw==
,2015-12-19 02:55:31.999 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:55:32.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:55:32.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:55:32.026 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:56:01.999 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:56:02.025 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:56:02.025 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
2015-12-19 02:56:02.025 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
,2015-12-19 02:56:31.999 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:56:32.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:56:32.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:56:32.027 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==
,2015-12-19 02:57:01.999 ThaliTest[508:435983] multipeer session: restart
,2015-12-19 02:57:02.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5-1_PT9897.wDmYaQ==
2015-12-19 02:57:02.026 ThaliTest[508:435983] client: found peer: Apple-Iphone5s-1_PT9396.+XAJIw==
2015-12-19 02:57:02.026 ThaliTest[508:435983] client: found peer: Apple-Iphone6-1_PT3166.6hHfhA==

```
