#### Test 87966432550c1e2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-07 13:47:22 - INFO Server: 'listening on *:3000'

2016-10-07 13:49:01 - DEBUG Server: 'client connected'

2016-10-07 13:49:01 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 13:49:01 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '69c95a26-6288-4061-9a85-299c5ffccd95', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 13:49:01 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-07 13:49:02 - DEBUG Server: 'client connected'

2016-10-07 13:49:02 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 13:49:02 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: 'b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 13:49:02 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-07 13:49:10 - DEBUG Server: 'client connected'

2016-10-07 13:49:10 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 13:49:10 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '8e89d8aa-678a-4caa-94d9-ddbf29d4548a', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 13:49:10 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-07 13:49:10 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-07 13:49:10 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-07 13:49:10 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-07 13:49:10 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 13:49:10 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"018be3f3-f07d-44d1-a091-4db3b08fa9d2","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 13:49:10 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 13:49:10 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"52b22790-734e-49d5-a1df-dca7fc937b51","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 13:49:11 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"d181046f-5ff2-48a3-af35-aea726d9cb11","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 13:49:11 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-07 13:49:11 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:11 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"f834da1d-bfdb-4aa9-a489-048b2e1f2fef"}''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:11 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"065c9d38-bf15-41cf-819f-2c8bdeedcb3a"}''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:11 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:11 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"cd48b940-5a9a-426b-b84a-4f8e64a84bca"}''

2016-10-07 13:49:12 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"065c9d38-bf15-41cf-819f-2c8bdeedcb3a"}''

2016-10-07 13:49:12 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-07 13:49:13 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"7f889f95-860e-4785-916e-f718e26b3afc","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"dcda9f63-7911-4120-8563-d41009ea9242","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"0ba1babd-0949-433a-86a7-f39adef458ae","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:13 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-07 13:49:13 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"3abe1037-630f-4ff6-8e8b-94d1c40242b8"}''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"0ad2017c-777a-4744-924f-239fde174866"}''
2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''
2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''
2016-10-07 13:49:13 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 13:49:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"d18fb056-9bb8-4d67-935b-ebfd6ddc6ebf"}''

2016-10-07 13:49:14 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-07 13:49:14 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 13:49:14 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"a1337b91-0f23-414c-b19e-659754aa1cd0"}''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 13:49:14 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"dd844fed-fcd7-441e-9731-26e417c8e107"}''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 13:49:14 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 13:49:14 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"7419366b-0e51-451e-b10a-b3c0ebe30dbb"}''

2016-10-07 13:49:15 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-07 13:49:15 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"d384a8e9-8bb3-4619-aea3-e18cc4fc4e8a","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"fa842307-b74c-4218-be93-29f57fda65e7","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"17232d51-9917-4199-a2b9-a27ee69312fb","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:15 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-07 13:49:15 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"35a277c0-fb2b-4b3e-a22b-e593cfe186e8"}''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"08c18c13-73c8-4a4b-af1f-28df1956254a"}''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 13:49:15 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 13:49:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"45eaab7c-a0ba-4cf2-b7c6-1eb879f78178"}''

2016-10-07 13:49:16 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-07 13:49:16 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"1765dca8-285f-4e84-9b6a-0dc4c3a38584"}''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"139001b9-8047-4798-8b9e-5d8780a21b5e"}''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"d405f205-6ed6-43da-b138-f4a23cbc5d78"}''

2016-10-07 13:49:16 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-07 13:49:16 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"22e4dbfe-09c7-41af-a414-b7f07a91e44f","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''
2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"11c6ca95-0ccc-4f70-8708-a61a3105f78b","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''
2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 13:49:16 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''
2016-10-07 13:49:16 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"11264147-7503-416a-8d60-4ef69b4c8405","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:17 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-07 13:49:17 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''
2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"6ff7906f-a00f-4d34-9f99-fb6f09f08f16"}''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"2240e512-9e96-4bc5-b659-908bc59f9477"}''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 13:49:17 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 13:49:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"be6b25cb-26b7-4732-a5f7-5f8b812690ae"}''

