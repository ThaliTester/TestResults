#### Test 552541413820a6d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2AE108D8-F545-4FF4-A372-9B8F72D7D191/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2AE108D8-F545-4FF4-A372-9B8F72D7D191/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/49F9A9FF-4BAA-425A-80AF-37FD41354F5B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49264"
,(lldb)     command script import "/tmp/2AE108D8-F545-4FF4-A372-9B8F72D7D191/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-06 20:48:58.215 ThaliTest[1012:3303539] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FD72057F-5804-4375-BE78-FB21C79F22C6/Library/Cookies/Cookies.binarycookies
,2016-01-06 20:48:58.331 ThaliTest[1012:3303539] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-06 20:48:58.332 ThaliTest[1012:3303539] Multi-tasking -> Device: YES, App: YES
,2016-01-06 20:48:58.337 ThaliTest[1012:3303539] Unlimited access to network resources
,2016-01-06 20:48:58.352 ThaliTest[1012:3303539] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-06 20:49:09.314 ThaliTest[1012:3303539] Resetting plugins due to page load.
,2016-01-06 20:49:12.966 ThaliTest[1012:3303539] Finished load of: file:///var/mobile/Containers/Bundle/Application/49F9A9FF-4BAA-425A-80AF-37FD41354F5B/ThaliTest.app/www/index.html
,2016-01-06 20:49:13.177 ThaliTest[1012:3303539] JXcore Cordova plugin initializing
,2016-01-06 20:49:13.180 ThaliTest[1012:3303723] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2016-01-06 20:49:15.600 ThaliTest[1012:3303539] THREAD WARNING: ['JXcore'] took '156.793213' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-06 20:57:02.422 ThaliTest[1012:3303723] jxcore: startBroadcasting
,2016-01-06 20:57:02.437 ThaliTest[1012:3303723] server: starting Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:02.438 ThaliTest[1012:3303723] multipeer session: start timer: 0x1b441a30
2016-01-06 20:57:02.439 ThaliTest[1012:3303723] THEMultipeerSession initialized peer Apple-Iphone5-1_PT2360
2016-01-06 20:57:02.439 ThaliTest[1012:3303723] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-06 20:57:03.564 ThaliTest[1012:3303539] client: found peer: Apple-IpadAir2-1_PT6789.T0JZzA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.T0JZzA==","peerName":"(null)","peerAvailable":true}]
2016-01-06 20:57:03.567 ThaliTes,t[1012:3303539] client: found peer: Apple-Iphone6-1_PT9564.cvfn7A==
Found peer : Apple-IpadAir2-1_PT6789.T0JZzA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-06 20:57:10.931 ThaliTest[1012:3303539] client: found peer: Apple-Iphone5s-1_PT1776.pROaFQ==
,2016-01-06 20:57:12.598 ThaliTest[1012:3303539] client: lost peer: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:12.598 ThaliTest[1012:3303539] client session: onPeerLost: Apple-IpadAir2-1_PT6789.T0JZzA==
2016-01-06 20:57:12.598 ThaliTest[1012:330353,9] client: lost peer: Apple-Iphone5s-1_PT1776.pROaFQ==
2016-01-06 20:57:12.598 ThaliTest[1012:3303539] client session: onPeerLost: Apple-Iphone5s-1_PT1776.pROaFQ==
,2016-01-06 20:57:12.955 ThaliTest[1012:3303539] client: lost peer: Apple-Iphone6-1_PT9564.cvfn7A==
2016-01-06 20:57:12.957 ThaliTest[1012:3303539] client session: onPeerLost: Apple-Iphone6-1_PT9564.cvfn7A==
,2016-01-06 20:57:12.958 ThaliTest[1012:3303539] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:12.994 ThaliTest[1012:3303539] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:13.002 ThaliTest[1012:3303539] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:57:13.248 ThaliTest[1012:3303539] multipeer session: reset timer
2016-01-06 20:57:13.248 ThaliTest[1012:3303539] multipeer session: stop timer
2016-01-06 20:57:13.248 ThaliTest[1012:3303539] multipeer session: start timer: 0x1b441a30
2016-01-06 20:57:13.248 ThaliTest[1012:3303539] server session: connect
2016-01-06 20:57:13.248 ThaliTest[1012:3303539] server session: stateChange:0->1 Apple-Iphone5s-1_PT1776
,2016-01-06 20:57:13.255 ThaliTest[1012:3303539] server: accepting invitation Apple-Iphone5s-1_PT1776
,teardown
,testFindPeers stopped
,2016-01-06 20:57:14.856 ThaliTest[1012:3303723] jxcore: stopBroadcasting
2016-01-06 20:57:14.857 ThaliTest[1012:3303723] THEMultipeerSession stopping peer
2016-01-06 20:57:14.857 ThaliTest[1012:3303723] multipeer session: stop timer
2016-01-06 20:57:14.857 ThaliTest[1012:3303723] server session: disconnect
2016-01-06 20:57:14.857 ThaliTest[1012:3303723] server session: stateChange:1->0 Apple-Iphone5s-1_PT1776
,2016-01-06 20:57:14.949 ThaliTest[1012:3303723] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 64697
,2016-01-06 20:57:14.965 ThaliTest[1012:3303723] jxcore: startBroadcasting
,2016-01-06 20:57:14.967 ThaliTest[1012:3303723] server: starting Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:57:14.968 ThaliTest[1012:3303723] multipeer session: start timer: 0x1b451680
2016-01-06 20:57:14.969 ThaliTest[1012:3303723] THEMultipeerSessio,n initialized peer Apple-Iphone5-1_PT2360
2016-01-06 20:57:14.969 ThaliTest[1012:3303723] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-06T19:57:14.972Z SendDataTCPServer.js: TCP/IP server is bound to port: 64697
,2016-01-06 20:57:15.001 ThaliTest[1012:3303539] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:15.001 ThaliTest[1012:3303539] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:15.002 ThaliTest[1012:3303539] clien,t: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.iuO8Uw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06T19:57:15.006Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06T19:57:15.006Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-,1_PT9564.iuO8Uw==
2016-01-06T19:57:15.008Z SendDataConnector.js: do connect now
2016-01-06 20:57:15.008 ThaliTest[1012:3303723] jxcore: connect Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:15.009 ThaliTest[1012:3303723] client session: connect
2016,-01-06 20:57:15.009 ThaliTest[1012:3303723] client session: stateChange:0->1 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:15.018 ThaliTest[1012:3303539] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.hQhn/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)",,"peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1776.mp8cwQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:15.998 ThaliTest[1012:3303539] client: lost peer: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:15.998 ThaliTest[1012:3303539] client session: onPeerLost: Apple-Iphone5-1_PT2360.KoeEnA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-06 20:57:17.852 ThaliTest[1012:3305266] client session: connected
2016-01-06 20:57:17.853 ThaliTest[1012:3305266] client session: stateChange:1->2 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:17.883 ThaliTest[1012:3305310] client session: fireConnectCallback: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:17.883 ThaliTest[1012:3305310] jxcore: connect: success
2016-01-06T19:57:17.884Z SendDataConnector.js: CLIENT connected to 64700, error: null
2016-01-06T19:57:17.884Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:57:17.888 ThaliTest[1012:3303539] client: relay established
2016-01-06 20:57:17.888 ThaliTest[1012:3303539] client: new accepted socket: 0x1b456d70
,2016-01-06T19:57:17.901Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:57:18.505Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-06T19:57:18.519Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:57:18.520Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:57:18.523Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:57:18.523Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:57:18.524 ThaliTest[1012:3303723] jxcore: disconnect
2016-01-06 20:57:18.525 ThaliTest[1012:3303723] client session: disconnectFromPeer: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:18.525 ThaliTest[1012:3303723] client session: disconnect
2016-01-06 20:57:18.525 ThaliTest[1012:3303723] client session: stateChange:2->0 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:18.535 ThaliTest[1012:3303723] jxcore: disconnect: success
2016-01-06T19:57:18.536Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.iuO8Uw==
---- round done--------
startWithNextDevice
device[2]: App,le-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19:57:18.537Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19:57:18.538Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19,:57:18.538Z SendDataConnector.js: do connect now
2016-01-06 20:57:18.538 ThaliTest[1012:3303723] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:18.539 ThaliTest[1012:3303723] client session: connect
2016-01-06 20:57:18.539 ThaliTest[1,012:3303723] client session: stateChange:0->1 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:21.981 ThaliTest[1012:3305314] client session: connected
,2016-01-06 20:57:21.981 ThaliTest[1012:3305314] client session: stateChange:1->2 Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:21.984 ThaliTest[1012:3305314] client session: fireConnectCallback: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:21.984 ThaliTest[1012:3305314] jxcore: connect: success
,2016-01-06T19:57:21.985Z SendDataConnector.js: CLIENT connected to 64703, error: null
2016-01-06T19:57:21.986Z SendDataConnector.js: CLIENT starting client 
2016-01-06 20:57:21.988 ThaliTest[1012:3303539] client: relay established
2016-01-06 20:57:21.989 ThaliTest[1012:3303539] client: new accepted socket: 0x1b456d70
,2016-01-06T19:57:22.002Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:57:22.537Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:57:22.551Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-06T19:57:22.702Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:57:22.702Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:57:22.703Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:57:22.703Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:57:22.704 ThaliTest[1012:3303723] jxcore: disconnect
2016-01-06 20:57:22.704 ThaliTest[1012:3303723] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:22.705 ThaliTest[1012:3303723] client session: disconnect
2016-01-06 20:57:22.705 ThaliTest[1012:3303723] client session: stateChange:2->0 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:57:22.713 ThaliTest[1012:3303723] jxcore: disconnect: success
2016-01-06T19:57:22.713Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn/g==
---- round done--------
startWithNextDevice
device[3]: Ap,ple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T19:57:22.714Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T19:57:22.715Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06T1,9:57:22.715Z SendDataConnector.js: do connect now
2016-01-06 20:57:22.715 ThaliTest[1012:3303723] jxcore: connect Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:22.715 ThaliTest[1012:3303723] client session: connect
,2016-01-06 20:57:22.716 ThaliTest[1012:3303723] client session: stateChange:0->1 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:57:25.714 ThaliTest[1012:3305310] client session: connected
2016-01-06 20:57:25.714 ThaliTest[1012:3305310] client session: stateChange:1->2 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:57:25.746 ThaliTest[1012:3305266] client session: fireConnectCallback: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:25.747 ThaliTest[1012:3305266] jxcore: connect: success
2016-01-06T19:57:25.747Z SendDataConnector.js: CLIENT connected, to 64706, error: null
2016-01-06T19:57:25.748Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:57:25.750 ThaliTest[1012:3303539] client: relay established
2016-01-06 20:57:25.751 ThaliTest[1012:3303539] client: new accepted socket: 0x1b4566e0
,2016-01-06T19:57:25.763Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:57:26.328Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-06T19:57:26.343Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-06T19:57:26.358Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-06T19:57:26.386Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-06T19:57:26.400Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-06T19:57:26.415Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:57:26.415Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:57:26.417Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:57:26.417Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:57:26.419 ThaliTest[1012:3303723] jxcore: disconnect
2016-01-06 20:57:26.419 ThaliTest[1012:3303723] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:26.419 ThaliTest[1012:3303723] client session: disconnect
2016-01-06 20:57:26.419 ThaliTest[1012:3303723] client session: stateChange:2->0 Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:57:26.427 ThaliTest[1012:3303723] jxcore: disconnect: success
2016-01-06T19:57:26.428Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1776.mp8cwQ==
---- round done--------
startWithNextDevice
,2016-01-06 20:57:44.970 ThaliTest[1012:3303539] multipeer session: restart
,2016-01-06 20:57:45.002 ThaliTest[1012:3303539] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:45.002 ThaliTest[1012:3303539] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:57:45.002 ThaliTest[1012:3303539] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:00.810 ThaliTest[1012:3303539] multipeer session: reset timer
2016-01-06 20:58:00.810 ThaliTest[1012:3303539] multipeer session: stop timer
2016-01-06 20:58:00.810 ThaliTest[1012:3303539] multipeer session: start timer: 0x1b451680
2016-,01-06 20:58:00.810 ThaliTest[1012:3303539] server session: connect
2016-01-06 20:58:00.810 ThaliTest[1012:3303539] server session: stateChange:0->1 Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:00.817 ThaliTest[1012:3303539] server: accepting invitation Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:03.559 ThaliTest[1012:3303539] multipeer session: reset timer
2016-01-06 20:58:03.560 ThaliTest[1012:3303539] multipeer session: stop timer
2016-01-06 20:58:03.560 ThaliTest[1012:3303539] multipeer session: start timer: 0x1b451680
2016-,01-06 20:58:03.560 ThaliTest[1012:3303539] server session: connect
2016-01-06 20:58:03.560 ThaliTest[1012:3303539] server session: stateChange:0->1 Apple-Iphone5s-1_PT1776
2016-01-06 20:58:03.566 ThaliTest[1012:3303539] server: accepting invitation Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:03.951 ThaliTest[1012:3305445] server session: connected
2016-01-06 20:58:03.951 ThaliTest[1012:3305445] server session: stateChange:1->2 Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:03.958 ThaliTest[1012:3303539] server relay: connected (to port: 64697)
,2016-01-06T19:58:03.967Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:04.380Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-06T19:58:04.397Z SendDataTCPServer.js: TCP/IP server has received 58704 bytes of data
,2016-01-06T19:58:04.412Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-06T19:58:04.428Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:04.458 ThaliTest[1012:3305457] server session: not connected Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:14.784 ThaliTest[1012:3305456] server session: not connected Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:22.194 ThaliTest[1012:3303539] client: lost peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
2016-01-06 20:58:22.194 ThaliTest[1012:3303539] client session: onPeerLost: Apple-Iphone5s-1_PT1776.mp8cwQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-Iphone5s-1_PT1776.mp8cwQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2016-01-06 20:58:23.999 ThaliTest[1012:3303539] client: found peer: Apple-Iphone5s-1_PT1776.mp8cwQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1776.mp8cwQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2016-01-06 20:58:25.053 ThaliTest[1012:3303539] multipeer session: reset timer
2016-01-06 20:58:25.053 ThaliTest[1012:3303539] multipeer session: stop timer
2016-01-06 20:58:25.053 ThaliTest[1012:3303539] multipeer session: start timer: 0x1b451680
2016-,01-06 20:58:25.054 ThaliTest[1012:3303539] server: disconnecting to refresh session (Apple-Iphone5s-1_PT1776)
2016-01-06 20:58:25.054 ThaliTest[1012:3303539] server session: disconnect
2016-01-06 20:58:25.054 ThaliTest[1012:3303539] server session: state,Change:1->0 Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:25.109 ThaliTest[1012:3303539] server session: connect
2016-01-06 20:58:25.109 ThaliTest[1012:3303539] server session: stateChange:0->1 Apple-Iphone5s-1_PT1776
2016-01-06 20:58:25.115 ThaliTest[1012:3303539] server: accepting invitation Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:28.065 ThaliTest[1012:3305501] server session: connected
2016-01-06 20:58:28.066 ThaliTest[1012:3305501] server session: stateChange:1->2 Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:28.090 ThaliTest[1012:3303539] server relay: connected (to port: 64697)
,2016-01-06T19:58:28.101Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:28.339Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-06T19:58:28.354Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-06T19:58:28.556Z SendDataTCPServer.js: TCP/IP server has received 37088 bytes of data
,2016-01-06T19:58:28.570Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-06T19:58:28.584Z SendDataTCPServer.js: TCP/IP server has received 87316 bytes of data
,2016-01-06T19:58:28.599Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:28.645 ThaliTest[1012:3305501] server session: not connected Apple-Iphone5s-1_PT1776
,2016-01-06 20:58:40.710 ThaliTest[1012:3303539] multipeer session: reset timer
2016-01-06 20:58:40.710 ThaliTest[1012:3303539] multipeer session: stop timer
2016-01-06 20:58:40.710 ThaliTest[1012:3303539] multipeer session: start timer: 0x1b451680
2016-01-06 20:58:40.711 ThaliTest[1012:3303539] server session: connect
2016-01-06 20:58:40.711 ThaliTest[1012:3303539] server session: stateChange:0->1 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:40.717 ThaliTest[1012:3303539] server: accepting invitation Apple-Iphone6-1_PT9564
,2016-01-06 20:58:43.286 ThaliTest[1012:3305540] server session: connected
2016-01-06 20:58:43.286 ThaliTest[1012:3305540] server session: stateChange:1->2 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:43.306 ThaliTest[1012:3303539] server relay: connected (to port: 64697)
,2016-01-06T19:58:43.316Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:43.753Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-06T19:58:43.769Z SendDataTCPServer.js: TCP/IP server has received 43658 bytes of data
,2016-01-06T19:58:43.785Z SendDataTCPServer.js: TCP/IP server has received 74176 bytes of data
,2016-01-06T19:58:43.801Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:43.837 ThaliTest[1012:3305503] server session: not connected Apple-Iphone6-1_PT9564
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2016-01-06T19:58:54.996Z SendDataConnector.js: CLIENT Stop now
,teardown
,testSendData stopped
,2016-01-06 20:59:02.501 ThaliTest[1012:3303723] jxcore: stopBroadcasting
2016-01-06 20:59:02.501 ThaliTest[1012:3303723] THEMultipeerSession stopping peer
2016-01-06 20:59:02.501 ThaliTest[1012:3303723] multipeer session: stop timer
2016-01-06 20:59:02.,502 ThaliTest[1012:3303723] server session: disconnect
2016-01-06 20:59:02.502 ThaliTest[1012:3303723] server session: stateChange:2->0 Apple-Iphone5s-1_PT1776
,2016-01-06 20:59:02.509 ThaliTest[1012:3303723] server session: disconnect
2016-01-06 20:59:02.510 ThaliTest[1012:3303723] server session: stateChange:2->0 Apple-Iphone6-1_PT9564
2016-01-06 20:59:02.514 ThaliTest[1012:3303723] server session: disconnect,
2016-01-06 20:59:02.514 ThaliTest[1012:3303723] server session: stateChange:2->0 Apple-IpadAir2-1_PT6789
2016-01-06 20:59:02.520 ThaliTest[1012:3303723] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-06T19:59:02.539Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-06T19:59:02.541Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-06T19:59:02.542Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-06T19:59:02.542Z SendDataTCPServer.,js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
