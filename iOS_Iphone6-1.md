#### Test 506502785b2d2b2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/17C47253-FD90-4C2D-AD0C-C785DC73DBA0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/17C47253-FD90-4C2D-AD0C-C785DC73DBA0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7ABDC76-B106-48B6-B274-5B2421BF4881/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60900"
,(lldb)     command script import "/tmp/17C47253-FD90-4C2D-AD0C-C785DC73DBA0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-20 03:39:42.770 ThaliTest[567:558474] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B8CB6B8-A605-4356-A554-99424BBE381F/Library/Cookies/Cookies.binarycookies
,2015-12-20 03:39:43.154 ThaliTest[567:558474] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-20 03:39:43.155 ThaliTest[567:558474] Multi-tasking -> Device: YES, App: YES
,2015-12-20 03:39:43.165 ThaliTest[567:558474] Unlimited access to network resources
,2015-12-20 03:39:43.176 ThaliTest[567:558474] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-20 03:39:52.248 ThaliTest[567:558474] Resetting plugins due to page load.
,2015-12-20 03:39:55.976 ThaliTest[567:558474] Finished load of: file:///var/mobile/Containers/Bundle/Application/F7ABDC76-B106-48B6-B274-5B2421BF4881/ThaliTest.app/www/index.html
,2015-12-20 03:39:56.158 ThaliTest[567:558474] JXcore Cordova plugin initializing
2015-12-20 03:39:56.160 ThaliTest[567:558695] JXcore instance initializing
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
,2015-12-20 03:39:57.242 ThaliTest[567:558474] THREAD WARNING: ['JXcore'] took '80.923828' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 54421
,2015-12-20 03:44:42.917 ThaliTest[567:558695] jxcore: startBroadcasting
,2015-12-20 03:44:42.932 ThaliTest[567:558695] server: starting Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:42.934 ThaliTest[567:558695] multipeer session: start timer: 0x18283ef0
2015-12-20 03:44:42.934 ThaliTest[567:558695] THEMultipeerSession initia,lized peer Apple-Iphone6-1_PT27
2015-12-20 03:44:42.935 ThaliTest[567:558695] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-20T02:44:42.941Z SendDataTCPServer.js: TCP/IP server is bound to port: 54421
,2015-12-20 03:44:44.041 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
startWithNextDevice
,device[1]: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20T02:44:44.045Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20T02:44:44.046Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20T02:44:44.047Z SendDataConnector.js: do connect now
,2015-12-20 03:44:44.048 ThaliTest[567:558695] jxcore: connect Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:44.049 ThaliTest[567:558695] client session: connect
2015-12-20 03:44:44.049 ThaliTest[567:558695] client session: stateChange:0->1 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:44.121 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.BRI7qQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-20 03:44:44.245 ThaliTest[567:558474] multipeer session: reset timer
2015-12-20 03:44:44.246 ThaliTest[567:558474] multipeer session: stop timer
2015-12-20 03:44:44.246 ThaliTest[567:558474] multipeer session: start timer: 0x18283ef0
2015-12-20 03:44:44.246 ThaliTest[567:558474] server session: connect
2015-12-20 03:44:44.247 ThaliTest[567:558474] server session: stateChange:0->1 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:44.256 ThaliTest[567:558474] server: accepting invitation Apple-Iphone5-1_PT1975
,2015-12-20 03:44:44.903 ThaliTest[567:558474] multipeer session: reset timer
2015-12-20 03:44:44.903 ThaliTest[567:558474] multipeer session: stop timer
2015-12-20 03:44:44.904 ThaliTest[567:558474] multipeer session: start timer: 0x18283ef0
2015-12-20 ,03:44:44.904 ThaliTest[567:558474] server session: connect
2015-12-20 03:44:44.904 ThaliTest[567:558474] server session: stateChange:0->1 Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:44.914 ThaliTest[567:558474] server: accepting invitation Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:45.771 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-20 03:44:46.867 ThaliTest[567:559189] client session: connected
2015-12-20 03:44:46.867 ThaliTest[567:559189] client session: stateChange:1->2 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:46.909 ThaliTest[567:559187] client session: fireConnectCallback: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:46.909 ThaliTest[567:559187] jxcore: connect: success
2015-12-20T02:44:46.911Z SendDataConnector.js: CLIENT connected to 54424, error: null
2015-12-20T02:44:46.912Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:46.916 ThaliTest[567:558474] client: relay established
2015-12-20 03:44:46.916 ThaliTest[567:558474] client: new accepted socket: 0x182997e0
,2015-12-20T02:44:46.932Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20 03:44:47.130 ThaliTest[567:559189] server session: connected
2015-12-20 03:44:47.130 ThaliTest[567:559189] server session: stateChange:1->2 Apple-Iphone5-1_PT1975
,2015-12-20 03:44:47.144 ThaliTest[567:558474] server relay: connected (to port: 54421)
,2015-12-20T02:44:47.228Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20 03:44:47.567 ThaliTest[567:559188] server session: connected
2015-12-20 03:44:47.567 ThaliTest[567:559188] server session: stateChange:1->2 Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:47.582 ThaliTest[567:558474] server relay: connected (to port: 54421)
,2015-12-20T02:44:47.586Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:47.714Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-20T02:44:47.728Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-20T02:44:47.732Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:47.733Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-20T02:44:47.734Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:47.735Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:47.737 ThaliTest[567:558695] jxcore: disconnect
2015-12-20 03:44:47.738 ThaliTest[567:558695] client session: disconnectFromPeer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:44:47.738 ThaliTest[567:558695] client session: disconnect
2,015-12-20 03:44:47.738 ThaliTest[567:558695] client session: stateChange:2->0 Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:47.754 ThaliTest[567:558695] jxcore: disconnect: success
2015-12-20T02:44:47.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1975.nu3zFw==
---- round done--------
startWithNextDevice
device[2]: Apple,-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:44:47.758Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:44:47.758Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20T02:4,4:47.759Z SendDataConnector.js: do connect now
2015-12-20 03:44:47.759 ThaliTest[567:558695] jxcore: connect Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:47.760 ThaliTest[567:558695] client session: connect
,2015-12-20 03:44:47.760 ThaliTest[567:558695] client session: stateChange:0->1 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20T02:44:47.825Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:47.936 ThaliTest[567:559189] server session: not connected Apple-Iphone5-1_PT1975
,2015-12-20T02:44:47.945Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-20T02:44:47.957Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-20T02:44:48.155Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-20T02:44:48.564Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-20T02:44:48.579Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:48.668 ThaliTest[567:559199] server session: not connected Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:50.282 ThaliTest[567:558474] multipeer session: reset timer
2015-12-20 03:44:50.282 ThaliTest[567:558474] multipeer session: stop timer
2015-12-20 03:44:50.283 ThaliTest[567:558474] multipeer session: start timer: 0x18283ef0
,2015-12-20 03:44:50.283 ThaliTest[567:558474] server session: connect
2015-12-20 03:44:50.284 ThaliTest[567:558474] server session: stateChange:0->1 Apple-Iphone5s-1_PT7946
2015-12-20 03:44:50.292 ThaliTest[567:558474] server: accepting invitation Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:50.685 ThaliTest[567:559198] client session: connected
2015-12-20 03:44:50.685 ThaliTest[567:559198] client session: stateChange:1->2 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:50.700 ThaliTest[567:559187] client session: fireConnectCallback: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:50.700 ThaliTest[567:559187] jxcore: connect: success
2015-12-20T02:44:50.701Z SendDataConnector.js: CLIENT connected to ,54429, error: null
2015-12-20T02:44:50.702Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:50.705 ThaliTest[567:558474] client: relay established
2015-12-20 03:44:50.706 ThaliTest[567:558474] client: new accepted socket: 0x184338f0
,2015-12-20T02:44:50.718Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:51.078Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-20T02:44:51.128Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-20T02:44:51.141Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:51.141Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:51.141Z SendDataConnector.js: CLIENT Stop now
2015-12-20T02:44:51.141Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:51.142 ThaliTest[567:558695] jxcore: disconnect
2015-12-20 03:44:51.142 ThaliTest[567:558695] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:51.142 ThaliTest[567:558695] client session: disconnect
2015-12-20 03:44:51.142 ThaliTest[567:558695] client session: stateChange:2->0 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:51.147 ThaliTest[567:558695] jxcore: disconnect: success
2015-12-20T02:44:51.147Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:51.148Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20T02:44:51.148Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:51.149Z SendDataConnector.js: do connect now
2015-12-20 03:44:51.149 ThaliTest[567:558695] jxcore: connect Apple-Iphone5s-1_PT7946,.2ECkqQ==
2015-12-20 03:44:51.149 ThaliTest[567:558695] client session: connect
2015-12-20 03:44:51.149 ThaliTest[567:558695] client session: stateChange:0->1 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:54.350 ThaliTest[567:559198] server session: connected
2015-12-20 03:44:54.350 ThaliTest[567:559198] server session: stateChange:1->2 Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:54.413 ThaliTest[567:558474] server relay: connected (to port: 54421)
,2015-12-20T02:44:54.421Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:54.866Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-20T02:44:54.881Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-20T02:44:54.899Z SendDataTCPServer.js: TCP/IP server has received 56372 bytes of data
,2015-12-20T02:44:54.916Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-20T02:44:54.930Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:55.014 ThaliTest[567:559189] server session: not connected Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:55.113 ThaliTest[567:559198] client session: connected
2015-12-20 03:44:55.113 ThaliTest[567:559198] client session: stateChange:1->2 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:55.708 ThaliTest[567:559189] client session: fireConnectCallback: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:55.708 ThaliTest[567:559189] jxcore: connect: success
,2015-12-20T02:44:55.710Z SendDataConnector.js: CLIENT connected to 54433, error: null
,2015-12-20T02:44:55.711Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:55.714 ThaliTest[567:558474] client: relay established
2015-12-20 03:44:55.715 ThaliTest[567:558474] client: new accepted socket: 0x18299f90
,2015-12-20T02:44:55.728Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:56.159Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:56.159Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:56.160Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:56.160Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:56.161 ThaliTest[567:558695] jxcore: disconnect
,2015-12-20 03:44:56.161 ThaliTest[567:558695] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:56.161 ThaliTest[567:558695] client session: disconnect
,2015-12-20 03:44:56.162 ThaliTest[567:558695] client session: stateChange:2->0 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:56.226 ThaliTest[567:558695] jxcore: disconnect: success
,2015-12-20T02:44:56.227Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
,---- round done--------
startWithNextDevice
,2015-12-20 03:45:20.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:45:21.105 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:45:21.105 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:45:21.105 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:45:50.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:45:50.330 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:45:50.333 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:45:50.334 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:46:02.920 ThaliTest[567:558474] client: lost peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:46:02.920 ThaliTest[567:558474] client session: onPeerLost: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 03:46:05.821 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-20 03:46:20.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:46:20.333 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:46:20.333 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:46:20.335 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:46:50.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:47:20.283 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:47:20.321 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:47:20.321 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:47:20.324 ThaliTest[567:558474] client: fou,nd peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:47:50.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:47:50.322 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:47:51.311 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:47:51.311 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:48:20.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:48:20.324 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:48:21.302 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:21.303 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:48:50.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:48:50.322 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:48:51.075 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:48:51.076 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:49:20.284 ThaliTest[567:558474] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-20 03:49:50.284 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:49:50.320 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:49:51.025 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:49:51.025 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:50:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:50:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:50:20.272 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:50:20.276 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,appEnteringBackground wasn't registered
,2015-12-20 03:50:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:50:50.275 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:50:50.275 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:50:50.276 ThaliTest[567:558474] client: fou,nd peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,Connected to the server!
,2015-12-20 03:51:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:51:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:51:21.210 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:51:21.211 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:51:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:51:50.269 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:51:51.152 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:51:51.153 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:52:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:52:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:52:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:52:20.273 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:52:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:52:50.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:52:51.020 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:52:51.022 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,appEnteredForeground wasn't registered
,2015-12-20 03:53:20.232 ThaliTest[567:558474] multipeer session: restart
,appEnteringBackground wasn't registered
,2015-12-20 03:53:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:53:50.269 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:53:50.269 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:53:50.274 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:54:20.231 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:54:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:54:20.273 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:54:20.274 ThaliTest[567:558474] client: fo,und peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:54:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:54:50.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:54:51.109 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:54:51.110 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:55:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:55:20.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:55:21.051 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:55:21.051 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:55:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:55:50.269 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:55:50.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:55:50.276 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:56:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:21.262 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:56:21.263 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:56:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:56:50.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:51.224 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:56:51.225 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:57:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:57:20.275 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:57:21.017 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:57:21.017 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:57:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:57:50.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:57:51.002 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:57:51.002 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:58:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:58:20.269 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:58:20.272 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:58:20.274 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:58:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:58:50.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:58:50.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:58:50.274 ThaliTest[567:558474] client: fou,nd peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:59:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 03:59:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:59:21.111 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 03:59:21.112 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:59:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:00:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:00:20.268 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:00:21.070 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:21.071 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:00:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:00:50.272 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:00:50.272 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:00:50.275 ThaliTest[567:558474] client: fou,nd peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:01:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:01:20.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:01:21.081 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:01:21.081 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-20T03:01:22.899Z SendDataConnector.js: CLIENT Stop now
,2015-12-20 04:01:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:01:50.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:01:51.035 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:01:51.035 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:02:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:02:20.270 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:02:20.272 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:02:20.273 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:02:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:02:50.271 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:02:51.234 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:02:51.234 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:03:20.272 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:03:21.177 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:03:21.178 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:50.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:03:50.272 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:03:50.275 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:03:50.275 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:04:20.232 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:04:20.268 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:04:20.953 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:04:20.955 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,teardown
,testSendData stopped
2015-12-20 04:04:42.794 ThaliTest[567:558695] jxcore: stopBroadcasting
2015-12-20 04:04:42.794 ThaliTest[567:558695] THEMultipeerSession stopping peer
2015-12-20 04:04:42.795 ThaliTest[567:558695] multipeer session: stop timer
,2015-12-20 04:04:42.795 ThaliTest[567:558695] server session: disconnect
,2015-12-20 04:04:42.796 ThaliTest[567:558695] server session: stateChange:2->0 Apple-IpadAir2-1_PT5083
,2015-12-20 04:04:42.806 ThaliTest[567:558695] server session: disconnect
2015-12-20 04:04:42.806 ThaliTest[567:558695] server session: stateChange:2->0 Apple-Iphone5s-1_PT7946
2015-12-20 04:04:42.813 ThaliTest[567:558695] server session: disconnect
,2015-12-20 04:04:42.813 ThaliTest[567:558695] server session: stateChange:2->0 Apple-Iphone5-1_PT1975
,2015-12-20 04:04:42.830 ThaliTest[567:558695] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-20T03:04:42.849Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-20T03:04:42.850Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-20T03:04:42.851Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-20T03:04:42.852Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-20 04:04:43.024 ThaliTest[567:558695] jxcore: startBroadcasting
,2015-12-20 04:04:43.027 ThaliTest[567:558695] server: starting Apple-Iphone6-1_PT27.xRGq6Q==
,2015-12-20 04:04:43.030 ThaliTest[567:558695] multipeer session: start timer: 0x1828d820
2015-12-20 04:04:43.030 ThaliTest[567:558695] THEMultipeerSession initialized peer Apple-Iphone6-1_PT27
2015-12-20 04:04:43.031 ThaliTest[567:558695] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-20 04:04:43.972 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:04:43.972 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:04:43.973 ThaliTest[567:558474] client: fou,nd peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT1975.nu3zFw==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-20 04:04:45.046 ThaliTest[567:558474] client: lost peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:45.046 ThaliTest[567:558474] client session: onPeerLost: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:04:45.105 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:05:13.031 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:05:43.031 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:05:43.069 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:05:43.069 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
2015-12-20 04:05:43.070 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 04:06:13.031 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:06:13.071 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:13.071 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:06:13.074 ThaliTest[567:558474] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:06:43.031 ThaliTest[567:558474] multipeer session: restart
,2015-12-20 04:06:43.070 ThaliTest[567:558474] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:43.071 ThaliTest[567:558474] client: found peer: Apple-Iphone5-1_PT1975.nu3zFw==
2015-12-20 04:06:43.075 ThaliTest[567:558474] client: fou,nd peer: Apple-IpadAir2-1_PT5083.ybzVtw==

```
