#### Test 506502787a45a3c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EDA88F40-3414-4A2E-A885-3986BB3EBEBF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/EDA88F40-3414-4A2E-A885-3986BB3EBEBF/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502787a45a3c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56541"
,(lldb)     command script import "/tmp/EDA88F40-3414-4A2E-A885-3986BB3EBEBF/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 02:06:38.908 ThaliTest[1838:1470878] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AF36D6CE-C6E0-48BA-96E0-469C12CFC7C2/Library/Cookies/Cookies.binarycookies
,2015-11-27 02:06:39.307 ThaliTest[1838:1470878] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 02:06:39.308 ThaliTest[1838:1470878] Multi-tasking -> Device: YES, App: YES
,2015-11-27 02:06:39.316 ThaliTest[1838:1470878] Unlimited access to network resources
,2015-11-27 02:06:39.322 ThaliTest[1838:1470878] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 02:06:42.805 ThaliTest[1838:1470878] Resetting plugins due to page load.
,2015-11-27 02:06:43.154 ThaliTest[1838:1470878] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/index.html
,2015-11-27 02:06:43.280 ThaliTest[1838:1470878] JXcore Cordova plugin initializing
,2015-11-27 02:06:43.280 ThaliTest[1838:1471014] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,Warning: iOS does not support ToggleWiFi
,Could not toggle Wifi - Warning: iOS does not support ToggleWiFi
,Radios toggled
,Test app app.js loaded
,CoordinatorConnector-debug: connect:undefined
,CoordinatorConnector-debug: schedule:["multiplex can send data","basic","another","successfully create a new pkcs12 file and return hash value","successfully read a previous pkcs12 file and return hash value","failed to extract public key because of corrup,t pkcs12 file","failed to get mobile documents path","#init should register the peerAvailabilityChanged event","#init should register the networkChanged event","#startBroadcasting should throw on null device name","#startBroadcasting should throw on empty ,string device name","#startBroadcasting should throw on non-number port","#startBroadcasting should throw on NaN port","#startBroadcasting should throw on negative port","#startBroadcasting should throw on too large port","#startBroadcasting should call Mo,bile(\"StartBroadcasting\") without an error","#startBroadcasting should call Mobile(\"StartBroadcasting\") and handle an error","#stopBroadcasting should call Mobile(\"StopBroadcasting\") without an error","#stopBroadcasting should call Mobile(\"StopBroad,casting\") and handle an error","#connect should call Mobile(\"Connect\") with a port and without an error","#connect should call Mobile(\"Connect\") and handle an error","should call Mobile(\"Disconnect\") without an error","should call Mobile(\"Disconnec,t\") and handle an error"]
,TAP version 13
,# setup
,# multiplex can send data
,CoordinatorConnector-debug: setup:multiplex can send data
,# teardown
,CoordinatorConnector-debug: start_test:multiplex can send data
,ok 1 String should be length:200
,# setup
,CoordinatorConnector-debug: teardown:multiplex can send data
,# basic
,CoordinatorConnector-debug: setup:basic
,# teardown
,CoordinatorConnector-debug: start_test:basic
,ok 2 sane
,# setup
,CoordinatorConnector-debug: teardown:basic
,# another
,CoordinatorConnector-debug: setup:another
,# teardown
,CoordinatorConnector-debug: start_test:another
,ok 3 sane
,# setup
,CoordinatorConnector-debug: teardown:another
,# successfully create a new pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully create a new pkcs12 file and return hash value
,# teardown
,CoordinatorConnector-debug: start_test:successfully create a new pkcs12 file and return hash value
,ok 4 should be equal
,ok 5 null
,ok 6 (unnamed assert)
ok 7 should be equal
,ok 8 should not throw
,# setup
,CoordinatorConnector-debug: teardown:successfully create a new pkcs12 file and return hash value
,# successfully read a previous pkcs12 file and return hash value
,CoordinatorConnector-debug: setup:successfully read a previous pkcs12 file and return hash value
,# teardown
,CoordinatorConnector-debug: start_test:successfully read a previous pkcs12 file and return hash value
,ok 9 (unnamed assert)
,ok 10 (unnamed assert)
,ok 11 should not throw
,ok 12 should be equal
ok 13 should be equal
,# setup
,CoordinatorConnector-debug: teardown:successfully read a previous pkcs12 file and return hash value
,# failed to extract public key because of corrupt pkcs12 file
,CoordinatorConnector-debug: setup:failed to extract public key because of corrupt pkcs12 file
,# teardown
,CoordinatorConnector-debug: start_test:failed to extract public key because of corrupt pkcs12 file
,ok 14 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to extract public key because of corrupt pkcs12 file
,# failed to get mobile documents path
,CoordinatorConnector-debug: setup:failed to get mobile documents path
,# teardown
,CoordinatorConnector-debug: start_test:failed to get mobile documents path
,ok 15 should be equal
,# setup
,CoordinatorConnector-debug: teardown:failed to get mobile documents path
,# #init should register the peerAvailabilityChanged event
,CoordinatorConnector-debug: setup:#init should register the peerAvailabilityChanged event
,# teardown
,CoordinatorConnector-debug: start_test:#init should register the peerAvailabilityChanged event
,ok 16 should be equal
,ok 17 should be equal
,ok 18 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the peerAvailabilityChanged event
,# #init should register the networkChanged event
,CoordinatorConnector-debug: setup:#init should register the networkChanged event
,# teardown
,CoordinatorConnector-debug: start_test:#init should register the networkChanged event
,ok 19 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#init should register the networkChanged event
,# #startBroadcasting should throw on null device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on null device name
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on null device name
,ok 20 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on null device name
,# #startBroadcasting should throw on empty string device name
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on empty string device name
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on empty string device name
,ok 21 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on empty string device name
,# #startBroadcasting should throw on non-number port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on non-number port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on non-number port
,ok 22 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on non-number port
,# #startBroadcasting should throw on NaN port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on NaN port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on NaN port
,ok 23 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on NaN port
,# #startBroadcasting should throw on negative port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on negative port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on negative port
,ok 24 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on negative port
,# #startBroadcasting should throw on too large port
,CoordinatorConnector-debug: setup:#startBroadcasting should throw on too large port
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should throw on too large port
,ok 25 should throw
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should throw on too large port
,# #startBroadcasting should call Mobile("StartBroadcasting") without an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,ok 26 should be equal
,ok 27 should be equal
,ok 28 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") without an error
,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,ok 29 should be equal
,ok 30 should be equal
,ok 31 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#startBroadcasting should call Mobile("StartBroadcasting") and handle an error
,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,ok 32 should be equal
,ok 33 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") without an error
,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,CoordinatorConnector-debug: setup:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,ok 34 should be equal
,ok 35 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
,# #connect should call Mobile("Connect") with a port and without an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") with a port and without an error
,# teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") with a port and without an error
,ok 36 should be equal
,ok 37 should be equal
,ok 38 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") with a port and without an error
,# #connect should call Mobile("Connect") and handle an error
,CoordinatorConnector-debug: setup:#connect should call Mobile("Connect") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:#connect should call Mobile("Connect") and handle an error
,ok 39 should be equal
,ok 40 should be equal
,# setup
,CoordinatorConnector-debug: teardown:#connect should call Mobile("Connect") and handle an error
,# should call Mobile("Disconnect") without an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") without an error
,# teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") without an error
,ok 41 should be equal
,ok 42 should be equal
,# setup
,CoordinatorConnector-debug: teardown:should call Mobile("Disconnect") without an error
,# should call Mobile("Disconnect") and handle an error
,CoordinatorConnector-debug: setup:should call Mobile("Disconnect") and handle an error
,# teardown
,CoordinatorConnector-debug: start_test:should call Mobile("Disconnect") and handle an error
,ok 43 should be equal
,ok 44 should be equal
,Total: 0	Passed: 0	Failed: 0
Toggling radios to false
,2015-11-27 02:08:02.750 ThaliTest[1838:1471014] Error!: Mobile.toggleBluetooth is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/lib/testUtils.js","_funct,ionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_file,Name":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3","_msg":"    at exports.toggleRadios@/priv,ate/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore,/lib/thali-tape.js","_functionName":"createStream/<","_lineNumber":"184","_columnNumber":"5","_msg":"    at createStream/<@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/lib/thali-tape.js:184,:5"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"98","_columnNumber":"7","_msg":"    at emit@events.js:98:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/n,ode_modules/tape/node_modules/through/index.js","_functionName":"drain","_lineNumber":"34","_columnNumber":"16","_msg":"    at drain@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_module,s/tape/node_modules/through/index.js:34:16"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/node_modules/through/index.js","_functionName":"through/stream.push,","_lineNumber":"45","_columnNumber":"5","_msg":"    at through/stream.push@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/node_modules/through/index.js:45:5"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js","_functionName":"Results.prototype.createStream/<","_lineNumber":"59","_columnNumber":"39","_msg":"    at Res,ults.prototype.createStream/<@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:59:39"},{"_fileName":"events.js","_functionName":"emit","_lineNumber":"79","_colu,mnNumber":"9","_msg":"    at emit@events.js:79:9"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js","_functionName":"next","_lineNumber":"73","_c,olumnNumber":"9","_msg":"    at next@/private/var/mobile/Containers/Bundle/Application/4364FA8B-A144-4373-BA83-33DBB9E0F580/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:73:9"}]
Uncaught Exception: TypeError: Mobile.toggleBluetooth is not a fu,nction
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
