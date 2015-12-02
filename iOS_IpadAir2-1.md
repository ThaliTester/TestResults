#### Test 51986340441e256_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0B023C7D-AB8B-49D9-B7C8-FF68A845B690/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0B023C7D-AB8B-49D9-B7C8-FF68A845B690/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51986340441e256/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/10DC8F40-6349-4937-9006-9753360EF3AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59781"
,(lldb)     command script import "/tmp/0B023C7D-AB8B-49D9-B7C8-FF68A845B690/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 18:55:03.209 ThaliTest[1809:2848374] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/43FE21B0-6DB2-415E-8CDD-0CBE70B38B42/Library/Cookies/Cookies.binarycookies
,2015-12-02 18:55:03.497 ThaliTest[1809:2848374] Apache Cordova native platform version 3.9.2 is starting.
2015-12-02 18:55:03.498 ThaliTest[1809:2848374] Multi-tasking -> Device: YES, App: YES
,2015-12-02 18:55:03.504 ThaliTest[1809:2848374] Unlimited access to network resources
,2015-12-02 18:55:03.510 ThaliTest[1809:2848374] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 18:55:07.690 ThaliTest[1809:2848374] Resetting plugins due to page load.
,2015-12-02 18:55:09.124 ThaliTest[1809:2848374] Finished load of: file:///var/mobile/Containers/Bundle/Application/10DC8F40-6349-4937-9006-9753360EF3AF/ThaliTest.app/www/index.html
,2015-12-02 18:55:09.268 ThaliTest[1809:2848374] JXcore Cordova plugin initializing
,2015-12-02 18:55:09.269 ThaliTest[1809:2848546] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT8086
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
Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 65399
,2015-12-02 19:01:52.251 ThaliTest[1809:2848546] jxcore: startBroadcasting
,2015-12-02 19:01:52.257 ThaliTest[1809:2848546] server: starting Apple-IpadAir2-1_PT8086.XWQOsA==
,2015-12-02 19:01:52.259 ThaliTest[1809:2848546] multipeer session: start timer: 0x19d97e30
2015-12-02 19:01:52.259 ThaliTest[1809:2848546] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8086
2015-12-02 19:01:52.260 ThaliTest[1809:2848546] jxcore,: startBroadcasting: success
,StartBroadcasting started ok
2015-12-02T18:01:52.263Z SendDataTCPServer.js: TCP/IP server is bound to port: 65399
,2015-12-02 19:01:52.945 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02T18:01:52.949Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02T18:01:52.949Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02T18:01:52.950Z SendDataConnector.js: do connect now
,2015-12-02 19:01:52.950 ThaliTest[1809:2848546] jxcore: connect Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:52.950 ThaliTest[1809:2848546] client session: connect
,2015-12-02 19:01:52.951 ThaliTest[1809:2848546] client session: stateChange:0->1 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:53.928 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT1792.Nse+hg==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-02 19:01:55.076 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
,2015-12-02 19:01:56.232 ThaliTest[1809:2848374] multipeer session: reset timer
2015-12-02 19:01:56.232 ThaliTest[1809:2848374] multipeer session: stop timer
,2015-12-02 19:01:56.233 ThaliTest[1809:2848374] multipeer session: start timer: 0x19d97e30
,2015-12-02 19:01:56.233 ThaliTest[1809:2848374] server session: connect
2015-12-02 19:01:56.233 ThaliTest[1809:2848374] server session: stateChange:0->1 Apple-Iphone5-1_PT1792
,2015-12-02 19:01:56.236 ThaliTest[1809:2848374] server: accepting invitation Apple-Iphone5-1_PT1792
,2015-12-02 19:01:57.534 ThaliTest[1809:2849362] client session: connected
2015-12-02 19:01:57.534 ThaliTest[1809:2849362] client session: stateChange:1->2 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:57.544 ThaliTest[1809:2849357] client session: fireConnectCallback: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:57.544 ThaliTest[1809:2849357] jxcore: connect: success
,2015-12-02T18:01:57.544Z SendDataConnector.js: CLIENT connected to 65402, error: null
2015-12-02T18:01:57.545Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:01:57.546 ThaliTest[1809:2848374] client: relay established
2015-12-02 19:01:57.546 ThaliTest[1809:2848374] client: new accepted socket: 0x19d9ede0
,2015-12-02T18:01:57.560Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:01:58.015Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:01:58.063Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-02T18:01:58.077Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:01:58.101Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-02T18:01:58.127Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T18:01:58.127Z SendDataConnector.js: got all data for this round
,2015-12-02T18:01:58.128Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:01:58.128Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:01:58.129 ThaliTest[1809:2848546] jxcore: disconnect
2015-12-02 19:01:58.129 ThaliTest[1809:2848546] client session: disconnectFromPeer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:01:58.129 ThaliTest[1809:2848546] client session: disconnect
2015-12-02 19:01:58.129 ThaliTest[1809:2848546] client session: stateChange:2->0 Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:01:58.133 ThaliTest[1809:2848546] jxcore: disconnect: success
2015-12-02T18:01:58.133Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT3324.ZgTNhQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.135Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.135Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02T18:01:58.135Z SendDataConnector.js: do connect now
,2015-12-02 19:01:58.136 ThaliTest[1809:2848546] jxcore: connect Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:01:58.138 ThaliTest[1809:2848546] client session: connect
2015-12-02 19:01:58.138 ThaliTest[1809:2848546] client session: stateChange:0->1 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:01:59.119 ThaliTest[1809:2849357] server session: connected
2015-12-02 19:01:59.119 ThaliTest[1809:2849357] server session: stateChange:1->2 Apple-Iphone5-1_PT1792
,2015-12-02 19:01:59.142 ThaliTest[1809:2848374] server relay: connected (to port: 65399)
,2015-12-02T18:01:59.144Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:01:59.638Z SendDataTCPServer.js: TCP/IP server has received 9920 bytes of data
,2015-12-02T18:01:59.651Z SendDataTCPServer.js: TCP/IP server has received 15872 bytes of data
,2015-12-02T18:01:59.784Z SendDataTCPServer.js: TCP/IP server has received 35712 bytes of data
,2015-12-02T18:01:59.795Z SendDataTCPServer.js: TCP/IP server has received 74400 bytes of data
,2015-12-02T18:01:59.809Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-12-02T18:01:59.835Z SendDataTCPServer.js: TCP/IP server has received 85312 bytes of data
,2015-12-02T18:01:59.848Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:00.226 ThaliTest[1809:2849354] server session: not connected Apple-Iphone5-1_PT1792
,2015-12-02 19:02:00.835 ThaliTest[1809:2849354] client session: connected
,2015-12-02 19:02:00.835 ThaliTest[1809:2849354] client session: stateChange:1->2 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:00.845 ThaliTest[1809:2849357] client session: fireConnectCallback: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:00.846 ThaliTest[1809:2849357] jxcore: connect: success
,2015-12-02T18:02:00.846Z SendDataConnector.js: CLIENT connected to 65406, error: null
,2015-12-02T18:02:00.847Z SendDataConnector.js: CLIENT starting client 
,2015-12-02 19:02:00.848 ThaliTest[1809:2848374] client: relay established
2015-12-02 19:02:00.848 ThaliTest[1809:2848374] client: new accepted socket: 0x1b056850
,2015-12-02T18:02:00.861Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:02:01.168Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-02T18:02:01.180Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:02:01.193Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-02T18:02:01.206Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-02T18:02:01.219Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-02T18:02:01.219Z SendDataConnector.js: got all data for this round
,2015-12-02T18:02:01.220Z SendDataConnector.js: CLIENT Stop now
2015-12-02T18:02:01.220Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:01.221 ThaliTest[1809:2848546] jxcore: disconnect
2015-12-02 19:02:01.221 ThaliTest[1809:2848546] client session: disconnectFromPeer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:01.221 ThaliTest[1809:2848546] client session: disconn,ect
2015-12-02 19:02:01.221 ThaliTest[1809:2848546] client session: stateChange:2->0 Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:02:01.225 ThaliTest[1809:2848546] jxcore: disconnect: success
2015-12-02T18:02:01.226Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT1792.Nse+hg==
---- round done--------
device[3]: Apple-Iphone6-1_PT8308.Z,3UjCg==
2015-12-02T18:02:01.226Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02T18:02:01.226Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02T18:02:01.226Z SendDataConnector.js: do connect now
2015-12-02 19:02:01.227 ThaliTest[1809:2848546] jxcore: connect Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:01.227 ThaliTest[1809:2848546] client session: connect
,2015-12-02 19:02:01.228 ThaliTest[1809:2848546] client session: stateChange:0->1 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:04.353 ThaliTest[1809:2848374] multipeer session: reset timer
2015-12-02 19:02:04.353 ThaliTest[1809:2848374] multipeer session: stop timer
2015-12-02 19:02:04.353 ThaliTest[1809:2848374] multipeer session: start timer: 0x19d97e30
2015-12-02 19:02:04.353 ThaliTest[1809:2848374] server session: connect
2015-12-02 19:02:04.353 ThaliTest[1809:2848374] server session: stateChange:0->1 Apple-Iphone6-1_PT8308
,2015-12-02 19:02:04.356 ThaliTest[1809:2849357] client session: connected
2015-12-02 19:02:04.356 ThaliTest[1809:2849357] client session: stateChange:1->2 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:04.359 ThaliTest[1809:2848374] server: accepting invitation Apple-Iphone6-1_PT8308
,2015-12-02 19:02:04.366 ThaliTest[1809:2849354] client session: fireConnectCallback: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:02:04.366 ThaliTest[1809:2849354] jxcore: connect: success
2015-12-02T18:02:04.367Z SendDataConnector.js: CLIENT connected to 65410, error: null
2015-12-02T18:02:04.367Z SendDataConnector.js: CLIENT starting client 
2015-12-02 19:02:04.368 ThaliTest[1809:2848374] client: relay established
2015-12-02 19:02:04.368 ThaliTest[1809:2848374] client: new accepted socket: 0x19d9a2a0
,2015-12-02T18:02:04.381Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-02T18:02:04.891Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-02T18:02:04.917Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-02T18:02:04.943Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-02T18:02:04.979Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-02T18:02:04.980Z SendDataConnector.js: got all data for this round
,2015-12-02T18:02:04.981Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T18:02:04.981Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:04.981 ThaliTest[1809:2848546] jxcore: disconnect
,2015-12-02 19:02:04.982 ThaliTest[1809:2848546] client session: disconnectFromPeer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:04.982 ThaliTest[1809:2848546] client session: disconnect
,2015-12-02 19:02:04.983 ThaliTest[1809:2848546] client session: stateChange:2->0 Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:05.048 ThaliTest[1809:2848546] jxcore: disconnect: success
2015-12-02T18:02:05.048Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8308.Z3UjCg==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT8086","time":12802,"result":"OK","sendList":[{"name":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","time":5178,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1,_PT1792.Nse+hg==","time":3084,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT8308.Z3UjCg==","time":3754,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]}
,sendList : 100% : 5178 ms, 99% : 5178 ms, 95 : 5178 ms, 90% : 5178 ms.
,Result count 3, range 3084 ms to  5178 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 0 [0 %]
,2015-12-02T18:02:05.053Z SendDataConnector.js: CLIENT Stop now
,2015-12-02T18:02:05.053Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-02 19:02:07.044 ThaliTest[1809:2849397] server session: connected
2015-12-02 19:02:07.044 ThaliTest[1809:2849397] server session: stateChange:1->2 Apple-Iphone6-1_PT8308
,2015-12-02 19:02:07.100 ThaliTest[1809:2848374] server relay: connected (to port: 65399)
,2015-12-02T18:02:07.110Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-02T18:02:07.433Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-02T18:02:07.445Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-02T18:02:07.460Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-02 19:02:07.499 ThaliTest[1809:2849362] server session: not connected Apple-Iphone6-1_PT8308
,2015-12-02 19:02:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:02:34.366 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:02:34.366 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:02:34.771 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
,2015-12-02 19:03:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:03:04.364 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:03:04.364 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:03:04.365 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:03:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:03:34.365 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:03:34.366 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:03:34.366 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:03:59.760 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone5s-1_PT3324.ZgTNhQ==
2015-12-02 19:03:59.760 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone5s-1_PT3324.ZgTNhQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT3324.ZgTNhQ==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:04:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:04:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:04:34.780 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:04:36.816 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:04:41.066 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:04:41.067 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:04:44.177 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:05:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:05:04.365 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:05:04.807 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:05:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:05:34.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:05:34.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:06:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:06:04.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:06:04.465 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:06:34.740 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:06:34.741 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:06:40.743 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:06:40.743 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:07:02.643 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:07:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:07:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:07:34.542 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:07:36.196 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:08:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:08:04.364 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:08:04.364 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:08:10.891 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:08:10.891 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:08:33.332 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:08:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:08:34.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
2015-12-02 19:08:34.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:09:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:09:04.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:09:04.364 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:09:11.039 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:09:11.039 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:09:32.643 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":true}]
,2015-12-02 19:09:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:09:34.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:09:34.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
,2015-12-02 19:10:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:10:04.365 ThaliTest[1809:2848374] client: found peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:10:04.365 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:10:05.454 ThaliTest[1809:2848374] client: lost peer: Apple-Iphone6-1_PT8308.Z3UjCg==
2015-12-02 19:10:05.454 ThaliTest[1809:2848374] client session: onPeerLost: Apple-Iphone6-1_PT8308.Z3UjCg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8308.Z3UjCg==","peerName":"(null)","peerAvailable":false}]
,2015-12-02 19:10:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:10:34.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:11:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:11:04.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:11:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:11:34.668 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:12:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:12:04.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:12:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:12:34.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:13:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:13:04.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:13:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:14:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:14:04.360 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:14:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:14:34.892 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:15:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:15:04.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:15:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:15:34.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:16:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:16:04.360 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:16:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:16:34.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:17:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:17:04.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:17:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:17:34.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:18:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:18:05.261 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:18:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:18:34.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:19:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:19:04.362 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:19:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:19:34.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:20:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:20:04.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:20:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:21:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:21:04.363 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:21:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:22:04.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:22:04.708 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,2015-12-02 19:22:34.354 ThaliTest[1809:2848374] multipeer session: restart
,2015-12-02 19:22:34.361 ThaliTest[1809:2848374] client: found peer: Apple-Iphone5-1_PT1792.Nse+hg==
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
,testSendData stopped
,2015-12-02 19:22:52.045 ThaliTest[1809:2848546] jxcore: stopBroadcasting
2015-12-02 19:22:52.045 ThaliTest[1809:2848546] THEMultipeerSession stopping peer
2015-12-02 19:22:52.045 ThaliTest[1809:2848546] multipeer session: stop timer
2015-12-02 19:22:52.045 ThaliTest[1809:2848546] server session: disconnect
2015-12-02 19:22:52.045 ThaliTest[1809:2848546] server session: stateChange:2->0 Apple-Iphone5-1_PT1792
,2015-12-02 19:22:52.049 ThaliTest[1809:2848546] server session: disconnect
2015-12-02 19:22:52.049 ThaliTest[1809:2848546] server session: stateChange:2->0 Apple-Iphone6-1_PT8308
,2015-12-02 19:22:52.052 ThaliTest[1809:2848546] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-02T18:22:52.066Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-02T18:22:52.066Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-02T18:22:52.066Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT1792.Nse+hg==\",\"time\":3084,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone6-1_PT8308.Z3UjCg==\",\"time\":3754,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5s-1_PT3324.ZgTNhQ==\",\"time\":5178,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":3,"addressList":[]}
,****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
