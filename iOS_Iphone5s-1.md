#### Test 50650278d76d9c3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/83030979-16A8-46EF-934C-010618CB5AA4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/83030979-16A8-46EF-934C-010618CB5AA4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278d76d9c3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA29B221-E95D-4B99-BD61-417E676F5664/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60364"
,(lldb)     command script import "/tmp/83030979-16A8-46EF-934C-010618CB5AA4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 19:32:50.561 ThaliTest[493:377432] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A87CC68B-635D-4528-880C-C374E9BD756B/Library/Cookies/Cookies.binarycookies
,2015-12-18 19:32:50.965 ThaliTest[493:377432] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 19:32:50.966 ThaliTest[493:377432] Multi-tasking -> Device: YES, App: YES
,2015-12-18 19:32:50.975 ThaliTest[493:377432] Unlimited access to network resources
,2015-12-18 19:32:50.988 ThaliTest[493:377432] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 19:32:59.854 ThaliTest[493:377432] Resetting plugins due to page load.
,2015-12-18 19:33:03.149 ThaliTest[493:377432] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA29B221-E95D-4B99-BD61-417E676F5664/ThaliTest.app/www/index.html
,2015-12-18 19:33:03.361 ThaliTest[493:377432] JXcore Cordova plugin initializing
,2015-12-18 19:33:03.363 ThaliTest[493:377760] JXcore instance initializing
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
,2015-12-18 19:33:04.692 ThaliTest[493:377432] THREAD WARNING: ['JXcore'] took '89.118896' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 51734
,2015-12-18 19:38:08.834 ThaliTest[493:377760] jxcore: startBroadcasting
,2015-12-18 19:38:08.849 ThaliTest[493:377760] server: starting Apple-Iphone5s-1_PT9213.s950ig==
,2015-12-18 19:38:08.850 ThaliTest[493:377760] multipeer session: start timer: 0x1946a3b0
2015-12-18 19:38:08.851 ThaliTest[493:377760] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT9213
2015-12-18 19:38:08.852 ThaliTest[493:377760] jxcore: star,tBroadcasting: success
StartBroadcasting started ok
,null
2015-12-18T18:38:08.866Z SendDataTCPServer.js: TCP/IP server is bound to port: 51734
,2015-12-18 19:38:09.947 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
startWithNextDevice
device[1]: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:09.953Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18T18:38:09.954Z SendDataConnector.js: doConnect called with peer Apple-Iphone,5-1_PT3434.MiytEA==
,2015-12-18T18:38:09.954Z SendDataConnector.js: do connect now
2015-12-18 19:38:09.955 ThaliTest[493:377760] jxcore: connect Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:09.956 ThaliTest[493:377760] client session: connect
2015-12-18 19:38:09.957 Tha,liTest[493:377760] client session: stateChange:0->1 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:09.963 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 19:38:10.082 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 19:38:10.881 ThaliTest[493:377432] multipeer session: reset timer
2015-12-18 19:38:10.882 ThaliTest[493:377432] multipeer session: stop timer
2015-12-18 19:38:10.882 ThaliTest[493:377432] multipeer session: start timer: 0x1946a3b0
2015-12-18 ,19:38:10.883 ThaliTest[493:377432] server session: connect
2015-12-18 19:38:10.884 ThaliTest[493:377432] server session: stateChange:0->1 Apple-IpadAir2-1_PT9191
2015-12-18 19:38:10.905 ThaliTest[493:377432] server: accepting invitation Apple-IpadAir2-1_PT9191
,2015-12-18 19:38:13.445 ThaliTest[493:378272] client session: connected
2015-12-18 19:38:13.445 ThaliTest[493:378272] client session: stateChange:1->2 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:14.152 ThaliTest[493:378282] client session: fireConnectCallback: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:14.152 ThaliTest[493:378282] jxcore: connect: success
2015-12-18T18:38:14.158Z SendDataConnector.js: CLIENT connected to 51737, error: null
2015-12-18T18:38:14.158Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:14.166 ThaliTest[493:377432] client: relay established
2015-12-18 19:38:14.166 ThaliTest[493:377432] client: new accepted socket: 0x1947b230
,2015-12-18 19:38:14.172 ThaliTest[493:378282] server session: connected
,2015-12-18 19:38:14.172 ThaliTest[493:378282] server session: stateChange:1->2 Apple-IpadAir2-1_PT9191
,2015-12-18T18:38:14.180Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 19:38:14.243 ThaliTest[493:377432] server relay: connected (to port: 51734)
,2015-12-18 19:38:14.280 ThaliTest[493:377432] multipeer session: reset timer
,2015-12-18 19:38:14.281 ThaliTest[493:377432] multipeer session: stop timer
,2015-12-18 19:38:14.282 ThaliTest[493:377432] multipeer session: start timer: 0x1946a3b0
,2015-12-18 19:38:14.282 ThaliTest[493:377432] server session: connect
,2015-12-18 19:38:14.283 ThaliTest[493:377432] server session: stateChange:0->1 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:14.294 ThaliTest[493:377432] server: accepting invitation Apple-Iphone5-1_PT3434
,2015-12-18T18:38:14.563Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:14.612Z SendDataTCPServer.js: TCP/IP server has received 34046 bytes of data
,2015-12-18T18:38:14.626Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:14.867 ThaliTest[493:378276] server session: not connected Apple-IpadAir2-1_PT9191
,2015-12-18T18:38:15.350Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T18:38:15.402Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T18:38:15.416Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:15.417Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:15.420Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:15.420Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:15.423 ThaliTest[493:377760] jxcore: disconnect
2015-12-18 19:38:15.423 ThaliTest[493:377760] client session: disconnectFromPeer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:15.424 ThaliTest[493:377760] client session: disconnect
2,015-12-18 19:38:15.424 ThaliTest[493:377760] client session: stateChange:2->0 Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:38:15.437 ThaliTest[493:377760] jxcore: disconnect: success
2015-12-18T18:38:15.441Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT3434.MiytEA==
---- round done--------
startWithNextDevice
device[2]: Apple,-Iphone6-1_PT6353.xIoHCA==
2015-12-18T18:38:15.444Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18T18:38:15.444Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18T18:38:1,5.444Z SendDataConnector.js: do connect now
2015-12-18 19:38:15.445 ThaliTest[493:377760] jxcore: connect Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:15.445 ThaliTest[493:377760] client session: connect
2015-12-18 19:38:15.446 ThaliTest[493:377760], client session: stateChange:0->1 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:16.971 ThaliTest[493:377432] multipeer session: reset timer
2015-12-18 19:38:16.972 ThaliTest[493:377432] multipeer session: stop timer
2015-12-18 19:38:16.972 ThaliTest[493:377432] multipeer session: start timer: 0x1946a3b0
2015-12-18 ,19:38:16.972 ThaliTest[493:377432] server session: connect
2015-12-18 19:38:16.973 ThaliTest[493:377432] server session: stateChange:0->1 Apple-Iphone6-1_PT6353
2015-12-18 19:38:16.982 ThaliTest[493:377432] server: accepting invitation Apple-Iphone6-1_PT6353
,2015-12-18 19:38:17.891 ThaliTest[493:378282] server session: connected
2015-12-18 19:38:17.891 ThaliTest[493:378282] server session: stateChange:1->2 Apple-Iphone5-1_PT3434
,2015-12-18 19:38:17.898 ThaliTest[493:377432] server relay: connected (to port: 51734)
,2015-12-18T18:38:17.900Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:18.415Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T18:38:18.433Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T18:38:18.450Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-18T18:38:18.481Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-18T18:38:18.497Z SendDataTCPServer.js: TCP/IP server has received 69086 bytes of data
2015-12-18T18:38:18.511Z SendDataTCPServer.js: TCP/IP server has received 78840 bytes of data
,2015-12-18T18:38:18.525Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:18.876 ThaliTest[493:378291] client session: connected
2015-12-18 19:38:18.876 ThaliTest[493:378291] client session: stateChange:1->2 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:18.935 ThaliTest[493:378276] client session: fireConnectCallback: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:18.936 ThaliTest[493:378276] jxcore: connect: success
2015-12-18T18:38:18.937Z SendDataConnector.js: CLIENT connected to 51742, error: null
2015-12-18T18:38:18.937Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:18.942 ThaliTest[493:377432] client: relay established
2015-12-18 19:38:18.942 ThaliTest[493:377432] client: new accepted socket: 0x1948cb80
,2015-12-18T18:38:18.955Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 19:38:19.022 ThaliTest[493:378276] server session: not connected Apple-Iphone5-1_PT3434
,2015-12-18T18:38:19.391Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T18:38:19.454Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T18:38:19.454Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:19.455Z SendDataConnector.js: CLIENT Stop now
2015-12-18T18:38:19.455Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-18 19:38:19.457 ThaliTest[493:377760] jxcore: disconnect
,2015-12-18 19:38:19.457 ThaliTest[493:377760] client session: disconnectFromPeer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:38:19.457 ThaliTest[493:377760] client session: disconnect
,2015-12-18 19:38:19.457 ThaliTest[493:377760] client session: stateChange:2->0 Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:38:19.470 ThaliTest[493:377760] jxcore: disconnect: success
2015-12-18T18:38:19.471Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT6353.xIoHCA==
---- round done--------
startWithNextDevice
device[3]: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:38:19.472Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:38:19.472Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18T18:38:19.472Z SendDataConnector.js: do connect now
,2015-12-18 19:38:19.473 ThaliTest[493:377760] jxcore: connect Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:19.475 ThaliTest[493:377760] client session: connect
2015-12-18 19:38:19.475 ThaliTest[493:377760] client session: stateChange:0->1 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:19.877 ThaliTest[493:378273] server session: connected
2015-12-18 19:38:19.881 ThaliTest[493:378273] server session: stateChange:1->2 Apple-Iphone6-1_PT6353
,2015-12-18 19:38:19.925 ThaliTest[493:377432] server relay: connected (to port: 51734)
,2015-12-18T18:38:19.933Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T18:38:20.165Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-18T18:38:20.445Z SendDataTCPServer.js: TCP/IP server has received 86584 bytes of data
,2015-12-18T18:38:20.464Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 19:38:20.532 ThaliTest[493:378273] server session: not connected Apple-Iphone6-1_PT6353
,2015-12-18 19:38:22.541 ThaliTest[493:378291] client session: connected
2015-12-18 19:38:22.541 ThaliTest[493:378291] client session: stateChange:1->2 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:22.601 ThaliTest[493:378273] client session: fireConnectCallback: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:22.601 ThaliTest[493:378273] jxcore: connect: success
,2015-12-18T18:38:22.605Z SendDataConnector.js: CLIENT connected to 51746, error: null
2015-12-18T18:38:22.605Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 19:38:22.609 ThaliTest[493:377432] client: relay established
2015-12-18 19:38:22.609 ThaliTest[493:377432] client: new accepted socket: 0x19356020
,2015-12-18T18:38:22.622Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T18:38:23.059Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T18:38:23.072Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T18:38:23.072Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T18:38:23.073Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T18:38:23.073Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 19:38:23.073 ThaliTest[493:377760] jxcore: disconnect
2015-12-18 19:38:23.074 ThaliTest[493:377760] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:23.074 ThaliTest[493:377760] client session: disconnect
2015-12-18 19:38:23.074 ThaliTest[493:377760] client session: stateChange:2->0 Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:38:23.079 ThaliTest[493:377760] jxcore: disconnect: success
2015-12-18T18:38:23.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9191.y0m4Ag==
---- round done--------
startWithNextDevice
,2015-12-18 19:38:46.974 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:38:47.038 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:38:47.039 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:38:47.043 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:39:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:39:17.035 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:39:17.035 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:39:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:39:47.046 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:39:47.047 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:39:47.047 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:40:17.040 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:40:17.043 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:40:17.880 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:40:38.810 ThaliTest[493:377432] client: lost peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:40:38.810 ThaliTest[493:377432] client session: onPeerLost: Apple-Iphone6-1_PT6353.xIoHCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:40:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:40:46.999 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:40:47.843 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:40:47.844 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:41:09.210 ThaliTest[493:377432] client: lost peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:41:09.211 ThaliTest[493:377432] client session: onPeerLost: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:41:09.212 ThaliTest[493:377432] client: lost peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:41:09.212 ThaliTest[493:377432] clie,nt session: onPeerLost: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:41:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:41:17.023 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:41:33.083 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 19:41:42.458 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 19:41:46.974 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:41:47.030 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:41:47.048 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:41:47.049 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:42:13.527 ThaliTest[493:377432] client: lost peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:42:13.527 ThaliTest[493:377432] client session: onPeerLost: Apple-Iphone6-1_PT6353.xIoHCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:42:13.811 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:42:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:42:17.033 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:42:17.034 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:42:17.037 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:42:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:43:16.974 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:43:18.006 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:18.006 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:43:18.006 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:43:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:43:47.842 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:43:47.843 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:43:47.844 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:44:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:44:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:44:47.026 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:44:47.027 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:44:47.029 ThaliTest[493:377432] client: foun,d peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:45:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:45:17.030 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:45:17.031 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:45:17.036 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:45:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:45:47.027 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:45:47.915 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:45:47.915 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:46:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:46:17.028 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:46:17.029 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:46:17.030 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:46:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:47:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:47:17.027 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:47:17.028 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:47:17.029 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:47:46.974 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:48:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:48:17.908 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:48:17.908 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:48:17.909 ThaliTest[493:377432] client: foun,d peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:48:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:48:47.029 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:48:47.030 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:48:47.030 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:49:16.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:49:17.022 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:49:17.028 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:49:17.028 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:49:46.973 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:50:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:50:17.765 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:50:17.767 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:50:17.768 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:50:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:50:46.999 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:50:47.711 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:50:47.712 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:51:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:51:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:51:47.922 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:51:47.923 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:51:47.923 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:52:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:52:17.863 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:52:17.863 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:52:17.864 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:52:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:52:47.697 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:52:47.701 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:52:47.702 ThaliTest[493:377432] client: foun,d peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:53:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:53:17.013 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:53:17.014 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:53:17.019 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:53:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:53:46.999 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:53:47.000 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:53:47.001 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:54:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:54:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:54:47.785 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:54:47.785 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:54:47.786 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:54:48.851Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:55:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:55:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:55:47.001 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:55:47.002 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:55:47.004 ThaliTest[493:377432] client: foun,d peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:56:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:56:17.937 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:56:17.937 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:56:17.937 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:56:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:56:47.744 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:56:47.745 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:56:47.746 ThaliTest[493:377432] client: foun,d peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:57:16.942 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:57:17.726 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:57:17.726 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:57:17.726 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
,2015-12-18 19:57:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:57:46.998 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.xIoHCA==
,2015-12-18 19:57:47.009 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:57:47.010 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.MiytEA==
,2015-12-18 19:58:10.570 ThaliTest[493:377432] client: lost peer: Apple-Iphone5-1_PT3434.MiytEA==
2015-12-18 19:58:10.571 ThaliTest[493:377432] client session: onPeerLost: Apple-Iphone5-1_PT3434.MiytEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.MiytEA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:58:10.631 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT3434.mAEuiQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true,
,startWithNextDevice
,2015-12-18 19:58:11.620 ThaliTest[493:377432] client: lost peer: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:58:11.621 ThaliTest[493:377432] client session: onPeerLost: Apple-IpadAir2-1_PT9191.y0m4Ag==
2015-12-18 19:58:11.621 ThaliTest[493:377432] cli,ent: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:58:11.622 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerName":"(null)","peerAva,ilable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT6353.kxqUHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
peerAvailabilityChanged [{"peerIdentif,ier":"Apple-IpadAir2-1_PT9191.+wp0cw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-18 19:58:15.483 ThaliTest[493:377432] client: lost peer: Apple-Iphone6-1_PT6353.xIoHCA==
2015-12-18 19:58:15.483 ThaliTest[493:377432] client session: onPeerLost: Apple-Iphone6-1_PT6353.xIoHCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT6353.xIoHCA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:58:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:58:16.993 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
,2015-12-18 19:58:17.003 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
2015-12-18 19:58:17.003 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:58:46.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:58:47.005 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:58:47.006 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
2015-12-18 19:58:47.006 ThaliTest[493:377432] client: fou,nd peer: Apple-Iphone5-1_PT3434.mAEuiQ==
,2015-12-18 19:59:16.943 ThaliTest[493:377432] multipeer session: restart
,2015-12-18 19:59:16.999 ThaliTest[493:377432] client: found peer: Apple-Iphone6-1_PT6353.kxqUHA==
2015-12-18 19:59:16.999 ThaliTest[493:377432] client: found peer: Apple-Iphone5-1_PT3434.mAEuiQ==
2015-12-18 19:59:17.002 ThaliTest[493:377432] client: found peer: Apple-IpadAir2-1_PT9191.+wp0cw==
,2015-12-18 19:59:46.943 ThaliTest[493:377432] multipeer session: restart

```
