#### Test 50650278fa25325_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278fa25325/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/943B82CA-93BB-4414-A7C8-59F87A386DE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/943B82CA-93BB-4414-A7C8-59F87A386DE1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278fa25325/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278fa25325/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BE01589F-7D59-4C80-A6F1-EF4F954A5060/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56596"
,(lldb)     command script import "/tmp/943B82CA-93BB-4414-A7C8-59F87A386DE1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-27 02:34:26.915 ThaliTest[1801:1552558] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED6532F8-BF35-4D13-A271-AFE92AB6C3D7/Library/Cookies/Cookies.binarycookies
,2015-11-27 02:34:27.351 ThaliTest[1801:1552558] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-27 02:34:27.352 ThaliTest[1801:1552558] Multi-tasking -> Device: YES, App: YES
,2015-11-27 02:34:27.361 ThaliTest[1801:1552558] Unlimited access to network resources
,2015-11-27 02:34:27.369 ThaliTest[1801:1552558] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-27 02:34:29.996 ThaliTest[1801:1552558] Resetting plugins due to page load.
,2015-11-27 02:34:30.222 ThaliTest[1801:1552558] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/BE01589F-7D59-4C80-A6F1-EF4F954A5060/ThaliTest.app/www/index.html
,2015-11-27 02:34:30.366 ThaliTest[1801:1552558] JXcore Cordova plugin initializing
2015-11-27 02:34:30.367 ThaliTest[1801:1552677] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
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
,ok 7 should be equal
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
,ok 13 should be equal
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
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
