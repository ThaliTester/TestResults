#### Test 54312298af2c956_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/11A01E21-3A80-4503-8CF8-BE28190E280D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/11A01E21-3A80-4503-8CF8-BE28190E280D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298af2c956/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4A84EE4B-8E97-4589-8DC3-5A75439DB779/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62397"
,(lldb)     command script import "/tmp/11A01E21-3A80-4503-8CF8-BE28190E280D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 03:06:36.964 ThaliTest[787:954577] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB0A86E9-106F-4CF6-AF1C-75D20D121FEA/Library/Cookies/Cookies.binarycookies
,2015-12-23 03:06:37.319 ThaliTest[787:954577] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 03:06:37.321 ThaliTest[787:954577] Multi-tasking -> Device: YES, App: YES
,2015-12-23 03:06:37.330 ThaliTest[787:954577] Unlimited access to network resources
,2015-12-23 03:06:37.339 ThaliTest[787:954577] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 03:06:46.021 ThaliTest[787:954577] Resetting plugins due to page load.
,2015-12-23 03:06:49.505 ThaliTest[787:954577] Finished load of: file:///var/mobile/Containers/Bundle/Application/4A84EE4B-8E97-4589-8DC3-5A75439DB779/ThaliTest.app/www/index.html
,2015-12-23 03:06:49.716 ThaliTest[787:954577] JXcore Cordova plugin initializing
2015-12-23 03:06:49.718 ThaliTest[787:954796] JXcore instance initializing
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
,2015-12-23 03:06:51.056 ThaliTest[787:954577] THREAD WARNING: ['JXcore'] took '99.887207' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-23 03:11:59.943 ThaliTest[787:954796] jxcore: startBroadcasting
,2015-12-23 03:11:59.965 ThaliTest[787:954796] server: starting Apple-Iphone5s-1_PT4021.JWtqWw==
2015-12-23 03:11:59.966 ThaliTest[787:954796] multipeer session: start timer: 0x18b907c0
2015-12-23 03:11:59.967 ThaliTest[787:954796] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT4021
2015-12-23 03:11:59.967 ThaliTest[787:954796] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-23 03:12:01.004 ThaliTest[787:954577] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT6053.,eofveg==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2015-12-23 03:12:01.074 ThaliTest[787:954577] client: found peer: Apple-Iphone5-1_PT4216.O2WEzg==
,2015-12-23 03:12:01.097 ThaliTest[787:954577] client: found peer: Apple-IpadAir2-1_PT8230.LvlR6w==
,teardown
,testFindPeers stopped
,2015-12-23 03:12:02.391 ThaliTest[787:954796] jxcore: stopBroadcasting
2015-12-23 03:12:02.392 ThaliTest[787:954796] THEMultipeerSession stopping peer
2015-12-23 03:12:02.392 ThaliTest[787:954796] multipeer session: stop timer
2015-12-23 03:12:02.393 ThaliTest[787:954796] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,check server
,serverPort is 53922
,2015-12-23 03:12:02.477 ThaliTest[787:954796] jxcore: startBroadcasting
,2015-12-23 03:12:02.479 ThaliTest[787:954796] server: starting Apple-Iphone5s-1_PT4021.SE3R7g==
2015-12-23 03:12:02.480 ThaliTest[787:954796] multipeer session: start timer: 0x18c5c320
2015-12-23 03:12:02.480 ThaliTest[787:954796] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT4021
2015-12-23 03:12:02.481 ThaliTest[787:954796] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2015-12-23T02:12:02.486Z SendDataTCPServer.js: TCP/IP server is bound to port: 53922
,2015-12-23 03:12:02.974 ThaliTest[787:954577] client: found peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:02.975 ThaliTest[787:954577] client: found peer: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:02.975 ThaliTest[787:954577] client: foun,d peer: Apple-IpadAir2-1_PT8230.LvlR6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.eofveg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1_PT6053.,eofveg==
2015-12-23T02:12:02.980Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:02.981Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
2015-12-23T02:12:02.982Z SendDataConnector.js: do connect now
,2015-12-23 03:12:02.984 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:02.985 ThaliTest[787:954796] client session: connect
2015-12-23 03:12:02.985 ThaliTest[787:954796] client session: stateChange:0->1 Apple-Iphon,e6-1_PT6053.eofveg==
,2015-12-23 03:12:03.005 ThaliTest[787:954577] client: found peer: Apple-Iphone5s-1_PT4021.JWtqWw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-23 03:12:03.529 ThaliTest[787:954577] client: lost peer: Apple-Iphone5s-1_PT4021.JWtqWw==
2015-12-23 03:12:03.530 ThaliTest[787:954577] client session: onPeerLost: Apple-Iphone5s-1_PT4021.JWtqWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT4021.JWtqWw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-23 03:12:03.663 ThaliTest[787:954577] client: lost peer: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.663 ThaliTest[787:954577] client session: onPeerLost: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.663 ThaliTest[787:954577] clien,t session: onLinkFailure: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.664 ThaliTest[787:954577] client session: disconnect
2015-12-23 03:12:03.665 ThaliTest[787:954577] client session: stateChange:1->0 Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 ,03:12:03.666 ThaliTest[787:954577] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:03.667 ThaliTest[787:954577] jxcore: connect: fail: Peer disconnected
2015-12-23T02:12:03.669Z SendDataConnector.js: CLIENT connected, to 0, error: Peer disconnected
2015-12-23T02:12:03.670Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-23T02:12:03.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_P,T6053.eofveg==","peerName":"(null)","peerAvailable":false}]
,2015-12-23 03:12:03.738 ThaliTest[787:954577] client: lost peer: Apple-IpadAir2-1_PT8230.LvlR6w==
2015-12-23 03:12:03.738 ThaliTest[787:954577] client session: onPeerLost: Apple-IpadAir2-1_PT8230.LvlR6w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT8230.LvlR6w==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-23 03:12:04.195 ThaliTest[787:954577] client: lost peer: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:04.195 ThaliTest[787:954577] client session: onPeerLost: Apple-Iphone5-1_PT4216.O2WEzg==
2015-12-23 03:12:04.196 ThaliTest[787:954577] clien,t: found peer: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:04.196 ThaliTest[787:954577] client: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:04.198 ThaliTest[787:954577] client: found peer: Apple-Iphone5-1_PT4216.OABFDg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.O2WEzg==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6053.vUErSg==","peerName":"(null),","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8230.FlW6Iw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4216.OABFDg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-23T02:12:08.682Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:08.684Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.692 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:13.693 ThaliTest[787:954796] jxcore: disconnect: fail
2015-12-23T02:12:13.693Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:13.694Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:13.694Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:13.694Z SendDataConnector.js: do connect now
2015-12-23 03:12:13.695 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:13.696 ThaliTest[787:954796] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
2015-12-23 03:12:13.697 ThaliTest[787:954796] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:13.698Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:13.699Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:13.699Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:18.708Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:18.709Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.720 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:23.720 ThaliTest[787:954796] jxcore: disconnect: fail
2015-12-23T02:12:23.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:23.721Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:23.722Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:23.722Z SendDataConnector.js: do connect now
2015-12-23 03:12:23.723 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.723 ThaliTest[787:954796] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:23.724 ThaliTest[787:954796] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:23.726Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:23.726Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:23.727Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:28.733Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:28.734Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:32.482 ThaliTest[787:954577] multipeer session: restart
,2015-12-23 03:12:32.540 ThaliTest[787:954577] client: found peer: Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:32.541 ThaliTest[787:954577] client: found peer: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:32.541 ThaliTest[787:954577] client: found peer: Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:33.746 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:33.747 ThaliTest[787:954796] jxcore: disconnect: fail
2015-12-23T02:12:33.747Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:33.748Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:33.748Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:33.748Z SendDataConnector.js: do connect now
2015-12-23 03:12:33.749 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.750 ThaliTest[787:954796] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:33.751 ThaliTest[787:954796] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:33.752Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2015-12-23T02:12:33.753Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2015-12-23T02:12:33.753Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-23T02:12:38.759Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:38.759Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.764 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:43.765 ThaliTest[787:954796] jxcore: disconnect: fail
2015-12-23T02:12:43.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==,
2015-12-23T02:12:43.766Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT6053.eofveg== with availability status: true
2015-12-23T02:12:43.766Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23T02:12:43.766Z SendDataConnector.js: do connect now
2015-12-23 03:12:43.767 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.768 ThaliTest[787:954796] client: connect: unreachable Apple-Iphone6-1_PT6053.eofveg==
,2015-12-23 03:12:43.769 ThaliTest[787:954796] jxcore: connect: fail: Peer unreachable
,2015-12-23T02:12:43.770Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-23T02:12:43.771Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2015-12-23T02:12:43.773Z SendDataConnector.js: CLIENT Stop now
,2015-12-23 03:12:43.774 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:43.775 ThaliTest[787:954796] jxcore: disconnect: fail
,2015-12-23T02:12:43.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.eofveg==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:43.780Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:43.780Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23T02:12:43.781Z SendDataConnector.js: do connect now
,2015-12-23 03:12:43.783 ThaliTest[787:954796] jxcore: connect Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:43.784 ThaliTest[787:954796] client session: connect
2015-12-23 03:12:43.784 ThaliTest[787:954796] client session: stateChange:0->1 Apple-Iphon,e6-1_PT6053.vUErSg==
,2015-12-23 03:12:44.125 ThaliTest[787:954577] multipeer session: reset timer
2015-12-23 03:12:44.125 ThaliTest[787:954577] multipeer session: stop timer
2015-12-23 03:12:44.125 ThaliTest[787:954577] multipeer session: start timer: 0x18c5c320
2015-12-23 ,03:12:44.126 ThaliTest[787:954577] server session: connect
2015-12-23 03:12:44.126 ThaliTest[787:954577] server session: stateChange:0->1 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:44.136 ThaliTest[787:954577] server: accepting invitation Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:46.943 ThaliTest[787:955402] server session: connected
2015-12-23 03:12:46.944 ThaliTest[787:955402] server session: stateChange:1->2 Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:47.735 ThaliTest[787:954577] server relay: connected (to port: 53922)
,2015-12-23T02:12:47.742Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:47.760Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-23T02:12:47.776Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-12-23T02:12:47.858Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-23T02:12:47.878Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-23T02:12:47.900Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:47.924 ThaliTest[787:954577] multipeer session: reset timer
,2015-12-23 03:12:47.924 ThaliTest[787:954577] multipeer session: stop timer
,2015-12-23 03:12:47.924 ThaliTest[787:954577] multipeer session: start timer: 0x18c5c320
,2015-12-23 03:12:47.926 ThaliTest[787:954577] server session: connect
2015-12-23 03:12:47.926 ThaliTest[787:954577] server session: stateChange:0->1 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:47.937 ThaliTest[787:954577] server: accepting invitation Apple-Iphone6-1_PT6053
,2015-12-23 03:12:47.999 ThaliTest[787:955416] server session: not connected Apple-IpadAir2-1_PT8230
,2015-12-23 03:12:48.966 ThaliTest[787:955403] client session: connected
2015-12-23 03:12:48.966 ThaliTest[787:955403] client session: stateChange:1->2 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:49.227 ThaliTest[787:955416] client session: fireConnectCallback: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:49.228 ThaliTest[787:955416] jxcore: connect: success
2015-12-23T02:12:49.229Z SendDataConnector.js: CLIENT connected to 5,3928, error: null
2015-12-23T02:12:49.230Z SendDataConnector.js: CLIENT starting client 
2015-12-23 03:12:49.233 ThaliTest[787:954577] client: relay established
2015-12-23 03:12:49.234 ThaliTest[787:954577] client: new accepted socket: 0x18bb3810
,2015-12-23T02:12:49.249Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:49.881Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-23T02:12:49.954Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-23T02:12:49.954Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-23T02:12:49.955Z SendDataConnector.js: CLIENT Stop now
,2015-12-23T02:12:49.955Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:49.957 ThaliTest[787:954796] jxcore: disconnect
2015-12-23 03:12:49.957 ThaliTest[787:954796] client session: disconnectFromPeer: Apple-Iphone6-1_PT6053.vUErSg==
2015-12-23 03:12:49.957 ThaliTest[787:954796] client session: disconnect
2015-12-23 03:12:49.958 ThaliTest[787:954796] client session: stateChange:2->0 Apple-Iphone6-1_PT6053.vUErSg==
,2015-12-23 03:12:50.022 ThaliTest[787:954796] jxcore: disconnect: success
2015-12-23T02:12:50.023Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6053.vUErSg==
---- round done--------
startWithNextDevice
,device[3]: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23T02:12:50.024Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23T02:12:50.024Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23T02:12:50.025Z SendDataConnector.js: do connect now
,2015-12-23 03:12:50.026 ThaliTest[787:954796] jxcore: connect Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:50.026 ThaliTest[787:954796] client session: connect
2015-12-23 03:12:50.026 ThaliTest[787:954796] client session: stateChange:0->1 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:50.875 ThaliTest[787:955403] server session: connected
,2015-12-23 03:12:50.875 ThaliTest[787:955403] server session: stateChange:1->2 Apple-Iphone6-1_PT6053
,2015-12-23 03:12:50.941 ThaliTest[787:954577] server relay: connected (to port: 53922)
,2015-12-23T02:12:50.949Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23T02:12:51.344Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-23T02:12:51.361Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-23T02:12:51.378Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-23T02:12:51.395Z SendDataTCPServer.js: TCP/IP server has received 64990 bytes of data
,2015-12-23T02:12:51.412Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-23T02:12:51.429Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23 03:12:51.497 ThaliTest[787:955417] server session: not connected Apple-Iphone6-1_PT6053
,2015-12-23 03:12:52.975 ThaliTest[787:954577] multipeer session: reset timer
,2015-12-23 03:12:52.976 ThaliTest[787:954577] multipeer session: stop timer
2015-12-23 03:12:52.976 ThaliTest[787:954577] multipeer session: start timer: 0x18c5c320
2015-12-23 03:12:52.977 ThaliTest[787:954577] server session: connect
,2015-12-23 03:12:52.977 ThaliTest[787:954577] server session: stateChange:0->1 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:52.998 ThaliTest[787:954577] server: accepting invitation Apple-Iphone5-1_PT4216
,2015-12-23 03:12:53.042 ThaliTest[787:955416] client session: connected
,2015-12-23 03:12:53.043 ThaliTest[787:955416] client session: stateChange:1->2 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:53.062 ThaliTest[787:955416] client session: fireConnectCallback: Apple-IpadAir2-1_PT8230.FlW6Iw==
2015-12-23 03:12:53.062 ThaliTest[787:955416] jxcore: connect: success
2015-12-23T02:12:53.063Z SendDataConnector.js: CLIENT connected to 53932, error: null
2015-12-23T02:12:53.064Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:53.070 ThaliTest[787:954577] client: relay established
,2015-12-23 03:12:53.078 ThaliTest[787:954577] client: new accepted socket: 0x18c690e0
,2015-12-23T02:12:53.081Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:53.372Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-23T02:12:53.422Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-23T02:12:53.435Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:53.436Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-23T02:12:53.436Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:53.436Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:53.437 ThaliTest[787:954796] jxcore: disconnect
,2015-12-23 03:12:53.437 ThaliTest[787:954796] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:53.438 ThaliTest[787:954796] client session: disconnect
,2015-12-23 03:12:53.439 ThaliTest[787:954796] client session: stateChange:2->0 Apple-IpadAir2-1_PT8230.FlW6Iw==
,2015-12-23 03:12:53.445 ThaliTest[787:954796] jxcore: disconnect: success
,2015-12-23T02:12:53.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8230.FlW6Iw==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23T02:12:53.450Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23T02:12:53.450Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23T02:12:53.451Z SendDataConnector.js: do connect now
,2015-12-23 03:12:53.451 ThaliTest[787:954796] jxcore: connect Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:53.452 ThaliTest[787:954796] client session: connect
,2015-12-23 03:12:53.453 ThaliTest[787:954796] client session: stateChange:0->1 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:55.666 ThaliTest[787:955401] server session: connected
,2015-12-23 03:12:55.668 ThaliTest[787:955401] server session: stateChange:1->2 Apple-Iphone5-1_PT4216
,2015-12-23T02:12:55.898Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-23 03:12:55.900 ThaliTest[787:954577] server relay: connected (to port: 53922)
,2015-12-23 03:12:56.182 ThaliTest[787:955416] client session: connected
,2015-12-23 03:12:56.182 ThaliTest[787:955416] client session: stateChange:1->2 Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:56.200 ThaliTest[787:955403] client session: fireConnectCallback: Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:56.201 ThaliTest[787:955403] jxcore: connect: success
,2015-12-23T02:12:56.202Z SendDataConnector.js: CLIENT connected to 53936, error: null
,2015-12-23T02:12:56.203Z SendDataConnector.js: CLIENT starting client 
,2015-12-23 03:12:56.206 ThaliTest[787:954577] client: relay established
,2015-12-23 03:12:56.206 ThaliTest[787:954577] client: new accepted socket: 0x18bc0650
,2015-12-23T02:12:56.221Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-23T02:12:56.498Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-23T02:12:56.705Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-23T02:12:56.718Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-23T02:12:56.783Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-23T02:12:56.833Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-23T02:12:56.847Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-23T02:12:56.911Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-23T02:12:56.911Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-23T02:12:56.912Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:56.912Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-23 03:12:56.913 ThaliTest[787:954796] jxcore: disconnect
,2015-12-23 03:12:56.914 ThaliTest[787:954796] client session: disconnectFromPeer: Apple-Iphone5-1_PT4216.OABFDg==
,2015-12-23 03:12:56.916 ThaliTest[787:954796] client session: disconnect
2015-12-23 03:12:56.917 ThaliTest[787:954796] client session: stateChange:2->0 Apple-Iphone5-1_PT4216.OABFDg==
2015-12-23 03:12:56.918 ThaliTest[787:955416] server session: not connected Apple-Iphone5-1_PT4216
,2015-12-23 03:12:57.000 ThaliTest[787:954796] jxcore: disconnect: success
,2015-12-23T02:12:57.001Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4216.OABFDg==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2015-12-23T02:12:57.008Z SendDataConnector.js: CLIENT Stop now
2015-12-23T02:12:57.009Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2015-12-23 03:12:58.628 ThaliTest[787:954796] jxcore: stopBroadcasting
,2015-12-23 03:12:58.628 ThaliTest[787:954796] THEMultipeerSession stopping peer
,2015-12-23 03:12:58.629 ThaliTest[787:954796] multipeer session: stop timer
,2015-12-23 03:12:58.630 ThaliTest[787:954796] server session: disconnect
2015-12-23 03:12:58.631 ThaliTest[787:954796] server session: stateChange:2->0 Apple-IpadAir2-1_PT8230
2015-12-23 03:12:58.638 ThaliTest[787:954796] server session: disconnect
2015,-12-23 03:12:58.638 ThaliTest[787:954796] server session: stateChange:2->0 Apple-Iphone6-1_PT6053
2015-12-23 03:12:58.646 ThaliTest[787:954796] server session: disconnect
2015-12-23 03:12:58.646 ThaliTest[787:954796] server session: stateChange:2->0 Apple-Iphone5-1_PT4216
,2015-12-23 03:12:58.660 ThaliTest[787:954796] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-23T02:12:58.686Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:58.688Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:58.690Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-23T02:12:58.692Z SendDataTCPServer.,js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
