#### Test 506502785223c58_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/63063DDC-1776-4047-8E7F-43B7E2385874/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/63063DDC-1776-4047-8E7F-43B7E2385874/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785223c58/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A0D2A973-F524-4E2B-8AB1-94BD273E9762/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59090"
,(lldb)     command script import "/tmp/63063DDC-1776-4047-8E7F-43B7E2385874/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 01:37:17.783 ThaliTest[335:152368] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FFC3A5B4-7257-4BD9-83EF-9356E3B87D8C/Library/Cookies/Cookies.binarycookies
,2015-12-17 01:37:18.186 ThaliTest[335:152368] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 01:37:18.187 ThaliTest[335:152368] Multi-tasking -> Device: YES, App: YES
,2015-12-17 01:37:18.196 ThaliTest[335:152368] Unlimited access to network resources
,2015-12-17 01:37:18.209 ThaliTest[335:152368] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 01:37:27.246 ThaliTest[335:152368] Resetting plugins due to page load.
,2015-12-17 01:37:31.009 ThaliTest[335:152368] Finished load of: file:///var/mobile/Containers/Bundle/Application/A0D2A973-F524-4E2B-8AB1-94BD273E9762/ThaliTest.app/www/index.html
,2015-12-17 01:37:31.217 ThaliTest[335:152368] JXcore Cordova plugin initializing
,2015-12-17 01:37:31.219 ThaliTest[335:152570] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-17 01:37:32.552 ThaliTest[335:152368] THREAD WARNING: ['JXcore'] took '92.058105' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-17 01:42:48.406 ThaliTest[335:152570] jxcore: startBroadcasting
,2015-12-17 01:42:48.425 ThaliTest[335:152570] server: starting Apple-Iphone5s-1_PT4765.aFuJbQ==
,2015-12-17 01:42:48.426 ThaliTest[335:152570] multipeer session: start timer: 0x16c86770
2015-12-17 01:42:48.427 ThaliTest[335:152570] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4765
2015-12-17 01:42:48.428 ThaliTest[335:152570] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17 01:42:49.533 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.tl0S1A==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.tl0S1A==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT6883.tl0S1A==, peerAvailable: true
weAreDoneNow
done, now sending data to server
,teardown
,testFindPeers stopped
,2015-12-17 01:42:50.497 ThaliTest[335:152570] jxcore: stopBroadcasting
2015-12-17 01:42:50.498 ThaliTest[335:152570] THEMultipeerSession stopping peer
2015-12-17 01:42:50.498 ThaliTest[335:152570] multipeer session: stop timer
2015-12-17 01:42:50.498 Th,aliTest[335:152570] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 50379
,2015-12-17 01:42:50.590 ThaliTest[335:152570] jxcore: startBroadcasting
,2015-12-17 01:42:50.597 ThaliTest[335:152570] server: starting Apple-Iphone5s-1_PT4765.ZBlg+A==
2015-12-17 01:42:50.597 ThaliTest[335:152570] multipeer session: start timer: 0x16c8db10
2015-12-17 01:42:50.598 ThaliTest[335:152570] THEMultipeerSession ini,tialized peer Apple-Iphone5s-1_PT4765
2015-12-17 01:42:50.598 ThaliTest[335:152570] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
2015-12-17T00:42:50.603Z SendDataTCPServer.js: TCP/IP server is bound to port: 50379
,2015-12-17 01:42:51.629 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2260.gQiHGg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:42:51.637Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17T00:42:51.638Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17T00:42:51.639Z SendDataConnector.js: do connect now
,2015-12-17 01:42:51.640 ThaliTest[335:152570] jxcore: connect Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:42:51.642 ThaliTest[335:152570] client session: connect
2015-12-17 01:42:51.642 ThaliTest[335:152570] client session: stateChange:0->1 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:42:51.665 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT4129.i5O+Uw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 01:42:52.677 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6883.KeEEhw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 01:42:55.768 ThaliTest[335:153089] client session: connected
2015-12-17 01:42:55.768 ThaliTest[335:153089] client session: stateChange:1->2 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:42:55.824 ThaliTest[335:153078] client session: fireConnectCallback: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:42:55.824 ThaliTest[335:153078] jxcore: connect: success
2015-12-17T00:42:55.826Z SendDataConnector.js: CLIENT connected to ,50382, error: null
2015-12-17T00:42:55.827Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:42:55.833 ThaliTest[335:152368] client: relay established
2015-12-17 01:42:55.834 ThaliTest[335:152368] client: new accepted socket: 0x16bc1690
,2015-12-17T00:42:55.848Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:42:56.350Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T00:42:56.411Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:42:56.412Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:42:56.413Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T00:42:56.413Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:42:56.414 ThaliTest[335:152570] jxcore: disconnect
2015-12-17 01:42:56.414 ThaliTest[335:152570] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:42:56.414 ThaliTest[335:152570] client session: disconnect
2015-12-17 01:42:56.414 ThaliTest[335:152570] client session: stateChange:2->0 Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:42:56.421 ThaliTest[335:152570] jxcore: disconnect: success
2015-12-17T00:42:56.421Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2260.gQiHGg==
---- round done--------
startWithNextDevice
device[2]: Appl,e-Iphone6-1_PT4129.i5O+Uw==
2015-12-17T00:42:56.422Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17T00:42:56.422Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17T00:42:56.422Z SendDataConnector.js: do connect now
2015-12-17 01:42:56.422 ThaliTest[335:152570] jxcore: connect Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:42:56.423 ThaliTest[335:152570] client session: connect
2015-12-17 01:42:56.423 ThaliTest[335:152570,] client session: stateChange:0->1 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:42:59.474 ThaliTest[335:153090] client session: connected
2015-12-17 01:42:59.475 ThaliTest[335:153090] client session: stateChange:1->2 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:42:59.497 ThaliTest[335:153079] client session: fireConnectCallback: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:42:59.498 ThaliTest[335:153079] jxcore: connect: success
,2015-12-17T00:42:59.499Z SendDataConnector.js: CLIENT connected to 50385, error: null
,2015-12-17T00:42:59.500Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:42:59.504 ThaliTest[335:152368] client: relay established
2015-12-17 01:42:59.505 ThaliTest[335:152368] client: new accepted socket: 0x16bc7540
,2015-12-17T00:42:59.516Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:42:59.996Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-17T00:43:00.011Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:43:00.011Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-17T00:43:00.012Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:43:00.012Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 01:43:00.013 ThaliTest[335:152570] jxcore: disconnect
,2015-12-17 01:43:00.013 ThaliTest[335:152570] client session: disconnectFromPeer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:00.014 ThaliTest[335:152570] client session: disconnect
,2015-12-17 01:43:00.015 ThaliTest[335:152570] client session: stateChange:2->0 Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:43:00.084 ThaliTest[335:152570] jxcore: disconnect: success
,2015-12-17T00:43:00.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT4129.i5O+Uw==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:43:00.086Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:43:00.087Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17T00:43:00.087Z SendDataConnector.js: do connect now
,2015-12-17 01:43:00.087 ThaliTest[335:152570] jxcore: connect Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:00.088 ThaliTest[335:152570] client session: connect
,2015-12-17 01:43:00.089 ThaliTest[335:152570] client session: stateChange:0->1 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:03.261 ThaliTest[335:153090] client session: connected
2015-12-17 01:43:03.262 ThaliTest[335:153090] client session: stateChange:1->2 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:03.300 ThaliTest[335:153089] client session: fireConnectCallback: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:03.301 ThaliTest[335:153089] jxcore: connect: success
2015-12-17T00:43:03.302Z SendDataConnector.js: CLIENT connected to 5,0388, error: null
2015-12-17T00:43:03.302Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 01:43:03.306 ThaliTest[335:152368] client: relay established
2015-12-17 01:43:03.307 ThaliTest[335:152368] client: new accepted socket: 0x16c92b10
,2015-12-17T00:43:03.320Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T00:43:03.685Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-17T00:43:03.698Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T00:43:03.698Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-17T00:43:03.698Z SendDataConnector.js: CLIENT Stop now
2015-12-17T00:43:03.699Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-17 01:43:03.699 ThaliTest[335:152570] jxcore: disconnect
2015-12-17 01:43:03.699 ThaliTest[335:152570] client session: disconnectFromPeer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:43:03.699 ThaliTest[335:152570] client session: disconnect
,2015-12-17 01:43:03.700 ThaliTest[335:152570] client session: stateChange:2->0 Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:43:03.704 ThaliTest[335:152570] jxcore: disconnect: success
2015-12-17T00:43:03.704Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6883.KeEEhw==
---- round done--------
startWithNextDevice
,2015-12-17 01:43:20.599 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:43:36.251 ThaliTest[335:152368] multipeer session: reset timer
2015-12-17 01:43:36.251 ThaliTest[335:152368] multipeer session: stop timer
2015-12-17 01:43:36.252 ThaliTest[335:152368] multipeer session: start timer: 0x16c8db10
,2015-12-17 01:43:36.253 ThaliTest[335:152368] server session: connect
2015-12-17 01:43:36.254 ThaliTest[335:152368] server session: stateChange:0->1 Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:36.264 ThaliTest[335:152368] server: accepting invitation Apple-IpadAir2-1_PT2260
,2015-12-17 01:43:39.200 ThaliTest[335:153180] server session: connected
,2015-12-17 01:43:39.202 ThaliTest[335:153180] server session: stateChange:1->2 Apple-IpadAir2-1_PT2260
,2015-12-17T00:43:39.269Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17 01:43:39.270 ThaliTest[335:152368] server relay: connected (to port: 50379)
,2015-12-17T00:43:39.470Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-17T00:43:39.489Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-12-17T00:43:39.513Z SendDataTCPServer.js: TCP/IP server has received 54182 bytes of data
,2015-12-17T00:43:39.531Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-17T00:43:39.547Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-17T00:43:39.565Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:43:39.605 ThaliTest[335:153180] server session: not connected Apple-IpadAir2-1_PT2260
,2015-12-17 01:44:06.253 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:44:06.311 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:44:06.311 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:44:06.312 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:44:12.034 ThaliTest[335:152368] multipeer session: reset timer
2015-12-17 01:44:12.035 ThaliTest[335:152368] multipeer session: stop timer
2015-12-17 01:44:12.035 ThaliTest[335:152368] multipeer session: start timer: 0x16c8db10
,2015-12-17 01:44:12.037 ThaliTest[335:152368] server session: connect
2015-12-17 01:44:12.037 ThaliTest[335:152368] server session: stateChange:0->1 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:12.047 ThaliTest[335:152368] server: accepting invitation Apple-Iphone6-1_PT4129
,2015-12-17 01:44:14.985 ThaliTest[335:153331] server session: connected
2015-12-17 01:44:14.985 ThaliTest[335:153331] server session: stateChange:1->2 Apple-Iphone6-1_PT4129
,2015-12-17 01:44:15.011 ThaliTest[335:152368] server relay: connected (to port: 50379)
2015-12-17T00:44:15.014Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:44:15.446Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-17T00:44:15.461Z SendDataTCPServer.js: TCP/IP server has received 32708 bytes of data
,2015-12-17T00:44:15.483Z SendDataTCPServer.js: TCP/IP server has received 56230 bytes of data
,2015-12-17T00:44:15.502Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-17T00:44:15.522Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-17T00:44:15.537Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:44:15.576 ThaliTest[335:153331] server session: not connected Apple-Iphone6-1_PT4129
,2015-12-17 01:44:21.268 ThaliTest[335:152368] multipeer session: reset timer
2015-12-17 01:44:21.268 ThaliTest[335:152368] multipeer session: stop timer
2015-12-17 01:44:21.269 ThaliTest[335:152368] multipeer session: start timer: 0x16c8db10
,2015-12-17 01:44:21.269 ThaliTest[335:152368] server session: connect
2015-12-17 01:44:21.271 ThaliTest[335:152368] server session: stateChange:0->1 Apple-Iphone5-1_PT6883
,2015-12-17 01:44:21.281 ThaliTest[335:152368] server: accepting invitation Apple-Iphone5-1_PT6883
,2015-12-17 01:44:23.954 ThaliTest[335:153331] server session: connected
2015-12-17 01:44:23.955 ThaliTest[335:153331] server session: stateChange:1->2 Apple-Iphone5-1_PT6883
,2015-12-17 01:44:23.975 ThaliTest[335:152368] server relay: connected (to port: 50379)
,2015-12-17T00:44:23.984Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T00:44:24.478Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-17T00:44:24.492Z SendDataTCPServer.js: TCP/IP server has received 21900 bytes of data
,2015-12-17T00:44:24.513Z SendDataTCPServer.js: TCP/IP server has received 43800 bytes of data
,2015-12-17T00:44:24.527Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-17T00:44:24.544Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-17T00:44:24.561Z SendDataTCPServer.js: TCP/IP server has received 81030 bytes of data
,2015-12-17T00:44:24.576Z SendDataTCPServer.js: TCP/IP server has received 96360 bytes of data
,2015-12-17T00:44:24.591Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 01:44:24.680 ThaliTest[335:153331] server session: not connected Apple-Iphone5-1_PT6883
,2015-12-17 01:44:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:44:51.338 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:44:51.338 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:44:51.339 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:45:21.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:45:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:45:51.325 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:45:51.326 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:45:51.329 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:46:21.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:46:21.333 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:46:21.335 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:46:21.336 ThaliTest[335:152368] client: fou,nd peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:46:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:47:21.271 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:47:21.332 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:47:21.333 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:47:21.333 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:47:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:47:51.337 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:47:51.338 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:47:51.338 ThaliTest[335:152368] client: fou,nd peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:48:21.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:48:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:48:51.328 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:48:51.328 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:48:51.329 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:49:21.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:49:21.339 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:49:21.340 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:49:21.342 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:49:51.270 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:49:51.331 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:49:51.339 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:49:51.340 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:50:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:50:21.314 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:50:21.321 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:50:21.322 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:50:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:50:51.319 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:50:51.320 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:50:51.321 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:51:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:51:21.315 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:51:21.316 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:51:21.317 ThaliTest[335:152368] client: fou,nd peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:51:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:51:51.315 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:51:51.316 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:51:51.317 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:52:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:52:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:52:51.318 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:52:51.319 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:52:51.319 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:53:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:53:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:53:51.316 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:53:51.316 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:53:51.317 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:54:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:54:21.315 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:54:21.316 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:54:21.321 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:54:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:54:51.317 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:54:51.319 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:54:51.320 ThaliTest[335:152368] client: foun,d peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:55:21.255 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:55:21.314 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:55:21.315 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:55:21.316 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:55:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:55:51.315 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:55:51.316 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:55:51.317 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:56:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:56:21.312 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:56:21.313 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:56:21.313 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:56:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:56:51.301 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:56:51.305 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:56:51.306 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:57:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:57:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:57:51.303 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:57:51.315 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
2015-12-17 01:57:51.316 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:58:21.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:58:21.311 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
,2015-12-17 01:58:21.314 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:58:21.329 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
,2015-12-17 01:58:51.254 ThaliTest[335:152368] multipeer session: restart
,2015-12-17 01:58:51.312 ThaliTest[335:152368] client: found peer: Apple-IpadAir2-1_PT2260.gQiHGg==
2015-12-17 01:58:51.313 ThaliTest[335:152368] client: found peer: Apple-Iphone5-1_PT6883.KeEEhw==
2015-12-17 01:58:51.315 ThaliTest[335:152368] client: found peer: Apple-Iphone6-1_PT4129.i5O+Uw==
,2015-12-17 01:59:21.254 ThaliTest[335:152368] multipeer session: restart
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-17T00:59:30.605Z SendDataConnector.js: CLIENT Stop now
,teardown
,testSendData stopped
2015-12-17 01:59:31.058 ThaliTest[335:152570] jxcore: stopBroadcasting
,2015-12-17 01:59:31.059 ThaliTest[335:152570] THEMultipeerSession stopping peer
2015-12-17 01:59:31.060 ThaliTest[335:152570] multipeer session: stop timer
2015-12-17 01:59:31.061 ThaliTest[335:152570] server session: disconnect
2015-12-17 01:59:31.062 ,ThaliTest[335:152570] server session: stateChange:2->0 Apple-Iphone6-1_PT4129
,2015-12-17 01:59:31.072 ThaliTest[335:152570] server session: disconnect
2015-12-17 01:59:31.072 ThaliTest[335:152570] server session: stateChange:2->0 Apple-Iphone5-1_PT6883
,2015-12-17 01:59:31.084 ThaliTest[335:152570] server session: disconnect
2015-12-17 01:59:31.085 ThaliTest[335:152570] server session: stateChange:2->0 Apple-IpadAir2-1_PT2260
,2015-12-17 01:59:31.198 ThaliTest[335:152570] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-17T00:59:31.219Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:31.221Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:31.223Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T00:59:31.224Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
