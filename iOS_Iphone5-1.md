#### Test 55613145e2b298d_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D47B2110-D31A-4889-B38A-0CD45F25518C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D47B2110-D31A-4889-B38A-0CD45F25518C/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55613145e2b298d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3374D37E-867B-4655-AFEF-B2A29C74F647/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52456"
,(lldb)     command script import "/tmp/D47B2110-D31A-4889-B38A-0CD45F25518C/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-11 15:37:13.746 ThaliTest[1250:4060060] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3172268D-F97A-481D-A3FA-83A9035F6992/Library/Cookies/Cookies.binarycookies
,2016-01-11 15:37:14.090 ThaliTest[1250:4060060] Apache Cordova native platform version 3.9.2 is starting.
2016-01-11 15:37:14.091 ThaliTest[1250:4060060] Multi-tasking -> Device: YES, App: YES
2016-01-11 15:37:14.095 ThaliTest[1250:4060060] Unlimited acc,ess to network resources
,2016-01-11 15:37:14.105 ThaliTest[1250:4060060] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-11 15:37:20.165 ThaliTest[1250:4060060] Resetting plugins due to page load.
,2016-01-11 15:37:21.944 ThaliTest[1250:4060060] Finished load of: file:///var/mobile/Containers/Bundle/Application/3374D37E-867B-4655-AFEF-B2A29C74F647/ThaliTest.app/www/index.html
,2016-01-11 15:37:22.137 ThaliTest[1250:4060060] JXcore Cordova plugin initializing
,2016-01-11 15:37:22.138 ThaliTest[1250:4060190] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,Perf Test app loaded loaded
2016-01-11 15:37:24.278 ThaliTest[1250:4060190] Native method   _callback_   not found.
,check test folder
found test : ./testFindPeers.js
,found test : ./testSendData.js
,Connected to the server!
LogCallback not set !!!!
,--- start :testFindPeers.js---
LogCallback not set !!!!
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-11 15:43:41.617 ThaliTest[1250:4060190] jxcore: startBroadcasting
,2016-01-11 15:43:41.627 ThaliTest[1250:4060190] server: starting Apple-Iphone5-1.oKqzPQ==
,2016-01-11 15:43:41.630 ThaliTest[1250:4060190] multipeer session: start timer: 0x1d4763f0
,2016-01-11 15:43:41.638 ThaliTest[1250:4060190] THEMultipeerSession initialized peer Apple-Iphone5-1
,2016-01-11 15:43:41.639 ThaliTest[1250:4060190] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2016-01-11 15:43:42.683 ThaliTest[1250:4060060] client: found peer: Apple-IpadAir2-1.aUvv7Q==
2016-01-11 15:43:42.684 ThaliTest[1250:4060060] client: found peer: Apple-Iphone6-1.UVBQ1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.aUvv7Q,==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1.aUvv7Q==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,2016-01-11 15:43:46.967 ThaliTest[1250:4060060] client: found peer: Apple-Iphone5s-1.IqfRAg==
,2016-01-11 15:43:47.050 ThaliTest[1250:4060060] multipeer session: reset timer
2016-01-11 15:43:47.050 ThaliTest[1250:4060060] multipeer session: stop timer
2016-01-11 15:43:47.050 ThaliTest[1250:4060060] multipeer session: start timer: 0x1d4763f0
2016-,01-11 15:43:47.050 ThaliTest[1250:4060060] server session: connect
2016-01-11 15:43:47.051 ThaliTest[1250:4060060] server session: stateChange:0->1 Apple-IpadAir2-1
2016-01-11 15:43:47.057 ThaliTest[1250:4060060] server: accepting invitation Apple-IpadAir2-1
,teardown
LogCallback not set !!!!
testFindPeers stopped
,2016-01-11 15:43:48.383 ThaliTest[1250:4060190] jxcore: stopBroadcasting
,2016-01-11 15:43:48.383 ThaliTest[1250:4060190] THEMultipeerSession stopping peer
,2016-01-11 15:43:48.384 ThaliTest[1250:4060190] multipeer session: stop timer
2016-01-11 15:43:48.384 ThaliTest[1250:4060190] server session: disconnect
2016-01-11 15:43:48.385 ThaliTest[1250:4060190] server session: stateChange:1->0 Apple-IpadAir2-1
,2016-01-11 15:43:48.489 ThaliTest[1250:4060190] jxcore: stopBroadcasting: success
StopBroadcasting went ok
--- start :testSendData.js---
LogCallback not set !!!!
testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"ro,unds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 51294
2016-01-11 15:43:48.505 ThaliTest[1250:4060190] jxcore: startBroadcasting
,2016-01-11 15:43:48.508 ThaliTest[1250:4060190] server: starting Apple-Iphone5-1.FPpLTg==
2016-01-11 15:43:48.509 ThaliTest[1250:4060190] multipeer session: start timer: 0x1d3b8bd0
2016-01-11 15:43:48.509 ThaliTest[1250:4060190] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-11 15:43:48.509 ThaliTest[1250:4060190] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
2016-01-11T14:43:48.512Z SendDataTCPServer.js: TCP/IP server is bound to port: 51294
,2016-01-11 15:43:49.520 ThaliTest[1250:4060060] client: found peer: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:49.520 ThaliTest[1250:4060060] client: found peer: Apple-Iphone5-1.oKqzPQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.UVBQ1A==,","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:43:49.523Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:43:4,9.523Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:43:49.523Z SendDataConnector.js: do connect now
2016-01-11 15:43:49.524 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:49.5,24 ThaliTest[1250:4060190] client session: connect
2016-01-11 15:43:49.524 ThaliTest[1250:4060190] client session: stateChange:0->1 Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:49.530 ThaliTest[1250:4060060] client: found peer: Apple-IpadAir2-1.3/8jow==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.oKqzPQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.3/8jow==","peerName":"(null)","peerAvailabl,e":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:49.854 ThaliTest[1250:4060060] client: lost peer: Apple-Iphone5-1.oKqzPQ==
2016-01-11 15:43:49.854 ThaliTest[1250:4060060] client session: onPeerLost: Apple-Iphone5-1.oKqzPQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.o,KqzPQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-11 15:43:50.042 ThaliTest[1250:4060060] client: lost peer: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:50.042 ThaliTest[1250:4060060] client session: onPeerLost: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:50.042 ThaliTest[1250:4060060] client sessio,n: onLinkFailure: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:50.042 ThaliTest[1250:4060060] client session: disconnect
2016-01-11 15:43:50.042 ThaliTest[1250:4060060] client session: stateChange:1->0 Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:50.043 Thali,Test[1250:4060060] client session: fireConnectCallback: Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:43:50.043 ThaliTest[1250:4060060] jxcore: connect: fail: Peer disconnected
2016-01-11T14:43:50.046Z SendDataConnector.js: CLIENT connected to 0, error: Peer di,sconnected
2016-01-11T14:43:50.046Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-11 15:43:50.046 ThaliTest[1250:4060060] client: found peer: Apple-Iphone5s-1./+n+RQ==
2016-01-11T14:43:50.046Z SendDataConnector.js: tryAgain afe,r: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.UVBQ1A==","peerName":"(null)","peerAvailable":false}]
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1./+n+RQ==","peerName":"(null)","peerAvailable":true}]
Found peer : ,(null), Available: true
,2016-01-11 15:43:50.553 ThaliTest[1250:4060060] client: found peer: Apple-Iphone6-1.wtwmkg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.wtwmkg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-11 15:43:54.257 ThaliTest[1250:4060060] multipeer session: reset timer
2016-01-11 15:43:54.257 ThaliTest[1250:4060060] multipeer session: stop timer
2016-01-11 15:43:54.258 ThaliTest[1250:4060060] multipeer session: start timer: 0x1d3b8bd0
2016-,01-11 15:43:54.258 ThaliTest[1250:4060060] server session: connect
2016-01-11 15:43:54.258 ThaliTest[1250:4060060] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-11 15:43:54.266 ThaliTest[1250:4060060] server: accepting invitation Apple-Iphone6-1
,2016-01-11T14:43:55.053Z SendDataConnector.js: re-try now : Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:43:55.053Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.UVBQ1A==
,2016-01-11 15:43:57.027 ThaliTest[1250:4060801] server session: connected
2016-01-11 15:43:57.027 ThaliTest[1250:4060801] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-11 15:43:57.081 ThaliTest[1250:4060060] server relay: connected (to port: 51294)
2016-01-11T14:43:57.082Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:43:57.623Z SendDataTCPServer.js: TCP/IP server has received 22853 bytes of data
2016-01-11T14:43:57.637Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-11T14:43:57.652Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2016-01-11T14:43:57.872Z SendDataTCPServer.js: TCP/IP server has received 59059 bytes of data
,2016-01-11T14:43:57.892Z SendDataTCPServer.js: TCP/IP server has received 74105 bytes of data
,2016-01-11T14:43:57.907Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-11T14:43:57.939Z SendDataTCPServer.js: TCP/IP server has received 75555 bytes of data
,2016-01-11T14:43:57.952Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:43:58.063 ThaliTest[1250:4060803] server session: not connected Apple-Iphone6-1
,2016-01-11 15:44:00.064 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:00.064 ThaliTest[1250:4060190] jxcore: disconnect: fail
2016-01-11T14:44:00.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.UVBQ1A==
20,16-01-11T14:44:00.065Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.UVBQ1A== with availability status: true
2016-01-11T14:44:00.065Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.UVBQ1A==
,2016-01-11T14:44:00.065Z SendDataConnector.js: do connect now
2016-01-11 15:44:00.066 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:00.066 ThaliTest[1250:4060190] client: connect: unreachable Apple-Iphone6-1.UVBQ1A==
,2016-01-11 15:44:00.066 ThaliTest[1250:4060190] jxcore: connect: fail: Peer unreachable
,2016-01-11T14:44:00.067Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:00.067Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-11T14:44:00.067Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:05.078Z SendDataConnector.js: re-try now : Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:05.079Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.UVBQ1A==
,2016-01-11 15:44:10.084 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:10.085 ThaliTest[1250:4060190] jxcore: disconnect: fail
2016-01-11T14:44:10.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.UVBQ1A==
20,16-01-11T14:44:10.085Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.UVBQ1A== with availability status: true
2016-01-11T14:44:10.085Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:10.08,6Z SendDataConnector.js: do connect now
2016-01-11 15:44:10.086 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:10.086 ThaliTest[1250:4060190] client: connect: unreachable Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:10.08,6 ThaliTest[1250:4060190] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:10.086Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:10.087Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016,-,01-11T14:44:10.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11T14:44:15.094Z SendDataConnector.js: re-try now : Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:15.095Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.UVBQ1A==
,2016-01-11 15:44:20.103 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:20.103 ThaliTest[1250:4060190] jxcore: disconnect: fail
2016-01-11T14:44:20.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.UVBQ1A==
20,16-01-11T14:44:20.104Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.UVBQ1A== with availability status: true
2016-01-11T14:44:20.104Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:20.10,4Z SendDataConnector.js: do connect now
2016-01-11 15:44:20.104 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:20.104 ThaliTest[1250:4060190] client: connect: unreachable Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:20.10,5 ThaliTest[1250:4060190] jxcore: connect: fail: Peer unreachable
2016-01-11T14:44:20.105Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:20.105Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016,-,01-11T14:44:20.105Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-11 15:44:24.259 ThaliTest[1250:4060060] multipeer session: restart
,2016-01-11 15:44:24.291 ThaliTest[1250:4060060] client: found peer: Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:44:24.291 ThaliTest[1250:4060060] client: found peer: Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:24.296 ThaliTest[1250:4060060] client: found peer: Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:25.118Z SendDataConnector.js: re-try now : Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:25.118Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.UVBQ1A==
,2016-01-11 15:44:30.127 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:30.128 ThaliTest[1250:4060190] jxcore: disconnect: fail
2016-01-11T14:44:30.128Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.UVBQ1A==
20,16-01-11T14:44:30.128Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.UVBQ1A== with availability status: true
2016-01-11T14:44:30.129Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.UVBQ1A==
2016-01-11T14:44:30.129Z SendDataConnector.js: do connect now
,2016-01-11 15:44:30.129 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:30.129 ThaliTest[1250:4060190] client: connect: unreachable Apple-Iphone6-1.UVBQ1A==
2016-01-11 15:44:30.130 ThaliTest[1250:4060190] jxcore: connect: fail: Peer unreachable
,2016-01-11T14:44:30.130Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-11T14:44:30.130Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
2016-01-11T14:44:30.132Z SendDataConnector.js: CLIENT Stop now
2016-01-11 15:44:30.132 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:30.132 ThaliTest[1250:4060190] jxcore: disconnect: fail
2016-01-11T14:44:30.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.UVBQ1A==
---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:30.134Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:30.134Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.3/8jow==
2016-01-11T14:44:30.134Z SendDataConnector.js: do connect now
,2016-01-11 15:44:30.136 ThaliTest[1250:4060190] jxcore: connect Apple-IpadAir2-1.3/8jow==
2016-01-11 15:44:30.136 ThaliTest[1250:4060190] client session: connect
2016-01-11 15:44:30.136 ThaliTest[1250:4060190] client session: stateChange:0->1 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:36.067 ThaliTest[1250:4060855] client session: connected
2016-01-11 15:44:36.067 ThaliTest[1250:4060855] client session: stateChange:1->2 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:36.074 ThaliTest[1250:4060060] multipeer session: reset timer
2016-01-11 15:44:36.074 ThaliTest[1250:4060060] multipeer session: stop timer
,2016-01-11 15:44:36.074 ThaliTest[1250:4060060] multipeer session: start timer: 0x1d3b8bd0
2016-01-11 15:44:36.074 ThaliTest[1250:4060060] server session: connect
,2016-01-11 15:44:36.074 ThaliTest[1250:4060060] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-11 15:44:36.081 ThaliTest[1250:4060060] server: accepting invitation Apple-IpadAir2-1
,2016-01-11 15:44:36.085 ThaliTest[1250:4060900] client session: fireConnectCallback: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:44:36.085 ThaliTest[1250:4060900] jxcore: connect: success
,2016-01-11T14:44:36.085Z SendDataConnector.js: CLIENT connected to 51300, error: null
2016-01-11T14:44:36.087Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:36.090 ThaliTest[1250:4060060] client: relay established
,2016-01-11 15:44:36.091 ThaliTest[1250:4060060] client: new accepted socket: 0x1d3d0090
,2016-01-11T14:44:36.107Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11 15:44:36.266 ThaliTest[1250:4060060] multipeer session: reset timer
,2016-01-11 15:44:36.267 ThaliTest[1250:4060060] multipeer session: stop timer
2016-01-11 15:44:36.267 ThaliTest[1250:4060060] multipeer session: start timer: 0x1d3b8bd0
,2016-01-11 15:44:36.268 ThaliTest[1250:4060060] server session: connect
,2016-01-11 15:44:36.268 ThaliTest[1250:4060060] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-11 15:44:36.275 ThaliTest[1250:4060060] server: accepting invitation Apple-Iphone5s-1
,2016-01-11T14:44:37.522Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-11T14:44:37.536Z SendDataConnector.js: CLIENT is data received : 30000
,2016-01-11T14:44:37.593Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T14:44:37.632Z SendDataConnector.js: CLIENT is data received : 90000
,2016-01-11T14:44:37.657Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:37.658Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T14:44:37.658Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:3,7.658Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 15:44:37.659 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:37.659 ThaliTest[1250:4060190] client session: disconnectFromPeer: Apple-IpadAir2-1.3/8jow==
2016-01-11 15:44:37.66,0 ThaliTest[1250:4060190] client session: disconnect
2016-01-11 15:44:37.660 ThaliTest[1250:4060190] client session: stateChange:2->0 Apple-IpadAir2-1.3/8jow==
,2016-01-11 15:44:37.672 ThaliTest[1250:4060190] jxcore: disconnect: success
2016-01-11T14:44:37.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.3/8jow==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one5s-1./+n+RQ==
2016-01-11T14:44:37.673Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1./+n+RQ==
2016-01-11T14:44:37.673Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1./+n+RQ==
2016-01-11T14:44:37.673Z SendDataConnector.js: do connect now
,2016-01-11 15:44:37.673 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:44:37.679 ThaliTest[1250:4060190] client session: connect
2016-01-11 15:44:37.679 ThaliTest[1250:4060190] client session: stateChange:0->1 Apple-Iphon,e5s-1./+n+RQ==
,2016-01-11 15:44:38.697 ThaliTest[1250:4060899] server session: connected
2016-01-11 15:44:38.698 ThaliTest[1250:4060899] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-11 15:44:38.837 ThaliTest[1250:4060060] server relay: connected (to port: 51294)
,2016-01-11T14:44:38.846Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:39.297Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2016-01-11T14:44:39.313Z SendDataTCPServer.js: TCP/IP server has received 49275 bytes of data
,2016-01-11 15:44:39.319 ThaliTest[1250:4060957] server session: connected
2016-01-11 15:44:39.319 ThaliTest[1250:4060957] server session: stateChange:1->2 Apple-IpadAir2-1
,2016-01-11T14:44:39.348Z SendDataTCPServer.js: TCP/IP server has received 51465 bytes of data
,2016-01-11 15:44:39.371 ThaliTest[1250:4060060] server relay: connected (to port: 51294)
2016-01-11T14:44:39.372Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-11T14:44:39.375Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-11T14:44:39.410Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2016-01-11T14:44:39.424Z SendDataTCPServer.js: TCP/IP server has received 88482 bytes of data
,2016-01-11T14:44:39.436Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:39.551 ThaliTest[1250:4060957] server session: not connected Apple-Iphone5s-1
,2016-01-11T14:44:39.732Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2016-01-11T14:44:39.747Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2016-01-11T14:44:39.761Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2016-01-11T14:44:39.774Z SendDataTCPServer.js: TCP/IP server has received 56443 bytes of data
,2016-01-11T14:44:39.789Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-11T14:44:39.803Z SendDataTCPServer.js: TCP/IP server has received 77532 bytes of data
,2016-01-11T14:44:39.815Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-11T14:44:39.929Z SendDataTCPServer.js: TCP/IP server has received 86505 bytes of data
,2016-01-11T14:44:39.941Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-11 15:44:40.066 ThaliTest[1250:4060957] server session: not connected Apple-IpadAir2-1
,2016-01-11 15:44:40.322 ThaliTest[1250:4060855] client session: connected
2016-01-11 15:44:40.323 ThaliTest[1250:4060855] client session: stateChange:1->2 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:40.333 ThaliTest[1250:4060957] client session: fireConnectCallback: Apple-Iphone5s-1./+n+RQ==
2016-01-11 15:44:40.333 ThaliTest[1250:4060957] jxcore: connect: success
2016-01-11T14:44:40.333Z SendDataConnector.js: CLIENT connected to 513,05, error: null
2016-01-11T14:44:40.334Z SendDataConnector.js: CLIENT starting client 
,2016-01-11 15:44:40.337 ThaliTest[1250:4060060] client: relay established
2016-01-11 15:44:40.337 ThaliTest[1250:4060060] client: new accepted socket: 0x1d4a12a0
,2016-01-11T14:44:40.355Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:41.615Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-11T14:44:41.651Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-11T14:44:41.899Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-11T14:44:41.915Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-11T14:44:41.915Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2016-01-11T14:44:41.916Z SendDataConnector.js: CLIENT Stop now
,2016-01-11T14:44:41.916Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-11 15:44:41.917 ThaliTest[1250:4060190] jxcore: disconnect
,2016-01-11 15:44:41.917 ThaliTest[1250:4060190] client session: disconnectFromPeer: Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:41.918 ThaliTest[1250:4060190] client session: disconnect
,2016-01-11 15:44:41.919 ThaliTest[1250:4060190] client session: stateChange:2->0 Apple-Iphone5s-1./+n+RQ==
,2016-01-11 15:44:42.010 ThaliTest[1250:4060190] jxcore: disconnect: success
,2016-01-11T14:44:42.010Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1./+n+RQ==
,---- round done--------
,startWithNextDevice
,device[4]: Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:42.012Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:42.013Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.wtwmkg==
,2016-01-11T14:44:42.013Z SendDataConnector.js: do connect now
,2016-01-11 15:44:42.014 ThaliTest[1250:4060190] jxcore: connect Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:42.014 ThaliTest[1250:4060190] client session: connect
,2016-01-11 15:44:42.015 ThaliTest[1250:4060190] client session: stateChange:0->1 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:44.528 ThaliTest[1250:4060956] client session: connected
2016-01-11 15:44:44.529 ThaliTest[1250:4060956] client session: stateChange:1->2 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:44.582 ThaliTest[1250:4060899] client session: fireConnectCallback: Apple-Iphone6-1.wtwmkg==
2016-01-11 15:44:44.582 ThaliTest[1250:4060899] jxcore: connect: success
2016-01-11T14:44:44.583Z SendDataConnector.js: CLIENT connected to 5130,8, error: null
2016-01-11T14:44:44.584Z SendDataConnector.js: CLIENT starting client 
2016-01-11 15:44:44.586 ThaliTest[1250:4060060] client: relay established
2016-01-11 15:44:44.587 ThaliTest[1250:4060060] client: new accepted socket: 0x1d4a4dd0
,2016-01-11T14:44:44.597Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-11T14:44:45.658Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-11T14:44:45.767Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-11T14:44:45.880Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-11T14:44:45.894Z SendDataConnector.js: CLIENT is data received : 100000
2016-01-11T14:44:45.894Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2016-01-11T14:44:45.894Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:45.894Z SendDataConnector.js: CLIENT closeClientSocket
2016-01-11 15:44:45.895 ThaliTest[1250:4060190] jxcore: disconnect
2016-01-11 15:44:45.895 ThaliTest[1250:4060190] client session: disconnectFromPeer: Apple-Iphone6-1.wtwmkg==
2016-01-11 15:44:45.895, ThaliTest[1250:4060190] client session: disconnect
2016-01-11 15:44:45.895 ThaliTest[1250:4060190] client session: stateChange:2->0 Apple-Iphone6-1.wtwmkg==
,2016-01-11 15:44:45.910 ThaliTest[1250:4060190] jxcore: disconnect: success
2016-01-11T14:44:45.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.wtwmkg==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
sendReportNow
done, now sending data to server
,2016-01-11T14:44:45.930Z SendDataConnector.js: CLIENT Stop now
2016-01-11T14:44:45.931Z SendDataConnector.js: CLIENT closeClientSocket
,appEnteredForeground wasn't registered
,2016-01-11 15:45:06.269 ThaliTest[1250:4060060] multipeer session: restart
,2016-01-11 15:45:36.269 ThaliTest[1250:4060060] multipeer session: restart
,teardown
LogCallback not set !!!!
testSendData stopped
2016-01-11 15:45:38.490 ThaliTest[1250:4060190] jxcore: stopBroadcasting
2016-01-11 15:45:38.490 ThaliTest[1250:4060190] THEMultipeerSession stopping peer
2016-01-11 15:45:38.491 ThaliTest[1250:4060190] multipeer session: stop timer
2016-01-11 15:45:38.491 ThaliTest[1250:4060190] server session: disconnect
2016-01-11 15:45:38.491 ThaliTest[1250:4060190] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-11 15:45:38.500 ThaliTest[1250:4060190] server session: disconnect
2016-01-11 15:45:38.501 ThaliTest[1250:4060190] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-11 15:45:38.507 ThaliTest[1250:4060190] server session: disconnect
,2016-01-11 15:45:38.507 ThaliTest[1250:4060190] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-11 15:45:38.538 ThaliTest[1250:4060190] jxcore: stopBroadcasting: success
StopBroadcasting went ok
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
