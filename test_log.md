#### Test 879664325d33342 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-07 14:35:11 - INFO Server: 'listening on *:3000'

2016-10-07 14:36:47 - DEBUG Server: 'client connected'

2016-10-07 14:36:47 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:36:47 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '7f4cd8e4-1243-4faa-bbad-c99b5ad6e022', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:36:47 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-07 14:36:48 - DEBUG Server: 'client connected'

2016-10-07 14:36:48 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:36:48 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '8b997ee1-66ab-42aa-a985-f7ffb1a293f9', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:36:48 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-07 14:37:01 - DEBUG Server: 'client connected'

2016-10-07 14:37:01 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:37:01 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'b3fae7b0-771c-421d-8236-8112b55e1ba3', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:37:01 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-07 14:37:01 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-07 14:37:01 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-07 14:37:01 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-07 14:37:01 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:37:01 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"8e8e2477-5470-40fe-82b5-847b9919aa40","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:37:01 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:37:01 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"e775951b-d6f0-4f81-92ad-4792366ea131","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:37:01 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:37:01 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"7e24ce42-a3b9-4f54-8966-2b4ffd65f535","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:37:02 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-07 14:37:02 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:02 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"20fa5136-38a3-4c16-95d1-b51e95b685a6"}''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:02 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"5e0acede-1da6-4e59-8a6c-6493e32ae5fb"}''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:02 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:02 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"0fe3f4c1-ce3d-4f0f-99bb-251151aca698"}''

2016-10-07 14:37:03 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"20fa5136-38a3-4c16-95d1-b51e95b685a6"}''

2016-10-07 14:37:03 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"5e0acede-1da6-4e59-8a6c-6493e32ae5fb"}''

2016-10-07 14:37:03 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-07 14:37:03 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:03 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"700adbb6-8d3b-480c-a65d-0df3e23cbb07","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:03 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"cc6ec720-af24-45d0-a9dc-285b2036bfae","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:03 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:03 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"eec182e2-a605-484b-998f-f33a76538b9e","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"96a1f3c1-a5fa-4d21-8d21-a08923e82fde"}''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"247c0238-7331-47ca-a2d1-c2cabecba019"}''
2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''
2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''
2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"2cd4a733-8b82-4fdb-883b-2d37db0e0656"}''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"d686aea5-4df8-4ffa-a5f5-ed7524cc8e41"}''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"2fe517a6-c235-43d8-b13c-664880214eef"}''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"b1259b41-89ac-49f8-8f72-343875eb3ec7"}''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-07 14:37:04 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:37:04 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:37:04 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"ee2df203-4933-4aa0-8d6d-a91ea51d77e2","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:37:05 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"2fe12ca1-35b6-4b16-ba69-85e3df096c76","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:37:05 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"b0161fb3-effe-43d4-8172-74fe03a2723f","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:05 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-07 14:37:05 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:37:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"d087f2e3-5b2c-49d7-a3be-1f8f5fd3f08f"}''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:37:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"954748cc-42ac-4db6-9e60-0f769ab9db31"}''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:37:05 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:37:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"10c86032-516d-42f8-9dff-86f59759fec9"}''

2016-10-07 14:37:06 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-07 14:37:06 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:06 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"e391595f-ec3a-484f-92fe-b8d41bdcf7a3"}''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:06 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"254baff0-f097-41e8-b704-b11adda92050"}''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:37:06 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:06 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"eb47d57c-c3e8-435c-8a9f-a0da52a59f38"}''

2016-10-07 14:37:07 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-07 14:37:07 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:07 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"8eaf186b-d911-4ef1-bd61-7460ce38bad9","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:07 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"3d3639bf-d09e-4c00-bdfb-8e335f6d14b1","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''
2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''
2016-10-07 14:37:07 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"fd17dd81-cea9-4296-aabb-5ad4c1f10d75","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:07 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-07 14:37:07 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''
2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 14:37:07 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"ec82a6c2-c181-465d-af04-2730b87c9ffa"}''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''
2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"be182553-5c3a-4614-b893-c520cb32c8ce"}''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''
2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"d84f75a6-df59-4521-a3b7-38fcb9be7ccc"}''

2016-10-07 14:37:08 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-07 14:37:08 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"1174f48d-4894-4f8a-9b10-e988bc6f7ad3"}''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''
2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"8e6ba8ff-12aa-4741-b186-ba258e478bbd"}''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''
2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"cda23506-39a5-4664-8a5a-9bfb44a3a890"}''

