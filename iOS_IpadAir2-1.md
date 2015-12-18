#### Test 50650278d76d9c3_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F570682A-3F76-4DC9-9E9B-ABCBB5B24EAF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F570682A-3F76-4DC9-9E9B-ABCBB5B24EAF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8767C3B6-04A8-4043-8397-4902E948947A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60360"
,(lldb)     command script import "/tmp/F570682A-3F76-4DC9-9E9B-ABCBB5B24EAF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 19:32:49.102 ThaliTest[474:393203] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6FA9EF12-36D3-48FB-AC92-CB408412FE3E/Library/Cookies/Cookies.binarycookies
,2015-12-18 19:32:49.418 ThaliTest[474:393203] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 19:32:49.419 ThaliTest[474:393203] Multi-tasking -> Device: YES, App: YES
,2015-12-18 19:32:49.427 ThaliTest[474:393203] Unlimited access to network resources
,2015-12-18 19:32:49.433 ThaliTest[474:393203] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 19:32:58.283 ThaliTest[474:393203] Resetting plugins due to page load.
,2015-12-18 19:33:01.799 ThaliTest[474:393203] Finished load of: file:///var/mobile/Containers/Bundle/Application/8767C3B6-04A8-4043-8397-4902E948947A/ThaliTest.app/www/index.html
,2015-12-18 19:33:01.930 ThaliTest[474:393203] JXcore Cordova plugin initializing
,2015-12-18 19:33:01.931 ThaliTest[474:393429] JXcore instance initializing
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
,2015-12-18 19:33:02.933 ThaliTest[474:393203] THREAD WARNING: ['JXcore'] took '70.020020' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 52904
,2015-12-18 19:38:09.441 ThaliTest[474:393429] jxcore: startBroadcasting
,2015-12-18 19:38:09.458 ThaliTest[474:393429] server: starting Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:09.460 ThaliTest[474:393429] multipeer session: start timer: 0x17782e40
,2015-12-18 19:38:09.460 ThaliTest[474:393429] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:09.462 ThaliTest[474:393429] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-18T18:38:09.470Z SendDataTCPServer.js: TCP/IP server is bound to port: 52904
,2015-12-18 19:38:11.145 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:11.145 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:11.146 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:11.151Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:11.153Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18T18:38:11.153Z SendDataConnector.js: do connect now
,2015-12-18 19:38:11.154 ThaliTest[474:393429] jxcore: connect Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:11.155 ThaliTest[474:393429] client session: connect
,2015-12-18 19:38:11.156 ThaliTest[474:393429] client session: stateChange:0->1 Apple-Iphone5s-1_PT9213.s950ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 19:38:14.463 ThaliTest[474:393203] multipeer session: reset timer
2015-12-18 19:38:14.464 ThaliTest[474:393203] multipeer session: stop timer
2015-12-18 19:38:14.464 ThaliTest[474:393203] multipeer session: start timer: 0x17782e40
2015-12-18 19:38:14.464 ThaliTest[474:393203] server session: connect
2015-12-18 19:38:14.465 ThaliTest[474:393203] server session: stateChange:0->1 Apple-Iphone6-1_PT6353
,2015-12-18 19:38:14.471 ThaliTest[474:393203] server: accepting invitation Apple-Iphone6-1_PT6353
,2015-12-18 19:38:14.791 ThaliTest[474:393898] client session: connected
2015-12-18 19:38:14.791 ThaliTest[474:393898] client session: stateChange:1->2 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:14.798 ThaliTest[474:393900] client session: fireConnectCallback: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:14.799 ThaliTest[474:393900] jxcore: connect: success
,2015-12-18T18:38:14.801Z SendDataConnector.js: CLIENT connected to 52907, error: null
,2015-12-18T18:38:14.801Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:14.804 ThaliTest[474:393203] client: relay established
2015-12-18 19:38:14.804 ThaliTest[474:393203] client: new accepted socket: 0x17600c50
,2015-12-18T18:38:14.822Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:15.389Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T18:38:15.389Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:15.390Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:15.390Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:15.391 ThaliTest[474:393429] jxcore: disconnect
,2015-12-18 19:38:15.391 ThaliTest[474:393429] client session: disconnectFromPeer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:15.391 ThaliTest[474:393429] client session: disconnect
,2015-12-18 19:38:15.391 ThaliTest[474:393429] client session: stateChange:2->0 Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:15.396 ThaliTest[474:393429] jxcore: disconnect: success
2015-12-18T18:38:15.397Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT9213.s950ig==
,---- round done--------
startWithNextDevice
device[2]: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18T18:38:15.398Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18T18:38:15.398Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18T18:38:15.398Z SendDataConnector.js: do connect now
2015-12-18 19:38:15.398 ThaliTest[474:393429] jxcore: connect Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:15.399 ThaliTest[474:393429] client session: connect
2015-12-18 19:38:15.399 ThaliTest[474:393429] client session: stateChange:0->1 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:17.024 ThaliTest[474:393900] server session: connected
2015-12-18 19:38:17.024 ThaliTest[474:393900] server session: stateChange:1->2 Apple-Iphone6-1_PT6353
,2015-12-18 19:38:17.032 ThaliTest[474:393203] server relay: connected (to port: 52904)
,2015-12-18T18:38:17.039Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:17.304Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-18T18:38:17.345Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-18T18:38:17.362Z SendDataTCPServer.js: TCP/IP server has received 41468 bytes of data
,2015-12-18T18:38:17.380Z SendDataTCPServer.js: TCP/IP server has received 74460 bytes of data
,2015-12-18T18:38:17.396Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:17.428 ThaliTest[474:393898] server session: not connected Apple-Iphone6-1_PT6353
,2015-12-18 19:38:18.433 ThaliTest[474:393898] client session: connected
,2015-12-18 19:38:18.433 ThaliTest[474:393898] client session: stateChange:1->2 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:18.454 ThaliTest[474:393900] client session: fireConnectCallback: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:18.455 ThaliTest[474:393900] jxcore: connect: success
,2015-12-18T18:38:18.456Z SendDataConnector.js: CLIENT connected to 52911, error: null
,2015-12-18T18:38:18.456Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:18.460 ThaliTest[474:393203] client: relay established
2015-12-18 19:38:18.460 ThaliTest[474:393203] client: new accepted socket: 0x19492c30
,2015-12-18T18:38:18.473Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:18.881Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T18:38:18.919Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T18:38:18.932Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T18:38:18.945Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:18.945Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T18:38:18.946Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:18.946Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:18.946 ThaliTest[474:393429] jxcore: disconnect
,2015-12-18 19:38:18.946 ThaliTest[474:393429] client session: disconnectFromPeer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:18.947 ThaliTest[474:393429] client session: disconnect
,2015-12-18 19:38:18.947 ThaliTest[474:393429] client session: stateChange:2->0 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:18.949 ThaliTest[474:393429] jxcore: disconnect: success
2015-12-18T18:38:18.950Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6353.xIoHCA==
,---- round done--------
startWithNextDevice
,device[3]: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18T18:38:18.951Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:18.951Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:18.951Z SendDataConnector.js: do connect now
2015-12-18 19:38:18.951 ThaliTest[474:393429] jxcore: connect Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:18.951 ThaliTest[474:393429] client session: connect
2015-12-18 19:38:18.951 ThaliTest[474:393429] client session: stateChange:0->1 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:19.606 ThaliTest[474:393203] multipeer session: reset timer
2015-12-18 19:38:19.606 ThaliTest[474:393203] multipeer session: stop timer
2015-12-18 19:38:19.607 ThaliTest[474:393203] multipeer session: start timer: 0x17782e40
2015-12-18 19:38:19.607 ThaliTest[474:393203] server session: connect
,2015-12-18 19:38:19.607 ThaliTest[474:393203] server session: stateChange:0->1 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:19.613 ThaliTest[474:393203] server: accepting invitation Apple-Iphone5-1_PT3434
,2015-12-18 19:38:20.160 ThaliTest[474:393203] multipeer session: reset timer
2015-12-18 19:38:20.160 ThaliTest[474:393203] multipeer session: stop timer
2015-12-18 19:38:20.160 ThaliTest[474:393203] multipeer session: start timer: 0x17782e40
2015-12-18 ,19:38:20.161 ThaliTest[474:393203] server session: connect
2015-12-18 19:38:20.161 ThaliTest[474:393203] server session: stateChange:0->1 Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:20.165 ThaliTest[474:393203] server: accepting invitation Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:22.291 ThaliTest[474:393898] client session: connected
,2015-12-18 19:38:22.292 ThaliTest[474:393898] client session: stateChange:1->2 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:22.296 ThaliTest[474:393898] client session: fireConnectCallback: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:22.296 ThaliTest[474:393898] jxcore: connect: success
,2015-12-18T18:38:22.298Z SendDataConnector.js: CLIENT connected to 52914, error: null
,2015-12-18T18:38:22.298Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:22.301 ThaliTest[474:393203] client: relay established
2015-12-18 19:38:22.301 ThaliTest[474:393203] client: new accepted socket: 0x194978b0
,2015-12-18T18:38:22.313Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 19:38:22.614 ThaliTest[474:393944] server session: connected
2015-12-18 19:38:22.615 ThaliTest[474:393944] server session: stateChange:1->2 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:22.618 ThaliTest[474:393203] server relay: connected (to port: 52904)
,2015-12-18T18:38:22.625Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:22.685Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T18:38:22.797Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-18 19:38:23.123 ThaliTest[474:393898] server session: connected
,2015-12-18 19:38:23.123 ThaliTest[474:393898] server session: stateChange:1->2 Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:23.221 ThaliTest[474:393203] server relay: connected (to port: 52904)
,2015-12-18T18:38:23.226Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:23.243Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T18:38:23.257Z SendDataTCPServer.js: TCP/IP server has received 48038 bytes of data
,2015-12-18T18:38:23.263Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:23.263Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:23.266Z SendDataConnector.js: CLIENT Stop now
2015-12-18T18:38:23.266Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:23.268 ThaliTest[474:393429] jxcore: disconnect
,2015-12-18 19:38:23.268 ThaliTest[474:393429] client session: disconnectFromPeer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:23.269 ThaliTest[474:393429] client session: disconnect
,2015-12-18 19:38:23.270 ThaliTest[474:393429] client session: stateChange:2->0 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:23.345 ThaliTest[474:393429] jxcore: disconnect: success
,2015-12-18T18:38:23.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3434.MiytEA==
,---- round done--------
,startWithNextDevice
,2015-12-18T18:38:23.363Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T18:38:23.573Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T18:38:23.590Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-18T18:38:23.607Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-18T18:38:23.634Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:23.685 ThaliTest[474:393937] server session: not connected Apple-Iphone5s-1_PT9213
,2015-12-18 19:38:23.701 ThaliTest[474:393937] server session: not connected Apple-Iphone5-1_PT3434
,2015-12-18 19:38:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:38:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:38:50.191 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:50.191 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:39:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:39:20.187 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:39:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:39:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:39:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:39:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:39:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:39:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:20.161 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:40:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:40:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:40:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:40:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:40:50.191 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:40:50.191 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:41:07.233 ThaliTest[474:393203] client: lost peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:41:07.234 ThaliTest[474:393203] client session: onPeerLost: Apple-Iphone5s-1_PT9213.s950ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-18 19:41:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:41:20.187 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:41:20.187 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:41:43.113 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:41:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:41:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:41:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:41:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:42:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:42:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:42:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:42:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:42:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:42:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:42:50.191 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:42:50.431 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:43:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:43:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:43:20.679 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-18 19:43:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:43:50.187 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:50.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:43:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:44:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:44:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:44:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:44:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:44:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:44:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:44:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:44:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:45:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:45:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:45:20.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:45:20.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:45:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:45:50.188 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:45:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:45:50.192 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:46:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:46:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:46:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:46:20.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:46:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:46:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:46:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:46:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:47:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:47:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:47:20.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:47:20.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:47:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:47:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:47:50.192 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:47:50.192 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:48:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:48:20.188 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:48:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:48:20.189 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:48:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:48:50.186 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:48:50.186 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:48:50.913 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:20.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:49:20.192 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:49:20.194 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:49:20.194 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:49:50.162 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:49:50.189 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:49:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:49:50.190 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:50:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:50:20.173 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:50:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:50:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:50:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:50:50.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:50:50.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:50:50.176 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:51:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:51:20.176 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:51:20.176 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:51:20.177 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:51:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:51:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:51:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:51:50.622 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:52:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:52:20.173 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:52:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:52:20.174 ThaliTest[474:393203] client: fou,nd peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:52:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:52:50.172 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:52:50.172 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:52:50.969 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:53:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:53:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:53:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:53:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:53:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:53:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:53:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:53:50.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:54:20.147 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:54:20.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:54:20.176 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:54:20.177 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:54:49.463Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:54:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:54:50.173 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:54:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:54:50.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:55:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:55:20.172 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:55:20.173 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:55:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:55:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:55:50.173 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:55:50.173 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:55:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:56:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:56:20.172 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:56:20.172 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:56:20.172 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:56:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:56:50.176 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:56:50.176 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:56:50.177 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:57:20.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:57:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:57:20.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:57:20.176 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:57:50.146 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:57:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:57:50.174 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:57:50.175 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,teardown
,testSendData stopped
,2015-12-18 19:58:10.762 ThaliTest[474:393429] jxcore: stopBroadcasting
,2015-12-18 19:58:10.762 ThaliTest[474:393429] THEMultipeerSession stopping peer
,2015-12-18 19:58:10.763 ThaliTest[474:393429] multipeer session: stop timer
,2015-12-18 19:58:10.764 ThaliTest[474:393429] server session: disconnect
2015-12-18 19:58:10.764 ThaliTest[474:393429] server session: stateChange:2->0 Apple-Iphone5s-1_PT9213
,2015-12-18 19:58:10.775 ThaliTest[474:393429] server session: disconnect
2015-12-18 19:58:10.775 ThaliTest[474:393429] server session: stateChange:2->0 Apple-Iphone6-1_PT6353
,2015-12-18 19:58:10.787 ThaliTest[474:393429] server session: disconnect
2015-12-18 19:58:10.788 ThaliTest[474:393429] server session: stateChange:2->0 Apple-Iphone5-1_PT3434
,2015-12-18 19:58:10.794 ThaliTest[474:393429] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-18T18:58:10.816Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:10.817Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:10.819Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:58:10.819Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-18 19:58:10.852 ThaliTest[474:393429] jxcore: startBroadcasting
,2015-12-18 19:58:10.855 ThaliTest[474:393429] server: starting Apple-IpadAir2-1_PT9191.+wp0cw==
2015-12-18 19:58:10.856 ThaliTest[474:393429] multipeer session: start timer: 0x194a08d0
2015-12-18 19:58:10.856 ThaliTest[474:393429] THEMultipeerSession ini,tialized peer Apple-IpadAir2-1_PT9191
2015-12-18 19:58:10.857 ThaliTest[474:393429] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-18 19:58:11.873 ThaliTest[474:393203] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:58:11.874 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-IpadAir2-1_PT9191.y0m4Ag==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-18 19:58:11.925 ThaliTest[474:393203] client: lost peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:58:11.926 ThaliTest[474:393203] client session: onPeerLost: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:58:11.926 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:58:11.926 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
,2015-12-18 19:58:40.858 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:58:40.884 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:58:40.885 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:58:40.885 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
,2015-12-18 19:59:10.858 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:59:10.885 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:59:10.886 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
2015-12-18 19:59:10.886 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
,2015-12-18 19:59:40.858 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 19:59:40.890 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
2015-12-18 19:59:40.890 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:59:40.890 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 20:00:10.858 ThaliTest[474:393203] multipeer session: restart
,2015-12-18 20:00:10.886 ThaliTest[474:393203] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 20:00:10.886 ThaliTest[474:393203] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
,2015-12-18 20:00:10.887 ThaliTest[474:393203] client: found peer: Apple-Iphone5s-1_PT9213.s950ig==

```
