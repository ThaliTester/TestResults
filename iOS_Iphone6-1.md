#### Test 50650278b86327b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/E8BBA497-C11B-49F7-819A-0253A0221973/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E8BBA497-C11B-49F7-819A-0253A0221973/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b86327b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A828E31B-029D-4AA1-85AC-4676D758C5EF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53607"
,(lldb)     command script import "/tmp/E8BBA497-C11B-49F7-819A-0253A0221973/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-10 15:09:50.141 ThaliTest[708:580607] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A80B495A-3D98-4637-9620-948048F96CF1/Library/Cookies/Cookies.binarycookies
,2015-12-10 15:09:50.524 ThaliTest[708:580607] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-10 15:09:50.525 ThaliTest[708:580607] Multi-tasking -> Device: YES, App: YES
,2015-12-10 15:09:50.536 ThaliTest[708:580607] Unlimited access to network resources
,2015-12-10 15:09:50.550 ThaliTest[708:580607] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-10 15:09:59.758 ThaliTest[708:580607] Resetting plugins due to page load.
,2015-12-10 15:10:03.296 ThaliTest[708:580607] Finished load of: file:///var/mobile/Containers/Bundle/Application/A828E31B-029D-4AA1-85AC-4676D758C5EF/ThaliTest.app/www/index.html
,2015-12-10 15:10:03.536 ThaliTest[708:580607] JXcore Cordova plugin initializing
,2015-12-10 15:10:03.537 ThaliTest[708:580794] JXcore instance initializing
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
,2015-12-10 15:10:04.612 ThaliTest[708:580607] THREAD WARNING: ['JXcore'] took '77.601074' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-10 15:14:33.455 ThaliTest[708:580794] jxcore: startBroadcasting
,2015-12-10 15:14:33.472 ThaliTest[708:580794] server: starting Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:14:33.473 ThaliTest[708:580794] multipeer session: start timer: 0x18bdafc0
,2015-12-10 15:14:33.476 ThaliTest[708:580794] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4262
2015-12-10 15:14:33.476 ThaliTest[708:580794] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-10 15:14:45.441 ThaliTest[708:580607] client: found peer: Apple-Iphone5-1_PT9189.I0Ha/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9189.I0Ha/w==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT9189.I0Ha/w==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-10 15:14:45.945 ThaliTest[708:580794] jxcore: stopBroadcasting
2015-12-10 15:14:45.946 ThaliTest[708:580794] THEMultipeerSession stopping peer
2015-12-10 15:14:45.946 ThaliTest[708:580794] multipeer session: stop timer
2015-12-10 15:14:45.946 ThaliTest[708:580794] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":2}bt-address length : 0
,daya100000
,check server
,serverPort is 55965
,2015-12-10 15:14:46.026 ThaliTest[708:580794] jxcore: startBroadcasting
,2015-12-10 15:14:46.030 ThaliTest[708:580794] server: starting Apple-Iphone6-1_PT4262.fxR5Pw==
,2015-12-10 15:14:46.032 ThaliTest[708:580794] multipeer session: start timer: 0x18bda9c0
,2015-12-10 15:14:46.033 ThaliTest[708:580794] THEMultipeerSession initialized peer Apple-Iphone6-1_PT4262
,2015-12-10 15:14:46.035 ThaliTest[708:580794] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-10T14:14:46.048Z SendDataTCPServer.js: TCP/IP server is bound to port: 55965
,2015-12-10 15:14:46.532 ThaliTest[708:580607] client: found peer: Apple-Iphone6-1_PT4262.KAmLlg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4262.KAmLlg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:14:46.536Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:14:46.539Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10T14:14:46.539Z SendDataConnector.js: do connect now
2015-12-10 15:14:46.540 ThaliTest[708:580607] client: found peer: Apple-Iphone5-1_PT91,89.I0Ha/w==
2015-12-10 15:14:46.540 ThaliTest[708:580794] jxcore: connect Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:46.541 ThaliTest[708:580794] client session: connect
2015-12-10 15:14:46.541 ThaliTest[708:580794] client session: stateChange:0->,1 Apple-Iphone6-1_PT4262.KAmLlg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9189.I0Ha/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10 15:14:47.049 ThaliTest[708:580607] client: lost peer: Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:47.049 ThaliTest[708:580607] client session: onPeerLost: Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:47.049 ThaliTest[708:580607] clien,t session: onLinkFailure: Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:47.049 ThaliTest[708:580607] client session: disconnect
2015-12-10 15:14:47.050 ThaliTest[708:580607] client session: stateChange:1->0 Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 ,15:14:47.050 ThaliTest[708:580607] client session: fireConnectCallback: Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:47.051 ThaliTest[708:580607] jxcore: connect: fail: Peer disconnected
2015-12-10T14:14:47.052Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-10T14:14:47.053Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-10T14:14:47.054Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_P,T4262.KAmLlg==","peerName":"(null)","peerAvailable":false}]
,2015-12-10 15:14:50.947 ThaliTest[708:580607] client: lost peer: Apple-Iphone5-1_PT9189.I0Ha/w==
2015-12-10 15:14:50.948 ThaliTest[708:580607] client session: onPeerLost: Apple-Iphone5-1_PT9189.I0Ha/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone5-1_PT9189.I0Ha/w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-10 15:14:50.951 ThaliTest[708:580607] client: found peer: Apple-Iphone5-1_PT9189.dQfCuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9189.dQfCuw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-10T14:14:52.060Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:14:52.061Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:14:57.066 ThaliTest[708:580794] jxcore: disconnect
2015-12-10 15:14:57.067 ThaliTest[708:580794] jxcore: disconnect: fail
2015-12-10T14:14:57.067Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.KAmLlg==,
2015-12-10T14:14:57.068Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT4262.KAmLlg== with availability status: true
2015-12-10T14:14:57.068Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:14:57.068Z SendDataConnector.js: do connect now
,2015-12-10 15:14:57.069 ThaliTest[708:580794] jxcore: connect Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:57.070 ThaliTest[708:580794] client: connect: unreachable Apple-Iphone6-1_PT4262.KAmLlg==
2015-12-10 15:14:57.071 ThaliTest[708:580794] jxcore:, connect: fail: Peer unreachable
2015-12-10T14:14:57.071Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:14:57.072Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-10T14:14:57.072Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:02.082Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:15:02.083Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:07.086 ThaliTest[708:580794] jxcore: disconnect
2015-12-10 15:15:07.087 ThaliTest[708:580794] jxcore: disconnect: fail
2015-12-10T14:15:07.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.KAmLlg==,
2015-12-10T14:15:07.088Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT4262.KAmLlg== with availability status: true
2015-12-10T14:15:07.088Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.KAmLlg==
2015-,12-10T14:15:07.088Z SendDataConnector.js: do connect now
,2015-12-10 15:15:07.089 ThaliTest[708:580794] jxcore: connect Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:07.090 ThaliTest[708:580794] client: connect: unreachable Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:07.091 ThaliTest[708:580794] jxcore: connect: fail: Peer unreachable
2015-12-10T14:15:07.091Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:15:07.092Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
2015-12-10T14:15:07.092Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:12.097Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:15:12.097Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:16.035 ThaliTest[708:580607] multipeer session: restart
,2015-12-10 15:15:16.072 ThaliTest[708:580607] client: found peer: Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10 15:15:17.103 ThaliTest[708:580794] jxcore: disconnect
2015-12-10 15:15:17.104 ThaliTest[708:580794] jxcore: disconnect: fail
2015-12-10T14:15:17.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.KAmLlg==,
2015-12-10T14:15:17.104Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT4262.KAmLlg== with availability status: true
2015-12-10T14:15:17.105Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.KAmLlg==
2015-,12-10T14:15:17.105Z SendDataConnector.js: do connect now
,2015-12-10 15:15:17.106 ThaliTest[708:580794] jxcore: connect Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:17.107 ThaliTest[708:580794] client: connect: unreachable Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:17.108 ThaliTest[708:580794] jxcore: connect: fail: Peer unreachable
2015-12-10T14:15:17.109Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:15:17.109Z SendDataConnector.js: CLIENT Can not Connect: Pee,r unreachable
2015-12-10T14:15:17.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-10T14:15:22.120Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:15:22.120Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:27.123 ThaliTest[708:580794] jxcore: disconnect
2015-12-10 15:15:27.124 ThaliTest[708:580794] jxcore: disconnect: fail
2015-12-10T14:15:27.124Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.KAmLlg==,
2015-12-10T14:15:27.124Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT4262.KAmLlg== with availability status: true
2015-12-10T14:15:27.125Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10T14:15:27.125Z SendDataConnector.js: do connect now
,2015-12-10 15:15:27.126 ThaliTest[708:580794] jxcore: connect Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:27.127 ThaliTest[708:580794] client: connect: unreachable Apple-Iphone6-1_PT4262.KAmLlg==
,2015-12-10 15:15:27.127 ThaliTest[708:580794] jxcore: connect: fail: Peer unreachable
,2015-12-10T14:15:27.128Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-10T14:15:27.129Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-10T14:15:27.132Z SendDataConnector.js: CLIENT Stop now
,2015-12-10 15:15:27.133 ThaliTest[708:580794] jxcore: disconnect
2015-12-10 15:15:27.133 ThaliTest[708:580794] jxcore: disconnect: fail
2015-12-10T14:15:27.134Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4262.KAmLlg==,
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10T14:15:27.138Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10T14:15:27.138Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10T14:15:27.139Z SendDataConnector.js: do connect now
,2015-12-10 15:15:27.140 ThaliTest[708:580794] jxcore: connect Apple-Iphone5-1_PT9189.dQfCuw==
2015-12-10 15:15:27.141 ThaliTest[708:580794] client session: connect
2015-12-10 15:15:27.141 ThaliTest[708:580794] client session: stateChange:0->1 Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10 15:15:33.891 ThaliTest[708:580607] multipeer session: reset timer
2015-12-10 15:15:33.891 ThaliTest[708:580607] multipeer session: stop timer
2015-12-10 15:15:33.891 ThaliTest[708:580607] multipeer session: start timer: 0x18bda9c0
,2015-12-10 15:15:33.892 ThaliTest[708:580607] server session: connect
2015-12-10 15:15:33.892 ThaliTest[708:580607] server session: stateChange:0->1 Apple-Iphone5-1_PT9189
,2015-12-10 15:15:33.902 ThaliTest[708:580607] server: accepting invitation Apple-Iphone5-1_PT9189
,2015-12-10 15:15:36.905 ThaliTest[708:581413] client session: connected
2015-12-10 15:15:36.906 ThaliTest[708:581413] client session: stateChange:1->2 Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10 15:15:36.959 ThaliTest[708:581331] server session: connected
2015-12-10 15:15:36.959 ThaliTest[708:581331] server session: stateChange:1->2 Apple-Iphone5-1_PT9189
,2015-12-10 15:15:37.418 ThaliTest[708:581413] client session: fireConnectCallback: Apple-Iphone5-1_PT9189.dQfCuw==
2015-12-10 15:15:37.420 ThaliTest[708:581413] jxcore: connect: success
2015-12-10T14:15:37.421Z SendDataConnector.js: CLIENT connected to 55972, error: null
2015-12-10T14:15:37.426Z SendDataConnector.js: CLIENT starting client 
,2015-12-10 15:15:37.434 ThaliTest[708:580607] client: relay established
2015-12-10 15:15:37.434 ThaliTest[708:580607] client: new accepted socket: 0x18beebd0
2015-12-10 15:15:37.438 ThaliTest[708:580607] server relay: connected (to port: 55965)
,2015-12-10T14:15:37.449Z SendDataTCPServer.js: TCP/IP server connected
2015-12-10T14:15:37.451Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-10T14:15:37.809Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-10T14:15:37.871Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-10T14:15:38.005Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-10T14:15:38.016Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-10T14:15:38.275Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-10T14:15:38.328Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-10T14:15:38.463Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-10T14:15:38.526Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-10T14:15:38.540Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-10T14:15:38.650Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-10T14:15:38.677Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-10T14:15:38.727Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-10T14:15:38.790Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-10T14:15:38.988Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-10T14:15:39.126Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-10T14:15:39.263Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-10T14:15:39.443Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-10T14:15:39.583Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-10T14:15:39.904Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-10T14:15:39.968Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2015-12-10T14:15:40.151Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-10T14:15:40.697Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-10T14:15:40.957Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-10T14:15:40.971Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-10T14:15:41.023Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-10T14:15:41.217Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-10T14:15:41.480Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-10T14:15:41.664Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-10T14:15:41.882Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-10T14:15:42.019Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-10T14:15:42.141Z SendDataTCPServer.js: TCP/IP server has received 69938 bytes of data
,2015-12-10T14:15:42.155Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-10T14:15:42.208Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-10T14:15:42.386Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-10T14:15:42.524Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-10T14:15:42.663Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-10T14:15:42.726Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-10T14:15:42.740Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-10T14:15:42.791Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-10T14:15:42.929Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-10T14:15:43.191Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-10T14:15:43.305Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-10T14:15:43.766Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-10T14:15:43.843Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-10T14:15:44.117Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-10T14:15:44.185Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-10T14:15:44.535Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-10T14:15:44.952Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-10T14:15:45.201Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-10T14:15:51.487Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-10T14:15:51.514Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-10T14:15:52.042Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-10T14:15:52.599Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-10T14:15:52.833Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-10T14:15:53.208Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-10T14:15:53.235Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-10T14:15:53.237Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-10T14:15:53.238Z SendDataConnector.js: CLIENT Stop now
,2015-12-10T14:15:53.239Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-10 15:15:53.242 ThaliTest[708:580794] jxcore: disconnect
,2015-12-10 15:15:53.244 ThaliTest[708:580794] client session: disconnectFromPeer: Apple-Iphone5-1_PT9189.dQfCuw==
2015-12-10 15:15:53.245 ThaliTest[708:580794] client session: disconnect
2015-12-10 15:15:53.245 ThaliTest[708:580794] client session: state,Change:2->0 Apple-Iphone5-1_PT9189.dQfCuw==
,2015-12-10 15:15:53.255 ThaliTest[708:580794] jxcore: disconnect: success
2015-12-10T14:15:53.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9189.dQfCuw==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 2
,sendReportNow
done, now sending data to server
2015-12-10T14:15:53.264Z SendDataConnector.js: CLIENT Stop now
2015-12-10T14:15:53.265Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2015-12-10 15:15:53.523 ThaliTest[708:580794] jxcore: stopBroadcasting
2015-12-10 15:15:53.524 ThaliTest[708:580794] THEMultipeerSession stopping peer
2015-12-10 15:15:53.524 ThaliTest[708:580794] multipeer session: stop timer
2015-12-10 15:15:53.525 Th,aliTest[708:580794] server session: disconnect
2015-12-10 15:15:53.525 ThaliTest[708:580794] server session: stateChange:2->0 Apple-Iphone5-1_PT9189
,2015-12-10 15:15:53.553 ThaliTest[708:580794] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-10T14:15:53.586Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-10T14:15:53.590Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
