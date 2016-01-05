#### Test 5507315224df3aa_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/034796ED-3776-4498-9086-6FB28733F6B2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/034796ED-3776-4498-9086-6FB28733F6B2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5507315224df3aa/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/399B0BFE-0424-472F-9E2F-E7AF03A314CF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65056"
,(lldb)     command script import "/tmp/034796ED-3776-4498-9086-6FB28733F6B2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-05 16:43:40.708 ThaliTest[1299:2786012] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C631E1CE-8B25-4CBA-9D8B-9DDBDA1918B6/Library/Cookies/Cookies.binarycookies
,2016-01-05 16:43:41.170 ThaliTest[1299:2786012] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-05 16:43:41.171 ThaliTest[1299:2786012] Multi-tasking -> Device: YES, App: YES
,2016-01-05 16:43:41.182 ThaliTest[1299:2786012] Unlimited access to network resources
,2016-01-05 16:43:41.198 ThaliTest[1299:2786012] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-05 16:43:50.182 ThaliTest[1299:2786012] Resetting plugins due to page load.
,2016-01-05 16:43:54.151 ThaliTest[1299:2786012] Finished load of: file:///var/mobile/Containers/Bundle/Application/399B0BFE-0424-472F-9E2F-E7AF03A314CF/ThaliTest.app/www/index.html
,2016-01-05 16:43:54.376 ThaliTest[1299:2786012] JXcore Cordova plugin initializing
,2016-01-05 16:43:54.377 ThaliTest[1299:2786253] JXcore instance initializing
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
,2016-01-05 16:43:55.710 ThaliTest[1299:2786012] THREAD WARNING: ['JXcore'] took '90.475098' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-05 16:48:41.743 ThaliTest[1299:2786253] jxcore: startBroadcasting
,2016-01-05 16:48:41.766 ThaliTest[1299:2786253] server: starting Apple-Iphone5s-1.LjVntA==
,2016-01-05 16:48:41.769 ThaliTest[1299:2786253] multipeer session: start timer: 0x18b71a60
,2016-01-05 16:48:41.792 ThaliTest[1299:2786253] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-05 16:48:41.797 ThaliTest[1299:2786253] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-05 16:48:42.007 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.uykjrA==, peerAvailable: true
weAreDoneNow
,done, now sending data to server
,teardown
,testFindPeers stopped
,2016-01-05 16:48:42.178 ThaliTest[1299:2786253] jxcore: stopBroadcasting
2016-01-05 16:48:42.179 ThaliTest[1299:2786253] THEMultipeerSession stopping peer
2016-01-05 16:48:42.179 ThaliTest[1299:2786253] multipeer session: stop timer
2016-01-05 16:48:42.,180 ThaliTest[1299:2786253] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 55125
,2016-01-05 16:48:42.250 ThaliTest[1299:2786253] jxcore: startBroadcasting
,2016-01-05 16:48:42.254 ThaliTest[1299:2786253] server: starting Apple-Iphone5s-1.lzdGtw==
2016-01-05 16:48:42.256 ThaliTest[1299:2786253] multipeer session: start timer: 0x18ac1e20
2016-01-05 16:48:42.257 ThaliTest[1299:2786253] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-05 16:48:42.257 ThaliTest[1299:2786253] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-05T15:48:42.262Z SendDataTCPServer.js: TCP/IP server is bound to port: 55125
,2016-01-05 16:48:42.780 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.uykjrA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5-1.uykjrA==
,2016-01-05T15:48:42.787Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:48:42.788Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:48:42.789Z SendDataConnector.js: do connect no,w
2016-01-05 16:48:42.790 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:42.791 ThaliTest[1299:2786253] client session: connect
2016-01-05 16:48:42.792 ThaliTest[1299:2786253] client session: stateChange:0->1 Apple-Iph,one5-1.uykjrA==
,2016-01-05 16:48:43.510 ThaliTest[1299:2786012] client: lost peer: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.510 ThaliTest[1299:2786012] client session: onPeerLost: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.511 ThaliTest[1299:2786012] client sessio,n: onLinkFailure: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.511 ThaliTest[1299:2786012] client session: disconnect
2016-01-05 16:48:43.512 ThaliTest[1299:2786012] client session: stateChange:1->0 Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.513 Thali,Test[1299:2786012] client session: fireConnectCallback: Apple-Iphone5-1.uykjrA==
2016-01-05 16:48:43.513 ThaliTest[1299:2786012] jxcore: connect: fail: Peer disconnected
2016-01-05T15:48:43.515Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-05T15:48:43.515Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-05T15:48:43.516Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.uykjrA==","peerName":",(null)","peerAvailable":false}]
,2016-01-05 16:48:43.542 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.cnOsew==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.cnOsew==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-05 16:48:44.959 ThaliTest[1299:2786012] client: found peer: Apple-IpadAir2-1.xC8Jhw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xC8Jhw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05T15:48:48.523Z SendDataConnector.js: re-try now : Apple-Iphone5-1.uykjrA==
,2016-01-05T15:48:48.524Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.uykjrA==
,2016-01-05 16:48:53.530 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:48:53.530 ThaliTest[1299:2786253] jxcore: disconnect: fail
2016-01-05T15:48:53.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.uykjrA==
20,16-01-05T15:48:53.532Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.uykjrA== with availability status: true
,2016-01-05T15:48:53.533Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:48:53.533Z SendDataConnector.js: do connect now
,2016-01-05 16:48:53.534 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.uykjrA==
,2016-01-05 16:48:53.535 ThaliTest[1299:2786253] client: connect: unreachable Apple-Iphone5-1.uykjrA==
,2016-01-05 16:48:53.535 ThaliTest[1299:2786253] jxcore: connect: fail: Peer unreachable
,2016-01-05T15:48:53.537Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:48:53.537Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:48:53.538Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05 16:48:56.790 ThaliTest[1299:2786012] client: found peer: Apple-Iphone6-1.GJN/JA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.GJN/JA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-05T15:48:58.541Z SendDataConnector.js: re-try now : Apple-Iphone5-1.uykjrA==
,2016-01-05T15:48:58.541Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:03.549 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:49:03.549 ThaliTest[1299:2786253] jxcore: disconnect: fail
2016-01-05T15:49:03.551Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.uykjrA==
20,16-01-05T15:49:03.552Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.uykjrA== with availability status: true
2016-01-05T15:49:03.552Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:49:03.55,2Z SendDataConnector.js: do connect now
,2016-01-05 16:49:03.553 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.uykjrA==
2016-01-05 16:49:03.554 ThaliTest[1299:2786253] client: connect: unreachable Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:03.555 ThaliTest[1299:2786253] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:03.556Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:03.556Z SendDataConnector.js: CLIENT Can not Connect: P,eer unreachable
2016-01-05T15:49:03.556Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:08.569Z SendDataConnector.js: re-try now : Apple-Iphone5-1.uykjrA==
,2016-01-05T15:49:08.570Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:12.258 ThaliTest[1299:2786012] multipeer session: restart
,2016-01-05 16:49:12.316 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:12.318 ThaliTest[1299:2786012] client: found peer: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:12.319 ThaliTest[1299:2786012] client: found peer: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:13.578 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:49:13.579 ThaliTest[1299:2786253] jxcore: disconnect: fail
2016-01-05T15:49:13.579Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.uykjrA==
20,16-01-05T15:49:13.580Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.uykjrA== with availability status: true
2016-01-05T15:49:13.580Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:49:13.580Z SendDataConnector.js: do connect now
,2016-01-05 16:49:13.581 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:13.582 ThaliTest[1299:2786253] client: connect: unreachable Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:13.583 ThaliTest[1299:2786253] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:13.584Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:13.585Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-05T15:49:13.585Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-05T15:49:18.592Z SendDataConnector.js: re-try now : Apple-Iphone5-1.uykjrA==
,2016-01-05T15:49:18.592Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:23.604 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:49:23.605 ThaliTest[1299:2786253] jxcore: disconnect: fail
2016-01-05T15:49:23.605Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.uykjrA==
20,16-01-05T15:49:23.606Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.uykjrA== with availability status: true
2016-01-05T15:49:23.606Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.uykjrA==
2016-01-05T15:49:23.606Z SendDataConnector.js: do connect now
,2016-01-05 16:49:23.607 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:23.608 ThaliTest[1299:2786253] client: connect: unreachable Apple-Iphone5-1.uykjrA==
,2016-01-05 16:49:23.610 ThaliTest[1299:2786253] jxcore: connect: fail: Peer unreachable
2016-01-05T15:49:23.611Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-05T15:49:23.611Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-05T15:49:23.613Z SendDataConnector.js: CLIENT Stop now
,2016-01-05 16:49:23.615 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:49:23.615 ThaliTest[1299:2786253] jxcore: disconnect: fail
,2016-01-05T15:49:23.618Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.uykjrA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.cnOsew==
,2016-01-05T15:49:23.622Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.cnOsew==
,2016-01-05T15:49:23.622Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.cnOsew==
,2016-01-05T15:49:23.623Z SendDataConnector.js: do connect now
,2016-01-05 16:49:23.624 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:23.625 ThaliTest[1299:2786253] client session: connect
2016-01-05 16:49:23.625 ThaliTest[1299:2786253] client session: stateChange:0->1 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:25.117 ThaliTest[1299:2786012] multipeer session: reset timer
2016-01-05 16:49:25.118 ThaliTest[1299:2786012] multipeer session: stop timer
2016-01-05 16:49:25.118 ThaliTest[1299:2786012] multipeer session: start timer: 0x18ac1e20
2016-,01-05 16:49:25.118 ThaliTest[1299:2786012] server session: connect
2016-01-05 16:49:25.119 ThaliTest[1299:2786012] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-05 16:49:25.131 ThaliTest[1299:2786012] server: accepting invitation Apple-IpadAir2-1
,2016-01-05 16:49:26.637 ThaliTest[1299:2786837] client session: connected
2016-01-05 16:49:26.637 ThaliTest[1299:2786837] client session: stateChange:1->2 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:26.690 ThaliTest[1299:2786795] client session: fireConnectCallback: Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:26.690 ThaliTest[1299:2786795] jxcore: connect: success
2016-01-05T15:49:26.692Z SendDataConnector.js: CLIENT connected to 5512,9, error: null
2016-01-05T15:49:26.692Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:26.697 ThaliTest[1299:2786012] client: relay established
2016-01-05 16:49:26.697 ThaliTest[1299:2786012] client: new accepted socket: 0x18b88e20
,2016-01-05T15:49:26.714Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:27.094Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T15:49:27.106Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-05T15:49:27.120Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-05T15:49:27.132Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T15:49:27.144Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-05T15:49:27.168Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-05T15:49:27.168Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:27.169Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:49:27.169Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:27.170 ThaliTest[1299:2786253] jxcore: disconnect
2016-01-05 16:49:27.170 ThaliTest[1299:2786253] client session: disconnectFromPeer: Apple-Iphone5-1.cnOsew==
2016-01-05 16:49:27.170 ThaliTest[1299:2786253] client session: disconnect
2016-01-05 16:49:27.170 ThaliTest[1299:2786253] client session: stateChange:2->0 Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:27.175 ThaliTest[1299:2786253] jxcore: disconnect: success
2016-01-05T15:49:27.176Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.cnOsew==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipad,Air2-1.xC8Jhw==
2016-01-05T15:49:27.176Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:27.176Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.xC8Jhw==
2016-01-05T15:49:27.177Z SendDataConnecto,r.js: do connect now
2016-01-05 16:49:27.177 ThaliTest[1299:2786253] jxcore: connect Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:27.177 ThaliTest[1299:2786253] client session: connect
2016-01-05 16:49:27.177 ThaliTest[1299:2786253] client session: stateChange:0->1 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:28.202 ThaliTest[1299:2786012] multipeer session: reset timer
2016-01-05 16:49:28.202 ThaliTest[1299:2786012] multipeer session: stop timer
2016-01-05 16:49:28.202 ThaliTest[1299:2786012] multipeer session: start timer: 0x18ac1e20
2016-01-05 16:49:28.203 ThaliTest[1299:2786012] server session: connect
2016-01-05 16:49:28.203 ThaliTest[1299:2786012] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-05 16:49:28.228 ThaliTest[1299:2786012] server: accepting invitation Apple-Iphone5-1
,2016-01-05 16:49:28.837 ThaliTest[1299:2786837] server session: connected
2016-01-05 16:49:28.837 ThaliTest[1299:2786837] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-05 16:49:28.870 ThaliTest[1299:2786012] server relay: connected (to port: 55125)
,2016-01-05T15:49:28.880Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:29.185Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-05T15:49:29.199Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-05T15:49:29.217Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-05T15:49:29.238Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2016-01-05T15:49:29.258Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-05T15:49:29.276Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-05T15:49:29.290Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:29.315 ThaliTest[1299:2786793] server session: not connected Apple-IpadAir2-1
,2016-01-05 16:49:30.825 ThaliTest[1299:2786795] client session: connected
,2016-01-05 16:49:30.826 ThaliTest[1299:2786795] client session: stateChange:1->2 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:30.847 ThaliTest[1299:2786795] client session: fireConnectCallback: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:49:30.847 ThaliTest[1299:2786795] jxcore: connect: success
,2016-01-05T15:49:30.849Z SendDataConnector.js: CLIENT connected to 55133, error: null
,2016-01-05T15:49:30.850Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:30.855 ThaliTest[1299:2786012] client: relay established
,2016-01-05 16:49:30.857 ThaliTest[1299:2786012] client: new accepted socket: 0x18b88c90
,2016-01-05T15:49:30.867Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05 16:49:30.956 ThaliTest[1299:2786795] server session: connected
,2016-01-05 16:49:30.958 ThaliTest[1299:2786795] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-05 16:49:30.961 ThaliTest[1299:2786012] server relay: connected (to port: 55125)
,2016-01-05T15:49:31.161Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:49:31.283Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-05T15:49:31.346Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:49:31.347Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:31.347Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:31.347Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:31.348 ThaliTest[1299:2786253] jxcore: disconnect
,2016-01-05 16:49:31.349 ThaliTest[1299:2786253] client session: disconnectFromPeer: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:31.349 ThaliTest[1299:2786253] client session: disconnect
,2016-01-05 16:49:31.349 ThaliTest[1299:2786253] client session: stateChange:2->0 Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:31.414 ThaliTest[1299:2786253] jxcore: disconnect: success
,2016-01-05T15:49:31.415Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.xC8Jhw==
---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:49:31.416Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:49:31.417Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:49:31.417Z SendDataConnector.js: do connect now
,2016-01-05 16:49:31.418 ThaliTest[1299:2786253] jxcore: connect Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:31.418 ThaliTest[1299:2786253] client session: connect
,2016-01-05 16:49:31.419 ThaliTest[1299:2786253] client session: stateChange:0->1 Apple-Iphone6-1.GJN/JA==
,2016-01-05T15:49:31.481Z SendDataTCPServer.js: TCP/IP server has received 54608 bytes of data
,2016-01-05T15:49:31.498Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-05T15:49:31.549Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:49:33.967 ThaliTest[1299:2786795] server session: not connected Apple-Iphone5-1
,2016-01-05 16:49:34.985 ThaliTest[1299:2786795] client session: connected
,2016-01-05 16:49:34.986 ThaliTest[1299:2786795] client session: stateChange:1->2 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:35.028 ThaliTest[1299:2786793] client session: fireConnectCallback: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:35.029 ThaliTest[1299:2786793] jxcore: connect: success
,2016-01-05T15:49:35.033Z SendDataConnector.js: CLIENT connected to 55137, error: null
2016-01-05T15:49:35.033Z SendDataConnector.js: CLIENT starting client 
,2016-01-05 16:49:35.038 ThaliTest[1299:2786012] client: relay established
,2016-01-05 16:49:35.038 ThaliTest[1299:2786012] client: new accepted socket: 0x18ad4390
,2016-01-05T15:49:35.050Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-05T15:49:35.340Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-05T15:49:35.360Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-05T15:49:35.412Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-05T15:49:35.473Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-05T15:49:35.473Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-05T15:49:35.473Z SendDataConnector.js: CLIENT Stop now
,2016-01-05T15:49:35.474Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:35.474 ThaliTest[1299:2786253] jxcore: disconnect
,2016-01-05 16:49:35.475 ThaliTest[1299:2786253] client session: disconnectFromPeer: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:35.475 ThaliTest[1299:2786253] client session: disconnect
,2016-01-05 16:49:35.476 ThaliTest[1299:2786253] client session: stateChange:2->0 Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:49:35.483 ThaliTest[1299:2786253] jxcore: disconnect: success
,2016-01-05T15:49:35.487Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.GJN/JA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-05T15:49:35.492Z SendDataConnector.js: CLIENT Stop now
2016-01-05T15:49:35.493Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-05 16:49:58.176 ThaliTest[1299:2786012] multipeer session: restart
,2016-01-05 16:49:58.233 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.cnOsew==
,2016-01-05 16:49:58.238 ThaliTest[1299:2786012] client: found peer: Apple-IpadAir2-1.xC8Jhw==
,2016-01-05 16:49:58.239 ThaliTest[1299:2786012] client: found peer: Apple-Iphone6-1.GJN/JA==
,2016-01-05 16:50:08.565 ThaliTest[1299:2786012] multipeer session: reset timer
2016-01-05 16:50:08.565 ThaliTest[1299:2786012] multipeer session: stop timer
2016-01-05 16:50:08.565 ThaliTest[1299:2786012] multipeer session: start timer: 0x18ac1e20
2016-,01-05 16:50:08.566 ThaliTest[1299:2786012] server session: connect
2016-01-05 16:50:08.566 ThaliTest[1299:2786012] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-05 16:50:08.577 ThaliTest[1299:2786012] server: accepting invitation Apple-Iphone6-1
,2016-01-05 16:50:11.115 ThaliTest[1299:2786927] server session: connected
2016-01-05 16:50:11.115 ThaliTest[1299:2786927] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-05 16:50:11.135 ThaliTest[1299:2786012] server relay: connected (to port: 55125)
2016-01-05T15:50:11.143Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-05T15:50:11.399Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-05T15:50:11.416Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-05T15:50:11.435Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2016-01-05T15:50:11.450Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-05T15:50:11.616Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-05T15:50:11.634Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2016-01-05T15:50:11.655Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-05 16:50:11.694 ThaliTest[1299:2786923] server session: not connected Apple-Iphone6-1
,2016-01-05 16:50:38.567 ThaliTest[1299:2786012] multipeer session: restart
,2016-01-05 16:50:38.629 ThaliTest[1299:2786012] client: found peer: Apple-IpadAir2-1.xC8Jhw==
2016-01-05 16:50:38.631 ThaliTest[1299:2786012] client: found peer: Apple-Iphone5-1.cnOsew==
,teardown
,testSendData stopped
,2016-01-05 16:50:39.107 ThaliTest[1299:2786253] jxcore: stopBroadcasting
2016-01-05 16:50:39.108 ThaliTest[1299:2786253] THEMultipeerSession stopping peer
2016-01-05 16:50:39.108 ThaliTest[1299:2786253] multipeer session: stop timer
2016-01-05 16:50:39.,109 ThaliTest[1299:2786253] server session: disconnect
2016-01-05 16:50:39.109 ThaliTest[1299:2786253] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-05 16:50:39.122 ThaliTest[1299:2786253] server session: disconnect
2016-01-05 16:50:39.123 ThaliTest[1299:2786253] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-05 16:50:39.131 ThaliTest[1299:2786253] server session: disconnect
2016-01-05 16:50:39.132 ThaliTest[1299:2786253] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-05 16:50:39.145 ThaliTest[1299:2786253] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-05T15:50:39.165Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:39.167Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:39.173Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-05T15:50:39.175Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
