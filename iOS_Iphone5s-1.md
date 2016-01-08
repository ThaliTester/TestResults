#### Test 5546736337bcedb_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/71A4117B-A577-45DD-8B30-2B3F7B56C0A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/71A4117B-A577-45DD-8B30-2B3F7B56C0A5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5546736337bcedb/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5ED91634-F230-4331-8148-02ECC9635EA0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50282"
,(lldb)     command script import "/tmp/71A4117B-A577-45DD-8B30-2B3F7B56C0A5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 15:48:25.268 ThaliTest[1507:3206726] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8F6BA2AF-7243-4153-B39F-3D55C4AEE053/Library/Cookies/Cookies.binarycookies
,2016-01-08 15:48:25.648 ThaliTest[1507:3206726] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 15:48:25.649 ThaliTest[1507:3206726] Multi-tasking -> Device: YES, App: YES
,2016-01-08 15:48:25.658 ThaliTest[1507:3206726] Unlimited access to network resources
,2016-01-08 15:48:25.671 ThaliTest[1507:3206726] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 15:48:34.639 ThaliTest[1507:3206726] Resetting plugins due to page load.
,2016-01-08 15:48:38.559 ThaliTest[1507:3206726] Finished load of: file:///var/mobile/Containers/Bundle/Application/5ED91634-F230-4331-8148-02ECC9635EA0/ThaliTest.app/www/index.html
,2016-01-08 15:48:38.768 ThaliTest[1507:3206726] JXcore Cordova plugin initializing
,2016-01-08 15:48:38.770 ThaliTest[1507:3206959] JXcore instance initializing
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
,2016-01-08 15:48:40.266 ThaliTest[1507:3206726] THREAD WARNING: ['JXcore'] took '90.429932' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 15:53:17.100 ThaliTest[1507:3206959] jxcore: startBroadcasting
,2016-01-08 15:53:17.131 ThaliTest[1507:3206959] server: starting Apple-Iphone5s-1.MP5wlA==
,2016-01-08 15:53:17.134 ThaliTest[1507:3206959] multipeer session: start timer: 0x174b26b0
,2016-01-08 15:53:17.150 ThaliTest[1507:3206959] THEMultipeerSession initialized peer Apple-Iphone5s-1
,2016-01-08 15:53:17.155 ThaliTest[1507:3206959] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-08 15:53:17.759 ThaliTest[1507:3206726] client: found peer: Apple-Iphone6-1.j1bF8Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1.j1bF8Q==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2016-01-08 15:53:17.972 ThaliTest[1507:3206726] client: found peer: Apple-IpadAir2-1.xmg6Nw==
,2016-01-08 15:53:18.463 ThaliTest[1507:3206726] client: found peer: Apple-Iphone5-1.oJtw2A==
,teardown
,testFindPeers stopped
,2016-01-08 15:53:19.145 ThaliTest[1507:3206959] jxcore: stopBroadcasting
2016-01-08 15:53:19.147 ThaliTest[1507:3206959] THEMultipeerSession stopping peer
2016-01-08 15:53:19.147 ThaliTest[1507:3206959] multipeer session: stop timer
2016-01-08 15:53:19.,148 ThaliTest[1507:3206959] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 56701
2016-01-08 15:53:19.216 ThaliTest[1507:3206959] jxcore: startBroadcasting
,2016-01-08 15:53:19.225 ThaliTest[1507:3206959] server: starting Apple-Iphone5s-1.zHt1vQ==
2016-01-08 15:53:19.227 ThaliTest[1507:3206959] multipeer session: start timer: 0x174b65b0
2016-01-08 15:53:19.227 ThaliTest[1507:3206959] THEMultipeerSession init,ialized peer Apple-Iphone5s-1
2016-01-08 15:53:19.228 ThaliTest[1507:3206959] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2016-01-08T14:53:19.236Z SendDataTCPServer.js: TCP/IP server is bound to port: 56701
,2016-01-08 15:53:19.264 ThaliTest[1507:3206726] client: found peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:19.264 ThaliTest[1507:3206726] client: found peer: Apple-IpadAir2-1.xmg6Nw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
2016-01-08 15:53:19.267 ThaliTest[1507:3206726] client: found peer: Apple-Iphone5-1.oJtw2A==
device[1]: Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:19.270Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:19.270Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:19.271Z SendDataConnector.js: do connect now
,2016-01-08 15:53:19.269 ThaliTest[1507:3206726] client: found peer: Apple-Iphone5s-1.MP5wlA==
,2016-01-08 15:53:19.273 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:19.273 ThaliTest[1507:3206959] client session: connect
,2016-01-08 15:53:19.273 ThaliTest[1507:3206959] client session: stateChange:0->1 Apple-Iphone6-1.j1bF8Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xmg6Nw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.MP5wlA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 15:53:20.248 ThaliTest[1507:3206726] client: lost peer: Apple-IpadAir2-1.xmg6Nw==
2016-01-08 15:53:20.248 ThaliTest[1507:3206726] client session: onPeerLost: Apple-IpadAir2-1.xmg6Nw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-,1.xmg6Nw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 15:53:20.512 ThaliTest[1507:3206726] client: lost peer: Apple-Iphone5s-1.MP5wlA==
2016-01-08 15:53:20.512 ThaliTest[1507:3206726] client session: onPeerLost: Apple-Iphone5s-1.MP5wlA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-,1.MP5wlA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 15:53:20.878 ThaliTest[1507:3206726] client: lost peer: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.879 ThaliTest[1507:3206726] client session: onPeerLost: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.879 ThaliTest[1507:3206726] client sessio,n: onLinkFailure: Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:20.880 ThaliTest[1507:3206726] client session: disconnect
2016-01-08 15:53:20.880 ThaliTest[1507:3206726] client session: stateChange:1->0 Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:20.888 ThaliTest[1507:3206726] client session: fireConnectCallback: Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:20.888 ThaliTest[1507:3206726] jxcore: connect: fail: Peer disconnected
2016-01-08T14:53:20.893Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T14:53:20.893Z SendDataConnector.js: CLIENT Can not Connect:, Peer disconnected
2016-01-08T14:53:20.895Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.j1bF8Q==","peerName":"(null)","peerAvailable":false}]
2016-01-08 15:53:20.897 ThaliTest[1507:3206726] c,lient: found peer: Apple-IpadAir2-1.+bX+WA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.+bX+WA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:20.927 ThaliTest[1507:3206726] client: lost peer: Apple-Iphone5-1.oJtw2A==
,2016-01-08 15:53:20.928 ThaliTest[1507:3206726] client session: onPeerLost: Apple-Iphone5-1.oJtw2A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oJtw2A==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2016-01-08 15:53:20.933 ThaliTest[1507:3206726] client: found peer: Apple-Iphone5-1.ziR9IQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.ziR9IQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 15:53:20.936 ThaliTest[1507:3206726] client: found peer: Apple-Iphone6-1.bICwVA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.bICwVA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08T14:53:25.907Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:25.908Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:30.920 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:53:30.921 ThaliTest[1507:3206959] jxcore: disconnect: fail
2016-01-08T14:53:30.922Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:53:30.922Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:30.923Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:30.923Z SendDataConnector.js: do connect now
,2016-01-08 15:53:30.925 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:30.926 ThaliTest[1507:3206959] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:30.926 ThaliTest[1507:3206959] jxcore: connect,: fail: Peer unreachable
2016-01-08T14:53:30.927Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:53:30.927Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:30.927Z SendDataConnector.js:, tryAgain afer: 5000 ms.
,2016-01-08T14:53:35.935Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:35.936Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:40.939 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:53:40.940 ThaliTest[1507:3206959] jxcore: disconnect: fail
2016-01-08T14:53:40.940Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:53:40.941Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:40.941Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
2016-01-08T14:53:40.941Z SendDataConnector.js: do connect now
,2016-01-08 15:53:40.942 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:40.943 ThaliTest[1507:3206959] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:40.943 ThaliTest[1507:3206959] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:40.944Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:53:40.945Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:40.946Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:45.954Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:45.954Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:49.229 ThaliTest[1507:3206726] multipeer session: restart
,2016-01-08 15:53:49.296 ThaliTest[1507:3206726] client: found peer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:53:49.296 ThaliTest[1507:3206726] client: found peer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:53:49.297 ThaliTest[1507:3206726] client: found peer: Apple-Iphone6-1.bICwVA==
,2016-01-08 15:53:50.961 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:53:50.962 ThaliTest[1507:3206959] jxcore: disconnect: fail
2016-01-08T14:53:50.962Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:53:50.963Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:53:50.963Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:50.963Z SendDataConnector.js: do connect now
2016-01-08 15:53:50.964 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:53:50.965 ThaliTest[1507:3206959] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:53:50.966 ThaliTest[1507:3206959] jxcore: connect: fail: Peer unreachable
,2016-01-08T14:53:50.966Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2016-01-08T14:53:50.967Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T14:53:50.968Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T14:53:55.969Z SendDataConnector.js: re-try now : Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:53:55.970Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:54:00.983 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:54:00.984 ThaliTest[1507:3206959] jxcore: disconnect: fail
2016-01-08T14:54:00.984Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
20,16-01-08T14:54:00.985Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.j1bF8Q== with availability status: true
2016-01-08T14:54:00.985Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.j1bF8Q==
,2016-01-08T14:54:00.985Z SendDataConnector.js: do connect now
2016-01-08 15:54:00.986 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.j1bF8Q==
,2016-01-08 15:54:00.987 ThaliTest[1507:3206959] client: connect: unreachable Apple-Iphone6-1.j1bF8Q==
2016-01-08 15:54:00.988 ThaliTest[1507:3206959] jxcore: connect: fail: Peer unreachable
2016-01-08T14:54:00.989Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T14:54:00.989Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2016-01-08T14:54:00.992Z SendDataConnector.js: CLIENT Stop now
,2016-01-08 15:54:00.993 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:54:00.994 ThaliTest[1507:3206959] jxcore: disconnect: fail
,2016-01-08T14:54:00.996Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.j1bF8Q==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:01.000Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:01.001Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.+bX+WA==
,2016-01-08T14:54:01.001Z SendDataConnector.js: do connect now
,2016-01-08 15:54:01.003 ThaliTest[1507:3206959] jxcore: connect Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:01.003 ThaliTest[1507:3206959] client session: connect
2016-01-08 15:54:01.003 ThaliTest[1507:3206959] client session: stateChange:0->1 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.743 ThaliTest[1507:3207552] client session: connected
,2016-01-08 15:54:07.743 ThaliTest[1507:3207552] client session: stateChange:1->2 Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:07.753 ThaliTest[1507:3207552] client session: fireConnectCallback: Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:07.753 ThaliTest[1507:3207552] jxcore: connect: success
2016-01-08T14:54:07.756Z SendDataConnector.js: CLIENT connected to 56706, error: null
2016-01-08T14:54:07.756Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:07.761 ThaliTest[1507:3206726] client: relay established
2016-01-08 15:54:07.762 ThaliTest[1507:3206726] client: new accepted socket: 0x1739d010
,2016-01-08T14:54:07.779Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:08.369Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T14:54:08.419Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-08T14:54:08.430Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T14:54:08.452Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T14:54:08.478Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:08.478Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:08.478Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:08.478Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:08.479 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:54:08.480 ThaliTest[1507:3206959] client session: disconnectFromPeer: Apple-IpadAir2-1.+bX+WA==
2016-01-08 15:54:08.480 ThaliTest[1507:3206959] client session: disconnect
2,016-01-08 15:54:08.480 ThaliTest[1507:3206959] client session: stateChange:2->0 Apple-IpadAir2-1.+bX+WA==
,2016-01-08 15:54:08.485 ThaliTest[1507:3206959] jxcore: disconnect: success
2016-01-08T14:54:08.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.+bX+WA==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5-1.ziR9IQ==
2016-01-08T14:54:08.486Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.ziR9IQ==
2016-01-08T14:54:08.486Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.ziR9IQ==
2016-01-08T14:54:08.486Z SendDataConnector.,js: do connect now
2016-01-08 15:54:08.486 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:08.487 ThaliTest[1507:3206959] client session: connect
2016-01-08 15:54:08.487 ThaliTest[1507:3206959] client session: stateChan,ge:0->1 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:09.835 ThaliTest[1507:3206726] multipeer session: reset timer
2016-01-08 15:54:09.835 ThaliTest[1507:3206726] multipeer session: stop timer
2016-01-08 15:54:09.835 ThaliTest[1507:3206726] multipeer session: start timer: 0x174b65b0
2016-,01-08 15:54:09.836 ThaliTest[1507:3206726] server session: connect
2016-01-08 15:54:09.836 ThaliTest[1507:3206726] server session: stateChange:0->1 Apple-Iphone5-1
,2016-01-08 15:54:09.846 ThaliTest[1507:3206726] server: accepting invitation Apple-Iphone5-1
,2016-01-08 15:54:11.211 ThaliTest[1507:3207552] client session: connected
,2016-01-08 15:54:11.212 ThaliTest[1507:3207552] client session: stateChange:1->2 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:11.483 ThaliTest[1507:3207571] client session: fireConnectCallback: Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:11.483 ThaliTest[1507:3207571] jxcore: connect: success
2016-01-08T14:54:11.486Z SendDataConnector.js: CLIENT connected to 56709, error: null
2016-01-08T14:54:11.488Z SendDataConnector.js: CLIENT starting client 
2016-01-08 15:54:11.492, ThaliTest[1507:3206726] client: relay established
2016-01-08 15:54:11.492 ThaliTest[1507:3206726] client: new accepted socket: 0x174c2670
,2016-01-08T14:54:11.504Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T14:54:12.136Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T14:54:12.184Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T14:54:12.197Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T14:54:12.244Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T14:54:12.258Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-08T14:54:12.284Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:12.284Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T14:54:12.285Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T14:54:12.285Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:12.286 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:54:12.286 ThaliTest[1507:3206959] client session: disconnectFromPeer: Apple-Iphone5-1.ziR9IQ==
2016-01-08 15:54:12.286 ThaliTest[1507:3206959] client session: disconnect
2016-01-08 15:54:12.287 ThaliTest[1507:3206959] client session: stateChange:2->0 Apple-Iphone5-1.ziR9IQ==
,2016-01-08 15:54:12.293 ThaliTest[1507:3206959] jxcore: disconnect: success
2016-01-08T14:54:12.294Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.ziR9IQ==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,ne6-1.bICwVA==
2016-01-08T14:54:12.294Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:12.295Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.bICwVA==
2016-01-08T14:54:12.295Z SendDataConnector.js: do connect now
2016-01-08 15:54:12.295 ThaliTest[1507:3206959] jxcore: connect Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:12.295 ThaliTest[1507:3206959] client session: connect
2016-01-08 15:54:12.295 ThaliTest[1507:3206959] client session: stateChang,e:0->1 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:12.602 ThaliTest[1507:3207527] server session: connected
,2016-01-08 15:54:12.603 ThaliTest[1507:3207527] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-08T14:54:12.689Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08 15:54:12.690 ThaliTest[1507:3206726] server relay: connected (to port: 56701)
,2016-01-08 15:54:12.771 ThaliTest[1507:3206726] multipeer session: reset timer
2016-01-08 15:54:12.771 ThaliTest[1507:3206726] multipeer session: stop timer
2016-01-08 15:54:12.772 ThaliTest[1507:3206726] multipeer session: start timer: 0x174b65b0
2016-01-08 15:54:12.772 ThaliTest[1507:3206726] server session: connect
2016-01-08 15:54:12.772 ThaliTest[1507:3206726] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 15:54:12.782 ThaliTest[1507:3206726] server: accepting invitation Apple-Iphone6-1
,2016-01-08 15:54:13.637 ThaliTest[1507:3206726] multipeer session: reset timer
2016-01-08 15:54:13.637 ThaliTest[1507:3206726] multipeer session: stop timer
2016-01-08 15:54:13.637 ThaliTest[1507:3206726] multipeer session: start timer: 0x174b65b0
2016-,01-08 15:54:13.638 ThaliTest[1507:3206726] server session: connect
2016-01-08 15:54:13.638 ThaliTest[1507:3206726] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-08T14:54:13.644Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08 15:54:13.680 ThaliTest[1507:3206726] server: accepting invitation Apple-IpadAir2-1
,2016-01-08T14:54:13.691Z SendDataTCPServer.js: TCP/IP server has received 16597 bytes of data
,2016-01-08T14:54:13.710Z SendDataTCPServer.js: TCP/IP server has received 27375 bytes of data
,2016-01-08T14:54:13.723Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2016-01-08T14:54:13.739Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2016-01-08T14:54:13.753Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-08T14:54:13.764Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-08T14:54:13.780Z SendDataTCPServer.js: TCP/IP server has received 55845 bytes of data
,2016-01-08T14:54:13.792Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2016-01-08T14:54:13.806Z SendDataTCPServer.js: TCP/IP server has received 66795 bytes of data
,2016-01-08T14:54:13.821Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2016-01-08T14:54:13.835Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-08T14:54:13.849Z SendDataTCPServer.js: TCP/IP server has received 89435 bytes of data
,2016-01-08T14:54:13.864Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:13.954 ThaliTest[1507:3207552] server session: not connected Apple-Iphone5-1
,2016-01-08 15:54:14.978 ThaliTest[1507:3207527] client session: connected
2016-01-08 15:54:14.978 ThaliTest[1507:3207527] client session: stateChange:1->2 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:14.988 ThaliTest[1507:3207527] client session: fireConnectCallback: Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:14.988 ThaliTest[1507:3207527] jxcore: connect: success
2016-01-08T14:54:14.991Z SendDataConnector.js: CLIENT connected to 5671,3, error: null
2016-01-08T14:54:14.992Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 15:54:14.998 ThaliTest[1507:3206726] client: relay established
2016-01-08 15:54:14.999 ThaliTest[1507:3206726] client: new accepted socket: 0x174d13d0
,2016-01-08T14:54:15.011Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 15:54:15.328 ThaliTest[1507:3207552] server session: connected
2016-01-08 15:54:15.328 ThaliTest[1507:3207552] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 15:54:15.332 ThaliTest[1507:3206726] server relay: connected (to port: 56701)
,2016-01-08T14:54:15.518Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T14:54:15.865Z SendDataTCPServer.js: TCP/IP server has received 3285 bytes of data
,2016-01-08T14:54:15.878Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2016-01-08T14:54:15.931Z SendDataTCPServer.js: TCP/IP server has received 14235 bytes of data
,2016-01-08T14:54:15.946Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2016-01-08T14:54:15.950Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T14:54:15.963Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2016-01-08T14:54:15.979Z SendDataTCPServer.js: TCP/IP server has received 64605 bytes of data
,2016-01-08T14:54:15.997Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
2016-01-08T14:54:16.000Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-08T14:54:16.000Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-08T14:54:16.001Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:16.001Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 15:54:16.002 ThaliTest[1507:3206959] jxcore: disconnect
2016-01-08 15:54:16.002 ThaliTest[1507:3206959] client session: disconnectFromPeer: Apple-Iphone6-1.bICwVA==
2016-01-08 15:54:16.003 ThaliTest[1507:3206959] client session: disconnect
2016-01-08 15:54:16.004 ThaliTest[1507:3206959] client session: stateChange:2->0 Apple-Iphone6-1.bICwVA==
,2016-01-08 15:54:16.087 ThaliTest[1507:3206959] jxcore: disconnect: success
2016-01-08T14:54:16.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.bICwVA==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-08T14:54:16.117Z SendDataConnector.js: CLIENT Stop now
2016-01-08T14:54:16.118Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08T14:54:16.133Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:16.218 ThaliTest[1507:3207552] server session: not connected Apple-Iphone6-1
,2016-01-08 15:54:17.043 ThaliTest[1507:3207552] server session: connected
2016-01-08 15:54:17.043 ThaliTest[1507:3207552] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-08 15:54:17.050 ThaliTest[1507:3206726] server relay: connected (to port: 56701)
2016-01-08T14:54:17.052Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T14:54:17.550Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2016-01-08T14:54:17.568Z SendDataTCPServer.js: TCP/IP server has received 19497 bytes of data
,2016-01-08T14:54:17.583Z SendDataTCPServer.js: TCP/IP server has received 27304 bytes of data
,2016-01-08T14:54:17.596Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
,2016-01-08T14:54:17.612Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2016-01-08T14:54:17.628Z SendDataTCPServer.js: TCP/IP server has received 47085 bytes of data
,2016-01-08T14:54:17.642Z SendDataTCPServer.js: TCP/IP server has received 55845 bytes of data
,2016-01-08T14:54:17.656Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2016-01-08T14:54:17.670Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-08T14:54:17.684Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-08T14:54:17.698Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 15:54:18.004 ThaliTest[1507:3207571] server session: not connected Apple-IpadAir2-1
,teardown
,testSendData stopped
,2016-01-08 15:54:18.879 ThaliTest[1507:3206959] jxcore: stopBroadcasting
2016-01-08 15:54:18.880 ThaliTest[1507:3206959] THEMultipeerSession stopping peer
2016-01-08 15:54:18.880 ThaliTest[1507:3206959] multipeer session: stop timer
2016-01-08 15:54:18.,881 ThaliTest[1507:3206959] server session: disconnect
2016-01-08 15:54:18.881 ThaliTest[1507:3206959] server session: stateChange:2->0 Apple-Iphone6-1
2016-01-08 15:54:18.889 ThaliTest[1507:3206959] server session: disconnect
2016-01-08 15:54:18.890 Th,aliTest[1507:3206959] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-08 15:54:18.909 ThaliTest[1507:3206959] server session: disconnect
2016-01-08 15:54:18.909 ThaliTest[1507:3206959] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 15:54:18.926 ThaliTest[1507:3206959] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
