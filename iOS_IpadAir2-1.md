#### Test 506502785b2d2b2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DDACD31E-5D21-499E-A9CE-569BDFFE9683/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DDACD31E-5D21-499E-A9CE-569BDFFE9683/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69D107DF-064F-42C6-98CB-A4DF2FE28346/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60898"
,(lldb)     command script import "/tmp/DDACD31E-5D21-499E-A9CE-569BDFFE9683/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-20 03:39:43.672 ThaliTest[558:573095] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1A77481-F2BC-4DC0-ABEF-C7ABAAC14F55/Library/Cookies/Cookies.binarycookies
,2015-12-20 03:39:44.074 ThaliTest[558:573095] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-20 03:39:44.075 ThaliTest[558:573095] Multi-tasking -> Device: YES, App: YES
,2015-12-20 03:39:44.084 ThaliTest[558:573095] Unlimited access to network resources
,2015-12-20 03:39:44.093 ThaliTest[558:573095] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-20 03:39:53.251 ThaliTest[558:573095] Resetting plugins due to page load.
,2015-12-20 03:39:56.502 ThaliTest[558:573095] Finished load of: file:///var/mobile/Containers/Bundle/Application/69D107DF-064F-42C6-98CB-A4DF2FE28346/ThaliTest.app/www/index.html
,2015-12-20 03:39:56.664 ThaliTest[558:573095] JXcore Cordova plugin initializing
,2015-12-20 03:39:56.665 ThaliTest[558:573363] JXcore instance initializing
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
,2015-12-20 03:39:57.657 ThaliTest[558:573095] THREAD WARNING: ['JXcore'] took '71.019775' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 54100
,2015-12-20 03:44:45.471 ThaliTest[558:573363] jxcore: startBroadcasting
,2015-12-20 03:44:45.487 ThaliTest[558:573363] server: starting Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:45.488 ThaliTest[558:573363] multipeer session: start timer: 0x157d0ad0
2015-12-20 03:44:45.490 ThaliTest[558:573363] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:45.491 ThaliTest[558:573363] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-20T02:44:45.500Z SendDataTCPServer.js: TCP/IP server is bound to port: 54100
,2015-12-20 03:44:47.097 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:47.102Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:47.103Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:47.103Z SendDataConnector.js: do connect now
,2015-12-20 03:44:47.104 ThaliTest[558:573363] jxcore: connect Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:47.105 ThaliTest[558:573363] client session: connect
,2015-12-20 03:44:47.105 ThaliTest[558:573363] client session: stateChange:0->1 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:47.431 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-20 03:44:48.225 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-20 03:44:50.094 ThaliTest[558:573882] client session: connected
2015-12-20 03:44:50.094 ThaliTest[558:573882] client session: stateChange:1->2 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:50.102 ThaliTest[558:573868] client session: fireConnectCallback: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:50.102 ThaliTest[558:573868] jxcore: connect: success
,2015-12-20T02:44:50.104Z SendDataConnector.js: CLIENT connected to 54103, error: null
2015-12-20T02:44:50.105Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:50.107 ThaliTest[558:573095] client: relay established
2015-12-20 03:44:50.108 ThaliTest[558:573095] client: new accepted socket: 0x1740c400
,2015-12-20T02:44:50.124Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20 03:44:50.435 ThaliTest[558:573095] multipeer session: reset timer
2015-12-20 03:44:50.435 ThaliTest[558:573095] multipeer session: stop timer
2015-12-20 03:44:50.435 ThaliTest[558:573095] multipeer session: start timer: 0x157d0ad0
2015-12-20 03:44:50.435 ThaliTest[558:573095] server session: connect
2015-12-20 03:44:50.435 ThaliTest[558:573095] server session: stateChange:0->1 Apple-Iphone6-1_PT27
,2015-12-20 03:44:50.437 ThaliTest[558:573095] server: accepting invitation Apple-Iphone6-1_PT27
,2015-12-20T02:44:50.692Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-20 03:44:50.798 ThaliTest[558:573095] multipeer session: reset timer
,2015-12-20 03:44:50.798 ThaliTest[558:573095] multipeer session: stop timer
2015-12-20 03:44:50.798 ThaliTest[558:573095] multipeer session: start timer: 0x157d0ad0
2015-12-20 03:44:50.798 ThaliTest[558:573095] server session: connect
2015-12-20 03:44:50.798 ThaliTest[558:573095] server session: stateChange:0->1 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:50.801 ThaliTest[558:573095] server: accepting invitation Apple-Iphone5-1_PT1975
,2015-12-20T02:44:51.153Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:51.154Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:51.155Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:51.155Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:51.157 ThaliTest[558:573363] jxcore: disconnect
2015-12-20 03:44:51.157 ThaliTest[558:573363] client session: disconnectFromPeer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:51.157 ThaliTest[558:573363] client session: disconnect
2015-12-20 03:44:51.158 ThaliTest[558:573363] client session: stateChange:2->0 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:51.164 ThaliTest[558:573363] jxcore: disconnect: success
2015-12-20T02:44:51.165Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT27.Ee1r/w==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20T02:44:51.168Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20T02:44:51.168Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20T02:44:51.168Z SendDataConnector.js: do connect now
2015-12-20 03:44:51.169 ThaliTest[558:573363] jxcore: connect Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:51.169 ThaliTest[558:573363] client s,ession: connect
2015-12-20 03:44:51.169 ThaliTest[558:573363] client session: stateChange:0->1 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:53.209 ThaliTest[558:573882] server session: connected
,2015-12-20 03:44:53.210 ThaliTest[558:573882] server session: stateChange:1->2 Apple-Iphone6-1_PT27
,2015-12-20 03:44:53.217 ThaliTest[558:573095] server relay: connected (to port: 54100)
2015-12-20T02:44:53.219Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:53.519Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-20T02:44:53.532Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-20T02:44:53.549Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-20T02:44:53.590Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-20T02:44:53.606Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-20T02:44:53.623Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:53.697 ThaliTest[558:573868] server session: not connected Apple-Iphone6-1_PT27
,2015-12-20 03:44:53.706 ThaliTest[558:573927] server session: connected
2015-12-20 03:44:53.706 ThaliTest[558:573927] server session: stateChange:1->2 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:53.720 ThaliTest[558:573095] server relay: connected (to port: 54100)
,2015-12-20T02:44:53.733Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:54.260Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-12-20T02:44:54.279Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-20T02:44:54.308Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:54.375 ThaliTest[558:573868] server session: not connected Apple-Iphone5-1_PT1975
,2015-12-20 03:44:54.384 ThaliTest[558:573868] client session: connected
,2015-12-20 03:44:54.384 ThaliTest[558:573868] client session: stateChange:1->2 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:54.439 ThaliTest[558:573868] client session: fireConnectCallback: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:54.440 ThaliTest[558:573868] jxcore: connect: success
,2015-12-20T02:44:54.441Z SendDataConnector.js: CLIENT connected to 54108, error: null
,2015-12-20T02:44:54.441Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:54.444 ThaliTest[558:573095] client: relay established
2015-12-20 03:44:54.444 ThaliTest[558:573095] client: new accepted socket: 0x1759f8f0
,2015-12-20T02:44:54.458Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:54.765Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-20T02:44:54.778Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-20T02:44:54.864Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:54.864Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-20T02:44:54.864Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:54.865Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-20 03:44:54.865 ThaliTest[558:573363] jxcore: disconnect
,2015-12-20 03:44:54.865 ThaliTest[558:573363] client session: disconnectFromPeer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:54.865 ThaliTest[558:573363] client session: disconnect
,2015-12-20 03:44:54.865 ThaliTest[558:573363] client session: stateChange:2->0 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:54.869 ThaliTest[558:573363] jxcore: disconnect: success
2015-12-20T02:44:54.869Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1975.nu3zFw==
---- round done--------
startWithNextDevice
device[3]: Apple,-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:54.869Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:54.869Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:54.869Z SendDataConnector.js: do connect now
2015-12-20 03:44:54.869 ThaliTest[558:573363] jxcore: connect Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:54.870 ThaliTest[558:573363] client session: connect
2015-12-20 03:44:54.870 ThaliTest[558:573,363] client session: stateChange:0->1 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:57.917 ThaliTest[558:573095] multipeer session: reset timer
2015-12-20 03:44:57.917 ThaliTest[558:573095] multipeer session: stop timer
,2015-12-20 03:44:57.917 ThaliTest[558:573095] multipeer session: start timer: 0x157d0ad0
,2015-12-20 03:44:57.918 ThaliTest[558:573095] server session: connect
2015-12-20 03:44:57.918 ThaliTest[558:573095] server session: stateChange:0->1 Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:57.924 ThaliTest[558:573095] server: accepting invitation Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:58.179 ThaliTest[558:573868] client session: connected
,2015-12-20 03:44:58.179 ThaliTest[558:573868] client session: stateChange:1->2 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:58.182 ThaliTest[558:573868] client session: fireConnectCallback: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:58.183 ThaliTest[558:573868] jxcore: connect: success
2015-12-20T02:44:58.183Z SendDataConnector.js: CLIENT connected to 54111, error: null
,2015-12-20T02:44:58.183Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:58.185 ThaliTest[558:573095] client: relay established
2015-12-20 03:44:58.185 ThaliTest[558:573095] client: new accepted socket: 0x157e47e0
,2015-12-20T02:44:58.196Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:58.495Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-20T02:44:58.689Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-20T02:44:58.689Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-20T02:44:58.690Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:58.690Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:58.691 ThaliTest[558:573363] jxcore: disconnect
,2015-12-20 03:44:58.691 ThaliTest[558:573363] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:58.691 ThaliTest[558:573363] client session: disconnect
2015-12-20 03:44:58.691 ThaliTest[558:573363] client session: stateChange:2->0 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:58.756 ThaliTest[558:573363] jxcore: disconnect: success
2015-12-20T02:44:58.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
,---- round done--------
,startWithNextDevice
,2015-12-20 03:45:01.135 ThaliTest[558:573868] server session: connected
2015-12-20 03:45:01.135 ThaliTest[558:573868] server session: stateChange:1->2 Apple-Iphone5s-1_PT7946
,2015-12-20 03:45:01.152 ThaliTest[558:573095] server relay: connected (to port: 54100)
,2015-12-20T02:45:01.159Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:45:01.582Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-20T02:45:01.599Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-20T02:45:01.616Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:45:01.685 ThaliTest[558:573868] server session: not connected Apple-Iphone5s-1_PT7946
,2015-12-20 03:45:27.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:45:27.945 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:45:27.945 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:45:27.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:45:57.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:45:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:45:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:45:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:46:27.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:46:27.945 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:46:27.946 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:46:27.947 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:46:57.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:46:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:46:57.949 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:46:57.949 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:47:27.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:47:27.947 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:47:27.948 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:47:27.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:47:32.342 ThaliTest[558:573095] client: lost peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:47:32.342 ThaliTest[558:573095] client session: onPeerLost: Apple-Iphone5-1_PT1975.nu3zFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 03:47:32.454 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-20 03:47:57.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:47:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:47:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:47:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:48:27.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:48:27.950 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:48:27.950 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:27.951 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:48:57.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:48:57.947 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:57.947 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:48:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:49:27.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:49:27.946 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:49:28.012 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:49:28.013 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:49:31.311 ThaliTest[558:573095] client: lost peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:49:31.312 ThaliTest[558:573095] client session: onPeerLost: Apple-Iphone6-1_PT27.Ee1r/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 03:49:37.892 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-20 03:49:57.919 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:49:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:49:57.948 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:49:57.949 ThaliTest[558:573095] client: fou,nd peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:50:00.448 ThaliTest[558:573095] client: lost peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:50:00.448 ThaliTest[558:573095] client session: onPeerLost: Apple-Iphone5s-1_PT7946.2ECkqQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 03:50:12.585 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-20 03:50:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:50:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:50:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:50:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:50:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:50:57.930 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:50:57.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:50:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:51:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:51:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:51:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:51:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:51:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:51:57.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:51:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:51:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:52:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:52:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:52:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:52:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:52:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:52:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:52:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:52:57.934 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:53:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:53:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:53:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:53:28.063 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:53:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:53:57.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:53:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:53:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:54:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:54:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:54:27.933 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:54:27.934 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:54:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:54:57.934 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:54:57.934 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:54:57.935 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:55:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:55:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:55:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:55:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:55:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:55:57.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:55:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:55:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:56:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:56:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:56:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:56:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:56:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:56:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:57:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:57:27.933 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:57:27.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:57:27.934 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:57:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:57:57.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:57:57.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:57:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:58:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:58:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:58:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:58:27.934 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:58:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:58:57.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:58:58.823 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:58:58.824 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:59:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:59:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:59:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:59:27.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:59:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 03:59:57.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:59:57.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:59:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:00:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:00:27.935 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:00:27.935 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:27.937 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:00:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:00:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:00:57.934 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-20T03:01:25.501Z SendDataConnector.js: CLIENT Stop now
,2015-12-20 04:01:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:01:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:27.932 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:01:27.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:01:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:01:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:01:57.933 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:02:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:02:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:02:28.183 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:02:28.184 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:02:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:03:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:03:27.930 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:03:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:03:57.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:03:57.928 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:03:57.929 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:03:57.929 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:04:27.904 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:04:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:04:27.931 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:04:27.932 ThaliTest[558:573095] client: found ,peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,teardown
,testSendData stopped
,2015-12-20 04:04:46.293 ThaliTest[558:573363] jxcore: stopBroadcasting
,2015-12-20 04:04:46.294 ThaliTest[558:573363] THEMultipeerSession stopping peer
,2015-12-20 04:04:46.294 ThaliTest[558:573363] multipeer session: stop timer
,2015-12-20 04:04:46.296 ThaliTest[558:573363] server session: disconnect
2015-12-20 04:04:46.296 ThaliTest[558:573363] server session: stateChange:2->0 Apple-Iphone5s-1_PT7946
,2015-12-20 04:04:46.304 ThaliTest[558:573363] server session: disconnect
2015-12-20 04:04:46.305 ThaliTest[558:573363] server session: stateChange:2->0 Apple-Iphone6-1_PT27
,2015-12-20 04:04:46.320 ThaliTest[558:573363] server session: disconnect
,2015-12-20 04:04:46.321 ThaliTest[558:573363] server session: stateChange:2->0 Apple-Iphone5-1_PT1975
,2015-12-20 04:04:46.326 ThaliTest[558:573363] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-20T03:04:46.346Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-20T03:04:46.347Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-20T03:04:46.349Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-20T03:04:46.350Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-20 04:04:46.384 ThaliTest[558:573363] jxcore: startBroadcasting
,2015-12-20 04:04:46.389 ThaliTest[558:573363] server: starting Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:04:46.396 ThaliTest[558:573363] multipeer session: start timer: 0x1759f440
2015-12-20 04:04:46.402 ThaliTest[558:573363] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT5083
,2015-12-20 04:04:46.403 ThaliTest[558:573363] jxcore: startBroadcasting: success
,2015-12-20 04:04:46.409 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
StartBroadcasting started ok
,2015-12-20 04:04:46.410 ThaliTest[558:573095] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:46.411 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:04:46.411 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT27.Ee1r/w==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-20 04:04:47.426 ThaliTest[558:573095] client: lost peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:47.426 ThaliTest[558:573095] client session: onPeerLost: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:04:47.663 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
,2015-12-20 04:04:52.273 ThaliTest[558:573095] client: lost peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:04:52.273 ThaliTest[558:573095] client session: onPeerLost: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:05:16.408 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:05:16.433 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:05:16.433 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:05:16.433 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
,2015-12-20 04:05:46.408 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:05:46.433 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:05:46.434 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:05:46.434 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:06:16.408 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:06:16.435 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:16.435 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:06:16.435 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:06:46.408 ThaliTest[558:573095] multipeer session: restart
,2015-12-20 04:06:46.434 ThaliTest[558:573095] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:46.435 ThaliTest[558:573095] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:06:46.435 ThaliTest[558:573095] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==

```
