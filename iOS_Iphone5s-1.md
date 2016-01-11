#### Test 55613145e2b298d_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BB2DF098-97CE-4136-9B11-CC5BCCD9026E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/BB2DF098-97CE-4136-9B11-CC5BCCD9026E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3EA93E9C-499C-41D8-A5E3-D6CA5BC3D126/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52472"
,(lldb)     command script import "/tmp/BB2DF098-97CE-4136-9B11-CC5BCCD9026E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 15:38:13.845 ThaliTest[1740:3769616] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1EA25968-7483-4578-A64C-65EF7B06579F/Library/Cookies/Cookies.binarycookies
,2016-01-11 15:38:14.112 ThaliTest[1740:3769616] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-11 15:38:14.113 ThaliTest[1740:3769616] Multi-tasking -> Device: YES, App: YES
,2016-01-11 15:38:14.120 ThaliTest[1740:3769616] Unlimited access to network resources
,2016-01-11 15:38:14.130 ThaliTest[1740:3769616] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 15:38:18.401 ThaliTest[1740:3769616] Resetting plugins due to page load.
,2016-01-11 15:38:19.945 ThaliTest[1740:3769616] Finished load of: file:///var/mobile/Containers/Bundle/Application/3EA93E9C-499C-41D8-A5E3-D6CA5BC3D126/ThaliTest.app/www/index.html
,2016-01-11 15:38:20.140 ThaliTest[1740:3769616] JXcore Cordova plugin initializing
2016-01-11 15:38:20.141 ThaliTest[1740:3769770] JXcore instance initializing
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
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
2016-01-11 15:43:44.636 ThaliTest[1740:3769770] jxcore: startBroadcasting
,2016-01-11 15:43:44.646 ThaliTest[1740:3769770] server: starting Apple-Iphone5s-1.IqfRAg==
2016-01-11 15:43:44.646 ThaliTest[1740:3769770] multipeer session: start timer: 0x17b50370
2016-01-11 15:43:44.646 ThaliTest[1740:3769770] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-11 15:43:44.646 ThaliTest[1740:3769770] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-11 15:43:45.749 ThaliTest[1740:3769616] client: found peer: Apple-IpadAir2-1.aUvv7Q==
2016-01-11 15:43:45.749 ThaliTest[1740:3769616] client: found peer: Apple-Iphone6-1.UVBQ1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.aUvv7Q==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.aUvv7Q==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-11 15:43:46.727 ThaliTest[1740:3769616] client: found peer: Apple-Iphone5-1.oKqzPQ==
,teardown
,testFindPeers stopped
,2016-01-11 15:43:48.101 ThaliTest[1740:3769770] jxcore: stopBroadcasting
2016-01-11 15:43:48.102 ThaliTest[1740:3769770] THEMultipeerSession stopping peer
2016-01-11 15:43:48.102 ThaliTest[1740:3769770] multipeer session: stop timer
2016-01-11 15:43:48.102 ThaliTest[1740:3769770] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 58456
,2016-01-11 15:43:48.418 ThaliTest[1740:3769770] jxcore: startBroadcasting
,2016-01-11 15:43:48.420 ThaliTest[1740:3769770] server: starting Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:43:48.421 ThaliTest[1740:3769770] multipeer session: start timer: 0x17b48bd0
2016-01-11 15:43:48.421 ThaliTest[1740:3769770] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-11 15:43:48.421 ThaliTest[1740:3769770] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-11T14:43:48.424Z SendDataTCPServer.js: TCP/IP server is bound to port: 58456
,2016-01-11 15:43:49.200 ThaliTest[1740:3769616] client: found peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.200 ThaliTest[1740:3769616] client: found peer: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:49.201 ThaliTest[1740:3769616] client: found peer: ,Apple-IpadAir2-1.3/8jow==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:49,.202Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:49.202Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:49.203Z SendDataConnector.js: do connect now
2016-01-11 15:43:49.203 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:43:49.203 ThaliTest[1740:3769770] client session: connect
2016-01-11 15:43:49.205 ThaliTest[1740:3769770] client session: stateChange:0->1 Apple-Iphone5-1.oKqzPQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.UVBQ1A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.3/8jow==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:49.736 ThaliTest[1740:3769616] client: lost peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.736 ThaliTest[1740:3769616] client session: onPeerLost: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.736 ThaliTest[1740:3769616] client sessio,n: onLinkFailure: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.737 ThaliTest[1740:3769616] client session: disconnect
2016-01-11 15:43:49.737 ThaliTest[1740:3769616] client session: stateChange:1->0 Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.737 Thali,Test[1740:3769616] client session: fireConnectCallback: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.737 ThaliTest[1740:3769616] jxcore: connect: fail: Peer disconnected
2016-01-11T14:43:49.738Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-11T14:43:49.738Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11T14:43:49.738Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-11 15:43:49.797 ThaliTest[1740:3769616] client: lost peer: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:49.797 ThaliTest[1740:3769616] client session: onPeerLost: Apple-Iphone6-1.UVBQ1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.U,VBQ1A==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 15:43:50.334 ThaliTest[1740:3769616] client: found peer: Apple-Iphone5-1.FPpLTg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.FPpLTg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:50.402 ThaliTest[1740:3769616] client: found peer: Apple-Iphone6-1.wtwmkg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.wtwmkg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11T14:43:54.742Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
,2016-01-11T14:43:54.742Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:43:58.303 ThaliTest[1740:3769616] multipeer session: reset timer
2016-01-11 15:43:58.303 ThaliTest[1740:3769616] multipeer session: stop timer
,2016-01-11 15:43:58.304 ThaliTest[1740:3769616] multipeer session: start timer: 0x17b48bd0
2016-01-11 15:43:58.304 ThaliTest[1740:3769616] server session: connect
2016-01-11 15:43:58.305 ThaliTest[1740:3769616] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-11 15:43:58.309 ThaliTest[1740:3769616] server: accepting invitation Apple-Iphone6-1
,2016-01-11 15:43:59.750 ThaliTest[1740:3769770] jxcore: disconnect
2016-01-11 15:43:59.750 ThaliTest[1740:3769770] jxcore: disconnect: fail
2016-01-11T14:43:59.750Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
20,16-01-11T14:43:59.750Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:43:59.750Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:43:59.751Z SendDataConnector.js: do connect now
,2016-01-11 15:43:59.751 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:59.752 ThaliTest[1740:3769770] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:59.752 ThaliTest[1740:3769770] jxcore: connect,: fail: Peer unreachable
2016-01-11T14:43:59.752Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:43:59.752Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T14:43:59.752Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11 15:44:00.666 ThaliTest[1740:3771521] server session: connected
,2016-01-11 15:44:00.666 ThaliTest[1740:3771521] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 15:44:00.723 ThaliTest[1740:3769616] server relay: connected (to port: 58456)
,2016-01-11T14:44:00.733Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:01.245Z SendDataTCPServer.js: TCP/IP server has received 1095 bytes of data
,2016-01-11T14:44:01.260Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2016-01-11T14:44:01.275Z SendDataTCPServer.js: TCP/IP server has received 38325 bytes of data
,2016-01-11T14:44:01.317Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2016-01-11T14:44:01.329Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-11T14:44:01.342Z SendDataTCPServer.js: TCP/IP server has received 82125 bytes of data
,2016-01-11T14:44:01.385Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-11T14:44:01.398Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:01.443 ThaliTest[1740:3771580] server session: not connected Apple-Iphone6-1
,2016-01-11T14:44:04.760Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:04.760Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:09.769 ThaliTest[1740:3769770] jxcore: disconnect
2016-01-11 15:44:09.770 ThaliTest[1740:3769770] jxcore: disconnect: fail
2016-01-11T14:44:09.770Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
20,16-01-11T14:44:09.770Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:09.770Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:09.770Z SendDataConnector.js: do connect now
,2016-01-11 15:44:09.771 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:09.771 ThaliTest[1740:3769770] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:09.771 ThaliTest[1740:3769770] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:09.771Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:09.772Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T14:44:09.772Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:14.774Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:14.774Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:19.776 ThaliTest[1740:3769770] jxcore: disconnect
2016-01-11 15:44:19.776 ThaliTest[1740:3769770] jxcore: disconnect: fail
2016-01-11T14:44:19.777Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
20,16-01-11T14:44:19.777Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:19.777Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:19.777Z SendDataConnector.js: do connect now
,2016-01-11 15:44:19.777 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:19.777 ThaliTest[1740:3769770] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:19.778 ThaliTest[1740:3769770] jxcore: connect: fail: Peer unreachable
,2016-01-11T14:44:19.778Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:19.778Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T14:44:19.779Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:24.787Z SendDataConnector.js: re-try now : Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:24.787Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:44:28.305 ThaliTest[1740:3769616] multipeer session: restart
,2016-01-11 15:44:28.345 ThaliTest[1740:3769616] client: found peer: Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:28.348 ThaliTest[1740:3769616] client: found peer: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:28.349 ThaliTest[1740:3769616] client: found peer: Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:29.797 ThaliTest[1740:3769770] jxcore: disconnect
2016-01-11 15:44:29.797 ThaliTest[1740:3769770] jxcore: disconnect: fail
2016-01-11T14:44:29.797Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:29.798Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1.oKqzPQ== with availability status: true
2016-01-11T14:44:29.798Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.oKqzPQ==
2016-01-11T14:44:29.798Z SendDataConnector.js: do connect now
2016-01-11 15:44:29.798 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:29.798 ThaliTest[1740:3769770] client: connect: unreachable Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:44:29.79,8 ThaliTest[1740:3769770] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:29.798Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:29.798Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRo,undDownNow
2016-01-11T14:44:29.802Z SendDataConnector.js: CLIENT Stop now
2016-01-11 15:44:29.802 ThaliTest[1740:3769770] jxcore: disconnect
2016-01-11 15:44:29.802 ThaliTest[1740:3769770] jxcore: disconnect: fail
2016-01-11T14:44:29.803Z SendDataConne,ctor.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.oKqzPQ==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:29.803Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:29.803Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:29.804Z SendDataConnector.js: do connect now
2016-01-11 15:44:29.804 ThaliTest[1740:3769770] jxcore: connect Apple-IpadAir2-1.3/8jow==
20,16-01-11 15:44:29.804 ThaliTest[1740:3769770] client session: connect
2016-01-11 15:44:29.804 ThaliTest[1740:3769770] client session: stateChange:0->1 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:30.675 ThaliTest[1740:3769616] multipeer session: reset timer
2016-01-11 15:44:30.675 ThaliTest[1740:3769616] multipeer session: stop timer
2016-01-11 15:44:30.676 ThaliTest[1740:3769616] multipeer session: start timer: 0x17b48bd0
2016-01-11 15:44:30.676 ThaliTest[1740:3769616] server session: connect
2016-01-11 15:44:30.676 ThaliTest[1740:3769616] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-11 15:44:30.680 ThaliTest[1740:3769616] server: accepting invitation Apple-IpadAir2-1
,2016-01-11 15:44:34.929 ThaliTest[1740:3771640] server session: connected
2016-01-11 15:44:34.929 ThaliTest[1740:3771640] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11T14:44:34.941Z SendDataTCPServer.js: TCP/IP server connected
2016-01-11 15:44:34.941 ThaliTest[1740:3769616] server relay: connected (to port: 58456)
,2016-01-11 15:44:35.071 ThaliTest[1740:3771654] client session: connected
2016-01-11 15:44:35.071 ThaliTest[1740:3771654] client session: stateChange:1->2 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:35.123 ThaliTest[1740:3771640] client session: fireConnectCallback: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:44:35.123 ThaliTest[1740:3771640] jxcore: connect: success
2016-01-11T14:44:35.124Z SendDataConnector.js: CLIENT connected to 58462, error: null
2016-01-11T14:44:35.124Z SendDataConnector.js: CLIENT starting client 
2016-01-11 15:44:35.125 ThaliTest[1740:3769616] client: relay established
2016-01-11 15:44:35.126 ThaliTest[1740:3769616] client: new accepted socket: 0x17b34180
,2016-01-11T14:44:35.139Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:35.619Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-11T14:44:35.646Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11T14:44:35.678Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-11 15:44:35.690 ThaliTest[1740:3771676] server session: not connected Apple-IpadAir2-1
,2016-01-11T14:44:35.692Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-11T14:44:35.775Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:35.775Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T14:44:35.775Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:44:35.776Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:35.777 ThaliTest[1740:3769770] jxcore: disconnect
,2016-01-11 15:44:35.777 ThaliTest[1740:3769770] client session: disconnectFromPeer: Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:35.778 ThaliTest[1740:3769770] client session: disconnect
,2016-01-11 15:44:35.779 ThaliTest[1740:3769770] client session: stateChange:2->0 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:35.842 ThaliTest[1740:3769770] jxcore: disconnect: success
,2016-01-11T14:44:35.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.3/8jow==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:35.844Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:35.845Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.FPpLTg==
,2016-01-11T14:44:35.845Z SendDataConnector.js: do connect now
,2016-01-11 15:44:35.845 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:35.846 ThaliTest[1740:3769770] client session: connect
,2016-01-11 15:44:35.846 ThaliTest[1740:3769770] client session: stateChange:0->1 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:37.512 ThaliTest[1740:3769616] multipeer session: reset timer
2016-01-11 15:44:37.512 ThaliTest[1740:3769616] multipeer session: stop timer
2016-01-11 15:44:37.512 ThaliTest[1740:3769616] multipeer session: start timer: 0x17b48bd0
2016-,01-11 15:44:37.512 ThaliTest[1740:3769616] server session: connect
2016-01-11 15:44:37.513 ThaliTest[1740:3769616] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-11 15:44:37.516 ThaliTest[1740:3769616] server: accepting invitation Apple-Iphone5-1
,2016-01-11 15:44:38.494 ThaliTest[1740:3771654] client session: connected
2016-01-11 15:44:38.495 ThaliTest[1740:3771654] client session: stateChange:1->2 Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:38.496 ThaliTest[1740:3771654] client session: fireConnectCallback: Apple-Iphone5-1.FPpLTg==
2016-01-11 15:44:38.496 ThaliTest[1740:3771654] jxcore: connect: success
2016-01-11T14:44:38.497Z SendDataConnector.js: CLIENT connected to 58465, error: null
2016-01-11T14:44:38.497Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:38.499 ThaliTest[1740:3769616] client: relay established
2016-01-11 15:44:38.499 ThaliTest[1740:3769616] client: new accepted socket: 0x17b25990
,2016-01-11T14:44:38.510Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:39.128Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T14:44:39.182Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T14:44:39.256Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T14:44:39.270Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T14:44:39.282Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T14:44:39.282Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T14:44:39.282Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:44:39.283Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:39.283 ThaliTest[1740:3769770] jxcore: disconnect
,2016-01-11 15:44:39.284 ThaliTest[1740:3769770] client session: disconnectFromPeer: Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:39.284 ThaliTest[1740:3769770] client session: disconnect
,2016-01-11 15:44:39.285 ThaliTest[1740:3769770] client session: stateChange:2->0 Apple-Iphone5-1.FPpLTg==
,2016-01-11 15:44:39.361 ThaliTest[1740:3769770] jxcore: disconnect: success
,2016-01-11T14:44:39.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.FPpLTg==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:39.363Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:39.363Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:39.364Z SendDataConnector.js: do connect now
,2016-01-11 15:44:39.364 ThaliTest[1740:3769770] jxcore: connect Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:39.365 ThaliTest[1740:3769770] client session: connect
,2016-01-11 15:44:39.365 ThaliTest[1740:3769770] client session: stateChange:0->1 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:40.102 ThaliTest[1740:3771640] server session: connected
2016-01-11 15:44:40.102 ThaliTest[1740:3771640] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 15:44:40.106 ThaliTest[1740:3769616] server relay: connected (to port: 58456)
,2016-01-11T14:44:40.117Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:41.306Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-11T14:44:41.354Z SendDataTCPServer.js: TCP/IP server has received 31755 bytes of data
,2016-01-11T14:44:41.369Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-11T14:44:41.562Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-11T14:44:41.612Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:41.738 ThaliTest[1740:3771655] server session: not connected Apple-Iphone5-1
,2016-01-11 15:44:42.141 ThaliTest[1740:3771655] client session: connected
2016-01-11 15:44:42.141 ThaliTest[1740:3771655] client session: stateChange:1->2 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:42.165 ThaliTest[1740:3771654] client session: fireConnectCallback: Apple-Iphone6-1.wtwmkg==
2016-01-11 15:44:42.165 ThaliTest[1740:3771654] jxcore: connect: success
2016-01-11T14:44:42.166Z SendDataConnector.js: CLIENT connected to 58469, error: null
2016-01-11T14:44:42.166Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:42.168 ThaliTest[1740:3769616] client: relay established
2016-01-11 15:44:42.168 ThaliTest[1740:3769616] client: new accepted socket: 0x17b25b50
,2016-01-11T14:44:42.178Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:42.727Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T14:44:42.787Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T14:44:42.822Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T14:44:42.822Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T14:44:42.823Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:42.823Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:42.824 ThaliTest[1740:3769770] jxcore: disconnect
,2016-01-11 15:44:42.825 ThaliTest[1740:3769770] client session: disconnectFromPeer: Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:42.825 ThaliTest[1740:3769770] client session: disconnect
,2016-01-11 15:44:42.826 ThaliTest[1740:3769770] client session: stateChange:2->0 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:42.896 ThaliTest[1740:3769770] jxcore: disconnect: success
,2016-01-11T14:44:42.897Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.wtwmkg==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-11T14:44:42.911Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:42.911Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:45:07.513 ThaliTest[1740:3769616] multipeer session: restart
,teardown
,testSendData stopped
2016-01-11 15:45:30.594 ThaliTest[1740:3769770] jxcore: stopBroadcasting
2016-01-11 15:45:30.594 ThaliTest[1740:3769770] THEMultipeerSession stopping peer
,2016-01-11 15:45:30.594 ThaliTest[1740:3769770] multipeer session: stop timer
,2016-01-11 15:45:30.595 ThaliTest[1740:3769770] server session: disconnect
2016-01-11 15:45:30.595 ThaliTest[1740:3769770] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-11 15:45:30.598 ThaliTest[1740:3769770] server session: disconnect
2016-01-11 15:45:30.598 ThaliTest[1740:3769770] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-11 15:45:30.607 ThaliTest[1740:3769770] server session: disconnect
2016-01-11 15:45:30.607 ThaliTest[1740:3769770] server session: stateChange:2->0 Apple-Iphone5-1
2016-01-11 15:45:30.610 ThaliTest[1740:3769770] jxcore: stopBroadcasting: success,
StopBroadcasting went ok
,2016-01-11T14:45:30.626Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:30.627Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-11T14:45:30.628Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-11T14:45:30.628Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
