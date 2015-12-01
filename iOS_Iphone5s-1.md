#### Test 522773652a05488_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DA71F5C5-833C-4CB1-AAD2-C087382A9E52/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DA71F5C5-833C-4CB1-AAD2-C087382A9E52/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/522773652a05488/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/12AC41A2-9A27-411D-8BC3-5704883565DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58618"
,(lldb)     command script import "/tmp/DA71F5C5-833C-4CB1-AAD2-C087382A9E52/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-01 17:20:47.452 ThaliTest[2200:2075973] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/34273878-D344-420C-A97C-0B003A313436/Library/Cookies/Cookies.binarycookies
,2015-12-01 17:20:47.878 ThaliTest[2200:2075973] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-01 17:20:47.879 ThaliTest[2200:2075973] Multi-tasking -> Device: YES, App: YES
,2015-12-01 17:20:47.889 ThaliTest[2200:2075973] Unlimited access to network resources
,2015-12-01 17:20:47.896 ThaliTest[2200:2075973] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-01 17:20:51.732 ThaliTest[2200:2075973] Resetting plugins due to page load.
,2015-12-01 17:20:52.213 ThaliTest[2200:2075973] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/12AC41A2-9A27-411D-8BC3-5704883565DA/ThaliTest.app/www/index.html
,2015-12-01 17:20:52.362 ThaliTest[2200:2075973] JXcore Cordova plugin initializing
,2015-12-01 17:20:52.363 ThaliTest[2200:2076106] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone5s-1_PT4380
,attempting to connect to test coordinator
check test folder
,found test : ./testFindPeers.js
,found test : ./testReConnect.js
,found test : ./testSendData.js
,Test app app.js loaded
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect_error called
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 64463
2015-12-01 17:26:56.003 ThaliTest[2200:2076106] jxcore: startBroadcasting
,2015-12-01 17:26:56.015 ThaliTest[2200:2076106] server: starting Apple-Iphone5s-1_PT4380.ZyAdcQ==
,2015-12-01 17:26:56.017 ThaliTest[2200:2076106] multipeer session: start timer: 0x1b5ab2e0
,2015-12-01 17:26:56.018 ThaliTest[2200:2076106] THEMultipeerSession initialized peer Apple-Iphone5s-1_PT4380
2015-12-01 17:26:56.027 ThaliTest[2200:2076106] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-01T16:26:56.031Z SendDataTCPServer.js: TCP/IP server is bound to port: 64463
,2015-12-01 17:26:56.687 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:26:56.688 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:26:56.690 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:26:56.691 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:26:56.692 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
,2015-12-01 17:26:56.704 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone6-1_PT8196
2015-12-01 17:26:56.711 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:26:56.712 ThaliTest[2200:2075973] multipeer session: stop tim,er
2015-12-01 17:26:56.712 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-12-01 17:26:56.713 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:26:56.713 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-,Iphone5-1_PT6379
2015-12-01 17:26:56.743 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:26:57.540 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:26:57.544 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Ipho,ne6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
2015-12-01 17:26:57.545 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
device[1]: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-,12-01T16:26:57.550Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:26:57.551Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01T16:26:57.552Z SendDataConnector.js: do connect now
,2015-12-01 17:26:57.552 ThaliTest[2200:2076106] jxcore: connect Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:26:57.553 ThaliTest[2200:2076106] client session: connect
2015-12-01 17:26:57.557 ThaliTest[2200:2076106] client session: stateChange:0->1 Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-01 17:26:58.882 ThaliTest[2200:2076664] server session: connected
2015-12-01 17:26:58.883 ThaliTest[2200:2076664] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:26:58.896 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:26:58.904Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 17:26:58.941 ThaliTest[2200:2076664] server session: connected
2015-12-01 17:26:58.942 ThaliTest[2200:2076664] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:26:59.149 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:26:59.161Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:26:59.203Z SendDataTCPServer.js: TCP/IP server has received 4238 bytes of data
,2015-12-01T16:26:59.217Z SendDataTCPServer.js: TCP/IP server has received 17236 bytes of data
,2015-12-01T16:26:59.234Z SendDataTCPServer.js: TCP/IP server has received 39420 bytes of data
,2015-12-01T16:26:59.252Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-01T16:26:59.268Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-01T16:26:59.288Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01T16:26:59.695Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-01T16:26:59.711Z SendDataTCPServer.js: TCP/IP server has received 15872 bytes of data
,2015-12-01T16:26:59.728Z SendDataTCPServer.js: TCP/IP server has received 27776 bytes of data
,2015-12-01T16:26:59.744Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-12-01T16:26:59.760Z SendDataTCPServer.js: TCP/IP server has received 43648 bytes of data
,2015-12-01T16:26:59.773Z SendDataTCPServer.js: TCP/IP server has received 53568 bytes of data
,2015-12-01T16:26:59.786Z SendDataTCPServer.js: TCP/IP server has received 61504 bytes of data
,2015-12-01T16:26:59.800Z SendDataTCPServer.js: TCP/IP server has received 73408 bytes of data
,2015-12-01T16:26:59.813Z SendDataTCPServer.js: TCP/IP server has received 86304 bytes of data
,2015-12-01T16:26:59.828Z SendDataTCPServer.js: TCP/IP server has received 99200 bytes of data
,2015-12-01T16:26:59.841Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:26:59.890 ThaliTest[2200:2076654] client session: connected
2015-12-01 17:26:59.891 ThaliTest[2200:2076654] client session: stateChange:1->2 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:26:59.903 ThaliTest[2200:2076654] client session: fireConnectCallback: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:26:59.904 ThaliTest[2200:2076654] jxcore: connect: success
,2015-12-01T16:26:59.905Z SendDataConnector.js: CLIENT connected to 64468, error: null
,2015-12-01T16:26:59.906Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:26:59.911 ThaliTest[2200:2075973] client: relay established
2015-12-01 17:26:59.912 ThaliTest[2200:2075973] client: new accepted socket: 0x1b656c80
,2015-12-01T16:26:59.927Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:27:00.241Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T16:27:00.241Z SendDataConnector.js: got all data for this round
,2015-12-01T16:27:00.243Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:27:00.243Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 17:27:00.243 ThaliTest[2200:2076106] jxcore: disconnect
,2015-12-01 17:27:00.244 ThaliTest[2200:2076106] client session: disconnectFromPeer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:27:00.244 ThaliTest[2200:2076106] client session: disconnect
2015-12-01 17:27:00.245 ThaliTest[2200:2076106] client session: stateChange:2->0 Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:27:00.246 ThaliTest[2200:2076106] jxcore: disconnect: success
2015-12-01T16:27:00.246Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8196.sJeqaQ==
,---- round done--------
,device[2]: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:27:00.251Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:27:00.252Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01T16:27:00.252Z SendDataConnector.js: do connect now
,2015-12-01 17:27:00.253 ThaliTest[2200:2076106] jxcore: connect Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:27:00.254 ThaliTest[2200:2076106] client session: connect
,2015-12-01 17:27:00.254 ThaliTest[2200:2076106] client session: stateChange:0->1 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:27:00.918 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:00.918 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:00.919 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:00.920 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:00.921 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:00.932 ThaliTest[2200:2075973] server: accepting invitation Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:02.864 ThaliTest[2200:2076705] client session: connected
2015-12-01 17:27:02.864 ThaliTest[2200:2076705] client session: stateChange:1->2 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:27:02.874 ThaliTest[2200:2076654] client session: fireConnectCallback: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:27:02.875 ThaliTest[2200:2076654] jxcore: connect: success
2015-12-01T16:27:02.877Z SendDataConnector.js: CLIENT connected to 64471, error: null
2015-12-01T16:27:02.878Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:02.883 ThaliTest[2200:2075973] client: relay established
2015-12-01 17:27:02.883 ThaliTest[2200:2075973] client: new accepted socket: 0x1b660310
,2015-12-01T16:27:02.895Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:27:03.301Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-01T16:27:03.326Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-01T16:27:03.326Z SendDataConnector.js: got all data for this round
,2015-12-01T16:27:03.327Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:27:03.327Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:27:03.328 ThaliTest[2200:2076106] jxcore: disconnect
,2015-12-01 17:27:03.328 ThaliTest[2200:2076106] client session: disconnectFromPeer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:27:03.329 ThaliTest[2200:2076106] client session: disconnect
2015-12-01 17:27:03.329 ThaliTest[2200:2076106] client session: stateChange:2->0 Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:27:03.331 ThaliTest[2200:2076106] jxcore: disconnect: success
2015-12-01T16:27:03.332Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT6379.NUteEA==
---- round done--------
,device[3]: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01T16:27:03.334Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01T16:27:03.334Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01T16:27:03.334Z SendDataConnector.js: do connect now
,2015-12-01 17:27:03.335 ThaliTest[2200:2076106] jxcore: connect Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:27:03.335 ThaliTest[2200:2076106] client session: connect
2015-12-01 17:27:03.335 ThaliTest[2200:2076106] client session: stateChange:0->1 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:27:03.338 ThaliTest[2200:2076661] server session: connected
2015-12-01 17:27:03.338 ThaliTest[2200:2076661] server session: stateChange:1->2 Apple-IpadAir2-1_PT7863
,2015-12-01T16:27:03.353Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01 17:27:03.355 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:27:03.596Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-01T16:27:03.834Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-01T16:27:03.846Z SendDataTCPServer.js: TCP/IP server has received 26280 bytes of data
,2015-12-01T16:27:03.872Z SendDataTCPServer.js: TCP/IP server has received 50370 bytes of data
,2015-12-01T16:27:03.884Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-01T16:27:03.923Z SendDataTCPServer.js: TCP/IP server has received 70080 bytes of data
,2015-12-01T16:27:03.933Z SendDataTCPServer.js: TCP/IP server has received 87600 bytes of data
,2015-12-01T16:27:03.947Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-01 17:27:07.142 ThaliTest[2200:2076661] client session: connected
2015-12-01 17:27:07.143 ThaliTest[2200:2076661] client session: stateChange:1->2 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:27:07.150 ThaliTest[2200:2076654] client session: fireConnectCallback: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:27:07.151 ThaliTest[2200:2076654] jxcore: connect: success
2015-12-01T16:27:07.153Z SendDataConnector.js: CLIENT connected to 64475, error: null
,2015-12-01T16:27:07.153Z SendDataConnector.js: CLIENT starting client 
,2015-12-01 17:27:07.159 ThaliTest[2200:2075973] client: relay established
2015-12-01 17:27:07.159 ThaliTest[2200:2075973] client: new accepted socket: 0x1b0e2520
,2015-12-01T16:27:07.171Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-01T16:27:07.476Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-01T16:27:07.502Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-01T16:27:07.538Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-01T16:27:07.587Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-01T16:27:07.588Z SendDataConnector.js: got all data for this round
,2015-12-01T16:27:07.588Z SendDataConnector.js: CLIENT Stop now
2015-12-01T16:27:07.589Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-01 17:27:07.589 ThaliTest[2200:2076106] jxcore: disconnect
2015-12-01 17:27:07.589 ThaliTest[2200:2076106] client session: disconnectFromPeer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:27:07.589 ThaliTest[2200:2076106] client session: disconnect
2015-12-01 17:27:07.590 ThaliTest[2200:2076106] client session: stateChange:2->0 Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:27:07.592 ThaliTest[2200:2076106] jxcore: disconnect: success
2015-12-01T16:27:07.592Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT7863.GmxszQ==
---- round done--------
weAreDoneNow , resultArray.length:, 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5s-1_PT4380","time":11606,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8196.sJeqaQ==","time":2692,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT6379.NUteEA==","time":3074,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT7863.GmxszQ==","time":4254,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 4254 ms, 99% : 4254 ms, 95 : 4254 ms, 90% : 4254 ms.
,Result count 3, range 2692 ms to  4254 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-01T16:27:07.598Z SendDataConnector.js: CLIENT Stop now
,2015-12-01T16:27:07.598Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-01 17:27:09.566 ThaliTest[2200:2076654] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:27:10.127 ThaliTest[2200:2076654] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:27:14.997 ThaliTest[2200:2076654] server session: not connected Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:19.923 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:19.924 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:19.924 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:19.925 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone6-1_PT8196)
2015-12-01 17:27:19.925 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:19.926 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8196
2015-12-01 17:27:19.931 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:19.932 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
2015-12-01T16:27:19.933Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-01 17:27:19.942 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone6-1_PT8196
,2015-12-01 17:27:20.069 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:20.069 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:20.070 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:20.071 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone5-1_PT6379)
2015-12-01 17:27:20.072 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:20.072 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6379
,2015-12-01T16:27:20.087Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 17:27:20.135 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:20.136 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
,2015-12-01 17:27:20.140 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:27:22.148 ThaliTest[2200:2076741] server session: connected
2015-12-01 17:27:22.148 ThaliTest[2200:2076741] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:27:22.158 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
2015-12-01T16:27:22.160Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:22.257Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:22.300 ThaliTest[2200:2076664] server session: connected
2015-12-01 17:27:22.301 ThaliTest[2200:2076664] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:27:22.312 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:27:22.320Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:22.397Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:27.038 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:27.039 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:27.040 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:27.040 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7863)
2015-12-01 17:27:27.041 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:27.041 ThaliTest[2200:2075973] server session: state,Change:2->0 Apple-IpadAir2-1_PT7863
,2015-12-01T16:27:27.054Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 17:27:27.107 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:27.108 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:27.115 ThaliTest[2200:2075973] server: accepting invitation Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:29.649 ThaliTest[2200:2076752] server session: connected
2015-12-01 17:27:29.650 ThaliTest[2200:2076752] server session: stateChange:1->2 Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:29.662 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:27:29.671Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:30.024Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:32.263 ThaliTest[2200:2076741] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:27:32.648 ThaliTest[2200:2076741] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:27:39.963 ThaliTest[2200:2076665] server session: not connected Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:42.748 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:42.749 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:42.749 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:42.750 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone6-1_PT8196)
2015-12-01 17:27:42.751 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:42.752 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8196
2015-12-01 17:27:42.756 ThaliTest[2200:2075973] server session: connect
2015-12-01T16:27:42.760Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01 17:27:42.757 ThaliTest[2200:2075973] server session: stateChange:0,->1 Apple-Iphone6-1_PT8196
,2015-12-01 17:27:42.778 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone6-1_PT8196
,2015-12-01 17:27:43.188 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:43.189 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:43.190 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:43.191 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone5-1_PT6379)
2015-12-01 17:27:43.191 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:43.192 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6379
2015-12-01 17:27:43.195 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:43.196 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
2015-12-01T16:27:43.198Z SendDataTCPServer.,js: TCP/IP server is ended
,2015-12-01 17:27:43.207 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:27:44.954 ThaliTest[2200:2076791] server session: connected
2015-12-01 17:27:44.955 ThaliTest[2200:2076791] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:27:44.967 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
2015-12-01T16:27:44.971Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:45.063Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-01T16:27:45.076Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:45.867 ThaliTest[2200:2076791] server session: connected
2015-12-01 17:27:45.867 ThaliTest[2200:2076791] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:27:45.896 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:27:45.909Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:45.960Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-01T16:27:45.972Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:50.187 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:27:50.188 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:27:50.188 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:27:50.189 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-IpadAir2-1_PT7863)
2015-12-01 17:27:50.189 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:27:50.190 ThaliTest[2200:2075973] server session: state,Change:2->0 Apple-IpadAir2-1_PT7863
2015-12-01 17:27:50.194 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:27:50.194 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-IpadAir2-1_PT7863
2015-12-01T16:27:50.197Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-01 17:27:50.205 ThaliTest[2200:2075973] server: accepting invitation Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:52.678 ThaliTest[2200:2076790] server session: connected
2015-12-01 17:27:52.678 ThaliTest[2200:2076790] server session: stateChange:1->2 Apple-IpadAir2-1_PT7863
,2015-12-01 17:27:53.266 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
2015-12-01T16:27:53.270Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:27:53.283Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:27:55.166 ThaliTest[2200:2076799] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:27:56.252 ThaliTest[2200:2076799] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:27:59.360 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:03.026 ThaliTest[2200:2076799] server session: not connected Apple-IpadAir2-1_PT7863
,2015-12-01 17:28:06.319 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:28:06.320 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:28:06.321 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:28:06.321 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone6-1_PT8196)
2015-12-01 17:28:06.322 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:28:06.322 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8196
2015-12-01 17:28:06.326 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:28:06.326 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
,2015-12-01T16:28:06.333Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 17:28:06.336 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone6-1_PT8196
,2015-12-01 17:28:06.770 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:28:06.770 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:28:06.771 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:28:06.772 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone5-1_PT6379)
2015-12-01 17:28:06.772 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:28:06.773 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:06.777 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:28:06.778 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
2015-12-01T16:28:06.778Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 17:28:06.788 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:28:08.454 ThaliTest[2200:2076790] server session: connected
,2015-12-01 17:28:08.455 ThaliTest[2200:2076790] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:28:08.462 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:28:08.466Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:08.560Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-01T16:28:08.575Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:28:08.984 ThaliTest[2200:2076665] server session: connected
2015-12-01 17:28:08.984 ThaliTest[2200:2076665] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:08.996 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
,2015-12-01T16:28:09.007Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:09.073Z SendDataTCPServer.js: TCP/IP server has received 3968 bytes of data
,2015-12-01T16:28:09.087Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:28:18.752 ThaliTest[2200:2076918] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:28:19.275 ThaliTest[2200:2076918] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:28:29.105 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:28:29.106 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:28:29.107 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:28:29.107 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone6-1_PT8196)
2015-12-01 17:28:29.108 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:28:29.108 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone6-1_PT8196
2015-12-01 17:28:29.112 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:28:29.113 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone6-1_PT8196
,2015-12-01T16:28:29.119Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-01 17:28:29.124 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone6-1_PT8196
2015-12-01 17:28:29.126 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:28:29.260 ThaliTest[2200:2075973] multipeer session: reset timer
2015-12-01 17:28:29.261 ThaliTest[2200:2075973] multipeer session: stop timer
2015-12-01 17:28:29.261 ThaliTest[2200:2075973] multipeer session: start timer: 0x1b5ab2e0
2015-,12-01 17:28:29.262 ThaliTest[2200:2075973] server: disconnecting to refresh session (Apple-Iphone5-1_PT6379)
2015-12-01 17:28:29.262 ThaliTest[2200:2075973] server session: disconnect
2015-12-01 17:28:29.263 ThaliTest[2200:2075973] server session: stateC,hange:2->0 Apple-Iphone5-1_PT6379
2015-12-01 17:28:29.267 ThaliTest[2200:2075973] server session: connect
2015-12-01 17:28:29.268 ThaliTest[2200:2075973] server session: stateChange:0->1 Apple-Iphone5-1_PT6379
,2015-12-01T16:28:29.280Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-01 17:28:29.287 ThaliTest[2200:2075973] server: accepting invitation Apple-Iphone5-1_PT6379
,2015-12-01 17:28:31.346 ThaliTest[2200:2076996] server session: connected
2015-12-01 17:28:31.347 ThaliTest[2200:2076996] server session: stateChange:1->2 Apple-Iphone6-1_PT8196
,2015-12-01 17:28:31.360 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
2015-12-01T16:28:31.368Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:31.420Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-01T16:28:31.434Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:28:31.460 ThaliTest[2200:2076918] server session: connected
,2015-12-01 17:28:31.460 ThaliTest[2200:2076918] server session: stateChange:1->2 Apple-Iphone5-1_PT6379
,2015-12-01 17:28:31.471 ThaliTest[2200:2075973] server relay: connected (to port: 64463)
2015-12-01T16:28:31.475Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-01T16:28:31.547Z SendDataTCPServer.js: TCP/IP server has received 992 bytes of data
,2015-12-01T16:28:31.563Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-01 17:28:41.435 ThaliTest[2200:2076996] server session: not connected Apple-Iphone6-1_PT8196
,2015-12-01 17:28:47.605 ThaliTest[2200:2077120] server session: not connected Apple-Iphone5-1_PT6379
,2015-12-01 17:28:59.263 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:28:59.373 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:28:59.374 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:28:59.376 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:29:19.032 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:26.502 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:29.263 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:29:29.286 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:29.289 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:29:29.291 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:29:56.430 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:29:59.263 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:29:59.288 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:29:59.290 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:29:59.291 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:17.351 ThaliTest[2200:2075973] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:30:17.352 ThaliTest[2200:2075973] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"App,le-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
2015-12-01 17:30:17.354 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:30:26.650 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:30:29.263 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:30:29.286 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:30:29.287 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:30:29.290 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:30:56.527 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:30:59.263 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:30:59.289 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:30:59.290 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:30:59.291 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:31:17.491 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:31:29.261 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:31:29.283 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:31:29.287 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:31:29.288 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:31:50.991 ThaliTest[2200:2075973] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:31:50.992 ThaliTest[2200:2075973] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:31:52.086 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:31:59.260 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:31:59.372 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:31:59.374 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:31:59.375 ThaliTest[2200:2075973] clien,t: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:32:29.261 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:32:29.289 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:29.290 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:29.291 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:32:56.571 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
,2015-12-01 17:32:59.261 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:32:59.283 ThaliTest[2200:2075973] client: found peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:32:59.285 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:32:59.287 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:33:01.213 ThaliTest[2200:2075973] client: lost peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:33:01.214 ThaliTest[2200:2075973] client session: onPeerLost: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"A,pple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:33:06.504 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT7863.GmxszQ==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:33:15.950 ThaliTest[2200:2075973] client: lost peer: Apple-Iphone6-1_PT8196.sJeqaQ==
2015-12-01 17:33:15.951 ThaliTest[2200:2075973] client session: onPeerLost: Apple-Iphone6-1_PT8196.sJeqaQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8196.sJeqaQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:33:29.261 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:33:29.283 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:33:29.285 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:33:59.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:33:59.281 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:33:59.282 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:34:29.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:34:29.282 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:34:29.284 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:34:59.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:34:59.280 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:34:59.283 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:35:29.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:35:29.279 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
2015-12-01 17:35:29.280 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:35:59.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:35:59.279 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:35:59.282 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:36:21.502 ThaliTest[2200:2075973] client: lost peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:36:21.503 ThaliTest[2200:2075973] client session: onPeerLost: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":false}]
,2015-12-01 17:36:23.603 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT6379.NUteEA==","peerName":"(null)","peerAvailable":true}]
,2015-12-01 17:36:29.259 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:36:29.321 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:36:29.324 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-01 17:36:59.266 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:36:59.372 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:37:00.381 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:37:29.266 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:37:29.287 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:37:29.288 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:37:59.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:37:59.290 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:37:59.291 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:38:29.266 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:38:29.288 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:38:29.291 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:38:59.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:38:59.285 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:38:59.288 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:39:29.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:39:29.287 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:39:30.346 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:39:59.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:39:59.286 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:39:59.289 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:40:29.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:40:29.287 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:40:30.057 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:40:59.265 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:40:59.381 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:40:59.455 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:41:29.264 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:41:29.283 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
2015-12-01 17:41:29.286 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:41:59.264 ThaliTest[2200:2075973] multipeer session: restart
,2015-12-01 17:41:59.290 ThaliTest[2200:2075973] client: found peer: Apple-Iphone5-1_PT6379.NUteEA==
,2015-12-01 17:42:00.187 ThaliTest[2200:2075973] client: found peer: Apple-IpadAir2-1_PT7863.GmxszQ==
,2015-12-01 17:42:29.263 ThaliTest[2200:2075973] multipeer session: restart
2015-12-01 17:42:29.270 ThaliTest[2200:2075973] *** Terminating app due to uncaught exception 'NSInvalidArgumentException', reason: '*** setObjectForKey: key cannot be nil'
*** Fi,rst throw call stack:
(0x2a8a745f 0x3876ac8b 0x2a7c4c53 0x2c829d95 0x2a3c4297 0x2a3c3b11 0x2a33d693 0x2a86dfbf 0x2a86d3cf 0x2a86ba35 0x2a7b93b1 0x2a7b91c3 0x31da6201 0x2de2343d 0x875e3 0x38cf6aaf)
libc++abi.dylib: terminating with uncaught exception of t,ype NSException
,Process 2200 stopped
* thread #1: tid = 0x1fad45, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
    frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x38dc0df0 <+8>:  blo    0x38dc0e08                ; <+32>
    0x38dc0df4 <+12>: ldr    r12, [pc, #0x4]           ; <+24>
    0x38dc0df8 <+16>: ldr    r12, [pc, r12]
    0x38dc0dfc <+20>: b      0x38dc0e04                ; <+28>
,* thread #1: tid = 0x1fad45, 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.main-thread', stop reason = signal SIGABRT
  * frame #0: 0x38dc0df0 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x38e3ecc6 libsystem_pthread.dylib`pthread_kill + 62
    frame #2: 0x38d5c908 libsystem_c.dylib`abort + 76
    frame #3: 0x3808c9c8 libc++abi.dylib`<redacted> + 88
    frame #4: 0x380a6670 libc++abi.dylib`<redacted> + 268
    frame #5: 0x3876af24 libobjc.A.dylib`<redacted> + 192
    frame #6: 0x380a3de2 libc++abi.dylib`<redacted> + 78
    frame #7: 0x380a38ae libc++abi.dylib`__cxa_rethrow + 102
    frame #8: 0x3876add2 libobjc.A.dylib`objc_exception_rethrow + 42
    frame #9: 0x2a7b944c CoreFoundation`CFRunLoopRunSpecific + 632
    frame #10: 0x2a7b91c2 CoreFoundation`CFRunLoopRunInMode + 106
    frame #11: 0x31da6200 GraphicsServices`GSEventRunModal + 136
    frame #12: 0x2de2343c UIKit`UIApplicationMain + 1440
    frame #13: 0x000875e2 ThaliTest`main + 50

```
