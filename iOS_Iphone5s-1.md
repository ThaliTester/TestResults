#### Test 55613145dd493c6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1E757A33-1F6C-4F86-962F-97F001AA3D8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1E757A33-1F6C-4F86-962F-97F001AA3D8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145dd493c6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5EBC6FB5-698B-4F80-8CC1-B61742A6EAC2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52221"
,(lldb)     command script import "/tmp/1E757A33-1F6C-4F86-962F-97F001AA3D8F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 13:54:30.525 ThaliTest[1721:3751190] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CD644DB8-2761-4A81-AA97-CD1BA0FE7163/Library/Cookies/Cookies.binarycookies
,2016-01-11 13:54:30.807 ThaliTest[1721:3751190] Apache Cordova native platform version 3.9.2 is starting.
2016-01-11 13:54:30.808 ThaliTest[1721:3751190] Multi-tasking -> Device: YES, App: YES
,2016-01-11 13:54:30.815 ThaliTest[1721:3751190] Unlimited access to network resources
,2016-01-11 13:54:30.824 ThaliTest[1721:3751190] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 13:54:34.989 ThaliTest[1721:3751190] Resetting plugins due to page load.
,2016-01-11 13:54:36.330 ThaliTest[1721:3751190] Finished load of: file:///var/mobile/Containers/Bundle/Application/5EBC6FB5-698B-4F80-8CC1-B61742A6EAC2/ThaliTest.app/www/index.html
,2016-01-11 13:54:36.516 ThaliTest[1721:3751190] JXcore Cordova plugin initializing
,2016-01-11 13:54:36.518 ThaliTest[1721:3751348] JXcore instance initializing
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
2016-01-11 13:59:31.464 ThaliTest[1721:3751348] jxcore: startBroadcasting
,2016-01-11 13:59:31.474 ThaliTest[1721:3751348] server: starting Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:31.474 ThaliTest[1721:3751348] multipeer session: start timer: 0x1646dac0
2016-01-11 13:59:31.474 ThaliTest[1721:3751348] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-11 13:59:31.476 ThaliTest[1721:3751348] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2016-01-11 13:59:32.696 ThaliTest[1721:3751190] client: found peer: Apple-Iphone6-1.4vXNuA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.4vXNuA==, peerAvail,able: true
weAreDoneNow
done, now sending data to server
,2016-01-11 13:59:32.961 ThaliTest[1721:3751190] client: found peer: Apple-Iphone5-1.b8hDBw==
,2016-01-11 13:59:33.287 ThaliTest[1721:3751190] client: found peer: Apple-IpadAir2-1.xr446Q==
,teardown
,testFindPeers stopped
2016-01-11 13:59:33.449 ThaliTest[1721:3751348] jxcore: stopBroadcasting
2016-01-11 13:59:33.449 ThaliTest[1721:3751348] THEMultipeerSession stopping peer
2016-01-11 13:59:33.449 ThaliTest[1721:3751348] multipeer session: stop timer
2016-01-11 13:59:33.449 ThaliTest[1721:3751348] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":2,0000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
daya100000
check server
,serverPort is 58213
2016-01-11 13:59:33.459 ThaliTest[1721:3751348] jxcore: startBroadcasting
,2016-01-11 13:59:33.462 ThaliTest[1721:3751348] server: starting Apple-Iphone5s-1.yPThEg==
2016-01-11 13:59:33.462 ThaliTest[1721:3751348] multipeer session: start timer: 0x14d1b110
2016-01-11 13:59:33.462 ThaliTest[1721:3751348] THEMultipeerSession initialized peer Apple-Iphone5s-1
2016-01-11 13:59:33.462 ThaliTest[1721:3751348] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-11T12:59:33.464Z SendDataTCPServer.js: TCP/IP server is bound to port: 58213
,2016-01-11 13:59:33.501 ThaliTest[1721:3751190] client: found peer: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:33.501 ThaliTest[1721:3751190] client: found peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:33.501 ThaliTest[1721:3751190] client: found peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:33.502 ThaliTest[1721:3751190] client: found peer: Apple-IpadAir2-1.xr446Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null),, Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:33.505Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:33.506Z SendDataConnector.js: doConnect called with peer Apple-Ipho,ne6-1.4vXNuA==
2016-01-11T12:59:33.506Z SendDataConnector.js: do connect now
2016-01-11 13:59:33.506 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.4vXNuA==
,2016-01-11 13:59:33.506 ThaliTest[1721:3751348] client session: connect
2016-01-11 13:59:33.511 ThaliTest[1721:3751348] client session: stateChange:0->1 Apple-Iphone6-1.4vXNuA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-11 13:59:34.590 ThaliTest[1721:3751190] client: lost peer: Apple-Iphone5s-1.hXPtug==
2016-01-11 13:59:34.590 ThaliTest[1721:3751190] client session: onPeerLost: Apple-Iphone5s-1.hXPtug==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.hXPtug==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 13:59:34.697 ThaliTest[1721:3751190] client: lost peer: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:34.697 ThaliTest[1721:3751190] client session: onPeerLost: Apple-Iphone5-1.b8hDBw==
2016-01-11 13:59:34.698 ThaliTest[1721:3751190] client: lost ,peer: Apple-IpadAir2-1.xr446Q==
2016-01-11 13:59:34.698 ThaliTest[1721:3751190] client session: onPeerLost: Apple-IpadAir2-1.xr446Q==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.b8hDBw==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.xr446Q==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 13:59:34.774 ThaliTest[1721:3751190] client: found peer: Apple-IpadAir2-1.oW56/g==
2016-01-11 13:59:34.775 ThaliTest[1721:3751190] client: found peer: Apple-Iphone5-1.03CIBg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.oW56/g,==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.03CIBg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:35.412 ThaliTest[1721:3751190] client: found peer: Apple-Iphone6-1.zQytdg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.zQytdg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 13:59:39.706 ThaliTest[1721:3751190] client: lost peer: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.706 ThaliTest[1721:3751190] client session: onPeerLost: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.706 ThaliTest[1721:3751190] client session: onLinkFailure: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.707 ThaliTest[1721:3751190] client session: disconnect
2016-01-11 13:59:39.707 ThaliTest[1721:3751190] client session: stateChange:1->0 Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.707 Thali,Test[1721:3751190] client session: fireConnectCallback: Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:39.707 ThaliTest[1721:3751190] jxcore: connect: fail: Peer disconnected
2016-01-11T12:59:39.708Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-11T12:59:39.708Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11T12:59:39.708Z SendDataConnector.js: tryAgain afer: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.4vXNuA==","peerName":",(null)","peerAvailable":false}]
,2016-01-11T12:59:44.717Z SendDataConnector.js: re-try now : Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:44.718Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.4vXNuA==
,2016-01-11 13:59:49.721 ThaliTest[1721:3751348] jxcore: disconnect
2016-01-11 13:59:49.721 ThaliTest[1721:3751348] jxcore: disconnect: fail
2016-01-11T12:59:49.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.4vXNuA==
20,16-01-11T12:59:49.722Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.4vXNuA== with availability status: true
2016-01-11T12:59:49.722Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:49.72,2Z SendDataConnector.js: do connect now
2016-01-11 13:59:49.722 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:49.722 ThaliTest[1721:3751348] client: connect: unreachable Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:49.72,2 ThaliTest[1721:3751348] jxcore: connect: fail: Peer unreachable
2016-01-11T12:59:49.723Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:49.723Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-,01-11T12:59:49.723Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T12:59:54.734Z SendDataConnector.js: re-try now : Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:54.735Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.4vXNuA==
,2016-01-11 13:59:59.743 ThaliTest[1721:3751348] jxcore: disconnect
2016-01-11 13:59:59.744 ThaliTest[1721:3751348] jxcore: disconnect: fail
2016-01-11T12:59:59.744Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:59.744Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.4vXNuA== with availability status: true
2016-01-11T12:59:59.744Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T12:59:59.74,4Z SendDataConnector.js: do connect now
,2016-01-11 13:59:59.745 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:59.745 ThaliTest[1721:3751348] client: connect: unreachable Apple-Iphone6-1.4vXNuA==
2016-01-11 13:59:59.745 ThaliTest[1721:3751348] jxcore: connect,: fail: Peer unreachable
2016-01-11T12:59:59.746Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T12:59:59.746Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-11T12:59:59.746Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11 14:00:03.462 ThaliTest[1721:3751190] multipeer session: restart
,2016-01-11 14:00:03.488 ThaliTest[1721:3751190] client: found peer: Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:03.492 ThaliTest[1721:3751190] client: found peer: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:03.492 ThaliTest[1721:3751190] client: found peer: Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:04.757Z SendDataConnector.js: re-try now : Apple-Iphone6-1.4vXNuA==
,2016-01-11T13:00:04.757Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.4vXNuA==
,2016-01-11 14:00:09.765 ThaliTest[1721:3751348] jxcore: disconnect
2016-01-11 14:00:09.765 ThaliTest[1721:3751348] jxcore: disconnect: fail
2016-01-11T13:00:09.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T13:00:09.765Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.4vXNuA== with availability status: true
2016-01-11T13:00:09.765Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T13:00:09.76,6Z SendDataConnector.js: do connect now
2016-01-11 14:00:09.766 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.4vXNuA==
2016-01-11 14:00:09.766 ThaliTest[1721:3751348] client: connect: unreachable Apple-Iphone6-1.4vXNuA==
2016-01-11 14:00:09.766 ThaliTest[1721:3751348] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:09.766Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:09.766Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-,01-11T13:00:09.766Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T13:00:14.770Z SendDataConnector.js: re-try now : Apple-Iphone6-1.4vXNuA==
2016-01-11T13:00:14.770Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.4vXNuA==
,2016-01-11 14:00:19.779 ThaliTest[1721:3751348] jxcore: disconnect
2016-01-11 14:00:19.779 ThaliTest[1721:3751348] jxcore: disconnect: fail
2016-01-11T13:00:19.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.4vXNuA==
20,16-01-11T13:00:19.779Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.4vXNuA== with availability status: true
2016-01-11T13:00:19.779Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.4vXNuA==
2016-01-11T13:00:19.779Z SendDataConnector.js: do connect now
2016-01-11 14:00:19.780 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.4vXNuA==
2016-01-11 14:00:19.780 ThaliTest[1721:3751348] client: connect: unreachable Apple-Iphone6-1.4vXNuA==
2016-01-11 14:00:19.780 ThaliTest[1721:3751348] jxcore: connect: fail: Peer unreachable
2016-01-11T13:00:19.780Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T13:00:19.780Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRo,undDownNow
2016-01-11T13:00:19.783Z SendDataConnector.js: CLIENT Stop now
2016-01-11 14:00:19.784 ThaliTest[1721:3751348] jxcore: disconnect
2016-01-11 14:00:19.784 ThaliTest[1721:3751348] jxcore: disconnect: fail
2016-01-11T13:00:19.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.4vXNuA==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.oW56/g==
2016-01-11T13:00:19.785Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.oW56/g==
2,016-01-11T13:00:19.785Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.oW56/g==
2016-01-11T13:00:19.785Z SendDataConnector.js: do connect now
2016-01-11 14:00:19.785 ThaliTest[1721:3751348] jxcore: connect Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:19.785 ThaliTest[1721:3751348] client session: connect
2016-01-11 14:00:19.786 ThaliTest[1721:3751348] client session: stateChange:0->1 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:21.703 ThaliTest[1721:3751190] multipeer session: reset timer
2016-01-11 14:00:21.703 ThaliTest[1721:3751190] multipeer session: stop timer
2016-01-11 14:00:21.703 ThaliTest[1721:3751190] multipeer session: start timer: 0x14d1b110
2016-01-11 14:00:21.703 ThaliTest[1721:3751190] server session: connect
2016-01-11 14:00:21.703 ThaliTest[1721:3751190] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-11 14:00:21.709 ThaliTest[1721:3751190] server: accepting invitation Apple-IpadAir2-1
,2016-01-11 14:00:22.618 ThaliTest[1721:3751190] multipeer session: reset timer
2016-01-11 14:00:22.618 ThaliTest[1721:3751190] multipeer session: stop timer
2016-01-11 14:00:22.618 ThaliTest[1721:3751190] multipeer session: start timer: 0x14d1b110
2016-,01-11 14:00:22.619 ThaliTest[1721:3751190] server session: connect
2016-01-11 14:00:22.619 ThaliTest[1721:3751190] server session: stateChange:0->1 Apple-Iphone5-1
2016-01-11 14:00:22.622 ThaliTest[1721:3751190] server: accepting invitation Apple-Iphone5-1
,2016-01-11 14:00:23.082 ThaliTest[1721:3752289] client session: connected
2016-01-11 14:00:23.082 ThaliTest[1721:3752289] client session: stateChange:1->2 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:23.085 ThaliTest[1721:3752289] client session: fireConnectCallback: Apple-IpadAir2-1.oW56/g==
2016-01-11 14:00:23.085 ThaliTest[1721:3752289] jxcore: connect: success
2016-01-11T13:00:23.086Z SendDataConnector.js: CLIENT connected to 58217, error: null
2016-01-11T13:00:23.086Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:23.088 ThaliTest[1721:3751190] client: relay established
2016-01-11 14:00:23.088 ThaliTest[1721:3751190] client: new accepted socket: 0x164844b0
,2016-01-11T13:00:23.102Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:23.579Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T13:00:23.596Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-11T13:00:23.609Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:23.610Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-11T13:00:23.610Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:23.610Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:23.611 ThaliTest[1721:3751348] jxcore: disconnect
,2016-01-11 14:00:23.612 ThaliTest[1721:3751348] client session: disconnectFromPeer: Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:23.612 ThaliTest[1721:3751348] client session: disconnect
,2016-01-11 14:00:23.613 ThaliTest[1721:3751348] client session: stateChange:2->0 Apple-IpadAir2-1.oW56/g==
,2016-01-11 14:00:23.681 ThaliTest[1721:3751348] jxcore: disconnect: success
,2016-01-11T13:00:23.681Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.oW56/g==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1.03CIBg==
,2016-01-11T13:00:23.683Z SendDataConnector.js: Start called with peer Apple-Iphone5-1.03CIBg==
,2016-01-11T13:00:23.683Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1.03CIBg==
,2016-01-11T13:00:23.683Z SendDataConnector.js: do connect now
,2016-01-11 14:00:23.685 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:23.685 ThaliTest[1721:3751348] client session: connect
,2016-01-11 14:00:23.686 ThaliTest[1721:3751348] client session: stateChange:0->1 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:24.779 ThaliTest[1721:3752269] server session: connected
2016-01-11 14:00:24.779 ThaliTest[1721:3752269] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11 14:00:24.783 ThaliTest[1721:3751190] server relay: connected (to port: 58213)
,2016-01-11T13:00:24.786Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11 14:00:25.109 ThaliTest[1721:3752269] server session: connected
,2016-01-11 14:00:25.109 ThaliTest[1721:3752269] server session: stateChange:1->2 Apple-Iphone5-1
,2016-01-11 14:00:25.178 ThaliTest[1721:3751190] server relay: connected (to port: 58213)
2016-01-11T13:00:25.179Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
2016-01-11T13:00:25.181Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:25.195Z SendDataTCPServer.js: TCP/IP server has received 50299 bytes of data
,2016-01-11T13:00:25.209Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-11T13:00:25.365Z SendDataTCPServer.js: TCP/IP server has received 71175 bytes of data
,2016-01-11T13:00:25.376Z SendDataTCPServer.js: TCP/IP server has received 94981 bytes of data
,2016-01-11T13:00:25.390Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:25.465 ThaliTest[1721:3752326] server session: not connected Apple-IpadAir2-1
,2016-01-11T13:00:26.621Z SendDataTCPServer.js: TCP/IP server has received 10879 bytes of data
,2016-01-11T13:00:26.635Z SendDataTCPServer.js: TCP/IP server has received 33945 bytes of data
,2016-01-11T13:00:26.687Z SendDataTCPServer.js: TCP/IP server has received 51323 bytes of data
,2016-01-11T13:00:26.701Z SendDataTCPServer.js: TCP/IP server has received 79935 bytes of data
,2016-01-11T13:00:26.749Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-11T13:00:26.811Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2016-01-11T13:00:26.825Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:26.893 ThaliTest[1721:3752326] client session: connected
2016-01-11 14:00:26.893 ThaliTest[1721:3752326] client session: stateChange:1->2 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:26.927 ThaliTest[1721:3752274] server session: not connected Apple-Iphone5-1
,2016-01-11 14:00:26.934 ThaliTest[1721:3752272] client session: fireConnectCallback: Apple-Iphone5-1.03CIBg==
2016-01-11 14:00:26.935 ThaliTest[1721:3752272] jxcore: connect: success
2016-01-11T13:00:26.936Z SendDataConnector.js: CLIENT connected to 58222, error: null
2016-01-11T13:00:26.936Z SendDataConnector.js: CLIENT starting client 
2016-01-11 14:00:26.938 ThaliTest[1721:3751190] client: relay established
2016-01-11 14:00:26.938 ThaliTest[1721:3751190] client: new accepted socket: 0x16490d80
,2016-01-11T13:00:26.950Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 14:00:27.070 ThaliTest[1721:3751190] multipeer session: reset timer
2016-01-11 14:00:27.070 ThaliTest[1721:3751190] multipeer session: stop timer
2016-01-11 14:00:27.070 ThaliTest[1721:3751190] multipeer session: start timer: 0x14d1b110
2016-,01-11 14:00:27.070 ThaliTest[1721:3751190] server session: connect
2016-01-11 14:00:27.070 ThaliTest[1721:3751190] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-11 14:00:27.074 ThaliTest[1721:3751190] server: accepting invitation Apple-Iphone6-1
,2016-01-11T13:00:27.744Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-11T13:00:27.796Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-11T13:00:27.811Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T13:00:27.811Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T13:00:27.812Z SendDataConnector.js: CLIENT Stop now
2016-01-11T13:00:27.812Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:27.813 ThaliTest[1721:3751348] jxcore: disconnect
,2016-01-11 14:00:27.813 ThaliTest[1721:3751348] client session: disconnectFromPeer: Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:27.814 ThaliTest[1721:3751348] client session: disconnect
,2016-01-11 14:00:27.815 ThaliTest[1721:3751348] client session: stateChange:2->0 Apple-Iphone5-1.03CIBg==
,2016-01-11 14:00:27.885 ThaliTest[1721:3751348] jxcore: disconnect: success
,2016-01-11T13:00:27.886Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1.03CIBg==
,---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.887Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.887Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.zQytdg==
,2016-01-11T13:00:27.887Z SendDataConnector.js: do connect now
,2016-01-11 14:00:27.888 ThaliTest[1721:3751348] jxcore: connect Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:27.888 ThaliTest[1721:3751348] client session: connect
,2016-01-11 14:00:27.888 ThaliTest[1721:3751348] client session: stateChange:0->1 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:29.441 ThaliTest[1721:3752326] server session: connected
,2016-01-11 14:00:29.441 ThaliTest[1721:3752326] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 14:00:29.446 ThaliTest[1721:3751190] server relay: connected (to port: 58213)
,2016-01-11T13:00:29.450Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T13:00:30.098Z SendDataTCPServer.js: TCP/IP server has received 15117 bytes of data
,2016-01-11T13:00:30.112Z SendDataTCPServer.js: TCP/IP server has received 50714 bytes of data
,2016-01-11T13:00:30.126Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-11T13:00:30.161Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-11T13:00:30.174Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T13:00:30.223Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2016-01-11T13:00:30.271Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2016-01-11T13:00:30.282Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 14:00:30.336 ThaliTest[1721:3752326] server session: not connected Apple-Iphone6-1
,2016-01-11 14:00:30.352 ThaliTest[1721:3752326] client session: connected
,2016-01-11 14:00:30.352 ThaliTest[1721:3752326] client session: stateChange:1->2 Apple-Iphone6-1.zQytdg==
2016-01-11 14:00:30.356 ThaliTest[1721:3752326] client session: fireConnectCallback: Apple-Iphone6-1.zQytdg==
2016-01-11 14:00:30.356 ThaliTest[1721,:3752326] jxcore: connect: success
2016-01-11T13:00:30.357Z SendDataConnector.js: CLIENT connected to 58226, error: null
2016-01-11T13:00:30.357Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 14:00:30.358 ThaliTest[1721:3751190] client: relay established
2016-01-11 14:00:30.360 ThaliTest[1721:3751190] client: new accepted socket: 0x163a5ba0
,2016-01-11T13:00:30.370Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T13:00:31.009Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T13:00:31.071Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T13:00:31.135Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T13:00:31.330Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T13:00:31.330Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T13:00:31.331Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:31.331Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 14:00:31.331 ThaliTest[1721:3751348] jxcore: disconnect
,2016-01-11 14:00:31.332 ThaliTest[1721:3751348] client session: disconnectFromPeer: Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.333 ThaliTest[1721:3751348] client session: disconnect
,2016-01-11 14:00:31.333 ThaliTest[1721:3751348] client session: stateChange:2->0 Apple-Iphone6-1.zQytdg==
,2016-01-11 14:00:31.400 ThaliTest[1721:3751348] jxcore: disconnect: success
,2016-01-11T13:00:31.401Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.zQytdg==
---- round done--------
,startWithNextDevice
,weAreDoneNow, resultArray.length: 4
,sendReportNow
,done, now sending data to server
,2016-01-11T13:00:31.414Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T13:00:31.414Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
2016-01-11 14:00:32.259 ThaliTest[1721:3751348] jxcore: stopBroadcasting
,2016-01-11 14:00:32.260 ThaliTest[1721:3751348] THEMultipeerSession stopping peer
2016-01-11 14:00:32.260 ThaliTest[1721:3751348] multipeer session: stop timer
,2016-01-11 14:00:32.260 ThaliTest[1721:3751348] server session: disconnect
2016-01-11 14:00:32.260 ThaliTest[1721:3751348] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-11 14:00:32.264 ThaliTest[1721:3751348] server session: disconnect
2016-01-11 14:00:32.264 ThaliTest[1721:3751348] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-11 14:00:32.858 ThaliTest[1721:3751348] server session: disconnect
2016-01-11 14:00:32.858 ThaliTest[1721:3751348] server session: stateChange:2->0 Apple-Iphone5-1
,2016-01-11 14:00:32.862 ThaliTest[1721:3751348] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
