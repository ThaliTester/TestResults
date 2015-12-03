#### Test 52383621712b264_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8FC668E7-27AA-4F6E-8525-5D82313E2825/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8FC668E7-27AA-4F6E-8525-5D82313E2825/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621712b264/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F633511A-448E-4972-988B-6C33C4F8C60A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60533"
,(lldb)     command script import "/tmp/8FC668E7-27AA-4F6E-8525-5D82313E2825/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 15:39:26.348 ThaliTest[2611:2211995] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/74D78461-7785-4311-AECA-A1FFDBC78EB6/Library/Cookies/Cookies.binarycookies
,2015-12-03 15:39:26.729 ThaliTest[2611:2211995] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 15:39:26.730 ThaliTest[2611:2211995] Multi-tasking -> Device: YES, App: YES
,2015-12-03 15:39:26.738 ThaliTest[2611:2211995] Unlimited access to network resources
,2015-12-03 15:39:26.745 ThaliTest[2611:2211995] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 15:39:30.195 ThaliTest[2611:2211995] Resetting plugins due to page load.
,2015-12-03 15:39:30.535 ThaliTest[2611:2211995] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/F633511A-448E-4972-988B-6C33C4F8C60A/ThaliTest.app/www/index.html
,2015-12-03 15:39:30.656 ThaliTest[2611:2211995] JXcore Cordova plugin initializing
2015-12-03 15:39:30.658 ThaliTest[2611:2212128] JXcore instance initializing
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
Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,my name is : Apple-Iphone6-1_PT1068
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
,DBG, CoordinatorConnector connect called
,Coordinator is now connected to the server!
,DBG, CoordinatorConnector start_tests called
,DBG, CoordinatorConnector command called
,command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":3,"addressList":[]}
,Start now : testSendData.js
,testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 0
,check server
serverPort is 50365
,2015-12-03 15:45:46.498 ThaliTest[2611:2212128] jxcore: startBroadcasting
,2015-12-03 15:45:46.509 ThaliTest[2611:2212128] server: starting Apple-Iphone6-1_PT1068.V8ys1g==
2015-12-03 15:45:46.510 ThaliTest[2611:2212128] multipeer session: start timer: 0x195612b0
2015-12-03 15:45:46.511 ThaliTest[2611:2212128] THEMultipeerSessio,n initialized peer Apple-Iphone6-1_PT1068
2015-12-03 15:45:46.512 ThaliTest[2611:2212128] jxcore: startBroadcasting: success
StartBroadcasting started ok
,2015-12-03T14:45:46.515Z SendDataTCPServer.js: TCP/IP server is bound to port: 50365
,2015-12-03 15:45:47.065 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT7057.4CFLyQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: tr,ue
device[1]: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:45:47.075Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:45:47.076Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==,
2015-12-03T14:45:47.077Z SendDataConnector.js: do connect now
2015-12-03 15:45:47.077 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:45:47.078 ThaliTest[2611:2212128] client session: connect
2015-12-03 15:45:47.0,79 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:45:47.085 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:45:47.086 ThaliTest[2611:2211995] multipeer session: stop timer
2015,-12-03 15:45:47.089 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-12-03 15:45:47.095 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:45:47.096 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5-,1_PT4165
,2015-12-03 15:45:47.118 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5-1_PT4165
,2015-12-03 15:45:47.392 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:45:47.392 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:45:47.392 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:45:47.392 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:45:47.392 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:47.396 ThaliTest[2611:2211995] server: accepting invitation Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:47.813 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT6724.bsoISg==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: ,true
,2015-12-03 15:45:47.845 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5-1_PT4165.Uz5DSQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:49.400 ThaliTest[2611:2212682] server session: connected
2015-12-03 15:45:49.400 ThaliTest[2611:2212682] server session: stateChange:1->2 Apple-Iphone5-1_PT4165
,2015-12-03 15:45:49.413 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
,2015-12-03T14:45:49.423Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:45:49.920Z SendDataTCPServer.js: TCP/IP server has received 4960 bytes of data
,2015-12-03T14:45:49.933Z SendDataTCPServer.js: TCP/IP server has received 12896 bytes of data
,2015-12-03T14:45:49.948Z SendDataTCPServer.js: TCP/IP server has received 22816 bytes of data
,2015-12-03T14:45:49.999Z SendDataTCPServer.js: TCP/IP server has received 27776 bytes of data
,2015-12-03T14:45:50.011Z SendDataTCPServer.js: TCP/IP server has received 32736 bytes of data
,2015-12-03T14:45:50.025Z SendDataTCPServer.js: TCP/IP server has received 38688 bytes of data
2015-12-03 15:45:50.027 ThaliTest[2611:2212682] server session: connected
,2015-12-03 15:45:50.027 ThaliTest[2611:2212682] server session: stateChange:1->2 Apple-IpadAir2-1_PT6724
,2015-12-03T14:45:50.038Z SendDataTCPServer.js: TCP/IP server has received 43648 bytes of data
,2015-12-03 15:45:50.048 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
2015-12-03T14:45:50.052Z SendDataTCPServer.js: TCP/IP server has received 46624 bytes of data
2015-12-03T14:45:50.054Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:45:50.069Z SendDataTCPServer.js: TCP/IP server has received 59520 bytes of data
,2015-12-03T14:45:50.083Z SendDataTCPServer.js: TCP/IP server has received 70432 bytes of data
,2015-12-03T14:45:50.097Z SendDataTCPServer.js: TCP/IP server has received 82336 bytes of data
,2015-12-03T14:45:50.109Z SendDataTCPServer.js: TCP/IP server has received 97216 bytes of data
,2015-12-03T14:45:50.121Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:45:50.154 ThaliTest[2611:2212669] server session: not connected Apple-Iphone5-1_PT4165
,2015-12-03 15:45:50.400 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT2374.Xv/DEA==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-03 15:45:51.025 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:45:51.025 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:45:51.026 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:45:51.026 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:45:51.027 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
,2015-12-03T14:45:51.028Z SendDataTCPServer.js: TCP/IP server has received 2190 bytes of data
,2015-12-03 15:45:51.053 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5s-1_PT2374
2015-12-03T14:45:51.057Z SendDataTCPServer.js: TCP/IP server has received 22670 bytes of data
2015-12-03T14:45:51.073Z SendDataTCPServer.js: TCP/IP serve,r has received 82062 bytes of data
2015-12-03T14:45:51.090Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:45:51.128 ThaliTest[2611:2212673] server session: not connected Apple-IpadAir2-1_PT6724
,2015-12-03 15:45:53.571 ThaliTest[2611:2212669] server session: connected
2015-12-03 15:45:53.572 ThaliTest[2611:2212669] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:45:53.586 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
,2015-12-03T14:45:53.598Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:45:54.003Z SendDataTCPServer.js: TCP/IP server has received 13140 bytes of data
,2015-12-03T14:45:54.018Z SendDataTCPServer.js: TCP/IP server has received 37230 bytes of data
,2015-12-03T14:45:54.033Z SendDataTCPServer.js: TCP/IP server has received 56940 bytes of data
,2015-12-03T14:45:54.048Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-03T14:45:54.063Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-03 15:46:04.094 ThaliTest[2611:2212674] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:14.485 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:46:14.486 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:46:14.487 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:46:14.487 ThaliTest[2611:2211995] server: disconnecting to refresh session (Apple-Iphone5s-1_PT2374)
2015-12-03 15:46:14.487 ThaliTest[2611:2211995] server session: disconnect
2015-12-03 15:46:14.488 ThaliTest[2611:2211995] server session: state,Change:2->0 Apple-Iphone5s-1_PT2374
2015-12-03 15:46:14.491 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:46:14.492 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
2015-12-03T14:46:14.498Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-03 15:46:14.516 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:16.694 ThaliTest[2611:2212729] server session: connected
2015-12-03 15:46:16.695 ThaliTest[2611:2212729] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:16.707 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
,2015-12-03T14:46:16.717Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:46:16.794Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:46:20.144 ThaliTest[2611:2212674] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:46:20.145 ThaliTest[2611:2212674] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:46:20.146 ThaliTest,[2611:2212674] client session: disconnect
2015-12-03 15:46:20.146 ThaliTest[2611:2212674] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:46:20.147 ThaliTest[2611:2212674] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 15:46:20.147 ThaliTest[2611:2212674] jxcore: connect: fail: Peer disconnected
,2015-12-03T14:46:20.150Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T14:46:20.150Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T14:46:20.151Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:46:25.161Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:46:25.162Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:46:27.017 ThaliTest[2611:2212730] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:30.175 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:46:30.175 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:46:30.176Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:46:30.177Z SendDataConnector.js: Connect (retry count 1) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:46:30.177Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-1,2-03T14:46:30.177Z SendDataConnector.js: do connect now
,2015-12-03 15:46:30.178 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:46:30.179 ThaliTest[2611:2212128] client session: connect
2015-12-03 15:46:30.180 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:46:37.003 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:46:37.003 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:46:37.004 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:46:37.005 ThaliTest[2611:2211995] server: disconnecting to refresh session (Apple-Iphone5s-1_PT2374)
2015-12-03 15:46:37.005 ThaliTest[2611:2211995] server session: disconnect
2015-12-03 15:46:37.005 ThaliTest[2611:2211995] server session: state,Change:2->0 Apple-Iphone5s-1_PT2374
2015-12-03 15:46:37.010 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:46:37.011 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
,2015-12-03T14:46:37.025Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03 15:46:37.030 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:39.272 ThaliTest[2611:2212729] server session: connected
2015-12-03 15:46:39.273 ThaliTest[2611:2212729] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:39.286 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
2015-12-03T14:46:39.291Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:46:39.365Z SendDataTCPServer.js: TCP/IP server has received 6570 bytes of data
,2015-12-03T14:46:39.380Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:46:49.554 ThaliTest[2611:2212769] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:46:59.536 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:46:59.536 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:46:59.537 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:46:59.538 ThaliTest[2611:2211995] server: disconnecting to refresh session (Apple-Iphone5s-1_PT2374)
2015-12-03 15:46:59.538 ThaliTest[2611:2211995] server session: disconnect
2015-12-03 15:46:59.538 ThaliTest[2611:2211995] server session: state,Change:2->0 Apple-Iphone5s-1_PT2374
2015-12-03 15:46:59.542 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:46:59.542 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
,2015-12-03T14:46:59.553Z SendDataTCPServer.js: TCP/IP server is ended
2015-12-03 15:46:59.558 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:01.796 ThaliTest[2611:2212805] server session: connected
,2015-12-03 15:47:01.797 ThaliTest[2611:2212805] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:01.808 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
2015-12-03T14:47:01.813Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:47:01.886Z SendDataTCPServer.js: TCP/IP server has received 4380 bytes of data
,2015-12-03T14:47:01.898Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:47:03.187 ThaliTest[2611:2212807] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:03.188 ThaliTest[2611:2212807] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:03.188 ThaliTest,[2611:2212807] client session: disconnect
2015-12-03 15:47:03.189 ThaliTest[2611:2212807] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:03.190 ThaliTest[2611:2212807] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 15:47:03.190 ThaliTest[2611:2212807] jxcore: connect: fail: Peer disconnected
,2015-12-03T14:47:03.192Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T14:47:03.193Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T14:47:03.193Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:47:08.196Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:47:08.197Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:13.207 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:47:13.208 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:47:13.209Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:47:13.209Z SendDataConnector.js: Connect (retry count 2) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
,2015-12-03T14:47:13.209Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:47:13.210Z SendDataConnector.js: do connect now
,2015-12-03 15:47:13.211 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:13.212 ThaliTest[2611:2212128] client session: connect
2015-12-03 15:47:13.212 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:18.423 ThaliTest[2611:2212807] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:22.117 ThaliTest[2611:2211995] multipeer session: reset timer
2015-12-03 15:47:22.118 ThaliTest[2611:2211995] multipeer session: stop timer
2015-12-03 15:47:22.118 ThaliTest[2611:2211995] multipeer session: start timer: 0x195612b0
2015-,12-03 15:47:22.119 ThaliTest[2611:2211995] server: disconnecting to refresh session (Apple-Iphone5s-1_PT2374)
2015-12-03 15:47:22.120 ThaliTest[2611:2211995] server session: disconnect
2015-12-03 15:47:22.121 ThaliTest[2611:2211995] server session: state,Change:2->0 Apple-Iphone5s-1_PT2374
2015-12-03 15:47:22.124 ThaliTest[2611:2211995] server session: connect
2015-12-03 15:47:22.124 ThaliTest[2611:2211995] server session: stateChange:0->1 Apple-Iphone5s-1_PT2374
2015-12-03T14:47:22.131Z SendDataTCPServ,er.js: TCP/IP server is ended
,2015-12-03 15:47:22.144 ThaliTest[2611:2211995] server: accepting invitation Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:24.366 ThaliTest[2611:2212807] server session: connected
2015-12-03 15:47:24.367 ThaliTest[2611:2212807] server session: stateChange:1->2 Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:24.379 ThaliTest[2611:2211995] server relay: connected (to port: 50365)
,2015-12-03T14:47:24.387Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-03T14:47:24.531Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,2015-12-03 15:47:34.714 ThaliTest[2611:2212805] server session: not connected Apple-Iphone5s-1_PT2374
,2015-12-03 15:47:46.215 ThaliTest[2611:2212807] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:46.215 ThaliTest[2611:2212807] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:46.216 ThaliTest,[2611:2212807] client session: disconnect
2015-12-03 15:47:46.216 ThaliTest[2611:2212807] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:47:46.217 ThaliTest[2611:2212807] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 15:47:46.217 ThaliTest[2611:2212807] jxcore: connect: fail: Peer disconnected
,2015-12-03T14:47:46.220Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T14:47:46.220Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T14:47:46.221Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:47:51.234Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:47:51.234Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:52.120 ThaliTest[2611:2211995] multipeer session: restart
,2015-12-03 15:47:52.142 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:47:52.144 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:47:52.146 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:47:52.146 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:56.242 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:47:56.243 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:47:56.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T14:47:56.244Z SendDataConnector.js: Connect (retry count 3) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
,2015-12-03T14:47:56.245Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03T14:47:56.245Z SendDataConnector.js: do connect now
,2015-12-03 15:47:56.246 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:47:56.247 ThaliTest[2611:2212128] client session: connect
,2015-12-03 15:47:56.248 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:22.120 ThaliTest[2611:2211995] multipeer session: restart
,2015-12-03 15:48:22.144 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:48:22.145 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:22.146 ThaliTest[2611:2211995] clien,t: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:48:22.147 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:29.254 ThaliTest[2611:2212930] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:29.256 ThaliTest[2611:2212930] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:48:29.256 ThaliTest[2611:2212930] client session: disconnect
2015-12-03 15:48:29.257 ThaliTest[2611:2212930] client session: stat,eChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:48:29.257 ThaliTest[2611:2212930] client session: fireConnectCallback: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:48:29.258 ThaliTest[2611:2212930] jxcore: connect: fail: Peer disconnected
20,15-12-03T14:48:29.259Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T14:48:29.260Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
2015-12-03T14:48:29.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03 15:48:33.862 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03T14:48:34.260Z SendDataConnector.js: re-try now : Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:48:34.261Z SendDataConnector.js: ReStart called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:39.270 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:48:39.270 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:48:39.271Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLy,Q==
2015-12-03T14:48:39.272Z SendDataConnector.js: Connect (retry count 4) to peer Apple-Iphone6-1_PT7057.4CFLyQ== with availability status: true
2015-12-03T14:48:39.272Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03T14:48:39.272Z SendDataConnector.js: do connect now
,2015-12-03 15:48:39.273 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:39.274 ThaliTest[2611:2212128] client session: connect
2015-12-03 15:48:39.275 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:48:42.807 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:48:52.120 ThaliTest[2611:2211995] multipeer session: restart
,2015-12-03 15:48:52.140 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:48:52.142 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:48:52.143 ThaliTest[2611:2211995] clie,nt: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:48:52.144 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:49:03.739 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:12.281 ThaliTest[2611:2213005] client session: not connected Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:12.282 ThaliTest[2611:2213005] client session: onLinkFailure: Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:12.282 ThaliTest,[2611:2213005] client session: disconnect
2015-12-03 15:49:12.283 ThaliTest[2611:2213005] client session: stateChange:1->0 Apple-Iphone6-1_PT7057.4CFLyQ==
2015-12-03 15:49:12.284 ThaliTest[2611:2213005] client session: fireConnectCallback: Apple-Iphone6-,1_PT7057.4CFLyQ==
2015-12-03 15:49:12.284 ThaliTest[2611:2213005] jxcore: connect: fail: Peer disconnected
2015-12-03T14:49:12.286Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
,2015-12-03T14:49:12.286Z SendDataConnector.js: CLIENT Can not Connect: Peer disconnected
,2015-12-03T14:49:12.292Z SendDataConnector.js: CLIENT Stop now
,2015-12-03 15:49:12.293 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:49:12.294 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:49:12.294Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT7057.4CFLyQ==
,---- round done--------
,device[2]: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:49:12.297Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:49:12.298Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:49:12.299Z SendDataConnector.js: do connect now
,2015-12-03 15:49:12.300 ThaliTest[2611:2212128] jxcore: connect Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:12.302 ThaliTest[2611:2212128] client session: connect
,2015-12-03 15:49:12.303 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:22.120 ThaliTest[2611:2211995] multipeer session: restart
,2015-12-03 15:49:22.143 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:22.144 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:22.144 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:49:22.149 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:49:33.750 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:43.084 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
,2015-12-03 15:49:45.310 ThaliTest[2611:2213041] client session: not connected Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:45.311 ThaliTest[2611:2213041] client session: onLinkFailure: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:45.311 ThaliTe,st[2611:2213041] client session: disconnect
2015-12-03 15:49:45.312 ThaliTest[2611:2213041] client session: stateChange:1->0 Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:45.312 ThaliTest[2611:2213041] client session: fireConnectCallback: Apple-IpadA,ir2-1_PT6724.bsoISg==
2015-12-03 15:49:45.313 ThaliTest[2611:2213041] jxcore: connect: fail: Peer disconnected
2015-12-03T14:49:45.314Z SendDataConnector.js: CLIENT connected to 0, error: Peer disconnected
2015-12-03T14:49:45.315Z SendDataConnector.js: ,CLIENT Can not Connect: Peer disconnected
2015-12-03T14:49:45.315Z SendDataConnector.js: tryAgain afer: 5000 ms.
,2015-12-03T14:49:50.322Z SendDataConnector.js: re-try now : Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:49:50.323Z SendDataConnector.js: ReStart called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:52.120 ThaliTest[2611:2211995] multipeer session: restart
,2015-12-03 15:49:52.139 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5s-1_PT2374.Xv/DEA==
2015-12-03 15:49:52.140 ThaliTest[2611:2211995] client: found peer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:49:52.140 ThaliTest[2611:2211995] client: found peer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:52.142 ThaliTest[2611:2211995] client: found peer: Apple-Iphone6-1_PT7057.4CFLyQ==
,2015-12-03 15:49:55.330 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:49:55.330 ThaliTest[2611:2212128] jxcore: disconnect: fail
2015-12-03T14:49:55.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6724.bsoI,Sg==
2015-12-03T14:49:55.331Z SendDataConnector.js: Connect (retry count 1) to peer Apple-IpadAir2-1_PT6724.bsoISg== with availability status: true
2015-12-03T14:49:55.332Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03T14:49:55.332Z SendDataConnector.js: do connect now
,2015-12-03 15:49:55.333 ThaliTest[2611:2212128] jxcore: connect Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:55.334 ThaliTest[2611:2212128] client session: connect
2015-12-03 15:49:55.335 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:59.010 ThaliTest[2611:2213104] client session: connected
2015-12-03 15:49:59.011 ThaliTest[2611:2213104] client session: stateChange:1->2 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:59.018 ThaliTest[2611:2213112] client session: fireConnectCallback: Apple-IpadAir2-1_PT6724.bsoISg==
2015-12-03 15:49:59.019 ThaliTest[2611:2213112] jxcore: connect: success
2015-12-03T14:49:59.020Z SendDataConnector.js: CLIENT connected to 50396, error: null
2015-12-03T14:49:59.020Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:49:59.024 ThaliTest[2611:2211995] client: relay established
2015-12-03 15:49:59.024 ThaliTest[2611:2211995] client: new accepted socket: 0x19587c50
,2015-12-03T14:49:59.037Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:49:59.321Z SendDataConnector.js: CLIENT is data received : 70000
,2015-12-03T14:49:59.334Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-03T14:49:59.334Z SendDataConnector.js: got all data for this round
,2015-12-03T14:49:59.335Z SendDataConnector.js: CLIENT Stop now
,2015-12-03T14:49:59.335Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:49:59.336 ThaliTest[2611:2212128] jxcore: disconnect
,2015-12-03 15:49:59.337 ThaliTest[2611:2212128] client session: disconnectFromPeer: Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:59.337 ThaliTest[2611:2212128] client session: disconnect
,2015-12-03 15:49:59.338 ThaliTest[2611:2212128] client session: stateChange:2->0 Apple-IpadAir2-1_PT6724.bsoISg==
,2015-12-03 15:49:59.339 ThaliTest[2611:2212128] jxcore: disconnect: success
,2015-12-03T14:49:59.343Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT6724.bsoISg==
,---- round done--------
,device[3]: Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:49:59.345Z SendDataConnector.js: Start called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:49:59.346Z SendDataConnector.js: doConnect called with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03T14:49:59.346Z SendDataConnector.js: do connect now
,2015-12-03 15:49:59.346 ThaliTest[2611:2212128] jxcore: connect Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:49:59.348 ThaliTest[2611:2212128] client session: connect
,2015-12-03 15:49:59.348 ThaliTest[2611:2212128] client session: stateChange:0->1 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:50:03.117 ThaliTest[2611:2213041] client session: connected
2015-12-03 15:50:03.118 ThaliTest[2611:2213041] client session: stateChange:1->2 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:50:03.128 ThaliTest[2611:2213105] client session: fireConnectCallback: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:50:03.129 ThaliTest[2611:2213105] jxcore: connect: success
2015-12-03T14:50:03.130Z SendDataConnector.js: CLIENT connected to 50399, error: null
,2015-12-03T14:50:03.130Z SendDataConnector.js: CLIENT starting client 
,2015-12-03 15:50:03.134 ThaliTest[2611:2211995] client: relay established
2015-12-03 15:50:03.134 ThaliTest[2611:2211995] client: new accepted socket: 0x19636e70
,2015-12-03T14:50:03.147Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-03T14:50:03.587Z SendDataConnector.js: CLIENT is data received : 20000
,2015-12-03T14:50:03.600Z SendDataConnector.js: CLIENT is data received : 50000
,2015-12-03T14:50:03.614Z SendDataConnector.js: CLIENT is data received : 80000
,2015-12-03T14:50:03.627Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-03T14:50:03.628Z SendDataConnector.js: got all data for this round
,2015-12-03T14:50:03.629Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:50:03.629Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-03 15:50:03.630 ThaliTest[2611:2212128] jxcore: disconnect
2015-12-03 15:50:03.630 ThaliTest[2611:2212128] client session: disconnectFromPeer: Apple-Iphone5-1_PT4165.Uz5DSQ==
2015-12-03 15:50:03.630 ThaliTest[2611:2212128] client session: disconnect
2015-12-03 15:50:03.631 ThaliTest[2611:2212128] client session: stateChange:2->0 Apple-Iphone5-1_PT4165.Uz5DSQ==
,2015-12-03 15:50:03.632 ThaliTest[2611:2212128] jxcore: disconnect: success
2015-12-03T14:50:03.633Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5-1_PT4165.Uz5DSQ==
,---- round done--------
,weAreDoneNow , resultArray.length: 3
,done, now sending data to server
,DBG, CoordinatorConnector sendData called
,-- RESULT DATA {"name:":"Apple-Iphone6-1_PT1068","time":257153,"result":"OK","sendList":[{"name":"Apple-Iphone6-1_PT7057.4CFLyQ==","time":205212,"result":"Peer disconnected","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"Appl,e-IpadAir2-1_PT6724.bsoISg==","time":47037,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4165.Uz5DSQ==","time":4282,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataR,eceived":100000}]}
sendList : 100% : 47037 ms, 99% : 47037 ms, 95 : 47037 ms, 90% : 47037 ms.
Result count 2, range 4282 ms to  47037 ms.
sendList failed peers count : 1 [33.333333333333336 %]
- Peer ID : Apple-Iphone6-1_PT7057.4CFLyQ==, Tried : 5
sen,dList never tried peers count : 0 [0 %]
2015-12-03T14:50:03.641Z SendDataConnector.js: CLIENT Stop now
2015-12-03T14:50:03.641Z SendDataConnector.js: CLIENT closeClientSocket
,DBG, CoordinatorConnector command called
,command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
,stop tests now !
stop current!
testSendData stopped
,2015-12-03 15:50:04.508 ThaliTest[2611:2212128] jxcore: stopBroadcasting
,2015-12-03 15:50:04.509 ThaliTest[2611:2212128] THEMultipeerSession stopping peer
,2015-12-03 15:50:04.510 ThaliTest[2611:2212128] multipeer session: stop timer
2015-12-03 15:50:04.511 ThaliTest[2611:2212128] server session: disconnect
2015-12-03 15:50:04.511 ThaliTest[2611:2212128] server session: stateChange:2->0 Apple-Iphone5s-1_PT2,374
,2015-12-03 15:50:04.518 ThaliTest[2611:2212128] server session: disconnect
2015-12-03 15:50:04.518 ThaliTest[2611:2212128] server session: stateChange:2->0 Apple-Iphone5-1_PT4165
,2015-12-03 15:50:04.521 ThaliTest[2611:2212128] server session: disconnect
,2015-12-03 15:50:04.522 ThaliTest[2611:2212128] server session: stateChange:2->0 Apple-IpadAir2-1_PT6724
,2015-12-03 15:50:04.528 ThaliTest[2611:2212128] jxcore: stopBroadcasting: success
,StopBroadcasting went ok
,2015-12-03T14:50:04.550Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:04.552Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:04.555Z SendDataTCPServer.js: TCP/IP server is ended
,2015-12-03T14:50:04.556Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,DBG, CoordinatorConnector command called
,command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"Apple-Iphone5-1_PT4165.Uz5DSQ==\",\"time\":4282,\"result\":\"OK\",\"connections\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},,{\"name\":\"Apple-IpadAir2-1_PT6724.bsoISg==\",\"time\":47037,\"result\":\"OK\",\"connections\":2,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"name\":\"Apple-Iphone6-1_PT7057.4CFLyQ==\",\"time\":205212,,\"result\":\"Peer disconnected\",\"connections\":5,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":0}],\"notTriedList\":[]}}}","devices":4,"addressList":[]}
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