2016-10-07 13:49:18 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-07 13:49:18 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''
2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''
2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''
2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"f6c114c0-a048-4ada-8799-15017006a031"}''
2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''
2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"49c974b0-dfdb-4314-906b-b32d99f8981e"}''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"1f3c5f07-d377-4c4d-94cd-2b1d31351580"}''

2016-10-07 13:49:18 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-07 13:49:18 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"22372cb9-d70e-4f62-bbc0-eeefbe3ba942","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"2ff145ee-4dd1-4ecd-aafe-43ebe892b88b","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 13:49:18 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 13:49:18 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"70f596bd-a9ec-49a9-9d1c-e15f857f19fe","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:19 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-07 13:49:19 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 13:49:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"7c90b5f9-db05-4f7c-9627-22dce7e91769"}''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 13:49:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"8ebfc4c2-b2b0-4af2-aa90-933ad0675e9c"}''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 13:49:19 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 13:49:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"1b72146d-1062-4b54-adf7-76115ed2585c"}''

2016-10-07 13:49:20 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-07 13:49:20 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"b1a383ed-e9a2-43f1-a8a6-be032eb9896b"}''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"f83ae89f-a201-4562-b226-cf20ef089077"}''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"ad6aadbc-d079-4190-aef3-96940b083795"}''

2016-10-07 13:49:20 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:20 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''
2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"17244127-54f7-4e8b-9ba2-facb560038cf","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''
2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''
2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''
2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"1fc3b4e0-80db-4100-b74a-687f9468747e","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:20 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:20 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"210fb308-0940-43b3-b166-f6f30469b5e6","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:21 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:21 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"a783039f-a68a-4137-83e2-c7e3de284d76"}''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"4c661f45-089f-4d8a-a759-33c26f829d6a"}''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 13:49:21 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 13:49:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"cf75f0c8-9702-41aa-9613-e1cb4a1bc8de"}''

2016-10-07 13:49:22 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 13:49:22 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"b14a22d5-5782-4cfb-8673-f0f494f24fb2"}''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"19844fe0-ce6d-44ca-8c8e-8746ba0a2b26"}''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"4e1836f7-42ea-42de-82ad-146de890673a"}''

2016-10-07 13:49:22 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:22 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"4bbbb840-a4aa-4862-b3cf-50b5e8d857ac","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"15ddcae6-37c4-4fa3-986c-0e0b6a716248","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:22 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:22 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"7a87f722-5922-474f-872e-1eb5531bee2d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:23 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:23 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"7339fdd0-c1df-478d-985d-85bd225f4845"}''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"b6ce1330-124d-4b50-bd30-86bfad8cf672"}''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 13:49:23 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 13:49:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"c1253153-a897-41c9-b13b-fe15aff3b15b"}''

2016-10-07 13:49:24 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 13:49:24 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"6097a25b-1ef3-40c3-bee5-f1f1a3db484a"}''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"75b6248a-8bb0-4cc3-8ad5-6262d4863d1f"}''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"26995d19-314c-4305-9810-1a76df19d8f2"}''

2016-10-07 13:49:24 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:24 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"3e1ed262-9f7b-48b9-8133-136ecc48c585","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"deec005e-6db6-48e9-a776-0f09efbb3ee2","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''
2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"183a2eff-9bd2-4030-b4cd-b01c6979a694","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:25 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:25 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"415a2172-6202-46e1-9be7-06cc9b84336d"}''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"4d4e6460-1711-4fd2-85ec-a884eb1fdd39"}''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 13:49:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 13:49:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"878df2be-142b-475c-98c6-74de675e8ea9"}''

2016-10-07 13:49:26 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 13:49:26 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"e9a2ab97-facc-474b-a86d-a039bbbc8b02"}''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"432121af-184b-4ba7-9e95-28e234e117c3"}''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"64a7962f-60c6-4982-92fe-cebf6f384141"}''

2016-10-07 13:49:27 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:27 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"1df8ae94-772b-480c-b18a-5616d0ad0fa5","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"1d81e278-d16f-448b-8f3e-3889ff1eb35c","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"2068e561-4d74-454a-84c4-11f243933654","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:27 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:27 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"3fc2f220-10af-477f-8153-f6a9f14a5c67"}''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''
2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"942e6d4c-83b2-49f6-884e-25466ba9bd92"}''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 13:49:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 13:49:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"7505ea2d-3367-49b4-a371-d4ee21e2ebd9"}''

