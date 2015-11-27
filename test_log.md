#### Test 50650278265fe5c Logs

Status: 
```

ios : false

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

2015-11-27T02:08:38.201Z (0 sec) - [object Object] tests will start after waiting for NaN seconds

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


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278265fe5c_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278265fe5c_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278265fe5c_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278265fe5c_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)


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

2015-11-27T02:08:38.201Z (0 sec) - [object Object] tests will start after waiting for NaN seconds

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


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```

