#### Test 50650278d76d9c3_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/97EC06CE-A68E-4671-9B14-57B0057F2233/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/97EC06CE-A68E-4671-9B14-57B0057F2233/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A28023D3-578E-44D4-9DC3-D04DDE7BDA8E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60328"
,(lldb)     command script import "/tmp/97EC06CE-A68E-4671-9B14-57B0057F2233/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 19:31:30.246 ThaliTest[400:444969] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/061338BF-156F-4E7A-923E-6122652488BA/Library/Cookies/Cookies.binarycookies
,2015-12-18 19:31:30.391 ThaliTest[400:444969] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 19:31:30.393 ThaliTest[400:444969] Multi-tasking -> Device: YES, App: YES
,2015-12-18 19:31:30.398 ThaliTest[400:444969] Unlimited access to network resources
,2015-12-18 19:31:30.409 ThaliTest[400:444969] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 19:31:40.610 ThaliTest[400:444969] Resetting plugins due to page load.
,2015-12-18 19:31:44.685 ThaliTest[400:444969] Finished load of: file:///var/mobile/Containers/Bundle/Application/A28023D3-578E-44D4-9DC3-D04DDE7BDA8E/ThaliTest.app/www/index.html
,2015-12-18 19:31:44.900 ThaliTest[400:444969] JXcore Cordova plugin initializing
,2015-12-18 19:31:44.901 ThaliTest[400:445165] JXcore instance initializing
Initializing JXcore engine
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
,2015-12-18 19:31:47.375 ThaliTest[400:444969] THREAD WARNING: ['JXcore'] took '155.393066' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 53367
,2015-12-18 19:38:08.860 ThaliTest[400:445165] jxcore: startBroadcasting
,2015-12-18 19:38:08.872 ThaliTest[400:445165] server: starting Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:08.874 ThaliTest[400:445165] multipeer session: start timer: 0x1b3fa3a0
,2015-12-18 19:38:08.875 ThaliTest[400:445165] THEMultipeerSession initialized peer Apple-Iphone5-1_PT3434
,2015-12-18 19:38:08.877 ThaliTest[400:445165] jxcore: startBroadcasting: success
,StartBroadcasting started ok
null
,2015-12-18T18:38:08.887Z SendDataTCPServer.js: TCP/IP server is bound to port: 53367
,2015-12-18 19:38:09.983 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18T18:38:09.988Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18T18:38:09.988Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18T18:38:09.989Z SendDataConnector.js: do connect now
,2015-12-18 19:38:09.990 ThaliTest[400:445165] jxcore: connect Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:09.990 ThaliTest[400:445165] client session: connect
2015-12-18 19:38:09.990 ThaliTest[400:445165] client session: stateChange:0->1 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:10.007 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-18 19:38:10.124 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 19:38:10.254 ThaliTest[400:444969] multipeer session: reset timer
2015-12-18 19:38:10.255 ThaliTest[400:444969] multipeer session: stop timer
2015-12-18 19:38:10.255 ThaliTest[400:444969] multipeer session: start timer: 0x1b3fa3a0
2015-12-18 19:38:10.255 ThaliTest[400:444969] server session: connect
,2015-12-18 19:38:10.255 ThaliTest[400:444969] server session: stateChange:0->1 Apple-Iphone6-1_PT6353
,2015-12-18 19:38:10.262 ThaliTest[400:444969] server: accepting invitation Apple-Iphone6-1_PT6353
,2015-12-18 19:38:10.516 ThaliTest[400:444969] multipeer session: reset timer
2015-12-18 19:38:10.516 ThaliTest[400:444969] multipeer session: stop timer
2015-12-18 19:38:10.517 ThaliTest[400:444969] multipeer session: start timer: 0x1b3fa3a0
2015-12-18 19:38:10.517 ThaliTest[400:444969] server session: connect
2015-12-18 19:38:10.517 ThaliTest[400:444969] server session: stateChange:0->1 Apple-Iphone5s-1_PT9213
2015-12-18 19:38:10.526 ThaliTest[400:444969] server: accepting invitation Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:12.992 ThaliTest[400:445879] client session: connected
2015-12-18 19:38:12.996 ThaliTest[400:445879] client session: stateChange:1->2 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:13.018 ThaliTest[400:445874] client session: fireConnectCallback: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:13.019 ThaliTest[400:445874] jxcore: connect: success
,2015-12-18T18:38:13.021Z SendDataConnector.js: CLIENT connected to 53370, error: null
2015-12-18T18:38:13.021Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:13.025 ThaliTest[400:444969] client: relay established
2015-12-18 19:38:13.025 ThaliTest[400:444969] client: new accepted socket: 0x1b3594c0
,2015-12-18T18:38:13.038Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 19:38:13.066 ThaliTest[400:445917] server session: connected
2015-12-18 19:38:13.066 ThaliTest[400:445917] server session: stateChange:1->2 Apple-Iphone6-1_PT6353
,2015-12-18 19:38:13.091 ThaliTest[400:444969] server relay: connected (to port: 53367)
,2015-12-18 19:38:13.338 ThaliTest[400:445874] server session: connected
2015-12-18 19:38:13.338 ThaliTest[400:445874] server session: stateChange:1->2 Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:13.487 ThaliTest[400:444969] server relay: connected (to port: 53367)
,2015-12-18T18:38:13.619Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:13.622Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:13.642Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:13.785 ThaliTest[400:445874] server session: not connected Apple-Iphone6-1_PT6353
,2015-12-18T18:38:13.844Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18T18:38:13.860Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T18:38:13.861Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:13.862Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:13.862Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:13.863 ThaliTest[400:445165] jxcore: disconnect
2015-12-18 19:38:13.864 ThaliTest[400:445165] client session: disconnectFromPeer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:13.864 ThaliTest[400:445165] client session: disconnect
2015-12-18 19:38:13.864 ThaliTest[400:445165] client session: stateChange:2->0 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:13.873 ThaliTest[400:445165] jxcore: disconnect: success
,2015-12-18T18:38:13.877Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6353.xIoHCA==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:13.879Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:13.880Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18T18:38:13.880Z SendDataConnector.js: do connect now
2015-12-18 19:38:13.880 ThaliTest[400:445165] jxcore: connect Apple-Iphone5s-1_PT9213,.s950ig==
2015-12-18 19:38:13.881 ThaliTest[400:445165] client session: connect
2015-12-18 19:38:13.881 ThaliTest[400:445165] client session: stateChange:0->1 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:14.639Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T18:38:14.652Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-18T18:38:14.717Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-18T18:38:14.770Z SendDataTCPServer.js: TCP/IP server has received 59130 bytes of data
,2015-12-18T18:38:14.785Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:15.686 ThaliTest[400:445879] server session: not connected Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:17.910 ThaliTest[400:445879] client session: connected
2015-12-18 19:38:17.910 ThaliTest[400:445879] client session: stateChange:1->2 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:17.938 ThaliTest[400:445874] client session: fireConnectCallback: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:17.938 ThaliTest[400:445874] jxcore: connect: success
2015-12-18T18:38:17.939Z SendDataConnector.js: CLIENT connected to 53375, error: null
2015-12-18T18:38:17.939Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:17.942 ThaliTest[400:444969] client: relay established
2015-12-18 19:38:17.942 ThaliTest[400:444969] client: new accepted socket: 0x156afc10
,2015-12-18T18:38:17.953Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:18.573Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T18:38:18.588Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T18:38:18.845Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:18.846Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:18.848Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:18.848Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:18.849 ThaliTest[400:445165] jxcore: disconnect
2015-12-18 19:38:18.849 ThaliTest[400:445165] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:18.849 ThaliTest[400:445165] client session: disconnect
,2015-12-18 19:38:18.849 ThaliTest[400:445165] client session: stateChange:2->0 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:18.859 ThaliTest[400:445165] jxcore: disconnect: success
2015-12-18T18:38:18.859Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9213.s950ig==
---- round done--------
startWithNextDevice
device[3]: Appl,e-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:38:18.860Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:38:18.860Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:,38:18.860Z SendDataConnector.js: do connect now
2015-12-18 19:38:18.861 ThaliTest[400:445165] jxcore: connect Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:18.861 ThaliTest[400:445165] client session: connect
,2015-12-18 19:38:18.861 ThaliTest[400:445165] client session: stateChange:0->1 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:19.027 ThaliTest[400:444969] multipeer session: reset timer
2015-12-18 19:38:19.028 ThaliTest[400:444969] multipeer session: stop timer
2015-12-18 19:38:19.028 ThaliTest[400:444969] multipeer session: start timer: 0x1b3fa3a0
2015-12-18 ,19:38:19.028 ThaliTest[400:444969] server session: connect
2015-12-18 19:38:19.029 ThaliTest[400:444969] server session: stateChange:0->1 Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:19.037 ThaliTest[400:444969] server: accepting invitation Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:21.726 ThaliTest[400:445881] server session: connected
2015-12-18 19:38:21.726 ThaliTest[400:445881] server session: stateChange:1->2 Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:21.998 ThaliTest[400:444969] server relay: connected (to port: 53367)
2015-12-18 19:38:21.998 ThaliTest[400:445882] client session: connected
2015-12-18 19:38:21.998 ThaliTest[400:445882] client session: stateChange:1->2 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18T18:38:22.008Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:22.110Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
2015-12-18T18:38:22.125Z SendDataTCPServer.js: TCP/IP server has received 28470 bytes of data
,2015-12-18 19:38:22.120 ThaliTest[400:445879] client session: fireConnectCallback: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:22.135 ThaliTest[400:445879] jxcore: connect: success
,2015-12-18T18:38:22.140Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
2015-12-18T18:38:22.140Z SendDataConnector.js: CLIENT connected to 53379, error: null
2015-12-18T18:38:22.141Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:22.144 ThaliTest[400:444969] client: relay established
2015-12-18 19:38:22.145 ThaliTest[400:444969] client: new accepted socket: 0x1b491940
2015-12-18T18:38:22.157Z SendDataTCPServer.js: TCP/IP server has received 94170 bytes of data
,2015-12-18T18:38:22.162Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:22.655Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:22.778 ThaliTest[400:445879] server session: not connected Apple-IpadAir2-1_PT9191
,2015-12-18T18:38:22.780Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T18:38:23.090Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:23.091Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:23.092Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:23.093Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:23.094 ThaliTest[400:445165] jxcore: disconnect
2015-12-18 19:38:23.094 ThaliTest[400:445165] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:23.095 ThaliTest[400:445165] client session: disconnect
,2015-12-18 19:38:23.095 ThaliTest[400:445165] client session: stateChange:2->0 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:23.104 ThaliTest[400:445165] jxcore: disconnect: success
2015-12-18T18:38:23.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
---- round done--------
startWithNextDevice
,2015-12-18 19:38:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:38:49.255 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:49.256 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:49.256 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:39:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:39:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:39:49.148 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:39:49.148 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:39:49.149 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:40:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:40:20.011 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:40:20.011 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:40:20.640 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:40:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:40:49.358 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:40:49.361 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:40:49.361 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:41:08.581 ThaliTest[400:444969] client: lost peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:41:08.581 ThaliTest[400:444969] client session: onPeerLost: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:41:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:41:19.057 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:41:19.058 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,appEnteredForeground wasn't registered
,2015-12-18 19:41:33.438 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:41:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:41:49.062 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:41:49.062 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:41:49.119 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:42:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:42:19.060 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:42:19.060 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:42:19.162 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,Connected to the server!
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2015-12-18 19:42:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:42:49.062 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:42:49.229 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:42:49.232 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,appEnteringBackground wasn't registered
,2015-12-18 19:43:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:43:19.063 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:19.063 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:43:19.102 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:43:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:43:49.060 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:49.060 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:43:49.487 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:44:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:44:19.059 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:44:19.059 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:44:19.065 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:44:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:45:19.030 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:45:19.057 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:45:19.057 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:45:19.067 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:45:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:45:49.061 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:45:49.061 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:45:49.061 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:46:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:46:19.061 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:46:19.062 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:46:19.526 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:46:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:46:49.060 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:46:49.060 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:46:49.216 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:47:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:47:19.060 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:47:19.061 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:47:19.167 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:47:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:47:49.061 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:47:49.061 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:47:49.063 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteredForeground wasn't registered
,2015-12-18 19:48:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:48:19.063 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:48:19.063 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:48:19.128 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteringBackground wasn't registered
,2015-12-18 19:48:49.030 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:48:49.058 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:48:49.058 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:48:49.315 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:19.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:49:19.061 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:49:19.061 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:49:19.147 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:49.029 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:50:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:50:18.987 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:50:18.989 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:50:18.989 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:50:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:50:48.990 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:50:48.994 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:50:48.994 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:51:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:51:18.990 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:51:18.991 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:51:19.179 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:51:48.959 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:52:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:52:18.989 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:52:19.049 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:52:19.050 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:52:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:52:48.991 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:52:48.994 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:52:48.994 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:53:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:53:18.988 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:53:18.988 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:53:19.215 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:53:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:54:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:54:18.989 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:54:18.991 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:54:18.992 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:54:48.819Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:54:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:54:48.991 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:54:48.991 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:54:48.991 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,appEnteredForeground wasn't registered
,2015-12-18 19:55:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:55:18.993 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:55:18.993 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:55:19.239 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:55:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:55:48.990 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:55:48.991 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:55:48.993 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteringBackground wasn't registered
,2015-12-18 19:56:18.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:56:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:56:48.991 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:56:48.991 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:56:48.991 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteredForeground wasn't registered
,2015-12-18 19:57:18.959 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:57:18.989 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:57:18.990 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:57:19.200 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteringBackground wasn't registered
,2015-12-18 19:57:48.960 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:57:48.990 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:57:48.991 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:57:49.145 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,teardown
,testSendData stopped
,2015-12-18 19:58:09.133 ThaliTest[400:445165] jxcore: stopBroadcasting
2015-12-18 19:58:09.134 ThaliTest[400:445165] THEMultipeerSession stopping peer
2015-12-18 19:58:09.134 ThaliTest[400:445165] multipeer session: stop timer
2015-12-18 19:58:09.134 Th,aliTest[400:445165] server session: disconnect
2015-12-18 19:58:09.134 ThaliTest[400:445165] server session: stateChange:2->0 Apple-IpadAir2-1_PT9191
,2015-12-18 19:58:09.200 ThaliTest[400:445165] server session: disconnect
2015-12-18 19:58:09.201 ThaliTest[400:445165] server session: stateChange:2->0 Apple-Iphone6-1_PT6353
,2015-12-18 19:58:09.204 ThaliTest[400:445165] server session: disconnect
2015-12-18 19:58:09.204 ThaliTest[400:445165] server session: stateChange:2->0 Apple-Iphone5s-1_PT9213
,2015-12-18 19:58:09.210 ThaliTest[400:445165] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-18T18:58:09.226Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:09.228Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:09.229Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:09.229Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 19:58:09.429 ThaliTest[400:445165] jxcore: startBroadcasting
,2015-12-18 19:58:09.431 ThaliTest[400:445165] server: starting Apple-Iphone5-1_PT3434.mAEuiQ==
2015-12-18 19:58:09.432 ThaliTest[400:445165] multipeer session: start timer: 0x1b354b50
2015-12-18 19:58:09.432 ThaliTest[400:445165] THEMultipeerSession initialized peer Apple-Iphone5-1_PT3434
2015-12-18 19:58:09.432 ThaliTest[400:445165] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-18 19:58:10.380 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:58:10.381 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6,-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone6-1_PT6353.xIoHCA==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-18 19:58:11.273 ThaliTest[400:444969] client: lost peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:58:11.273 ThaliTest[400:444969] client session: onPeerLost: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:58:11.275 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
,2015-12-18 19:58:11.280 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:58:39.433 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:58:39.464 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:58:39.464 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
,2015-12-18 19:58:39.469 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:59:09.433 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:59:09.465 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:59:09.465 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:59:10.019 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:59:39.433 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 19:59:39.466 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:59:39.467 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:59:39.468 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 20:00:09.433 ThaliTest[400:444969] multipeer session: restart
,2015-12-18 20:00:09.461 ThaliTest[400:444969] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 20:00:09.754 ThaliTest[400:444969] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 20:00:09.754 ThaliTest[400:444969] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==

```