2016-10-07 13:49:28 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-07 13:49:28 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"1be6c96d-71ec-49d0-bfce-8a3fa97fc8ba"}''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"18d80da7-e10c-424a-98f7-bae0710cadb9"}''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"40a7d4d1-7e90-403a-b302-a52d1c69fc08"}''

2016-10-07 13:49:28 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:28 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''
2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"4a6d78ad-563c-44cc-bd49-cfe7aa89b9a8","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"e98af871-fa5f-4f93-86e8-c2eac24e5225","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:28 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:28 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"2b5207dd-61eb-41fc-9979-499e0725c0ae","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:29 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:29 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"e0ed103a-60b1-4b84-bc02-6f46fcba681d"}''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"01c5e683-1635-4f31-a497-8196d8ec40dc"}''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 13:49:29 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 13:49:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"d68b9971-607d-424c-8e5a-c41fc57ca558"}''

2016-10-07 13:49:30 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"e0ed103a-60b1-4b84-bc02-6f46fcba681d"}''

2016-10-07 13:49:31 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 13:49:31 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:31 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"1c5a5876-5ecd-4b1f-8dc8-6b5ff427df46"}''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:31 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"7858b160-48c5-4065-ac28-a3cc80d281a9"}''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 13:49:31 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 13:49:31 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"22b69290-389c-4aba-a6e7-a350a0bddb57"}''

2016-10-07 13:49:32 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"7858b160-48c5-4065-ac28-a3cc80d281a9"}''

2016-10-07 13:49:33 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 13:49:33 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"f71c9534-d351-4b36-ab3b-47102b07a85e","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"eed13252-f91c-4fd6-bfbd-5cacd0a0bb6a","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''
2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"c0f18613-4937-4940-90a0-9fb90f95a4cc","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:33 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 13:49:33 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"4a900646-2492-4cf7-b1fa-0251100d3a08"}''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"116dca13-a25f-4a04-b104-ca113959cb0f"}''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 13:49:33 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 13:49:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"32954263-2e63-4384-afc8-86f1d775586e"}''

2016-10-07 13:49:34 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 13:49:34 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:34 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"127ded73-babf-45b6-bf92-19a8d27c0d1e"}''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:34 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"1437c204-6090-4bcd-9657-5b2f720a7fd0"}''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:34 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:34 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"2bbe8982-9c0e-4d1f-8d99-75b1cea750d1"}''

2016-10-07 13:49:35 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:35 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:35 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"3bf3b676-fb34-4a65-9c9c-7ee2dc00b5e3","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:35 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"3271cbd7-b771-4a68-ab67-c3b108847cf6","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:35 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:35 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"b3662736-236c-4019-a745-b624c99e1396","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:36 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:36 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"f6d86a8e-f33f-4002-b8d5-f2d7d63c2b9d"}''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"543d30a5-e776-47d9-96dc-11d2547155b8"}''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"229300d7-f753-459f-afbc-480819a6ea2d"}''

2016-10-07 13:49:36 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 13:49:36 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"de9b63aa-a429-4f56-9148-3ad8253396d6"}''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"ce5082eb-b239-4907-9b25-bfdde688bd65"}''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:36 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"46e211fe-4200-4fe7-9d61-10f40b4bfd8c"}''

2016-10-07 13:49:37 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:37 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:37 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"0ce627a7-4978-4db3-91f5-9393781f86a4","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:37 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"515e27bf-4810-4402-94d4-c4a74fdd2c05","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:37 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:37 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"15ee066e-4d84-49de-9beb-69c65673f724","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:38 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:38 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"e1d1c77e-68d2-46a9-87bc-56589003341c"}''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"320bb379-1491-462b-8d40-1179ecfe6b97"}''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"38a413a6-8265-4943-ae29-66565c02c92b"}''

2016-10-07 13:49:38 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 13:49:38 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"bf4270e2-a7d2-498c-9847-47bd659afce8"}''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"cef01635-1ff2-474e-b042-873b18dccd03"}''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:38 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"583a4e1c-7ea7-4b16-bf14-020d743191f6"}''

