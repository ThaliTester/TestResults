#### Test 531915643820a6d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/23A0E0E1-5957-4EE3-9C06-76BC419417F3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/23A0E0E1-5957-4EE3-9C06-76BC419417F3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/531915643820a6d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4961121-E2B0-462F-B31C-512285ADBCB1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53832"
,(lldb)     command script import "/tmp/23A0E0E1-5957-4EE3-9C06-76BC419417F3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-11 01:48:23.665 ThaliTest[779:634810] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1A9C22E2-BE68-420C-BE28-8A10403A0497/Library/Cookies/Cookies.binarycookies
,2015-12-11 01:48:23.680 ThaliTest[779:634810] <CATransformLayer: 0x17687e30> - changing property masksToBounds in transform-only layer, will have no effect
2015-12-11 01:48:23.683 ThaliTest[779:634810] <CATransformLayer: 0x1767dea0> - changing property ma,sksToBounds in transform-only layer, will have no effect
2015-12-11 01:48:23.684 ThaliTest[779:634810] <CATransformLayer: 0x17687bf0> - changing property masksToBounds in transform-only layer, will have no effect
,2015-12-11 01:48:23.984 ThaliTest[779:634810] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-11 01:48:23.984 ThaliTest[779:634810] Multi-tasking -> Device: YES, App: YES
,2015-12-11 01:48:23.992 ThaliTest[779:634810] Unlimited access to network resources
,2015-12-11 01:48:23.997 ThaliTest[779:634810] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-11 01:48:32.778 ThaliTest[779:634810] Resetting plugins due to page load.
,2015-12-11 01:48:36.139 ThaliTest[779:634810] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4961121-E2B0-462F-B31C-512285ADBCB1/ThaliTest.app/www/index.html
,2015-12-11 01:48:36.277 ThaliTest[779:634810] JXcore Cordova plugin initializing
,2015-12-11 01:48:36.278 ThaliTest[779:635099] JXcore instance initializing
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
,my name is : Apple-IpadAir2-1_PT8618
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
,serverPort is 55707
,2015-12-11 01:55:28.660 ThaliTest[779:635099] jxcore: startBroadcasting
,2015-12-11 01:55:28.672 ThaliTest[779:635099] server: starting Apple-IpadAir2-1_PT8618.Ut+byw==
,2015-12-11 01:55:28.674 ThaliTest[779:635099] multipeer session: start timer: 0x19766480
2015-12-11 01:55:28.674 ThaliTest[779:635099] THEMultipeerSession initialized peer Apple-IpadAir2-1_PT8618
,2015-12-11 01:55:28.676 ThaliTest[779:635099] jxcore: startBroadcasting: success
,StartBroadcasting started ok
,2015-12-11T00:55:28.678Z SendDataTCPServer.js: TCP/IP server is bound to port: 55707
,2015-12-11 01:55:29.958 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:29.960 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,device[1]: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:29.966Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:29.967Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11T00:55:29.967Z SendDataConnector.js: do connect now
,2015-12-11 01:55:29.968 ThaliTest[779:635099] jxcore: connect Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:29.969 ThaliTest[779:635099] client session: connect
,2015-12-11 01:55:29.969 ThaliTest[779:635099] client session: stateChange:0->1 Apple-Iphone6-1_PT9748.JvjfiA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4192.MPIGmg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-11 01:55:32.716 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7285.LNATEw==","peerName":"(null)","peerAvailable":true}]
,Found peer : (null), Available: true
,2015-12-11 01:55:33.330 ThaliTest[779:634810] multipeer session: reset timer
2015-12-11 01:55:33.330 ThaliTest[779:634810] multipeer session: stop timer
2015-12-11 01:55:33.330 ThaliTest[779:634810] multipeer session: start timer: 0x19766480
2015-12-11 01:55:33.331 ThaliTest[779:634810] server session: connect
2015-12-11 01:55:33.331 ThaliTest[779:634810] server session: stateChange:0->1 Apple-Iphone6-1_PT9748
,2015-12-11 01:55:33.338 ThaliTest[779:634810] server: accepting invitation Apple-Iphone6-1_PT9748
,2015-12-11 01:55:36.313 ThaliTest[779:635750] server session: connected
,2015-12-11 01:55:36.313 ThaliTest[779:635750] server session: stateChange:1->2 Apple-Iphone6-1_PT9748
,2015-12-11T00:55:36.439Z SendDataTCPServer.js: TCP/IP server connected
2015-12-11 01:55:36.439 ThaliTest[779:634810] server relay: connected (to port: 55707)
,2015-12-11T00:55:36.706Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-11T00:55:36.722Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-11T00:55:36.777Z SendDataTCPServer.js: TCP/IP server has received 87458 bytes of data
,2015-12-11T00:55:36.795Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:55:36.900 ThaliTest[779:635750] server session: not connected Apple-Iphone6-1_PT9748
,2015-12-11 01:55:36.975 ThaliTest[779:635758] client session: connected
,2015-12-11 01:55:36.975 ThaliTest[779:635758] client session: stateChange:1->2 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:37.225 ThaliTest[779:635750] client session: fireConnectCallback: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:37.226 ThaliTest[779:635750] jxcore: connect: success
,2015-12-11T00:55:37.228Z SendDataConnector.js: CLIENT connected to 55711, error: null
,2015-12-11T00:55:37.228Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:37.232 ThaliTest[779:634810] client: relay established
2015-12-11 01:55:37.233 ThaliTest[779:634810] client: new accepted socket: 0x1a98eb50
,2015-12-11T00:55:37.248Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11T00:55:37.533Z SendDataConnector.js: CLIENT is data received : 40000
,2015-12-11T00:55:37.546Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-11T00:55:37.754Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T00:55:37.754Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:37.755Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:55:37.755Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:37.757 ThaliTest[779:635099] jxcore: disconnect
2015-12-11 01:55:37.757 ThaliTest[779:635099] client session: disconnectFromPeer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:55:37.757 ThaliTest[779:635099] client session: disconnect
,2015-12-11 01:55:37.757 ThaliTest[779:635099] client session: stateChange:2->0 Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:55:37.763 ThaliTest[779:635099] jxcore: disconnect: success
2015-12-11T00:55:37.763Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT9748.JvjfiA==
---- round done--------
,device[2]: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11T00:55:37.765Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11T00:55:37.765Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11T00:55:37.766Z SendDataConnector.js: do connect now
2015-12-11 01:55:37.767 ThaliTest[779:635099] jxcore: connect Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:37.767 ThaliTest[779:635099] client session: connect
,2015-12-11 01:55:37.767 ThaliTest[779:635099] client session: stateChange:0->1 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:38.808 ThaliTest[779:634810] multipeer session: reset timer
2015-12-11 01:55:38.808 ThaliTest[779:634810] multipeer session: stop timer
2015-12-11 01:55:38.808 ThaliTest[779:634810] multipeer session: start timer: 0x19766480
,2015-12-11 01:55:38.809 ThaliTest[779:634810] server session: connect
2015-12-11 01:55:38.809 ThaliTest[779:634810] server session: stateChange:0->1 Apple-Iphone5-1_PT4192
,2015-12-11 01:55:38.814 ThaliTest[779:634810] server: accepting invitation Apple-Iphone5-1_PT4192
,2015-12-11 01:55:41.954 ThaliTest[779:635808] client session: connected
2015-12-11 01:55:41.955 ThaliTest[779:635808] client session: stateChange:1->2 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:41.964 ThaliTest[779:635759] server session: connected
2015-12-11 01:55:41.964 ThaliTest[779:635759] server session: stateChange:1->2 Apple-Iphone5-1_PT4192
,2015-12-11 01:55:42.007 ThaliTest[779:635759] client session: fireConnectCallback: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:55:42.008 ThaliTest[779:635759] jxcore: connect: success
,2015-12-11T00:55:42.010Z SendDataConnector.js: CLIENT connected to 55714, error: null
2015-12-11T00:55:42.010Z SendDataConnector.js: CLIENT starting client 
,2015-12-11 01:55:42.012 ThaliTest[779:634810] client: relay established
2015-12-11 01:55:42.012 ThaliTest[779:634810] client: new accepted socket: 0x19754760
,2015-12-11T00:55:42.025Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-11 01:55:42.110 ThaliTest[779:634810] server relay: connected (to port: 55707)
,2015-12-11T00:55:42.279Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:42.678Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-11T00:55:43.050Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-11T00:55:43.066Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-11T00:55:43.067Z SendDataConnector.js: got all data for this round
,2015-12-11T00:55:43.068Z SendDataConnector.js: CLIENT Stop now
,2015-12-11T00:55:43.069Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-11 01:55:43.070 ThaliTest[779:635099] jxcore: disconnect
,2015-12-11 01:55:43.070 ThaliTest[779:635099] client session: disconnectFromPeer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:43.071 ThaliTest[779:635099] client session: disconnect
2015-12-11 01:55:43.071 ThaliTest[779:635099] client session: stateChange:2->0 Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:55:43.083 ThaliTest[779:635099] jxcore: disconnect: success
2015-12-11T00:55:43.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4192.MPIGmg==
,---- round done--------
device[3]: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:43.087Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11T00:55:43.088Z SendDataConnector.js: doConnect called with peer Apple-Ip,hone5s-1_PT7285.LNATEw==
2015-12-11T00:55:43.088Z SendDataConnector.js: do connect now
,2015-12-11 01:55:43.088 ThaliTest[779:635099] jxcore: connect Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:43.090 ThaliTest[779:635099] client session: connect
2015-12-11 01:55:43.090 ThaliTest[779:635099] client session: stateChange:0->1 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:55:43.098Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:55:43.165 ThaliTest[779:635759] server session: not connected Apple-Iphone5-1_PT4192
,2015-12-11 01:55:43.693 ThaliTest[779:634810] multipeer session: reset timer
2015-12-11 01:55:43.693 ThaliTest[779:634810] multipeer session: stop timer
,2015-12-11 01:55:43.693 ThaliTest[779:634810] multipeer session: start timer: 0x19766480
2015-12-11 01:55:43.694 ThaliTest[779:634810] server session: connect
2015-12-11 01:55:43.694 ThaliTest[779:634810] server session: stateChange:0->1 Apple-Iphone5s-1,_PT7285
,2015-12-11 01:55:43.701 ThaliTest[779:634810] server: accepting invitation Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:46.931 ThaliTest[779:635750] server session: connected
2015-12-11 01:55:46.932 ThaliTest[779:635750] server session: stateChange:1->2 Apple-Iphone5s-1_PT7285
,2015-12-11 01:55:47.389 ThaliTest[779:635799] client session: connected
2015-12-11 01:55:47.390 ThaliTest[779:635799] client session: stateChange:1->2 Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:55:47.395 ThaliTest[779:634810] server relay: connected (to port: 55707)
,2015-12-11T00:55:47.406Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-11T00:55:47.932Z SendDataTCPServer.js: TCP/IP server has received 8760 bytes of data
,2015-12-11T00:55:47.947Z SendDataTCPServer.js: TCP/IP server has received 24090 bytes of data
,2015-12-11 01:55:58.948 ThaliTest[779:635799] client session: not connected Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:58.949 ThaliTest[779:635799] client session: onLinkFailure: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:58.949 ThaliTest[7,79:635799] client session: disconnect
2015-12-11 01:55:58.949 ThaliTest[779:635799] client session: stateChange:2->0 Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:55:58.950 ThaliTest[779:635799] client session: fireConnectionErrorEvent: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T00:56:02.379Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-11T00:56:02.398Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-11 01:56:02.909 ThaliTest[779:635808] server session: not connected Apple-Iphone5s-1_PT7285
,2015-12-11 01:56:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:56:13.724 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:56:13.725 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:56:13.725 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:56:16.613 ThaliTest[779:634810] client: lost peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:56:16.613 ThaliTest[779:634810] client session: onPeerLost: Apple-Iphone6-1_PT9748.JvjfiA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":false}]
,2015-12-11 01:56:20.385 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT9748.JvjfiA==","peerName":"(null)","peerAvailable":true}]
,2015-12-11 01:56:43.695 ThaliTest[779:634810] multipeer session: restart
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 01:57:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:57:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:57:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 01:57:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:57:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:57:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 01:57:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 01:58:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:58:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:58:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:58:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:58:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:58:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:58:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 01:58:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:59:13.694 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 01:59:13.719 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 01:59:13.719 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 01:59:14.311 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 01:59:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:00:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:00:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:00:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:00:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector disconnect called
The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,2015-12-11 02:00:43.695 ThaliTest[779:634810] multipeer session: restart
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:01:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:01:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:01:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:01:14.216 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,2015-12-11 02:01:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:01:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:01:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:01:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:02:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:02:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:02:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:02:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:02:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:02:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:02:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:02:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:03:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:03:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:03:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:03:13.724 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:03:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:03:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:03:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:03:43.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:04:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:04:13.719 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:04:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:04:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector disconnect called
,The Coordinator has disconnected!
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:04:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:04:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:04:43.723 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:04:43.723 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:05:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:05:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:05:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:05:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:05:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:05:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:05:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:05:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:06:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:06:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:06:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:06:13.724 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:06:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:06:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:06:43.723 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:06:43.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:07:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:07:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:07:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:07:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:07:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:07:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:07:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:07:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:08:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:08:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:08:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:08:13.723 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:08:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:08:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:08:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:08:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:09:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:09:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:09:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,2015-12-11 02:09:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:09:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:09:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:09:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:09:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:10:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:10:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:10:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:10:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:10:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:10:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:10:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:10:43.725 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:11:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:11:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:11:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:11:13.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:11:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:11:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:11:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:11:43.722 ThaliTest[779:634810] client: foun,d peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,timeout now
dun
,weAreDoneNow , resultArray.length: 2
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-IpadAir2-1_PT8618","time":1000038,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT9748.JvjfiA==","time":7789,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4192.MPIGmg==","time":5303,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7285.LNATEw==","time":0,"result":"Fail"}]}
,sendList : 100% : 7789 ms, 99% : 7789 ms, 95 : 7789 ms, 90% : 7789 ms.
,Result count 2, range 5303 ms to  7789 ms.
,sendList failed peers count : 0 [0 %]
,sendList never tried peers count : 1 [33.333333333333336 %]
,- Peer ID : Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11T01:12:08.692Z SendDataConnector.js: CLIENT Stop now
,2015-12-11 02:12:08.693 ThaliTest[779:635099] jxcore: disconnect
,2015-12-11 02:12:08.693 ThaliTest[779:635099] jxcore: disconnect: fail
,2015-12-11T01:12:08.694Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:12:13.694 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:12:13.719 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:12:13.719 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,2015-12-11 02:12:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:12:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:12:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:12:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:12:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:13:13.694 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:13:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:13:13.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:13:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:13:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:13:43.720 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:13:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:13:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:14:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:14:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:14:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:14:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:14:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:14:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:14:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
2015-12-11 02:14:43.722 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:15:13.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:15:13.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
,2015-12-11 02:15:13.724 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:15:13.724 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Wifi toggled for connection repairment
,DBG, CoordinatorConnector connect_error called
,Error type "connect_error" when connecting to the test server
,2015-12-11 02:15:43.695 ThaliTest[779:634810] multipeer session: restart
,2015-12-11 02:15:43.720 ThaliTest[779:634810] client: found peer: Apple-Iphone5-1_PT4192.MPIGmg==
2015-12-11 02:15:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone5s-1_PT7285.LNATEw==
2015-12-11 02:15:43.721 ThaliTest[779:634810] client: found peer: Apple-Iphone6-1_PT9748.JvjfiA==

```
