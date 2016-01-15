#### Test 56204092c98eeae_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/599F5208-A497-429C-9248-F396FE3021A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/599F5208-A497-429C-9248-F396FE3021A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/56204092c98eeae/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/62289613-7967-42F6-81F0-F49F416D311F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56554"
,(lldb)     command script import "/tmp/599F5208-A497-429C-9248-F396FE3021A5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-15 19:43:04.303 ThaliTest[2005:4722895] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9F5442B5-2F56-4BB0-9C96-7208526B3A9B/Library/Cookies/Cookies.binarycookies
,2016-01-15 19:43:04.573 ThaliTest[2005:4722895] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-15 19:43:04.574 ThaliTest[2005:4722895] Multi-tasking -> Device: YES, App: YES
,2016-01-15 19:43:04.581 ThaliTest[2005:4722895] Unlimited access to network resources
,2016-01-15 19:43:04.591 ThaliTest[2005:4722895] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-15 19:43:08.941 ThaliTest[2005:4722895] Resetting plugins due to page load.
,2016-01-15 19:43:10.519 ThaliTest[2005:4722895] Finished load of: file:///var/mobile/Containers/Bundle/Application/62289613-7967-42F6-81F0-F49F416D311F/ThaliTest.app/www/index.html
,2016-01-15 19:43:10.711 ThaliTest[2005:4722895] JXcore Cordova plugin initializing
2016-01-15 19:43:10.712 ThaliTest[2005:4723066] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
,--- start :testFindPeers.js---
testFindPeers created [object Object]
serverPort is 8876
,2016-01-15 19:48:23.843 ThaliTest[2005:4723066] jxcore: startBroadcasting
,2016-01-15 19:48:23.857 ThaliTest[2005:4723066] server: starting Apple-Iphone5s-1_PT6477.NhmDbg==
,2016-01-15 19:48:23.862 ThaliTest[2005:4723066] multipeer session: start timer: 0x17b98470
2016-01-15 19:48:23.862 ThaliTest[2005:4723066] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6477
2016-01-15 19:48:23.862 ThaliTest[2005:4723066] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-15 19:48:24.874 ThaliTest[2005:4722895] client: found peer: Apple-Iphone6-1_PT3224.cXLr/Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3224.cXLr/Q==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT3224.cXLr/Q==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-15 19:48:25.428 ThaliTest[2005:4722895] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:29.435 ThaliTest[2005:4722895] client: found peer: Apple-IpadAir2-1_PT6810.+fMbbA==
,teardown
,testFindPeers stopped
2016-01-15 19:48:30.103 ThaliTest[2005:4723066] jxcore: stopBroadcasting
2016-01-15 19:48:30.103 ThaliTest[2005:4723066] THEMultipeerSession stopping peer
2016-01-15 19:48:30.103 ThaliTest[2005:4723066] multipeer session: stop timer
2016-01-15 19:48:30.103 ThaliTest[2005:4723066] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
daya100000
check server
serverPort is 60282
2016-01-15 19:48:30.111 ThaliTest[2005:4723066] jxcore: startBroadcasting
,2016-01-15 19:48:30.116 ThaliTest[2005:4723066] server: starting Apple-Iphone5s-1_PT6477.TN0Czw==
2016-01-15 19:48:30.117 ThaliTest[2005:4723066] multipeer session: start timer: 0x17babd50
2016-01-15 19:48:30.117 ThaliTest[2005:4723066] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT6477
2016-01-15 19:48:30.117 ThaliTest[2005:4723066] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-15T18:48:30.119Z SendDataTCPServer.js: TCP/IP server is bound to port: 60282
,2016-01-15 19:48:30.925 ThaliTest[2005:4722895] client: found peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.925 ThaliTest[2005:4722895] client: found peer: Apple-Iphone5s-1_PT6477.NhmDbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:30.928Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:30.929Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:30.929Z SendDataConnector.js:, do connect now
,2016-01-15 19:48:30.930 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:30.931 ThaliTest[2005:4723066] client session: connect
2016-01-15 19:48:30.931 ThaliTest[2005:4723066] client session: stateChange:0->1 Apple,-Iphone5-1_PT5004.158h0w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:31.247 ThaliTest[2005:4722895] client: lost peer: Apple-Iphone5s-1_PT6477.NhmDbg==
2016-01-15 19:48:31.248 ThaliTest[2005:4722895] client session: onPeerLost: Apple-Iphone5s-1_PT6477.NhmDbg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT6477.NhmDbg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
2016-01-15 19:48:31.248 ThaliTest[2005:4722895] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
peerAvailabilityChanged [{"peerIdenti,fier":"Apple-IpadAir2-1_PT6810.kDDcMw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-15 19:48:31.249 ThaliTest[2005:4722895] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
peerAvailabilityChanged [{"peerI,dentifier":"Apple-Iphone6-1_PT3224.81B+Sg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2016-01-15 19:48:31.250 ThaliTest[2005:4722895] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
peerAvailabilityChanged [{"p,eerIdentifier":"Apple-Iphone5-1_PT5004.rhpQQw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-15 19:48:33.028 ThaliTest[2005:4722895] client: lost peer: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:33.028 ThaliTest[2005:4722895] client session: onPeerLost: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:33.028 ThaliTest[2005:4722895] client session: onLinkFailure: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:33.028 ThaliTest[2005:4722895] client session: disconnect
2016-01-15 19:48:33.028 ThaliTest[2005:4722895] client session: stateChange:1->0 Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15 19:48:33.029 ThaliTest[2005:4722895] client session: fireConnectCallback: Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:33.029 ThaliTest[2005:4722895] jxcore: connect: fail: Peer disconnected
2016-01-15T18:48:33.029Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-15T18:48:33.030Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-15T18:48:33.030Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5004.158h0w==","peerName":"(null)","peerAvailable":false}]
,2016-01-15T18:48:38.040Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:38.040Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:43.044 ThaliTest[2005:4723066] jxcore: disconnect
2016-01-15 19:48:43.045 ThaliTest[2005:4723066] jxcore: disconnect: fail
2016-01-15T18:48:43.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:43.045Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:48:43.045Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:43.045Z SendDataConnector.js: do connect now
2016-01-15 19:48:43.045 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:43.046 ThaliTest[2005:4723066] client: connect: unreachable Apple-Iphone5-1_PT50,04.158h0w==
2016-01-15 19:48:43.046 ThaliTest[2005:4723066] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:43.046Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:43.046Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer unreachable
2016-01-15T18:48:43.049Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:48.054Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15T18:48:48.055Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:48:53.063 ThaliTest[2005:4723066] jxcore: disconnect
2016-01-15 19:48:53.064 ThaliTest[2005:4723066] jxcore: disconnect: fail
2016-01-15T18:48:53.064Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:48:53.064Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:48:53.064Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:53.064Z SendDataConnector.js: do connect now
2016-01-15 19:48:53.065 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:53.065 ThaliTest[2005:4723066] client: connect: unreachable Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:48:53.065 ThaliTest[2005:4723066] jxcore: connect: fail: Peer unreachable
2016-01-15T18:48:53.065Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:48:53.065Z SendDataConnector.js: CLIENT Can n,ot Connect: Peer unreachable
2016-01-15T18:48:53.067Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:48:58.075Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:48:58.075Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:49:00.117 ThaliTest[2005:4722895] multipeer session: restart
,2016-01-15 19:49:00.136 ThaliTest[2005:4722895] client: found peer: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:00.136 ThaliTest[2005:4722895] client: found peer: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:00.137 ThaliTest[2005:4722895] client: found peer: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:03.082 ThaliTest[2005:4723066] jxcore: disconnect
2016-01-15 19:49:03.083 ThaliTest[2005:4723066] jxcore: disconnect: fail
2016-01-15T18:49:03.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0,w==
2016-01-15T18:49:03.083Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:49:03.083Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:49:03.083Z SendDataConnector.js: do connect now
2016-01-15 19:49:03.083 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:49:03.084 ThaliTest[2005:4723066] client: connect: unreachable Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:03.084 ThaliTest[2005:4723066] jxcore: connect: fail: Peer unreachable
2016-01-15T18:49:03.085Z SendDataConnector.js: CLIENT con,nected to 0, error: Peer unreachable
2016-01-15T18:49:03.085Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-15T18:49:03.085Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-15T18:49:08.087Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:49:08.087Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT5004.158h0w==
,2016-01-15 19:49:13.093 ThaliTest[2005:4723066] jxcore: disconnect
2016-01-15 19:49:13.094 ThaliTest[2005:4723066] jxcore: disconnect: fail
2016-01-15T18:49:13.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0w==
2016-01-15T18:49:13.094Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT5004.158h0w== with availability status: true
2016-01-15T18:49:13.094Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.158h0w==
2,016-01-15T18:49:13.094Z SendDataConnector.js: do connect now
,2016-01-15 19:49:13.095 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:13.095 ThaliTest[2005:4723066] client: connect: unreachable Apple-Iphone5-1_PT5004.158h0w==
2016-01-15 19:49:13.095 ThaliTest[2005:4723066] j,xcore: connect: fail: Peer unreachable
2016-01-15T18:49:13.095Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-15T18:49:13.096Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-15T18:49:13.096Z SendDataConnector.js: CLIENT Stop now
,2016-01-15 19:49:13.097 ThaliTest[2005:4723066] jxcore: disconnect
2016-01-15 19:49:13.097 ThaliTest[2005:4723066] jxcore: disconnect: fail
2016-01-15T18:49:13.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.158h0w==
---- round done--------
,startWithNextDevice
device[2]: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15T18:49:13.099Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:13.099Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15T18:49:13.099Z SendDataConnector.js: do connect now
,2016-01-15 19:49:13.099 ThaliTest[2005:4723066] jxcore: connect Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:13.100 ThaliTest[2005:4723066] client session: connect
2016-01-15 19:49:13.100 ThaliTest[2005:4723066] client session: stateChange:0->1 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:14.991 ThaliTest[2005:4722895] multipeer session: reset timer
2016-01-15 19:49:14.992 ThaliTest[2005:4722895] multipeer session: stop timer
2016-01-15 19:49:14.992 ThaliTest[2005:4722895] multipeer session: start timer: 0x17babd50
2016-01-15 19:49:14.992 ThaliTest[2005:4722895] server session: connect
2016-01-15 19:49:14.992 ThaliTest[2005:4722895] server session: stateChange:0->1 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:14.996 ThaliTest[2005:4722895] server: accepting invitation Apple-Iphone5-1_PT5004
,2016-01-15 19:49:16.544 ThaliTest[2005:4724000] client session: connected
2016-01-15 19:49:16.544 ThaliTest[2005:4724000] client session: stateChange:1->2 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:16.585 ThaliTest[2005:4723985] client session: fireConnectCallback: Apple-IpadAir2-1_PT6810.kDDcMw==
2016-01-15 19:49:16.585 ThaliTest[2005:4723985] jxcore: connect: success
2016-01-15T18:49:16.586Z SendDataConnector.js: CLIENT connected, to 60287, error: null
2016-01-15T18:49:16.586Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:16.587 ThaliTest[2005:4722895] client: relay established
2016-01-15 19:49:16.588 ThaliTest[2005:4722895] client: new accepted socket: 0x17bbed10
,2016-01-15T18:49:16.600Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:16.863Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-15T18:49:16.888Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-15T18:49:16.888Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:16.889Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:16.889Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:16.890 ThaliTest[2005:4723066] jxcore: disconnect
,2016-01-15 19:49:16.891 ThaliTest[2005:4723066] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:16.891 ThaliTest[2005:4723066] client session: disconnect
,2016-01-15 19:49:16.892 ThaliTest[2005:4723066] client session: stateChange:2->0 Apple-IpadAir2-1_PT6810.kDDcMw==
,2016-01-15 19:49:16.959 ThaliTest[2005:4723066] jxcore: disconnect: success
,2016-01-15T18:49:16.960Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6810.kDDcMw==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15T18:49:16.961Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15T18:49:16.961Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15T18:49:16.962Z SendDataConnector.js: do connect now
,2016-01-15 19:49:16.962 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:16.963 ThaliTest[2005:4723066] client session: connect
,2016-01-15 19:49:16.963 ThaliTest[2005:4723066] client session: stateChange:0->1 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:17.585 ThaliTest[2005:4724000] server session: connected
,2016-01-15 19:49:17.585 ThaliTest[2005:4724000] server session: stateChange:1->2 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:17.652 ThaliTest[2005:4722895] server relay: connected (to port: 60282)
,2016-01-15T18:49:17.662Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:18.108Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-15T18:49:18.122Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-15T18:49:18.171Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2016-01-15T18:49:18.183Z SendDataTCPServer.js: TCP/IP server has received 93460 bytes of data
,2016-01-15T18:49:18.198Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:18.310 ThaliTest[2005:4723984] server session: not connected Apple-Iphone5-1_PT5004
,2016-01-15 19:49:18.705 ThaliTest[2005:4722895] multipeer session: reset timer
2016-01-15 19:49:18.705 ThaliTest[2005:4722895] multipeer session: stop timer
2016-01-15 19:49:18.705 ThaliTest[2005:4722895] multipeer session: start timer: 0x17babd50
2016-01-15 19:49:18.706 ThaliTest[2005:4722895] server session: connect
2016-01-15 19:49:18.706 ThaliTest[2005:4722895] server session: stateChange:0->1 Apple-Iphone6-1_PT3224
2016-01-15 19:49:18.709 ThaliTest[2005:4722895] server: accepting invitation Apple-Iphone6-1_PT3224
,2016-01-15 19:49:19.623 ThaliTest[2005:4722895] multipeer session: reset timer
2016-01-15 19:49:19.623 ThaliTest[2005:4722895] multipeer session: stop timer
2016-01-15 19:49:19.623 ThaliTest[2005:4722895] multipeer session: start timer: 0x17babd50
2016-,01-15 19:49:19.624 ThaliTest[2005:4722895] server session: connect
2016-01-15 19:49:19.624 ThaliTest[2005:4722895] server session: stateChange:0->1 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:19.627 ThaliTest[2005:4722895] server: accepting invitation Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:19.754 ThaliTest[2005:4723985] client session: connected
2016-01-15 19:49:19.754 ThaliTest[2005:4723985] client session: stateChange:1->2 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:19.778 ThaliTest[2005:4724000] client session: fireConnectCallback: Apple-Iphone6-1_PT3224.81B+Sg==
2016-01-15 19:49:19.778 ThaliTest[2005:4724000] jxcore: connect: success
2016-01-15T18:49:19.778Z SendDataConnector.js: CLIENT connected ,to 60291, error: null
2016-01-15T18:49:19.779Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:19.780 ThaliTest[2005:4722895] client: relay established
2016-01-15 19:49:19.780 ThaliTest[2005:4722895] client: new accepted socket: 0x17bca2b0
,2016-01-15T18:49:19.793Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:20.225Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-15T18:49:20.238Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:20.238Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:20.239Z SendDataConnector.js: CLIENT Stop now
,2016-01-15T18:49:20.239Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:20.240 ThaliTest[2005:4723066] jxcore: disconnect
,2016-01-15 19:49:20.240 ThaliTest[2005:4723066] client session: disconnectFromPeer: Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:20.241 ThaliTest[2005:4723066] client session: disconnect
,2016-01-15 19:49:20.241 ThaliTest[2005:4723066] client session: stateChange:2->0 Apple-Iphone6-1_PT3224.81B+Sg==
,2016-01-15 19:49:20.307 ThaliTest[2005:4723066] jxcore: disconnect: success
,2016-01-15T18:49:20.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3224.81B+Sg==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:20.309Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:20.309Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15T18:49:20.309Z SendDataConnector.js: do connect now
,2016-01-15 19:49:20.310 ThaliTest[2005:4723066] jxcore: connect Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:20.310 ThaliTest[2005:4723066] client session: connect
,2016-01-15 19:49:20.311 ThaliTest[2005:4723066] client session: stateChange:0->1 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:21.325 ThaliTest[2005:4724000] server session: connected
2016-01-15 19:49:21.325 ThaliTest[2005:4724000] server session: stateChange:1->2 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:21.331 ThaliTest[2005:4722895] server relay: connected (to port: 60282)
,2016-01-15T18:49:21.341Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15T18:49:21.722Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2016-01-15T18:49:21.736Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-15T18:49:21.750Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-15T18:49:21.763Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2016-01-15T18:49:21.777Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2016-01-15T18:49:21.791Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15 19:49:21.907 ThaliTest[2005:4724000] server session: not connected Apple-Iphone6-1_PT3224
,2016-01-15 19:49:22.836 ThaliTest[2005:4723984] server session: connected
2016-01-15 19:49:22.836 ThaliTest[2005:4723984] server session: stateChange:1->2 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:22.894 ThaliTest[2005:4722895] server relay: connected (to port: 60282)
,2016-01-15T18:49:22.901Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-15 19:49:22.958 ThaliTest[2005:4723985] client session: connected
,2016-01-15 19:49:22.958 ThaliTest[2005:4723985] client session: stateChange:1->2 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:23.025 ThaliTest[2005:4723984] client session: fireConnectCallback: Apple-Iphone5-1_PT5004.rhpQQw==
2016-01-15 19:49:23.025 ThaliTest[2005:4723984] jxcore: connect: success
2016-01-15T18:49:23.026Z SendDataConnector.js: CLIENT connected to 60296, error: null
2016-01-15T18:49:23.026Z SendDataConnector.js: CLIENT starting client 
,2016-01-15 19:49:23.028 ThaliTest[2005:4722895] client: relay established
2016-01-15 19:49:23.028 ThaliTest[2005:4722895] client: new accepted socket: 0x17bd5e80
,2016-01-15T18:49:23.039Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-15T18:49:23.361Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-15T18:49:23.421Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-15T18:49:23.421Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-15T18:49:23.422Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:23.422Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-15 19:49:23.423 ThaliTest[2005:4723066] jxcore: disconnect
,2016-01-15 19:49:23.423 ThaliTest[2005:4723066] client session: disconnectFromPeer: Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:23.424 ThaliTest[2005:4723066] client session: disconnect
,2016-01-15 19:49:23.424 ThaliTest[2005:4723066] client session: stateChange:2->0 Apple-Iphone5-1_PT5004.rhpQQw==
,2016-01-15 19:49:23.487 ThaliTest[2005:4724054] server session: not connected Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:23.493 ThaliTest[2005:4723066] jxcore: disconnect: success
,2016-01-15T18:49:23.494Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5004.rhpQQw==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-15T18:49:23.506Z SendDataConnector.js: CLIENT Stop now
2016-01-15T18:49:23.506Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-15 19:49:24.270 ThaliTest[2005:4723066] jxcore: stopBroadcasting
2016-01-15 19:49:24.271 ThaliTest[2005:4723066] THEMultipeerSession stopping peer
2016-01-15 19:49:24.271 ThaliTest[2005:4723066] multipeer session: stop timer
2016-01-15 19:49:24.271 ThaliTest[2005:4723066] server session: disconnect
2016-01-15 19:49:24.271 ThaliTest[2005:4723066] server session: stateChange:2->0 Apple-Iphone5-1_PT5004
,2016-01-15 19:49:24.275 ThaliTest[2005:4723066] server session: disconnect
2016-01-15 19:49:24.275 ThaliTest[2005:4723066] server session: stateChange:2->0 Apple-Iphone6-1_PT3224
,2016-01-15 19:49:24.282 ThaliTest[2005:4723066] server session: disconnect
2016-01-15 19:49:24.282 ThaliTest[2005:4723066] server session: stateChange:2->0 Apple-IpadAir2-1_PT6810
,2016-01-15 19:49:24.287 ThaliTest[2005:4723066] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