2016-10-07 13:49:39 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:39 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:39 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"9a3c13c4-280f-49a9-9bbf-69edc0765ff8","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:39 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"323977c2-e3f4-49a5-9bee-0446f1f3952d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:39 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:39 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"f17c9e4c-f063-40a2-9888-1439f8340ae5","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"8c2b1b64-1cf4-4bc7-a534-46f9c00f9919"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"9883cebd-21cb-47a9-b754-54d6d4e5ae40"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"b52598ee-dd33-409c-8255-42b11fcbbcec"}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"1cc892a2-80e5-4bed-a14c-344e7bf4886a"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"2327a461-9587-494c-b67d-7d8b6285179e"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"117b2037-634a-476b-9137-2690e7eacba4"}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"b4bf5bdb-e8e1-4112-b147-5c5b7972562c","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"eab15e75-8160-4388-af14-87ec6c483feb","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"963857e0-57ad-430b-a2fb-ad8766ec2c79","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"264af465-dcd3-4698-8c06-b2d4b338e578"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"8578936a-7e9a-429b-a4a5-a369d3a54e6b"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"fc7dcf81-1925-4800-9082-43244632f291"}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"d3cb671c-b35e-4acc-a1c2-bf83f76f1f6e"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"7f93dd82-55c2-49e7-a1d5-5f1d75d82644"}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"8d4419f1-0b63-4c9c-8c98-ec1b2572ea6f"}''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:40 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"3d6d5060-74f3-42bf-a257-057b2b8d691e","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"f80b6a98-a8be-4a7b-b862-cd7e0684c6bd","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:40 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:40 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"f34b882d-0b44-4ace-ba37-7b0a2590aa76","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"d8ae61e2-8335-4f3a-8cba-e5e3c228fca8"}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"d9252f6b-c288-44ae-8b8e-1bb4255f3bce"}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"f9f1fab9-338c-4398-b001-d5e8c54bafe1"}''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"3202f56a-164e-41ce-a7f8-e2a4ebe8184b"}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"f90ebe22-d506-40d6-a503-9e0d9a7a102d"}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"8eb39228-14ad-476e-b741-7e9605161ca2"}''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:42 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"a0da1da9-259f-4ff0-8188-ea916ab03a9c","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"f885fe4a-86e9-4331-ab3f-709d6fede61f","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:42 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:42 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"b7eddef5-db22-4c59-95e8-e36eb4708403","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"e2537a8c-d978-41ef-a10e-be5458edfbee"}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"f267c626-085c-4f1a-8c34-9bcc1a04bf1a"}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"cc460701-0058-42bc-b869-e8018c513ab8"}''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"97a50a61-2025-4bdc-b389-cd0f9564cdf3"}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"46a8d9f3-c19a-49fe-b58d-b042e06ecc26"}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"6347f2b8-3e36-4c62-bbb3-62bee1ec1e7c"}''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:43 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"c710a03d-d706-46b9-8de3-63c9d0b41ddc","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"d492503b-04bd-4e5b-a355-61aa36dd677d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:43 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:43 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"a99c95cc-4927-464f-8405-061597efd3c9","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"b0fae2bc-43b7-4e8d-96f6-efa67c393905"}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"ee76c8e8-0b5f-4e5d-8721-db834df9cac9"}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"81c0addb-c364-464f-add7-73cbc2b87668"}''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"af7985ca-0e92-49b0-843a-ae4a0219076f"}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"1d24b0ec-3e54-47f3-be3e-7013c254c5f6"}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"03aa7ea9-9669-41e7-9944-75e6f9572405"}''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:44 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"5ea58d81-6a6f-432e-8627-ff61950d3738","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"3d9d5c2b-465c-4ecb-b399-fe50310e2cb1","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:44 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:44 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"aa0eb2c1-8454-4460-a331-30341266e2ce","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"aba1b632-7c09-449f-ac43-b8bf0d2b46f0"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"cb39aae4-e1d8-4996-a2de-3e74eedc23fe"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"76da32a6-55d6-412d-8154-1ce92770c1ef"}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"d54c3b16-fe12-4c71-9d22-3b5362d93509"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"147a6acd-f3b5-4ab1-9307-56d05d32a7fe"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"9bef62d1-f038-428c-9c4c-c387ceb52489"}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"f6500628-db3c-4146-9230-392ad36d258b","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"16330878-eb90-4525-b9bb-66ef420b1460","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"3e5816fb-1239-484f-b85b-9d31d3168740","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"4e0323b9-b2dc-4d2e-a693-a7a245089f80"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"c6d484ea-4ce1-472e-972e-ff357cf2e457"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"6a586320-e57d-485b-82e9-97441ec57add"}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"1a9386fa-d78b-4580-8b87-c12cb4b4fb50"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"9abad4bb-71e8-42d6-a365-8619b122675c"}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"8d6bdb63-3a62-4e2d-b327-5f471d4385c6"}''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:45 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"ca907930-d829-45e1-830a-f2c926ca4304","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"02bb5b21-7fef-4f8e-b5aa-e27a309a49d6","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:45 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:45 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"b6339219-c672-4aca-9d9d-f5621458a08d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"5b4d01c4-415d-435a-9f7d-01bc9f455c85"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"f085a448-e4f8-454a-b741-c77e1e543469"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"d28e109f-6805-40fc-867d-f76c8eefc715"}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"c8b469ea-119c-4dc8-88e0-caeaf028dff3"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"b8785fc0-8ff3-42a5-b845-0d47396e3478"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"ee95d53a-0467-4bad-b0a9-96473efed456"}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"8f2d9dee-828c-46f2-88e9-21e40d87cdbf","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"d4a55033-99e7-4cc8-afed-e2a7356337c6","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"02eb5ed7-a152-47e1-aa50-335ffabc8d31","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"a8d2debb-7940-4f01-bdbb-754d860860c6"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"6e0dd680-b322-44fb-a329-05ace5ed8bb4"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"be5802f8-c909-4c12-831c-185b3e4987ba"}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"5a374b39-9ca8-405b-920c-bdc83951b704"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"548c165c-ec63-47d5-a594-6c9f9b841e73"}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"87b9c0c5-a9ac-492b-9142-8e3ee3def7d7"}''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-07 13:49:46 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"f4804875-9ffc-4912-8ad7-9c5939765df8","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"8c96e76d-5acb-4a52-88b5-fe5c20914a10","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 13:49:46 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 13:49:46 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"c519cb4e-ec49-4d8e-b893-7c2a856a2bda","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"e8bc668e-202d-4d5d-b17a-594f2b86f15f"}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"ce59f278-a9bf-4ae4-912e-e59c9a23f517"}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"bfa4fa7a-faa3-4cb7-a986-1165ab156c97"}''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"7eaa42bc-455d-4450-9df5-4546e23b8733"}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"e7c1da78-5967-45b1-a1f7-0c38c6df9917"}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"ac6dcb2e-2be2-4f0e-8d18-bab0d4d19729"}''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-07 13:49:47 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"90ce98c3-69b9-4114-902b-ce2a7c22f4fe","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"655e848b-a133-491d-9648-fedf73ac8f82","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:47 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:47 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"dfc70799-a562-4e82-82b3-d20fe5d3e83c","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"a315cb56-dff2-476e-8616-a82c6678f763"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"4ad1e834-f70d-4080-ba86-c4dc71c85e1c"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"4c7e6552-f399-4e59-abee-ff85d4cdca66"}''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"8ae9c0c2-6d5c-4e7e-a7f2-865506b51368"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"b767e183-5b0b-437b-9e84-51daea6b30a1"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"d3136146-0b23-4d65-9ded-c49a1c2fb657"}''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"af421027-cf64-4cf9-9edc-73dc4c99691d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"734ed7dd-b2d4-46ee-a219-eeca4dae4008","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"f1927caa-71ac-4a86-a364-496d905a288f","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"5b4ede3c-4c95-40f5-9c58-a78af0d00d36"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"b8d4911e-0ef4-4771-8cfe-f48394cbba95"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"89a195c3-bbb0-4e19-8892-32a18b8088f2"}''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 13:49:48 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"e004944b-a362-4a68-85f5-e7d43c652f70"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"dd8fa68b-4fa0-4a30-ba01-13527d9099d3"}''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:48 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:48 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"2f397348-ed63-4c0c-8003-9d9426e77eae"}''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"1d9205c4-9ece-43fd-a968-e867eb007754","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"a9278977-775f-43ce-9d20-9ac000719ec0","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"9ae61c3f-a4f6-4787-9d5f-a2031323b93d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"cd3cc01e-2ed8-487d-912a-ffceddceeea5"}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"f590546e-0cd1-4933-99f0-a2ac82095d27"}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"e66acb8f-7ef2-4b43-b5c8-18973057b679"}''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"67c03997-c477-4476-9e31-31d21bf20d96"}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"1fd70c49-1c9a-4cd4-a041-50b2eefd9b59"}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"39a2346a-43d5-4d7e-a0f8-3f037fb1ba4e"}''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-07 13:49:49 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"6a8d2146-1e6d-4570-8daf-2c311bd60c4b","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"9b512e02-c669-492a-8092-cc05808f4912","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 13:49:49 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:49 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"c53b39ad-6fde-4ba7-acc6-b38b2480c233","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"3a99cff2-73d9-433f-9d7c-3da4d9000a25"}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"89a31ec4-67f8-4a0a-bfe2-d0757a72a572"}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"0188e5c1-1245-4501-8500-8f66b4c71295"}''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"b4869184-f517-4c5d-8a5a-99368b73c680"}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"85888bac-04d4-4f4a-8ba6-b03d3165d53a"}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"91204643-7b2f-491b-bd53-e491aa234082"}''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:51 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"7ab211d2-ca21-4ea9-a62f-94d9411e5e37","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"26b0338f-f6e7-4f6d-830c-c287fb95fb5d","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:51 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:51 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"2deee20a-aa7b-49b9-b612-d59fb7004f72","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95"},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860"},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a"}]}''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"ac59e91f-d628-469b-b4a4-645603c3a936"}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"4f6e9855-3727-4b60-bb21-11356d79a698"}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"9a04c00e-acf1-4314-853a-afe839e8ab9f"}''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"f0ec5023-c158-4225-9c01-8b1587309840"}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"47d84fce-9d82-465c-a4a3-8ca824bb3a18"}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"2233d1de-91fd-44b5-83f2-6171ad247a3a"}''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-07 13:49:52 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"33f0aba3-a7d4-41d8-92df-41b2645f7092","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95","data":[4,214,51,137,220,186,137,74,255,223,207,3,236,69,78,140,118,52,93,63,27,66,183,109,154,103,78,207,45,67,86,108,40,177,44,40,109,1,97,1,53,178,236,235,224,166,81,204,28,86,229,70,229,8,75,210,169,155,129,64,81,101,173,62,74]},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860","data":[4,60,176,170,182,42,191,110,123,129,204,79,35,154,50,53,214,170,161,206,25,192,171,188,58,104,247,50,197,193,120,157,69,103,116,190,60,150,35,167,26,61,156,65,41,214,170,220,229,31,221,247,155,81,100,209,52,174,119,17,102,123,254,12,97]},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a","data":[4,250,244,207,221,127,227,112,163,194,56,150,105,221,96,77,243,242,142,217,135,176,86,19,92,47,103,41,157,253,56,119,216,96,150,25,241,138,131,252,247,210,93,48,53,62,0,39,49,234,154,227,144,218,211,7,221,28,99,59,215,148,28,242,27]}]}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"d5b93eb6-433a-4ad0-a7fb-171f526bd039","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95","data":[4,214,51,137,220,186,137,74,255,223,207,3,236,69,78,140,118,52,93,63,27,66,183,109,154,103,78,207,45,67,86,108,40,177,44,40,109,1,97,1,53,178,236,235,224,166,81,204,28,86,229,70,229,8,75,210,169,155,129,64,81,101,173,62,74]},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860","data":[4,60,176,170,182,42,191,110,123,129,204,79,35,154,50,53,214,170,161,206,25,192,171,188,58,104,247,50,197,193,120,157,69,103,116,190,60,150,35,167,26,61,156,65,41,214,170,220,229,31,221,247,155,81,100,209,52,174,119,17,102,123,254,12,97]},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a","data":[4,250,244,207,221,127,227,112,163,194,56,150,105,221,96,77,243,242,142,217,135,176,86,19,92,47,103,41,157,253,56,119,216,96,150,25,241,138,131,252,247,210,93,48,53,62,0,39,49,234,154,227,144,218,211,7,221,28,99,59,215,148,28,242,27]}]}''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 13:49:52 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 13:49:52 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"101afab3-5d67-4df7-a7cb-19ba8b45712e","content":[{"uuid":"69c95a26-6288-4061-9a85-299c5ffccd95","data":[4,214,51,137,220,186,137,74,255,223,207,3,236,69,78,140,118,52,93,63,27,66,183,109,154,103,78,207,45,67,86,108,40,177,44,40,109,1,97,1,53,178,236,235,224,166,81,204,28,86,229,70,229,8,75,210,169,155,129,64,81,101,173,62,74]},{"uuid":"b5edb1e7-f2cc-48f0-b8f9-5b8a06fee860","data":[4,60,176,170,182,42,191,110,123,129,204,79,35,154,50,53,214,170,161,206,25,192,171,188,58,104,247,50,197,193,120,157,69,103,116,190,60,150,35,167,26,61,156,65,41,214,170,220,229,31,221,247,155,81,100,209,52,174,119,17,102,123,254,12,97]},{"uuid":"8e89d8aa-678a-4caa-94d9-ddbf29d4548a","data":[4,250,244,207,221,127,227,112,163,194,56,150,105,221,96,77,243,242,142,217,135,176,86,19,92,47,103,41,157,253,56,119,216,96,150,25,241,138,131,252,247,210,93,48,53,62,0,39,49,234,154,227,144,218,211,7,221,28,99,59,215,148,28,242,27]}]}''

