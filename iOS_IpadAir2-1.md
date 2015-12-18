#### Test 506502781a07ac8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0B39E882-9294-491F-90F8-33288240A54B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0B39E882-9294-491F-90F8-33288240A54B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781a07ac8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E8B6BA0-297A-4C1F-950E-9E0AEE341F92/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59782"
,(lldb)     command script import "/tmp/0B39E882-9294-491F-90F8-33288240A54B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 12:24:33.585 ThaliTest[407:345145] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FE83805B-423D-45D8-BE64-4AD737173DCC/Library/Cookies/Cookies.binarycookies
,2015-12-18 12:24:33.967 ThaliTest[407:345145] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 12:24:33.968 ThaliTest[407:345145] Multi-tasking -> Device: YES, App: YES
,2015-12-18 12:24:33.977 ThaliTest[407:345145] Unlimited access to network resources
,2015-12-18 12:24:33.986 ThaliTest[407:345145] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 12:24:43.075 ThaliTest[407:345145] Resetting plugins due to page load.
,2015-12-18 12:24:46.827 ThaliTest[407:345145] Finished load of: file:///var/mobile/Containers/Bundle/Application/4E8B6BA0-297A-4C1F-950E-9E0AEE341F92/ThaliTest.app/www/index.html
,2015-12-18 12:24:46.988 ThaliTest[407:345145] JXcore Cordova plugin initializing
2015-12-18 12:24:46.988 ThaliTest[407:345408] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-18 12:24:47.989 ThaliTest[407:345145] THREAD WARNING: ['JXcore'] took '70.521973' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 12:31:19.997 ThaliTest[407:345408] jxcore: startBroadcasting
,2015-12-18 12:31:20.014 ThaliTest[407:345408] server: starting Apple-IpadAir2-1_PT6115.H3bAHA==
,2015-12-18 12:31:20.015 ThaliTest[407:345408] multipeer session: start timer: 0x19d84e80
,2015-12-18 12:31:20.016 ThaliTest[407:345408] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6115
2015-12-18 12:31:20.017 ThaliTest[407:345408] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 12:31:20.518 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT5479.4UkRdw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5-1_PT5479.4UkRdw==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-18 12:31:20.971 ThaliTest[407:345145] client: found peer: Apple-Iphone6-1_PT3077.XaIcQQ==
,2015-12-18 12:31:22.017 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT6300.vmgLvQ==
,teardown
,testFindPeers stopped
,2015-12-18 12:31:23.244 ThaliTest[407:345408] jxcore: stopBroadcasting
,2015-12-18 12:31:23.244 ThaliTest[407:345408] THEMultipeerSession stopping peer
2015-12-18 12:31:23.245 ThaliTest[407:345408] multipeer session: stop timer
2015-12-18 12:31:23.246 ThaliTest[407:345408] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 52055
,2015-12-18 12:31:23.308 ThaliTest[407:345408] jxcore: startBroadcasting
,2015-12-18 12:31:23.311 ThaliTest[407:345408] server: starting Apple-IpadAir2-1_PT6115.GXbC4w==
,2015-12-18 12:31:23.312 ThaliTest[407:345408] multipeer session: start timer: 0x17fbcee0
2015-12-18 12:31:23.313 ThaliTest[407:345408] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT6115
,2015-12-18 12:31:23.313 ThaliTest[407:345408] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-18T11:31:23.318Z SendDataTCPServer.js: TCP/IP server is bound to port: 52055
,2015-12-18 12:31:23.328 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:23.329 ThaliTest[407:345145] client: found peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:23.329 ThaliTest[407:345145] client: found peer: Apple-IpadAir2-1_PT6115.H3bAHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.vmgLvQ==","peerName":"(null)","peerAvailable":true}]
2015-12-18 12:31:23.330 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT5479.4UkRdw==
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:23.332Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:23.333Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18T11:31:23.333Z SendDataConnector.js: do connect now
,2015-12-18 12:31:23.334 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:23.334 ThaliTest[407:345408] client session: connect
,2015-12-18 12:31:23.334 ThaliTest[407:345408] client session: stateChange:0->1 Apple-Iphone5-1_PT6300.vmgLvQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 12:31:23.378 ThaliTest[407:345145] client: lost peer: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-18 12:31:23.378 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone5-1_PT5479.4UkRdw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-18 12:31:23.700 ThaliTest[407:345145] client: found peer: Apple-Iphone5s-1_PT8285.POBncQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 12:31:24.464 ThaliTest[407:345145] client: lost peer: Apple-IpadAir2-1_PT6115.H3bAHA==
2015-12-18 12:31:24.465 ThaliTest[407:345145] client session: onPeerLost: Apple-IpadAir2-1_PT6115.H3bAHA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6115.H3bAHA==","peerName":"(null)","peerAvailable":false}]
,Found peer : (null), Available: false
,2015-12-18 12:31:24.615 ThaliTest[407:345145] client: lost peer: Apple-Iphone6-1_PT3077.XaIcQQ==
2015-12-18 12:31:24.615 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone6-1_PT3077.XaIcQQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.XaIcQQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,2015-12-18 12:31:24.758 ThaliTest[407:345145] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:31:24.759 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-,1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 12:31:25.857 ThaliTest[407:345145] client: lost peer: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.857 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.858 ThaliTest[407:345145] clien,t session: onLinkFailure: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.858 ThaliTest[407:345145] client session: disconnect
2015-12-18 12:31:25.858 ThaliTest[407:345145] client session: stateChange:1->0 Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:25.859 ThaliTest[407:345145] client session: fireConnectCallback: Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:25.859 ThaliTest[407:345145] jxcore: connect: fail: Peer disconnected
,2015-12-18T11:31:25.861Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-18T11:31:25.862Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-18T11:31:25.863Z SendDataConnector.js: tryAgain afer: 5000 ms.
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.vmgLvQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-18T11:31:30.865Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:30.866Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:30.939 ThaliTest[407:345145] client: lost peer: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.939 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone5s-1_PT8285.POBncQ==
2015-12-18 12:31:30.939 ThaliTest[407:345145] client: found peer: Apple-Iphone5s-1_PT8285.14R9MQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.POBncQ==","peerName":"(null)","peerAvailable":false}]
Found peer : (null), Available: false
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT8285.14R9MQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 12:31:35.875 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:31:35.876 ThaliTest[407:345408] jxcore: disconnect: fail
,2015-12-18T11:31:35.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:35.878Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
,2015-12-18T11:31:35.878Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:35.880Z SendDataConnector.js: do connect now
,2015-12-18 12:31:35.881 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:35.881 ThaliTest[407:345408] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:35.882 ThaliTest[407:345408] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:31:35.883Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T11:31:35.883Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T11:31:35.884Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:40.885Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18T11:31:40.885Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:45.889 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:31:45.890 ThaliTest[407:345408] jxcore: disconnect: fail
,2015-12-18T11:31:45.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18T11:31:45.891Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
,2015-12-18T11:31:45.892Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:45.892Z SendDataConnector.js: do connect now
,2015-12-18 12:31:45.893 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:45.893 ThaliTest[407:345408] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:45.894 ThaliTest[407:345408] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:31:45.895Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T11:31:45.896Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T11:31:45.896Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:31:50.904Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:50.905Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:31:53.314 ThaliTest[407:345145] multipeer session: restart
,2015-12-18 12:31:53.356 ThaliTest[407:345145] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:31:53.356 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:31:53.356 ThaliTest[407:345145] client: foun,d peer: Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:31:55.910 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:31:55.910 ThaliTest[407:345408] jxcore: disconnect: fail
,2015-12-18T11:31:55.911Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18T11:31:55.912Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
,2015-12-18T11:31:55.913Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:31:55.913Z SendDataConnector.js: do connect now
,2015-12-18 12:31:55.914 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:55.915 ThaliTest[407:345408] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
2015-12-18 12:31:55.915 ThaliTest[407:345408] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:31:55.916Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T11:31:55.916Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,2015-12-18T11:31:55.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-18T11:32:00.929Z SendDataConnector.js: re-try now : Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:32:00.930Z SendDataConnector.js: ReStart called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.938 ThaliTest[407:345408] jxcore: disconnect
2015-12-18 12:32:05.939 ThaliTest[407:345408] jxcore: disconnect: fail
,2015-12-18T11:32:05.939Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:32:05.940Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone5-1_PT6300.vmgLvQ== with availability status: true
,2015-12-18T11:32:05.941Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18T11:32:05.941Z SendDataConnector.js: do connect now
,2015-12-18 12:32:05.942 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.943 ThaliTest[407:345408] client: connect: unreachable Apple-Iphone5-1_PT6300.vmgLvQ==
,2015-12-18 12:32:05.943 ThaliTest[407:345408] jxcore: connect: fail: Peer unreachable
,2015-12-18T11:32:05.944Z SendDataConnector.js: CLIENT connected to 0, error: Peer unreachable
,2015-12-18T11:32:05.945Z SendDataConnector.js: CLIENT Can not Connect: Peer unreachable
,oneRoundDownNow
,2015-12-18T11:32:05.947Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 12:32:05.948 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:32:05.949 ThaliTest[407:345408] jxcore: disconnect: fail
,2015-12-18T11:32:05.950Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.vmgLvQ==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:05.953Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:05.954Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18T11:32:05.954Z SendDataConnector.js: do connect now
,2015-12-18 12:32:05.955 ThaliTest[407:345408] jxcore: connect Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:05.956 ThaliTest[407:345408] client session: connect
,2015-12-18 12:32:05.956 ThaliTest[407:345408] client session: stateChange:0->1 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:08.878 ThaliTest[407:346206] client session: connected
,2015-12-18 12:32:08.878 ThaliTest[407:346206] client session: stateChange:1->2 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:08.907 ThaliTest[407:346206] client session: fireConnectCallback: Apple-Iphone6-1_PT3077.TwkGOQ==
2015-12-18 12:32:08.908 ThaliTest[407:346206] jxcore: connect: success
,2015-12-18T11:32:08.909Z SendDataConnector.js: CLIENT connected to 52060, error: null
,2015-12-18T11:32:08.910Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:08.913 ThaliTest[407:345145] client: relay established
2015-12-18 12:32:08.913 ThaliTest[407:345145] client: new accepted socket: 0x19d8e980
,2015-12-18T11:32:08.929Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:09.210Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T11:32:09.223Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T11:32:09.248Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T11:32:09.261Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:09.261Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-18T11:32:09.261Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:09.261Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:09.262 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:32:09.262 ThaliTest[407:345408] client session: disconnectFromPeer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:09.263 ThaliTest[407:345408] client session: disconnect
,2015-12-18 12:32:09.263 ThaliTest[407:345408] client session: stateChange:2->0 Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:09.266 ThaliTest[407:345408] jxcore: disconnect: success
2015-12-18T11:32:09.266Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3077.TwkGOQ==
,---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:09.267Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:09.267Z SendDataConnector.js: doConnect called, with peer Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18T11:32:09.267Z SendDataConnector.js: do connect now
,2015-12-18 12:32:09.267 ThaliTest[407:345408] jxcore: connect Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:09.268 ThaliTest[407:345408] client session: connect
2015-12-18 12:32:09.268 ThaliTest[407:345408] client session: stateChange:0->1 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:11.565 ThaliTest[407:345145] multipeer session: reset timer
2015-12-18 12:32:11.566 ThaliTest[407:345145] multipeer session: stop timer
2015-12-18 12:32:11.566 ThaliTest[407:345145] multipeer session: start timer: 0x17fbcee0
2015-12-18 12:32:11.567 ThaliTest[407:345145] server session: connect
,2015-12-18 12:32:11.567 ThaliTest[407:345145] server session: stateChange:0->1 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:11.574 ThaliTest[407:345145] server: accepting invitation Apple-Iphone5-1_PT6300
,2015-12-18 12:32:12.088 ThaliTest[407:346206] client session: connected
2015-12-18 12:32:12.088 ThaliTest[407:346206] client session: stateChange:1->2 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:12.119 ThaliTest[407:346206] client session: fireConnectCallback: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:12.119 ThaliTest[407:346206] jxcore: connect: success
,2015-12-18T11:32:12.119Z SendDataConnector.js: CLIENT connected to 52063, error: null
,2015-12-18T11:32:12.120Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:12.120 ThaliTest[407:345145] client: relay established
2015-12-18 12:32:12.120 ThaliTest[407:345145] client: new accepted socket: 0x19e67b10
,2015-12-18T11:32:12.133Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:12.408Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T11:32:12.419Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:12.419Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-18T11:32:12.420Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T11:32:12.420Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:12.420 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:32:12.421 ThaliTest[407:345408] client session: disconnectFromPeer: Apple-Iphone5-1_PT6300.t11aeg==
2015-12-18 12:32:12.421 ThaliTest[407:345408] client session: disconnect
2015-12-18 12:32:12.421 ThaliTest[407:345408] client session: state,Change:2->0 Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:12.424 ThaliTest[407:345408] jxcore: disconnect: success
2015-12-18T11:32:12.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6300.t11aeg==
---- round done--------
startWithNextDevice
,device[4]: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18T11:32:12.425Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18T11:32:12.425Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18T11:32:12.425Z SendDataConnector.js: do connect now
2015-12-18 12:32:12.425 ThaliTest[407:345408] jxcore: connect Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:12.425 ThaliTest[407:345408] client session: connect
2015-12-18 12:32:12.425 ThaliTest[407:345408] client session: stateChange:0->1 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:14.390 ThaliTest[407:346199] server session: connected
,2015-12-18 12:32:14.391 ThaliTest[407:346199] server session: stateChange:1->2 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:14.411 ThaliTest[407:345145] server relay: connected (to port: 52055)
,2015-12-18T11:32:14.417Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:14.965Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T11:32:14.982Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-18T11:32:14.998Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-18T11:32:15.025Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-18T11:32:15.041Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:15.094 ThaliTest[407:346216] server session: not connected Apple-Iphone5-1_PT6300
,2015-12-18 12:32:15.555 ThaliTest[407:346216] client session: connected
,2015-12-18 12:32:15.555 ThaliTest[407:346216] client session: stateChange:1->2 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:15.618 ThaliTest[407:346216] client session: fireConnectCallback: Apple-Iphone5s-1_PT8285.14R9MQ==
2015-12-18 12:32:15.618 ThaliTest[407:346216] jxcore: connect: success
,2015-12-18T11:32:15.620Z SendDataConnector.js: CLIENT connected to 52067, error: null
,2015-12-18T11:32:15.621Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 12:32:15.623 ThaliTest[407:345145] client: relay established
2015-12-18 12:32:15.624 ThaliTest[407:345145] client: new accepted socket: 0x19d9f1b0
,2015-12-18T11:32:15.637Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T11:32:16.068Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T11:32:16.068Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
2015-12-18T11:32:16.069Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:16.069Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:16.069 ThaliTest[407:345408] jxcore: disconnect
,2015-12-18 12:32:16.069 ThaliTest[407:345408] client session: disconnectFromPeer: Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:16.069 ThaliTest[407:345408] client session: disconnect
,2015-12-18 12:32:16.070 ThaliTest[407:345408] client session: stateChange:2->0 Apple-Iphone5s-1_PT8285.14R9MQ==
,2015-12-18 12:32:16.073 ThaliTest[407:345408] jxcore: disconnect: success
2015-12-18T11:32:16.073Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT8285.14R9MQ==
---- round done--------
startWithNextDevice
weAreDoneNow, resultArray.length: 4
,sendReportNow
done, now sending data to server
,2015-12-18T11:32:16.076Z SendDataConnector.js: CLIENT Stop now
2015-12-18T11:32:16.076Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 12:32:19.159 ThaliTest[407:345145] multipeer session: reset timer
2015-12-18 12:32:19.159 ThaliTest[407:345145] multipeer session: stop timer
,2015-12-18 12:32:19.160 ThaliTest[407:345145] multipeer session: start timer: 0x17fbcee0
,2015-12-18 12:32:19.160 ThaliTest[407:345145] server session: connect
,2015-12-18 12:32:19.161 ThaliTest[407:345145] server session: stateChange:0->1 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:19.167 ThaliTest[407:345145] server: accepting invitation Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:22.110 ThaliTest[407:346199] server session: connected
2015-12-18 12:32:22.110 ThaliTest[407:346199] server session: stateChange:1->2 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:22.153 ThaliTest[407:345145] server relay: connected (to port: 52055)
,2015-12-18T11:32:22.158Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:22.432Z SendDataTCPServer.js: TCP/IP server has received 17378 bytes of data
,2015-12-18T11:32:22.452Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-18T11:32:22.470Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-18T11:32:22.495Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-18T11:32:22.510Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:22.553 ThaliTest[407:346216] server session: not connected Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:39.075 ThaliTest[407:345145] client: lost peer: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:39.076 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone6-1_PT3077.TwkGOQ==
,2015-12-18 12:32:39.076 ThaliTest[407:345145] client: lost peer: Apple-Iphone5-1_PT6300.t11aeg==
,2015-12-18 12:32:39.076 ThaliTest[407:345145] client session: onPeerLost: Apple-Iphone5-1_PT6300.t11aeg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-18 12:32:44.511 ThaliTest[407:345145] client: found peer: Apple-Iphone5-1_PT6300.t11aeg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6300.t11aeg==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 12:32:46.484 ThaliTest[407:345145] multipeer session: reset timer
2015-12-18 12:32:46.485 ThaliTest[407:345145] multipeer session: stop timer
,2015-12-18 12:32:46.485 ThaliTest[407:345145] multipeer session: start timer: 0x17fbcee0
,2015-12-18 12:32:46.486 ThaliTest[407:345145] server session: connect
,2015-12-18 12:32:46.486 ThaliTest[407:345145] server session: stateChange:0->1 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:46.493 ThaliTest[407:345145] server: accepting invitation Apple-Iphone6-1_PT3077
,2015-12-18 12:32:47.873 ThaliTest[407:345145] client: found peer: Apple-Iphone6-1_PT3077.TwkGOQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3077.TwkGOQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 12:32:49.397 ThaliTest[407:346316] server session: connected
,2015-12-18 12:32:49.397 ThaliTest[407:346316] server session: stateChange:1->2 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:49.416 ThaliTest[407:345145] server relay: connected (to port: 52055)
,2015-12-18T11:32:49.422Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T11:32:49.696Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T11:32:49.709Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-18T11:32:49.737Z SendDataTCPServer.js: TCP/IP server has received 32282 bytes of data
,2015-12-18T11:32:49.752Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 12:32:49.789 ThaliTest[407:346322] server session: not connected Apple-Iphone6-1_PT3077
,teardown
,testSendData stopped
,2015-12-18 12:32:57.072 ThaliTest[407:345408] jxcore: stopBroadcasting
,2015-12-18 12:32:57.073 ThaliTest[407:345408] THEMultipeerSession stopping peer
2015-12-18 12:32:57.073 ThaliTest[407:345408] multipeer session: stop timer
,2015-12-18 12:32:57.074 ThaliTest[407:345408] server session: disconnect
2015-12-18 12:32:57.076 ThaliTest[407:345408] server session: stateChange:2->0 Apple-Iphone6-1_PT3077
,2015-12-18 12:32:57.084 ThaliTest[407:345408] server session: disconnect
2015-12-18 12:32:57.084 ThaliTest[407:345408] server session: stateChange:2->0 Apple-Iphone5-1_PT6300
,2015-12-18 12:32:57.156 ThaliTest[407:345408] server session: disconnect
,2015-12-18 12:32:57.157 ThaliTest[407:345408] server session: stateChange:2->0 Apple-Iphone5s-1_PT8285
,2015-12-18 12:32:57.220 ThaliTest[407:345408] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T11:32:57.238Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.240Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.241Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T11:32:57.242Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
