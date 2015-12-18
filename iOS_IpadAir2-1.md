#### Test 50650278bcecc5c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6E788E09-991D-45D4-9C5A-2188FCBE488A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6E788E09-991D-45D4-9C5A-2188FCBE488A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278bcecc5c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3E017F08-3CF2-4475-A66B-341154940FC6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60241"
,(lldb)     command script import "/tmp/6E788E09-991D-45D4-9C5A-2188FCBE488A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-18 18:51:08.643 ThaliTest[460:386242] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D0ECB270-566F-4B44-A0D4-681618E5A989/Library/Cookies/Cookies.binarycookies
,2015-12-18 18:51:09.043 ThaliTest[460:386242] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-18 18:51:09.044 ThaliTest[460:386242] Multi-tasking -> Device: YES, App: YES
,2015-12-18 18:51:09.053 ThaliTest[460:386242] Unlimited access to network resources
,2015-12-18 18:51:09.061 ThaliTest[460:386242] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-18 18:51:17.892 ThaliTest[460:386242] Resetting plugins due to page load.
,2015-12-18 18:51:20.818 ThaliTest[460:386242] Finished load of: file:///var/mobile/Containers/Bundle/Application/3E017F08-3CF2-4475-A66B-341154940FC6/ThaliTest.app/www/index.html
,2015-12-18 18:51:20.974 ThaliTest[460:386242] JXcore Cordova plugin initializing
,2015-12-18 18:51:20.975 ThaliTest[460:386492] JXcore instance initializing
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
,2015-12-18 18:51:21.968 ThaliTest[460:386242] THREAD WARNING: ['JXcore'] took '70.622803' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 52707
,2015-12-18 18:56:26.616 ThaliTest[460:386492] jxcore: startBroadcasting
,2015-12-18 18:56:26.628 ThaliTest[460:386492] server: starting Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 18:56:26.630 ThaliTest[460:386492] multipeer session: start timer: 0x18c0a530
,2015-12-18 18:56:26.631 ThaliTest[460:386492] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9737
,2015-12-18 18:56:26.632 ThaliTest[460:386492] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-18T17:56:26.639Z SendDataTCPServer.js: TCP/IP server is bound to port: 52707
,2015-12-18 18:56:27.964 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,startWithNextDevice
,device[1]: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.970Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.971Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18T17:56:27.972Z SendDataConnector.js: do connect now
,2015-12-18 18:56:27.973 ThaliTest[460:386492] jxcore: connect Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:27.973 ThaliTest[460:386492] client session: connect
,2015-12-18 18:56:27.974 ThaliTest[460:386492] client session: stateChange:0->1 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:28.267 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:28.881 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-18 18:56:32.103 ThaliTest[460:387300] client session: connected
2015-12-18 18:56:32.103 ThaliTest[460:387300] client session: stateChange:1->2 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:32.132 ThaliTest[460:387283] client session: fireConnectCallback: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:56:32.132 ThaliTest[460:387283] jxcore: connect: success
,2015-12-18T17:56:32.134Z SendDataConnector.js: CLIENT connected to 52710, error: null
,2015-12-18T17:56:32.135Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:32.138 ThaliTest[460:386242] client: relay established
2015-12-18 18:56:32.139 ThaliTest[460:386242] client: new accepted socket: 0x18c04840
,2015-12-18T17:56:32.155Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18 18:56:32.204 ThaliTest[460:386242] multipeer session: reset timer
,2015-12-18 18:56:32.205 ThaliTest[460:386242] multipeer session: stop timer
,2015-12-18 18:56:32.205 ThaliTest[460:386242] multipeer session: start timer: 0x18c0a530
,2015-12-18 18:56:32.206 ThaliTest[460:386242] server session: connect
,2015-12-18 18:56:32.206 ThaliTest[460:386242] server session: stateChange:0->1 Apple-Iphone6-1_PT892
,2015-12-18 18:56:32.212 ThaliTest[460:386242] server: accepting invitation Apple-Iphone6-1_PT892
,2015-12-18T17:56:32.533Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T17:56:32.544Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T17:56:32.557Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-18T17:56:32.571Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T17:56:32.584Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-18T17:56:32.584Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:32.585Z SendDataConnector.js: CLIENT Stop now
2015-12-18T17:56:32.585Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:32.586 ThaliTest[460:386492] jxcore: disconnect
,2015-12-18 18:56:32.586 ThaliTest[460:386492] client session: disconnectFromPeer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:32.586 ThaliTest[460:386492] client session: disconnect
,2015-12-18 18:56:32.587 ThaliTest[460:386492] client session: stateChange:2->0 Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:56:32.591 ThaliTest[460:386492] jxcore: disconnect: success
,2015-12-18T17:56:32.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT892.v2mOqA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18T17:56:32.593Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18T17:56:32.594Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18T17:56:32.594Z SendDataConnector.js: do connect now
,2015-12-18 18:56:32.594 ThaliTest[460:386492] jxcore: connect Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:32.595 ThaliTest[460:386492] client session: connect
,2015-12-18 18:56:32.595 ThaliTest[460:386492] client session: stateChange:0->1 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:33.910 ThaliTest[460:386242] multipeer session: reset timer
2015-12-18 18:56:33.911 ThaliTest[460:386242] multipeer session: stop timer
2015-12-18 18:56:33.911 ThaliTest[460:386242] multipeer session: start timer: 0x18c0a530
2015-12-18 ,18:56:33.911 ThaliTest[460:386242] server session: connect
2015-12-18 18:56:33.912 ThaliTest[460:386242] server session: stateChange:0->1 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:33.918 ThaliTest[460:386242] server: accepting invitation Apple-Iphone5-1_PT4784
,2015-12-18 18:56:35.115 ThaliTest[460:387287] server session: connected
,2015-12-18 18:56:35.116 ThaliTest[460:387287] server session: stateChange:1->2 Apple-Iphone6-1_PT892
,2015-12-18T17:56:35.122Z SendDataTCPServer.js: TCP/IP server connected
2015-12-18 18:56:35.122 ThaliTest[460:386242] server relay: connected (to port: 52707)
,2015-12-18T17:56:35.384Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-18 18:56:35.485 ThaliTest[460:387333] client session: connected
2015-12-18 18:56:35.485 ThaliTest[460:387333] client session: stateChange:1->2 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:35.490 ThaliTest[460:387333] client session: fireConnectCallback: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:35.491 ThaliTest[460:387333] jxcore: connect: success
,2015-12-18T17:56:35.492Z SendDataConnector.js: CLIENT connected to 52714, error: null
,2015-12-18T17:56:35.493Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:35.495 ThaliTest[460:386242] client: relay established
,2015-12-18 18:56:35.496 ThaliTest[460:386242] client: new accepted socket: 0x18bb2740
,2015-12-18T17:56:35.510Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:35.758Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18T17:56:35.808Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-18T17:56:35.821Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-18 18:56:35.824 ThaliTest[460:387287] server session: not connected Apple-Iphone6-1_PT892
,2015-12-18T17:56:35.858Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T17:56:35.884Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-18T17:56:35.945Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:35.946Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-18T17:56:35.946Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:35.946Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:35.947 ThaliTest[460:386492] jxcore: disconnect
,2015-12-18 18:56:35.947 ThaliTest[460:386492] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:35.947 ThaliTest[460:386492] client session: disconnect
,2015-12-18 18:56:35.947 ThaliTest[460:386492] client session: stateChange:2->0 Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:56:35.951 ThaliTest[460:386492] jxcore: disconnect: success
,2015-12-18T17:56:35.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7811.xvr6/w==
,---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18T17:56:35.954Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18T17:56:35.954Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18T17:56:35.954Z SendDataConnector.js: do connect now
,2015-12-18 18:56:35.954 ThaliTest[460:386492] jxcore: connect Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:35.955 ThaliTest[460:386492] client session: connect
,2015-12-18 18:56:35.955 ThaliTest[460:386492] client session: stateChange:0->1 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:36.555 ThaliTest[460:387287] server session: connected
2015-12-18 18:56:36.555 ThaliTest[460:387287] server session: stateChange:1->2 Apple-Iphone5-1_PT4784
,2015-12-18 18:56:36.560 ThaliTest[460:386242] server relay: connected (to port: 52707)
,2015-12-18T17:56:36.571Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:37.121Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T17:56:37.135Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-18T17:56:37.151Z SendDataTCPServer.js: TCP/IP server has received 52560 bytes of data
,2015-12-18T17:56:37.187Z SendDataTCPServer.js: TCP/IP server has received 56656 bytes of data
,2015-12-18T17:56:37.201Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:37.254 ThaliTest[460:387287] server session: not connected Apple-Iphone5-1_PT4784
,2015-12-18 18:56:38.302 ThaliTest[460:386242] multipeer session: reset timer
2015-12-18 18:56:38.302 ThaliTest[460:386242] multipeer session: stop timer
2015-12-18 18:56:38.302 ThaliTest[460:386242] multipeer session: start timer: 0x18c0a530
2015-12-18 ,18:56:38.303 ThaliTest[460:386242] server session: connect
,2015-12-18 18:56:38.303 ThaliTest[460:386242] server session: stateChange:0->1 Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:38.310 ThaliTest[460:386242] server: accepting invitation Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:38.763 ThaliTest[460:387300] client session: connected
2015-12-18 18:56:38.764 ThaliTest[460:387300] client session: stateChange:1->2 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:38.769 ThaliTest[460:387300] client session: fireConnectCallback: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:56:38.769 ThaliTest[460:387300] jxcore: connect: success
,2015-12-18T17:56:38.771Z SendDataConnector.js: CLIENT connected to 52718, error: null
2015-12-18T17:56:38.772Z SendDataConnector.js: CLIENT starting client 
,2015-12-18 18:56:38.775 ThaliTest[460:386242] client: relay established
2015-12-18 18:56:38.776 ThaliTest[460:386242] client: new accepted socket: 0x18d3eec0
,2015-12-18T17:56:38.788Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-18T17:56:39.096Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-18T17:56:39.145Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-18T17:56:39.158Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-18T17:56:39.158Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-18T17:56:39.158Z SendDataConnector.js: CLIENT Stop now
,2015-12-18T17:56:39.158Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-18 18:56:39.159 ThaliTest[460:386492] jxcore: disconnect
,2015-12-18 18:56:39.159 ThaliTest[460:386492] client session: disconnectFromPeer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:39.159 ThaliTest[460:386492] client session: disconnect
,2015-12-18 18:56:39.159 ThaliTest[460:386492] client session: stateChange:2->0 Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:56:39.162 ThaliTest[460:386492] jxcore: disconnect: success
2015-12-18T17:56:39.162Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4784.tBG+yQ==
---- round done--------
startWithNextDevice
,2015-12-18 18:56:41.014 ThaliTest[460:387283] server session: connected
2015-12-18 18:56:41.014 ThaliTest[460:387283] server session: stateChange:1->2 Apple-Iphone5s-1_PT7811
,2015-12-18 18:56:41.018 ThaliTest[460:386242] server relay: connected (to port: 52707)
,2015-12-18T17:56:41.031Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-18T17:56:41.341Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-18T17:56:41.355Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-18T17:56:41.395Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-18T17:56:41.411Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-18 18:56:41.453 ThaliTest[460:387282] server session: not connected Apple-Iphone5s-1_PT7811
,2015-12-18 18:57:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:57:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:57:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:57:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:57:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:57:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 18:57:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:57:38.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:58:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:58:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:58:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 18:58:08.401 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:58:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:58:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:58:38.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:58:38.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:59:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:59:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:59:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:08.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 18:59:14.179 ThaliTest[460:386242] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 18:59:14.179 ThaliTest[460:386242] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-18 18:59:15.997 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 18:59:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 18:59:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 18:59:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 18:59:38.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:00:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:00:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:00:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:00:08.696 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-18 19:00:38.303 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:00:38.612 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:00:38.961 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:00:38.962 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:01:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:01:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:01:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:01:08.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:01:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:01:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:01:38.380 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:01:39.313 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,appEnteredForeground wasn't registered
,2015-12-18 19:02:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:02:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:02:09.121 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:02:09.122 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,appEnteringBackground wasn't registered
,2015-12-18 19:02:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:02:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:02:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:02:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:03:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:03:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:03:08.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:03:08.333 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:03:29.791 ThaliTest[460:386242] client: lost peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:03:29.791 ThaliTest[460:386242] client session: onPeerLost: Apple-Iphone5s-1_PT7811.xvr6/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-18 19:03:30.098 ThaliTest[460:386242] client: lost peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:03:30.099 ThaliTest[460:386242] client session: onPeerLost: Apple-Iphone6-1_PT892.v2mOqA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-18 19:03:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:03:38.323 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:03:49.264 ThaliTest[460:386242] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:03:49.265 ThaliTest[460:386242] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-18 19:03:57.350 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:03:57.355 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4784.tBG+yQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-18 19:03:57.359 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":true}]
,startWithNextDevice
,2015-12-18 19:04:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:04:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:04:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:04:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:04:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:04:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:04:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:04:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:05:08.303 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:05:08.328 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:05:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:05:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:05:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:05:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:05:38.392 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:05:38.460 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:06:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:06:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:06:08.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:06:08.334 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:06:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:06:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:06:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:06:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:07:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:07:08.334 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:07:08.334 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:07:08.335 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:07:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:07:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:07:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:07:38.495 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:08:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:08:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:08:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:08:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:08:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:08:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:08:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:08:39.296 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:09:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:09:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:09:38.326 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:09:38.327 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:09:38.503 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:10:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:10:08.328 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:10:08.401 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:10:08.475 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:10:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:10:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:10:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:10:38.332 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:11:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:11:08.327 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:11:08.327 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:11:08.328 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:11:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:11:38.327 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:11:38.327 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:11:38.328 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:12:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:12:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:12:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:12:08.425 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:12:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:12:39.438 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:12:39.438 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:12:39.438 ThaliTest[460:386242] client: foun,d peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-18T18:13:06.651Z SendDataConnector.js: CLIENT Stop now
,2015-12-18 19:13:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:13:08.328 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:13:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:13:08.833 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:13:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:13:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:13:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:13:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:14:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:14:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:14:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:14:08.470 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:14:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:14:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:14:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:14:38.334 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:15:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:15:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:15:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:15:08.330 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:15:38.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:15:38.329 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:15:38.330 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:15:38.331 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:16:08.304 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:16:08.328 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:16:08.329 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:16:08.330 ThaliTest[460:386242] client: foun,d peer: Apple-Iphone5-1_PT4784.tBG+yQ==
,teardown
,testSendData stopped
,2015-12-18 19:16:27.630 ThaliTest[460:386492] jxcore: stopBroadcasting
,2015-12-18 19:16:27.631 ThaliTest[460:386492] THEMultipeerSession stopping peer
,2015-12-18 19:16:27.631 ThaliTest[460:386492] multipeer session: stop timer
,2015-12-18 19:16:27.632 ThaliTest[460:386492] server session: disconnect
,2015-12-18 19:16:27.633 ThaliTest[460:386492] server session: stateChange:2->0 Apple-Iphone6-1_PT892
,2015-12-18 19:16:27.644 ThaliTest[460:386492] server session: disconnect
2015-12-18 19:16:27.645 ThaliTest[460:386492] server session: stateChange:2->0 Apple-Iphone5-1_PT4784
,2015-12-18 19:16:27.655 ThaliTest[460:386492] server session: disconnect
,2015-12-18 19:16:27.656 ThaliTest[460:386492] server session: stateChange:2->0 Apple-Iphone5s-1_PT7811
,2015-12-18 19:16:27.662 ThaliTest[460:386492] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-18T18:16:27.681Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:16:27.683Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:16:27.684Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-18T18:16:27.685Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
serverPort is 8876
,2015-12-18 19:16:27.718 ThaliTest[460:386492] jxcore: startBroadcasting
,2015-12-18 19:16:27.721 ThaliTest[460:386492] server: starting Apple-IpadAir2-1_PT9737.STphng==
2015-12-18 19:16:27.722 ThaliTest[460:386492] multipeer session: start timer: 0x18bac550
2015-12-18 19:16:27.723 ThaliTest[460:386492] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT9737
2015-12-18 19:16:27.724 ThaliTest[460:386492] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-18 19:16:27.739 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:16:27.740 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:16:27.740 ThaliTest[460:386242] client: found peer: Apple-IpadAir2-1_PT9737.0QrSBA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT892.v2mOqA==, peerAvailable: true
,weAreDoneNow
2015-12-18 19:16:27.743 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.tBG+yQ==
done, now sending data to server
,2015-12-18 19:16:28.856 ThaliTest[460:386242] client: lost peer: Apple-IpadAir2-1_PT9737.0QrSBA==
2015-12-18 19:16:28.856 ThaliTest[460:386242] client session: onPeerLost: Apple-IpadAir2-1_PT9737.0QrSBA==
,2015-12-18 19:16:28.957 ThaliTest[460:386242] client: lost peer: Apple-Iphone5-1_PT4784.tBG+yQ==
2015-12-18 19:16:28.958 ThaliTest[460:386242] client session: onPeerLost: Apple-Iphone5-1_PT4784.tBG+yQ==
,2015-12-18 19:16:28.991 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
,2015-12-18 19:16:57.725 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:16:57.747 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:16:57.747 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
,2015-12-18 19:16:57.762 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:17:27.725 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:17:27.751 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:17:27.751 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:17:27.752 ThaliTest[460:386242] client: fou,nd peer: Apple-Iphone6-1_PT892.v2mOqA==
,2015-12-18 19:17:57.725 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:17:57.749 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:17:57.749 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==
2015-12-18 19:17:57.750 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
,2015-12-18 19:18:27.725 ThaliTest[460:386242] multipeer session: restart
,2015-12-18 19:18:27.749 ThaliTest[460:386242] client: found peer: Apple-Iphone6-1_PT892.v2mOqA==
2015-12-18 19:18:27.750 ThaliTest[460:386242] client: found peer: Apple-Iphone5-1_PT4784.B3pdeg==
2015-12-18 19:18:27.750 ThaliTest[460:386242] client: found peer: Apple-Iphone5s-1_PT7811.xvr6/w==

```
