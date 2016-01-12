#### Test 55742142a5c2fdb_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/672BC230-D7E2-48D7-BFBA-4FAAD3969BA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/672BC230-D7E2-48D7-BFBA-4FAAD3969BA7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55742142a5c2fdb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D490548F-C52A-4A96-B55C-B17729292E3B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53497"
,(lldb)     command script import "/tmp/672BC230-D7E2-48D7-BFBA-4FAAD3969BA7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-12 13:14:24.035 ThaliTest[1800:3979310] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8DFACE2E-80C1-42CF-9424-75765079B85F/Library/Cookies/Cookies.binarycookies
,2016-01-12 13:14:24.292 ThaliTest[1800:3979310] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-12 13:14:24.293 ThaliTest[1800:3979310] Multi-tasking -> Device: YES, App: YES
,2016-01-12 13:14:24.300 ThaliTest[1800:3979310] Unlimited access to network resources
,2016-01-12 13:14:24.309 ThaliTest[1800:3979310] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-12 13:14:28.303 ThaliTest[1800:3979310] Resetting plugins due to page load.
,2016-01-12 13:14:29.492 ThaliTest[1800:3979310] Finished load of: file:///var/mobile/Containers/Bundle/Application/D490548F-C52A-4A96-B55C-B17729292E3B/ThaliTest.app/www/index.html
,2016-01-12 13:14:29.715 ThaliTest[1800:3979310] JXcore Cordova plugin initializing
,2016-01-12 13:14:29.716 ThaliTest[1800:3979455] JXcore instance initializing
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
2016-01-12 13:19:30.785 ThaliTest[1800:3979455] jxcore: startBroadcasting
,2016-01-12 13:19:30.793 ThaliTest[1800:3979455] server: starting Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:19:30.794 ThaliTest[1800:3979455] multipeer session: start timer: 0x17c82470
2016-01-12 13:19:30.794 ThaliTest[1800:3979455] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-12 13:19:30.794 ThaliTest[1800:3979455] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-12 13:19:31.837 ThaliTest[1800:3979310] client: found peer: Apple-Iphone6-1.vdOTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.vdOTuw==, peerAvail,able: true
weAreDoneNow
done, now sending data to server
,2016-01-12 13:19:31.906 ThaliTest[1800:3979310] client: found peer: Apple-Iphone5-1.IBb4nw==
,2016-01-12 13:19:32.146 ThaliTest[1800:3979310] client: found peer: Apple-IpadAir2-1.hA+i5Q==
,teardown
,testFindPeers stopped
,2016-01-12 13:19:32.699 ThaliTest[1800:3979455] jxcore: stopBroadcasting
2016-01-12 13:19:32.701 ThaliTest[1800:3979455] THEMultipeerSession stopping peer
2016-01-12 13:19:32.701 ThaliTest[1800:3979455] multipeer session: stop timer
2016-01-12 13:19:32.701 ThaliTest[1800:3979455] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 58877
,2016-01-12 13:19:32.718 ThaliTest[1800:3979455] jxcore: startBroadcasting
,2016-01-12 13:19:32.721 ThaliTest[1800:3979455] server: starting Apple-Iphone5s-1.8kws4w==
2016-01-12 13:19:32.722 ThaliTest[1800:3979455] multipeer session: start timer: 0x17b382a0
2016-01-12 13:19:32.722 ThaliTest[1800:3979455] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-12 13:19:32.722 ThaliTest[1800:3979455] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-12T12:19:32.725Z SendDataTCPServer.js: TCP/IP server is bound to port: 58877
,2016-01-12 13:19:32.744 ThaliTest[1800:3979310] client: found peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:32.744 ThaliTest[1800:3979310] client: found peer: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:32.744 ThaliTest[1800:3979310] client: found peer:, Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:32.744 ThaliTest[1800:3979310] client: found peer: Apple-IpadAir2-1.hA+i5Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null),, Available: true
startWithNextDevice
,device[1]: Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:32.747Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:32.748Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:32.,748Z SendDataConnector.js: do connect now
2016-01-12 13:19:32.748 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:32.748 ThaliTest[1800:3979455] client session: connect
2016-01-12 13:19:32.749 ThaliTest[1800:3979455] client session: stateChange:0->1 Apple-Iphone5s-1.+FhoNw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.vdOTuw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:33.962 ThaliTest[1800:3979310] client: lost peer: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] client session: onPeerLost: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] client sess,ion: onLinkFailure: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] client session: disconnect
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] client session: stateChange:1->0 Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] client session: fireConnectCallback: Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:33.963 ThaliTest[1800:3979310] jxcore: connect: fail: Peer disconnected
2016-01-12T12:19:33.964Z SendDataConnector.js: CLIENT connected to 0, error: Pe,er disconnected
2016-01-12T12:19:33.964Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-12T12:19:33.964Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.+FhoNw==","peerName":"(null)","peerAvailable":false}]
,2016-01-12 13:19:34.472 ThaliTest[1800:3979310] client: lost peer: Apple-Iphone6-1.vdOTuw==
2016-01-12 13:19:34.472 ThaliTest[1800:3979310] client session: onPeerLost: Apple-Iphone6-1.vdOTuw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.v,dOTuw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-12 13:19:34.490 ThaliTest[1800:3979310] client: lost peer: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.491 ThaliTest[1800:3979310] client session: onPeerLost: Apple-Iphone5-1.IBb4nw==
2016-01-12 13:19:34.491 ThaliTest[1800:3979310] client: lost ,peer: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.492 ThaliTest[1800:3979310] client session: onPeerLost: Apple-IpadAir2-1.hA+i5Q==
2016-01-12 13:19:34.492 ThaliTest[1800:3979310] client: found peer: Apple-Iphone5-1.mOZnMg==
peerAvailabilityChanged [{,"peerIdentifier":"Apple-Iphone5-1.IBb4nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.hA+i5Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.mOZnMg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12 13:19:34.573 ThaliTest[1800:3979310] client: found peer: Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:19:34.573 ThaliTest[1800:3979310] client: found peer: Apple-Iphone6-1.56+AEA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.WKZK+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.56+AEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-12T12:19:38.972Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:38.972Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:19:43.980 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:19:43.980 ThaliTest[1800:3979455] jxcore: disconnect: fail
2016-01-12T12:19:43.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.+FhoNw==
2,016-01-12T12:19:43.980Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5s-1.+FhoNw== with availability status: true
2016-01-12T12:19:43.980Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:43.981Z SendDataConnector.js: do connect now
2016-01-12 13:19:43.981 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:43.981 ThaliTest[1800:3979455] client: connect: unreachable Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:,43.981 ThaliTest[1800:3979455] jxcore: connect: fail: Peer unreachable
2016-01-12T12:19:43.981Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:43.981Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-12T12:19:43.981Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:19:48.985Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:48.985Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:19:53.995 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:19:53.995 ThaliTest[1800:3979455] jxcore: disconnect: fail
2016-01-12T12:19:53.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:53.996Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5s-1.+FhoNw== with availability status: true
2016-01-12T12:19:53.996Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:53.996Z SendDataConnector.js: do connect now
,2016-01-12 13:19:53.996 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:53.997 ThaliTest[1800:3979455] client: connect: unreachable Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:19:53.997 ThaliTest[1800:3979455] jxcore: conne,ct: fail: Peer unreachable
2016-01-12T12:19:53.997Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:19:53.997Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-12T12:19:53.997Z SendDataConnector.j,s: tryAgain afer: 5000 ms.
,2016-01-12T12:19:59.008Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:19:59.008Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:20:02.735 ThaliTest[1800:3979310] multipeer session: restart
,2016-01-12 13:20:02.757 ThaliTest[1800:3979310] client: found peer: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:02.758 ThaliTest[1800:3979310] client: found peer: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:02.759 ThaliTest[1800:3979310] client: found peer: Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:04.016 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:20:04.016 ThaliTest[1800:3979455] jxcore: disconnect: fail
2016-01-12T12:20:04.016Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.+FhoNw==
2,016-01-12T12:20:04.016Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5s-1.+FhoNw== with availability status: true
2016-01-12T12:20:04.016Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:20:04.017Z SendDataConnector.js: do connect now
2016-01-12 13:20:04.017 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:20:04.017 ThaliTest[1800:3979455] client: connect: unreachable Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:20:,04.017 ThaliTest[1800:3979455] jxcore: connect: fail: Peer unreachable
2016-01-12T12:20:04.017Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:04.017Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-12T12:20:04.017Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-12T12:20:09.034Z SendDataConnector.js: re-try now : Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:20:09.034Z SendDataConnector.js: ReStart called with peer Apple-Iphone5s-1.+FhoNw==
,2016-01-12 13:20:14.042 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:20:14.042 ThaliTest[1800:3979455] jxcore: disconnect: fail
2016-01-12T12:20:14.042Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.+FhoNw==
2,016-01-12T12:20:14.042Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5s-1.+FhoNw== with availability status: true
2016-01-12T12:20:14.043Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.+FhoNw==
2016-01-12T12:20:14,.043Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.043 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:20:14.043 ThaliTest[1800:3979455] client: connect: unreachable Apple-Iphone5s-1.+FhoNw==
2016-01-12 13:20:,14.043 ThaliTest[1800:3979455] jxcore: connect: fail: Peer unreachable
2016-01-12T12:20:14.043Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-12T12:20:14.043Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-12T12:20:14.046Z SendDataConnector.js: CLIENT Stop now
2016-01-12 13:20:14.046 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:20:14.046 ThaliTest[1800:3979455] jxcore: disconnect: fail
2016-01-12T12:20:14.046Z SendData,Connector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.+FhoNw==
---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:14.047Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.mOZnMg=,=
2016-01-12T12:20:14.047Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.mOZnMg==
2016-01-12T12:20:14.047Z SendDataConnector.js: do connect now
2016-01-12 13:20:14.048 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:14.048 ThaliTest[1800:3979455] client session: connect
2016-01-12 13:20:14.048 ThaliTest[1800:3979455] client session: stateChange:0->1 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:14.439 ThaliTest[1800:3979310] multipeer session: reset timer
2016-01-12 13:20:14.439 ThaliTest[1800:3979310] multipeer session: stop timer
2016-01-12 13:20:14.439 ThaliTest[1800:3979310] multipeer session: start timer: 0x17b382a0
2016-,01-12 13:20:14.439 ThaliTest[1800:3979310] server session: connect
2016-01-12 13:20:14.439 ThaliTest[1800:3979310] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-12 13:20:14.445 ThaliTest[1800:3979310] server: accepting invitation Apple-IpadAir2-1
,2016-01-12 13:20:17.033 ThaliTest[1800:3980349] client session: connected
2016-01-12 13:20:17.034 ThaliTest[1800:3980349] client session: stateChange:1->2 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:17.072 ThaliTest[1800:3980347] client session: fireConnectCallback: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:17.072 ThaliTest[1800:3980347] jxcore: connect: success
2016-01-12T12:20:17.072Z SendDataConnector.js: CLIENT connected to 58884, error: null
2016-01-12T12:20:17.073Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:17.075 ThaliTest[1800:3979310] client: relay established
2016-01-12 13:20:17.076 ThaliTest[1800:3979310] client: new accepted socket: 0x17c9edd0
,2016-01-12T12:20:17.088Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:17.728Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-12T12:20:17.739Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-12T12:20:17.750Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-12T12:20:18.000Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-12T12:20:18.038Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-12T12:20:18.039Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2016-01-12T12:20:18.039Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:18.039Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:18.040 ThaliTest[1800:3979455] jxcore: disconnect
2016-01-12 13:20:18.041 ThaliTest[1800:3979455] client session: disconnectFromPeer: Apple-Iphone5-1.mOZnMg==
2016-01-12 13:20:18.041 ThaliTest[1800:3979455] client session: disconnect
2016-01-12 13:20:18.041 ThaliTest[1800:3979455] client session: stateChange:2->0 Apple-Iphone5-1.mOZnMg==
,2016-01-12 13:20:18.046 ThaliTest[1800:3979455] jxcore: disconnect: success
2016-01-12T12:20:18.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.mOZnMg==
---- round done--------
startWithNextDevice
device[3]: Apple-Ipad,Air2-1.WKZK+A==
2016-01-12T12:20:18.047Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:18.047Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.WKZK+A==
2016-01-12T12:20:18.047Z SendDataConnector.js: do connect now
2016-01-12 13:20:18.047 ThaliTest[1800:3979455] jxcore: connect Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:20:18.048 ThaliTest[1800:3979455] client session: connect
2016-01-12 13:20:18.048 ThaliTest[1800:3979455] client session: stateC,hange:0->1 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:18.239 ThaliTest[1800:3980347] server session: connected
2016-01-12 13:20:18.239 ThaliTest[1800:3980347] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-12T12:20:18.684Z SendDataTCPServer.js: TCP/IP server connected
2016-01-12 13:20:18.685 ThaliTest[1800:3979310] server relay: connected (to port: 58877)
,2016-01-12T12:20:18.769Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-12T12:20:18.782Z SendDataTCPServer.js: TCP/IP server has received 12572 bytes of data
,2016-01-12T12:20:18.795Z SendDataTCPServer.js: TCP/IP server has received 16425 bytes of data
,2016-01-12T12:20:18.832Z SendDataTCPServer.js: TCP/IP server has received 31755 bytes of data
,2016-01-12T12:20:18.882Z SendDataTCPServer.js: TCP/IP server has received 36135 bytes of data
,2016-01-12T12:20:18.897Z SendDataTCPServer.js: TCP/IP server has received 62415 bytes of data
,2016-01-12T12:20:18.912Z SendDataTCPServer.js: TCP/IP server has received 76437 bytes of data
,2016-01-12T12:20:18.926Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-12T12:20:18.971Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:19.081 ThaliTest[1800:3980412] server session: not connected Apple-IpadAir2-1
,2016-01-12 13:20:21.185 ThaliTest[1800:3980412] client session: connected
2016-01-12 13:20:21.185 ThaliTest[1800:3980412] client session: stateChange:1->2 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:21.187 ThaliTest[1800:3980412] client session: fireConnectCallback: Apple-IpadAir2-1.WKZK+A==
2016-01-12 13:20:21.187 ThaliTest[1800:3980412] jxcore: connect: success
2016-01-12T12:20:21.188Z SendDataConnector.js: CLIENT connected to 588,88, error: null
2016-01-12T12:20:21.188Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:21.189 ThaliTest[1800:3979310] client: relay established
2016-01-12 13:20:21.190 ThaliTest[1800:3979310] client: new accepted socket: 0x17caa400
,2016-01-12T12:20:21.202Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12T12:20:21.740Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-12T12:20:21.782Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-12T12:20:21.796Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:21.797Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-12T12:20:21.797Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:21.798Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:21.798 ThaliTest[1800:3979455] jxcore: disconnect
,2016-01-12 13:20:21.799 ThaliTest[1800:3979455] client session: disconnectFromPeer: Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:21.799 ThaliTest[1800:3979455] client session: disconnect
,2016-01-12 13:20:21.800 ThaliTest[1800:3979455] client session: stateChange:2->0 Apple-IpadAir2-1.WKZK+A==
,2016-01-12 13:20:21.869 ThaliTest[1800:3979455] jxcore: disconnect: success
,2016-01-12T12:20:21.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.WKZK+A==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:21.871Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:21.872Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.56+AEA==
,2016-01-12T12:20:21.872Z SendDataConnector.js: do connect now
,2016-01-12 13:20:21.872 ThaliTest[1800:3979455] jxcore: connect Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:21.873 ThaliTest[1800:3979455] client session: connect
,2016-01-12 13:20:21.874 ThaliTest[1800:3979455] client session: stateChange:0->1 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:24.003 ThaliTest[1800:3979310] multipeer session: reset timer
2016-01-12 13:20:24.003 ThaliTest[1800:3979310] multipeer session: stop timer
2016-01-12 13:20:24.003 ThaliTest[1800:3979310] multipeer session: start timer: 0x17b382a0
2016-01-12 13:20:24.003 ThaliTest[1800:3979310] server session: connect
2016-01-12 13:20:24.003 ThaliTest[1800:3979310] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-12 13:20:24.008 ThaliTest[1800:3979310] server: accepting invitation Apple-Iphone6-1
,2016-01-12 13:20:24.781 ThaliTest[1800:3980347] client session: connected
2016-01-12 13:20:24.782 ThaliTest[1800:3980347] client session: stateChange:1->2 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:24.843 ThaliTest[1800:3980412] client session: fireConnectCallback: Apple-Iphone6-1.56+AEA==
2016-01-12 13:20:24.843 ThaliTest[1800:3980412] jxcore: connect: success
2016-01-12T12:20:24.843Z SendDataConnector.js: CLIENT connected to 5889,1, error: null
2016-01-12T12:20:24.844Z SendDataConnector.js: CLIENT starting client 
,2016-01-12 13:20:24.845 ThaliTest[1800:3979310] client: relay established
2016-01-12 13:20:24.846 ThaliTest[1800:3979310] client: new accepted socket: 0x17cab630
,2016-01-12T12:20:24.858Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-12 13:20:25.118 ThaliTest[1800:3979310] multipeer session: reset timer
2016-01-12 13:20:25.118 ThaliTest[1800:3979310] multipeer session: stop timer
2016-01-12 13:20:25.118 ThaliTest[1800:3979310] multipeer session: start timer: 0x17b382a0
2016-01-12 13:20:25.118 ThaliTest[1800:3979310] server session: connect
2016-01-12 13:20:25.119 ThaliTest[1800:3979310] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-12 13:20:25.123 ThaliTest[1800:3979310] server: accepting invitation Apple-Iphone5-1
,2016-01-12T12:20:25.499Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-12T12:20:25.523Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-12T12:20:25.536Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-12T12:20:25.573Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-12T12:20:25.574Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-12T12:20:25.574Z SendDataConnector.js: CLIENT Stop now
,2016-01-12T12:20:25.575Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:25.575 ThaliTest[1800:3979455] jxcore: disconnect
,2016-01-12 13:20:25.576 ThaliTest[1800:3979455] client session: disconnectFromPeer: Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:25.576 ThaliTest[1800:3979455] client session: disconnect
,2016-01-12 13:20:25.577 ThaliTest[1800:3979455] client session: stateChange:2->0 Apple-Iphone6-1.56+AEA==
,2016-01-12 13:20:25.646 ThaliTest[1800:3979455] jxcore: disconnect: success
,2016-01-12T12:20:25.647Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.56+AEA==
,---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-12T12:20:25.660Z SendDataConnector.js: CLIENT Stop now
2016-01-12T12:20:25.660Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-12 13:20:26.548 ThaliTest[1800:3980349] server session: connected
2016-01-12 13:20:26.548 ThaliTest[1800:3980349] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-12 13:20:26.556 ThaliTest[1800:3979310] server relay: connected (to port: 58877)
,2016-01-12T12:20:26.560Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:26.995Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-12T12:20:27.007Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-12T12:20:27.021Z SendDataTCPServer.js: TCP/IP server has received 35922 bytes of data
,2016-01-12T12:20:27.033Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-12T12:20:27.085Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2016-01-12T12:20:27.108Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-12T12:20:27.120Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2016-01-12T12:20:27.145Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:27.298 ThaliTest[1800:3980412] server session: not connected Apple-Iphone6-1
,2016-01-12 13:20:27.792 ThaliTest[1800:3980412] server session: connected
2016-01-12 13:20:27.792 ThaliTest[1800:3980412] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-12 13:20:27.819 ThaliTest[1800:3979310] server relay: connected (to port: 58877)
,2016-01-12T12:20:27.828Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-12T12:20:28.856Z SendDataTCPServer.js: TCP/IP server has received 7665 bytes of data
,2016-01-12T12:20:28.870Z SendDataTCPServer.js: TCP/IP server has received 9855 bytes of data
,2016-01-12T12:20:28.882Z SendDataTCPServer.js: TCP/IP server has received 16425 bytes of data
,2016-01-12T12:20:28.906Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2016-01-12T12:20:28.921Z SendDataTCPServer.js: TCP/IP server has received 60154 bytes of data
,2016-01-12T12:20:28.934Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-12T12:20:29.041Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2016-01-12T12:20:29.055Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-12 13:20:29.134 ThaliTest[1800:3980412] server session: not connected Apple-Iphone5-1
,teardown
,testSendData stopped
,2016-01-12 13:20:29.404 ThaliTest[1800:3979455] jxcore: stopBroadcasting
2016-01-12 13:20:29.405 ThaliTest[1800:3979455] THEMultipeerSession stopping peer
2016-01-12 13:20:29.405 ThaliTest[1800:3979455] multipeer session: stop timer
2016-01-12 13:20:29.,406 ThaliTest[1800:3979455] server session: disconnect
2016-01-12 13:20:29.406 ThaliTest[1800:3979455] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-12 13:20:29.409 ThaliTest[1800:3979455] server session: disconnect
,2016-01-12 13:20:29.409 ThaliTest[1800:3979455] server session: stateChange:2->0 Apple-IpadAir2-1
2016-01-12 13:20:29.411 ThaliTest[1800:3979455] server session: disconnect
2016-01-12 13:20:29.411 ThaliTest[1800:3979455] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-12 13:20:29.414 ThaliTest[1800:3979455] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-12T12:20:29.431Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-12T12:20:29.432Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.433Z SendDataTCPServer.js: TCP/IP server is ended
2016-01-12T12:20:29.433Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
