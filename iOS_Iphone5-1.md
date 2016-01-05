#### Test 550731521dbc378_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/83325020-C631-4317-80A3-6465AFC98807/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/83325020-C631-4317-80A3-6465AFC98807/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/550731521dbc378/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EB0187BE-290C-4D09-A168-A346D74E7316/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64874"
,(lldb)     command script import "/tmp/83325020-C631-4317-80A3-6465AFC98807/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 11:15:59.962 ThaliTest[945:3082552] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F09D920D-395B-46F9-8E48-458553E06D2A/Library/Cookies/Cookies.binarycookies
,2016-01-05 11:16:00.521 ThaliTest[945:3082552] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 11:16:00.522 ThaliTest[945:3082552] Multi-tasking -> Device: YES, App: YES
,2016-01-05 11:16:00.529 ThaliTest[945:3082552] Unlimited access to network resources
,2016-01-05 11:16:00.542 ThaliTest[945:3082552] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 11:16:11.002 ThaliTest[945:3082552] Resetting plugins due to page load.
,2016-01-05 11:16:14.670 ThaliTest[945:3082552] Finished load of: file:///var/mobile/Containers/Bundle/Application/EB0187BE-290C-4D09-A168-A346D74E7316/ThaliTest.app/www/index.html
,2016-01-05 11:16:14.884 ThaliTest[945:3082552] JXcore Cordova plugin initializing
,2016-01-05 11:16:14.886 ThaliTest[945:3082736] JXcore instance initializing
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
,2016-01-05 11:16:17.357 ThaliTest[945:3082552] THREAD WARNING: ['JXcore'] took '155.449707' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 11:23:09.941 ThaliTest[945:3082736] jxcore: startBroadcasting
,2016-01-05 11:23:09.951 ThaliTest[945:3082736] server: starting Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:09.953 ThaliTest[945:3082736] multipeer session: start timer: 0x1bb6fdb0
,2016-01-05 11:23:09.953 ThaliTest[945:3082736] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-05 11:23:09.958 ThaliTest[945:3082736] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 11:23:11.061 ThaliTest[945:3082552] client: found peer: Apple-IpadAir2-1.o3kBVg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.o3kBVg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-05 11:23:11.651 ThaliTest[945:3082552] client: found peer: Apple-Iphone5s-1.Jzs4Xw==
,teardown
,testFindPeers stopped
,2016-01-05 11:23:12.375 ThaliTest[945:3082736] jxcore: stopBroadcasting
2016-01-05 11:23:12.375 ThaliTest[945:3082736] THEMultipeerSession stopping peer
2016-01-05 11:23:12.375 ThaliTest[945:3082736] multipeer session: stop timer
2016-01-05 11:23:12.376 ThaliTest[945:3082736] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 63599
,2016-01-05 11:23:12.436 ThaliTest[945:3082736] jxcore: startBroadcasting
,2016-01-05 11:23:12.439 ThaliTest[945:3082736] server: starting Apple-Iphone5-1.GgrI3w==
2016-01-05 11:23:12.440 ThaliTest[945:3082736] multipeer session: start timer: 0x1bb62060
2016-01-05 11:23:12.440 ThaliTest[945:3082736] THEMultipeerSession initiali,zed peer Apple-Iphone5-1
2016-01-05 11:23:12.441 ThaliTest[945:3082736] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2016-01-05T10:23:12.445Z SendDataTCPServer.js: TCP/IP server is bound to port: 63599
,2016-01-05 11:23:12.465 ThaliTest[945:3082552] client: found peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:12.466 ThaliTest[945:3082552] client: found peer: Apple-IpadAir2-1.o3kBVg==
2016-01-05 11:23:12.466 ThaliTest[945:3082552] client: found peer: Ap,ple-Iphone5s-1.Jzs4Xw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:12.4,69Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:12.470Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:12.470Z SendDataConnector.js: do connect now
,2016-01-05 11:23:12.471 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:12.472 ThaliTest[945:3082736] client session: connect
2016-01-05 11:23:12.473 ThaliTest[945:3082736] client session: stateChange:0->1 Apple-Iphone5-1.+hwmKw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Jzs4Xw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 11:23:13.698 ThaliTest[945:3082552] client: lost peer: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:13.699 ThaliTest[945:3082552] client session: onPeerLost: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:13.699 ThaliTest[945:3082552] client session: ,onLinkFailure: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:13.699 ThaliTest[945:3082552] client session: disconnect
2016-01-05 11:23:13.699 ThaliTest[945:3082552] client session: stateChange:1->0 Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:13.702 ThaliTest[945:3082552] client session: fireConnectCallback: Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:13.702 ThaliTest[945:3082552] jxcore: connect: fail: Peer disconnected
2016-01-05 11:23:13.703 ThaliTest[945:3082552] client: lo,st peer: Apple-IpadAir2-1.o3kBVg==
2016-01-05 11:23:13.704 ThaliTest[945:3082552] client session: onPeerLost: Apple-IpadAir2-1.o3kBVg==
2016-01-05T10:23:13.705Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-05T10:23:13.70,5Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T10:23:13.706Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.+hwmKw==","peerName":"(null)","peerAvailable":false}]
p,eerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.o3kBVg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-05 11:23:13.793 ThaliTest[945:3082552] client: found peer: Apple-IpadAir2-1.C4KP1Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.C4KP1Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 11:23:14.152 ThaliTest[945:3082552] client: found peer: Apple-Iphone6-1.DQd5Sw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DQd5Sw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 11:23:14.717 ThaliTest[945:3082552] client: lost peer: Apple-Iphone5s-1.Jzs4Xw==
,2016-01-05 11:23:14.718 ThaliTest[945:3082552] client session: onPeerLost: Apple-Iphone5s-1.Jzs4Xw==
2016-01-05 11:23:14.719 ThaliTest[945:3082552] client: found peer: Apple-Iphone5s-1.R3Z2qA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1,.Jzs4Xw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.R3Z2qA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05T10:23:18.715Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:18.716Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:23.720 ThaliTest[945:3082736] jxcore: disconnect
2016-01-05 11:23:23.720 ThaliTest[945:3082736] jxcore: disconnect: fail
2016-01-05T10:23:23.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
2016,-01-05T10:23:23.721Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
2016-01-05T10:23:23.722Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:23.722Z SendDataConnector.js: do connect now
,2016-01-05 11:23:23.723 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:23.724 ThaliTest[945:3082736] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:23.724 ThaliTest[945:3082736] jxcore: connect: f,ail: Peer unreachable
2016-01-05T10:23:23.725Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:23.725Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:23.725Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:28.735Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:28.736Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:33.747 ThaliTest[945:3082736] jxcore: disconnect
2016-01-05 11:23:33.747 ThaliTest[945:3082736] jxcore: disconnect: fail
2016-01-05T10:23:33.748Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
2016,-01-05T10:23:33.748Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
2016-01-05T10:23:33.748Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:33.749Z, SendDataConnector.js: do connect now
,2016-01-05 11:23:33.750 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:33.750 ThaliTest[945:3082736] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:33.751 ThaliTest[945:3082736] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:33.751Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:33.751Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:33.751Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:38.764Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:38.764Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:42.442 ThaliTest[945:3082552] multipeer session: restart
,2016-01-05 11:23:42.476 ThaliTest[945:3082552] client: found peer: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:23:42.477 ThaliTest[945:3082552] client: found peer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:42.477 ThaliTest[945:3082552] client: found peer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:23:43.771 ThaliTest[945:3082736] jxcore: disconnect
2016-01-05 11:23:43.771 ThaliTest[945:3082736] jxcore: disconnect: fail
2016-01-05T10:23:43.772Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
2016,-01-05T10:23:43.772Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
2016-01-05T10:23:43.773Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:43.773Z SendDataConnector.js: do connect now
,2016-01-05 11:23:43.774 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:43.775 ThaliTest[945:3082736] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:43.775 ThaliTest[945:3082736] jxcore: connect: fail: Peer unreachable
,2016-01-05T10:23:43.776Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T10:23:43.776Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T10:23:43.776Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T10:23:48.784Z SendDataConnector.js: re-try now : Apple-Iphone5-1.+hwmKw==
,2016-01-05T10:23:48.785Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:53.655 ThaliTest[945:3082552] multipeer session: reset timer
2016-01-05 11:23:53.656 ThaliTest[945:3082552] multipeer session: stop timer
2016-01-05 11:23:53.656 ThaliTest[945:3082552] multipeer session: start timer: 0x1bb62060
2016-01-,05 11:23:53.656 ThaliTest[945:3082552] server session: connect
2016-01-05 11:23:53.656 ThaliTest[945:3082552] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 11:23:53.662 ThaliTest[945:3082552] server: accepting invitation Apple-Iphone6-1
,2016-01-05 11:23:53.792 ThaliTest[945:3082736] jxcore: disconnect
2016-01-05 11:23:53.792 ThaliTest[945:3082736] jxcore: disconnect: fail
2016-01-05T10:23:53.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
2016,-01-05T10:23:53.793Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.+hwmKw== with availability status: true
2016-01-05T10:23:53.793Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.+hwmKw==
2016-01-05T10:23:53.793Z, SendDataConnector.js: do connect now
,2016-01-05 11:23:53.794 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5-1.+hwmKw==
,2016-01-05 11:23:53.795 ThaliTest[945:3082736] client: connect: unreachable Apple-Iphone5-1.+hwmKw==
2016-01-05 11:23:53.797 ThaliTest[945:3082736] jxcore: connect: fail: Peer unreachable
2016-01-05T10:23:53.797Z SendDataConnector.js: CLIENT connected to, 0, error: Peer unreachable
2016-01-05T10:23:53.797Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-05T10:23:53.798Z SendDataConnector.js: CLIENT Stop now
2016-01-05 11:23:53.799 ThaliTest[945:3082736] jxcore: di,sconnect
2016-01-05 11:23:53.799 ThaliTest[945:3082736] jxcore: disconnect: fail
2016-01-05T10:23:53.799Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.+hwmKw==
---- round done--------
startWithNextDevice
device[2]: Appl,e-IpadAir2-1.C4KP1Q==
2016-01-05T10:23:53.800Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:23:53.801Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.C4KP1Q==
2016-01-05T10:23:53.801Z SendDataConnector.js: do connect now
,2016-01-05 11:23:53.804 ThaliTest[945:3082736] jxcore: connect Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:53.805 ThaliTest[945:3082736] client session: connect
2016-01-05 11:23:53.806 ThaliTest[945:3082736] client session: stateChange:0->1 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:54.372 ThaliTest[945:3082552] multipeer session: reset timer
2016-01-05 11:23:54.372 ThaliTest[945:3082552] multipeer session: stop timer
2016-01-05 11:23:54.372 ThaliTest[945:3082552] multipeer session: start timer: 0x1bb62060
2016-01-,05 11:23:54.372 ThaliTest[945:3082552] server session: connect
2016-01-05 11:23:54.372 ThaliTest[945:3082552] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 11:23:54.380 ThaliTest[945:3082552] server: accepting invitation Apple-IpadAir2-1
,2016-01-05 11:23:56.275 ThaliTest[945:3083544] server session: connected
2016-01-05 11:23:56.276 ThaliTest[945:3083544] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 11:23:56.335 ThaliTest[945:3082552] server relay: connected (to port: 63599)
,2016-01-05T10:23:56.341Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:23:56.741Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-05T10:23:56.754Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:23:57.786 ThaliTest[945:3083599] server session: connected
,2016-01-05 11:23:57.786 ThaliTest[945:3083599] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 11:23:57.824 ThaliTest[945:3082552] server relay: connected (to port: 63599)
2016-01-05T10:23:57.826Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05 11:23:57.835 ThaliTest[945:3083554] client session: connected
2016-01-05 11:23:57.835 ThaliTest[945:3083554] client session: stateChange:1->2 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:57.872 ThaliTest[945:3083554] client session: fireConnectCallback: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:57.872 ThaliTest[945:3083554] jxcore: connect: success
,2016-01-05T10:23:57.873Z SendDataConnector.js: CLIENT connected to 63608, error: null
,2016-01-05T10:23:57.873Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:23:57.875 ThaliTest[945:3082552] client: relay established
2016-01-05 11:23:57.875 ThaliTest[945:3082552] client: new accepted socket: 0x1bca7d00
,2016-01-05T10:23:57.891Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:23:58.505Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-05T10:23:58.521Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
2016-01-05T10:23:58.523Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T10:23:58.523Z SendDataConnector.js: got all data for this round
oneR,oundDownNow
2016-01-05T10:23:58.524Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:23:58.524Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-05 11:23:58.526 ThaliTest[945:3082736] jxcore: disconnect
2016-01-05 11:23:58.526 ThaliTest[945:3,082736] client session: disconnectFromPeer: Apple-IpadAir2-1.C4KP1Q==
2016-01-05 11:23:58.526 ThaliTest[945:3082736] client session: disconnect
2016-01-05 11:23:58.526 ThaliTest[945:3082736] client session: stateChange:2->0 Apple-IpadAir2-1.C4KP1Q==
,2016-01-05 11:23:58.545 ThaliTest[945:3082736] jxcore: disconnect: success
2016-01-05T10:23:58.548Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.C4KP1Q==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipho,ne6-1.DQd5Sw==
2016-01-05T10:23:58.549Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DQd5Sw==
2016-01-05T10:23:58.550Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DQd5Sw==
2016-01-05T10:23:58.550Z SendDataConnector.j,s: do connect now
2016-01-05 11:23:58.550 ThaliTest[945:3082736] jxcore: connect Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:23:58.550 ThaliTest[945:3082736] client session: connect
2016-01-05 11:23:58.551 ThaliTest[945:3082736] client session: stateChange:0,->1 Apple-Iphone6-1.DQd5Sw==
,2016-01-05T10:23:58.587Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:23:58.648 ThaliTest[945:3083544] server session: not connected Apple-IpadAir2-1
,2016-01-05 11:24:01.449 ThaliTest[945:3083554] client session: connected
2016-01-05 11:24:01.449 ThaliTest[945:3083554] client session: stateChange:1->2 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:01.480 ThaliTest[945:3083600] client session: fireConnectCallback: Apple-Iphone6-1.DQd5Sw==
2016-01-05 11:24:01.480 ThaliTest[945:3083600] jxcore: connect: success
2016-01-05T10:24:01.481Z SendDataConnector.js: CLIENT connected to 63611, error: null
2016-01-05T10:24:01.481Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 11:24:01.483 ThaliTest[945:3082552] client: relay established
2016-01-05 11:24:01.484 ThaliTest[945:3082552] client: new accepted socket: 0x1bca40d0
,2016-01-05T10:24:01.497Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:02.035Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T10:24:02.075Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-05T10:24:02.103Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:02.103Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T10:24:02.105Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:02.105Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:02.106 ThaliTest[945:3082736] jxcore: disconnect
,2016-01-05 11:24:02.107 ThaliTest[945:3082736] client session: disconnectFromPeer: Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:02.108 ThaliTest[945:3082736] client session: disconnect
,2016-01-05 11:24:02.108 ThaliTest[945:3082736] client session: stateChange:2->0 Apple-Iphone6-1.DQd5Sw==
,2016-01-05 11:24:02.184 ThaliTest[945:3082736] jxcore: disconnect: success
,2016-01-05T10:24:02.186Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DQd5Sw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:02.188Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:02.189Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.R3Z2qA==
,2016-01-05T10:24:02.189Z SendDataConnector.js: do connect now
,2016-01-05 11:24:02.190 ThaliTest[945:3082736] jxcore: connect Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:02.191 ThaliTest[945:3082736] client session: connect
,2016-01-05 11:24:02.191 ThaliTest[945:3082736] client session: stateChange:0->1 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:05.145 ThaliTest[945:3083600] client session: connected
2016-01-05 11:24:05.146 ThaliTest[945:3083600] client session: stateChange:1->2 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:05.175 ThaliTest[945:3083554] client session: fireConnectCallback: Apple-Iphone5s-1.R3Z2qA==
2016-01-05 11:24:05.175 ThaliTest[945:3083554] jxcore: connect: success
2016-01-05T10:24:05.175Z SendDataConnector.js: CLIENT connected to 63614,, error: null
2016-01-05T10:24:05.176Z SendDataConnector.js: CLIENT starting client 
2016-01-05 11:24:05.178 ThaliTest[945:3082552] client: relay established
,2016-01-05 11:24:05.178 ThaliTest[945:3082552] client: new accepted socket: 0x1bca2fe0
,2016-01-05T10:24:05.191Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T10:24:05.770Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T10:24:05.784Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T10:24:05.837Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T10:24:05.852Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-05T10:24:05.903Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T10:24:05.904Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T10:24:05.906Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T10:24:05.906Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:05.907 ThaliTest[945:3082736] jxcore: disconnect
,2016-01-05 11:24:05.908 ThaliTest[945:3082736] client session: disconnectFromPeer: Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:05.909 ThaliTest[945:3082736] client session: disconnect
,2016-01-05 11:24:05.910 ThaliTest[945:3082736] client session: stateChange:2->0 Apple-Iphone5s-1.R3Z2qA==
,2016-01-05 11:24:05.988 ThaliTest[945:3082736] jxcore: disconnect: success
,2016-01-05T10:24:05.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.R3Z2qA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T10:24:05.995Z SendDataConnector.js: CLIENT Stop now
2016-01-05T10:24:05.995Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 11:24:07.891 ThaliTest[945:3083554] server session: not connected Apple-Iphone6-1
,2016-01-05 11:24:24.373 ThaliTest[945:3082552] multipeer session: restart
,2016-01-05 11:24:39.498 ThaliTest[945:3082552] multipeer session: reset timer
2016-01-05 11:24:39.498 ThaliTest[945:3082552] multipeer session: stop timer
2016-01-05 11:24:39.498 ThaliTest[945:3082552] multipeer session: start timer: 0x1bb62060
2016-01-,05 11:24:39.498 ThaliTest[945:3082552] server session: connect
2016-01-05 11:24:39.498 ThaliTest[945:3082552] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-05 11:24:39.504 ThaliTest[945:3082552] server: accepting invitation Apple-Iphone5s-1
,2016-01-05 11:24:42.278 ThaliTest[945:3083690] server session: connected
2016-01-05 11:24:42.278 ThaliTest[945:3083690] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-05 11:24:42.800 ThaliTest[945:3082552] server relay: connected (to port: 63599)
,2016-01-05T10:24:42.812Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T10:24:43.248Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-05T10:24:43.262Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-05T10:24:43.276Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2016-01-05T10:24:43.293Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-05T10:24:43.319Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
,2016-01-05T10:24:43.333Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 11:24:43.381 ThaliTest[945:3083652] server session: not connected Apple-Iphone5s-1
,teardown
,testSendData stopped
2016-01-05 11:24:49.990 ThaliTest[945:3082736] jxcore: stopBroadcasting
,2016-01-05 11:24:49.990 ThaliTest[945:3082736] THEMultipeerSession stopping peer
2016-01-05 11:24:49.990 ThaliTest[945:3082736] multipeer session: stop timer
,2016-01-05 11:24:49.991 ThaliTest[945:3082736] server session: disconnect
2016-01-05 11:24:49.991 ThaliTest[945:3082736] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-05 11:24:49.995 ThaliTest[945:3082736] server session: disconnect
2016-01-05 11:24:49.996 ThaliTest[945:3082736] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-05 11:24:50.000 ThaliTest[945:3082736] server session: disconnect
2016-01-05 11:24:50.000 ThaliTest[945:3082736] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-05 11:24:50.088 ThaliTest[945:3082736] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-05T10:24:50.105Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.108Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.109Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T10:24:50.109Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
