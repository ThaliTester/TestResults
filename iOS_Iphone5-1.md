#### Test 52539314a265f91_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2BEC16FB-4841-457A-ABFA-47AA35F82CA5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/2BEC16FB-4841-457A-ABFA-47AA35F82CA5/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52539314a265f91/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/3884862E-9FE5-4317-AA0E-7EC5DF423D87/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61305"
,(lldb)     command script import "/tmp/2BEC16FB-4841-457A-ABFA-47AA35F82CA5/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-04 09:03:32.782 ThaliTest[1305:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-04 09:03:32.787 ThaliTest[1305:60b] Multi-tasking -> Device: YES, App: YES
2015-12-04 09:03:32.793 ThaliTest[1305:60b] Unlimited access to network resources
,2015-12-04 09:03:32.801 ThaliTest[1305:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.app,le.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-04 09:03:42.233 ThaliTest[1305:60b] Resetting plugins due to page load.
,2015-12-04 09:03:42.991 ThaliTest[1305:60b] Finished load of: file:///var/mobile/Applications/3884862E-9FE5-4317-AA0E-7EC5DF423D87/ThaliTest.app/www/index.html
,2015-12-04 09:03:43.173 ThaliTest[1305:60b] JXcore Cordova plugin initializing
,2015-12-04 09:03:43.176 ThaliTest[1305:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Radios toggled
,my name is : Apple-Iphone5-1_PT1372
,attempting to connect to test coordinator
,check test folder
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":,2,"addressList":[]}
Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 64950
,2015-12-04 09:09:27.675 ThaliTest[1305:6707] jxcore: startBroadcasting
,2015-12-04 09:09:27.688 ThaliTest[1305:6707] server: starting Apple-Iphone5-1_PT1372.xmPKsQ==
,2015-12-04 09:09:27.690 ThaliTest[1305:6707] multipeer session: start timer: 0x1a6bbd20
2015-12-04 09:09:27.692 ThaliTest[1305:6707] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1372
2015-12-04 09:09:27.693 ThaliTest[1305:6707] jxcore: startBroadcasting: success
StartBroadcasting started ok
2015-12-04T08:09:27.696Z SendDataTCPServer.js: TCP/IP server is bound to port: 64950
,2015-12-04 09:09:28.200 ThaliTest[1305:60b] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9579.WOzdIQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:09:28.204Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04T08:09:28.205Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9579.WOzdIQ==
2015-12-04T08:09:28.205Z SendDataConnector.js: do connect now
,2015-12-04 09:09:28.205 ThaliTest[1305:6707] jxcore: connect Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:28.206 ThaliTest[1305:6707] client session: connect
,2015-12-04 09:09:28.207 ThaliTest[1305:6707] client session: stateChange:0->1 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:28.478 ThaliTest[1305:60b] client: found peer: Apple-IpadAir2-1_PT2716.efpToQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT2716.efpToQ==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-04 09:09:30.773 ThaliTest[1305:6223] client session: connected
,2015-12-04 09:09:30.774 ThaliTest[1305:6223] client session: stateChange:1->2 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:30.800 ThaliTest[1305:6223] client session: fireConnectCallback: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:30.801 ThaliTest[1305:6223] jxcore: connect: success
,2015-12-04T08:09:30.803Z SendDataConnector.js: CLIENT connected to 64953, error: null
,2015-12-04T08:09:30.803Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:30.805 ThaliTest[1305:60b] client: relay established
2015-12-04 09:09:30.805 ThaliTest[1305:60b] client: new accepted socket: 0x1a5f7cf0
,2015-12-04T08:09:30.818Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:09:31.361Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-04T08:09:31.374Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-04T08:09:31.387Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-04T08:09:31.421Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-04T08:09:31.434Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-04T08:09:31.434Z SendDataConnector.js: got all data for this round
,2015-12-04T08:09:31.437Z SendDataConnector.js: CLIENT Stop now
,2015-12-04T08:09:31.437Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:09:31.439 ThaliTest[1305:6707] jxcore: disconnect
2015-12-04 09:09:31.440 ThaliTest[1305:6707] client session: disconnectFromPeer: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:31.441 ThaliTest[1305:6707] client session: disconnect
,2015-12-04 09:09:31.441 ThaliTest[1305:6707] client session: stateChange:2->0 Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:09:31.444 ThaliTest[1305:6707] jxcore: disconnect: success
2015-12-04T08:09:31.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9579.WOzdIQ==
---- round done--------
,device[2]: Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04T08:09:31.449Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04T08:09:31.449Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04T08:09:31.449Z SendDataConnector.js: do connect now
,2015-12-04 09:09:31.450 ThaliTest[1305:6707] jxcore: connect Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:31.451 ThaliTest[1305:6707] client session: connect
,2015-12-04 09:09:31.451 ThaliTest[1305:6707] client session: stateChange:0->1 Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:32.866 ThaliTest[1305:60b] multipeer session: reset timer
,2015-12-04 09:09:32.867 ThaliTest[1305:60b] multipeer session: stop timer
,2015-12-04 09:09:32.868 ThaliTest[1305:60b] multipeer session: start timer: 0x1a6bbd20
2015-12-04 09:09:32.869 ThaliTest[1305:60b] server session: connect
,2015-12-04 09:09:32.869 ThaliTest[1305:60b] server session: stateChange:0->1 Apple-Iphone6-1_PT9579
,2015-12-04 09:09:32.873 ThaliTest[1305:60b] server: accepting invitation Apple-Iphone6-1_PT9579
,2015-12-04 09:09:34.050 ThaliTest[1305:8303] client session: connected
,2015-12-04 09:09:34.051 ThaliTest[1305:8303] client session: stateChange:1->2 Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:34.058 ThaliTest[1305:8303] client session: fireConnectCallback: Apple-IpadAir2-1_PT2716.efpToQ==
2015-12-04 09:09:34.059 ThaliTest[1305:8303] jxcore: connect: success
,2015-12-04T08:09:34.060Z SendDataConnector.js: CLIENT connected to 64956, error: null
,2015-12-04T08:09:34.060Z SendDataConnector.js: CLIENT starting client 
,2015-12-04 09:09:34.062 ThaliTest[1305:60b] client: relay established
,2015-12-04 09:09:34.064 ThaliTest[1305:60b] client: new accepted socket: 0x1a6cfa60
,2015-12-04T08:09:34.074Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-04T08:09:34.639Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-04T08:09:35.193Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-04T08:09:35.193Z SendDataConnector.js: got all data for this round
,2015-12-04T08:09:35.195Z SendDataConnector.js: CLIENT Stop now
2015-12-04T08:09:35.195Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:09:35.197 ThaliTest[1305:6707] jxcore: disconnect
,2015-12-04 09:09:35.198 ThaliTest[1305:6707] client session: disconnectFromPeer: Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:35.198 ThaliTest[1305:6707] client session: disconnect
,2015-12-04 09:09:35.199 ThaliTest[1305:6707] client session: stateChange:2->0 Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:09:35.201 ThaliTest[1305:6707] jxcore: disconnect: success
2015-12-04T08:09:35.204Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT2716.efpToQ==
---- round done--------
weAreDoneNow , resultArray.length: 2
done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone5-1_PT1372","time":7540,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT9579.WOzdIQ==","time":3231,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT2716.efpToQ==","time":3745,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 3745 ms, 99% : 3745 ms, 95 : 3745 ms, 90% : 3745 ms.
Result count 2, range 3231 ms to  3745 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-04T08:09:35.213Z SendDataConnector.js: CLIENT Sto,p now
2015-12-04T08:09:35.213Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-04 09:09:35.628 ThaliTest[1305:750f] server session: connected
,2015-12-04 09:09:35.629 ThaliTest[1305:750f] server session: stateChange:1->2 Apple-Iphone6-1_PT9579
,2015-12-04 09:09:35.711 ThaliTest[1305:60b] server relay: connected (to port: 64950)
,2015-12-04T08:09:35.712Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:09:36.023Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-04T08:09:36.037Z SendDataTCPServer.js: TCP/IP server has received 27902 bytes of data
,2015-12-04T08:09:36.051Z SendDataTCPServer.js: TCP/IP server has received 58988 bytes of data
,2015-12-04T08:09:36.063Z SendDataTCPServer.js: TCP/IP server has received 78414 bytes of data
,2015-12-04T08:09:36.078Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:09:36.094 ThaliTest[1305:9d13] server session: not connected Apple-Iphone6-1_PT9579
,2015-12-04 09:10:02.870 ThaliTest[1305:60b] multipeer session: restart
,2015-12-04 09:10:32.870 ThaliTest[1305:60b] multipeer session: restart
,2015-12-04 09:10:32.879 ThaliTest[1305:60b] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:10:33.617 ThaliTest[1305:60b] client: found peer: Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:11:02.870 ThaliTest[1305:60b] multipeer session: restart
,2015-12-04 09:11:02.879 ThaliTest[1305:60b] client: found peer: Apple-Iphone6-1_PT9579.WOzdIQ==
,2015-12-04 09:11:03.563 ThaliTest[1305:60b] client: found peer: Apple-IpadAir2-1_PT2716.efpToQ==
,2015-12-04 09:11:16.198 ThaliTest[1305:60b] multipeer session: reset timer
2015-12-04 09:11:16.199 ThaliTest[1305:60b] multipeer session: stop timer
2015-12-04 09:11:16.200 ThaliTest[1305:60b] multipeer session: start timer: 0x1a6bbd20
,2015-12-04 09:11:16.201 ThaliTest[1305:60b] server session: connect
2015-12-04 09:11:16.201 ThaliTest[1305:60b] server session: stateChange:0->1 Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:16.205 ThaliTest[1305:60b] server: accepting invitation Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:18.918 ThaliTest[1305:9827] server session: connected
,2015-12-04 09:11:18.920 ThaliTest[1305:9827] server session: stateChange:1->2 Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:18.928 ThaliTest[1305:60b] server relay: connected (to port: 64950)
,2015-12-04T08:11:18.930Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-04T08:11:19.142Z SendDataTCPServer.js: TCP/IP server has received 6144 bytes of data
,2015-12-04T08:11:19.155Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-04T08:11:19.171Z SendDataTCPServer.js: TCP/IP server has received 82936 bytes of data
,2015-12-04T08:11:19.184Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-04 09:11:19.302 ThaliTest[1305:9213] server session: not connected Apple-IpadAir2-1_PT2716
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-04 09:11:20.684 ThaliTest[1305:6707] jxcore: stopBroadcasting
,2015-12-04 09:11:20.684 ThaliTest[1305:6707] THEMultipeerSession stopping peer
,2015-12-04 09:11:20.685 ThaliTest[1305:6707] multipeer session: stop timer
,2015-12-04 09:11:20.686 ThaliTest[1305:6707] server session: disconnect
2015-12-04 09:11:20.688 ThaliTest[1305:6707] server session: stateChange:2->0 Apple-IpadAir2-1_PT2716
,2015-12-04 09:11:20.692 ThaliTest[1305:6707] server session: disconnect
,2015-12-04 09:11:20.694 ThaliTest[1305:6707] server session: stateChange:2->0 Apple-Iphone6-1_PT9579
,2015-12-04 09:11:22.281 ThaliTest[1305:6707] jxcore: stopBroadcasting: success
StopBroadcasting went ok
,2015-12-04T08:11:22.296Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:11:22.298Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-04T08:11:22.298Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT9579.WOzdIQ==\",\"time\":3231,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT2716.efpToQ==\",\"time\":3745,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":3,"addressList":[]}
****TE,ST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
