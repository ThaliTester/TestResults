#### Test 50650278f6345ef_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/50E567AF-EC80-4A7F-A6C4-31E8CDB80610/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/50E567AF-EC80-4A7F-A6C4-31E8CDB80610/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278f6345ef/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C7B36016-1A61-4412-9AA3-95A407880014/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54136"
,(lldb)     command script import "/tmp/50E567AF-EC80-4A7F-A6C4-31E8CDB80610/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 13:11:03.465 ThaliTest[658:806153] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0689B5A5-34F9-4AEA-95D1-DF9CDA29AF54/Library/Cookies/Cookies.binarycookies
,2015-12-11 13:11:04.010 ThaliTest[658:806153] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 13:11:04.012 ThaliTest[658:806153] Multi-tasking -> Device: YES, App: YES
,2015-12-11 13:11:04.018 ThaliTest[658:806153] Unlimited access to network resources
,2015-12-11 13:11:04.031 ThaliTest[658:806153] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 13:11:14.448 ThaliTest[658:806153] Resetting plugins due to page load.
,2015-12-11 13:11:17.659 ThaliTest[658:806153] Finished load of: file:///var/mobile/Containers/Bundle/Application/C7B36016-1A61-4412-9AA3-95A407880014/ThaliTest.app/www/index.html
,2015-12-11 13:11:17.864 ThaliTest[658:806153] JXcore Cordova plugin initializing
,2015-12-11 13:11:17.866 ThaliTest[658:806331] JXcore instance initializing
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
,2015-12-11 13:11:20.299 ThaliTest[658:806153] THREAD WARNING: ['JXcore'] took '154.561035' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testFindPeers.js---
,testFindPeers created [object Object]
,serverPort is 8876
,2015-12-11 13:17:50.410 ThaliTest[658:806331] jxcore: startBroadcasting
,2015-12-11 13:17:50.422 ThaliTest[658:806331] server: starting Apple-Iphone5-1_PT6904.k/CT+g==
,2015-12-11 13:17:50.423 ThaliTest[658:806331] multipeer session: start timer: 0x1bc4c920
,2015-12-11 13:17:50.424 ThaliTest[658:806331] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6904
2015-12-11 13:17:50.425 ThaliTest[658:806331] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-11 13:17:52.142 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.5CC0vg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.5CC0vg==","peerName":"(null)","peerAvailable":true}]
,Found peer : Apple-Iphone6-1_PT7734.5CC0vg==, peerAvailable: true
,weAreDoneNow
,done, now sending data to server
,2015-12-11 13:17:52.235 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.QAAa6w==
,2015-12-11 13:17:53.307 ThaliTest[658:806153] multipeer session: reset timer
2015-12-11 13:17:53.308 ThaliTest[658:806153] multipeer session: stop timer
,2015-12-11 13:17:53.308 ThaliTest[658:806153] multipeer session: start timer: 0x1bc4c920
,2015-12-11 13:17:53.309 ThaliTest[658:806153] server session: connect
,2015-12-11 13:17:53.309 ThaliTest[658:806153] server session: stateChange:0->1 Apple-Iphone5s-1_PT1055
,2015-12-11 13:17:53.317 ThaliTest[658:806153] server: accepting invitation Apple-Iphone5s-1_PT1055
,teardown
,testFindPeers stopped
,2015-12-11 13:17:54.016 ThaliTest[658:806331] jxcore: stopBroadcasting
2015-12-11 13:17:54.017 ThaliTest[658:806331] THEMultipeerSession stopping peer
2015-12-11 13:17:54.017 ThaliTest[658:806331] multipeer session: stop timer
2015-12-11 13:17:54.017 Th,aliTest[658:806331] server session: disconnect
2015-12-11 13:17:54.017 ThaliTest[658:806331] server session: stateChange:1->0 Apple-Iphone5s-1_PT1055
,2015-12-11 13:17:54.105 ThaliTest[658:806331] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,--- start :testSendData.js---
,testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
,check server
,serverPort is 57307
,2015-12-11 13:17:54.168 ThaliTest[658:806331] jxcore: startBroadcasting
,2015-12-11 13:17:54.171 ThaliTest[658:806331] server: starting Apple-Iphone5-1_PT6904.Jd0UjA==
,2015-12-11 13:17:54.174 ThaliTest[658:806331] multipeer session: start timer: 0x15e205b0
,2015-12-11 13:17:54.177 ThaliTest[658:806331] THEMultipeerSession initialized peer Apple-Iphone5-1_PT6904
,2015-12-11 13:17:54.180 ThaliTest[658:806331] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,null
,2015-12-11T12:17:54.190Z SendDataTCPServer.js: TCP/IP server is bound to port: 57307
,2015-12-11 13:17:55.094 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1055.SsV7MA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,startWithNextDevice
device[1]: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:17:55.099Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:17:55.100Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11T12:17:55.100Z SendDataConnector.js: do connect now
,2015-12-11 13:17:55.101 ThaliTest[658:806331] jxcore: connect Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:55.101 ThaliTest[658:806331] client session: connect
2015-12-11 13:17:55.102 ThaliTest[658:806331] client session: stateChange:0->1 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:55.215 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:55.218 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT8639.AH2xbQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 13:17:57.925 ThaliTest[658:807050] client session: connected
2015-12-11 13:17:57.925 ThaliTest[658:807050] client session: stateChange:1->2 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:57.971 ThaliTest[658:807052] client session: fireConnectCallback: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:17:57.971 ThaliTest[658:807052] jxcore: connect: success
2015-12-11T12:17:57.972Z SendDataConnector.js: CLIENT connected to 57310, error: null
2015-12-11T12:17:57.972Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:17:57.975 ThaliTest[658:806153] client: relay established
2015-12-11 13:17:57.975 ThaliTest[658:806153] client: new accepted socket: 0x1bbc8530
,2015-12-11T12:17:57.990Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:17:58.558Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:17:58.574Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T12:17:58.591Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-11T12:17:58.607Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:17:58.608Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:17:58.611Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:17:58.611Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:17:58.612 ThaliTest[658:806331] jxcore: disconnect
,2015-12-11 13:17:58.613 ThaliTest[658:806331] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:58.614 ThaliTest[658:806331] client session: disconnect
,2015-12-11 13:17:58.615 ThaliTest[658:806331] client session: stateChange:2->0 Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:17:58.693 ThaliTest[658:806331] jxcore: disconnect: success
,2015-12-11T12:17:58.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1055.SsV7MA==
,---- round done--------
,startWithNextDevice
,device[2]: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:17:58.698Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:17:58.698Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11T12:17:58.698Z SendDataConnector.js: do connect now
,2015-12-11 13:17:58.699 ThaliTest[658:806331] jxcore: connect Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:17:58.700 ThaliTest[658:806331] client session: connect
,2015-12-11 13:17:58.701 ThaliTest[658:806331] client session: stateChange:0->1 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:01.680 ThaliTest[658:807055] client session: connected
2015-12-11 13:18:01.681 ThaliTest[658:807055] client session: stateChange:1->2 Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:01.684 ThaliTest[658:807055] client session: fireConne,ctCallback: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:01.684 ThaliTest[658:807055] jxcore: connect: success
2015-12-11T12:18:01.685Z SendDataConnector.js: CLIENT connected to 57313, error: null
2015-12-11T12:18:01.685Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 13:18:01.688 ThaliTest[658:806153] client: relay established
2015-12-11 13:18:01.688 ThaliTest[658:806153] client: new accepted socket: 0x1bbce810
,2015-12-11T12:18:01.701Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:02.258Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T12:18:02.490Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T12:18:02.542Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:18:02.543Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:02.544Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T12:18:02.545Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:02.546 ThaliTest[658:806331] jxcore: disconnect
2015-12-11 13:18:02.546 ThaliTest[658:806331] client session: disconnectFromPeer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:02.546 ThaliTest[658:806331] client session: disconnect
2,015-12-11 13:18:02.547 ThaliTest[658:806331] client session: stateChange:2->0 Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:18:02.556 ThaliTest[658:806331] jxcore: disconnect: success
2015-12-11T12:18:02.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7734.oRkpZA==
---- round done--------
startWithNextDevice
device[3]: Apple,-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:02.557Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:18:02.558Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11T12:1,8:02.558Z SendDataConnector.js: do connect now
2015-12-11 13:18:02.558 ThaliTest[658:806331] jxcore: connect Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:02.558 ThaliTest[658:806331] client session: connect
2015-12-11 13:18:02.559 ThaliTest[658:806,331] client session: stateChange:0->1 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:06.751 ThaliTest[658:807052] client session: connected
2015-12-11 13:18:06.751 ThaliTest[658:807052] client session: stateChange:1->2 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:06.872 ThaliTest[658:807046] client session: fireConnectCallback: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:06.873 ThaliTest[658:807046] jxcore: connect: success
2015-12-11T12:18:06.873Z SendDataConnector.js: CLIENT connected to ,57316, error: null
2015-12-11T12:18:06.873Z SendDataConnector.js: CLIENT starting client 
2015-12-11 13:18:06.876 ThaliTest[658:806153] client: relay established
2015-12-11 13:18:06.876 ThaliTest[658:806153] client: new accepted socket: 0x1bc625f0
,2015-12-11T12:18:06.887Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T12:18:07.464Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-11T12:18:07.492Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-11T12:18:07.506Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T12:18:07.507Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-11T12:18:07.508Z SendDataConnector.js: CLIENT Stop now
2015-12-11T12:18:07.509Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 13:18:07.510 ThaliTest[658:806331] jxcore: disconnect
,2015-12-11 13:18:07.511 ThaliTest[658:806331] client session: disconnectFromPeer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:07.511 ThaliTest[658:806331] client session: disconnect
,2015-12-11 13:18:07.512 ThaliTest[658:806331] client session: stateChange:2->0 Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:18:07.523 ThaliTest[658:806331] jxcore: disconnect: success
,2015-12-11T12:18:07.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT8639.AH2xbQ==
,---- round done--------
,startWithNextDevice
,2015-12-11 13:18:24.178 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:18:24.213 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:18:24.213 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:18:24.214 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:18:43.993 ThaliTest[658:806153] multipeer session: reset timer
2015-12-11 13:18:43.993 ThaliTest[658:806153] multipeer session: stop timer
2015-12-11 13:18:43.993 ThaliTest[658:806153] multipeer session: start timer: 0x15e205b0
2015-12-11 13:18:43.993 ThaliTest[658:806153] server session: connect
2015-12-11 13:18:43.994 ThaliTest[658:806153] server session: stateChange:0->1 Apple-Iphone6-1_PT7734
,2015-12-11 13:18:43.999 ThaliTest[658:806153] server: accepting invitation Apple-Iphone6-1_PT7734
,2015-12-11 13:18:44.935 ThaliTest[658:806153] multipeer session: reset timer
2015-12-11 13:18:44.935 ThaliTest[658:806153] multipeer session: stop timer
2015-12-11 13:18:44.935 ThaliTest[658:806153] multipeer session: start timer: 0x15e205b0
,2015-12-11 13:18:44.936 ThaliTest[658:806153] server session: connect
2015-12-11 13:18:44.936 ThaliTest[658:806153] server session: stateChange:0->1 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:44.942 ThaliTest[658:806153] server: accepting invitation Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:46.560 ThaliTest[658:807199] server session: connected
2015-12-11 13:18:46.560 ThaliTest[658:807199] server session: stateChange:1->2 Apple-Iphone6-1_PT7734
,2015-12-11 13:18:46.567 ThaliTest[658:806153] server relay: connected (to port: 57307)
,2015-12-11T12:18:46.575Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:46.826Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-11T12:18:46.840Z SendDataTCPServer.js: TCP/IP server has received 30092 bytes of data
,2015-12-11T12:18:46.855Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-11T12:18:46.868Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-11T12:18:46.884Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:46.986 ThaliTest[658:807199] server session: not connected Apple-Iphone6-1_PT7734
,2015-12-11 13:18:47.136 ThaliTest[658:806153] multipeer session: reset timer
2015-12-11 13:18:47.136 ThaliTest[658:806153] multipeer session: stop timer
2015-12-11 13:18:47.136 ThaliTest[658:806153] multipeer session: start timer: 0x15e205b0
2015-12-11 13:18:47.136 ThaliTest[658:806153] server session: connect
2015-12-11 13:18:47.136 ThaliTest[658:806153] server session: stateChange:0->1 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:47.144 ThaliTest[658:806153] server: accepting invitation Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:47.474 ThaliTest[658:807200] server session: connected
2015-12-11 13:18:47.474 ThaliTest[658:807200] server session: stateChange:1->2 Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:47.492 ThaliTest[658:806153] server relay: connected (to port: 57307)
,2015-12-11T12:18:47.494Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:47.732Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-11T12:18:47.748Z SendDataTCPServer.js: TCP/IP server has received 32850 bytes of data
,2015-12-11T12:18:47.765Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T12:18:47.781Z SendDataTCPServer.js: TCP/IP server has received 83220 bytes of data
,2015-12-11T12:18:47.795Z SendDataTCPServer.js: TCP/IP server has received 98550 bytes of data
,2015-12-11T12:18:47.810Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:47.834 ThaliTest[658:807200] server session: not connected Apple-IpadAir2-1_PT8639
,2015-12-11 13:18:49.864 ThaliTest[658:807198] server session: connected
2015-12-11 13:18:49.864 ThaliTest[658:807198] server session: stateChange:1->2 Apple-Iphone5s-1_PT1055
,2015-12-11 13:18:49.870 ThaliTest[658:806153] server relay: connected (to port: 57307)
,2015-12-11T12:18:49.878Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T12:18:50.186Z SendDataTCPServer.js: TCP/IP server has received 15330 bytes of data
,2015-12-11T12:18:50.203Z SendDataTCPServer.js: TCP/IP server has received 41326 bytes of data
,2015-12-11T12:18:50.217Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T12:18:50.233Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 13:18:50.272 ThaliTest[658:807198] server session: not connected Apple-Iphone5s-1_PT1055
,2015-12-11 13:19:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:19:17.169 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:19:17.454 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:19:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:19:47.167 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:19:47.172 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:20:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:20:17.173 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:20:17.174 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:20:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:21:16.001 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:21:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:21:17.167 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:21:17.168 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:21:17.174 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:21:39.642 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:21:39.642 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 13:21:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:21:47.814 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:21:47.815 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:22:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:22:17.164 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:22:17.164 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:22:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:22:47.917 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:22:47.918 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:23:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:23:17.160 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:23:17.164 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:23:37.456 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:23:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:24:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:24:17.164 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:24:17.168 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:24:30.924 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:24:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:24:47.355 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:24:47.356 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:25:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:25:17.169 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:25:17.171 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:25:43.269 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:25:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:26:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:26:17.170 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:26:17.170 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:26:41.049 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:26:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:27:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:27:17.163 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:27:17.166 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:27:25.532 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:27:46.423 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:27:46.423 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 13:27:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:27:47.163 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:27:47.166 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:28:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:28:17.164 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:28:17.315 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:28:24.155 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:28:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:28:47.163 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:28:47.168 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:29:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:29:17.164 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:29:17.165 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:29:28.736 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:29:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:29:47.169 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:29:47.170 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:29:47.171 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:29:58.281 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:29:58.282 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 13:30:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:30:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:30:47.160 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:30:47.160 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:30:57.177 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:30:57.178 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:31:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:31:17.167 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:31:17.168 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:31:17.169 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:31:34.425 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:31:34.425 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 13:31:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:31:47.165 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:31:47.165 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:32:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:32:17.171 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:32:17.450 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:32:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:32:47.924 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:32:47.925 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:33:03.570 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:33:10.009 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:33:10.011 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-11 13:33:13.010 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:33:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:33:17.172 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:33:17.173 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,2015-12-11 13:33:17.255 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:33:42.549 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:33:42.550 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
,startWithNextDevice
,2015-12-11 13:33:47.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:33:47.164 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
2015-12-11 13:33:47.164 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
,2015-12-11 13:34:08.697 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-11 13:34:17.137 ThaliTest[658:806153] multipeer session: restart
,2015-12-11 13:34:17.172 ThaliTest[658:806153] client: found peer: Apple-IpadAir2-1_PT8639.AH2xbQ==
2015-12-11 13:34:17.172 ThaliTest[658:806153] client: found peer: Apple-Iphone5s-1_PT1055.SsV7MA==
,2015-12-11 13:34:17.180 ThaliTest[658:806153] client: found peer: Apple-Iphone6-1_PT7734.oRkpZA==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-11T12:34:34.200Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 13:34:36.482 ThaliTest[658:806153] client: lost peer: Apple-Iphone6-1_PT7734.oRkpZA==
2015-12-11 13:34:36.482 ThaliTest[658:806153] client session: onPeerLost: Apple-Iphone6-1_PT7734.oRkpZA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-I,phone6-1_PT7734.oRkpZA==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,teardown
,testSendData stopped
,2015-12-11 13:34:37.049 ThaliTest[658:806331] jxcore: stopBroadcasting
,2015-12-11 13:34:37.049 ThaliTest[658:806331] THEMultipeerSession stopping peer
2015-12-11 13:34:37.050 ThaliTest[658:806331] multipeer session: stop timer
2015-12-11 13:34:37.050 ThaliTest[658:806331] server session: disconnect
2015-12-11 13:34:37.050 ThaliTest[658:806331] server session: stateChange:2->0 Apple-Iphone6-1_PT7734
,2015-12-11 13:34:37.055 ThaliTest[658:806331] server session: disconnect
2015-12-11 13:34:37.056 ThaliTest[658:806331] server session: stateChange:2->0 Apple-IpadAir2-1_PT8639
2015-12-11 13:34:37.061 ThaliTest[658:806331] server session: disconnect
2015,-12-11 13:34:37.061 ThaliTest[658:806331] server session: stateChange:2->0 Apple-Iphone5s-1_PT1055
,2015-12-11 13:34:37.068 ThaliTest[658:806331] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-11T12:34:37.088Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:37.089Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:37.091Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-11T12:34:37.092Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
