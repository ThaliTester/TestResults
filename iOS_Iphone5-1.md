#### Test 5065027869d93ea_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4787A994-675F-461E-BF53-E9CFEF75EE99/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/4787A994-675F-461E-BF53-E9CFEF75EE99/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027869d93ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2E166F4E-244F-4975-A5E6-441DC8A59887/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60475"
,(lldb)     command script import "/tmp/4787A994-675F-461E-BF53-E9CFEF75EE99/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-19 01:20:28.761 ThaliTest[430:484500] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/400911BE-419D-47E9-B766-8BF9B9FD2DA4/Library/Cookies/Cookies.binarycookies
,2015-12-19 01:20:28.898 ThaliTest[430:484500] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-19 01:20:28.900 ThaliTest[430:484500] Multi-tasking -> Device: YES, App: YES
,2015-12-19 01:20:28.907 ThaliTest[430:484500] Unlimited access to network resources
,2015-12-19 01:20:28.919 ThaliTest[430:484500] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-19 01:20:39.256 ThaliTest[430:484500] Resetting plugins due to page load.
,2015-12-19 01:20:43.409 ThaliTest[430:484500] Finished load of: file:///var/mobile/Containers/Bundle/Application/2E166F4E-244F-4975-A5E6-441DC8A59887/ThaliTest.app/www/index.html
,2015-12-19 01:20:43.626 ThaliTest[430:484500] JXcore Cordova plugin initializing
,2015-12-19 01:20:43.628 ThaliTest[430:484689] JXcore instance initializing
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
,2015-12-19 01:20:46.100 ThaliTest[430:484500] THREAD WARNING: ['JXcore'] took '156.875977' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 53695
,2015-12-19 01:26:56.339 ThaliTest[430:484689] jxcore: startBroadcasting
,2015-12-19 01:26:56.353 ThaliTest[430:484689] server: starting Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:26:56.354 ThaliTest[430:484689] multipeer session: start timer: 0x1aaf2b20
2015-12-19 01:26:56.355 ThaliTest[430:484689] THEMultipeerSession initialized peer Apple-Iphone5-1_PT7806
2015-12-19 01:26:56.355 ThaliTest[430:484689] jxcore: startBroadcasting: success
StartBroadcasting started ok
,null
,2015-12-19T00:26:56.360Z SendDataTCPServer.js: TCP/IP server is bound to port: 53695
,2015-12-19 01:26:57.405 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:26:57.407 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAi,r2-1_PT6779.RtEaKg==","peerName":"(null)","peerAvailable":true}]
2015-12-19 01:26:57.408 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
Found peer : (null), Available: true
startWithNextDevice
device[1]: Apple-IpadAir2-1_PT67,79.RtEaKg==
2015-12-19T00:26:57.410Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19T00:26:57.410Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19T00:26:57.411Z SendDa,taConnector.js: do connect now
2015-12-19 01:26:57.411 ThaliTest[430:484689] jxcore: connect Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:26:57.412 ThaliTest[430:484689] client session: connect
2015-12-19 01:26:57.412 ThaliTest[430:484689] client sess,ion: stateChange:0->1 Apple-IpadAir2-1_PT6779.RtEaKg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT3810.9x5b9w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-19 01:26:57.625 ThaliTest[430:484500] multipeer session: reset timer
2015-12-19 01:26:57.625 ThaliTest[430:484500] multipeer session: stop timer
2015-12-19 01:26:57.625 ThaliTest[430:484500] multipeer session: start timer: 0x1aaf2b20
2015-12-19 ,01:26:57.626 ThaliTest[430:484500] server session: connect
2015-12-19 01:26:57.626 ThaliTest[430:484500] server session: stateChange:0->1 Apple-IpadAir2-1_PT6779
,2015-12-19 01:26:57.632 ThaliTest[430:484500] server: accepting invitation Apple-IpadAir2-1_PT6779
,2015-12-19 01:26:57.726 ThaliTest[430:484500] multipeer session: reset timer
2015-12-19 01:26:57.727 ThaliTest[430:484500] multipeer session: stop timer
2015-12-19 01:26:57.728 ThaliTest[430:484500] multipeer session: start timer: 0x1aaf2b20
2015-12-19 01:26:57.728 ThaliTest[430:484500] server session: connect
2015-12-19 01:26:57.728 ThaliTest[430:484500] server session: stateChange:0->1 Apple-Iphone5s-1_PT7601
2015-12-19 01:26:57.738 ThaliTest[430:484500] server: accepting invitation Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:00.294 ThaliTest[430:485326] server session: connected
2015-12-19 01:27:00.294 ThaliTest[430:485326] server session: stateChange:1->2 Apple-IpadAir2-1_PT6779
,2015-12-19 01:27:00.302 ThaliTest[430:485326] client session: connected
2015-12-19 01:27:00.302 ThaliTest[430:485326] client session: stateChange:1->2 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19T00:27:00.349Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19 01:27:00.352 ThaliTest[430:484500] server relay: connected (to port: 53695)
,2015-12-19 01:27:00.352 ThaliTest[430:485341] client session: fireConnectCallback: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:00.353 ThaliTest[430:485341] jxcore: connect: success
,2015-12-19T00:27:00.355Z SendDataConnector.js: CLIENT connected to 53699, error: null
2015-12-19T00:27:00.355Z SendDataConnector.js: CLIENT starting client 
2015-12-19 01:27:00.361 ThaliTest[430:484500] client: relay established
2015-12-19 01:27:00.362 ,ThaliTest[430:484500] client: new accepted socket: 0x1aa12e90
,2015-12-19T00:27:00.375Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 01:27:00.544 ThaliTest[430:485349] server session: connected
2015-12-19 01:27:00.544 ThaliTest[430:485349] server session: stateChange:1->2 Apple-Iphone5s-1_PT7601
,2015-12-19 01:27:00.574 ThaliTest[430:484500] server relay: connected (to port: 53695)
,2015-12-19T00:27:00.947Z SendDataTCPServer.js: TCP/IP server connected
2015-12-19T00:27:00.950Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19T00:27:00.999Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:01.068 ThaliTest[430:485348] server session: not connected Apple-IpadAir2-1_PT6779
,2015-12-19T00:27:01.073Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-19T00:27:01.073Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19 01:27:01.088 ThaliTest[430:485348] server session: not connected Apple-Iphone5s-1_PT7601
,2015-12-19T00:27:01.089Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:01.090Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:01.092 ThaliTest[430:484689] jxcore: disconnect
,2015-12-19 01:27:01.094 ThaliTest[430:484689] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:01.095 ThaliTest[430:484689] client session: disconnect
,2015-12-19 01:27:01.096 ThaliTest[430:484689] client session: stateChange:2->0 Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:27:01.171 ThaliTest[430:484689] jxcore: disconnect: success
,2015-12-19T00:27:01.173Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6779.RtEaKg==
,---- round done--------
startWithNextDevice
,device[2]: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:01.176Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:01.176Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19T00:27:01.177Z SendDataConnector.js: do connect now
,2015-12-19 01:27:01.177 ThaliTest[430:484689] jxcore: connect Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:01.178 ThaliTest[430:484689] client session: connect
,2015-12-19 01:27:01.179 ThaliTest[430:484689] client session: stateChange:0->1 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:03.965 ThaliTest[430:485348] client session: connected
,2015-12-19 01:27:03.965 ThaliTest[430:485348] client session: stateChange:1->2 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:04.148 ThaliTest[430:485341] client session: fireConnectCallback: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:04.148 ThaliTest[430:485341] jxcore: connect: success
2015-12-19T00:27:04.150Z SendDataConnector.js: CLIENT connected to ,53703, error: null
2015-12-19T00:27:04.152Z SendDataConnector.js: CLIENT starting client 
,2015-12-19 01:27:04.157 ThaliTest[430:484500] client: relay established
2015-12-19 01:27:04.157 ThaliTest[430:484500] client: new accepted socket: 0x1abe15b0
,2015-12-19T00:27:04.165Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19 01:27:04.174 ThaliTest[430:484500] multipeer session: reset timer
2015-12-19 01:27:04.174 ThaliTest[430:484500] multipeer session: stop timer
2015-12-19 01:27:04.174 ThaliTest[430:484500] multipeer session: start timer: 0x1aaf2b20
2015-12-19 ,01:27:04.175 ThaliTest[430:484500] server session: connect
2015-12-19 01:27:04.175 ThaliTest[430:484500] server session: stateChange:0->1 Apple-Iphone6-1_PT3810
2015-12-19 01:27:04.181 ThaliTest[430:484500] server: accepting invitation Apple-Iphone6-1_PT3810
,2015-12-19T00:27:04.870Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-19T00:27:04.885Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T00:27:04.886Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T00:27:04.888Z SendDataConnector.js: CLIENT Stop now
2015-12-19T00:27:04.889Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:04.890 ThaliTest[430:484689] jxcore: disconnect
,2015-12-19 01:27:04.890 ThaliTest[430:484689] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:04.891 ThaliTest[430:484689] client session: disconnect
,2015-12-19 01:27:04.892 ThaliTest[430:484689] client session: stateChange:2->0 Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:27:04.972 ThaliTest[430:484689] jxcore: disconnect: success
,2015-12-19T00:27:04.975Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7601.1oUnQA==
---- round done--------
,startWithNextDevice
,device[3]: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.976Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.977Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19T00:27:04.977Z SendDataConnector.js: do connect now
,2015-12-19 01:27:04.978 ThaliTest[430:484689] jxcore: connect Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:04.979 ThaliTest[430:484689] client session: connect
,2015-12-19 01:27:04.980 ThaliTest[430:484689] client session: stateChange:0->1 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:06.751 ThaliTest[430:485341] server session: connected
2015-12-19 01:27:06.752 ThaliTest[430:485341] server session: stateChange:1->2 Apple-Iphone6-1_PT3810
,2015-12-19 01:27:06.755 ThaliTest[430:484500] server relay: connected (to port: 53695)
,2015-12-19T00:27:06.765Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-19T00:27:07.041Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-19T00:27:07.055Z SendDataTCPServer.js: TCP/IP server has received 10950 bytes of data
,2015-12-19T00:27:07.096Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-19T00:27:07.113Z SendDataTCPServer.js: TCP/IP server has received 47754 bytes of data
,2015-12-19T00:27:07.127Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-19T00:27:07.142Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-19 01:27:07.261 ThaliTest[430:485348] server session: not connected Apple-Iphone6-1_PT3810
,2015-12-19 01:27:07.760 ThaliTest[430:485348] client session: connected
2015-12-19 01:27:07.761 ThaliTest[430:485348] client session: stateChange:1->2 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:07.814 ThaliTest[430:485349] client session: fireConnectCallback: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:27:07.814 ThaliTest[430:485349] jxcore: connect: success
2015-12-19T00:27:07.815Z SendDataConnector.js: CLIENT connected to 5,3707, error: null
2015-12-19T00:27:07.815Z SendDataConnector.js: CLIENT starting client 
2015-12-19 01:27:07.818 ThaliTest[430:484500] client: relay established
2015-12-19 01:27:07.818 ThaliTest[430:484500] client: new accepted socket: 0x1aa04230
,2015-12-19T00:27:07.832Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-19T00:27:08.405Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-19T00:27:08.419Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-19T00:27:08.420Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-19T00:27:08.422Z SendDataConnector.js: CLIENT Stop now
,2015-12-19T00:27:08.422Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-19 01:27:08.423 ThaliTest[430:484689] jxcore: disconnect
2015-12-19 01:27:08.423 ThaliTest[430:484689] client session: disconnectFromPeer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:27:08.424 ThaliTest[430:484689] client session: disconnect
2,015-12-19 01:27:08.424 ThaliTest[430:484689] client session: stateChange:2->0 Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:27:08.431 ThaliTest[430:484689] jxcore: disconnect: success
2015-12-19T00:27:08.431Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT3810.9x5b9w==
---- round done--------
startWithNextDevice
,2015-12-19 01:27:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:27:34.210 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:27:34.210 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:27:34.212 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:28:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:28:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:28:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:28:34.207 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:28:34.208 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:29:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:29:04.208 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:29:04.208 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:29:04.208 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:29:34.176 ThaliTest[430:484500] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-19 01:30:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:30:04.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:30:04.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:30:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteringBackground wasn't registered
,2015-12-19 01:30:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:30:34.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:30:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:30:34.212 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteredForeground wasn't registered
,2015-12-19 01:31:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:31:04.206 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:31:04.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:31:04.210 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteringBackground wasn't registered
,2015-12-19 01:31:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:31:34.208 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:31:34.209 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:31:34.211 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:32:04.175 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:32:04.784 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:32:04.785 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:32:04.785 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:32:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:32:34.208 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:32:34.210 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:32:34.211 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,Connected to the server!
,2015-12-19 01:33:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:33:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:33:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:33:04.207 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2015-12-19 01:33:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:33:34.205 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:33:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:33:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,appEnteringBackground wasn't registered
,2015-12-19 01:34:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:34:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:34:34.204 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:34:34.206 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:34:34.208 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:35:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:35:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:35:34.205 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:35:34.206 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:35:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:36:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:36:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:36:34.203 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:36:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:36:34.285 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:37:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:37:04.208 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:37:04.209 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:37:04.210 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:37:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:37:34.560 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:37:34.560 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:37:34.561 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:38:04.175 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:38:04.482 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:38:04.482 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:38:04.483 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:38:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:38:34.204 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:38:34.205 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:38:34.205 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:39:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:39:04.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:39:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:39:04.208 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:39:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:39:34.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:39:34.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:39:34.211 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:40:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:40:04.206 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:40:04.206 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:04.206 ThaliTest[430:484500] client: fou,nd peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:40:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:40:34.431 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:40:34.431 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:40:34.431 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,appEnteredForeground wasn't registered
,2015-12-19 01:41:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:41:04.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:41:04.205 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:41:04.747 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteringBackground wasn't registered
,2015-12-19 01:41:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:41:34.207 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:41:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:41:34.208 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:42:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:42:04.206 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:42:04.208 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:42:04.209 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:42:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:42:34.385 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:42:34.385 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:42:34.386 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-19 01:43:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:43:04.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:43:04.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:43:04.208 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:43:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:43:34.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:43:34.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:43:34.208 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-19T00:43:36.366Z SendDataConnector.js: CLIENT Stop now
,2015-12-19 01:44:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:44:04.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:44:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:44:04.207 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:44:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:44:34.206 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:44:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
,2015-12-19 01:44:34.209 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:45:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:45:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:04.207 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:45:04.208 ThaliTest[430:484500] client: fo,und peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:45:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:45:34.209 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,2015-12-19 01:45:34.214 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:45:34.214 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:46:04.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:46:04.205 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:46:04.205 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
2015-12-19 01:46:04.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:46:34.176 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:46:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
2015-12-19 01:46:34.207 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:46:34.207 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.RtEaKg==
,teardown
,testSendData stopped
2015-12-19 01:46:56.811 ThaliTest[430:484689] jxcore: stopBroadcasting
2015-12-19 01:46:56.811 ThaliTest[430:484689] THEMultipeerSession stopping peer
2015-12-19 01:46:56.811 ThaliTest[430:484689] multipeer session: stop timer
,2015-12-19 01:46:56.811 ThaliTest[430:484689] server session: disconnect
,2015-12-19 01:46:56.812 ThaliTest[430:484689] server session: stateChange:2->0 Apple-Iphone5s-1_PT7601
,2015-12-19 01:46:56.817 ThaliTest[430:484689] server session: disconnect
2015-12-19 01:46:56.817 ThaliTest[430:484689] server session: stateChange:2->0 Apple-Iphone6-1_PT3810
,2015-12-19 01:46:56.825 ThaliTest[430:484689] server session: disconnect
2015-12-19 01:46:56.826 ThaliTest[430:484689] server session: stateChange:2->0 Apple-IpadAir2-1_PT6779
,2015-12-19 01:46:56.843 ThaliTest[430:484689] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-19T00:46:56.860Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:56.862Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:56.864Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-19T00:46:56.865Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,--- start :testFindPeers.js---
testFindPeers created [object Object]
serverPort is 8876
2015-12-19 01:46:56.899 ThaliTest[430:484689] jxcore: startBroadcasting
,2015-12-19 01:46:56.907 ThaliTest[430:484689] server: starting Apple-Iphone5-1_PT7806.jHAIjw==
,2015-12-19 01:46:56.915 ThaliTest[430:484689] multipeer session: start timer: 0x1abd9100
,2015-12-19 01:46:56.921 ThaliTest[430:484689] THEMultipeerSession initialized peer Apple-Iphone5-1_PT7806
,2015-12-19 01:46:56.924 ThaliTest[430:484689] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-19 01:46:57.855 ThaliTest[430:484500] client: found peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:57.856 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:46:57.857 ThaliTest[430:484500] client: fou,nd peer: Apple-Iphone6-1_PT3810.9x5b9w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerName":"(null)","peerAvailable":true}]
Found peer : Apple-Iphone5-1_PT7806.b8v14g==, peerAvailable: true
,weAreDoneNow
done, now sending data to server
,2015-12-19 01:46:58.060 ThaliTest[430:484500] client: lost peer: Apple-Iphone5-1_PT7806.b8v14g==
2015-12-19 01:46:58.061 ThaliTest[430:484500] client session: onPeerLost: Apple-Iphone5-1_PT7806.b8v14g==
,2015-12-19 01:46:58.420 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
,2015-12-19 01:47:26.922 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:47:26.951 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:47:26.951 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:47:26.952 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2015-12-19 01:47:56.922 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:48:26.922 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:48:26.951 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:48:26.951 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==
,2015-12-19 01:48:27.464 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
,2015-12-19 01:48:56.922 ThaliTest[430:484500] multipeer session: restart
,2015-12-19 01:48:56.953 ThaliTest[430:484500] client: found peer: Apple-Iphone5s-1_PT7601.1oUnQA==
2015-12-19 01:48:56.954 ThaliTest[430:484500] client: found peer: Apple-IpadAir2-1_PT6779.Eyppcg==
2015-12-19 01:48:56.954 ThaliTest[430:484500] client: found peer: Apple-Iphone6-1_PT3810.9x5b9w==

```