2016-10-07 14:37:08 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-07 14:37:08 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"5c7aaec7-f429-4ddb-a58c-ccd2e51aa061","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"f79eb972-30b0-45ee-963a-54dc9d39f536","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:37:08 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:37:08 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"cdbeea2c-677c-4bf0-8a5d-7188fa7c507a","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"e4ea456c-26dc-4619-ba15-2aa01b00b73d"}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"aa451c0f-2ae7-4127-8cfe-ffb412d819f3"}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"13809414-09c9-4e84-b3a5-7df251a528c8"}''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"d3eb6b50-b5bf-4603-ab15-3bb5e644a5d4"}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"e459c206-ac76-43d5-bb75-3dac40387353"}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"cf5e53a4-5b4b-42b2-b031-688f34393167"}''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:09 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"a340507e-b12e-48a2-a8a9-aee70abbd031","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''
2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"aafe2c1d-a6c7-42a9-91b0-a7fa6f7bbd92","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:09 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:09 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"64a51057-afd0-4725-a4c8-20f3dafa8069","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"efca6cf8-fdf7-4a15-b11c-0efedfa713ba"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"ee5a9ff9-debe-4d20-a4c4-aa7728cdb461"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"80943f44-7f15-47d1-8634-701dc6e4151d"}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"62043081-eeab-435c-9e45-d468c91efdbc"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"0c4af9bb-1bfa-4739-958e-8a18f193ebe3"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"6b39f414-ad44-4e93-b90d-4573008d0047"}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"b939d135-15d6-492e-be6c-71ddb997b248","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"100c2278-fe14-419c-b0c5-09b75c505832","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"923a4635-36cd-4460-bc14-c72b8dbea867","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"ff80733b-715f-44e4-8d1c-8d56bd9b6253"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"61ff9ab0-4d80-421a-95d4-a755a55a2336"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"96aeae02-08ba-4e9e-b0df-b5e1aeadfb3a"}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"fba317b2-ff46-4c1b-ae93-3181d1c90879"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"bb14b633-c3f2-45f1-8ebd-bc523447a224"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"0ac0dc59-dccc-43c4-89dd-0c2a87bc951a"}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"96253ccc-767b-46b6-b591-7389513310c8","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"12e616e0-fd9f-4ee0-96b2-87e5e7998160","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''
2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''
2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''
2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"0a7a6bd0-6ca7-4dbb-99c4-43080b374fbf","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"faa40d53-5d61-45d0-b4bf-ce399610893e"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"cf9f441a-9a17-45a8-af6b-d115d11fd860"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"e31a799e-3f4f-4baa-94e8-2caf85d9cae4"}''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:37:10 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"6a5e014e-8755-4a1d-842c-0ef9c0490de0"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"8b0226df-64f6-4090-97bb-8c1f11d5b29c"}''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:10 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:10 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"f49f069f-3829-482a-9604-2a76c3d8c444"}''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"013efbe0-9452-4c56-b02b-2a57af6045c3","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"ffc3f2c0-d079-4865-b02a-c1a0b95e7d14","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"892b2a28-d6ce-4d84-b373-eaeda7278e4a","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"81aadafc-3d0e-4f60-8aba-6c29e1a07f7b"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"84c545ea-d1df-4009-b7cd-5ccb37a3b5a8"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''
2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"b0b5e1bd-e319-4e91-af17-2ddcaba23f86"}''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"044ec7f3-baa2-42b3-a4bf-17a287d16b7f"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"46d6e924-b4a1-4a11-9ecb-8ddc1d6d9b8b"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"5a90d97e-bcaa-4658-a99a-116e0f22bea7"}''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"ed147424-c5de-4a01-8b4a-0542c5c8528f","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"e7ed5c76-b1e7-4be1-a394-549c1e1279b9","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"1d3dfbf5-7b1d-487f-93ef-ecf88eee7eb4","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:11 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"1fcd52ef-451b-4993-8069-4d9f56ea687b"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"4f5687e3-9460-44b7-9e66-85ab7e1a3772"}''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:37:11 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:37:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"416cd690-b9e7-4731-8bf6-fd4033f737f8"}''

2016-10-07 14:37:12 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"1fcd52ef-451b-4993-8069-4d9f56ea687b"}''

