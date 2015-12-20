#### Test 506502785b2d2b2_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/901BEAF7-3201-4E1B-8807-6784A5CE7DEB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/901BEAF7-3201-4E1B-8807-6784A5CE7DEB/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502785b2d2b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F79B8FEA-3309-41A8-8C30-57319FCA15F7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60866"
,(lldb)     command script import "/tmp/901BEAF7-3201-4E1B-8807-6784A5CE7DEB/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-20 03:38:21.070 ThaliTest[490:642373] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0387FF05-3197-448D-A7F0-BC13FA646316/Library/Cookies/Cookies.binarycookies
,2015-12-20 03:38:21.202 ThaliTest[490:642373] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-20 03:38:21.204 ThaliTest[490:642373] Multi-tasking -> Device: YES, App: YES
,2015-12-20 03:38:21.209 ThaliTest[490:642373] Unlimited access to network resources
,2015-12-20 03:38:21.222 ThaliTest[490:642373] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-20 03:38:31.491 ThaliTest[490:642373] Resetting plugins due to page load.
,2015-12-20 03:38:35.688 ThaliTest[490:642373] Finished load of: file:///var/mobile/Containers/Bundle/Application/F79B8FEA-3309-41A8-8C30-57319FCA15F7/ThaliTest.app/www/index.html
,2015-12-20 03:38:35.899 ThaliTest[490:642373] JXcore Cordova plugin initializing
2015-12-20 03:38:35.900 ThaliTest[490:642731] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-20 03:38:38.364 ThaliTest[490:642373] THREAD WARNING: ['JXcore'] took '154.287109' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData.js---
,testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":4}bt-address length : 0
,daya100000
check server
,serverPort is 54807
,2015-12-20 03:44:42.945 ThaliTest[490:642731] jxcore: startBroadcasting
,2015-12-20 03:44:42.958 ThaliTest[490:642731] server: starting Apple-Iphone5-1_PT1975.nu3zFw==
,2015-12-20 03:44:42.959 ThaliTest[490:642731] multipeer session: start timer: 0x194676f0
,2015-12-20 03:44:42.960 ThaliTest[490:642731] THEMultipeerSession initialized peer Apple-Iphone5-1_PT1975
,2015-12-20 03:44:42.961 ThaliTest[490:642731] jxcore: startBroadcasting: success
,StartBroadcasting started ok
null
,2015-12-20T02:44:42.965Z SendDataTCPServer.js: TCP/IP server is bound to port: 54807
,2015-12-20 03:44:44.003 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,startWithNextDevice
device[1]: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:44.007Z SendDataConnector.js: Start called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:44.007Z SendDataConnector.js: doConnect called with peer Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20T02:44:44.008Z SendDataConnector.js: do connect now
,2015-12-20 03:44:44.009 ThaliTest[490:642731] jxcore: connect Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:44.009 ThaliTest[490:642731] client session: connect
2015-12-20 03:44:44.009 ThaliTest[490:642731] client session: stateChange:0->1 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:44.068 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.BRI7qQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-20 03:44:44.202 ThaliTest[490:642373] multipeer session: reset timer
2015-12-20 03:44:44.202 ThaliTest[490:642373] multipeer session: stop timer
2015-12-20 03:44:44.202 ThaliTest[490:642373] multipeer session: start timer: 0x194676f0
2015-12-20 ,03:44:44.203 ThaliTest[490:642373] server session: connect
2015-12-20 03:44:44.203 ThaliTest[490:642373] server session: stateChange:0->1 Apple-Iphone6-1_PT27
,2015-12-20 03:44:44.209 ThaliTest[490:642373] server: accepting invitation Apple-Iphone6-1_PT27
,2015-12-20 03:44:44.909 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
,2015-12-20 03:44:45.654 ThaliTest[490:642373] multipeer session: reset timer
2015-12-20 03:44:45.654 ThaliTest[490:642373] multipeer session: stop timer
2015-12-20 03:44:45.654 ThaliTest[490:642373] multipeer session: start timer: 0x194676f0
2015-12-20 03:44:45.654 ThaliTest[490:642373] server session: connect
2015-12-20 03:44:45.654 ThaliTest[490:642373] server session: stateChange:0->1 Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:45.662 ThaliTest[490:642373] server: accepting invitation Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:46.833 ThaliTest[490:643395] server session: connected
2015-12-20 03:44:46.834 ThaliTest[490:643395] server session: stateChange:1->2 Apple-Iphone6-1_PT27
,2015-12-20 03:44:46.840 ThaliTest[490:642373] server relay: connected (to port: 54807)
,2015-12-20T02:44:46.846Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20 03:44:47.099 ThaliTest[490:643378] client session: connected
2015-12-20 03:44:47.099 ThaliTest[490:643378] client session: stateChange:1->2 Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:47.102 ThaliTest[490:643378] client session: fireConnect,Callback: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:47.103 ThaliTest[490:643378] jxcore: connect: success
2015-12-20T02:44:47.104Z SendDataConnector.js: CLIENT connected to 54811, error: null
2015-12-20T02:44:47.104Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:47.109 ThaliTest[490:642373] client: relay established
,2015-12-20 03:44:47.109 ThaliTest[490:642373] client: new accepted socket: 0x19474040
,2015-12-20T02:44:47.121Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:47.672Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20T02:44:47.716Z SendDataConnector.js: CLIENT is data received : 30000
,2015-12-20 03:44:47.751 ThaliTest[490:643396] server session: not connected Apple-Iphone6-1_PT27
,2015-12-20T02:44:47.806Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:47.807Z SendDataConnector.js: got all data for this round
oneRoundDownNow
,2015-12-20T02:44:47.808Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:47.808Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:47.809 ThaliTest[490:642731] jxcore: disconnect
2015-12-20 03:44:47.810 ThaliTest[490:642731] client session: disconnectFromPeer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:44:47.810 ThaliTest[490:642731] client session: disconnect
201,5-12-20 03:44:47.810 ThaliTest[490:642731] client session: stateChange:2->0 Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:44:47.888 ThaliTest[490:642731] jxcore: disconnect: success
2015-12-20T02:44:47.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone6-1_PT27.Ee1r/w==
,---- round done--------
startWithNextDevice
,device[2]: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20T02:44:47.892Z SendDataConnector.js: Start called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20T02:44:47.892Z SendDataConnector.js: doConnect called with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20T02:44:47.892Z SendDataConnector.js: do connect now
,2015-12-20 03:44:47.893 ThaliTest[490:642731] jxcore: connect Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:47.893 ThaliTest[490:642731] client session: connect
2015-12-20 03:44:47.894 ThaliTest[490:642731] client session: stateChange:0->1 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:48.995 ThaliTest[490:642373] multipeer session: reset timer
2015-12-20 03:44:48.996 ThaliTest[490:642373] multipeer session: stop timer
2015-12-20 03:44:48.996 ThaliTest[490:642373] multipeer session: start timer: 0x194676f0
2015-12-20 ,03:44:48.996 ThaliTest[490:642373] server session: connect
2015-12-20 03:44:48.996 ThaliTest[490:642373] server session: stateChange:0->1 Apple-IpadAir2-1_PT5083
2015-12-20 03:44:49.001 ThaliTest[490:642373] server: accepting invitation Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:49.102 ThaliTest[490:643378] server session: connected
2015-12-20 03:44:49.103 ThaliTest[490:643378] server session: stateChange:1->2 Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:49.117 ThaliTest[490:642373] server relay: connected (to port: 54807)
,2015-12-20T02:44:49.126Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:49.590Z SendDataTCPServer.js: TCP/IP server has received 19710 bytes of data
,2015-12-20T02:44:49.610Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
2015-12-20T02:44:49.626Z SendDataTCPServer.js: TCP/IP server has received 65700 bytes of data
,2015-12-20T02:44:49.641Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-20T02:44:49.654Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:49.709 ThaliTest[490:643432] server session: not connected Apple-Iphone5s-1_PT7946
,2015-12-20 03:44:51.147 ThaliTest[490:643390] client session: connected
2015-12-20 03:44:51.148 ThaliTest[490:643390] client session: stateChange:1->2 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:51.154 ThaliTest[490:643390] client session: fireConnectCallback: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:51.155 ThaliTest[490:643390] jxcore: connect: success
2015-12-20T02:44:51.156Z SendDataConnector.js: CLIENT connected to 54815, error: null
2015-12-20T02:44:51.156Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:51.160 ThaliTest[490:642373] client: relay established
2015-12-20 03:44:51.161 ThaliTest[490:642373] client: new accepted socket: 0x193afff0
,2015-12-20T02:44:51.171Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:51.761Z SendDataConnector.js: CLIENT is data received : 100000
2015-12-20T02:44:51.761Z SendDataConnector.js: got all data for this round
oneRoundDownNow
2015-12-20T02:44:51.762Z SendDataConnector.js: CLIENT Stop now
2015-12-20T02:44:51.762Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:51.762 ThaliTest[490:642731] jxcore: disconnect
2015-12-20 03:44:51.764 ThaliTest[490:642731] client session: disconnectFromPeer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:44:51.764 ThaliTest[490:642731] client session: disconnect
2015-12-20 03:44:51.764 ThaliTest[490:642731] client session: stateChange:2->0 Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:44:51.779 ThaliTest[490:642731] jxcore: disconnect: success
2015-12-20T02:44:51.781Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-IpadAir2-1_PT5083.BRI7qQ==
---- round done--------
startWithNextDevice
device[3]: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:51.783Z SendDataConnector.js: Start called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20T02:44:51.784Z SendDataConnector.js: doConnect called with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20T02:44:51.784Z SendDataConnector.js: do connect now
2015-12-20 03:44:51.784 ThaliTest[490:642731] jxcore: connect Apple-Iphone5s-1_PT7946,.2ECkqQ==
2015-12-20 03:44:51.785 ThaliTest[490:642731] client session: connect
2015-12-20 03:44:51.785 ThaliTest[490:642731] client session: stateChange:0->1 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:51.831 ThaliTest[490:643394] server session: connected
2015-12-20 03:44:51.832 ThaliTest[490:643394] server session: stateChange:1->2 Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:51.890 ThaliTest[490:642373] server relay: connected (to port: 54807)
2015-12-20T02:44:51.890Z SendDataTCPServer.js: TCP/IP server connected
,2015-12-20T02:44:52.149Z SendDataTCPServer.js: TCP/IP server has received 17520 bytes of data
,2015-12-20T02:44:52.164Z SendDataTCPServer.js: TCP/IP server has received 41610 bytes of data
,2015-12-20T02:44:52.179Z SendDataTCPServer.js: TCP/IP server has received 76650 bytes of data
,2015-12-20T02:44:52.218Z SendDataTCPServer.js: TCP/IP server has received 85410 bytes of data
,2015-12-20T02:44:52.282Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
,2015-12-20 03:44:52.334 ThaliTest[490:643395] server session: not connected Apple-IpadAir2-1_PT5083
,2015-12-20 03:44:55.096 ThaliTest[490:643395] client session: connected
2015-12-20 03:44:55.096 ThaliTest[490:643395] client session: stateChange:1->2 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:55.100 ThaliTest[490:643395] client session: fireConnectCallback: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:55.100 ThaliTest[490:643395] jxcore: connect: success
2015-12-20T02:44:55.101Z SendDataConnector.js: CLIENT connected to 54819, error: null
2015-12-20T02:44:55.101Z SendDataConnector.js: CLIENT starting client 
,2015-12-20 03:44:55.104 ThaliTest[490:642373] client: relay established
2015-12-20 03:44:55.104 ThaliTest[490:642373] client: new accepted socket: 0x19393030
,2015-12-20T02:44:55.117Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
,2015-12-20T02:44:56.131Z SendDataConnector.js: CLIENT is data received : 100000
,2015-12-20T02:44:56.131Z SendDataConnector.js: got all data for this round
,oneRoundDownNow
,2015-12-20T02:44:56.133Z SendDataConnector.js: CLIENT Stop now
,2015-12-20T02:44:56.133Z SendDataConnector.js: CLIENT closeClientSocket
,2015-12-20 03:44:56.134 ThaliTest[490:642731] jxcore: disconnect
2015-12-20 03:44:56.135 ThaliTest[490:642731] client session: disconnectFromPeer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:44:56.135 ThaliTest[490:642731] client session: disconnect
2015-12-20 03:44:56.135 ThaliTest[490:642731] client session: stateChange:2->0 Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:44:56.144 ThaliTest[490:642731] jxcore: disconnect: success
2015-12-20T02:44:56.144Z SendDataConnector.js: Mobile.Disconnect() callback with peer Apple-Iphone5s-1_PT7946.2ECkqQ==
---- round done--------
startWithNextDevice
,2015-12-20 03:45:18.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:45:48.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:45:49.027 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:45:49.027 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:45:49.029 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:46:18.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:46:19.027 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:46:19.027 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:46:19.029 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:46:48.997 ThaliTest[490:642373] multipeer session: restart
,appEnteredForeground wasn't registered
,2015-12-20 03:47:18.996 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:47:19.038 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:47:19.039 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:47:19.039 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,appEnteringBackground wasn't registered
,2015-12-20 03:47:48.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:47:49.028 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:47:49.029 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:47:49.032 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:48:18.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:48:19.028 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:48:19.028 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:48:19.029 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:48:48.997 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:48:49.026 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:48:49.031 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:48:49.034 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,appEnteredForeground wasn't registered
,2015-12-20 03:48:57.350 ThaliTest[490:642373] client: lost peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:48:57.350 ThaliTest[490:642373] client session: onPeerLost: Apple-Iphone6-1_PT27.Ee1r/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphon,e6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,appEnteringBackground wasn't registered
,2015-12-20 03:48:58.414 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-20 03:49:18.996 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:49:48.996 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:49:49.025 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:49:49.026 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:49:49.028 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:49:59.853 ThaliTest[490:642373] client: lost peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:49:59.853 ThaliTest[490:642373] client session: onPeerLost: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 03:50:06.754 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone5s-1_PT7946.2ECkqQ==","peerName":"(null)","peerAvailable":true}]
startWithNextDevice
,2015-12-20 03:50:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:50:18.954 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:50:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:50:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:50:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:50:48.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:50:48.958 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:50:48.964 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:51:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:51:18.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:51:18.962 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:51:18.962 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:51:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:51:48.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:51:48.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:51:48.962 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,appEnteredForeground wasn't registered
,2015-12-20 03:52:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:52:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:52:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:52:19.456 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:52:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:52:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:52:48.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:52:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:53:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:53:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:53:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:53:18.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:53:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:53:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:53:48.959 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:53:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:54:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:54:18.954 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:54:18.954 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:54:18.955 ThaliTest[490:642373] client: found, peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:54:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:54:48.952 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:54:48.953 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:54:48.955 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:55:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:55:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:55:48.955 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:55:48.955 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:55:48.956 ThaliTest[490:642373] client: found, peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:56:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:56:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:56:18.960 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 03:56:18.960 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 03:56:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:56:48.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:56:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:56:48.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:57:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:57:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:57:48.953 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:57:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:57:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:58:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:58:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:58:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:58:18.962 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:58:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:58:48.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:58:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:58:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:59:18.925 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:59:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:59:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 03:59:18.963 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 03:59:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 03:59:48.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 03:59:48.958 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 03:59:48.960 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:00:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:00:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:00:18.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:00:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:00:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:00:48.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:00:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:00:48.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:01:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:01:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:01:18.962 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:18.964 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,timeout now
,weAreDoneNow, resultArray.length: 3
,sendReportNow
,done, now sending data to server
,2015-12-20T03:01:22.898Z SendDataConnector.js: CLIENT Stop now
,2015-12-20 04:01:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:01:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:01:48.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:01:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:02:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:02:18.955 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:02:18.956 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:02:18.958 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:02:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:02:48.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:02:48.958 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:02:48.958 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:03:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:03:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:03:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:03:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:03:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:03:48.953 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
,2015-12-20 04:03:48.958 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
,2015-12-20 04:03:48.960 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:04:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:04:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:04:18.959 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:18.959 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:04:43.989 ThaliTest[490:642373] client: lost peer: Apple-Iphone6-1_PT27.Ee1r/w==
2015-12-20 04:04:43.989 ThaliTest[490:642373] client session: onPeerLost: Apple-Iphone6-1_PT27.Ee1r/w==
peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
,2015-12-20 04:04:43.989 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-Iphone6-1_PT27.xRGq6Q==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-20 04:04:45.038 ThaliTest[490:642373] client: lost peer: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:45.038 ThaliTest[490:642373] client session: onPeerLost: Apple-IpadAir2-1_PT5083.BRI7qQ==
2015-12-20 04:04:45.039 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.BRI7qQ==","peerName":"(null)","peerAvailable":false}]
startWithNextDevice
peerAvailabilityChanged [{"peerIdentifier":"Apple-IpadAir2-1_PT5083.ybzVtw==","peerName":"(null)","peerAvailable":true}]
Found peer : (null), Available: true
startWithNextDevice
,2015-12-20 04:04:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:04:48.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:04:48.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:04:48.957 ThaliTest[490:642373] client: found, peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:05:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:05:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:05:18.957 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:05:18.957 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:05:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:05:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
,2015-12-20 04:05:48.959 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==
2015-12-20 04:05:48.959 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
,2015-12-20 04:06:18.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:06:18.956 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:06:18.958 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:18.960 ThaliTest[490:642373] client: found, peer: Apple-IpadAir2-1_PT5083.ybzVtw==
,2015-12-20 04:06:48.926 ThaliTest[490:642373] multipeer session: restart
,2015-12-20 04:06:48.955 ThaliTest[490:642373] client: found peer: Apple-Iphone6-1_PT27.xRGq6Q==
2015-12-20 04:06:48.956 ThaliTest[490:642373] client: found peer: Apple-Iphone5s-1_PT7946.2ECkqQ==
2015-12-20 04:06:48.958 ThaliTest[490:642373] client: found peer: Apple-IpadAir2-1_PT5083.ybzVtw==

```
