#### Test 50650278bcecc5c_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A14F3F0E-72CB-4ACE-8663-B6A6C92DB9B6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/A14F3F0E-72CB-4ACE-8663-B6A6C92DB9B6/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/14D8C8D4-B550-42E1-B6AD-5CC941C7EEF8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60203"
,(lldb)     command script import "/tmp/A14F3F0E-72CB-4ACE-8663-B6A6C92DB9B6/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 18:49:50.020 ThaliTest[369:436314] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5CE3F672-3B34-47B2-BD8E-E83D5BDF573E/Library/Cookies/Cookies.binarycookies
,2015-12-18 18:49:50.154 ThaliTest[369:436314] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 18:49:50.157 ThaliTest[369:436314] Multi-tasking -> Device: YES, App: YES
,2015-12-18 18:49:50.162 ThaliTest[369:436314] Unlimited access to network resources
,2015-12-18 18:49:50.174 ThaliTest[369:436314] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 18:50:00.752 ThaliTest[369:436314] Resetting plugins due to page load.
,2015-12-18 18:50:04.264 ThaliTest[369:436314] Finished load of: file:///var/mobile/Containers/Bundle/Application/14D8C8D4-B550-42E1-B6AD-5CC941C7EEF8/ThaliTest.app/www/index.html
,2015-12-18 18:50:04.482 ThaliTest[369:436314] JXcore Cordova plugin initializing
,2015-12-18 18:50:04.483 ThaliTest[369:436664] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-18 18:50:06.936 ThaliTest[369:436314] THREAD WARNING: ['JXcore'] took '152.343994' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53138
,2015-12-18 18:56:26.201 ThaliTest[369:436664] jxcore: startBroadcasting
,2015-12-18 18:56:26.215 ThaliTest[369:436664] server: starting Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:26.216 ThaliTest[369:436664] multipeer session: start timer: 0x18c56f20
2015-12-18 18:56:26.217 ThaliTest[369:436664] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4784
2015-12-18 18:56:26.217 ThaliTest[369:436664] jxcore: start,Broadcasting: success
StartBroadcasting started ok
,null
,2015-12-18T17:56:26.220Z SendDataTCPServer.js: TCP/IP server is bound to port: 53138
,2015-12-18 18:56:27.404 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.407Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18T17:56:27.408Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.408Z SendDataConnector.js: do connect now
2015-12-18 18:56:27.408 ThaliTest[369:436664] jxcore: connect Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:27.409 ThaliTest[369:436664] client session: connect
,2015-12-18 18:56:27.409 ThaliTest[369:436664] client session: stateChange:0->1 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:27.532 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:28.819 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:31.474 ThaliTest[369:437691] client session: connected
2015-12-18 18:56:31.474 ThaliTest[369:437691] client session: stateChange:1->2 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:31.525 ThaliTest[369:437689] client session: fireConnectCallback: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:31.525 ThaliTest[369:437689] jxcore: connect: success
2015-12-18T17:56:31.526Z SendDataConnector.js: CLIENT connected to 53141, error: null
,2015-12-18T17:56:31.527Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:31.529 ThaliTest[369:436314] client: relay established
2015-12-18 18:56:31.529 ThaliTest[369:436314] client: new accepted socket: 0x18bf1330
,2015-12-18T17:56:31.544Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:32.191Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:32.191Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:32.193Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:32.193Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:32.195 ThaliTest[369:436664] jxcore: disconnect
2015-12-18 18:56:32.195 ThaliTest[369:436664] client session: disconnectFromPeer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:32.195 ThaliTest[369:436664] client session: disconnect
20,15-12-18 18:56:32.195 ThaliTest[369:436664] client session: stateChange:2->0 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:32.204 ThaliTest[369:436664] jxcore: disconnect: success
2015-12-18T17:56:32.204Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT892.v2mOqA==
---- round done--------
startWithNextDevice
device[2]: Apple-,IpadAir2-1_PT9737.0QrSBA==
2015-12-18T17:56:32.206Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18T17:56:32.206Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18T17:56,:32.206Z SendDataConnector.js: do connect now
,2015-12-18 18:56:32.207 ThaliTest[369:436664] jxcore: connect Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:32.211 ThaliTest[369:436664] client session: connect
2015-12-18 18:56:32.211 ThaliTest[369:436664] client session: stateChange:0->1 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:34.229 ThaliTest[369:436314] multipeer session: reset timer
2015-12-18 18:56:34.230 ThaliTest[369:436314] multipeer session: stop timer
2015-12-18 18:56:34.230 ThaliTest[369:436314] multipeer session: start timer: 0x18c56f20
2015-12-18 ,18:56:34.230 ThaliTest[369:436314] server session: connect
2015-12-18 18:56:34.230 ThaliTest[369:436314] server session: stateChange:0->1 Apple-Iphone5s-1_PT7811
2015-12-18 18:56:34.235 ThaliTest[369:436314] server: accepting invitation Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:35.331 ThaliTest[369:436314] multipeer session: reset timer
2015-12-18 18:56:35.331 ThaliTest[369:436314] multipeer session: stop timer
2015-12-18 18:56:35.331 ThaliTest[369:436314] multipeer session: start timer: 0x18c56f20
2015-12-18 ,18:56:35.331 ThaliTest[369:436314] server session: connect
2015-12-18 18:56:35.332 ThaliTest[369:436314] server session: stateChange:0->1 Apple-Iphone6-1_PT892
,2015-12-18 18:56:35.338 ThaliTest[369:436314] server: accepting invitation Apple-Iphone6-1_PT892
,2015-12-18 18:56:35.505 ThaliTest[369:436314] multipeer session: reset timer
2015-12-18 18:56:35.506 ThaliTest[369:436314] multipeer session: stop timer
2015-12-18 18:56:35.507 ThaliTest[369:436314] multipeer session: start timer: 0x18c56f20
2015-12-18 ,18:56:35.507 ThaliTest[369:436314] server session: connect
2015-12-18 18:56:35.507 ThaliTest[369:436314] server session: stateChange:0->1 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:35.517 ThaliTest[369:436314] server: accepting invitation Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:35.996 ThaliTest[369:437676] client session: connected
2015-12-18 18:56:35.996 ThaliTest[369:437676] client session: stateChange:1->2 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:36.056 ThaliTest[369:437689] client session: fireConnectCallback: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:36.060 ThaliTest[369:437689] jxcore: connect: success
,2015-12-18T17:56:36.061Z SendDataConnector.js: CLIENT connected to 53144, error: null
2015-12-18T17:56:36.062Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:36.065 ThaliTest[369:436314] client: relay established
2015-12-18 18:56:36.066 ThaliTest[369:436314] client: new accepted socket: 0x18b4f070
,2015-12-18T17:56:36.077Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:36.646Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T17:56:36.673Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:36.673Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:36.675Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:36.675Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:36.676 ThaliTest[369:436664] jxcore: disconnect
2015-12-18 18:56:36.676 ThaliTest[369:436664] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:36.677 ThaliTest[369:436664] client session: disconnect
,2015-12-18 18:56:36.677 ThaliTest[369:436664] client session: stateChange:2->0 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:36.685 ThaliTest[369:436664] jxcore: disconnect: success
2015-12-18T17:56:36.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9737.0QrSBA==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5s-1_PT7811.xvr6/w==
2015-12-18T17:56:36.686Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18T17:56:36.687Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18T17:,56:36.687Z SendDataConnector.js: do connect now
2015-12-18 18:56:36.687 ThaliTest[369:436664] jxcore: connect Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:36.687 ThaliTest[369:436664] client session: connect
2015-12-18 18:56:36.688 ThaliTest[369:43,6664] client session: stateChange:0->1 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:37.067 ThaliTest[369:437693] server session: connected
2015-12-18 18:56:37.067 ThaliTest[369:437693] server session: stateChange:1->2 Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:37.072 ThaliTest[369:436314] server relay: connected (to port: 53138)
,2015-12-18T17:56:37.081Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:37.322Z SendDataTCPServer.js: TCP/IP server has received 2048 bytes of data
,2015-12-18T17:56:37.336Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-18T17:56:37.351Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-18T17:56:37.367Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-18T17:56:37.382Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-18T17:56:37.395Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:37.560 ThaliTest[369:437689] server session: not connected Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:38.216 ThaliTest[369:437689] server session: connected
2015-12-18 18:56:38.217 ThaliTest[369:437689] server session: stateChange:1->2 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:38.230 ThaliTest[369:436314] server relay: connected (to port: 53138)
,2015-12-18T17:56:38.237Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18 18:56:38.284 ThaliTest[369:437689] server session: connected
2015-12-18 18:56:38.284 ThaliTest[369:437689] server session: stateChange:1->2 Apple-Iphone6-1_PT892
,2015-12-18 18:56:38.342 ThaliTest[369:436314] server relay: connected (to port: 53138)
,2015-12-18T17:56:38.349Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:38.474Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T17:56:38.490Z SendDataTCPServer.js: TCP/IP server has received 36946 bytes of data
,2015-12-18T17:56:38.507Z SendDataTCPServer.js: TCP/IP server has received 65416 bytes of data
,2015-12-18T17:56:38.522Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-18T17:56:38.537Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:38.638 ThaliTest[369:437692] server session: not connected Apple-IpadAir2-1_PT9737
,2015-12-18T17:56:38.736Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18T17:56:38.751Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-18T17:56:38.770Z SendDataTCPServer.js: TCP/IP server has received 69796 bytes of data
,2015-12-18T17:56:38.787Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:38.846 ThaliTest[369:437676] server session: not connected Apple-Iphone6-1_PT892
,2015-12-18 18:56:39.730 ThaliTest[369:437676] client session: connected
2015-12-18 18:56:39.731 ThaliTest[369:437676] client session: stateChange:1->2 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:39.747 ThaliTest[369:437693] client session: fireConnectCallback: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:39.748 ThaliTest[369:437693] jxcore: connect: success
2015-12-18T17:56:39.748Z SendDataConnector.js: CLIENT connected to 53150, error: null
2015-12-18T17:56:39.749Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:39.751 ThaliTest[369:436314] client: relay established
2015-12-18 18:56:39.751 ThaliTest[369:436314] client: new accepted socket: 0x18b46ec0
,2015-12-18T17:56:39.764Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:40.379Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-18T17:56:40.406Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:40.406Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:40.408Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:40.408Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:40.409 ThaliTest[369:436664] jxcore: disconnect
2015-12-18 18:56:40.410 ThaliTest[369:436664] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:40.410 ThaliTest[369:436664] client session: disconnect
,2015-12-18 18:56:40.410 ThaliTest[369:436664] client session: stateChange:2->0 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:40.418 ThaliTest[369:436664] jxcore: disconnect: success
2015-12-18T17:56:40.418Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7811.xvr6/w==
---- round done--------
startWithNextDevice
,2015-12-18 18:57:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:57:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:57:35.539 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:57:35.539 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:57:35.539 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:58:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:58:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:58:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:58:05.541 ThaliTest[369:436314] client: foun,d peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:58:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:58:35.540 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:58:35.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:58:35.541 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:59:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:59:05.538 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:59:05.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:05.539 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:59:12.772 ThaliTest[369:436314] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:12.772 ThaliTest[369:436314] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 18:59:15.575 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 18:59:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 18:59:35.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:59:35.540 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:59:35.542 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:00:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:00:05.544 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:00:05.700 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:00:06.105 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:00:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:00:35.533 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:00:35.533 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:00:35.535 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,appEnteringBackground wasn't registered
,2015-12-18 19:01:05.507 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:01:05.538 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:01:05.538 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:01:05.539 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:01:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:01:35.539 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:01:35.539 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:01:35.545 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:02:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:02:05.542 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:02:05.543 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:02:05.543 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:02:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:02:35.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:02:35.540 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:02:35.541 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-18 19:03:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:03:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:03:35.537 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:03:35.834 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:03:49.755 ThaliTest[369:436314] client: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:49.755 ThaliTest[369:436314] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,appEnteredForeground wasn't registered
,2015-12-18 19:03:56.246 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:04:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:04:05.537 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:04:05.541 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:04:05.541 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,appEnteringBackground wasn't registered
,2015-12-18 19:04:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:04:35.539 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:04:35.542 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:04:35.542 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,appEnteredForeground wasn't registered
,2015-12-18 19:05:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:05:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:05:05.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:05:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,appEnteringBackground wasn't registered
,2015-12-18 19:05:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:06:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:06:05.537 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:06:05.767 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:06:05.768 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:06:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:07:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:07:05.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:07:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:07:05.541 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:07:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:07:35.540 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:07:35.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:07:35.541 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:08:05.507 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:08:05.537 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:08:05.541 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:08:05.745 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:08:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:09:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:09:05.534 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:09:05.536 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:09:05.538 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:09:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:09:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:09:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:09:35.544 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,appEnteredForeground wasn't registered
,2015-12-18 19:10:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:10:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:10:05.541 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:10:05.545 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,appEnteringBackground wasn't registered
,2015-12-18 19:10:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:10:35.537 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:10:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:10:35.539 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:11:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:11:05.539 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:11:05.540 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:11:05.545 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:11:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:11:35.535 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:11:35.536 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:11:35.536 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:12:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:12:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:12:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:12:35.539 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:12:35.734 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:13:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:13:05.537 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:13:06.113 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:13:06.114 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,timeout now
weAreDoneNow, resultArray.length: 3
sendReportNow
done, now sending data to server
,2015-12-18T18:13:06.241Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:13:35.508 ThaliTest[369:436314] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-18 19:14:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:14:05.536 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:14:06.337 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:14:06.338 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,appEnteringBackground wasn't registered
,2015-12-18 19:14:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:14:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:14:35.538 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:14:35.545 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:15:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:15:05.538 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:15:05.545 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:15:05.545 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:15:35.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:16:05.508 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:16:05.537 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:16:05.543 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:16:05.543 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,teardown
,testSendData stopped
2015-12-18 19:16:26.999 ThaliTest[369:436664] jxcore: stopBroadcasting
2015-12-18 19:16:26.999 ThaliTest[369:436664] THEMultipeerSession stopping peer
2015-12-18 19:16:26.999 ThaliTest[369:436664] multipeer session: stop timer
,2015-12-18 19:16:27.000 ThaliTest[369:436664] server session: disconnect
,2015-12-18 19:16:27.000 ThaliTest[369:436664] server session: stateChange:2->0 Apple-Iphone5s-1_PT7811
2015-12-18 19:16:27.005 ThaliTest[369:436664] server session: disconnect
2015-12-18 19:16:27.005 ThaliTest[369:436664] server session: stateChange:2->0, Apple-Iphone6-1_PT892
2015-12-18 19:16:27.009 ThaliTest[369:436664] server session: disconnect
2015-12-18 19:16:27.009 ThaliTest[369:436664] server session: stateChange:2->0 Apple-IpadAir2-1_PT9737
,2015-12-18 19:16:27.020 ThaliTest[369:436664] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T18:16:27.039Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-18T18:16:27.040Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:16:27.042Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:16:27.043Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 19:16:27.085 ThaliTest[369:436664] jxcore: startBroadcasting
,2015-12-18 19:16:27.092 ThaliTest[369:436664] server: starting Apple-Iphone5-1_PT4784.B3pdeg==
,2015-12-18 19:16:27.095 ThaliTest[369:436664] multipeer session: start timer: 0x18b3ed10
2015-12-18 19:16:27.098 ThaliTest[369:436664] THEMultipeerSession initialized peer Apple-Iphone5-1_PT4784
2015-12-18 19:16:27.098 ThaliTest[369:436664] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 19:16:27.116 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:16:27.117 ThaliTest[369:436314] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:16:27.119 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone5s-1_PT7811.xvr6/w==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-18 19:16:27.408 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:16:28.143 ThaliTest[369:436314] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:28.143 ThaliTest[369:436314] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:16:28.572 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:16:33.433 ThaliTest[369:436314] client: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:16:33.433 ThaliTest[369:436314] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:16:57.115 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:16:57.143 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:16:57.147 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:16:57.219 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:17:27.115 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:17:27.149 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:17:27.153 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:17:27.232 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:17:57.115 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:18:27.115 ThaliTest[369:436314] multipeer session: restart
,2015-12-18 19:18:27.145 ThaliTest[369:436314] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:18:27.145 ThaliTest[369:436314] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:18:27.145 ThaliTest[369:436314] client: found peer: Apple-IpadAir2-1_PT9737.STphng==

```