2016-10-07 14:37:13 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:37:13 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:37:13 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"2e5ddef7-7a18-4f7d-b9e9-49698c46f546"}''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:37:13 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"9e00dc34-d36c-40cb-bd3e-e97b58c08393"}''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:37:13 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:13 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"66679088-97c6-449a-8032-09ba3215efcf"}''

2016-10-07 14:37:14 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:37:14 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"c9265aff-9348-4c5b-b4d0-9a285cd7bdfa","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"3d161c0f-aa64-405a-819f-3a1c644f56f4","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"e1c1253b-383d-40bb-8c64-129e69707a94","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:14 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:37:14 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"834bbd80-9e3f-467e-835d-4e22ed1f5ac9"}''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"1ea7d0e2-4ab0-49c9-9d9a-a1689d2b7eff"}''

2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:37:14 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:37:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"19d6dc79-bd18-4992-949d-bf3de5cb0512"}''

2016-10-07 14:37:15 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:37:15 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"8f1c13fb-3bc6-4bd1-b41c-1f7fbcaa67d1"}''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"94026365-a55a-4878-a388-5ac30f1e469a"}''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"a0a33541-9474-40b7-95d5-95b8702bb55d"}''

2016-10-07 14:37:15 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:15 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"3ea362ae-99af-44a6-a4a1-fa6393b27f28","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"9ad82de3-ec11-4569-9075-db267b989b34","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:15 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:15 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"bab744f0-c384-4aa8-b1de-7c5b74af7995","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"44839b55-40b6-4c3c-8f5d-7e5a1d599cab"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"c8106d38-5b9b-42be-b6fd-1e810bf402fc"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"2534a4ce-a5ee-4a13-8c66-7d0e3742c2ef"}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"9bb49415-eb20-461d-8f92-dc49f0eab3f2"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"25475931-ad93-4676-9ee3-57d1a8b043df"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"be1ff629-eac4-4fad-879e-700b25f44bd5"}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"33122909-21d9-4294-87e5-fb9dd9d4a95a","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"167e6106-57f5-449c-8e30-479859c6fd03","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"92b5905a-b145-42b5-8157-0479478211f8","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"5b77d512-455f-40ef-a304-996d984f689f"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"e7f5148a-7be5-4711-b630-8396a729e7a9"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"5f7b6605-c268-42b9-b918-a9bdc76e6572"}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"e0279236-a3ec-409d-b4ff-9c44f4d59da1"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"86d0a164-3953-4c6e-9289-1bc67e00962b"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"6a3dc59e-7539-4591-af6d-8bd5631ee45b"}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"a7a5d6c5-33d2-464f-a928-bf2691aa8d22","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"6bdf4a97-78fb-4470-a954-e486899f6f68","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"609c7db7-b4bc-436e-899a-2fe21add459b","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"c5f8169d-413e-46b2-a2bd-c662e730db63"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"dfc16b93-3a92-47e2-9136-20bc634aaaf8"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"18c2d550-1006-4b1f-972c-46b8a89fbc2c"}''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:37:16 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"30378f2f-8573-4be6-ad67-91c047c12758"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"4ee21497-852a-4661-bb3f-3d5d68280d16"}''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:16 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"dce9f456-2a2a-4de5-a1c3-76984e3f421d"}''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"7632e90d-5ca8-4650-aaf9-96ee5b1180f8","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"b9e7cf7a-0c49-422e-8f13-be22118e268e","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"33ed0943-bdfd-4a81-8b75-5f1a96a0dfd0","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"390059e3-a632-462a-90ed-6b535680a997"}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"3aded969-e5e5-4ccc-9e5e-0b6840ad9ad0"}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"d6244877-1b20-4986-ac7f-0482a18e0b92"}''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"cc61c0b5-00c6-44be-87ed-2b7559dfb938"}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"d8a59de2-0da4-4f5c-8097-781adef74cf2"}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"87b8a4e7-efd3-4ef0-b5d4-44d7c08bf90c"}''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:17 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"680b062f-ae33-4c05-a607-f70726834b41","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"e6828252-726d-420e-b512-37439d01ca5f","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:17 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:17 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"98d61beb-509f-4edf-ad3b-f9daaf5f4703","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"96e92802-585a-4848-b956-41e3795d5e7f"}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"d9a8c45a-81c2-4f08-8429-0c57b9539d8a"}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''
2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"b990d08f-8f9b-4495-99de-a1b65d352fac"}''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"b6458280-d954-41c6-9bc2-e9cfc24d925b"}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"a77cf7df-e9ad-4d3e-9917-ea25e23af420"}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"56d0867f-5e0d-4f12-a782-39e71845791d"}''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:19 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"755f36e2-2459-438a-abd2-f9e0842398aa","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"e3e8b904-8cac-4aae-83de-2bb24a82caab","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:19 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:19 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"d924ad10-d600-4c52-9e96-657c38a554c5","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"4239eebd-cb30-4b13-8e8b-ce48923d497a"}''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"3f0eb192-b441-47cb-9d04-07187332df20"}''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"b7adf8e7-a067-4ae3-bbbc-beb642a9adbe"}''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''
2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"ba39a0c1-8362-4d22-b0a2-d1bd8bd48933"}''
2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''
2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"b5c97dc2-5cad-446a-87e5-68870379b54a"}''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"31964f59-e516-4a41-b334-1850ef4d7ed6"}''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:20 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"bc25c48b-5d76-4417-ad13-58246ebc2a16","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"92059984-5b83-48ad-a5e1-00aabd15b992","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:20 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:20 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"5d88d36d-0207-43b0-849b-316adde6c3fd","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"a21b5915-910d-410b-8a4f-34856f6fecf4"}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"cddcacfe-d15a-4b9f-b7d8-cd43105500df"}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"c5ab3d00-3037-4df1-a193-7865bce60f15"}''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"1a06f63d-5849-475e-939d-cd6e633c327f"}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"def306ae-ba8b-4358-bf76-32df7420c0b5"}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"6d931930-cc59-43b6-b9c0-704af584a1aa"}''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:21 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"f147918e-4905-4cbd-9505-130e2ff72574","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"e4ef25bb-a750-4abd-9ff8-97cd39de42e0","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:21 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:21 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"bf170b98-a0ec-4183-98d1-18db376939de","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"9750a097-bb08-42f0-88ef-f3b586b3d9a9"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"8be77dc0-f17b-4031-ac44-e32eae5d9586"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"36b7ad5e-ca98-46e7-a1d8-0a4876be75dc"}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"6f42176c-f742-49cc-84cf-05250f5ef3f5"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"dee05d79-51c5-4027-8453-44f3cb755aac"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"24001683-14e5-4627-9759-739796ecade2"}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"9cd03fa8-1001-49b0-83b0-6980b43c5e6d","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"85583146-ef7d-49e3-8c7f-d6e0a0893f60","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"651d0f3f-f97e-465e-90bd-0480231a83c4","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"a3260839-f28a-47f8-bce4-21746ac1bfa9"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"e8ed3cc6-e754-4a83-bb2a-4291f47f6369"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"3c1146a4-3f2b-4c46-adda-09429e42eda2"}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"b4c24c71-80ea-444b-872a-7289e1f03a70"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"98a405f4-f9bc-4c0b-8e90-9e654175bc1b"}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"a37fbd2b-d7b4-4949-b528-6f93d936e01c"}''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:22 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"8e332b02-b348-4785-9592-90aadac9c841","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"5c72946a-90ea-40c9-8bba-03af8ec90ab8","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:22 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:22 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"8b3e6d47-462c-4b79-9884-1f54b449459b","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"da8852e6-f76c-4a32-af4d-79b825d208ec"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"451827fe-b3b0-4ef7-8929-76e8821ecddc"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"8ddadbaa-5ad3-47e7-9c11-c78b5c925f49"}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"676eb9ee-edf4-41f0-a003-3bfcc351a64e"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"01d9fdc6-5ff0-4e0b-9779-7e7ec7d85ddb"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"930fb421-cb0d-4bd6-b97e-a2f85379c5f8"}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"4991b793-cd4a-4d92-9746-419bec9188a2","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"0f5a7489-1426-4ca7-a86d-f9f331117973","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"47466f03-d417-4ad4-9ae3-9f30fa7a7847","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"8cfec1b1-7b3d-47a7-b5c4-eb7c5f79ea6b"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"04772dbe-9c00-437b-ac8a-f9f5ecdff37f"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"52731a61-b51c-4095-8adf-257c13dfdbf1"}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"76909740-04e5-4590-9f8a-bbd0525b9100"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"daa750de-7652-4117-a572-d5f371bc59d5"}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"fecafe7d-07ff-4f52-99a5-875e118b8081"}''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-07 14:37:23 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"56f7efc2-5591-474b-8415-e86aa2fa4cdf","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"df414da4-4c0f-4794-b996-6e8f011bdc2f","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:37:23 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:37:23 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"40f9b900-f84c-49ad-aed1-ac8c33670bee","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"606500dd-111a-476b-8a3d-0d8ba7b769df"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"4cf7d4d4-2441-4f0a-8b08-0cda678e2477"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"02c57918-04e8-463d-858d-198e3e1b79c9"}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"ebf98727-6f23-485f-8523-8b78e0661922"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"3bd82254-bd71-4b0d-b9af-7ded7e4a9d87"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"effe99b3-ad16-4c3c-b095-68f2d7b3f516"}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"bbee5253-238b-43ba-8892-85235f606587","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"10dd956f-a841-4265-99aa-7793d4b409d7","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"7fb67e23-274a-4439-b5fd-48460f304f41","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"215cdb5d-3ff7-4e05-a30a-0a835e885789"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"abe1f5fa-e946-462d-8e30-a72e20092c50"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"64c1364c-b229-4ab4-863a-23054018b9f0"}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"f99b8d37-3be7-40b0-8868-284fdac994cd"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"17027d1a-066a-4410-a968-2dd981466c77"}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"d7deba71-92cb-4dad-8728-e3f84f27c617"}''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:24 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"9c585f01-4d4f-41b3-871c-6d066b852e09","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"05e3d872-1d3f-45d0-b685-14b2db506351","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:24 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:24 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"ba8ba476-a277-44fe-9954-626d8f715b15","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"24fe83e3-3a8b-4362-ba72-72db302bf67e"}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"ca8648e8-e1be-4efe-990f-3b3a70875ebc"}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"2d7f58c4-c104-4c09-a789-1d9233fded4c"}''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"4a629614-a891-4191-b5cc-ee87b2728846"}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"3690bd06-0c2d-4a7e-9a8b-c4704df22538"}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"5f04d62a-7c72-492c-bd58-7a3b275da2da"}''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-07 14:37:25 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"717ecd3b-7972-4ea0-b457-b14de4cd8414","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"780b9a88-11c3-4bd2-81a6-d1661c6b4338","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:25 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:25 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"a067ecfa-e110-49b8-a650-66b3bc2eea0a","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"1174bac4-8ab5-465e-b4b6-c914878b26fb"}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"2bfc3067-ef85-40dc-a861-8dacf31ced2e"}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"fa718d92-c492-4423-86b3-af1a0e810848"}''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"320a2e1c-794c-4438-baf4-d16f20ed7e9d"}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"f0078726-eb53-4095-b0cc-6c2d1e724997"}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"82f061d9-980d-4971-a3a8-b5167be0dc6d"}''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-07 14:37:26 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"c4d62816-8726-4ac2-8768-0b1b11a51859","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"d85a20e2-a107-4511-9dd1-7cbe5c94c24c","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:37:26 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:26 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"1f3481e6-ad12-4185-8b5b-532eeb439083","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"a83ad4da-9b8a-4714-a4a1-6b8985bf61b4"}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"fc7f7741-320e-408d-8aaa-0ad56baa57d5"}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"9ca9687f-2b22-41dc-bb28-20be73e54933"}''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"d149d353-0b02-47ce-ad73-78a953ef7c52"}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"9ee4cd74-8bad-4db0-8498-5ffdec259643"}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"17060e45-b45f-4dff-a21e-0c566c2fe2ac"}''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:27 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"19b860c5-fb87-4b5e-98c3-b3778a21726d","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"650f64be-3485-430c-9e9a-12674e949133","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:27 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:27 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"62cd292a-55be-44a4-81f3-6c47b923dd12","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022"},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9"},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3"}]}''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"82effea2-c158-435b-a337-96ec08c09341"}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"2c0a5d5e-68a1-4b48-8005-4398b3a82362"}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"aecbdc51-4a1a-4aab-8857-11573a3fce11"}''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"3f2ba077-53c0-4d73-8027-7484a2b0f493"}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"f747af25-339d-46b0-9791-fa0557fc1a09"}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"a2dd71fc-e8e7-41fb-9aa1-89c3c23e9847"}''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-07 14:37:29 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"0ba089b3-85f8-48f5-bb69-5ed35b08a6af","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022","data":[4,185,5,219,142,20,128,167,33,130,90,17,52,37,78,115,186,176,206,146,19,69,232,216,125,118,90,186,128,79,122,104,217,125,64,213,73,219,170,209,98,216,194,53,55,177,134,81,117,111,242,230,145,145,200,208,2,24,87,85,142,107,160,192,67]},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9","data":[4,150,94,139,186,22,31,153,195,108,160,68,229,204,211,250,187,162,247,36,209,4,33,74,158,92,18,16,137,246,12,122,61,132,194,57,82,143,119,89,210,148,199,165,117,59,179,81,199,89,175,32,25,142,140,87,0,235,99,40,68,187,4,157,109]},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3","data":[4,99,235,94,238,119,215,155,148,176,229,34,54,164,237,81,208,111,8,65,164,116,149,116,25,91,175,242,169,154,87,103,94,27,247,19,223,23,17,230,176,114,117,128,16,145,122,172,211,50,187,145,108,139,159,234,224,95,137,158,186,48,58,6,118]}]}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"10f58d67-ba40-4783-89c1-a31a8788bcb9","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022","data":[4,185,5,219,142,20,128,167,33,130,90,17,52,37,78,115,186,176,206,146,19,69,232,216,125,118,90,186,128,79,122,104,217,125,64,213,73,219,170,209,98,216,194,53,55,177,134,81,117,111,242,230,145,145,200,208,2,24,87,85,142,107,160,192,67]},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9","data":[4,150,94,139,186,22,31,153,195,108,160,68,229,204,211,250,187,162,247,36,209,4,33,74,158,92,18,16,137,246,12,122,61,132,194,57,82,143,119,89,210,148,199,165,117,59,179,81,199,89,175,32,25,142,140,87,0,235,99,40,68,187,4,157,109]},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3","data":[4,99,235,94,238,119,215,155,148,176,229,34,54,164,237,81,208,111,8,65,164,116,149,116,25,91,175,242,169,154,87,103,94,27,247,19,223,23,17,230,176,114,117,128,16,145,122,172,211,50,187,145,108,139,159,234,224,95,137,158,186,48,58,6,118]}]}''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:37:29 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:37:29 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"132e1e1f-9896-4925-9d16-7cd8f3d153ed","content":[{"uuid":"7f4cd8e4-1243-4faa-bbad-c99b5ad6e022","data":[4,185,5,219,142,20,128,167,33,130,90,17,52,37,78,115,186,176,206,146,19,69,232,216,125,118,90,186,128,79,122,104,217,125,64,213,73,219,170,209,98,216,194,53,55,177,134,81,117,111,242,230,145,145,200,208,2,24,87,85,142,107,160,192,67]},{"uuid":"8b997ee1-66ab-42aa-a985-f7ffb1a293f9","data":[4,150,94,139,186,22,31,153,195,108,160,68,229,204,211,250,187,162,247,36,209,4,33,74,158,92,18,16,137,246,12,122,61,132,194,57,82,143,119,89,210,148,199,165,117,59,179,81,199,89,175,32,25,142,140,87,0,235,99,40,68,187,4,157,109]},{"uuid":"b3fae7b0-771c-421d-8236-8112b55e1ba3","data":[4,99,235,94,238,119,215,155,148,176,229,34,54,164,237,81,208,111,8,65,164,116,149,116,25,91,175,242,169,154,87,103,94,27,247,19,223,23,17,230,176,114,117,128,16,145,122,172,211,50,187,145,108,139,159,234,224,95,137,158,186,48,58,6,118]}]}''

2016-10-07 14:40:29 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:29 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:29 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:40:29 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:29 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:40:29 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:29 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:40:29 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:29 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:177:5
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:142:10)
    at TestDevice.error (/home/pi/Test/server_879664325d33342/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_879664325d33342/test/TestServer/UnitTestFramework.js:89:23''

2016-10-07 14:40:30 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:30 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:30 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:30 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:30 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:30 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:31 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:31 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:31 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:31 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:31 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:31 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:32 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:32 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:32 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:32 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:32 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:32 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:33 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:33 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:33 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:33 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:33 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:33 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:34 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:34 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:34 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:34 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:34 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:34 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:35 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"8c9495e3-d5eb-4ed2-9c95-63b8e9072625","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:35 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:35 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"9ea9ad2a-3703-4f07-9c34-b13658160fcd","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:35 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:40:35 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"b947dac5-a61a-493b-a23e-a34d11635cf7","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:40:35 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_879664325d33342/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_879664325d33342/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_879664325d33342/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_879664325d33342/test/TestServer/Socket.js:173:22)
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

Device test finished on ce061606e320561102 
Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/879664325d33342_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/879664325d33342_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/879664325d33342_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)




