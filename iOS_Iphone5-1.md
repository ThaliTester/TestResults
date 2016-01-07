#### Test 5531115118861c0_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/808DEDD6-BA9B-4087-A38B-2E366ABBE03A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/808DEDD6-BA9B-4087-A38B-2E366ABBE03A/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5531115118861c0/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0FFBB43D-5841-41AD-8BA2-98A5D49869C3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49572"
,(lldb)     command script import "/tmp/808DEDD6-BA9B-4087-A38B-2E366ABBE03A/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-07 10:41:04.045 ThaliTest[1037:3394111] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78B4C333-9B6B-47AA-9A11-AC8C8A7B4B9D/Library/Cookies/Cookies.binarycookies
,2016-01-07 10:41:04.583 ThaliTest[1037:3394111] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-07 10:41:04.584 ThaliTest[1037:3394111] Multi-tasking -> Device: YES, App: YES
,2016-01-07 10:41:04.591 ThaliTest[1037:3394111] Unlimited access to network resources
,2016-01-07 10:41:04.601 ThaliTest[1037:3394111] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-07 10:41:15.479 ThaliTest[1037:3394111] Resetting plugins due to page load.
,2016-01-07 10:41:19.010 ThaliTest[1037:3394111] Finished load of: file:///var/mobile/Containers/Bundle/Application/0FFBB43D-5841-41AD-8BA2-98A5D49869C3/ThaliTest.app/www/index.html
,2016-01-07 10:41:19.222 ThaliTest[1037:3394111] JXcore Cordova plugin initializing
,2016-01-07 10:41:19.223 ThaliTest[1037:3394291] JXcore instance initializing
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
,2016-01-07 10:41:21.633 ThaliTest[1037:3394111] THREAD WARNING: ['JXcore'] took '156.477051' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-07 10:47:29.888 ThaliTest[1037:3394291] jxcore: startBroadcasting
,2016-01-07 10:47:29.900 ThaliTest[1037:3394291] server: starting Apple-Iphone5-1.kLcgag==
2016-01-07 10:47:29.901 ThaliTest[1037:3394291] multipeer session: start timer: 0x19bc03e0
2016-01-07 10:47:29.902 ThaliTest[1037:3394291] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-07 10:47:29.902 ThaliTest[1037:3394291] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-07 10:47:30.414 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5-1.Xe0AvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1.Xe0AvA==, peerAvail,able: true
,weAreDoneNow
,done, now sending data to server
,2016-01-07 10:47:30.942 ThaliTest[1037:3394111] client: found peer: Apple-IpadAir2-1.1I3u2A==
,2016-01-07 10:47:31.077 ThaliTest[1037:3394111] client: found peer: Apple-Iphone6-1.W/Fi/g==
,teardown
,testFindPeers stopped
,2016-01-07 10:47:33.762 ThaliTest[1037:3394291] jxcore: stopBroadcasting
,2016-01-07 10:47:33.762 ThaliTest[1037:3394291] THEMultipeerSession stopping peer
2016-01-07 10:47:33.763 ThaliTest[1037:3394291] multipeer session: stop timer
2016-01-07 10:47:33.764 ThaliTest[1037:3394291] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 65007
2016-01-07 10:47:33.785 ThaliTest[1037:3394291] jxcore: startBroadcasting
,2016-01-07 10:47:33.794 ThaliTest[1037:3394291] server: starting Apple-Iphone5-1.XzilZw==
2016-01-07 10:47:33.795 ThaliTest[1037:3394291] multipeer session: start timer: 0x19bc2220
2016-01-07 10:47:33.795 ThaliTest[1037:3394291] THEMultipeerSession initialized peer Apple-Iphone5-1
2016-01-07 10:47:33.795 ThaliTest[1037:3394291] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2016-01-07T09:47:33.800Z SendDataTCPServer.js: TCP/IP server is bound to port: 65007
,2016-01-07 10:47:34.693 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5-1.Xe0AvA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithN,extDevice
device[1]: Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:47:34.697Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:34.697 ThaliTest[1037:3394111] client: found peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:,34.698 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5-1.kLcgag==
2016-01-07T09:47:34.698Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.Xe0AvA==
,2016-01-07T09:47:34.699Z SendDataConnector.js: do connect now
2016-01-07 10:47:34.699 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:34.700 ThaliTest[1037:3394291] client session: connect
2016-01-07 10:47:34.701 ThaliT,est[1037:3394291] client session: stateChange:0->1 Apple-Iphone5-1.Xe0AvA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:34.897 ThaliTest[1037:3394111] client: lost peer: Apple-Iphone5-1.kLcgag==
2016-01-07 10:47:34.897 ThaliTest[1037:3394111] client session: onPeerLost: Apple-Iphone5-1.kLcgag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kLcgag==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07 10:47:35.146 ThaliTest[1037:3394111] client: found peer: Apple-IpadAir2-1.CdHxkA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.CdHxkA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:35.150 ThaliTest[1037:3394111] client: found peer: Apple-Iphone6-1.Uf4Y7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.Uf4Y7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:35.694 ThaliTest[1037:3394111] client: lost peer: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.694 ThaliTest[1037:3394111] client session: onPeerLost: Apple-IpadAir2-1.1I3u2A==
2016-01-07 10:47:35.695 ThaliTest[1037:3394111] client: fou,nd peer: Apple-Iphone5s-1.Waegsg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.1I3u2A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07 10:47:45.900 ThaliTest[1037:3394111] client: lost peer: Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:45.901 ThaliTest[1037:3394111] client session: onPeerLost: Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:45.901 ThaliTest[1037:3394111] client sessio,n: onLinkFailure: Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:45.901 ThaliTest[1037:3394111] client session: disconnect
2016-01-07 10:47:45.902 ThaliTest[1037:3394111] client session: stateChange:1->0 Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:45.903 Thali,Test[1037:3394111] client session: fireConnectCallback: Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:45.903 ThaliTest[1037:3394111] jxcore: connect: fail: Peer disconnected
2016-01-07T09:47:45.904Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-07T09:47:45.904Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-07T09:47:45.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerName":"(null)","peerAvailable":false}]
,2016-01-07T09:47:50.914Z SendDataConnector.js: re-try now : Apple-Iphone5-1.Xe0AvA==
,2016-01-07T09:47:50.915Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.Xe0AvA==
,2016-01-07 10:47:55.917 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:47:55.917 ThaliTest[1037:3394291] jxcore: disconnect: fail
2016-01-07T09:47:55.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.Xe0AvA==
20,16-01-07T09:47:55.919Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.Xe0AvA== with availability status: true
2016-01-07T09:47:55.919Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:47:55.91,9Z SendDataConnector.js: do connect now
2016-01-07 10:47:55.920 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:55.921 ThaliTest[1037:3394291] client: connect: unreachable Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:47:55.92,1 ThaliTest[1037:3394291] jxcore: connect: fail: Peer unreachable
2016-01-07T09:47:55.921Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:47:55.921Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:47:55.922Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:00.928Z SendDataConnector.js: re-try now : Apple-Iphone5-1.Xe0AvA==
,2016-01-07T09:48:00.928Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.Xe0AvA==
,2016-01-07 10:48:03.817 ThaliTest[1037:3394111] multipeer session: restart
,2016-01-07 10:48:03.854 ThaliTest[1037:3394111] client: found peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:03.854 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:03.855 ThaliTest[1037:3394111] client: found peer: Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:05.937 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:05.937 ThaliTest[1037:3394291] jxcore: disconnect: fail
2016-01-07T09:48:05.938Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:48:05.938Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.Xe0AvA== with availability status: true
2016-01-07T09:48:05.939Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:48:05.93,9Z SendDataConnector.js: do connect now
,2016-01-07 10:48:05.940 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:05.940 ThaliTest[1037:3394291] client: connect: unreachable Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:05.941 ThaliTest[1037:3394291] jxcore: connect,: fail: Peer unreachable
2016-01-07T09:48:05.941Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:05.942Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:05.942Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:10.954Z SendDataConnector.js: re-try now : Apple-Iphone5-1.Xe0AvA==
,2016-01-07T09:48:10.954Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.Xe0AvA==
,2016-01-07 10:48:15.956 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:15.956 ThaliTest[1037:3394291] jxcore: disconnect: fail
2016-01-07T09:48:15.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.Xe0AvA==
20,16-01-07T09:48:15.957Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.Xe0AvA== with availability status: true
2016-01-07T09:48:15.958Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:48:15.958Z SendDataConnector.js: do connect now
,2016-01-07 10:48:15.959 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:15.959 ThaliTest[1037:3394291] client: connect: unreachable Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:15.960 ThaliTest[1037:3394291] jxcore: connect: fail: Peer unreachable
,2016-01-07T09:48:15.960Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-07T09:48:15.960Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-07T09:48:15.961Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-07T09:48:20.973Z SendDataConnector.js: re-try now : Apple-Iphone5-1.Xe0AvA==
,2016-01-07T09:48:20.974Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.Xe0AvA==
,2016-01-07 10:48:25.985 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:25.985 ThaliTest[1037:3394291] jxcore: disconnect: fail
2016-01-07T09:48:25.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.Xe0AvA==
20,16-01-07T09:48:25.986Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.Xe0AvA== with availability status: true
2016-01-07T09:48:25.987Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.Xe0AvA==
2016-01-07T09:48:25.987Z SendDataConnector.js: do connect now
,2016-01-07 10:48:25.988 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:25.988 ThaliTest[1037:3394291] client: connect: unreachable Apple-Iphone5-1.Xe0AvA==
2016-01-07 10:48:25.989 ThaliTest[1037:3394291] jxcore: connect,: fail: Peer unreachable
2016-01-07T09:48:25.989Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-07T09:48:25.989Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-07T09:48:25.991Z SendDataConnector.js: CLIENT Stop now
2016-01-07 10:48:25.991 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:25.992 ThaliTest[1037:3394291] jxcore: disconnect: fail
2016-01-07T09:48:25.992Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.Xe0AvA==
---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1.CdHxkA==
2016-01-07T09:48:25.993Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.CdHxkA==
2016-01-07T09:48:25.994Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.CdHxkA==
,2016-01-07T09:48:25.994Z SendDataConnector.js: do connect now
,2016-01-07 10:48:25.994 ThaliTest[1037:3394291] jxcore: connect Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:25.995 ThaliTest[1037:3394291] client session: connect
2016-01-07 10:48:25.995 ThaliTest[1037:3394291] client session: stateChange:0->1 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:27.471 ThaliTest[1037:3394111] client: lost peer: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:27.472 ThaliTest[1037:3394111] client session: onPeerLost: Apple-Iphone5s-1.Waegsg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.Waegsg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-07 10:48:29.422 ThaliTest[1037:3395019] client session: connected
2016-01-07 10:48:29.423 ThaliTest[1037:3395019] client session: stateChange:1->2 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:29.660 ThaliTest[1037:3395035] client session: fireConnectCallback: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:29.660 ThaliTest[1037:3395035] jxcore: connect: success
2016-01-07T09:48:29.661Z SendDataConnector.js: CLIENT connected to 65011, error: null
2016-01-07T09:48:29.661Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:29.664 ThaliTest[1037:3394111] client: relay established
2016-01-07 10:48:29.664 ThaliTest[1037:3394111] client: new accepted socket: 0x19bd9a50
,2016-01-07T09:48:29.679Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07 10:48:30.182 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5s-1.Waegsg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.Waegsg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-07T09:48:30.739Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-07T09:48:30.753Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-07T09:48:31.234Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-07T09:48:31.235Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-07T09:48:31.236Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:31.237Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:31.239 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:31.239 ThaliTest[1037:3394291] client session: disconnectFromPeer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:31.239 ThaliTest[1037:3394291] client session: disconnect
2,016-01-07 10:48:31.239 ThaliTest[1037:3394291] client session: stateChange:2->0 Apple-IpadAir2-1.CdHxkA==
,2016-01-07 10:48:31.249 ThaliTest[1037:3394291] jxcore: disconnect: success
2016-01-07T09:48:31.251Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.CdHxkA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one6-1.Uf4Y7g==
2016-01-07T09:48:31.252Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.Uf4Y7g==
2016-01-07T09:48:31.253Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.Uf4Y7g==
,2016-01-07T09:48:31.254Z SendDataConnector.js: do connect now
2016-01-07 10:48:31.255 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:31.255 ThaliTest[1037:3394291] client session: connect
2016-01-07 10:48:31.255 ThaliTest[1037:3394291] client session: stateChange:0->1 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:33.817 ThaliTest[1037:3394111] multipeer session: restart
,2016-01-07 10:48:33.852 ThaliTest[1037:3394111] client: found peer: Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:33.855 ThaliTest[1037:3394111] client: found peer: Apple-IpadAir2-1.CdHxkA==
2016-01-07 10:48:33.855 ThaliTest[1037:3394111] client: found peer: Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:34.439 ThaliTest[1037:3395035] client session: connected
,2016-01-07 10:48:34.439 ThaliTest[1037:3395035] client session: stateChange:1->2 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:34.443 ThaliTest[1037:3395035] client session: fireConnectCallback: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:34.443 ThaliTest[1037:3395035] jxcore: connect: success
2016-01-07T09:48:34.444Z SendDataConnector.js: CLIENT connected to 65015, error: null
2016-01-07T09:48:34.445Z SendDataConnector.js: CLIENT starting client 
,2016-01-07 10:48:34.449 ThaliTest[1037:3394111] client: relay established
2016-01-07 10:48:34.449 ThaliTest[1037:3394111] client: new accepted socket: 0x19bda7f0
,2016-01-07T09:48:34.460Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:35.524Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-07T09:48:35.625Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-07T09:48:35.750Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-07T09:48:35.750Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-07T09:48:35.751Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:35.751Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:35.752 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:35.752 ThaliTest[1037:3394291] client session: disconnectFromPeer: Apple-Iphone6-1.Uf4Y7g==
2016-01-07 10:48:35.752 ThaliTest[1037:3394291] client session: disconnect
20,16-01-07 10:48:35.752 ThaliTest[1037:3394291] client session: stateChange:2->0 Apple-Iphone6-1.Uf4Y7g==
,2016-01-07 10:48:35.761 ThaliTest[1037:3394291] jxcore: disconnect: success
2016-01-07T09:48:35.762Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.Uf4Y7g==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,ne5s-1.Waegsg==
2016-01-07T09:48:35.763Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.Waegsg==
2016-01-07T09:48:35.763Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.Waegsg==
2016-01-07T09:48:35.763Z SendDataConnecto,r.js: do connect now
2016-01-07 10:48:35.764 ThaliTest[1037:3394291] jxcore: connect Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:35.764 ThaliTest[1037:3394291] client session: connect
2016-01-07 10:48:35.764 ThaliTest[1037:3394291] client session: stateChange:0->1 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:39.096 ThaliTest[1037:3395019] client session: connected
2016-01-07 10:48:39.098 ThaliTest[1037:3395019] client session: stateChange:1->2 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:39.214 ThaliTest[1037:3395036] client session: fireConnectCallback: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:39.214 ThaliTest[1037:3395036] jxcore: connect: success
2016-01-07T09:48:39.215Z SendDataConnector.js: CLIENT connected to 650,18, error: null
2016-01-07T09:48:39.215Z SendDataConnector.js: CLIENT starting client 
2016-01-07 10:48:39.217 ThaliTest[1037:3394111] client: relay established
2016-01-07 10:48:39.218 ThaliTest[1037:3394111] client: new accepted socket: 0x19caf7e0
,2016-01-07T09:48:39.230Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-07T09:48:40.350Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-07T09:48:40.684Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-07T09:48:40.699Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-07T09:48:40.737Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-07T09:48:40.873Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-07T09:48:40.925Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-07T09:48:40.925Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-07T09:48:40.926Z SendDataConnector.js: CLIENT Stop now
,2016-01-07T09:48:40.926Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:40.927 ThaliTest[1037:3394291] jxcore: disconnect
2016-01-07 10:48:40.927 ThaliTest[1037:3394291] client session: disconnectFromPeer: Apple-Iphone5s-1.Waegsg==
2016-01-07 10:48:40.927 ThaliTest[1037:3394291] client session: disconnect
2,016-01-07 10:48:40.927 ThaliTest[1037:3394291] client session: stateChange:2->0 Apple-Iphone5s-1.Waegsg==
,2016-01-07 10:48:40.936 ThaliTest[1037:3394291] jxcore: disconnect: success
2016-01-07T09:48:40.936Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.Waegsg==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-07T09:48:40.956Z SendDataConnector.js: CLIENT Stop now
2016-01-07T09:48:40.956Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-07 10:48:44.590 ThaliTest[1037:3394111] multipeer session: reset timer
2016-01-07 10:48:44.590 ThaliTest[1037:3394111] multipeer session: stop timer
2016-01-07 10:48:44.590 ThaliTest[1037:3394111] multipeer session: start timer: 0x19bc2220
2016-01-07 10:48:44.590 ThaliTest[1037:3394111] server session: connect
2016-01-07 10:48:44.590 ThaliTest[1037:3394111] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-07 10:48:44.596 ThaliTest[1037:3394111] server: accepting invitation Apple-IpadAir2-1
,2016-01-07 10:48:45.967 ThaliTest[1037:3394111] multipeer session: reset timer
2016-01-07 10:48:45.967 ThaliTest[1037:3394111] multipeer session: stop timer
2016-01-07 10:48:45.968 ThaliTest[1037:3394111] multipeer session: start timer: 0x19bc2220
2016-,01-07 10:48:45.968 ThaliTest[1037:3394111] server session: connect
2016-01-07 10:48:45.968 ThaliTest[1037:3394111] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-07 10:48:45.974 ThaliTest[1037:3394111] server: accepting invitation Apple-Iphone5s-1
,2016-01-07 10:48:47.808 ThaliTest[1037:3395036] server session: connected
,2016-01-07 10:48:47.809 ThaliTest[1037:3395036] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-07 10:48:47.877 ThaliTest[1037:3394111] server relay: connected (to port: 65007)
2016-01-07T09:48:47.879Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:48.271Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2016-01-07T09:48:48.287Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-07T09:48:48.303Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-07T09:48:48.315Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-07T09:48:48.327Z SendDataTCPServer.js: TCP/IP server has received 73365 bytes of data
,2016-01-07T09:48:48.343Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2016-01-07T09:48:48.358Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:48.458 ThaliTest[1037:3395059] server session: not connected Apple-IpadAir2-1
,2016-01-07 10:48:48.729 ThaliTest[1037:3395019] server session: connected
2016-01-07 10:48:48.729 ThaliTest[1037:3395019] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-07 10:48:48.787 ThaliTest[1037:3394111] server relay: connected (to port: 65007)
,2016-01-07T09:48:48.794Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-07T09:48:49.257Z SendDataTCPServer.js: TCP/IP server has received 4238 bytes of data
,2016-01-07T09:48:49.271Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-07T09:48:49.286Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-07T09:48:49.302Z SendDataTCPServer.js: TCP/IP server has received 39349 bytes of data
,2016-01-07T09:48:49.318Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-07T09:48:49.329Z SendDataTCPServer.js: TCP/IP server has received 58035 bytes of data
,2016-01-07T09:48:49.345Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-07T09:48:49.358Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2016-01-07T09:48:49.373Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-07T09:48:49.387Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-07T09:48:49.403Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-07 10:48:49.427 ThaliTest[1037:3395019] server session: not connected Apple-Iphone5s-1
,teardown
,testSendData stopped
,2016-01-07 10:49:13.526 ThaliTest[1037:3394291] jxcore: stopBroadcasting
2016-01-07 10:49:13.526 ThaliTest[1037:3394291] THEMultipeerSession stopping peer
2016-01-07 10:49:13.527 ThaliTest[1037:3394291] multipeer session: stop timer
2016-01-07 10:49:13.,527 ThaliTest[1037:3394291] server session: disconnect
2016-01-07 10:49:13.527 ThaliTest[1037:3394291] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-07 10:49:13.534 ThaliTest[1037:3394291] server session: disconnect
2016-01-07 10:49:13.534 ThaliTest[1037:3394291] server session: stateChange:2->0 Apple-Iphone5s-1
2016-01-07 10:49:13.539 ThaliTest[1037:3394291] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-07T09:49:13.557Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-07T09:49:13.559Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-07T09:49:13.560Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
