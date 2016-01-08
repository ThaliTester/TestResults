#### Test 55431344e5dd625_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/38E1E90E-76A3-4849-9BD0-EA26D2D74E9A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/38E1E90E-76A3-4849-9BD0-EA26D2D74E9A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E000AEAF-BEDA-476D-91B5-528E5F21F7A2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49848"
,(lldb)     command script import "/tmp/38E1E90E-76A3-4849-9BD0-EA26D2D74E9A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 08:25:09.626 ThaliTest[1476:3196534] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3336B6F1-351D-4BBF-B3A4-E5D21FDBB6F5/Library/Cookies/Cookies.binarycookies
,2016-01-08 08:25:09.998 ThaliTest[1476:3196534] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 08:25:09.999 ThaliTest[1476:3196534] Multi-tasking -> Device: YES, App: YES
,2016-01-08 08:25:10.008 ThaliTest[1476:3196534] Unlimited access to network resources
,2016-01-08 08:25:10.022 ThaliTest[1476:3196534] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 08:25:19.030 ThaliTest[1476:3196534] Resetting plugins due to page load.
,2016-01-08 08:25:22.477 ThaliTest[1476:3196534] Finished load of: file:///var/mobile/Containers/Bundle/Application/E000AEAF-BEDA-476D-91B5-528E5F21F7A2/ThaliTest.app/www/index.html
,2016-01-08 08:25:22.664 ThaliTest[1476:3196534] JXcore Cordova plugin initializing
,2016-01-08 08:25:22.666 ThaliTest[1476:3196773] JXcore instance initializing
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
,2016-01-08 08:25:23.861 ThaliTest[1476:3196534] THREAD WARNING: ['JXcore'] took '73.740967' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 08:30:18.798 ThaliTest[1476:3196773] jxcore: startBroadcasting
,2016-01-08 08:30:18.821 ThaliTest[1476:3196773] server: starting Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:18.828 ThaliTest[1476:3196773] multipeer session: start timer: 0x16c5fb20
2016-01-08 08:30:18.831 ThaliTest[1476:3196773] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-08 08:30:18.831 ThaliTest[1476:3196773] jxcore: startB,roadcasting: success
StartBroadcasting started ok
,2016-01-08 08:30:19.851 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5-1.8yAUdA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.8yAUdA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,2016-01-08 08:30:20.047 ThaliTest[1476:3196534] client: found peer: Apple-IpadAir2-1.SM1CRQ==
,2016-01-08 08:30:20.527 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5s-1.NE8BAA==
,teardown
,testFindPeers stopped
2016-01-08 08:30:20.795 ThaliTest[1476:3196773] jxcore: stopBroadcasting
2016-01-08 08:30:20.795 ThaliTest[1476:3196773] THEMultipeerSession stopping peer
2016-01-08 08:30:20.795 ThaliTest[1476:3196773] multipeer session: stop timer
,2016-01-08 08:30:20.796 ThaliTest[1476:3196773] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 64219
,2016-01-08 08:30:20.827 ThaliTest[1476:3196773] jxcore: startBroadcasting
,2016-01-08 08:30:20.836 ThaliTest[1476:3196773] server: starting Apple-Iphone6-1.O1yvYA==
2016-01-08 08:30:20.837 ThaliTest[1476:3196773] multipeer session: start timer: 0x16c62a60
2016-01-08 08:30:20.837 ThaliTest[1476:3196773] THEMultipeerSession initialized peer Apple-Iphone6-1
2016-01-08 08:30:20.838 ThaliTest[1476:3196773] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2016-01-08T07:30:20.843Z SendDataTCPServer.js: TCP/IP server is bound to port: 64219
,2016-01-08 08:30:20.878 ThaliTest[1476:3196534] client: found peer: Apple-Iphone6-1.DpDJvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:20.884Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:20.879 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5-1.8yAUdA==
,2016-01-08 08:30:20.891 ThaliTest[1476:3196534] client: found peer: Apple-IpadAir2-1.SM1CRQ==
2016-01-08 08:30:20.892 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5s-1.NE8BAA==
,2016-01-08T07:30:20.897Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:20.899Z SendDataConnector.js: do connect now
,2016-01-08 08:30:20.901 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:20.902 ThaliTest[1476:3196773] client session: connect
,2016-01-08 08:30:20.903 ThaliTest[1476:3196773] client session: stateChange:0->1 Apple-Iphone6-1.DpDJvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 08:30:22.072 ThaliTest[1476:3196534] client: lost peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.072 ThaliTest[1476:3196534] client session: onPeerLost: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.072 ThaliTest[1476:3196534] client sessio,n: onLinkFailure: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.072 ThaliTest[1476:3196534] client session: disconnect
2016-01-08 08:30:22.073 ThaliTest[1476:3196534] client session: stateChange:1->0 Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.073 Thali,Test[1476:3196534] client session: fireConnectCallback: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.074 ThaliTest[1476:3196534] jxcore: connect: fail: Peer disconnected
2016-01-08 08:30:22.074 ThaliTest[1476:3196534] client: lost peer: Apple-IpadAir2-1.,SM1CRQ==
2016-01-08 08:30:22.074 ThaliTest[1476:3196534] client session: onPeerLost: Apple-IpadAir2-1.SM1CRQ==
2016-01-08T07:30:22.076Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T07:30:22.076Z SendDataConnector.js: ,CLIENT Can not Connect: Peer disconnected
,2016-01-08T07:30:22.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 08:30:22.116 ThaliTest[1476:3196534] client: lost peer: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:22.116 ThaliTest[1476:3196534] client session: onPeerLost: Apple-Iphone5s-1.NE8BAA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 08:30:22.470 ThaliTest[1476:3196534] client: lost peer: Apple-Iphone5-1.8yAUdA==
2016-01-08 08:30:22.471 ThaliTest[1476:3196534] client session: onPeerLost: Apple-Iphone5-1.8yAUdA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 08:30:22.486 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5-1.kpUZpA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kpUZpA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:22.491 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5s-1.WrRjQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.WrRjQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:22.980 ThaliTest[1476:3196534] client: found peer: Apple-IpadAir2-1.5QwW9A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.5QwW9A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T07:30:27.082Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:27.083Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.095 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:30:32.095 ThaliTest[1476:3196773] jxcore: disconnect: fail
2016-01-08T07:30:32.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:32.096Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:32.096Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:32.097Z SendDataConnector.js: do connect now
,2016-01-08 08:30:32.098 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:32.099 ThaliTest[1476:3196773] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:32.099 ThaliTest[1476:3196773] jxcore: connect,: fail: Peer unreachable
2016-01-08T07:30:32.100Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:32.100Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:32.101Z SendDataConnector.js:, tryAgain afer: 5000 ms.
,2016-01-08T07:30:37.106Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:37.106Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:42.108 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:30:42.109 ThaliTest[1476:3196773] jxcore: disconnect: fail
2016-01-08T07:30:42.109Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:42.110Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:42.110Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:42.11,0Z SendDataConnector.js: do connect now
,2016-01-08 08:30:42.111 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:42.112 ThaliTest[1476:3196773] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:42.113 ThaliTest[1476:3196773] jxcore: connect: fail: Peer unreachable
2016-01-08T07:30:42.114Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T07:30:42.114Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:42.114Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:47.127Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:47.127Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:50.864 ThaliTest[1476:3196534] multipeer session: restart
,2016-01-08 08:30:50.904 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:30:50.904 ThaliTest[1476:3196534] client: found peer: Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:30:50.909 ThaliTest[1476:3196534] client: found peer: Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:30:52.131 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:30:52.132 ThaliTest[1476:3196773] jxcore: disconnect: fail
2016-01-08T07:30:52.132Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:52.133Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:52.133Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:52.133Z SendDataConnector.js: do connect now
,2016-01-08 08:30:52.134 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:52.135 ThaliTest[1476:3196773] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:52.136 ThaliTest[1476:3196773] jxcore: connect,: fail: Peer unreachable
2016-01-08T07:30:52.136Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:52.136Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:52.137Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:57.145Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:57.146Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:31:02.156 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:31:02.157 ThaliTest[1476:3196773] jxcore: disconnect: fail
2016-01-08T07:31:02.157Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:31:02.158Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:31:02.158Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:31:02.15,8Z SendDataConnector.js: do connect now
,2016-01-08 08:31:02.159 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:31:02.160 ThaliTest[1476:3196773] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:31:02.161 ThaliTest[1476:3196773] jxcore: connect: fail: Peer unreachable
2016-01-08T07:31:02.161Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:31:02.161Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T07:31:02.164Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 08:31:02.165 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:31:02.166 ThaliTest[1476:3196773] jxcore: disconnect: fail
2016-01-08T07:31:02.166Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.170Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.171Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.172Z SendDataConnector.js: do connect now
,2016-01-08 08:31:02.173 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:02.173 ThaliTest[1476:3196773] client session: connect
2016-01-08 08:31:02.174 ThaliTest[1476:3196773] client session: stateChange:0->1 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:05.208 ThaliTest[1476:3197371] client session: connected
,2016-01-08 08:31:05.209 ThaliTest[1476:3197371] client session: stateChange:1->2 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:05.855 ThaliTest[1476:3197372] client session: fireConnectCallback: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:05.856 ThaliTest[1476:3197372] jxcore: connect: success
2016-01-08T07:31:05.857Z SendDataConnector.js: CLIENT connected to 6422,6, error: null
,2016-01-08T07:31:05.858Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:05.862 ThaliTest[1476:3196534] client: relay established
2016-01-08 08:31:05.862 ThaliTest[1476:3196534] client: new accepted socket: 0x16c78710
,2016-01-08T07:31:05.878Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:06.459Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T07:31:06.508Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T07:31:06.521Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T07:31:06.594Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T07:31:06.703Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:06.704Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T07:31:06.704Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:06.705Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:06.706 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:31:06.707 ThaliTest[1476:3196773] client session: disconnectFromPeer: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:06.707 ThaliTest[1476:3196773] client session: disconnect
2016-01-08 08:31:06.707 ThaliTest[1476:3196773] client session: stateChange:2->0 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:06.713 ThaliTest[1476:3196773] jxcore: disconnect: success
2016-01-08T07:31:06.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kpUZpA==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipho,ne5s-1.WrRjQQ==
2016-01-08T07:31:06.714Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:06.714Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:06.714Z SendDataConnecto,r.js: do connect now
2016-01-08 08:31:06.715 ThaliTest[1476:3196773] jxcore: connect Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:06.715 ThaliTest[1476:3196773] client session: connect
2016-01-08 08:31:06.715 ThaliTest[1476:3196773] client session: stateC,hange:0->1 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:08.605 ThaliTest[1476:3196534] multipeer session: reset timer
2016-01-08 08:31:08.606 ThaliTest[1476:3196534] multipeer session: stop timer
2016-01-08 08:31:08.606 ThaliTest[1476:3196534] multipeer session: start timer: 0x16c62a60
2016-01-08 08:31:08.607 ThaliTest[1476:3196534] server session: connect
2016-01-08 08:31:08.607 ThaliTest[1476:3196534] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 08:31:08.618 ThaliTest[1476:3196534] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 08:31:08.704 ThaliTest[1476:3196534] multipeer session: reset timer
2016-01-08 08:31:08.704 ThaliTest[1476:3196534] multipeer session: stop timer
2016-01-08 08:31:08.704 ThaliTest[1476:3196534] multipeer session: start timer: 0x16c62a60
2016-01-08 08:31:08.705 ThaliTest[1476:3196534] server session: connect
2016-01-08 08:31:08.705 ThaliTest[1476:3196534] server session: stateChange:0->1 Apple-Iphone5s-1
2016-01-08 08:31:08.715 ThaliTest[1476:3196534] server: accepting invitation Apple-Iphone,5s-1
,2016-01-08 08:31:08.746 ThaliTest[1476:3196534] multipeer session: reset timer
,2016-01-08 08:31:08.748 ThaliTest[1476:3196534] multipeer session: stop timer
,2016-01-08 08:31:08.752 ThaliTest[1476:3196534] multipeer session: start timer: 0x16c62a60
,2016-01-08 08:31:08.753 ThaliTest[1476:3196534] server session: connect
2016-01-08 08:31:08.755 ThaliTest[1476:3196534] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 08:31:08.783 ThaliTest[1476:3196534] server: accepting invitation Apple-Iphone5-1
,2016-01-08 08:31:10.640 ThaliTest[1476:3197371] client session: connected
2016-01-08 08:31:10.641 ThaliTest[1476:3197371] client session: stateChange:1->2 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:10.671 ThaliTest[1476:3197382] client session: fireConnectCallback: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:10.671 ThaliTest[1476:3197382] jxcore: connect: success
,2016-01-08T07:31:10.673Z SendDataConnector.js: CLIENT connected to 64229, error: null
,2016-01-08T07:31:10.673Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:10.677 ThaliTest[1476:3196534] client: relay established
2016-01-08 08:31:10.677 ThaliTest[1476:3196534] client: new accepted socket: 0x16c8a6f0
,2016-01-08T07:31:10.690Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:11.180Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T07:31:11.363Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08 08:31:11.384 ThaliTest[1476:3197371] server session: connected
2016-01-08 08:31:11.384 ThaliTest[1476:3197371] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08T07:31:11.426Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:11.427Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T07:31:11.428Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:11.428Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:11.429 ThaliTest[1476:3196773] jxcore: disconnect
,2016-01-08 08:31:11.431 ThaliTest[1476:3196773] client session: disconnectFromPeer: Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:11.432 ThaliTest[1476:3196773] client session: disconnect
2016-01-08 08:31:11.433 ThaliTest[1476:3196534] server relay: connected (to port: 64219)
,2016-01-08 08:31:11.433 ThaliTest[1476:3196773] client session: stateChange:2->0 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:11.493 ThaliTest[1476:3197382] server session: connected
2016-01-08 08:31:11.493 ThaliTest[1476:3197382] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 08:31:11.498 ThaliTest[1476:3196773] jxcore: disconnect: success
,2016-01-08T07:31:11.499Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.WrRjQQ==
---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:11.500Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:11.501Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:11.501Z SendDataConnector.js: do connect now
,2016-01-08 08:31:11.502 ThaliTest[1476:3196773] jxcore: connect Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:11.502 ThaliTest[1476:3196773] client session: connect
,2016-01-08 08:31:11.503 ThaliTest[1476:3196773] client session: stateChange:0->1 Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:11.526Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 08:31:11.626 ThaliTest[1476:3196534] server relay: connected (to port: 64219)
2016-01-08T07:31:11.630Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:12.019Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T07:31:12.033Z SendDataTCPServer.js: TCP/IP server has received 20805 bytes of data
,2016-01-08T07:31:12.050Z SendDataTCPServer.js: TCP/IP server has received 36135 bytes of data
,2016-01-08T07:31:12.067Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-08T07:31:12.096Z SendDataTCPServer.js: TCP/IP server has received 49731 bytes of data
,2016-01-08T07:31:12.114Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-08T07:31:12.133Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-08T07:31:12.146Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T07:31:12.164Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T07:31:12.180Z SendDataTCPServer.js: TCP/IP server has received 93075 bytes of data
,2016-01-08T07:31:12.279Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:12.289 ThaliTest[1476:3197370] server session: connected
2016-01-08 08:31:12.291 ThaliTest[1476:3197370] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 08:31:12.296 ThaliTest[1476:3196534] server relay: connected (to port: 64219)
,2016-01-08T07:31:12.309Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 08:31:12.351 ThaliTest[1476:3197370] server session: not connected Apple-Iphone5s-1
,2016-01-08T07:31:12.421Z SendDataTCPServer.js: TCP/IP server has received 5475 bytes of data
,2016-01-08T07:31:12.473Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-08T07:31:12.489Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-08T07:31:12.503Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-08T07:31:12.518Z SendDataTCPServer.js: TCP/IP server has received 45990 bytes of data
,2016-01-08T07:31:12.545Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-08T07:31:12.559Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-08T07:31:12.620Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-08T07:31:12.764Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-08T07:31:12.807Z SendDataTCPServer.js: TCP/IP server has received 51465 bytes of data
,2016-01-08T07:31:12.841Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-08T07:31:12.846Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-08T07:31:12.859Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-08T07:31:12.874Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T07:31:12.875Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-08T07:31:12.886Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-08T07:31:12.900Z SendDataTCPServer.js: TCP/IP server has received 93075 bytes of data
,2016-01-08T07:31:12.937Z SendDataTCPServer.js: TCP/IP server has received 99645 bytes of data
,2016-01-08 08:31:12.941 ThaliTest[1476:3197372] server session: not connected Apple-Iphone5-1
,2016-01-08T07:31:12.950Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:13.265 ThaliTest[1476:3197372] server session: not connected Apple-IpadAir2-1
,2016-01-08 08:31:15.431 ThaliTest[1476:3197372] client session: connected
,2016-01-08 08:31:15.431 ThaliTest[1476:3197372] client session: stateChange:1->2 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:15.449 ThaliTest[1476:3197383] client session: fireConnectCallback: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:15.449 ThaliTest[1476:3197383] jxcore: connect: success
2016-01-08T07:31:15.450Z SendDataConnector.js: CLIENT connected to 64235, error: null
2016-01-08T07:31:15.451Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:15.455 ThaliTest[1476:3196534] client: relay established
2016-01-08 08:31:15.455 ThaliTest[1476:3196534] client: new accepted socket: 0x16c9bb70
,2016-01-08T07:31:15.467Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:16.013Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T07:31:16.027Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T07:31:16.075Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T07:31:16.147Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:16.147Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T07:31:16.148Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:16.148Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:16.149 ThaliTest[1476:3196773] jxcore: disconnect
2016-01-08 08:31:16.149 ThaliTest[1476:3196773] client session: disconnectFromPeer: Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:16.150 ThaliTest[1476:3196773] client session: disconnect
,2016-01-08 08:31:16.150 ThaliTest[1476:3196773] client session: stateChange:2->0 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:16.217 ThaliTest[1476:3196773] jxcore: disconnect: success
,2016-01-08T07:31:16.217Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.5QwW9A==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T07:31:16.236Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:16.236Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-08 08:31:17.337 ThaliTest[1476:3196773] jxcore: stopBroadcasting
,2016-01-08 08:31:17.338 ThaliTest[1476:3196773] THEMultipeerSession stopping peer
,2016-01-08 08:31:17.339 ThaliTest[1476:3196773] multipeer session: stop timer
2016-01-08 08:31:17.340 ThaliTest[1476:3196773] server session: disconnect
2016-01-08 08:31:17.340 ThaliTest[1476:3196773] server session: stateChange:2->0 Apple-Iphone5-1
201,6-01-08 08:31:17.348 ThaliTest[1476:3196773] server session: disconnect
2016-01-08 08:31:17.348 ThaliTest[1476:3196773] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 08:31:17.360 ThaliTest[1476:3196773] server session: disconnect
,2016-01-08 08:31:17.360 ThaliTest[1476:3196773] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 08:31:17.393 ThaliTest[1476:3196773] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-08T07:31:17.420Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.424Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.425Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.426Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
