#### Test 54312298af2c956_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/281448A0-E966-442C-9663-4FC26263971C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/281448A0-E966-442C-9663-4FC26263971C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15FA10BF-8145-4DEB-A3C9-50569656FD6E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62360"
,(lldb)     command script import "/tmp/281448A0-E966-442C-9663-4FC26263971C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 03:05:11.797 ThaliTest[618:1080579] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B8D7B64-011C-4D2B-B4C5-3E7841B5BD22/Library/Cookies/Cookies.binarycookies
,2015-12-23 03:05:11.936 ThaliTest[618:1080579] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 03:05:11.938 ThaliTest[618:1080579] Multi-tasking -> Device: YES, App: YES
,2015-12-23 03:05:11.945 ThaliTest[618:1080579] Unlimited access to network resources
,2015-12-23 03:05:11.960 ThaliTest[618:1080579] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 03:05:22.118 ThaliTest[618:1080579] Resetting plugins due to page load.
,2015-12-23 03:05:26.122 ThaliTest[618:1080579] Finished load of: file:///var/mobile/Containers/Bundle/Application/15FA10BF-8145-4DEB-A3C9-50569656FD6E/ThaliTest.app/www/index.html
,2015-12-23 03:05:26.337 ThaliTest[618:1080579] JXcore Cordova plugin initializing
,2015-12-23 03:05:26.339 ThaliTest[618:1080777] JXcore instance initializing
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
,found test : ./testSendData2.js
,2015-12-23 03:05:28.807 ThaliTest[618:1080579] THREAD WARNING: ['JXcore'] took '167.259033' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-23 03:11:59.962 ThaliTest[618:1080777] jxcore: startBroadcasting
,2015-12-23 03:11:59.974 ThaliTest[618:1080777] server: starting Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:11:59.975 ThaliTest[618:1080777] multipeer session: start timer: 0x1bc4ea70
2015-12-23 03:11:59.976 ThaliTest[618:1080777] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4216
2015-12-23 03:11:59.976 ThaliTest[618:1080777] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-23 03:12:01.707 ThaliTest[618:1080579] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT6053.eofveg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
2015-12-23 03:12:02.600 ThaliTest[618:1080777] jxcore: stopBroadcasting
,2015-12-23 03:12:02.601 ThaliTest[618:1080777] THEMultipeerSession stopping peer
,2015-12-23 03:12:02.601 ThaliTest[618:1080777] multipeer session: stop timer
,2015-12-23 03:12:02.602 ThaliTest[618:1080777] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,check server
serverPort is 57094
,2015-12-23 03:12:02.876 ThaliTest[618:1080777] jxcore: startBroadcasting
,2015-12-23 03:12:02.879 ThaliTest[618:1080777] server: starting Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:02.879 ThaliTest[618:1080777] multipeer session: start timer: 0x1bc4e400
2015-12-23 03:12:02.880 ThaliTest[618:1080777] THEMultipeerSession i,nitialized peer Apple-Iphone5-1_PT4216
2015-12-23 03:12:02.880 ThaliTest[618:1080777] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2015-12-23T02:12:02.884Z SendDataTCPServer.js: TCP/IP server is bound to port: 57094
,2015-12-23 03:12:03.902 ThaliTest[618:1080579] client: found peer: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:03.902 ThaliTest[618:1080579] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone,6-1_PT6053.vUErSg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:03.906Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23T02:12:03.907Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:03.907Z SendDataConnector.js: do connect now
,2015-12-23 03:12:03.908 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:03.909 ThaliTest[618:1080777] client session: connect
2015-12-23 03:12:03.909 ThaliTest[618:1080777] client session: stateChange:0->1 Apple-Ip,hone6-1_PT6053.vUErSg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23 03:12:04.057 ThaliTest[618:1080579] client: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.FlW6Iw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23 03:12:04.331 ThaliTest[618:1080579] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.SE3R7g==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: t,rue
,2015-12-23 03:12:06.890 ThaliTest[618:1081459] client session: connected
2015-12-23 03:12:06.890 ThaliTest[618:1081459] client session: stateChange:1->2 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:06.897 ThaliTest[618:1081457] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:06.897 ThaliTest[618:1081457] jxcore: connect: success
2015-12-23T02:12:06.898Z SendDataConnector.js: CLIENT connected to 57097, error: null
,2015-12-23T02:12:06.899Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:06.901 ThaliTest[618:1080579] client: relay established
2015-12-23 03:12:06.902 ThaliTest[618:1080579] client: new accepted socket: 0x1bc5c830
,2015-12-23T02:12:06.917Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:07.483Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-23T02:12:07.511Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-23T02:12:07.538Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-23T02:12:07.552Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-23T02:12:07.553Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-23T02:12:07.556Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:07.556Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:07.557 ThaliTest[618:1080777] jxcore: disconnect
2015-12-23 03:12:07.557 ThaliTest[618:1080777] client session: disconnectFromPeer: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:07.557 ThaliTest[618:1080777] client session: disconnect
,2015-12-23 03:12:07.558 ThaliTest[618:1080777] client session: stateChange:2->0 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:07.565 ThaliTest[618:1080777] jxcore: disconnect: success
2015-12-23T02:12:07.566Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.vUErSg==
---- round done--------
startWithNextDevice
device[2]: Appl,e-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:07.567Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:07.568Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:,07.568Z SendDataConnector.js: do connect now
,2015-12-23 03:12:07.568 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:07.569 ThaliTest[618:1080777] client session: connect
2015-12-23 03:12:07.569 ThaliTest[618:1080777] client session: stateChange:0->1 Apple-Ip,hone6-1_PT6053.eofveg==
,2015-12-23 03:12:07.869 ThaliTest[618:1080579] client: lost peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:07.870 ThaliTest[618:1080579] client session: onPeerLost: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:07.870 ThaliTest[618:1080579] cl,ient session: onLinkFailure: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:07.870 ThaliTest[618:1080579] client session: disconnect
2015-12-23 03:12:07.871 ThaliTest[618:1080579] client session: stateChange:1->0 Apple-Iphone6-1_PT6053.eofveg==
2015-1,2-23 03:12:07.871 ThaliTest[618:1080579] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:07.871 ThaliTest[618:1080579] jxcore: connect: fail: Peer disconnected
2015-12-23T02:12:07.872Z SendDataConnector.js: CLIENT co,nnected to 0, error: Peer disconnected
2015-12-23T02:12:07.872Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-23T02:12:07.872Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":false}]
,2015-12-23T02:12:12.878Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:12.879Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,appEnteredForeground wasn't registered
,2015-12-23 03:12:17.884 ThaliTest[618:1080777] jxcore: disconnect
,2015-12-23 03:12:17.887 ThaliTest[618:1080777] jxcore: disconnect: fail
,2015-12-23T02:12:17.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:17.889Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
,2015-12-23T02:12:17.889Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:17.890Z SendDataConnector.js: do connect now
,2015-12-23 03:12:17.891 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:17.891 ThaliTest[618:1080777] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:17.891 ThaliTest[618:1080777] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:17.892Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:17.893Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-23T02:12:17.893Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:22.897Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:22.897Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,appEnteringBackground wasn't registered
,2015-12-23 03:12:27.901 ThaliTest[618:1080777] jxcore: disconnect
2015-12-23 03:12:27.902 ThaliTest[618:1080777] jxcore: disconnect: fail
2015-12-23T02:12:27.902Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg=,=
2015-12-23T02:12:27.903Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:27.903Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
201,5-12-23T02:12:27.903Z SendDataConnector.js: do connect now
,2015-12-23 03:12:27.904 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:27.905 ThaliTest[618:1080777] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:27.905 ThaliTest[618:1080777] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:27.905Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:27.906Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-23T02:12:27.907Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23 03:12:32.881 ThaliTest[618:1080579] multipeer session: restart
,2015-12-23T02:12:32.908Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:32.908Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:32.917 ThaliTest[618:1080579] client: found peer: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:32.917 ThaliTest[618:1080579] client: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:32.917 ThaliTest[618:1080579] client:, found peer: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:37.913 ThaliTest[618:1080777] jxcore: disconnect
2015-12-23 03:12:37.913 ThaliTest[618:1080777] jxcore: disconnect: fail
2015-12-23T02:12:37.914Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg=,=
2015-12-23T02:12:37.914Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:37.915Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:37.915Z SendDataConnector.js: do connect now
,2015-12-23 03:12:37.916 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:37.916 ThaliTest[618:1080777] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:37.917 ThaliTest[618:1080777] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:37.917Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:37.917Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-23T02:12:37.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:42.925Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:42.925Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:47.931 ThaliTest[618:1080777] jxcore: disconnect
2015-12-23 03:12:47.932 ThaliTest[618:1080777] jxcore: disconnect: fail
2015-12-23T02:12:47.932Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg=,=
2015-12-23T02:12:47.933Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:47.933Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:47.933Z SendDataConnector.js: do connect now
,2015-12-23 03:12:47.934 ThaliTest[618:1080777] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:47.935 ThaliTest[618:1080777] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:47.935 ThaliTest[618:1080777] jxco,re: connect: fail: Peer unreachable
,2015-12-23T02:12:47.935Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:47.936Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2015-12-23T02:12:47.936Z SendDataConnector.js: CLIENT Stop now
,2015-12-23 03:12:47.937 ThaliTest[618:1080777] jxcore: disconnect
2015-12-23 03:12:47.937 ThaliTest[618:1080777] jxcore: disconnect: fail
2015-12-23T02:12:47.937Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg=,=
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23T02:12:47.938Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23T02:12:47.938Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23T02:12:47.938Z SendDataConnector.js: do connect now
,2015-12-23 03:12:47.939 ThaliTest[618:1080777] jxcore: connect Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:47.939 ThaliTest[618:1080777] client session: connect
2015-12-23 03:12:47.939 ThaliTest[618:1080777] client session: stateChange:0->1 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:48.820 ThaliTest[618:1080579] multipeer session: reset timer
2015-12-23 03:12:48.820 ThaliTest[618:1080579] multipeer session: stop timer
2015-12-23 03:12:48.820 ThaliTest[618:1080579] multipeer session: start timer: 0x1bc4e400
2015-12-,23 03:12:48.820 ThaliTest[618:1080579] server session: connect
,2015-12-23 03:12:48.821 ThaliTest[618:1080579] server session: stateChange:0->1 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:48.828 ThaliTest[618:1080579] server: accepting invitation Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:51.910 ThaliTest[618:1080579] multipeer session: reset timer
,2015-12-23 03:12:51.912 ThaliTest[618:1080579] multipeer session: stop timer
,2015-12-23 03:12:51.913 ThaliTest[618:1080579] multipeer session: start timer: 0x1bc4e400
,2015-12-23 03:12:51.914 ThaliTest[618:1080579] server session: connect
,2015-12-23 03:12:51.915 ThaliTest[618:1080579] server session: stateChange:0->1 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:51.940 ThaliTest[618:1080579] server: accepting invitation Apple-Iphone6-1_PT6053
,2015-12-23 03:12:51.977 ThaliTest[618:1081808] client session: connected
,2015-12-23 03:12:51.978 ThaliTest[618:1081808] client session: stateChange:1->2 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:52.028 ThaliTest[618:1081808] client session: fireConnectCallback: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:52.029 ThaliTest[618:1081808] jxcore: connect: success
2015-12-23T02:12:52.029Z SendDataConnector.js: CLIENT connected to 57111, error: null
2015-12-23T02:12:52.029Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:52.033 ThaliTest[618:1080579] client: relay established
2015-12-23 03:12:52.035 ThaliTest[618:1080579] client: new accepted socket: 0x1bc7a840
,2015-12-23 03:12:52.038 ThaliTest[618:1081808] server session: connected
,2015-12-23 03:12:52.040 ThaliTest[618:1081808] server session: stateChange:1->2 Apple-IpadAir2-1_PT8230
,2015-12-23T02:12:52.044Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23 03:12:52.056 ThaliTest[618:1080579] server relay: connected (to port: 57094)
,2015-12-23T02:12:52.587Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:52.605Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23T02:12:52.627Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-23 03:12:52.643 ThaliTest[618:1081807] server session: not connected Apple-IpadAir2-1_PT8230
,2015-12-23T02:12:52.654Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-23T02:12:52.667Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-23T02:12:52.680Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-23T02:12:52.695Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-23T02:12:52.697Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-23T02:12:52.698Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:52.699Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:52.700 ThaliTest[618:1080777] jxcore: disconnect
,2015-12-23 03:12:52.702 ThaliTest[618:1080777] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:52.703 ThaliTest[618:1080777] client session: disconnect
,2015-12-23 03:12:52.703 ThaliTest[618:1080777] client session: stateChange:2->0 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:52.716 ThaliTest[618:1080777] jxcore: disconnect: success
,2015-12-23T02:12:52.720Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:52.729Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:52.730Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23T02:12:52.731Z SendDataConnector.js: do connect now
,2015-12-23 03:12:52.732 ThaliTest[618:1080777] jxcore: connect Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:52.733 ThaliTest[618:1080777] client session: connect
,2015-12-23 03:12:52.734 ThaliTest[618:1080777] client session: stateChange:0->1 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:53.533 ThaliTest[618:1080579] multipeer session: reset timer
2015-12-23 03:12:53.534 ThaliTest[618:1080579] multipeer session: stop timer
2015-12-23 03:12:53.534 ThaliTest[618:1080579] multipeer session: start timer: 0x1bc4e400
2015-12-,23 03:12:53.534 ThaliTest[618:1080579] server session: connect
2015-12-23 03:12:53.534 ThaliTest[618:1080579] server session: stateChange:0->1 Apple-Iphone5s-1_PT4021
2015-12-23 03:12:53.540 ThaliTest[618:1080579] server: accepting invitation Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:54.983 ThaliTest[618:1081779] server session: connected
2015-12-23 03:12:54.985 ThaliTest[618:1081779] server session: stateChange:1->2 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:55.040 ThaliTest[618:1080579] server relay: connected (to port: 57094)
,2015-12-23T02:12:55.046Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:55.274Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-23T02:12:55.512Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-23T02:12:55.527Z SendDataTCPServer.js: TCP/IP server has received 58704 bytes of data
,2015-12-23T02:12:55.544Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-23T02:12:55.561Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:55.641 ThaliTest[618:1081808] server session: not connected Apple-Iphone6-1_PT6053
,2015-12-23 03:12:55.838 ThaliTest[618:1081808] client session: connected
2015-12-23 03:12:55.838 ThaliTest[618:1081808] client session: stateChange:1->2 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:55.846 ThaliTest[618:1081779] client session: fireConnectCallback: Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:55.846 ThaliTest[618:1081779] jxcore: connect: success
2015-12-23T02:12:55.847Z SendDataConnector.js: CLIENT connected to 57116, error: null
2015-12-23T02:12:55.847Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:55.849 ThaliTest[618:1080579] client: relay established
2015-12-23 03:12:55.850 ThaliTest[618:1080579] client: new accepted socket: 0x1bbcc110
,2015-12-23T02:12:55.860Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23 03:12:56.175 ThaliTest[618:1081807] server session: connected
2015-12-23 03:12:56.175 ThaliTest[618:1081807] server session: stateChange:1->2 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:56.182 ThaliTest[618:1080579] server relay: connected (to port: 57094)
,2015-12-23T02:12:56.373Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:56.561Z SendDataTCPServer.js: TCP/IP server has received 17094 bytes of data
,2015-12-23T02:12:56.577Z SendDataTCPServer.js: TCP/IP server has received 58278 bytes of data
,2015-12-23T02:12:56.598Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-23T02:12:56.603Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-23T02:12:56.618Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23T02:12:56.621Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-23T02:12:56.708Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-23T02:12:56.709Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-23T02:12:56.710Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:56.710Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:56.711 ThaliTest[618:1080777] jxcore: disconnect
,2015-12-23 03:12:56.712 ThaliTest[618:1080777] client session: disconnectFromPeer: Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:56.712 ThaliTest[618:1080777] client session: disconnect
,2015-12-23 03:12:56.713 ThaliTest[618:1080777] client session: stateChange:2->0 Apple-Iphone5s-1_PT4021.SE3R7g==
,2015-12-23 03:12:56.788 ThaliTest[618:1080777] jxcore: disconnect: success
,2015-12-23T02:12:56.791Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT4021.SE3R7g==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-23T02:12:56.796Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:56.796Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:56.955 ThaliTest[618:1081779] server session: not connected Apple-Iphone5s-1_PT4021
,teardown
,testSendData stopped
,2015-12-23 03:12:59.409 ThaliTest[618:1080777] jxcore: stopBroadcasting
2015-12-23 03:12:59.410 ThaliTest[618:1080777] THEMultipeerSession stopping peer
2015-12-23 03:12:59.410 ThaliTest[618:1080777] multipeer session: stop timer
2015-12-23 03:12:59.410, ThaliTest[618:1080777] server session: disconnect
2015-12-23 03:12:59.410 ThaliTest[618:1080777] server session: stateChange:2->0 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:59.418 ThaliTest[618:1080777] server session: disconnect
2015-12-23 03:12:59.418 ThaliTest[618:1080777] server session: stateChange:2->0 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:59.429 ThaliTest[618:1080777] server session: disconnect
2015-12-23 03:12:59.430 ThaliTest[618:1080777] server session: stateChange:2->0 Apple-Iphone5s-1_PT4021
,2015-12-23 03:12:59.445 ThaliTest[618:1080777] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-23T02:12:59.460Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:59.461Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:59.462Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:59.463Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
