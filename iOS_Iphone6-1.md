#### Test 50650278cb112b9_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/3347BAB6-D778-46FE-8479-6E3E83A68B6A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3347BAB6-D778-46FE-8479-6E3E83A68B6A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278cb112b9/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EAADD6AD-D5AE-4C61-920A-BEE589F5480C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56162"
,(lldb)     command script import "/tmp/3347BAB6-D778-46FE-8479-6E3E83A68B6A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-15 04:20:30.941 ThaliTest[982:1249062] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B86AFC2B-1385-4FFE-80DA-ED5C8F21DCE2/Library/Cookies/Cookies.binarycookies
,2015-12-15 04:20:31.354 ThaliTest[982:1249062] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-15 04:20:31.355 ThaliTest[982:1249062] Multi-tasking -> Device: YES, App: YES
,2015-12-15 04:20:31.361 ThaliTest[982:1249062] Unlimited access to network resources
,2015-12-15 04:20:31.373 ThaliTest[982:1249062] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-15 04:20:39.728 ThaliTest[982:1249062] Resetting plugins due to page load.
,2015-12-15 04:20:42.933 ThaliTest[982:1249062] Finished load of: file:///var/mobile/Containers/Bundle/Application/EAADD6AD-D5AE-4C61-920A-BEE589F5480C/ThaliTest.app/www/index.html
,2015-12-15 04:20:43.136 ThaliTest[982:1249062] JXcore Cordova plugin initializing
,2015-12-15 04:20:43.138 ThaliTest[982:1249382] JXcore instance initializing
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
,2015-12-15 04:20:44.204 ThaliTest[982:1249062] THREAD WARNING: ['JXcore'] took '76.989014' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-15 04:25:44.835 ThaliTest[982:1249382] jxcore: startBroadcasting
,2015-12-15 04:25:44.853 ThaliTest[982:1249382] server: starting Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:44.855 ThaliTest[982:1249382] multipeer session: start timer: 0x163f7da0
2015-12-15 04:25:44.856 ThaliTest[982:1249382] THEMultipeerSession i,nitialized peer Apple-Iphone6-1_PT1123
2015-12-15 04:25:44.856 ThaliTest[982:1249382] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-15 04:25:46.025 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT7023.MnyDhQ==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-15 04:25:46.305 ThaliTest[982:1249382] jxcore: stopBroadcasting
2015-12-15 04:25:46.306 ThaliTest[982:1249382] THEMultipeerSession stopping peer
2015-12-15 04:25:46.307 ThaliTest[982:1249382] multipeer session: stop timer
2015-12-15 04:25:46.307, ThaliTest[982:1249382] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 58955
,2015-12-15 04:25:46.372 ThaliTest[982:1249382] jxcore: startBroadcasting
,2015-12-15 04:25:46.376 ThaliTest[982:1249382] server: starting Apple-Iphone6-1_PT1123.uhofxg==
2015-12-15 04:25:46.377 ThaliTest[982:1249382] multipeer session: start timer: 0x16376970
2015-12-15 04:25:46.377 ThaliTest[982:1249382] THEMultipeerSession i,nitialized peer Apple-Iphone6-1_PT1123
2015-12-15 04:25:46.378 ThaliTest[982:1249382] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-15T03:25:46.383Z SendDataTCPServer.js: TCP/IP server is bound to port: 58955
,2015-12-15 04:25:46.843 ThaliTest[982:1249062] client: found peer: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:46.844 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:25:46.849Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:46.850Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:25:46.850Z SendDataConnector.js: do connect now
,2015-12-15 04:25:46.852 ThaliTest[982:1249382] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:46.853 ThaliTest[982:1249382] client session: connect
2015-12-15 04:25:46.853 ThaliTest[982:1249382] client session: stateChange:0->1 Apple-Ip,hone6-1_PT1123.S9LZPw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:46.959 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.mlJOKQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:47.539 ThaliTest[982:1249062] client: lost peer: Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:47.540 ThaliTest[982:1249062] client session: onPeerLost: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.541 ThaliTest[982:1249062] client session: onLinkFailure: Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.541 ThaliTest[982,:1249062] client session: disconnect
2015-12-15 04:25:47.542 ThaliTest[982:1249062] client session: stateChange:1->0 Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:47.542 ThaliTest[982:1249062] client session: fireConnectCallback: Apple-Iphone6-1_PT112,3.S9LZPw==
,2015-12-15 04:25:47.543 ThaliTest[982:1249062] jxcore: connect: fail: Peer disconnected
,2015-12-15 04:25:47.544 ThaliTest[982:1249062] client: lost peer: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15 04:25:47.545 ThaliTest[982:1249062] client session: onPeerLost: Apple-IpadAir2-1_PT7023.MnyDhQ==
2015-12-15T03:25:47.546Z SendDataConnector.js: ,CLIENT connected to 0, error: Peer disconnected
2015-12-15T03:25:47.546Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-15T03:25:47.547Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone6-1_PT1123.S9LZPw==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.MnyDhQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 04:25:47.944 ThaliTest[982:1249062] client: lost peer: Apple-Iphone5-1_PT9128.mlJOKQ==
2015-12-15 04:25:47.944 ThaliTest[982:1249062] client session: onPeerLost: Apple-Iphone5-1_PT9128.mlJOKQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5-1_PT9128.mlJOKQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 04:25:48.149 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.h41t3A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 04:25:48.252 ThaliTest[982:1249062] multipeer session: reset timer
2015-12-15 04:25:48.252 ThaliTest[982:1249062] multipeer session: stop timer
2015-12-15 04:25:48.253 ThaliTest[982:1249062] multipeer session: start timer: 0x16376970
2015-12-,15 04:25:48.253 ThaliTest[982:1249062] server session: connect
2015-12-15 04:25:48.253 ThaliTest[982:1249062] server session: stateChange:0->1 Apple-Iphone5-1_PT9128
,2015-12-15 04:25:48.263 ThaliTest[982:1249062] server: accepting invitation Apple-Iphone5-1_PT9128
2015-12-15 04:25:48.265 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:49.061 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9128.H9FQ7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-15 04:25:51.405 ThaliTest[982:1249947] server session: connected
2015-12-15 04:25:51.405 ThaliTest[982:1249947] server session: stateChange:1->2 Apple-Iphone5-1_PT9128
,2015-12-15 04:25:51.424 ThaliTest[982:1249062] server relay: connected (to port: 58955)
,2015-12-15T03:25:51.432Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15T03:25:51.954Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-15T03:25:51.969Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-15T03:25:52.200Z SendDataTCPServer.js: TCP/IP server has received 32140 bytes of data
,2015-12-15T03:25:52.215Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:25:52.290 ThaliTest[982:1249936] server session: not connected Apple-Iphone5-1_PT9128
,2015-12-15T03:25:52.555Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:52.556Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:25:57.564 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:25:57.565 ThaliTest[982:1249382] jxcore: disconnect: fail
2015-12-15T03:25:57.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw=,=
2015-12-15T03:25:57.566Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:25:57.566Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:25:57.567Z SendDataConnector.js: do connect now
,2015-12-15 04:25:57.568 ThaliTest[982:1249382] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:57.569 ThaliTest[982:1249382] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:25:57.569 ThaliTest[982:1249382] jxco,re: connect: fail: Peer unreachable
2015-12-15T03:25:57.570Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:25:57.570Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T03:25:57.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:02.571Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:02.571Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:07.585 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:26:07.586 ThaliTest[982:1249382] jxcore: disconnect: fail
2015-12-15T03:26:07.586Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw=,=
2015-12-15T03:26:07.587Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:07.587Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
201,5-12-15T03:26:07.587Z SendDataConnector.js: do connect now
,2015-12-15 04:26:07.589 ThaliTest[982:1249382] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:07.590 ThaliTest[982:1249382] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:07.590 ThaliTest[982:1249382] jxco,re: connect: fail: Peer unreachable
2015-12-15T03:26:07.591Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:26:07.591Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T03:26:07.592Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15T03:26:12.599Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:12.599Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:16.480 ThaliTest[982:1249062] client: lost peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:16.481 ThaliTest[982:1249062] client session: onPeerLost: Apple-IpadAir2-1_PT7023.h41t3A==
peerAvailabilityChanged [{"peerIdentifier":"App,le-IpadAir2-1_PT7023.h41t3A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-15 04:26:17.030 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7023.h41t3A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-15 04:26:17.608 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:26:17.609 ThaliTest[982:1249382] jxcore: disconnect: fail
2015-12-15T03:26:17.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw=,=
2015-12-15T03:26:17.610Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:17.610Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:17.610Z SendDataConnector.js: do connect now
,2015-12-15 04:26:17.612 ThaliTest[982:1249382] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:17.613 ThaliTest[982:1249382] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:17.613 ThaliTest[982:1249382] jxco,re: connect: fail: Peer unreachable
2015-12-15T03:26:17.614Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:26:17.614Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-15T03:26:17.615Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-15 04:26:18.254 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:26:18.294 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:18.300 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:20.309 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15T03:26:22.618Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15T03:26:22.619Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT1123.S9LZPw==
,2015-12-15 04:26:27.622 ThaliTest[982:1249382] jxcore: disconnect
,2015-12-15 04:26:27.623 ThaliTest[982:1249382] jxcore: disconnect: fail
2015-12-15T03:26:27.623Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:26:27.624Z SendDataConnector.js: Connect (retry co,unt 4) to peer Apple-Iphone6-1_PT1123.S9LZPw== with availability status: true
2015-12-15T03:26:27.624Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15T03:26:27.624Z SendDataConnector.js: do connect now
,2015-12-15 04:26:27.626 ThaliTest[982:1249382] jxcore: connect Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:27.627 ThaliTest[982:1249382] client: connect: unreachable Apple-Iphone6-1_PT1123.S9LZPw==
2015-12-15 04:26:27.627 ThaliTest[982:1249382] jxco,re: connect: fail: Peer unreachable
2015-12-15T03:26:27.627Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-15T03:26:27.628Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-15T03:26:27.631Z SendDataConnector.js: CLIENT Stop now
,2015-12-15 04:26:27.631 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:26:27.632 ThaliTest[982:1249382] jxcore: disconnect: fail
2015-12-15T03:26:27.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1123.S9LZPw==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:27.637Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:27.637Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15T03:26:27.638Z SendDataConnector.js: do connect now
,2015-12-15 04:26:27.639 ThaliTest[982:1249382] jxcore: connect Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:27.640 ThaliTest[982:1249382] client session: connect
2015-12-15 04:26:27.640 ThaliTest[982:1249382] client session: stateChange:0->1 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:27.965 ThaliTest[982:1249062] multipeer session: reset timer
,2015-12-15 04:26:27.966 ThaliTest[982:1249062] multipeer session: stop timer
,2015-12-15 04:26:27.966 ThaliTest[982:1249062] multipeer session: start timer: 0x16376970
,2015-12-15 04:26:27.967 ThaliTest[982:1249062] server session: connect
,2015-12-15 04:26:27.968 ThaliTest[982:1249062] server session: stateChange:0->1 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:27.979 ThaliTest[982:1249062] server: accepting invitation Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:28.199 ThaliTest[982:1249062] multipeer session: reset timer
,2015-12-15 04:26:28.200 ThaliTest[982:1249062] multipeer session: stop timer
,2015-12-15 04:26:28.200 ThaliTest[982:1249062] multipeer session: start timer: 0x16376970
,2015-12-15 04:26:28.201 ThaliTest[982:1249062] server session: connect
,2015-12-15 04:26:28.202 ThaliTest[982:1249062] server session: stateChange:0->1 Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:28.210 ThaliTest[982:1249062] server: accepting invitation Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:30.623 ThaliTest[982:1250051] server session: connected
,2015-12-15 04:26:30.624 ThaliTest[982:1250051] server session: stateChange:1->2 Apple-IpadAir2-1_PT7023
,2015-12-15 04:26:30.680 ThaliTest[982:1249062] server relay: connected (to port: 58955)
,2015-12-15T03:26:30.683Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 04:26:30.697 ThaliTest[982:1250107] client session: connected
,2015-12-15 04:26:30.697 ThaliTest[982:1250107] client session: stateChange:1->2 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:30.702 ThaliTest[982:1250107] client session: fireConnectCallback: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:26:30.702 ThaliTest[982:1250107] jxcore: connect: success
,2015-12-15T03:26:30.703Z SendDataConnector.js: CLIENT connected to 58967, error: null
,2015-12-15T03:26:30.704Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:30.709 ThaliTest[982:1249062] client: relay established
,2015-12-15 04:26:30.710 ThaliTest[982:1249062] client: new accepted socket: 0x164baac0
,2015-12-15T03:26:30.723Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:31.016Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-15T03:26:31.150Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-15T03:26:31.163Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T03:26:31.212Z SendDataTCPServer.js: TCP/IP server has received 21758 bytes of data
,2015-12-15 04:26:31.216 ThaliTest[982:1250107] server session: connected
2015-12-15 04:26:31.216 ThaliTest[982:1250107] server session: stateChange:1->2 Apple-Iphone5s-1_PT9749
,2015-12-15T03:26:31.218Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-15T03:26:31.218Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:31.219Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:31.219Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:31.220 ThaliTest[982:1249382] jxcore: disconnect
,2015-12-15 04:26:31.220 ThaliTest[982:1249382] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:31.221 ThaliTest[982:1249382] client session: disconnect
,2015-12-15 04:26:31.221 ThaliTest[982:1249382] client session: stateChange:2->0 Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:26:31.277 ThaliTest[982:1249062] server relay: connected (to port: 58955)
,2015-12-15 04:26:31.285 ThaliTest[982:1249382] jxcore: disconnect: success
,2015-12-15T03:26:31.285Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7023.h41t3A==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15T03:26:31.286Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15T03:26:31.287Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15T03:26:31.287Z SendDataConnector.js: do connect now
,2015-12-15 04:26:31.287 ThaliTest[982:1249382] jxcore: connect Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:31.288 ThaliTest[982:1249382] client session: connect
,2015-12-15 04:26:31.288 ThaliTest[982:1249382] client session: stateChange:0->1 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15T03:26:31.307Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15T03:26:31.313Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-15 04:26:31.365 ThaliTest[982:1250206] server session: not connected Apple-IpadAir2-1_PT7023
,2015-12-15T03:26:32.261Z SendDataTCPServer.js: TCP/IP server has received 6428 bytes of data
,2015-12-15T03:26:32.280Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-15T03:26:32.295Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-15T03:26:32.311Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-12-15T03:26:32.327Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-15T03:26:32.342Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-15T03:26:32.359Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-15 04:26:32.446 ThaliTest[982:1250206] server session: not connected Apple-Iphone5s-1_PT9749
,2015-12-15 04:26:33.967 ThaliTest[982:1250206] client session: connected
,2015-12-15 04:26:33.968 ThaliTest[982:1250206] client session: stateChange:1->2 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:33.985 ThaliTest[982:1250050] client session: fireConnectCallback: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:26:33.985 ThaliTest[982:1250050] jxcore: connect: success
,2015-12-15T03:26:33.986Z SendDataConnector.js: CLIENT connected to 58971, error: null
,2015-12-15T03:26:33.987Z SendDataConnector.js: CLIENT starting client 
,2015-12-15 04:26:33.991 ThaliTest[982:1249062] client: relay established
,2015-12-15 04:26:33.991 ThaliTest[982:1249062] client: new accepted socket: 0x164be060
,2015-12-15T03:26:34.001Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:34.380Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-15T03:26:34.416Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T03:26:34.428Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-15T03:26:34.479Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T03:26:34.479Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:34.479Z SendDataConnector.js: CLIENT Stop now
,2015-12-15T03:26:34.480Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:34.480 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:26:34.480 ThaliTest[982:1249382] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:26:34.480 ThaliTest[982:1249382] client session: disconnect
2015-12-15 04:26:34.481 ThaliTest[982:1249382] client session: stateChange:2->0 Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:26:34.484 ThaliTest[982:1249382] jxcore: disconnect: success
2015-12-15T03:26:34.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9749.OdNUWQ==
---- round done--------
startWithNextDevice
device[4]: App,le-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26:34.485Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26:34.485Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15T03:26,:34.485Z SendDataConnector.js: do connect now
2015-12-15 04:26:34.485 ThaliTest[982:1249382] jxcore: connect Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:34.486 ThaliTest[982:1249382] client session: connect
2015-12-15 04:26:34.486 ThaliTest[982:124,9382] client session: stateChange:0->1 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:37.336 ThaliTest[982:1250050] client session: connected
2015-12-15 04:26:37.337 ThaliTest[982:1250050] client session: stateChange:1->2 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:37.342 ThaliTest[982:1250050] client session: fireConnectCallback: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:37.343 ThaliTest[982:1250050] jxcore: connect: success
2015-12-15T03:26:37.345Z SendDataConnector.js: CLIENT connected to, 58974, error: null
2015-12-15T03:26:37.345Z SendDataConnector.js: CLIENT starting client 
2015-12-15 04:26:37.349 ThaliTest[982:1249062] client: relay established
2015-12-15 04:26:37.350 ThaliTest[982:1249062] client: new accepted socket: 0x16366a40
,2015-12-15T03:26:37.362Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-15T03:26:37.656Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-15T03:26:37.682Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-15T03:26:37.695Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-15T03:26:37.695Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-15T03:26:37.696Z SendDataConnector.js: CLIENT Stop now
2015-12-15T03:26:37.696Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:37.696 ThaliTest[982:1249382] jxcore: disconnect
2015-12-15 04:26:37.696 ThaliTest[982:1249382] client session: disconnectFromPeer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:26:37.696 ThaliTest[982:1249382] client session: disconnect,
2015-12-15 04:26:37.697 ThaliTest[982:1249382] client session: stateChange:2->0 Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:26:37.700 ThaliTest[982:1249382] jxcore: disconnect: success
2015-12-15T03:26:37.701Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9128.H9FQ7Q==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
,done, now sending data to server
,2015-12-15T03:26:37.704Z SendDataConnector.js: CLIENT Stop now
2015-12-15T03:26:37.704Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-15 04:26:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:27:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:27:28.236 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:27:28.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:27:28.238 ThaliTest[982:1249062] client: ,found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:27:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:27:58.239 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:27:58.243 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:27:59.444 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:28:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:28:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:28:58.235 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:28:58.235 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:28:58.239 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,Connected to the server!
,2015-12-15 04:29:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:29:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:29:58.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:29:58.238 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:29:58.240 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:30:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:30:28.239 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:30:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:30:32.392 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:30:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:30:58.239 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:30:58.239 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:30:58.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:31:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:31:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:31:58.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:31:58.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:31:58.243 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:32:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:32:28.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:32:28.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:32:28.796 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:32:58.201 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:32:58.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:32:58.241 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:32:58.242 ThaliTest[982:1249062] client: ,found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:33:22.884 ThaliTest[982:1249062] client: lost peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:33:22.884 ThaliTest[982:1249062] client session: onPeerLost: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-15 04:33:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:33:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:33:58.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:33:58.238 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:33:58.238 ThaliTest[982:1249062] client: ,found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9749.OdNUWQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-15 04:34:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:34:28.239 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:34:28.240 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:34:28.241 ThaliTest[982:1249062] client: ,found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:34:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:34:58.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:34:58.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:34:58.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:35:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:35:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:28.241 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:35:28.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:35:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:35:58.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:35:58.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:35:58.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:36:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:36:28.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:36:28.243 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:36:28.244 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:36:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:36:58.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:36:58.243 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:36:58.243 ThaliTest[982:1249062] client: ,found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:37:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:37:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:37:58.240 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:37:58.240 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:37:58.241 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:38:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:38:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:38:58.237 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:38:58.238 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:38:58.238 ThaliTest[982:1249062] client:, found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:39:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:39:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:39:28.241 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:39:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:39:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:40:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:40:28.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:40:28.240 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:40:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:40:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:40:58.238 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:40:58.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:40:58.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:41:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:41:28.241 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:41:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:41:28.242 ThaliTest[982:1249062] client:, found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:41:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:42:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:42:28.236 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:42:28.237 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:42:28.238 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:42:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:42:58.237 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:42:58.238 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:42:58.420 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:43:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:43:28.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:43:28.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:43:28.244 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:43:58.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:43:58.240 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:43:58.240 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:43:58.241 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:44:28.202 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:44:28.242 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:44:28.242 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:44:28.244 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:44:58.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:44:58.189 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:44:58.190 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:44:58.191 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:45:28.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:45:28.194 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:45:28.194 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:45:28.195 ThaliTest[982:1249062] client: ,found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:45:58.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:45:58.189 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:45:58.189 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:45:58.191 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:46:28.150 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:46:28.185 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
,2015-12-15 04:46:28.189 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:46:28.190 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:46:58.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:46:58.189 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:46:58.189 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
,2015-12-15 04:46:58.986 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:47:28.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:47:28.189 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:47:28.189 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==
2015-12-15 04:47:28.189 ThaliTest[982:1249062] client: ,found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
,2015-12-15 04:47:58.151 ThaliTest[982:1249062] multipeer session: restart
,2015-12-15 04:47:58.192 ThaliTest[982:1249062] client: found peer: Apple-Iphone5-1_PT9128.H9FQ7Q==
2015-12-15 04:47:58.192 ThaliTest[982:1249062] client: found peer: Apple-Iphone5s-1_PT9749.OdNUWQ==
2015-12-15 04:47:58.192 ThaliTest[982:1249062] client: found peer: Apple-IpadAir2-1_PT7023.h41t3A==

```