2016-10-07 13:52:53 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:53 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:53 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 13:52:53 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:53 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 13:52:53 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:53 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 13:52:53 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:53 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:177:5
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:142:10)
    at TestDevice.error (/home/pi/Test/server_87966432550c1e2/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/UnitTestFramework.js:89:23''

2016-10-07 13:52:54 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:54 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:54 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:54 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:54 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:54 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:55 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:55 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:55 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:55 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:55 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:55 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:56 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:56 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:56 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:56 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:56 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:56 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:57 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:57 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:57 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:57 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:57 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:57 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:58 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:58 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:58 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:58 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:58 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:58 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:59 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:59 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:59 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:59 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:52:59 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:52:59 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:53:00 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"2eaaa7c0-d080-4fd8-b754-3c1102e6e6b3","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:53:00 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:53:00 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"570e5534-fb3f-43f6-9682-d82a85a04f27","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:53:00 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 13:53:00 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"760a910a-9a74-4016-81a9-97d24967d95c","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 13:53:00 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432550c1e2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432550c1e2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432550c1e2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali05
Console output:
```
Stopping app on  ce0616068b9f212302
Uninstalling app on  ce0616068b9f212302
Stopping app on  ce061606e320561102
Uninstalling app on  ce061606e320561102
Stopping app on  ENU7N16516000107
Uninstalling app on  ENU7N16516000107

All devices are ready!

Deploying to ce0616068b9f212302
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce0616068b9f212302

Deploying to ce061606e320561102
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ce061606e320561102

Deploying to ENU7N16516000107
Marshmallow device. Granting ACCESS_COARSE_LOCATION permission.
App was succesfully deployed to ENU7N16516000107

Starting application ThaliTest on ce0616068b9f212302

Starting application ThaliTest on ce061606e320561102

Starting application ThaliTest on ENU7N16516000107

App was succesfully started on ce0616068b9f212302

App was succesfully started on ce061606e320561102

App was succesfully started on ENU7N16516000107

STOP log received from ENU7N16516000107
Test has FAILED

Device test finished on ENU7N16516000107 
STOP log received from ce0616068b9f212302
Test has FAILED

STOP log received from ce061606e320561102
Test has FAILED

Device test finished on ce0616068b9f212302 
Device test finished on ce061606e320561102 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87966432550c1e2_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87966432550c1e2_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87966432550c1e2_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)




