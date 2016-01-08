#### Test 55431344e5dd625_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FE756024-534F-4182-95DD-E8C58B896C53/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FE756024-534F-4182-95DD-E8C58B896C53/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/327A197E-9DDF-4C1D-A1F3-3C663BA197C6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49851"
,(lldb)     command script import "/tmp/FE756024-534F-4182-95DD-E8C58B896C53/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 08:25:11.815 ThaliTest[1471:3160143] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6F9151E-9FCA-4E67-819B-C36F5BF6A5A2/Library/Cookies/Cookies.binarycookies
,2016-01-08 08:25:12.241 ThaliTest[1471:3160143] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 08:25:12.243 ThaliTest[1471:3160143] Multi-tasking -> Device: YES, App: YES
,2016-01-08 08:25:12.253 ThaliTest[1471:3160143] Unlimited access to network resources
,2016-01-08 08:25:12.264 ThaliTest[1471:3160143] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 08:25:21.166 ThaliTest[1471:3160143] Resetting plugins due to page load.
,2016-01-08 08:25:25.115 ThaliTest[1471:3160143] Finished load of: file:///var/mobile/Containers/Bundle/Application/327A197E-9DDF-4C1D-A1F3-3C663BA197C6/ThaliTest.app/www/index.html
,2016-01-08 08:25:25.319 ThaliTest[1471:3160143] JXcore Cordova plugin initializing
,2016-01-08 08:25:25.321 ThaliTest[1471:3160319] JXcore instance initializing
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
,2016-01-08 08:25:26.817 ThaliTest[1471:3160143] THREAD WARNING: ['JXcore'] took '92.078125' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 08:30:18.773 ThaliTest[1471:3160319] jxcore: startBroadcasting
,2016-01-08 08:30:18.792 ThaliTest[1471:3160319] server: starting Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:18.794 ThaliTest[1471:3160319] multipeer session: start timer: 0x193849b0
2016-01-08 08:30:18.795 ThaliTest[1471:3160319] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-08 08:30:18.795 ThaliTest[1471:3160319] jxcore: start,Broadcasting: success
StartBroadcasting started ok
,2016-01-08 08:30:19.828 ThaliTest[1471:3160143] client: found peer: Apple-Iphone6-1.DpDJvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.DpDJvQ==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2016-01-08 08:30:20.469 ThaliTest[1471:3160143] client: found peer: Apple-IpadAir2-1.SM1CRQ==
,teardown
,testFindPeers stopped
2016-01-08 08:30:20.749 ThaliTest[1471:3160319] jxcore: stopBroadcasting
,2016-01-08 08:30:20.749 ThaliTest[1471:3160319] THEMultipeerSession stopping peer
,2016-01-08 08:30:20.750 ThaliTest[1471:3160319] multipeer session: stop timer
,2016-01-08 08:30:20.752 ThaliTest[1471:3160319] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 56403
,2016-01-08 08:30:20.811 ThaliTest[1471:3160319] jxcore: startBroadcasting
,2016-01-08 08:30:20.833 ThaliTest[1471:3160319] server: starting Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:30:20.843 ThaliTest[1471:3160319] multipeer session: start timer: 0x1907ad00
,2016-01-08 08:30:20.851 ThaliTest[1471:3160319] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-08 08:30:20.852 ThaliTest[1471:3160319] jxcore: startBroadcasting: success
,StartBroadcasting started ok
2016-01-08 08:30:20.864 ThaliTest[1471:3160143] client: found peer: Apple-Iphone6-1.DpDJvQ==
null
2016-01-08T07:30:20.868Z SendDataTCPServer.js: TCP/IP server is bound to port: 56403
,2016-01-08 08:30:20.869 ThaliTest[1471:3160143] client: found peer: Apple-Iphone5s-1.NE8BAA==
2016-01-08 08:30:20.871 ThaliTest[1471:3160143] client: found peer: Apple-IpadAir2-1.SM1CRQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:20.881Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:20.883Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:20.884Z SendDataConnector.js: do connect now
,2016-01-08 08:30:20.885 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:20.887 ThaliTest[1471:3160319] client session: connect
,2016-01-08 08:30:20.888 ThaliTest[1471:3160319] client session: stateChange:0->1 Apple-Iphone6-1.DpDJvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:21.883 ThaliTest[1471:3160143] client: lost peer: Apple-Iphone5s-1.NE8BAA==
,2016-01-08 08:30:21.884 ThaliTest[1471:3160143] client session: onPeerLost: Apple-Iphone5s-1.NE8BAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 08:30:21.912 ThaliTest[1471:3160143] client: found peer: Apple-Iphone5-1.kpUZpA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.kpUZpA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 08:30:22.850 ThaliTest[1471:3160143] client: lost peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.851 ThaliTest[1471:3160143] client session: onPeerLost: Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:22.851 ThaliTest[1471:3160143] client session: onLinkFailure: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.852 ThaliTest[1471:3160143] client session: disconnect
2016-01-08 08:30:22.852 ThaliTest[1471:3160143] client session: stateChange,:1->0 Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.854 ThaliTest[1471:3160143] client session: fireConnectCallback: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.854 ThaliTest[1471:3160143] jxcore: connect: fail: Peer disconnected
2016-01-08T07:30:22.856,Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T07:30:22.857Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T07:30:22.858Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChang,ed [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":false}]
,2016-01-08 08:30:22.886 ThaliTest[1471:3160143] client: found peer: Apple-Iphone6-1.O1yvYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.O1yvYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:22.892 ThaliTest[1471:3160143] client: found peer: Apple-IpadAir2-1.5QwW9A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.5QwW9A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:24.056 ThaliTest[1471:3160143] client: lost peer: Apple-IpadAir2-1.SM1CRQ==
2016-01-08 08:30:24.057 ThaliTest[1471:3160143] client session: onPeerLost: Apple-IpadAir2-1.SM1CRQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-,1.SM1CRQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08T07:30:27.859Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:27.861Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.872 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:30:32.873 ThaliTest[1471:3160319] jxcore: disconnect: fail
2016-01-08T07:30:32.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:32.874Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:32.875Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:32.875Z SendDataConnector.js: do connect now
,2016-01-08 08:30:32.876 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.877 ThaliTest[1471:3160319] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.878 ThaliTest[1471:3160319] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:32.879Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:32.880Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:32.880Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:37.883Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:37.883Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:42.893 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:30:42.894 ThaliTest[1471:3160319] jxcore: disconnect: fail
2016-01-08T07:30:42.894Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:42.895Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:42.895Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:42.89,6Z SendDataConnector.js: do connect now
,2016-01-08 08:30:42.896 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:42.897 ThaliTest[1471:3160319] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:42.897 ThaliTest[1471:3160319] jxcore: connect,: fail: Peer unreachable
,2016-01-08T07:30:42.899Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T07:30:42.899Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:42.900Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:47.901Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:47.901Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:50.850 ThaliTest[1471:3160143] multipeer session: restart
,2016-01-08 08:30:50.912 ThaliTest[1471:3160143] client: found peer: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:30:50.913 ThaliTest[1471:3160143] client: found peer: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:30:50.913 ThaliTest[1471:3160143] client: found peer: Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:30:52.905 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:30:52.905 ThaliTest[1471:3160319] jxcore: disconnect: fail
2016-01-08T07:30:52.906Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:52.907Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
,2016-01-08T07:30:52.907Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:52.908Z SendDataConnector.js: do connect now
,2016-01-08 08:30:52.909 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:52.910 ThaliTest[1471:3160319] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:52.910 ThaliTest[1471:3160319] jxcore: connect: fail: Peer unreachable
2016-01-08T07:30:52.911Z SendDataConnector.js: CLIENT connected ,to 0, error: Peer unreachable
2016-01-08T07:30:52.911Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:52.912Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:57.922Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:57.922Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:31:02.928 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:31:02.928 ThaliTest[1471:3160319] jxcore: disconnect: fail
2016-01-08T07:31:02.929Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:31:02.929Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:31:02.930Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:31:02.930Z SendDataConnector.js: do connect now
2016-01-08 08:31:02.931 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:31:02.932 ThaliTest[1471:3160319] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:31:02.933 ThaliTest[1471:3160319] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:31:02.934Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:31:02.935Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
,2016-01-08T07:31:02.937Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 08:31:02.938 ThaliTest[1471:3160319] jxcore: disconnect
,2016-01-08 08:31:02.939 ThaliTest[1471:3160319] jxcore: disconnect: fail
2016-01-08T07:31:02.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.944Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.945Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.kpUZpA==
,2016-01-08T07:31:02.945Z SendDataConnector.js: do connect now
,2016-01-08 08:31:02.947 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:02.947 ThaliTest[1471:3160319] client session: connect
2016-01-08 08:31:02.948 ThaliTest[1471:3160319] client session: stateChange:0->1 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:06.932 ThaliTest[1471:3160868] client session: connected
2016-01-08 08:31:06.932 ThaliTest[1471:3160868] client session: stateChange:1->2 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:06.957 ThaliTest[1471:3160870] client session: fireConnectCallback: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:06.958 ThaliTest[1471:3160870] jxcore: connect: success
2016-01-08T07:31:06.959Z SendDataConnector.js: CLIENT connected to 5640,7, error: null
2016-01-08T07:31:06.960Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:06.964 ThaliTest[1471:3160143] client: relay established
2016-01-08 08:31:06.964 ThaliTest[1471:3160143] client: new accepted socket: 0x192cf510
,2016-01-08T07:31:06.982Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 08:31:07.058 ThaliTest[1471:3160143] multipeer session: reset timer
2016-01-08 08:31:07.058 ThaliTest[1471:3160143] multipeer session: stop timer
2016-01-08 08:31:07.059 ThaliTest[1471:3160143] multipeer session: start timer: 0x1907ad00
2016-,01-08 08:31:07.059 ThaliTest[1471:3160143] server session: connect
2016-01-08 08:31:07.060 ThaliTest[1471:3160143] server session: stateChange:0->1 Apple-Iphone6-1
2016-01-08 08:31:07.070 ThaliTest[1471:3160143] server: accepting invitation Apple-Iphone6-1
,2016-01-08T07:31:08.246Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T07:31:08.513Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:08.513Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T07:31:08.517Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:08.518Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:08.523 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:31:08.524 ThaliTest[1471:3160319] client session: disconnectFromPeer: Apple-Iphone5-1.kpUZpA==
2016-01-08 08:31:08.525 ThaliTest[1471:3160319] client session: disconnect
20,16-01-08 08:31:08.525 ThaliTest[1471:3160319] client session: stateChange:2->0 Apple-Iphone5-1.kpUZpA==
,2016-01-08 08:31:08.544 ThaliTest[1471:3160319] jxcore: disconnect: success
2016-01-08T07:31:08.544Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.kpUZpA==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipho,ne6-1.O1yvYA==
2016-01-08T07:31:08.546Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.546Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.546Z SendDataConnector.j,s: do connect now
2016-01-08 08:31:08.547 ThaliTest[1471:3160319] jxcore: connect Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:08.549 ThaliTest[1471:3160319] client session: connect
2016-01-08 08:31:08.549 ThaliTest[1471:3160319] client session: stateChang,e:0->1 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:10.602 ThaliTest[1471:3160925] server session: connected
,2016-01-08 08:31:10.603 ThaliTest[1471:3160925] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 08:31:10.612 ThaliTest[1471:3160143] server relay: connected (to port: 56403)
,2016-01-08T07:31:10.621Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:11.082Z SendDataTCPServer.js: TCP/IP server has received 7310 bytes of data
,2016-01-08T07:31:11.096Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-08T07:31:11.166Z SendDataTCPServer.js: TCP/IP server has received 18615 bytes of data
,2016-01-08T07:31:11.183Z SendDataTCPServer.js: TCP/IP server has received 70839 bytes of data
,2016-01-08T07:31:11.201Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-08T07:31:11.304Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2016-01-08T07:31:11.330Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-08T07:31:11.385Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:11.423 ThaliTest[1471:3160882] server session: not connected Apple-Iphone6-1
,2016-01-08 08:31:11.457 ThaliTest[1471:3160868] client session: connected
2016-01-08 08:31:11.457 ThaliTest[1471:3160868] client session: stateChange:1->2 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:11.462 ThaliTest[1471:3160868] client session: fireConnectCallback: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:11.463 ThaliTest[1471:3160868] jxcore: connect: success
,2016-01-08T07:31:11.464Z SendDataConnector.js: CLIENT connected to 56411, error: null
2016-01-08T07:31:11.465Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:11.471 ThaliTest[1471:3160143] client: relay established
2016-01-08 08:31:11.471 ThaliTest[1471:3160143] client: new accepted socket: 0x192de450
,2016-01-08T07:31:11.482Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:12.031Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T07:31:12.102Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T07:31:12.128Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T07:31:12.260Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:12.261Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T07:31:12.262Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:12.262Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:12.263 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:31:12.263 ThaliTest[1471:3160319] client session: disconnectFromPeer: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:12.263 ThaliTest[1471:3160319] client session: disconnect
2016-01-08 08:31:12.263 ThaliTest[1471:3160319] client session: stateChange:2->0 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:12.271 ThaliTest[1471:3160319] jxcore: disconnect: success
,2016-01-08T07:31:12.277Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.O1yvYA==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:12.281Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:12.281Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.5QwW9A==
,2016-01-08T07:31:12.282Z SendDataConnector.js: do connect now
,2016-01-08 08:31:12.283 ThaliTest[1471:3160319] jxcore: connect Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:12.284 ThaliTest[1471:3160319] client session: connect
,2016-01-08 08:31:12.285 ThaliTest[1471:3160319] client session: stateChange:0->1 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:13.016 ThaliTest[1471:3160143] multipeer session: reset timer
2016-01-08 08:31:13.017 ThaliTest[1471:3160143] multipeer session: stop timer
2016-01-08 08:31:13.017 ThaliTest[1471:3160143] multipeer session: start timer: 0x1907ad00
2016-,01-08 08:31:13.017 ThaliTest[1471:3160143] server session: connect
2016-01-08 08:31:13.018 ThaliTest[1471:3160143] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 08:31:13.028 ThaliTest[1471:3160143] server: accepting invitation Apple-Iphone5-1
,2016-01-08 08:31:13.275 ThaliTest[1471:3160143] multipeer session: reset timer
2016-01-08 08:31:13.275 ThaliTest[1471:3160143] multipeer session: stop timer
2016-01-08 08:31:13.275 ThaliTest[1471:3160143] multipeer session: start timer: 0x1907ad00
2016-01-08 08:31:13.276 ThaliTest[1471:3160143] server session: connect
2016-01-08 08:31:13.276 ThaliTest[1471:3160143] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 08:31:13.283 ThaliTest[1471:3160143] server: accepting invitation Apple-IpadAir2-1
,2016-01-08 08:31:15.701 ThaliTest[1471:3160882] server session: connected
2016-01-08 08:31:15.701 ThaliTest[1471:3160882] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08 08:31:15.716 ThaliTest[1471:3160143] server relay: connected (to port: 56403)
,2016-01-08T07:31:15.719Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 08:31:16.035 ThaliTest[1471:3160882] client session: connected
2016-01-08 08:31:16.035 ThaliTest[1471:3160882] client session: stateChange:1->2 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:16.042 ThaliTest[1471:3160882] client session: fireConnectCallback: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:16.043 ThaliTest[1471:3160882] jxcore: connect: success
2016-01-08T07:31:16.044Z SendDataConnector.js: CLIENT connected to 56415, error: null
2016-01-08T07:31:16.045Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:16.049 ThaliTest[1471:3160143] client: relay established
2016-01-08 08:31:16.049 ThaliTest[1471:3160143] client: new accepted socket: 0x1939d4a0
,2016-01-08T07:31:16.062Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 08:31:16.441 ThaliTest[1471:3160869] server session: connected
2016-01-08 08:31:16.441 ThaliTest[1471:3160869] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 08:31:16.446 ThaliTest[1471:3160143] server relay: connected (to port: 56403)
,2016-01-08T07:31:16.590Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:16.751Z SendDataTCPServer.js: TCP/IP server has received 7594 bytes of data
,2016-01-08T07:31:16.764Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-08T07:31:16.777Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2016-01-08T07:31:16.792Z SendDataTCPServer.js: TCP/IP server has received 47085 bytes of data
,2016-01-08T07:31:16.807Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-08T07:31:16.819Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2016-01-08T07:31:16.882Z SendDataTCPServer.js: TCP/IP server has received 98965 bytes of data
,2016-01-08T07:31:16.896Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T07:31:16.920Z SendDataTCPServer.js: TCP/IP server has received 12045 bytes of data
,2016-01-08T07:31:16.934Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-08T07:31:16.936Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:16.938Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T07:31:16.941Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:16.941Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:16.942 ThaliTest[1471:3160319] jxcore: disconnect
2016-01-08 08:31:16.942 ThaliTest[1471:3160319] client session: disconnectFromPeer: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:16.942 ThaliTest[1471:3160319] client session: disconnect
2016-01-08 08:31:16.942 ThaliTest[1471:3160319] client session: stateChange:2->0 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:16.987 ThaliTest[1471:3160941] server session: not connected Apple-Iphone5-1
2016-01-08 08:31:16.987 ThaliTest[1471:3160319] jxcore: disconnect: success
,2016-01-08T07:31:16.989Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.5QwW9A==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T07:31:17.012Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:17.012Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08T07:31:17.027Z SendDataTCPServer.js: TCP/IP server has received 92911 bytes of data
,2016-01-08T07:31:17.033Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:17.060 ThaliTest[1471:3160925] server session: not connected Apple-IpadAir2-1
,teardown
,testSendData stopped
,2016-01-08 08:31:17.290 ThaliTest[1471:3160319] jxcore: stopBroadcasting
,2016-01-08 08:31:17.292 ThaliTest[1471:3160319] THEMultipeerSession stopping peer
,2016-01-08 08:31:17.294 ThaliTest[1471:3160319] multipeer session: stop timer
,2016-01-08 08:31:17.329 ThaliTest[1471:3160319] server session: disconnect
,2016-01-08 08:31:17.347 ThaliTest[1471:3160319] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 08:31:17.423 ThaliTest[1471:3160319] server session: disconnect
,2016-01-08 08:31:17.424 ThaliTest[1471:3160319] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 08:31:17.434 ThaliTest[1471:3160319] server session: disconnect
,2016-01-08 08:31:17.437 ThaliTest[1471:3160319] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 08:31:18.155 ThaliTest[1471:3160319] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
