#### Test 51335028c93db41_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AEA10E5B-312A-434C-BDB5-35225849DC36/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AEA10E5B-312A-434C-BDB5-35225849DC36/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/51335028c93db41/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1A9D84CA-B8E3-41F9-BB4B-D028CD0E2D0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55457"
,(lldb)     command script import "/tmp/AEA10E5B-312A-434C-BDB5-35225849DC36/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-25 13:44:16.199 ThaliTest[1304:1730791] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2DEDB0CC-9A89-4EEA-BCBA-789CE4DDFB12/Library/Cookies/Cookies.binarycookies
,2015-11-25 13:44:16.489 ThaliTest[1304:1730791] Apache Cordova native platform version 3.9.2 is starting.
2015-11-25 13:44:16.490 ThaliTest[1304:1730791] Multi-tasking -> Device: YES, App: YES
,2015-11-25 13:44:16.496 ThaliTest[1304:1730791] Unlimited access to network resources
,2015-11-25 13:44:16.502 ThaliTest[1304:1730791] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-25 13:44:20.692 ThaliTest[1304:1730791] Resetting plugins due to page load.
,2015-11-25 13:44:22.127 ThaliTest[1304:1730791] Finished load of: file:///var/mobile/Containers/Bundle/Application/1A9D84CA-B8E3-41F9-BB4B-D028CD0E2D0B/ThaliTest.app/www/index.html
,2015-11-25 13:44:22.266 ThaliTest[1304:1730791] JXcore Cordova plugin initializing
,2015-11-25 13:44:22.267 ThaliTest[1304:1730997] JXcore instance initializing
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
,Radios toggled
,my name is : Apple-IpadAir2-1_PT7357
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
,serverPort is 61621
,2015-11-25 13:53:11.130 ThaliTest[1304:1730997] jxcore: startBroadcasting
,2015-11-25 13:53:11.136 ThaliTest[1304:1730997] server: starting Apple-IpadAir2-1_PT7357.1lZx3Q==
2015-11-25 13:53:11.137 ThaliTest[1304:1730997] multipeer session: start timer: 0x167bdff0
,2015-11-25 13:53:11.137 ThaliTest[1304:1730997] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT7357
2015-11-25 13:53:11.137 ThaliTest[1304:1730997] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-11-25T12:53:11.139Z SendDataTCPServer.js: TCP/IP server is bound to port: 61621
,2015-11-25 13:53:11.817 ThaliTest[1304:1730791] client: found peer: Apple-Iphone6-1_PT8750.Du3EhQ==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT8750.Du3EhQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:11.819Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:11.820Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25T12:53:11.820Z SendDataConnector.js: do connect now
,2015-11-25 13:53:11.820 ThaliTest[1304:1730997] jxcore: connect Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:11.820 ThaliTest[1304:1730997] client session: connect
2015-11-25 13:53:11.821 ThaliTest[1304:1730997] client session: stateChange:0->1 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:12.829 ThaliTest[1304:1730791] client: found peer: Apple-Iphone5-1_PT9701.GagVHA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT9701.GagVHA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:13.411 ThaliTest[1304:1730791] client: found peer: Apple-Iphone5s-1_PT5807.1C0pWw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT5807.1C0pWw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-11-25 13:53:14.999 ThaliTest[1304:1730791] multipeer session: reset timer
2015-11-25 13:53:14.999 ThaliTest[1304:1730791] multipeer session: stop timer
2015-11-25 13:53:14.999 ThaliTest[1304:1730791] multipeer session: start timer: 0x167bdff0
2015-11-25 13:53:14.999 ThaliTest[1304:1730791] server session: connect
2015-11-25 13:53:14.999 ThaliTest[1304:1730791] server session: stateChange:0->1 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:15.002 ThaliTest[1304:1730791] server: accepting invitation Apple-Iphone6-1_PT8750
,2015-11-25 13:53:15.495 ThaliTest[1304:1731934] client session: connected
2015-11-25 13:53:15.495 ThaliTest[1304:1731934] client session: stateChange:1->2 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:15.504 ThaliTest[1304:1731926] client session: fireConnectCallback: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:15.504 ThaliTest[1304:1731926] jxcore: connect: success
,2015-11-25T12:53:15.505Z SendDataConnector.js: CLIENT connected to 61624, error: null
,2015-11-25T12:53:15.505Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:15.506 ThaliTest[1304:1730791] client: relay established
2015-11-25 13:53:15.506 ThaliTest[1304:1730791] client: new accepted socket: 0x167c2ce0
,2015-11-25T12:53:15.519Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:15.589Z SendDataConnector.js: CLIENT is data received : 30000
,2015-11-25T12:53:15.601Z SendDataConnector.js: CLIENT is data received : 40000
,2015-11-25T12:53:15.614Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T12:53:15.627Z SendDataConnector.js: CLIENT is data received : 80000
,2015-11-25T12:53:15.639Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:15.639Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:15.640Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:15.640Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:15.641 ThaliTest[1304:1730997] jxcore: disconnect
2015-11-25 13:53:15.641 ThaliTest[1304:1730997] client session: disconnectFromPeer: Apple-Iphone6-1_PT8750.Du3EhQ==
2015-11-25 13:53:15.641 ThaliTest[1304:1730997] client session: disconnect
2015-11-25 13:53:15.642 ThaliTest[1304:1730997] client session: stateChange:2->0 Apple-Iphone6-1_PT8750.Du3EhQ==
,2015-11-25 13:53:15.660 ThaliTest[1304:1730791] multipeer session: reset timer
2015-11-25 13:53:15.660 ThaliTest[1304:1730791] multipeer session: stop timer
,2015-11-25 13:53:15.660 ThaliTest[1304:1730791] multipeer session: start timer: 0x167bdff0
2015-11-25 13:53:15.660 ThaliTest[1304:1730791] server session: connect
,2015-11-25 13:53:15.660 ThaliTest[1304:1730791] server session: stateChange:0->1 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:15.663 ThaliTest[1304:1730791] server: accepting invitation Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:15.705 ThaliTest[1304:1730997] jxcore: disconnect: success
2015-11-25T12:53:15.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT8750.Du3EhQ==
---- round done--------
,device[2]: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:15.709Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25T12:53:15.709Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT9701.GagVHA==
20,15-11-25T12:53:15.709Z SendDataConnector.js: do connect now
2015-11-25 13:53:15.710 ThaliTest[1304:1730997] jxcore: connect Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:15.711 ThaliTest[1304:1730997] client session: connect
2015-11-25 13:53:15.711 T,haliTest[1304:1730997] client session: stateChange:0->1 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:17.200 ThaliTest[1304:1731934] server session: connected
2015-11-25 13:53:17.200 ThaliTest[1304:1731934] server session: stateChange:1->2 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:17.210 ThaliTest[1304:1730791] server relay: connected (to port: 61621)
,2015-11-25T12:53:17.221Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:17.612Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:17.681 ThaliTest[1304:1731923] server session: not connected Apple-Iphone6-1_PT8750
,2015-11-25 13:53:18.232 ThaliTest[1304:1731934] server session: connected
2015-11-25 13:53:18.232 ThaliTest[1304:1731934] server session: stateChange:1->2 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:18.259 ThaliTest[1304:1730791] server relay: connected (to port: 61621)
,2015-11-25T12:53:18.266Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:18.712Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-11-25T12:53:18.725Z SendDataTCPServer.js: TCP/IP server has received 30660 bytes of data
,2015-11-25T12:53:18.763Z SendDataTCPServer.js: TCP/IP server has received 35040 bytes of data
,2015-11-25T12:53:18.775Z SendDataTCPServer.js: TCP/IP server has received 61320 bytes of data
,2015-11-25T12:53:18.789Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:19.212 ThaliTest[1304:1731934] server session: not connected Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:19.230 ThaliTest[1304:1730791] multipeer session: reset timer
2015-11-25 13:53:19.230 ThaliTest[1304:1730791] multipeer session: stop timer
2015-11-25 13:53:19.231 ThaliTest[1304:1730791] multipeer session: start timer: 0x167bdff0
,2015-11-25 13:53:19.231 ThaliTest[1304:1730791] server session: connect
,2015-11-25 13:53:19.231 ThaliTest[1304:1730791] server session: stateChange:0->1 Apple-Iphone5-1_PT9701
,2015-11-25 13:53:19.236 ThaliTest[1304:1730791] server: accepting invitation Apple-Iphone5-1_PT9701
,2015-11-25 13:53:19.693 ThaliTest[1304:1731926] client session: connected
2015-11-25 13:53:19.693 ThaliTest[1304:1731926] client session: stateChange:1->2 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:19.699 ThaliTest[1304:1731934] client session: fireConnectCallback: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:19.699 ThaliTest[1304:1731934] jxcore: connect: success
2015-11-25T12:53:19.699Z SendDataConnector.js: CLIENT connected to 61629, error: null
2015-11-25T12:53:19.700Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:19.701 ThaliTest[1304:1730791] client: relay established
2015-11-25 13:53:19.701 ThaliTest[1304:1730791] client: new accepted socket: 0x167dadf0
,2015-11-25T12:53:19.714Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:20.355Z SendDataConnector.js: CLIENT is data received : 20000
,2015-11-25T12:53:20.379Z SendDataConnector.js: CLIENT is data received : 100000
2015-11-25T12:53:20.379Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:20.380Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:20.380Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:20.381 ThaliTest[1304:1730997] jxcore: disconnect
2015-11-25 13:53:20.381 ThaliTest[1304:1730997] client session: disconnectFromPeer: Apple-Iphone5-1_PT9701.GagVHA==
2015-11-25 13:53:20.381 ThaliTest[1304:1730997] client session: disconnect
2015-11-25 13:53:20.381 ThaliTest[1304:1730997] client session: stateChange:2->0 Apple-Iphone5-1_PT9701.GagVHA==
,2015-11-25 13:53:20.386 ThaliTest[1304:1730997] jxcore: disconnect: success
2015-11-25T12:53:20.386Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT9701.GagVHA==
---- round done--------
device[3]: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:20.388Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:20.388Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25T12:53:20.388Z SendDataConnector.js: do connect now
2015-11-25 13:53:20.388 ThaliTest[1304:1730997] jxcore: connect Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:20.389 ThaliTest[1304:1730997] client session: connect
2015-11-25 13:53:20.390 ThaliTest[1304:1730997] client session: stateChange:0->1 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:23.360 ThaliTest[1304:1731926] server session: connected
2015-11-25 13:53:23.360 ThaliTest[1304:1731926] server session: stateChange:1->2 Apple-Iphone5-1_PT9701
,2015-11-25 13:53:23.368 ThaliTest[1304:1730791] server relay: connected (to port: 61621)
,2015-11-25T12:53:23.372Z SendDataTCPServer.js: TCP/IP server connected
,2015-11-25T12:53:23.508Z SendDataTCPServer.js: TCP/IP server has received 13888 bytes of data
,2015-11-25T12:53:23.533Z SendDataTCPServer.js: TCP/IP server has received 30752 bytes of data
,2015-11-25T12:53:23.547Z SendDataTCPServer.js: TCP/IP server has received 62496 bytes of data
,2015-11-25T12:53:23.959Z SendDataTCPServer.js: TCP/IP server has received 72416 bytes of data
,2015-11-25 13:53:23.962 ThaliTest[1304:1731933] client session: connected
2015-11-25 13:53:23.962 ThaliTest[1304:1731933] client session: stateChange:1->2 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25T12:53:23.972Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
,2015-11-25 13:53:23.989 ThaliTest[1304:1731926] client session: fireConnectCallback: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 13:53:23.989 ThaliTest[1304:1731926] jxcore: connect: success
2015-11-25T12:53:23.989Z SendDataConnector.js: CLIENT connected, to 61634, error: null
2015-11-25T12:53:23.989Z SendDataConnector.js: CLIENT starting client 
,2015-11-25 13:53:23.991 ThaliTest[1304:1730791] client: relay established
2015-11-25 13:53:23.991 ThaliTest[1304:1730791] client: new accepted socket: 0x167df3a0
,2015-11-25T12:53:24.003Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-11-25T12:53:24.484Z SendDataConnector.js: CLIENT is data received : 50000
,2015-11-25T12:53:24.497Z SendDataConnector.js: CLIENT is data received : 90000
,2015-11-25 13:53:24.503 ThaliTest[1304:1731926] server session: not connected Apple-Iphone5-1_PT9701
,2015-11-25T12:53:24.509Z SendDataConnector.js: CLIENT is data received : 100000
,2015-11-25T12:53:24.509Z SendDataConnector.js: got all data for this round
,2015-11-25T12:53:24.510Z SendDataConnector.js: CLIENT Stop now
2015-11-25T12:53:24.510Z SendDataConnector.js: CLIENT closeClientSocket
,2015-11-25 13:53:24.511 ThaliTest[1304:1730997] jxcore: disconnect
2015-11-25 13:53:24.511 ThaliTest[1304:1730997] client session: disconnectFromPeer: Apple-Iphone5s-1_PT5807.1C0pWw==
2015-11-25 13:53:24.511 ThaliTest[1304:1730997] client session: discon,nect
2015-11-25 13:53:24.511 ThaliTest[1304:1730997] client session: stateChange:2->0 Apple-Iphone5s-1_PT5807.1C0pWw==
,2015-11-25 13:53:24.516 ThaliTest[1304:1730997] jxcore: disconnect: success
2015-11-25T12:53:24.516Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT5807.1C0pWw==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT7357","time":13393,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT8750.Du3EhQ==","time":3819,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_,PT9701.GagVHA==","time":4670,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT5807.1C0pWw==","time":4121,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
sendList : 100% : 4670 ms, 99% : 4670 ms, 95 : 4670 ms, 90% : 4670 ms.
Result count 3, range 3819 ms to  4670 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-11-25T12:53:24.521Z SendDataConnector.js: CLI,ENT Stop now
2015-11-25T12:53:24.521Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-11-25 13:53:25.241 ThaliTest[1304:1730997] jxcore: stopBroadcasting
2015-11-25 13:53:25.242 ThaliTest[1304:1730997] THEMultipeerSession stopping peer
2015-11-25 13:53:25.242 ThaliTest[1304:1730997] multipeer session: stop timer
2015-11-25 13:53:25.,242 ThaliTest[1304:1730997] server session: disconnect
2015-11-25 13:53:25.242 ThaliTest[1304:1730997] server session: stateChange:2->0 Apple-Iphone5-1_PT9701
,2015-11-25 13:53:25.245 ThaliTest[1304:1730997] server session: disconnect
2015-11-25 13:53:25.245 ThaliTest[1304:1730997] server session: stateChange:2->0 Apple-Iphone5s-1_PT5807
,2015-11-25 13:53:25.250 ThaliTest[1304:1730997] server session: disconnect
2015-11-25 13:53:25.250 ThaliTest[1304:1730997] server session: stateChange:2->0 Apple-Iphone6-1_PT8750
,2015-11-25 13:53:25.254 ThaliTest[1304:1730997] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-11-25T12:53:25.269Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:25.270Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:25.270Z SendDataTCPServer.js: TCP/IP server is ended
,2015-11-25T12:53:25.270Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone6-1_PT8750.Du3EhQ==\",\"time\":3819,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT5807.1C0pWw==\",\"time\":4121,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone5-1_PT9701.GagVHA==\",\"time\":4670,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
