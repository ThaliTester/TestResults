#### Test 539786639813e59_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8BCEA481-4B35-4AA4-BA28-92625A2F8494/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8BCEA481-4B35-4AA4-BA28-92625A2F8494/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/539786639813e59/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BD290DBE-3F60-47DB-94A3-95C6A1CC4EB4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59289"
,(lldb)     command script import "/tmp/8BCEA481-4B35-4AA4-BA28-92625A2F8494/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-17 15:09:27.327 ThaliTest[367:232301] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8F506202-AC86-4B24-8FA7-13CC95D54CED/Library/Cookies/Cookies.binarycookies
,2015-12-17 15:09:27.656 ThaliTest[367:232301] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-17 15:09:27.657 ThaliTest[367:232301] Multi-tasking -> Device: YES, App: YES
,2015-12-17 15:09:27.665 ThaliTest[367:232301] Unlimited access to network resources
,2015-12-17 15:09:27.672 ThaliTest[367:232301] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-17 15:09:36.535 ThaliTest[367:232301] Resetting plugins due to page load.
,2015-12-17 15:09:39.901 ThaliTest[367:232301] Finished load of: file:///var/mobile/Containers/Bundle/Application/BD290DBE-3F60-47DB-94A3-95C6A1CC4EB4/ThaliTest.app/www/index.html
,2015-12-17 15:09:40.063 ThaliTest[367:232301] JXcore Cordova plugin initializing
,2015-12-17 15:09:40.064 ThaliTest[367:232530] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT1563
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
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 51447
,2015-12-17 15:16:45.951 ThaliTest[367:232530] jxcore: startBroadcasting
,2015-12-17 15:16:45.970 ThaliTest[367:232530] server: starting Apple-IpadAir2-1_PT1563.8yqJeg==
,2015-12-17 15:16:45.971 ThaliTest[367:232530] multipeer session: start timer: 0x18fc1990
,2015-12-17 15:16:45.972 ThaliTest[367:232530] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT1563
,2015-12-17 15:16:45.973 ThaliTest[367:232530] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-17T14:16:45.976Z SendDataTCPServer.js: TCP/IP server is bound to port: 51447
,2015-12-17 15:16:47.141 ThaliTest[367:232301] client: found peer: Apple-Iphone6-1_PT1480.8RWX+A==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT1480.8RWX+A==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:16:47.147Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:16:47.148Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17T14:16:47.149Z SendDataConnector.js: do connect now
,2015-12-17 15:16:47.150 ThaliTest[367:232530] jxcore: connect Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:47.151 ThaliTest[367:232530] client session: connect
,2015-12-17 15:16:47.151 ThaliTest[367:232530] client session: stateChange:0->1 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:47.739 ThaliTest[367:232301] multipeer session: reset timer
2015-12-17 15:16:47.739 ThaliTest[367:232301] multipeer session: stop timer
2015-12-17 15:16:47.739 ThaliTest[367:232301] multipeer session: start timer: 0x18fc1990
,2015-12-17 15:16:47.740 ThaliTest[367:232301] server session: connect
,2015-12-17 15:16:47.740 ThaliTest[367:232301] server session: stateChange:0->1 Apple-Iphone6-1_PT1480
,2015-12-17 15:16:47.747 ThaliTest[367:232301] server: accepting invitation Apple-Iphone6-1_PT1480
,2015-12-17 15:16:47.959 ThaliTest[367:232301] client: found peer: Apple-Iphone5s-1_PT1370.za9tCA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT1370.za9tCA==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-17 15:16:48.356 ThaliTest[367:232301] client: found peer: Apple-Iphone5-1_PT5479.4UkRdw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT5479.4UkRdw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-17 15:16:49.036 ThaliTest[367:232301] multipeer session: reset timer
2015-12-17 15:16:49.036 ThaliTest[367:232301] multipeer session: stop timer
,2015-12-17 15:16:49.037 ThaliTest[367:232301] multipeer session: start timer: 0x18fc1990
,2015-12-17 15:16:49.037 ThaliTest[367:232301] server session: connect
2015-12-17 15:16:49.037 ThaliTest[367:232301] server session: stateChange:0->1 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:49.044 ThaliTest[367:232301] server: accepting invitation Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:50.756 ThaliTest[367:233301] server session: connected
,2015-12-17 15:16:50.757 ThaliTest[367:233301] server session: stateChange:1->2 Apple-Iphone6-1_PT1480
,2015-12-17 15:16:50.763 ThaliTest[367:233301] client session: connected
2015-12-17 15:16:50.763 ThaliTest[367:233301] client session: stateChange:1->2 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:51.235 ThaliTest[367:233301] client session: fireConnectCallback: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:16:51.236 ThaliTest[367:233301] jxcore: connect: success
2015-12-17 15:16:51.238 ThaliTest[367:232301] server relay: connected (to port: 51447)
2015-12-17T14:16:51.242Z SendDataTCPServer.js: TCP/IP server connected
2015-12-17T14:16:51.245Z SendDataConnector.js: CLIENT connected to 51450, error: null
2015-12-17T14:16:51.245Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:51.252 ThaliTest[367:232301] client: relay established
2015-12-17 15:16:51.252 ThaliTest[367:232301] client: new accepted socket: 0x1a030250
,2015-12-17T14:16:51.267Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:16:51.729Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-17T14:16:51.742Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-17T14:16:51.802Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17T14:16:51.864Z SendDataConnector.js: CLIENT is data received : 10000
,2015-12-17T14:16:51.939Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-17 15:16:52.449 ThaliTest[367:233301] server session: connected
2015-12-17 15:16:52.449 ThaliTest[367:233301] server session: stateChange:1->2 Apple-Iphone5s-1_PT1370
,2015-12-17 15:16:52.777 ThaliTest[367:232301] server relay: connected (to port: 51447)
,2015-12-17T14:16:52.779Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:53.067Z SendDataTCPServer.js: TCP/IP server has received 48180 bytes of data
,2015-12-17T14:16:53.122Z SendDataTCPServer.js: TCP/IP server has received 54750 bytes of data
,2015-12-17T14:16:53.138Z SendDataTCPServer.js: TCP/IP server has received 89790 bytes of data
,2015-12-17T14:16:53.193Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17T14:16:53.628Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T14:16:53.644Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:16:53.644Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:53.648Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:53.648Z SendDataConnector.js: CLIENT closeClientSocket
2015-12-17 15:16:53.650 ThaliTest[367:233311] server session: not connected Apple-Iphone5s-1_PT1370
2015-12-17 15:16:53.650 ThaliTest[367:232530] jxcore: disconnect
,2015-12-17 15:16:53.651 ThaliTest[367:232530] client session: disconnectFromPeer: Apple-Iphone6-1_PT1480.8RWX+A==
2015-12-17 15:16:53.651 ThaliTest[367:232530] client session: disconnect
,2015-12-17 15:16:53.652 ThaliTest[367:232530] client session: stateChange:2->0 Apple-Iphone6-1_PT1480.8RWX+A==
,2015-12-17 15:16:53.669 ThaliTest[367:232530] jxcore: disconnect: success
2015-12-17T14:16:53.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT1480.8RWX+A==
,---- round done--------
device[2]: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17T14:16:53.673Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17T14:16:53.673Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17T14:16:53.678Z SendDataConnector.js: do connect now
2015-12-17 15:16:53.679 ThaliTest[367:232530] jxcore: connect Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:53.679 ThaliTest[367:232530] client session: connect
2015-12-17 15:16:53.680 ThaliTest[367:232530] client session: stateChange:0->1 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:53.771 ThaliTest[367:232301] multipeer session: reset timer
2015-12-17 15:16:53.771 ThaliTest[367:232301] multipeer session: stop timer
2015-12-17 15:16:53.771 ThaliTest[367:232301] multipeer session: start timer: 0x18fc1990
,2015-12-17 15:16:53.772 ThaliTest[367:232301] server session: connect
,2015-12-17 15:16:53.772 ThaliTest[367:232301] server session: stateChange:0->1 Apple-Iphone5-1_PT5479
,2015-12-17 15:16:53.779 ThaliTest[367:232301] server: accepting invitation Apple-Iphone5-1_PT5479
,2015-12-17 15:16:56.860 ThaliTest[367:233311] client session: connected
2015-12-17 15:16:56.860 ThaliTest[367:233311] client session: stateChange:1->2 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:56.918 ThaliTest[367:233299] client session: fireConnectCallback: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:56.918 ThaliTest[367:233299] jxcore: connect: success
,2015-12-17T14:16:56.919Z SendDataConnector.js: CLIENT connected to 51455, error: null
2015-12-17T14:16:56.920Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:16:56.922 ThaliTest[367:232301] client: relay established
2015-12-17 15:16:56.923 ThaliTest[367:232301] client: new accepted socket: 0x1a028640
,2015-12-17T14:16:56.935Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17 15:16:56.944 ThaliTest[367:233364] server session: connected
2015-12-17 15:16:56.944 ThaliTest[367:233364] server session: stateChange:1->2 Apple-Iphone5-1_PT5479
,2015-12-17 15:16:56.982 ThaliTest[367:232301] server relay: connected (to port: 51447)
,2015-12-17T14:16:57.225Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-17T14:16:57.325Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-17T14:16:57.387Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T14:16:57.501Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-17T14:16:57.514Z SendDataTCPServer.js: TCP/IP server has received 67890 bytes of data
,2015-12-17T14:16:57.529Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
,2015-12-17T14:16:57.779Z SendDataTCPServer.js: TCP/IP server has received 91980 bytes of data
,2015-12-17T14:16:57.794Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-17 15:16:57.903 ThaliTest[367:233298] server session: not connected Apple-Iphone5-1_PT5479
,2015-12-17T14:16:58.296Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:16:58.297Z SendDataConnector.js: got all data for this round
,2015-12-17T14:16:58.299Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:16:58.300Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:16:58.301 ThaliTest[367:232530] jxcore: disconnect
2015-12-17 15:16:58.301 ThaliTest[367:232530] client session: disconnectFromPeer: Apple-Iphone5s-1_PT1370.za9tCA==
2015-12-17 15:16:58.301 ThaliTest[367:232530] client session: disconnect
2015-12-17 15:16:58.302 ThaliTest[367:232530] client session: stateChange:2->0 Apple-Iphone5s-1_PT1370.za9tCA==
,2015-12-17 15:16:58.321 ThaliTest[367:232530] jxcore: disconnect: success
2015-12-17T14:16:58.321Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT1370.za9tCA==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:58.335Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:58.337Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17T14:16:58.338Z SendDataConnector.js: do connect now
,2015-12-17 15:16:58.339 ThaliTest[367:232530] jxcore: connect Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:16:58.341 ThaliTest[367:232530] client session: connect
,2015-12-17 15:16:58.342 ThaliTest[367:232530] client session: stateChange:0->1 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:17:01.572 ThaliTest[367:233311] client session: connected
2015-12-17 15:17:01.572 ThaliTest[367:233311] client session: stateChange:1->2 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:17:01.601 ThaliTest[367:233301] client session: fireConnectCallback: Apple-Iphone5-1_PT5479.4UkRdw==
2015-12-17 15:17:01.602 ThaliTest[367:233301] jxcore: connect: success
2015-12-17T14:17:01.603Z SendDataConnector.js: CLIENT connected to 51459, error: null
,2015-12-17T14:17:01.604Z SendDataConnector.js: CLIENT starting client 
,2015-12-17 15:17:01.606 ThaliTest[367:232301] client: relay established
2015-12-17 15:17:01.607 ThaliTest[367:232301] client: new accepted socket: 0x18cd7fe0
,2015-12-17T14:17:01.618Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-17T14:17:02.029Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-17T14:17:02.042Z SendDataConnector.js: CLIENT is data received : 60000
,2015-12-17T14:17:02.054Z SendDataConnector.js: CLIENT is data received : 90000
,2015-12-17T14:17:02.091Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-17T14:17:02.091Z SendDataConnector.js: got all data for this round
2015-12-17T14:17:02.091Z SendDataConnector.js: CLIENT Stop now
,2015-12-17T14:17:02.091Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:17:02.092 ThaliTest[367:232530] jxcore: disconnect
,2015-12-17 15:17:02.092 ThaliTest[367:232530] client session: disconnectFromPeer: Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:17:02.092 ThaliTest[367:232530] client session: disconnect
,2015-12-17 15:17:02.093 ThaliTest[367:232530] client session: stateChange:2->0 Apple-Iphone5-1_PT5479.4UkRdw==
,2015-12-17 15:17:02.096 ThaliTest[367:232530] jxcore: disconnect: success
2015-12-17T14:17:02.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT5479.4UkRdw==
---- round done--------
weAreDoneNow , resultArray.length: 3
,done, now sending data to server
DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT1563","time":16160,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT1480.8RWX+A==","time":6498,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1,_PT1370.za9tCA==","time":4624,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT5479.4UkRdw==","time":3754,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":1000,00}]}
sendList : 100% : 6498 ms, 99% : 6498 ms, 95 : 6498 ms, 90% : 6498 ms.
Result count 3, range 3754 ms to  6498 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
2015-12-17T14:17:02.101Z SendDataConnector.js: CLIENT Stop now
2015-12-17T14:17:02.101Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-17 15:17:03.321 ThaliTest[367:233299] server session: not connected Apple-Iphone6-1_PT1480
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
,stop current!
,testSendData stopped
,2015-12-17 15:17:07.986 ThaliTest[367:232530] jxcore: stopBroadcasting
,2015-12-17 15:17:07.987 ThaliTest[367:232530] THEMultipeerSession stopping peer
,2015-12-17 15:17:07.987 ThaliTest[367:232530] multipeer session: stop timer
,2015-12-17 15:17:07.988 ThaliTest[367:232530] server session: disconnect
2015-12-17 15:17:07.989 ThaliTest[367:232530] server session: stateChange:2->0 Apple-Iphone5s-1_PT1370
,2015-12-17 15:17:07.998 ThaliTest[367:232530] server session: disconnect
2015-12-17 15:17:07.999 ThaliTest[367:232530] server session: stateChange:2->0 Apple-Iphone5-1_PT5479
,2015-12-17 15:17:08.010 ThaliTest[367:232530] server session: disconnect
2015-12-17 15:17:08.010 ThaliTest[367:232530] server session: stateChange:2->0 Apple-Iphone6-1_PT1480
,2015-12-17 15:17:08.016 ThaliTest[367:232530] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-17T14:17:08.036Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:08.037Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:08.039Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-17T14:17:08.040Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT5479.4UkRdw==\",\"time\":3754,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-Iphone5s-1_PT1370.za9tCA==\",\"time\":4624,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"Apple-Iphone6-1_PT1480.8RWX+A==\",\"time\":6498,\"result\":\"OK\",\"connections\":1,,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
stop tests now !

```
