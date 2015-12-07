#### Test 5065027860d2bae Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4}}
listening on *:3000

New unit test device:UNITTEST-0.1335434728214473

New unit test device:UNITTEST-0.1017197271142638

New unit test device:UNITTEST-0.8490445262789056

New unit test device:UNITTEST-0.8324425557971814

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

Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

Running test: ThaliEmitter calls startBroadcasting twice with error

Running test: ThaliEmitter throws on connection to bad peer

Running test: ThaliEmitter throws on disconnect to bad peer

Running test: ThaliEmitter can discover and connect to peers

Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

Running test: ThaliEmitter handles socket disconnect correctly

Running test: ThaliReplicationManager can call start without error

Running test: ThaliReplicationManager receives identity


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
true

```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5065027860d2bae_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5065027860d2bae_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5065027860d2bae_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5065027860d2bae_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)




