#### Test 55431344e5dd625_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1FE43388-33DE-4691-AF88-20F6598A6A03/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/1FE43388-33DE-4691-AF88-20F6598A6A03/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/55431344e5dd625/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2E6EB2BF-5537-4A27-AAD7-468D3542D570/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49814"
,(lldb)     command script import "/tmp/1FE43388-33DE-4691-AF88-20F6598A6A03/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-01-08 08:23:43.696 ThaliTest[1069:3534595] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BE3F718B-8A0C-43ED-A683-E3EB003279ED/Library/Cookies/Cookies.binarycookies
,2016-01-08 08:23:43.815 ThaliTest[1069:3534595] Apache Cordova native platform version 3.9.2 is starting.
,2016-01-08 08:23:43.816 ThaliTest[1069:3534595] Multi-tasking -> Device: YES, App: YES
,2016-01-08 08:23:43.820 ThaliTest[1069:3534595] Unlimited access to network resources
,2016-01-08 08:23:43.833 ThaliTest[1069:3534595] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-01-08 08:23:54.325 ThaliTest[1069:3534595] Resetting plugins due to page load.
,2016-01-08 08:23:58.728 ThaliTest[1069:3534595] Finished load of: file:///var/mobile/Containers/Bundle/Application/2E6EB2BF-5537-4A27-AAD7-468D3542D570/ThaliTest.app/www/index.html
,2016-01-08 08:23:58.936 ThaliTest[1069:3534595] JXcore Cordova plugin initializing
,2016-01-08 08:23:58.938 ThaliTest[1069:3534780] JXcore instance initializing
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
,2016-01-08 08:24:01.691 ThaliTest[1069:3534595] THREAD WARNING: ['JXcore'] took '158.590088' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2016-01-08 08:30:18.704 ThaliTest[1069:3534780] jxcore: startBroadcasting
,2016-01-08 08:30:18.716 ThaliTest[1069:3534780] server: starting Apple-Iphone5-1.8yAUdA==
,2016-01-08 08:30:18.717 ThaliTest[1069:3534780] multipeer session: start timer: 0x1db2f390
2016-01-08 08:30:18.717 ThaliTest[1069:3534780] THEMultipeerSession initialized peer Apple-Iphone5-1
2016-01-08 08:30:18.718 ThaliTest[1069:3534780] jxcore: startB,roadcasting: success
StartBroadcasting started ok
,2016-01-08 08:30:19.822 ThaliTest[1069:3534595] client: found peer: Apple-Iphone6-1.DpDJvQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1.DpDJvQ==, peerAvail,able: true
weAreDoneNow
done, now sending data to server
,2016-01-08 08:30:19.906 ThaliTest[1069:3534595] client: found peer: Apple-IpadAir2-1.SM1CRQ==
,2016-01-08 08:30:20.505 ThaliTest[1069:3534595] client: found peer: Apple-Iphone5s-1.NE8BAA==
,teardown
,testFindPeers stopped
,2016-01-08 08:30:20.770 ThaliTest[1069:3534780] jxcore: stopBroadcasting
2016-01-08 08:30:20.771 ThaliTest[1069:3534780] THEMultipeerSession stopping peer
2016-01-08 08:30:20.771 ThaliTest[1069:3534780] multipeer session: stop timer
2016-01-08 08:30:20.,772 ThaliTest[1069:3534780] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
serverPort is 65215
2016-01-08 08:30:20.793 ThaliTest[1069:3534780] jxcore: startBroadcasting
,2016-01-08 08:30:20.803 ThaliTest[1069:3534780] server: starting Apple-Iphone5-1.kpUZpA==
2016-01-08 08:30:20.804 ThaliTest[1069:3534780] multipeer session: start timer: 0x1dc85450
2016-01-08 08:30:20.804 ThaliTest[1069:3534780] THEMultipeerSession initi,alized peer Apple-Iphone5-1
2016-01-08 08:30:20.804 ThaliTest[1069:3534780] jxcore: startBroadcasting: success
StartBroadcasting started ok
null
,2016-01-08T07:30:20.810Z SendDataTCPServer.js: TCP/IP server is bound to port: 65215
,2016-01-08 08:30:20.849 ThaliTest[1069:3534595] client: found peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:20.849 ThaliTest[1069:3534595] client: found peer: Apple-Iphone5-1.8yAUdA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==,","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
2016-01-08 08:30:20.852 ThaliTest[1069:3534595] client: found peer: Apple-IpadAir2-1.SM1CRQ==
device[1]: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:20,.853 ThaliTest[1069:3534595] client: found peer: Apple-Iphone5s-1.NE8BAA==
2016-01-08T07:30:20.853Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:20.854Z SendDataConnector.js: doConnect called with peer Apple-Ipho,ne6-1.DpDJvQ==
2016-01-08T07:30:20.854Z SendDataConnector.js: do connect now
,2016-01-08 08:30:20.855 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:20.856 ThaliTest[1069:3534780] client session: connect
2016-01-08 08:30:20.856 ThaliTest[1069:3534780] client session: stateChange:0->1 Apple-Iphone,6-1.DpDJvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2016-01-08 08:30:22.037 ThaliTest[1069:3534595] client: lost peer: Apple-Iphone5-1.8yAUdA==
,2016-01-08 08:30:22.038 ThaliTest[1069:3534595] client session: onPeerLost: Apple-Iphone5-1.8yAUdA==
,2016-01-08 08:30:22.038 ThaliTest[1069:3534595] client: lost peer: Apple-IpadAir2-1.SM1CRQ==
2016-01-08 08:30:22.039 ThaliTest[1069:3534595] client session: onPeerLost: Apple-IpadAir2-1.SM1CRQ==
,2016-01-08 08:30:22.039 ThaliTest[1069:3534595] client: lost peer: Apple-Iphone5s-1.NE8BAA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1.8yAUdA==","peerName":"(null)","peerAvailable":false}]
2016-01-08 08:30:22.039 ThaliTest[1069:3534595] client session: onPeerLost: Apple-Iphone5s-1.NE8BAA==
Found peer : (null), Available: false,
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.SM1CRQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.NE8BAA==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2016-01-08 08:30:22.434 ThaliTest[1069:3534595] client: lost peer: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.434 ThaliTest[1069:3534595] client session: onPeerLost: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.434 ThaliTest[1069:3534595] client sessio,n: onLinkFailure: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.435 ThaliTest[1069:3534595] client session: disconnect
2016-01-08 08:30:22.435 ThaliTest[1069:3534595] client session: stateChange:1->0 Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.435 Thali,Test[1069:3534595] client session: fireConnectCallback: Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:22.436 ThaliTest[1069:3534595] jxcore: connect: fail: Peer disconnected
2016-01-08 08:30:22.436 ThaliTest[1069:3534595] client: found peer: Apple-IpadAir2-1,.5QwW9A==
2016-01-08T07:30:22.437Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2016-01-08T07:30:22.438Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2016-01-08T07:30:22.438Z SendDataConnector.js: tryAgain af,e,r: 5000 ms.
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.DpDJvQ==","peerName":"(null)","peerAvailable":false}]
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1.5QwW9A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:22.907 ThaliTest[1069:3534595] client: found peer: Apple-Iphone6-1.O1yvYA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1.O1yvYA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08 08:30:23.083 ThaliTest[1069:3534595] client: found peer: Apple-Iphone5s-1.WrRjQQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1.WrRjQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2016-01-08T07:30:27.448Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:27.449Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.461 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:30:32.462 ThaliTest[1069:3534780] jxcore: disconnect: fail
2016-01-08T07:30:32.462Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:32.463Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:32.463Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:32.463Z SendDataConnector.js: do connect now
2016-01-08 08:30:32.464 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:32.465 ThaliTest[1069:3534780] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:32.465 ThaliTest[1069:3534780] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:32.465Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:32.466Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:32.466Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:37.472Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:37.473Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:42.475 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:30:42.475 ThaliTest[1069:3534780] jxcore: disconnect: fail
2016-01-08T07:30:42.476Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:42.476Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:42.476Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:30:42.477Z SendDataConnector.js: do connect now
,2016-01-08 08:30:42.478 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:42.478 ThaliTest[1069:3534780] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:42.478 ThaliTest[1069:3534780] jxcore: connect,: fail: Peer unreachable
2016-01-08T07:30:42.479Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:42.479Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
2016-01-08T07:30:42.479Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:47.479Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:47.480Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:50.830 ThaliTest[1069:3534595] multipeer session: restart
,2016-01-08 08:30:50.863 ThaliTest[1069:3534595] client: found peer: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:30:50.865 ThaliTest[1069:3534595] client: found peer: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:30:50.866 ThaliTest[1069:3534595] client: found peer,: Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:30:52.481 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:30:52.481 ThaliTest[1069:3534780] jxcore: disconnect: fail
2016-01-08T07:30:52.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
20,16-01-08T07:30:52.482Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:30:52.482Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:52.483Z SendDataConnector.js: do connect now
2016-01-08 08:30:52.484 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:30:52.484 ThaliTest[1069:3534780] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:30:52.485 ThaliTest[1069:3534780] jxcore: connect: fail: Peer unreachable
,2016-01-08T07:30:52.485Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
2016-01-08T07:30:52.485Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2016-01-08T07:30:52.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2016-01-08T07:30:57.493Z SendDataConnector.js: re-try now : Apple-Iphone6-1.DpDJvQ==
,2016-01-08T07:30:57.493Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1.DpDJvQ==
,2016-01-08 08:31:02.426 ThaliTest[1069:3534595] multipeer session: reset timer
2016-01-08 08:31:02.426 ThaliTest[1069:3534595] multipeer session: stop timer
2016-01-08 08:31:02.426 ThaliTest[1069:3534595] multipeer session: start timer: 0x1dc85450
2016-,01-08 08:31:02.426 ThaliTest[1069:3534595] server session: connect
2016-01-08 08:31:02.426 ThaliTest[1069:3534595] server session: stateChange:0->1 Apple-IpadAir2-1
,2016-01-08 08:31:02.433 ThaliTest[1069:3534595] server: accepting invitation Apple-IpadAir2-1
2016-01-08 08:31:02.437 ThaliTest[1069:3534595] multipeer session: reset timer
2016-01-08 08:31:02.437 ThaliTest[1069:3534595] multipeer session: stop timer
20,16-01-08 08:31:02.438 ThaliTest[1069:3534595] multipeer session: start timer: 0x1dc85450
2016-01-08 08:31:02.438 ThaliTest[1069:3534595] server session: connect
2016-01-08 08:31:02.438 ThaliTest[1069:3534595] server session: stateChange:0->1 Apple-Iphone6-1
,2016-01-08 08:31:02.455 ThaliTest[1069:3534595] server: accepting invitation Apple-Iphone6-1
,2016-01-08 08:31:02.505 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:31:02.506 ThaliTest[1069:3534780] jxcore: disconnect: fail
,2016-01-08T07:31:02.507Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:31:02.509Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1.DpDJvQ== with availability status: true
2016-01-08T07:31:02.509Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.DpDJvQ==
2016-01-08T07:31:02.509Z SendDataConnector.js: do connect now
2016-01-08 08:31:02.510 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:31:02.510 ThaliTest[1069:3534780] client: connect: unreachable Apple-Iphone6-1.DpDJvQ==
2016-01-08 08:31:02.510 ThaliTest[1069:3534780] jxcore: connect: fail: Peer unreachable
2016-01-08T07:31:02.511Z SendDataConnector.js: CLIENT connected to 0, error,: Peer unreachable
2016-01-08T07:31:02.511Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
oneRoundDownNow
2016-01-08T07:31:02.512Z SendDataConnector.js: CLIENT Stop now
2016-01-08 08:31:02.512 ThaliTest[1069:3534780] jxcore: disconnec,t
2016-01-08 08:31:02.515 ThaliTest[1069:3534780] jxcore: disconnect: fail
2016-01-08T07:31:02.516Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.DpDJvQ==
---- round done--------
startWithNextDevice
device[2]: Apple-IpadAir2-1.5QwW9A==
2016-01-08T07:31:02.517Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1.5QwW9A==
2016-01-08T07:31:02.517Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1.5QwW9A==
2016-01-08T07:31:02.517Z SendDataConnector.js: do connect now
2016-01-08 08:31:02.518 ThaliTest[1069:3534780] jxcore: connect Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:02.518 ThaliTest[1069:3534780] client session: connect
2016-01-08 08:31:02.523 ThaliTest[1069:3534780] client session: stateChange:0->1 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:03.546 ThaliTest[1069:3534595] multipeer session: reset timer
2016-01-08 08:31:03.546 ThaliTest[1069:3534595] multipeer session: stop timer
2016-01-08 08:31:03.546 ThaliTest[1069:3534595] multipeer session: start timer: 0x1dc85450
2016-,01-08 08:31:03.546 ThaliTest[1069:3534595] server session: connect
2016-01-08 08:31:03.546 ThaliTest[1069:3534595] server session: stateChange:0->1 Apple-Iphone5s-1
,2016-01-08 08:31:03.554 ThaliTest[1069:3534595] server: accepting invitation Apple-Iphone5s-1
,2016-01-08 08:31:05.190 ThaliTest[1069:3535547] server session: connected
2016-01-08 08:31:05.190 ThaliTest[1069:3535547] server session: stateChange:1->2 Apple-Iphone6-1
,2016-01-08 08:31:05.225 ThaliTest[1069:3534595] server relay: connected (to port: 65215)
,2016-01-08T07:31:05.235Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:06.357Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2016-01-08T07:31:06.370Z SendDataTCPServer.js: TCP/IP server has received 20805 bytes of data
,2016-01-08T07:31:06.385Z SendDataTCPServer.js: TCP/IP server has received 29565 bytes of data
,2016-01-08T07:31:06.399Z SendDataTCPServer.js: TCP/IP server has received 40444 bytes of data
,2016-01-08T07:31:06.414Z SendDataTCPServer.js: TCP/IP server has received 53655 bytes of data
,2016-01-08T07:31:06.426Z SendDataTCPServer.js: TCP/IP server has received 62344 bytes of data
,2016-01-08T07:31:06.441Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2016-01-08T07:31:06.615Z SendDataTCPServer.js: TCP/IP server has received 85511 bytes of data
,2016-01-08T07:31:06.630Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08 08:31:06.697 ThaliTest[1069:3535547] server session: connected
2016-01-08 08:31:06.697 ThaliTest[1069:3535547] server session: stateChange:1->2 Apple-IpadAir2-1
2016-01-08 08:31:06.700 ThaliTest[1069:3535517] client session: connected
2016-01,-08 08:31:06.700 ThaliTest[1069:3535517] client session: stateChange:1->2 Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:06.701 ThaliTest[1069:3534595] server relay: connected (to port: 65215)
2016-01-08T07:31:06.709Z SendDataTCPServer.js: TCP/IP server conn,ected
2016-01-08 08:31:06.711 ThaliTest[1069:3535518] client session: fireConnectCallback: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:06.711 ThaliTest[1069:3535518] jxcore: connect: success
2016-01-08T07:31:06.712Z SendDataConnector.js: CLIENT connected, to 65222, error: null
2016-01-08T07:31:06.713Z SendDataConnector.js: CLIENT starting client 
,2016-01-08 08:31:06.718 ThaliTest[1069:3534595] client: relay established
,2016-01-08 08:31:06.718 ThaliTest[1069:3534595] client: new accepted socket: 0x17ecf8a0
,2016-01-08T07:31:06.731Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08 08:31:06.754 ThaliTest[1069:3535519] server session: not connected Apple-Iphone6-1
,2016-01-08 08:31:06.959 ThaliTest[1069:3535519] server session: connected
2016-01-08 08:31:06.959 ThaliTest[1069:3535519] server session: stateChange:1->2 Apple-Iphone5s-1
,2016-01-08 08:31:07.008 ThaliTest[1069:3534595] server relay: connected (to port: 65215)
,2016-01-08T07:31:07.864Z SendDataTCPServer.js: TCP/IP server connected
,2016-01-08T07:31:07.869Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T07:31:07.889Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T07:31:07.907Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
,2016-01-08T07:31:07.917Z SendDataTCPServer.js: TCP/IP server has received 84315 bytes of data
,2016-01-08T07:31:08.004Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2016-01-08T07:31:08.057Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T07:31:08.070Z SendDataTCPServer.js: TCP/IP server has received 88695 bytes of data
,2016-01-08T07:31:08.084Z SendDataTCPServer.js: TCP/IP server has received 95265 bytes of data
,2016-01-08T07:31:08.124Z SendDataConnector.js: CLIENT is data received : 40000
,2016-01-08T07:31:08.137Z SendDataTCPServer.js: TCP/IP server has received 97455 bytes of data
,2016-01-08T07:31:08.202Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T07:31:08.226Z SendDataConnector.js: CLIENT is data received : 60000
,2016-01-08T07:31:08.276Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2016-01-08T07:31:08.539Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08 08:31:08.550 ThaliTest[1069:3535518] server session: not connected Apple-IpadAir2-1
,2016-01-08T07:31:08.563Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T07:31:08.577Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:08.578Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T07:31:08.580Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:08.580Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:08.581 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:31:08.581 ThaliTest[1069:3534780] client session: disconnectFromPeer: Apple-IpadAir2-1.5QwW9A==
2016-01-08 08:31:08.582 ThaliTest[1069:3534780] client session: disconnect
2016-01-08 08:31:08.582 ThaliTest[1069:3534780] client session: stateChange:2->0 Apple-IpadAir2-1.5QwW9A==
,2016-01-08 08:31:08.590 ThaliTest[1069:3534780] jxcore: disconnect: success
2016-01-08T07:31:08.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1.5QwW9A==
---- round done--------
startWithNextDevice
device[3]: Apple-Iph,one6-1.O1yvYA==
2016-01-08T07:31:08.591Z SendDataConnector.js: Start called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.591Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1.O1yvYA==
2016-01-08T07:31:08.592Z SendDataConnector.,js: do connect now
2016-01-08 08:31:08.592 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:08.592 ThaliTest[1069:3534780] client session: connect
2016-01-08 08:31:08.593 ThaliTest[1069:3534780] client session: stateChange:0->1 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:08.645 ThaliTest[1069:3535547] server session: not connected Apple-Iphone5s-1
,2016-01-08 08:31:11.399 ThaliTest[1069:3535517] client session: connected
2016-01-08 08:31:11.400 ThaliTest[1069:3535517] client session: stateChange:1->2 Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:11.402 ThaliTest[1069:3535517] client session: fireConnec,tCallback: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:11.402 ThaliTest[1069:3535517] jxcore: connect: success
,2016-01-08T07:31:11.403Z SendDataConnector.js: CLIENT connected to 65226, error: null
2016-01-08T07:31:11.404Z SendDataConnector.js: CLIENT starting client 
2016-01-08 08:31:11.407 ThaliTest[1069:3534595] client: relay established
2016-01-08 08:31:11.407 ThaliTest[1069:3534595] client: new accepted socket: 0x1dcac9b0
,2016-01-08T07:31:11.419Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:12.640Z SendDataConnector.js: CLIENT is data received : 10000
,2016-01-08T07:31:12.654Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T07:31:12.666Z SendDataConnector.js: CLIENT is data received : 80000
,2016-01-08T07:31:12.853Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:12.853Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T07:31:12.856Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:12.856Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:12.857 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:31:12.857 ThaliTest[1069:3534780] client session: disconnectFromPeer: Apple-Iphone6-1.O1yvYA==
2016-01-08 08:31:12.858 ThaliTest[1069:3534780] client session: disconnect
2016-01-08 08:31:12.858 ThaliTest[1069:3534780] client session: stateChange:2->0 Apple-Iphone6-1.O1yvYA==
,2016-01-08 08:31:12.867 ThaliTest[1069:3534780] jxcore: disconnect: success
2016-01-08T07:31:12.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1.O1yvYA==
---- round done--------
startWithNextDevice
device[4]: Apple-Ipho,ne5s-1.WrRjQQ==
2016-01-08T07:31:12.868Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:12.868Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1.WrRjQQ==
2016-01-08T07:31:12.868Z SendDataConnecto,r.js: do connect now
2016-01-08 08:31:12.869 ThaliTest[1069:3534780] jxcore: connect Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:12.869 ThaliTest[1069:3534780] client session: connect
2016-01-08 08:31:12.869 ThaliTest[1069:3534780] client session: stateC,hange:0->1 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:15.728 ThaliTest[1069:3535518] client session: connected
2016-01-08 08:31:15.728 ThaliTest[1069:3535518] client session: stateChange:1->2 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:15.733 ThaliTest[1069:3535518] client session: fireConnectCallback: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:15.733 ThaliTest[1069:3535518] jxcore: connect: success
2016-01-08T07:31:15.734Z SendDataConnector.js: CLIENT connected to 652,29, error: null
2016-01-08T07:31:15.734Z SendDataConnector.js: CLIENT starting client 
2016-01-08 08:31:15.736 ThaliTest[1069:3534595] client: relay established
2016-01-08 08:31:15.736 ThaliTest[1069:3534595] client: new accepted socket: 0x1dc95c80
,2016-01-08T07:31:15.749Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2016-01-08T07:31:16.816Z SendDataConnector.js: CLIENT is data received : 20000
,2016-01-08T07:31:16.840Z SendDataConnector.js: CLIENT is data received : 50000
,2016-01-08T07:31:16.928Z SendDataConnector.js: CLIENT is data received : 70000
,2016-01-08T07:31:16.942Z SendDataConnector.js: CLIENT is data received : 100000
,2016-01-08T07:31:16.944Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2016-01-08T07:31:16.945Z SendDataConnector.js: CLIENT Stop now
,2016-01-08T07:31:16.945Z SendDataConnector.js: CLIENT closeClientSocket
,2016-01-08 08:31:16.946 ThaliTest[1069:3534780] jxcore: disconnect
2016-01-08 08:31:16.946 ThaliTest[1069:3534780] client session: disconnectFromPeer: Apple-Iphone5s-1.WrRjQQ==
2016-01-08 08:31:16.946 ThaliTest[1069:3534780] client session: disconnect
2016-01-08 08:31:16.947 ThaliTest[1069:3534780] client session: stateChange:2->0 Apple-Iphone5s-1.WrRjQQ==
,2016-01-08 08:31:16.954 ThaliTest[1069:3534780] jxcore: disconnect: success
2016-01-08T07:31:16.954Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1.WrRjQQ==
---- round done--------
startWithNextDevice
weAreDoneNow, result,Array.length: 4
sendReportNow
done, now sending data to server
,2016-01-08T07:31:16.979Z SendDataConnector.js: CLIENT Stop now
2016-01-08T07:31:16.980Z SendDataConnector.js: CLIENT closeClientSocket
,teardown
,testSendData stopped
,2016-01-08 08:31:17.313 ThaliTest[1069:3534780] jxcore: stopBroadcasting
2016-01-08 08:31:17.313 ThaliTest[1069:3534780] THEMultipeerSession stopping peer
2016-01-08 08:31:17.314 ThaliTest[1069:3534780] multipeer session: stop timer
2016-01-08 08:31:17.,314 ThaliTest[1069:3534780] server session: disconnect
2016-01-08 08:31:17.314 ThaliTest[1069:3534780] server session: stateChange:2->0 Apple-Iphone6-1
,2016-01-08 08:31:17.392 ThaliTest[1069:3534780] server session: disconnect
2016-01-08 08:31:17.393 ThaliTest[1069:3534780] server session: stateChange:2->0 Apple-IpadAir2-1
,2016-01-08 08:31:17.454 ThaliTest[1069:3534780] server session: disconnect
2016-01-08 08:31:17.454 ThaliTest[1069:3534780] server session: stateChange:2->0 Apple-Iphone5s-1
,2016-01-08 08:31:17.458 ThaliTest[1069:3534780] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2016-01-08T07:31:17.474Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.476Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.477Z SendDataTCPServer.js: TCP/IP server is ended
,2016-01-08T07:31:17.478Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
