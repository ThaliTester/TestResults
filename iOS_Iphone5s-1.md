#### Test 552541413820a6d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/2A199E95-A6BA-45B7-878B-531B1EEE016B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2A199E95-A6BA-45B7-878B-531B1EEE016B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/552541413820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/806C7871-BC3E-4060-AC28-0DA14E8D1BAA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49301"
,(lldb)     command script import "/tmp/2A199E95-A6BA-45B7-878B-531B1EEE016B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-06 20:50:33.269 ThaliTest[1378:2952065] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/79427509-72DA-4301-9AE7-FEE10A587FA8/Library/Cookies/Cookies.binarycookies
,2016-01-06 20:50:33.705 ThaliTest[1378:2952065] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-06 20:50:33.707 ThaliTest[1378:2952065] Multi-tasking -> Device: YES, App: YES
,2016-01-06 20:50:33.717 ThaliTest[1378:2952065] Unlimited access to network resources
,2016-01-06 20:50:33.728 ThaliTest[1378:2952065] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-06 20:50:42.657 ThaliTest[1378:2952065] Resetting plugins due to page load.
,2016-01-06 20:50:46.719 ThaliTest[1378:2952065] Finished load of: file:///var/mobile/Containers/Bundle/Application/806C7871-BC3E-4060-AC28-0DA14E8D1BAA/ThaliTest.app/www/index.html
,2016-01-06 20:50:46.922 ThaliTest[1378:2952065] JXcore Cordova plugin initializing
,2016-01-06 20:50:46.923 ThaliTest[1378:2952317] JXcore instance initializing
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
,2016-01-06 20:50:48.221 ThaliTest[1378:2952065] THREAD WARNING: ['JXcore'] took '94.342041' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-06 20:57:02.922 ThaliTest[1378:2952317] jxcore: startBroadcasting
,2016-01-06 20:57:02.941 ThaliTest[1378:2952317] server: starting Apple-Iphone5s-1_PT1776.pROaFQ==
2016-01-06 20:57:02.943 ThaliTest[1378:2952317] multipeer session: start timer: 0x15b7a9e0
2016-01-06 20:57:02.943 ThaliTest[1378:2952317] THEMultipeerSessi,on initialized peer Apple-Iphone5s-1_PT1776
2016-01-06 20:57:02.944 ThaliTest[1378:2952317] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-06 20:57:11.146 ThaliTest[1378:2952065] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT2360.KoeEnA==, peerAvailable: true
weAreDoneNow
done, now sending data to server
2016-01-06 20:57:11.152 ThaliTest[1378:2952065] client: found peer: Apple-IpadAir2-1_PT6789.T0JZzA==
,teardown
,testFindPeers stopped
,2016-01-06 20:57:11.449 ThaliTest[1378:2952317] jxcore: stopBroadcasting
2016-01-06 20:57:11.450 ThaliTest[1378:2952317] THEMultipeerSession stopping peer
2016-01-06 20:57:11.450 ThaliTest[1378:2952317] multipeer session: stop timer
2016-01-06 20:57:11.,451 ThaliTest[1378:2952317] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 55676
,2016-01-06 20:57:11.968 ThaliTest[1378:2952317] jxcore: startBroadcasting
,2016-01-06 20:57:11.973 ThaliTest[1378:2952317] server: starting Apple-Iphone5s-1_PT1776.mp8cwQ==
,2016-01-06 20:57:11.976 ThaliTest[1378:2952317] multipeer session: start timer: 0x15c73710
,2016-01-06 20:57:11.995 ThaliTest[1378:2952317] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT1776
,2016-01-06 20:57:11.998 ThaliTest[1378:2952317] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2016-01-06T19:57:12.009Z SendDataTCPServer.js: TCP/IP server is bound to port: 55676
,2016-01-06 20:57:12.874 ThaliTest[1378:2952065] client: found peer: Apple-Iphone5-1_PT2360.KoeEnA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:12.884Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06T19:57:12.885Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06T19:57:12.886Z SendDataConnector.js:, do connect now
2016-01-06 20:57:12.887 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:12.891 ThaliTest[1378:2952317] client session: connect
2016-01-06 20:57:12.892 ThaliTest[1378:2952317] client session: stateChange:0->1 Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:13.169 ThaliTest[1378:2952065] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9564.iuO8Uw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:13.178 ThaliTest[1378:2952065] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6789.hQhn/g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06 20:57:16.271 ThaliTest[1378:2952065] client: lost peer: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:16.272 ThaliTest[1378:2952065] client session: onPeerLost: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:16.273 ThaliTest[1378:2952065], client session: onLinkFailure: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:16.273 ThaliTest[1378:2952065] client session: disconnect
2016-01-06 20:57:16.273 ThaliTest[1378:2952065] client session: stateChange:1->0 Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:16.282 ThaliTest[1378:2952065] client session: fireConnectCallback: Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:16.282 ThaliTest[1378:2952065] jxcore: connect: fail: Peer disconnected
2016-01-06T19:57:16.284Z SendDataConnector.js: C,LIENT connected to 0, error: Peer disconnected
2016-01-06T19:57:16.284Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-06T19:57:16.285Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Ap,ple-Iphone5-1_PT2360.KoeEnA==","peerName":"(null)","peerAvailable":false}]
,2016-01-06 20:57:16.315 ThaliTest[1378:2952065] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT2360.wZr66g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-06T19:57:21.292Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:21.293Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:23.269 ThaliTest[1378:2952065] multipeer session: reset timer
2016-01-06 20:57:23.270 ThaliTest[1378:2952065] multipeer session: stop timer
2016-01-06 20:57:23.270 ThaliTest[1378:2952065] multipeer session: start timer: 0x15c73710
,2016-01-06 20:57:23.271 ThaliTest[1378:2952065] server session: connect
,2016-01-06 20:57:23.272 ThaliTest[1378:2952065] server session: stateChange:0->1 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:23.284 ThaliTest[1378:2952065] server: accepting invitation Apple-Iphone5-1_PT2360
,2016-01-06 20:57:25.898 ThaliTest[1378:2952921] server session: connected
2016-01-06 20:57:25.898 ThaliTest[1378:2952921] server session: stateChange:1->2 Apple-Iphone5-1_PT2360
,2016-01-06 20:57:25.906 ThaliTest[1378:2952065] server relay: connected (to port: 55676)
,2016-01-06T19:57:25.916Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06 20:57:26.307 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:57:26.307 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:57:26.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.KoeEn,A==
2016-01-06T19:57:26.309Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2360.KoeEnA== with availability status: true
,2016-01-06T19:57:26.309Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06T19:57:26.309Z SendDataConnector.js: do connect now
,2016-01-06 20:57:26.310 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:26.311 ThaliTest[1378:2952317] client: connect: unreachable Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:26.313 ThaliTest[1378:2952317] jxcore: connect: fail: Peer unreachable
2016-01-06T19:57:26.313Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:26.314Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2016-01-06T19:57:26.314Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:26.428Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-06T19:57:26.443Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-06T19:57:26.482Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2016-01-06T19:57:26.498Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-06T19:57:26.516Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-06T19:57:26.539Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-06T19:57:26.557Z SendDataTCPServer.js: TCP/IP server has received 94028 bytes of data
,2016-01-06T19:57:26.574Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:57:26.627 ThaliTest[1378:2953002] server session: not connected Apple-Iphone5-1_PT2360
,2016-01-06T19:57:31.326Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:31.327Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:36.329 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:57:36.330 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:57:36.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.KoeEn,A==
2016-01-06T19:57:36.331Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT2360.KoeEnA== with availability status: true
2016-01-06T19:57:36.332Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.KoeEnA==
2,016-01-06T19:57:36.332Z SendDataConnector.js: do connect now
,2016-01-06 20:57:36.333 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:36.334 ThaliTest[1378:2952317] client: connect: unreachable Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:36.334 ThaliTest[1378:2952317] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:36.335Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:36.337Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-06T19:57:36.337Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:41.340Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:41.341Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:46.352 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:57:46.352 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:57:46.353Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.KoeEn,A==
2016-01-06T19:57:46.353Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT2360.KoeEnA== with availability status: true
2016-01-06T19:57:46.353Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06T19:57:46.353Z SendDataConnector.js: do connect now
,2016-01-06 20:57:46.354 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:46.354 ThaliTest[1378:2952317] client: connect: unreachable Apple-Iphone5-1_PT2360.KoeEnA==
2016-01-06 20:57:46.354 ThaliTest[1378:2952317] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:46.355Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-06T19:57:46.355Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-06T19:57:46.356Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:57:51.356Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:51.357Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:53.272 ThaliTest[1378:2952065] multipeer session: restart
,2016-01-06 20:57:53.331 ThaliTest[1378:2952065] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:53.332 ThaliTest[1378:2952065] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:56.169 ThaliTest[1378:2952065] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:57:56.361 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:57:56.361 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:57:56.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.KoeEn,A==
2016-01-06T19:57:56.362Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT2360.KoeEnA== with availability status: true
2016-01-06T19:57:56.363Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06T19:57:56.364Z SendDataConnector.js: do connect now
2016-01-06 20:57:56.365 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:56.366 ThaliTest[1378:2952317] client: connect: unreachable Apple-Iphone5-1_PT2360.KoeEnA==
,2016-01-06 20:57:56.366 ThaliTest[1378:2952317] jxcore: connect: fail: Peer unreachable
,2016-01-06T19:57:56.368Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-06T19:57:56.369Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-06T19:57:56.372Z SendDataConnector.js: CLIENT Stop now
,2016-01-06 20:57:56.373 ThaliTest[1378:2952317] jxcore: disconnect
,2016-01-06 20:57:56.374 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:57:56.375Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.KoeEnA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:56.379Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:56.379Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06T19:57:56.380Z SendDataConnector.js: do connect now
,2016-01-06 20:57:56.381 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:56.382 ThaliTest[1378:2952317] client session: connect
2016-01-06 20:57:56.382 ThaliTest[1378:2952317] client session: stateChange:0->1 Apple,-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:57.250 ThaliTest[1378:2952065] multipeer session: reset timer
2016-01-06 20:57:57.251 ThaliTest[1378:2952065] multipeer session: stop timer
2016-01-06 20:57:57.251 ThaliTest[1378:2952065] multipeer session: start timer: 0x15c73710
2016-,01-06 20:57:57.251 ThaliTest[1378:2952065] server session: connect
2016-01-06 20:57:57.252 ThaliTest[1378:2952065] server session: stateChange:0->1 Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:57.265 ThaliTest[1378:2952065] server: accepting invitation Apple-IpadAir2-1_PT6789
,2016-01-06 20:57:59.340 ThaliTest[1378:2953239] client session: connected
2016-01-06 20:57:59.341 ThaliTest[1378:2953239] client session: stateChange:1->2 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:59.350 ThaliTest[1378:2953239] client session: fireConnectCallback: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:59.351 ThaliTest[1378:2953239] jxcore: connect: success
2016-01-06T19:57:59.353Z SendDataConnector.js: CLIENT connected ,to 55682, error: null
2016-01-06T19:57:59.353Z SendDataConnector.js: CLIENT starting client 
2016-01-06 20:57:59.358 ThaliTest[1378:2952065] client: relay established
2016-01-06 20:57:59.359 ThaliTest[1378:2952065] client: new accepted socket: 0x15b94b10
,2016-01-06T19:57:59.373Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:57:59.848Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-06T19:57:59.860Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-06T19:57:59.872Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:57:59.885Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-06T19:57:59.896Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-06T19:57:59.908Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-06T19:57:59.909Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-06T19:57:59.909Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:57:59.909Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:57:59.910 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:57:59.911 ThaliTest[1378:2952317] client session: disconnectFromPeer: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:57:59.911 ThaliTest[1378:2952317] client session: disconnect
2016-01-06 20:57:59.911 ThaliTest[1378:2952317] client session: stateChange:2->0 Apple-Iphone6-1_PT9564.iuO8Uw==
,2016-01-06 20:57:59.915 ThaliTest[1378:2952317] jxcore: disconnect: success
2016-01-06T19:57:59.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9564.iuO8Uw==
---- round done--------
startWithNextDevice
device[3]: App,le-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19:57:59.915Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19:57:59.916Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06T19:57:59.916Z SendDataConnector.js: do connect now
2016-01-06 20:57:59.916 ThaliTest[1378:2952317] jxcore: connect Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:57:59.916 ThaliTest[1378:2952317] client session: connect
,2016-01-06 20:57:59.916 ThaliTest[1378:2952317] client session: stateChange:0->1 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:00.031 ThaliTest[1378:2953061] server session: connected
2016-01-06 20:58:00.031 ThaliTest[1378:2953061] server session: stateChange:1->2 Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:00.039 ThaliTest[1378:2952065] server relay: connected (to port: 55676)
,2016-01-06T19:58:00.049Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:00.361Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-06T19:58:00.379Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-06T19:58:00.395Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-06T19:58:00.412Z SendDataTCPServer.js: TCP/IP server has received 74034 bytes of data
,2016-01-06T19:58:00.428Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-06T19:58:00.443Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:00.487 ThaliTest[1378:2953239] server session: not connected Apple-IpadAir2-1_PT6789
,2016-01-06 20:58:03.019 ThaliTest[1378:2953236] client session: connected
,2016-01-06 20:58:03.020 ThaliTest[1378:2953236] client session: stateChange:1->2 Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:03.033 ThaliTest[1378:2953236] client session: fireConnectCallback: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:03.033 ThaliTest[1378:2953236] jxcore: connect: success
,2016-01-06T19:58:03.035Z SendDataConnector.js: CLIENT connected to 55686, error: null
2016-01-06T19:58:03.036Z SendDataConnector.js: CLIENT starting client 
,2016-01-06 20:58:03.039 ThaliTest[1378:2952065] client: relay established
,2016-01-06 20:58:03.041 ThaliTest[1378:2952065] client: new accepted socket: 0x14655ba0
,2016-01-06T19:58:03.054Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:03.515Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-06T19:58:03.528Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-06T19:58:03.541Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-06T19:58:03.541Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:58:03.542Z SendDataConnector.js: CLIENT Stop now
2016-01-06T19:58:03.542Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:03.543 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:58:03.543 ThaliTest[1378:2952317] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:03.543 ThaliTest[1378:2952317] client session: discon,nect
2016-01-06 20:58:03.543 ThaliTest[1378:2952317] client session: stateChange:2->0 Apple-IpadAir2-1_PT6789.hQhn/g==
2016-01-06 20:58:03.547 ThaliTest[1378:2952317] jxcore: disconnect: success
2016-01-06T19:58:03.548Z SendDataConnector.js: Mobile.Disc,onnect() callback with peer Apple-IpadAir2-1_PT6789.hQhn/g==
---- round done--------
startWithNextDevice
device[4]: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:03.548Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT2360.wZr66g==
2,016-01-06T19:58:03.549Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06T19:58:03.549Z SendDataConnector.js: do connect now
2016-01-06 20:58:03.549 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.,wZr66g==
2016-01-06 20:58:03.549 ThaliTest[1378:2952317] client session: connect
2016-01-06 20:58:03.549 ThaliTest[1378:2952317] client session: stateChange:0->1 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:14.120 ThaliTest[1378:2953236] client session: not connected Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:14.121 ThaliTest[1378:2953236] client session: onLinkFailure: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:14.121 ThaliTest,[1378:2953236] client session: disconnect
2016-01-06 20:58:14.121 ThaliTest[1378:2953236] client session: stateChange:1->0 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:14.125 ThaliTest[1378:2953236] client session: fireConnectCallback: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:14.126 ThaliTest[1378:2953236] jxcore: connect: fail: Peer disconnected
2016-01-06T19:58:14.127Z SendDataConnector.js: C,LIENT connected to 0, error: Peer disconnected
2016-01-06T19:58:14.128Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-06T19:58:14.129Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-06T19:58:19.136Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06T19:58:19.136Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:24.143 ThaliTest[1378:2952317] jxcore: disconnect
2016-01-06 20:58:24.143 ThaliTest[1378:2952317] jxcore: disconnect: fail
2016-01-06T19:58:24.144Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.wZr66,g==
2016-01-06T19:58:24.144Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT2360.wZr66g== with availability status: true
2016-01-06T19:58:24.145Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06T19:58:24.145Z SendDataConnector.js: do connect now
2016-01-06 20:58:24.146 ThaliTest[1378:2952317] jxcore: connect Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:24.147 ThaliTest[1378:2952317] client session: connect
,2016-01-06 20:58:24.148 ThaliTest[1378:2952317] client session: stateChange:0->1 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:27.252 ThaliTest[1378:2952065] multipeer session: restart
,2016-01-06 20:58:27.318 ThaliTest[1378:2952065] client: found peer: Apple-Iphone6-1_PT9564.iuO8Uw==
2016-01-06 20:58:27.318 ThaliTest[1378:2952065] client: found peer: Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:27.319 ThaliTest[1378:2952065] client: found peer: Apple-IpadAir2-1_PT6789.hQhn/g==
,2016-01-06 20:58:28.254 ThaliTest[1378:2953456] client session: connected
2016-01-06 20:58:28.254 ThaliTest[1378:2953456] client session: stateChange:1->2 Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:28.260 ThaliTest[1378:2953456] client session: fir,eConnectCallback: Apple-Iphone5-1_PT2360.wZr66g==
2016-01-06 20:58:28.260 ThaliTest[1378:2953456] jxcore: connect: success
2016-01-06T19:58:28.262Z SendDataConnector.js: CLIENT connected to 55694, error: null
2016-01-06T19:58:28.262Z SendDataConnector.j,s: CLIENT starting client 
,2016-01-06 20:58:28.267 ThaliTest[1378:2952065] client: relay established
2016-01-06 20:58:28.267 ThaliTest[1378:2952065] client: new accepted socket: 0x15b98730
,2016-01-06T19:58:28.281Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-06T19:58:28.733Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-06T19:58:28.759Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-06T19:58:28.771Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-06T19:58:28.785Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-06T19:58:28.785Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-06T19:58:28.787Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:28.787Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:28.788 ThaliTest[1378:2952317] jxcore: disconnect
,2016-01-06 20:58:28.790 ThaliTest[1378:2952317] client session: disconnectFromPeer: Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:28.791 ThaliTest[1378:2952317] client session: disconnect
,2016-01-06 20:58:28.792 ThaliTest[1378:2952317] client session: stateChange:2->0 Apple-Iphone5-1_PT2360.wZr66g==
,2016-01-06 20:58:28.865 ThaliTest[1378:2952317] jxcore: disconnect: success
,2016-01-06T19:58:28.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT2360.wZr66g==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-06T19:58:28.885Z SendDataConnector.js: CLIENT Stop now
,2016-01-06T19:58:28.886Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-06 20:58:37.285 ThaliTest[1378:2952065] multipeer session: reset timer
2016-01-06 20:58:37.286 ThaliTest[1378:2952065] multipeer session: stop timer
2016-01-06 20:58:37.286 ThaliTest[1378:2952065] multipeer session: start timer: 0x15c73710
2016-,01-06 20:58:37.287 ThaliTest[1378:2952065] server session: connect
2016-01-06 20:58:37.287 ThaliTest[1378:2952065] server session: stateChange:0->1 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:37.300 ThaliTest[1378:2952065] server: accepting invitation Apple-Iphone6-1_PT9564
,2016-01-06 20:58:39.773 ThaliTest[1378:2953236] server session: connected
2016-01-06 20:58:39.773 ThaliTest[1378:2953236] server session: stateChange:1->2 Apple-Iphone6-1_PT9564
,2016-01-06 20:58:39.783 ThaliTest[1378:2952065] server relay: connected (to port: 55676)
,2016-01-06T19:58:39.794Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-06T19:58:40.047Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-06T19:58:40.068Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-06T19:58:40.087Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2016-01-06T19:58:40.108Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-06T19:58:40.265Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-06T19:58:40.281Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-06 20:58:40.321 ThaliTest[1378:2953456] server session: not connected Apple-Iphone6-1_PT9564
,Connected to the server!
,teardown
,testSendData stopped
2016-01-06 20:59:03.606 ThaliTest[1378:2952317] jxcore: stopBroadcasting
,2016-01-06 20:59:03.607 ThaliTest[1378:2952317] THEMultipeerSession stopping peer
2016-01-06 20:59:03.607 ThaliTest[1378:2952317] multipeer session: stop timer
,2016-01-06 20:59:03.608 ThaliTest[1378:2952317] server session: disconnect
2016-01-06 20:59:03.609 ThaliTest[1378:2952317] server session: stateChange:2->0 Apple-Iphone5-1_PT2360
,2016-01-06 20:59:03.622 ThaliTest[1378:2952317] server session: disconnect
2016-01-06 20:59:03.622 ThaliTest[1378:2952317] server session: stateChange:2->0 Apple-Iphone6-1_PT9564
,2016-01-06 20:59:03.648 ThaliTest[1378:2952317] server session: disconnect
2016-01-06 20:59:03.649 ThaliTest[1378:2952317] server session: stateChange:2->0 Apple-IpadAir2-1_PT6789
,2016-01-06 20:59:03.756 ThaliTest[1378:2952317] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2016-01-06T19:59:03.775Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:03.777Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:03.778Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-06T19:59:03.780Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
