#### Test 50650278f3f3060 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-27T12:48:57.027Z (0 sec) - [object Object] tests will start after waiting for NaN seconds

listening on *:3000

Running test: multiplex can send data

Running test: basic

Running test: another

Running test: successfully create a new pkcs12 file and return hash value

Running test: successfully read a previous pkcs12 file and return hash value

Running test: failed to extract public key because of corrupt pkcs12 file

Running test: failed to get mobile documents path

Running test: #init should register the peerAvailabilityChanged event

Running test: #init should register the networkChanged event

Running test: #startBroadcasting should throw on null device name

Running test: #startBroadcasting should throw on empty string device name

Running test: #startBroadcasting should throw on non-number port

Running test: #startBroadcasting should throw on NaN port

Running test: #startBroadcasting should throw on negative port

Running test: #startBroadcasting should throw on too large port

Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

Running test: #connect should call Mobile("Connect") with a port and without an error

Running test: #connect should call Mobile("Connect") and handle an error

Running test: should call Mobile("Disconnect") without an error

Running test: should call Mobile("Disconnect") and handle an error

Test run complete



-== UNIT TEST RESULTS ==-

RESULT: PASS

23 of 23 tests completed
23/23 passed (0 failures)

---


multiplex can send data - pass

basic - pass
another - pass
successfully create a new pkcs12 file and return hash value - pass
successfully read a previous pkcs12 file and return hash value - pass
failed to extract public key because of corrupt pkcs12 file - pass

failed to get mobile documents path - pass
#init should register the peerAvailabilityChanged event - pass
#init should register the networkChanged event - pass
#startBroadcasting should throw on null device name - pass

#startBroadcasting should throw on empty string device name - pass
#startBroadcasting should throw on non-number port - pass
#startBroadcasting should throw on NaN port - pass
#startBroadcasting should throw on negative port - pass
#startBroadcasting should throw on too large port - pass

#startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
#startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

#connect should call Mobile("Connect") with a port and without an error - pass
#connect should call Mobile("Connect") and handle an error - pass
should call Mobile("Disconnect") without an error - pass
should call Mobile("Disconnect") and handle an error - pass
-== END ==-



ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true

```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278f3f3060_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278f3f3060_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278f3f3060_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278f3f3060_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278f3f3060_Enable_UnitTest_tobybrad/iOS_server.md)




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
Test ID 0 configuration: testSendData.js, server timeout: 1200000, data:

{ timeout: 1000000,
  rounds: 1,
  dataTimeout: 10000,
  dataAmount: 100000,
  conReTryTimeout: 5000,
  conReTryCount: 5 }

2015-11-27T12:48:57.027Z (0 sec) - [object Object] tests will start after waiting for NaN seconds

listening on *:3000

Running test: multiplex can send data

Running test: basic

Running test: another

Running test: successfully create a new pkcs12 file and return hash value

Running test: successfully read a previous pkcs12 file and return hash value

Running test: failed to extract public key because of corrupt pkcs12 file

Running test: failed to get mobile documents path

Running test: #init should register the peerAvailabilityChanged event

Running test: #init should register the networkChanged event

Running test: #startBroadcasting should throw on null device name

Running test: #startBroadcasting should throw on empty string device name

Running test: #startBroadcasting should throw on non-number port

Running test: #startBroadcasting should throw on NaN port

Running test: #startBroadcasting should throw on negative port

Running test: #startBroadcasting should throw on too large port

Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

Running test: #connect should call Mobile("Connect") with a port and without an error

Running test: #connect should call Mobile("Connect") and handle an error

Running test: should call Mobile("Disconnect") without an error

Running test: should call Mobile("Disconnect") and handle an error

Test run complete



-== UNIT TEST RESULTS ==-

RESULT: PASS

23 of 23 tests completed
23/23 passed (0 failures)

---


multiplex can send data - pass

basic - pass
another - pass
successfully create a new pkcs12 file and return hash value - pass
successfully read a previous pkcs12 file and return hash value - pass
failed to extract public key because of corrupt pkcs12 file - pass

failed to get mobile documents path - pass
#init should register the peerAvailabilityChanged event - pass
#init should register the networkChanged event - pass
#startBroadcasting should throw on null device name - pass

#startBroadcasting should throw on empty string device name - pass
#startBroadcasting should throw on non-number port - pass
#startBroadcasting should throw on NaN port - pass
#startBroadcasting should throw on negative port - pass
#startBroadcasting should throw on too large port - pass

#startBroadcasting should call Mobile("StartBroadcasting") without an error - pass
#startBroadcasting should call Mobile("StartBroadcasting") and handle an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") without an error - pass
#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error - pass

#connect should call Mobile("Connect") with a port and without an error - pass
#connect should call Mobile("Connect") and handle an error - pass
should call Mobile("Disconnect") without an error - pass
should call Mobile("Disconnect") and handle an error - pass
-== END ==-


```

