#### Test 50650278bcecc5c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/47000A34-7B94-4BB1-A8C7-93312F61BFFB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/47000A34-7B94-4BB1-A8C7-93312F61BFFB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4041EE2E-A030-4708-9EBC-1493479601B4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60243"
,(lldb)     command script import "/tmp/47000A34-7B94-4BB1-A8C7-93312F61BFFB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-18 18:51:10.140 ThaliTest[454:374865] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29CFEA54-65D9-4335-8145-E35E07148C86/Library/Cookies/Cookies.binarycookies
,2015-12-18 18:51:10.473 ThaliTest[454:374865] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 18:51:10.474 ThaliTest[454:374865] Multi-tasking -> Device: YES, App: YES
,2015-12-18 18:51:10.478 ThaliTest[454:374865] Unlimited access to network resources
,2015-12-18 18:51:10.487 ThaliTest[454:374865] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 18:51:18.811 ThaliTest[454:374865] Resetting plugins due to page load.
,2015-12-18 18:51:22.088 ThaliTest[454:374865] Finished load of: file:///var/mobile/Containers/Bundle/Application/4041EE2E-A030-4708-9EBC-1493479601B4/ThaliTest.app/www/index.html
,2015-12-18 18:51:22.268 ThaliTest[454:374865] JXcore Cordova plugin initializing
,2015-12-18 18:51:22.269 ThaliTest[454:375072] JXcore instance initializing
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
,2015-12-18 18:51:23.344 ThaliTest[454:374865] THREAD WARNING: ['JXcore'] took '76.623779' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 52653
,2015-12-18 18:56:26.179 ThaliTest[454:375072] jxcore: startBroadcasting
,2015-12-18 18:56:26.200 ThaliTest[454:375072] server: starting Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:26.202 ThaliTest[454:375072] multipeer session: start timer: 0x16321410
,2015-12-18 18:56:26.216 ThaliTest[454:375072] THEMultipeerSession initialized peer Apple-Iphone6-1_PT892
,2015-12-18 18:56:26.218 ThaliTest[454:375072] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-18T17:56:26.224Z SendDataTCPServer.js: TCP/IP server is bound to port: 52653
,2015-12-18 18:56:27.754 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18T17:56:27.759Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18T17:56:27.760Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18T17:56:27.760Z SendDataConnector.j,s: do connect now
,2015-12-18 18:56:27.761 ThaliTest[454:375072] jxcore: connect Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:27.762 ThaliTest[454:375072] client session: connect
2015-12-18 18:56:27.763 ThaliTest[454:375072] client session: stateChange:0->1 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:27.793 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:27.820 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-18 18:56:28.775 ThaliTest[454:374865] multipeer session: reset timer
,2015-12-18 18:56:28.776 ThaliTest[454:374865] multipeer session: stop timer
2015-12-18 18:56:28.776 ThaliTest[454:374865] multipeer session: start timer: 0x16321410
,2015-12-18 18:56:28.777 ThaliTest[454:374865] server session: connect
2015-12-18 18:56:28.777 ThaliTest[454:374865] server session: stateChange:0->1 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:28.786 ThaliTest[454:374865] server: accepting invitation Apple-Iphone5-1_PT4784
,2015-12-18 18:56:28.969 ThaliTest[454:374865] multipeer session: reset timer
2015-12-18 18:56:28.969 ThaliTest[454:374865] multipeer session: stop timer
2015-12-18 18:56:28.970 ThaliTest[454:374865] multipeer session: start timer: 0x16321410
2015-12-18 ,18:56:28.970 ThaliTest[454:374865] server session: connect
2015-12-18 18:56:28.970 ThaliTest[454:374865] server session: stateChange:0->1 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:28.977 ThaliTest[454:374865] server: accepting invitation Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:29.888 ThaliTest[454:374865] multipeer session: reset timer
2015-12-18 18:56:29.889 ThaliTest[454:374865] multipeer session: stop timer
2015-12-18 18:56:29.889 ThaliTest[454:374865] multipeer session: start timer: 0x16321410
2015-12-18 ,18:56:29.889 ThaliTest[454:374865] server session: connect
2015-12-18 18:56:29.890 ThaliTest[454:374865] server session: stateChange:0->1 Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:29.900 ThaliTest[454:374865] server: accepting invitation Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:30.941 ThaliTest[454:375749] client session: connected
2015-12-18 18:56:30.943 ThaliTest[454:375749] client session: stateChange:1->2 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:30.948 ThaliTest[454:375749] client session: fireConnectCallback: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:30.949 ThaliTest[454:375749] jxcore: connect: success
,2015-12-18T17:56:30.952Z SendDataConnector.js: CLIENT connected to 52656, error: null
2015-12-18T17:56:30.952Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:30.957 ThaliTest[454:374865] client: relay established
2015-12-18 18:56:30.957 ThaliTest[454:374865] client: new accepted socket: 0x14e216f0
,2015-12-18T17:56:30.972Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:31.458Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18T17:56:31.472Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18 18:56:31.490 ThaliTest[454:375750] server session: connected
2015-12-18 18:56:31.490 ThaliTest[454:375750] server session: stateChange:1->2 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:31.494 ThaliTest[454:374865] server relay: connected (to port: 52653)
,2015-12-18T17:56:31.500Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:31.525Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:31.525Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:31.526Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:31.527Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:31.528 ThaliTest[454:375072] jxcore: disconnect
,2015-12-18 18:56:31.528 ThaliTest[454:375072] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:31.529 ThaliTest[454:375072] client session: disconnect
,2015-12-18 18:56:31.529 ThaliTest[454:375072] client session: stateChange:2->0 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:31.554 ThaliTest[454:375749] server session: connected
,2015-12-18 18:56:31.554 ThaliTest[454:375749] server session: stateChange:1->2 Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:31.565 ThaliTest[454:374865] server relay: connected (to port: 52653)
,2015-12-18 18:56:31.599 ThaliTest[454:375072] jxcore: disconnect: success
,2015-12-18T17:56:31.600Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7811.xvr6/w==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:31.601Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:31.602Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:31.602Z SendDataConnector.js: do connect now
,2015-12-18 18:56:31.603 ThaliTest[454:375072] jxcore: connect Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:31.603 ThaliTest[454:375072] client session: connect
,2015-12-18 18:56:31.604 ThaliTest[454:375072] client session: stateChange:0->1 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18T17:56:31.627Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:31.970Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-18T17:56:32.033Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T17:56:32.064Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-18T17:56:32.079Z SendDataTCPServer.js: TCP/IP server has received 63510 bytes of data
,2015-12-18T17:56:32.094Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-18T17:56:32.122Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-18 18:56:32.127 ThaliTest[454:375753] server session: not connected Apple-IpadAir2-1_PT9737
,2015-12-18T17:56:32.137Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:32.230 ThaliTest[454:375750] server session: not connected Apple-Iphone5-1_PT4784
,2015-12-18 18:56:33.512 ThaliTest[454:375750] server session: connected
2015-12-18 18:56:33.512 ThaliTest[454:375750] server session: stateChange:1->2 Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:33.521 ThaliTest[454:374865] server relay: connected (to port: 52653)
2015-12-18T17:56:33.523Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:34.026Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-18T17:56:34.042Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-18T17:56:34.061Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-18T17:56:34.077Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:34.155 ThaliTest[454:375750] server session: not connected Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:34.566 ThaliTest[454:375750] client session: connected
2015-12-18 18:56:34.567 ThaliTest[454:375750] client session: stateChange:1->2 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:34.583 ThaliTest[454:375753] client session: fireConnectCallback: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:34.583 ThaliTest[454:375753] jxcore: connect: success
2015-12-18T17:56:34.584Z SendDataConnector.js: CLIENT connected to ,52662, error: null
2015-12-18T17:56:34.585Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:34.589 ThaliTest[454:374865] client: relay established
2015-12-18 18:56:34.590 ThaliTest[454:374865] client: new accepted socket: 0x14e1ac90
,2015-12-18T17:56:34.602Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:35.235Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T17:56:35.249Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:35.249Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:35.250Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:35.251Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:35.251 ThaliTest[454:375072] jxcore: disconnect
2015-12-18 18:56:35.252 ThaliTest[454:375072] client session: disconnectFromPeer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:56:35.252 ThaliTest[454:375072] client session: disconnect
2015-12-18 18:56:35.252 ThaliTest[454:375072] client session: stateChange:2->0 Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:35.260 ThaliTest[454:375072] jxcore: disconnect: success
2015-12-18T17:56:35.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT9737.0QrSBA==
---- round done--------
startWithNextDevice
device[3]: Appl,e-Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:35.264Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:35.264Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18T17:56:,35.264Z SendDataConnector.js: do connect now
2015-12-18 18:56:35.264 ThaliTest[454:375072] jxcore: connect Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:56:35.265 ThaliTest[454:375072] client session: connect
2015-12-18 18:56:35.265 ThaliTest[454:375072,] client session: stateChange:0->1 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:38.292 ThaliTest[454:375750] client session: connected
2015-12-18 18:56:38.294 ThaliTest[454:375750] client session: stateChange:1->2 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:38.305 ThaliTest[454:375753] client session: fireConnectCallback: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:56:38.305 ThaliTest[454:375753] jxcore: connect: success
2015-12-18T17:56:38.306Z SendDataConnector.js: CLIENT connected to 5,2665, error: null
2015-12-18T17:56:38.307Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:38.310 ThaliTest[454:374865] client: relay established
,2015-12-18 18:56:38.312 ThaliTest[454:374865] client: new accepted socket: 0x14e25dc0
,2015-12-18T17:56:38.322Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:38.803Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-18T17:56:38.816Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:38.816Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:38.817Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:38.818Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:38.818 ThaliTest[454:375072] jxcore: disconnect
2015-12-18 18:56:38.819 ThaliTest[454:375072] client session: disconnectFromPeer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:56:38.819 ThaliTest[454:375072] client session: disconnect
2015-12-18 18:56:38.819 ThaliTest[454:375072] client session: stateChange:2->0 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:38.828 ThaliTest[454:375072] jxcore: disconnect: success
2015-12-18T17:56:38.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4784.tBG+yQ==
---- round done--------
startWithNextDevice
,2015-12-18 18:56:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:56:59.931 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:59.942 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:56:59.942 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:57:22.117 ThaliTest[454:374865] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:57:22.118 ThaliTest[454:374865] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 18:57:23.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 18:57:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:57:29.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:57:29.937 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:57:29.939 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:57:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:57:59.939 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:57:59.939 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:57:59.942 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:58:09.748 ThaliTest[454:374865] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:58:09.748 ThaliTest[454:374865] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 18:58:25.994 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 18:58:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:58:29.935 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 18:58:29.938 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:58:29.938 ThaliTest[454:374865] client: fo,und peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:58:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:58:59.934 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:58:59.938 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:58:59.938 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:59:12.964 ThaliTest[454:374865] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:12.964 ThaliTest[454:374865] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 18:59:15.031 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-18 18:59:29.891 ThaliTest[454:374865] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-18 18:59:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 18:59:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:59.928 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:59:59.932 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:00:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:00:29.931 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:00:29.931 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:00:29.933 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:00:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:01:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:01:29.923 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:01:29.925 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:01:29.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:01:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:01:59.926 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:01:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:01:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:02:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:02:29.932 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:02:29.933 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:02:29.934 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:02:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:02:59.925 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:02:59.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:02:59.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:03:29.002 ThaliTest[454:374865] client: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:29.003 ThaliTest[454:374865] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple,-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:03:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:03:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:03:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:03:59.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:03:59.930 ThaliTest[454:374865] client: fo,und peer: Apple-Iphone5-1_PT4784.tBG+yQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:04:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:04:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:04:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:04:29.936 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:04:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:05:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:05:29.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:05:29.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:05:29.928 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:05:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:05:59.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:05:59.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:05:59.937 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:06:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:06:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:06:59.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:06:59.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:06:59.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:07:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:07:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:07:59.925 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:07:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:07:59.927 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:08:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:08:29.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:08:29.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:08:29.930 ThaliTest[454:374865] client: fou,nd peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:08:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:08:59.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:08:59.931 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:08:59.933 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:09:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:09:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:09:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:09:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:09:59.928 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:10:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:10:29.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:10:29.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:10:29.930 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:10:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:10:59.935 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:10:59.936 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:10:59.937 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:11:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:11:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:11:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:11:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:11:59.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:12:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:12:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:12:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:12:29.931 ThaliTest[454:374865] client: fou,nd peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:12:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:12:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:12:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:12:59.931 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:13:06.240Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:13:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:13:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:13:59.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:13:59.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:13:59.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:14:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:14:29.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:14:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:14:29.930 ThaliTest[454:374865] client: fou,nd peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:14:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:14:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:14:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:14:59.930 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:15:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:15:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:15:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:15:29.932 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:15:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:15:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:15:59.933 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:15:59.934 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:16:28.411 ThaliTest[454:374865] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:16:28.411 ThaliTest[454:374865] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:28.413 ThaliTest[454:374865] client: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:16:28.413 ThaliTest[454:374865] clie,nt session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadA,ir2-1_PT9737.0QrSBA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:16:28.442 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
2015-12-18 19:16:28.443 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir,2-1_PT9737.STphng==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.B3pdeg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,2015-12-18 19:16:29.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:16:29.929 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:16:29.932 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:16:29.932 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:16:59.891 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:17:29.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:17:29.926 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:17:29.929 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
2015-12-18 19:17:29.930 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
,2015-12-18 19:17:59.890 ThaliTest[454:374865] multipeer session: restart
,2015-12-18 19:17:59.927 ThaliTest[454:374865] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:17:59.928 ThaliTest[454:374865] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:17:59.930 ThaliTest[454:374865] client: found peer: Apple-IpadAir2-1_PT9737.STphng==
,2015-12-18 19:18:29.890 ThaliTest[454:374865] multipeer session: restart

```
