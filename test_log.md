#### Test 879664323f02699 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-05 12:10:41 - INFO Server: 'listening on *:3000'

2016-10-05 12:11:29 - DEBUG Server: 'client connected'

2016-10-05 12:11:29 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:11:29 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '6eb3bf76-76be-45ec-b637-46cd5317ba7d', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-05 12:11:29 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-05 12:11:31 - DEBUG Server: 'client connected'

2016-10-05 12:11:31 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:11:31 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '4c2516a4-1983-4fee-af18-f2224d6a51e5', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-05 12:11:31 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-05 12:11:40 - DEBUG Server: 'client connected'

2016-10-05 12:11:40 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-05 12:11:40 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '9dd87dbc-76ea-45d8-a5f7-9589f58e449f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-05 12:11:40 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-05 12:11:40 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-05 12:11:40 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-05 12:11:40 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-05 12:11:40 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-05 12:11:40 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"33b69aa0-d9ea-4146-bff6-2fddb7ba2c73","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-05 12:11:40 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-05 12:11:40 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"6b8873a6-d3a4-4dc6-b2f7-ddfe792a60fe","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-05 12:11:40 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-05 12:11:40 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"6202b1c6-0fee-4981-98b8-5d7d5b32c5ce","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-05 12:11:41 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-05 12:11:41 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:41 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"302f072c-3103-4892-ae66-2e461802e96d"}''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:41 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"0ea6b3df-f553-4d48-b9d4-5e9ca4c08ffe"}''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:41 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:41 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"cc0b93fc-48b1-4534-b895-d1d7919dad0e"}''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"302f072c-3103-4892-ae66-2e461802e96d"}''

2016-10-05 12:11:42 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-05 12:11:42 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"38e9197a-f076-443e-8d20-40985d099d47","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"247b22ac-4d2d-44a3-aee0-917645cbfda8","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"d2bc7dfa-871a-4859-ae83-d9c4f5b2c22b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:42 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-05 12:11:42 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"48cffbc2-91cb-406a-9128-046d7f55dfb4"}''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"0154bee6-bc24-4c5c-9b9c-d976a14ef6df"}''
2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''
2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''
2016-10-05 12:11:42 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-05 12:11:42 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"b0a53947-508d-4820-ba5c-160de4da9dfd"}''

2016-10-05 12:11:43 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-05 12:11:43 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-05 12:11:43 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"c5d788b2-a96f-493c-b958-ba9d9cdba706"}''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-05 12:11:43 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"171080a3-7f48-4876-8ec5-71b27c7a355f"}''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-05 12:11:43 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-05 12:11:43 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"8015e8f3-9327-460d-b6c8-55017d4ed774"}''

2016-10-05 12:11:44 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-05 12:11:44 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"682196c0-c4ad-41cb-b0b8-0c1aa97d44ad","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"40d7a799-3e94-4f87-b7ab-18df2eae9582","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"0e50eeee-c8b0-48a1-a74a-83d5e921e876","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:44 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-05 12:11:44 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"edce62b8-dacd-412c-bf85-b0df894d0529"}''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"a2d2216b-6714-4eeb-afdf-32c61b25fdbf"}''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-05 12:11:44 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-05 12:11:44 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"f81d10b4-cc68-4ed2-b9fa-50eb99c44d5f"}''

2016-10-05 12:11:45 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-05 12:11:45 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:45 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"6d6a9bc4-55ea-4f89-b94e-eb25fb0830bb"}''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:45 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"50dd0652-b325-48cb-9c09-6507b58e82ee"}''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:45 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:45 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"f34f2690-e953-44f6-a487-c7b43c2d63ab"}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"d44fd36e-73b9-4dee-88ca-9e1df872f3c3","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''
2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"092f98b9-1406-4c70-bf72-3fd7763905b6","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"d52915da-5379-42d4-8f03-454386c8e28e","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''
2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"a983bf5d-5f21-4d06-addb-be849df9f9dd"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"54c27c09-8a97-4522-82f0-987647516e56"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"2f69e10d-5e08-4454-b897-7369fbb2beb3"}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''
2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"9bc6aa55-d89b-48b3-b629-61b9109ee4d3"}''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"8f869c0b-fa90-4939-9803-b25288189412"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"1c2830a8-671a-499e-a518-4f400bcd3d41"}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"9b063bb9-f9f2-4b09-8f62-414d5e913a97","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"d4d7699d-0ac1-48c3-af04-929f7be9b92f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"20d237cf-9259-44c7-9246-9da79f049f20","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"0da9eff2-a227-4d31-9a62-9416bb681445"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"eaa53a33-41db-471b-8b00-8f14bb101d8f"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"7a89e63a-342e-4f62-9aa3-8464e72e482a"}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"5f37109e-36ce-4244-8e6f-57002d32bc02"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"34f30b60-c619-41ed-9f6e-045e0c0d502d"}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"afa5cd02-ecbf-4f27-bc3b-948899cbda18"}''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:46 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''
2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"80979a2a-5fbc-4dd2-a8a9-0165dc061a40","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"7da7e0b7-e86c-4e29-bda4-27c1edb9b4cb","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:46 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:46 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"03c0d7b3-7d25-4663-977f-b0abb2303331","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"5c2b140c-0e5d-4640-b6f9-c62268ff2ce7"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"1708cc77-c43e-49c1-8e5e-bd1316972861"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"03ebde5b-26f6-4f31-8309-6314db0914c1"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"62bcc33d-f32d-4830-a52e-66869a7eba13"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"14e90967-bd88-4784-ad5e-ac48e63eea47"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"3fccc0cb-1b94-4d29-ba04-a0f8ab6b0bb8"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"b5d9be02-eaa9-4e8d-93cd-ec45d8f2c9fb","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"ddfad6e9-cb7a-418b-8b59-3c9d5228a787","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"5c2de9c1-27ed-4dcf-844f-8780162db59a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"316071e8-29e3-4a77-a066-a44399f64dc4"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"0e3e1ca5-57e3-4d2f-8523-04a23738f594"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"599e193a-5f71-420f-8d3a-5ed80ae695d7"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"d23aa176-501d-43c5-a4ea-801b325168cc"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"fa79c781-5dfe-4565-94da-4483b325aced"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"2bf873f3-f1fb-4dce-9f63-3e77863f94aa"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"041da861-623b-46d7-bb4b-eb0bfa60e0e9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"978064c9-3656-4fe5-b6cd-df7cc3b1201a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''
2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''
2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''
2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''
2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"19471492-829f-44d5-951d-95326c9dca95","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"c2b761a3-84bc-427a-92f8-417647b7dbf7"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"c0b0be99-d674-44a9-a323-3afae0b38a5f"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"7b417fad-6626-4f53-abbc-bb2250f1866e"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"689af104-4016-4baa-84fb-705165d4b36c"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"f6c4e9a0-793b-414e-8438-fa11ebda14b5"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"ade0cf78-d19e-40ca-80dd-5e13c1943de3"}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"a438540f-1422-45d4-82a4-d4c6fadf0759","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"91aef308-d653-48f7-bf94-7a1256c958dc","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"2a75fd59-f0d2-40e6-a777-9952d5f1208f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:47 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"31483f92-de4e-4729-baf5-7bc7e633e1b2"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"d710a821-a0d5-4ca6-a7c2-e9c03034a389"}''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-05 12:11:47 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-05 12:11:47 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"2ba8ad7e-caaf-47ee-8725-ac7d60cb7a27"}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"32415996-9c17-4ff5-afd2-ca75c190b4e8"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"5a8fc7b1-e3d2-42ba-94ea-136cedc0637c"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"5c3479b5-8674-4aa6-91bf-ae7552bea791"}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"882b0ef1-e9cd-4654-8c36-78aaa56ea7d9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"d49e8fd6-52c1-45e7-9286-36dc830c7c85","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"fc0af605-bdd8-4083-821d-cb462c5b253b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"28b9930c-b68b-4969-8d69-01b3b7f2305c"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"2a258608-741e-41a0-96dd-f422390a8226"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"089dbb85-dd1d-4c7b-8f55-f91bee35ffad"}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"d156d1a2-6f54-4857-a613-927a05631a6c"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"e3276202-0801-4c69-984a-aa0440003c09"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"06ea3ee8-0f4d-4b35-923f-41b824571dc9"}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"5223e9e0-7097-4699-96b6-945651df6f01","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"c523f5ce-7864-4edf-bf51-8b52717e0b16","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"189c967e-8de7-4b67-b847-19f56f8f99e0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"f83c832b-45ce-4fc0-8523-9eea350d0fca"}''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"ce5cc33e-5f14-4191-b2fc-c2777b1a2449"}''
2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"7e39d1fe-db91-49a6-b1a7-514c6c385bb0"}''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-05 12:11:48 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"84d6fcd8-22ec-4c25-8a0a-89698b1642ff"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"47c82974-1b29-46b0-9a7c-1c7bee0536fc"}''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:48 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:48 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"1f96853e-1846-4abc-8d4b-add43fdde3bb"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"185543c0-85fa-4145-81d6-b8a4e79cad70","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"f66e07d2-da39-4116-821f-31ed20e5c8e9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"53e7d1c3-cf09-42e3-a793-603eff29411d","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"e8b6581a-f5ab-4b84-917a-ebcc89c2b497"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''
2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"51d14d33-a24f-413d-add5-322ebea4f854"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"7df373bb-c236-4a25-9f66-014314743d3b"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"9ffffb2c-8514-425a-81df-d7501d7b3589"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"6c2e37ea-7661-43ab-a412-89f865c169f8"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"b21fa5e1-6fb6-4381-b06e-3b66821dd9d8"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"526b0415-24f6-426b-bce2-bef9e5512ddb","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"0a982fbb-3e39-4c2a-8a4f-83cbd371be37","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"d204c546-dcdb-4670-ad43-bf134b239342","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"4f4b4558-376c-47d6-b472-5ae88c2c17ef"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"e2b63d84-defa-44e0-ba1c-7f112418e631"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"42124e9b-cd34-4aaa-bb07-ddbb717410c4"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"1eb25d10-cb79-4afd-924f-588bdc53551d"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"0a18ded2-16ea-40ed-9d30-819b8e5a1394"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"a3902649-331e-4180-8927-ad50ced69f0d"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"7dd97db3-e239-4f0b-8f8d-b3b180677b1b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"c65e9016-a480-4c32-809e-03807d1d850a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"0b084260-dc06-4161-8113-a22b8a8ab385","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"15b9a9b1-31bb-42eb-877d-7c81574012a4"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"f9552122-1dab-4e5b-87b5-cf7e7260f4f2"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"e03d888b-ff8d-4624-be9a-460f5380e550"}''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-05 12:11:49 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"67a59880-47c7-4861-85a7-ef60ee487a52"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"2d5e5d48-785c-4964-bf25-1fbb3be70c02"}''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:49 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:49 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"fe31e25f-9a3d-4121-b89c-57e0b7fa785f"}''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"9ab689ea-a531-4255-b8e9-74774bed8f85","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"4fabfcd6-89c0-431e-9e05-7a193f6a247b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"ab829a27-3cb8-4cef-a4ae-a382fb16e71f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"5e4d9405-0fcb-456b-a927-88bbf703e267"}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"b2c9fa44-aa06-4d65-a3d5-d52cb303b28f"}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"b2c7ce62-e5ea-4605-bc4d-f57a3b8b0b8d"}''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"882b41c2-a032-4e53-ad4b-393bf211bd27"}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"fabe720e-4a14-4f55-97db-a60a2520454c"}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"3a74a73b-8511-48cb-bb21-a465ecd57fd4"}''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:50 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"b0de6003-0249-4698-b452-c7606c87e418","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"26abe845-1391-4817-9327-3c5173760cb9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:50 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:50 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"a5465d84-add2-47a7-9223-df9a546d8058","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:52 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:52 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"30fb63c1-adc4-4913-93ba-debcfdcfde87"}''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"54d0fb07-7c99-4c13-8f1a-5b8c8c27ed8f"}''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"cdd83932-88d6-4626-92ff-dce185234acd"}''

2016-10-05 12:11:52 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-05 12:11:52 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"a066c2cd-d0b5-47d4-bba1-2ed388ada2e2"}''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"f196f30b-4810-4352-b64d-2fb7c5e003c8"}''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:52 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:52 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"c5e64eb0-4626-4f32-9ce3-c30a806d6833"}''

2016-10-05 12:11:53 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:53 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:53 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"9a2a98c7-7d41-432b-a6bf-f34f69ea01e8","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:53 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"b330be2a-4ab9-4e72-8d4b-31da0621bfce","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:53 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:53 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"f95eb8ad-ff7a-41fd-a4d9-01f40fc5a1e0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:54 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:54 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"456ea0e9-8b44-418e-a765-8712a171dcdd"}''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"37771a2c-5dd2-4608-9c14-0882f5201fb1"}''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"3197021c-f7dd-4d13-bc4a-dddc8180883d"}''

2016-10-05 12:11:54 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-05 12:11:54 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''
2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"c4bc360f-d5a4-4bb3-974b-0239927b3413"}''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"dc77f148-6216-4513-9b2f-4c110a7e08d7"}''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:54 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:54 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"9576d70c-61fb-4881-9974-b7af21d4441f"}''

2016-10-05 12:11:55 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:55 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:55 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"d35f03b1-e0ea-4f1a-8f02-e79ad63cbb9b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:55 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"d6cb042c-129b-42d6-8b92-81e33022a64f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:55 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:55 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"6fb2f2bc-95e0-4f58-bae9-cf9e7a0074ab","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:56 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:56 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:56 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"65f8f358-42d8-49bc-a4fd-671b491195a8"}''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:56 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"29beee9a-5a23-41b3-a8c1-383e47fd130e"}''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-05 12:11:56 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-05 12:11:56 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"91215620-41f0-44a3-8156-4e11901fb298"}''

2016-10-05 12:11:57 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-05 12:11:57 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"6becbc43-bc89-4327-9232-551925a20427"}''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"cff9be8f-6fec-444e-af57-d1e7cc870484"}''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"17ca8789-bf1f-4dbb-8ed1-22e335816468"}''

2016-10-05 12:11:57 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:57 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"4a6a4475-7f45-42f6-bea7-af48f613fd40","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"f45a3ffb-d350-4b75-bd2e-0fd42653438c","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:57 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:57 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"4b873e96-3bf8-4d3c-b00b-a030bbdf8e0d","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:58 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:58 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:58 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"857418fe-c27d-4379-9f28-9d8f6a036e58"}''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:58 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"33a681fc-4712-4821-b2fd-d81d24d59ca6"}''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-05 12:11:58 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-05 12:11:58 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"2033a9da-a516-4016-98e6-665244ceeacc"}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"badc8244-2a6a-42eb-b907-16e5db1c27d2"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"aa3224d2-1b9e-444b-82ac-3dad97ec26fd"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"bb0b7210-1fb7-4d1a-a75c-086b8737c9ef"}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"467158db-6937-4785-b02e-fa0431a23989","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"7336665b-17c7-4ce5-a340-497e9b2c4422","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"753d133a-e982-49df-8ac0-aaf2d0776298","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"f5bcdc98-9e46-4c44-9f67-70301a55a2ec"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"4cb652a2-849a-47e4-bcd4-280f0f6c49b5"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"6c27725d-8989-49dc-9777-e7e850bf82fe"}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"f2a643ac-7319-45d2-a536-8a0de703fff0"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"f8c88969-dcab-4076-a2ea-280f5336fd43"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"6e56e0a2-9788-4c70-8957-9e732eac1cd2"}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"a9f77ace-3e50-4d36-bdb2-b1577e87b0b8","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"e949b7a5-8bef-4b71-a8a6-f1e0acba5e07","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"ad16d0dc-6ecc-4320-adaa-f13879006c16","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"a090da8d-2add-4670-b4bf-90d980ebd1f8"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"2897a391-da85-4c84-893c-9d42722a09c9"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"bf162491-ff9e-46f3-ab85-2273cb20ccc0"}''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-05 12:11:59 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"92cef411-278b-45d5-a8e2-decc0192c7ca"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"3cde5d99-1315-4c40-b673-661b893b0764"}''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-05 12:11:59 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-05 12:11:59 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"fef861f2-b0ae-4559-96ff-bf340ca500f0"}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"e65376cf-2559-4c6c-a3b1-e91e9bb3b585","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"bcbd85ca-875c-4896-a6eb-4e507e395904","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"22c93300-beea-4c29-8fff-2b8fdb07b72a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"7f0d5e88-4ceb-4bf6-ad27-6ba67b4b1081"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"d19d7696-2d36-41fe-827d-175f55d2c170"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"2c3a072f-0a49-4a7b-981b-5da22fc4a909"}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"535003f6-23b5-47a0-b35b-4e5422b37499"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"add4defa-3754-44b5-bb07-4ae17a91ee54"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"8187000b-7d43-466e-a31c-eced46c1ccdf"}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"91047c77-6a70-447e-ada4-8145636bef0e","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"5ea3a4a1-4aed-4f81-a632-49920cab99f0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"29c841e0-0ded-4b93-b796-4c6a57d30316","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"8555ad9b-edf1-4014-940f-ce1175aad7ad"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"8aa7f4d9-01a3-454b-b918-77eba48d6c40"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"a35aaebf-e573-4e00-b5c9-53d1ff7cc4eb"}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"18930438-e67f-458d-b1ca-09be90b1b739"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"feb6fd11-b23f-4527-863f-23968d9e3fba"}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"1e544b7a-a07f-48d6-a2dc-7909d5828b02"}''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-05 12:12:00 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"bec700a8-3fc9-4eb7-8ab9-3fb364385ac6","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"616a1a27-4ab6-4bf6-a1b4-be4a6ed0cca0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:00 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:00 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"d2ba82ad-311e-4b53-8270-c988f949ef35","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"1c459dc8-00ab-4147-8c02-86c40f223f5b"}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"5aea160e-0335-4727-9637-22be57aabb3a"}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"4928ec86-e818-44c7-b334-ab22f70108c9"}''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"9fe7fdcd-4bbb-47bc-a0c5-95271d3e1cbf"}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"0d81428c-3f77-45e1-aab0-65add754c9c0"}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"1087ff12-a8cb-45b9-bb02-2df03d82a871"}''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:01 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"e016bc52-1c1b-4f2c-b2c5-303eb41669de","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"165e9c19-75d7-483f-af8e-d1c95ed96454","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:01 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:01 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"8cecb406-9c16-4b2f-a503-740b3bde38a7","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"23f3aeee-9d51-4bb8-912c-34f4d855d5b2"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"321ce815-8f23-4550-80ca-38cd9cb111d5"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"6d06ffb2-e37c-4dfe-80c6-15412ca537a2"}''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"753d7f8c-54d2-4377-ba96-a13344944568"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"e1859ed9-ebd3-4dbe-8895-5c2467f4f3a3"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"07142d6b-c4a9-43d9-8dea-2dcb9776d0a0"}''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"4e7a1f9f-2cd1-42c2-b2bf-d70bdf8f7f4e","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"03b11813-c2fd-43da-86c3-2fda246aa36a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"a1f08f0b-80e9-423d-bd86-0d0649a0d8a9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"83365dac-84da-4472-889b-21e6263a7e10"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"47e251fc-e380-446c-9995-e0958d98f370"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"babc4e71-62f6-4826-ab19-67f97b776b2a"}''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-05 12:12:02 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"e1693fc3-a43f-4996-bc03-5183b5220d95"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"c1deffb3-2df0-428b-a1f4-1b31f2270d79"}''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-05 12:12:02 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:02 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"649be250-73eb-4ecd-a465-2f507f6a4417"}''

2016-10-05 12:12:03 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-05 12:12:03 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:03 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"a0886200-10bb-4314-8886-8237a005b002","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:03 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"35fa89db-3b84-42e4-9d38-8e452784d8f3","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-05 12:12:03 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:03 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"e0a4c280-9de5-409e-9d86-692882bb1883","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"4f5ec058-e0dc-40b0-a6d6-9f9c4cfd5e2c"}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"86e1c1e8-4ae8-41be-bf46-2affe4b34bc6"}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"81547c58-badc-4dca-abb8-7682948b16ab"}''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"769607d3-8ff4-4a74-b15f-d793055d41de"}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"34a6dce3-0b5d-4903-be52-01185a4a7af3"}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"b37acac3-9b17-4e14-9680-f60c44c3042f"}''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:04 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"dc90a59b-a066-4e60-972f-7526b54ed0d9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"68976930-c7ab-44c3-bb8d-e3a82aeba416","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:04 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:04 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"6d02d0a3-1303-4710-8dc5-b86192a5962f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:05 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:05 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"89c7a072-ae73-4c60-91d5-cd62fe77a38e"}''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"01d8e175-e351-4fc9-8eca-80c8abd76ae8"}''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-05 12:12:05 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-05 12:12:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"29882e2d-44bf-41ea-9df2-6575927bf413"}''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"a261a287-4dbe-469e-b0f5-b2288ab65a78"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"c64742f8-7481-433e-a9db-6e3e33013138"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"2fe0fff7-667f-49cf-8404-0ad2d04d97c3"}''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"7c5dc806-bc11-4d2d-99be-0400035f2f76","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,124,157,81,161,62,175,102,97,138,238,10,60,104,163,224,151,39,135,226,227,124,18,113,92,125,10,115,132,242,22,149,233,33,100,227,10,85,159,159,104,1,147,218,231,141,232,191,217,209,48,227,143,207,245,95,227,64,67,179,218,239,131,86,114]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,93,241,191,155,239,34,66,251,20,67,46,23,147,163,73,80,74,121,17,108,153,11,134,21,81,208,230,132,155,166,67,176,83,144,19,166,129,19,183,233,187,166,242,238,117,246,171,54,220,169,30,178,49,240,46,207,102,158,72,87,12,150,66,147]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,16,205,150,206,166,86,107,230,250,63,36,166,88,249,185,120,9,8,133,122,135,237,97,61,107,250,23,157,185,245,97,226,70,114,93,8,54,208,140,18,213,198,169,134,181,65,63,63,199,133,97,251,98,55,224,51,109,70,154,52,10,153,114,98]}]}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"1e0d31e6-919a-4a9a-95d7-56a13d6dceec","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,124,157,81,161,62,175,102,97,138,238,10,60,104,163,224,151,39,135,226,227,124,18,113,92,125,10,115,132,242,22,149,233,33,100,227,10,85,159,159,104,1,147,218,231,141,232,191,217,209,48,227,143,207,245,95,227,64,67,179,218,239,131,86,114]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,93,241,191,155,239,34,66,251,20,67,46,23,147,163,73,80,74,121,17,108,153,11,134,21,81,208,230,132,155,166,67,176,83,144,19,166,129,19,183,233,187,166,242,238,117,246,171,54,220,169,30,178,49,240,46,207,102,158,72,87,12,150,66,147]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,16,205,150,206,166,86,107,230,250,63,36,166,88,249,185,120,9,8,133,122,135,237,97,61,107,250,23,157,185,245,97,226,70,114,93,8,54,208,140,18,213,198,169,134,181,65,63,63,199,133,97,251,98,55,224,51,109,70,154,52,10,153,114,98]}]}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"b8635cc3-9998-42f0-8fce-1512363ae1a9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,124,157,81,161,62,175,102,97,138,238,10,60,104,163,224,151,39,135,226,227,124,18,113,92,125,10,115,132,242,22,149,233,33,100,227,10,85,159,159,104,1,147,218,231,141,232,191,217,209,48,227,143,207,245,95,227,64,67,179,218,239,131,86,114]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,93,241,191,155,239,34,66,251,20,67,46,23,147,163,73,80,74,121,17,108,153,11,134,21,81,208,230,132,155,166,67,176,83,144,19,166,129,19,183,233,187,166,242,238,117,246,171,54,220,169,30,178,49,240,46,207,102,158,72,87,12,150,66,147]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,16,205,150,206,166,86,107,230,250,63,36,166,88,249,185,120,9,8,133,122,135,237,97,61,107,250,23,157,185,245,97,226,70,114,93,8,54,208,140,18,213,198,169,134,181,65,63,63,199,133,97,251,98,55,224,51,109,70,154,52,10,153,114,98]}]}''

2016-10-05 12:12:06 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-10-05 12:12:06 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-10-05 12:12:06 - INFO Socket: 'run skipped, test: 'Coordinated seq test', event: 'run_Coordinated seq test''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#run ok: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#teardown: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_Coordinated seq test', data: '{"uuid":"fe695a3d-2562-48a5-bca3-7f8902a0842c"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_Coordinated seq test', data: '{"uuid":"9c36d997-352d-4160-ae83-9559bc93d8a1"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'teardown_Coordinated seq test_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_Coordinated seq test', data: '{"uuid":"71f230a3-46b8-4b5f-bd27-5e74ca9a5d34"}''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#teardown ok: 'Coordinated seq test''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#setup: 'closeAll can close even when connections open''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll can close even when connections open', data: '{"uuid":"3305e2d9-6c08-4379-af72-b60942af7539"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll can close even when connections open', data: '{"uuid":"8a4713b2-b049-4655-b5ed-fcb01596d478"}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll can close even when connections open', data: '{"uuid":"cd28c76e-1e53-41c0-911a-41076f777014"}''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#setup ok: 'closeAll can close even when connections open''

2016-10-05 12:12:06 - DEBUG UnitTestFramework: '#run: 'closeAll can close even when connections open''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll can close even when connections open', data: '{"uuid":"bb6ce282-9a0b-48d2-a315-6cb134c0241e","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll can close even when connections open', data: '{"uuid":"29dc91e5-dd98-4a17-8a13-a8f5cdd8c9d5","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_finished''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_skipped''

2016-10-05 12:12:06 - DEBUG Socket: 'we are waiting for event: 'run_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:06 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll can close even when connections open', data: '{"uuid":"f01e60b0-3b94-4b27-8e03-db08d2b052ac","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:07 - DEBUG UnitTestFramework: '#run ok: 'closeAll can close even when connections open''

2016-10-05 12:12:07 - DEBUG UnitTestFramework: '#teardown: 'closeAll can close even when connections open''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_finished''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_skipped''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll can close even when connections open', data: '{"uuid":"ccdf65e2-cf67-4ab3-9e25-0dd5b285e7f9"}''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_finished''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_skipped''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll can close even when connections open', data: '{"uuid":"3083e2c4-8a69-4a0e-823b-9f2d5ce8601d"}''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_finished''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_skipped''

2016-10-05 12:12:07 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll can close even when connections open_confirmed''

2016-10-05 12:12:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll can close even when connections open', data: '{"uuid":"5e03b713-d4da-48f9-97e7-bb17b5496446"}''

2016-10-05 12:12:08 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll can close even when connections open''

2016-10-05 12:12:08 - DEBUG UnitTestFramework: '#setup: 'closeAll with promise''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_finished''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_skipped''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_confirmed''

2016-10-05 12:12:08 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll with promise', data: '{"uuid":"50634604-fa8a-4c9d-8db2-bef72ec4c6f0"}''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_finished''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_skipped''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_confirmed''

2016-10-05 12:12:08 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll with promise', data: '{"uuid":"5a42c7bc-4511-4be2-ae9b-77dac287377d"}''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_finished''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_skipped''

2016-10-05 12:12:08 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll with promise_confirmed''

2016-10-05 12:12:08 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll with promise', data: '{"uuid":"c1815f1a-de6d-4bf2-b138-3ee1ee749108"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll with promise', data: '{"uuid":"50634604-fa8a-4c9d-8db2-bef72ec4c6f0"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll with promise', data: '{"uuid":"5a42c7bc-4511-4be2-ae9b-77dac287377d"}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll with promise''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#run: 'closeAll with promise''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll with promise', data: '{"uuid":"33b23a9c-fddf-4c32-9fab-900050e72799","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll with promise', data: '{"uuid":"7e180024-15d5-43d0-b2a4-ba00b4491fa7","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll with promise', data: '{"uuid":"a6fda4e0-6a58-42bd-aba3-8002e7c3cc8b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll with promise''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll with promise''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll with promise', data: '{"uuid":"8afdd255-f665-417a-a2b5-0cfdf628132d"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll with promise', data: '{"uuid":"eec1d50b-bec6-488c-b65c-75bdfa82ce37"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll with promise_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll with promise', data: '{"uuid":"c5105026-f3c7-419c-a1df-a17194b86880"}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll with promise''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#setup: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"13e0e399-e3f5-477c-99c0-be4a77a59d3c"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"6c01d3cc-7d4e-4500-87f1-acaf248d8ee5"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"4277c571-5c70-4548-8778-cf0357b4488c"}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#run: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"5507434a-3186-4584-acd2-35fe66a13152","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"b7865800-b985-4ded-b2b3-879045aa0b3b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"c032b2f3-15df-4511-b59f-6781e5dbf497","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#run ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#teardown: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"25a0842d-f8f1-4b5e-8323-06bf5f43b00d"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"9f2a8437-16d3-4206-80bd-542f84c3aa31"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll properly throws when closing a non open server with eatNotRunning set to false', data: '{"uuid":"ca3e1401-9f55-473b-9b1c-b7c8674f283e"}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll properly throws when closing a non open server with eatNotRunning set to false''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#setup: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"6eed12ec-c88e-4327-a96b-a30b92231c8b"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"0057029a-97fb-4673-bf8b-c80b96eea303"}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'setup_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"50d0d6b4-d516-4778-b461-1d3f7c200176"}''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#setup ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:09 - DEBUG UnitTestFramework: '#run: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:09 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"196c9efb-27aa-4a54-97e9-dd2fcc024654","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:09 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"90be1c0d-23d3-494d-a447-a8e43557f99f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"348d9083-8651-4606-a2b0-12f10a11e29f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"b146e780-5ba2-4fec-8142-a6e35377474a"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"86a6fadd-cd6e-478b-87b0-6ea5ac5c640b"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_closeAll works even with a server that is not listening yet witheatNotRunning set to true', data: '{"uuid":"415de37c-8a91-4410-9d5a-019fcea9c7bc"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'closeAll works even with a server that is not listening yet witheatNotRunning set to true''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerLost calls jxcore', data: '{"uuid":"beb9899a-9d9c-4c01-957a-d4fec5511957"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerLost calls jxcore', data: '{"uuid":"6bdefd1a-d3b3-41df-a864-888086799d53"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerLost calls jxcore', data: '{"uuid":"92c639eb-52ed-4a2e-8608-d62a744cea7b"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerLost calls jxcore', data: '{"uuid":"9719f0a5-c3d5-4173-880b-e911c83f5392","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerLost calls jxcore', data: '{"uuid":"64c33401-8cb6-4cf1-b350-5c7622c50610","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerLost calls jxcore', data: '{"uuid":"418603db-211f-4c7c-9f94-e263b21fba47","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerLost calls jxcore', data: '{"uuid":"df2fb0d5-61fd-4c94-9528-78f878a73d4c"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerLost calls jxcore', data: '{"uuid":"4442e8ef-0bf1-4621-b028-e473b4d28938"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerLost calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerLost calls jxcore', data: '{"uuid":"b4d1efa4-02b6-4c28-bede-a9cdc91e61e4"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerLost calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerDiscovered calls jxcore', data: '{"uuid":"ff798a54-2ab5-468a-9f43-3e0b7414eec6"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerDiscovered calls jxcore', data: '{"uuid":"f4ab94f4-d8af-46d5-aff8-008582e329e9"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_onPeerDiscovered calls jxcore', data: '{"uuid":"67e91a6f-5325-450f-ba81-321d9511727e"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerDiscovered calls jxcore', data: '{"uuid":"71bbe3f8-f22f-4c66-b2af-e33ba239ac1b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerDiscovered calls jxcore', data: '{"uuid":"0d419739-5e25-4fe5-96c4-23754b686abd","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_onPeerDiscovered calls jxcore', data: '{"uuid":"e40d0125-266d-49fb-ba16-f4dc733e5652","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run ok: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerDiscovered calls jxcore', data: '{"uuid":"b7adc475-b068-492b-8fe9-c98eb681997e"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerDiscovered calls jxcore', data: '{"uuid":"89a4630f-261a-4fdc-977f-7aeef663e309"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'teardown_onPeerDiscovered calls jxcore_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'teardown_onPeerDiscovered calls jxcore', data: '{"uuid":"3012bb11-c342-49a8-8919-b73febb88414"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#teardown ok: 'onPeerDiscovered calls jxcore''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"171f7256-c421-4b07-848a-7e7665331209"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"c7e568c9-5c13-4e98-8ba1-837858ca3957"}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"c03ce6a2-51b4-40bf-bced-54c575ac6f66"}''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:10 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"37477632-aebe-4a9b-ac4a-199458fee9cc","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"133ab00c-9945-41b6-bd3d-0cd85fd3312c","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:10 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:10 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"1080b920-2bec-4c92-a5c4-45f41ec42965","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"0e528a2a-b527-4776-98c9-b2a385f2666d"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"75ee0561-cf7a-49a0-9cd7-77d745f674fa"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on a single db change', data: '{"uuid":"1364bd28-0aa7-422f-8273-c89a3b889413"}''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on a single db change''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#setup: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"d2222212-b2c5-41e8-8e1c-8499459d8eed"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"1245f9ad-2263-4503-abea-07567831f6e0"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"ffd8697c-61ff-455a-9656-7f8fae42e7ed"}''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#setup ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#run: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'run_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"34b8cf2c-4eac-42e4-9ae6-ad46ae3659cb","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'run_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"6fe63b25-8c46-420e-bcb6-f67e43863d02","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'run_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'run_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"4c81a177-5901-4698-b84a-79f533e98759","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#run ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#teardown: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"e5eb1a88-60a3-4b66-ac40-df18cba2fea6"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"7c2be7ba-ee13-4bd4-80a1-5e6b15f63e9b"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of multiple onCheckpointReached handlers on a single db change', data: '{"uuid":"69eedd5a-8bd5-4673-9139-7639ede98827"}''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#teardown ok: 'Call of multiple onCheckpointReached handlers on a single db change''

2016-10-05 12:12:11 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"888adf6c-f3b6-4a9f-a123-ef4838dd5e88"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:11 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"6883dcdc-e73c-497f-824c-a5c3ddf35b5c"}''

2016-10-05 12:12:11 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:12 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"e1c2bd8e-c3ea-47c1-8f0c-8ed73f12ed30"}''

2016-10-05 12:12:12 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:12 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:12 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"c8009bc8-e217-4f26-832e-63d7467078e8","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:12 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"6ac8df74-2cbf-4a4d-85f5-ffee3bad005f","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:12 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:12 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"3176c319-9d8a-41fd-836e-911e2b9c1206","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"e11d5287-6708-405c-ba31-8810b96d6f85"}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"0070d845-4b1a-41cb-ad2d-ce4743f32a61"}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval', data: '{"uuid":"c6058ea9-0470-4fc5-ab67-7129f6a59415"}''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#setup: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"46ee88ac-6e0b-4912-b611-0291c8e34f41"}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"3ba13a65-0a3d-4005-aa1f-cd81f6971206"}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'setup_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"8c05a04d-4ea2-4c0e-bf6e-a5910049b407"}''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#setup ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG UnitTestFramework: '#run: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"b23afee5-6f0c-4c21-ae6f-9df36545b9ea","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"adae8755-3a77-4f40-a98b-3da79992d7f6","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:13 - DEBUG Socket: 'we are waiting for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:13 - DEBUG Socket: 'we are emitting data for event: 'run_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"820e568e-0ad9-4ff3-b726-16574664c8f9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#run ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#teardown: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"83740e9b-5c3f-4541-bc93-fcdaeb2680a0"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"8ad6ef53-b3b6-4f49-bc14-f065acf41d46"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval', data: '{"uuid":"cf873d80-e862-40ba-a59b-1710f9e081e9"}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#teardown ok: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#setup: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultDirectory', data: '{"uuid":"6a8da3b6-6621-4453-a4ad-a2873531063b"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultDirectory', data: '{"uuid":"cdfac983-1243-4e5a-bfd7-498f32ef0c55"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultDirectory', data: '{"uuid":"fe4e63c3-0f03-494f-89f1-33212ca38625"}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#setup ok: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#run: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultDirectory', data: '{"uuid":"214304eb-eb55-48e1-bf3c-918501a16393","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultDirectory', data: '{"uuid":"f20a2033-a250-4540-aff6-598b28321a47","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultDirectory', data: '{"uuid":"5e3e7202-9f5d-4f6d-a762-ec93483f0c6a","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#run ok: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#teardown: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultDirectory', data: '{"uuid":"7aa8c42e-45d6-4132-b5f3-6da56dfc7989"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultDirectory', data: '{"uuid":"bc16f95c-14f4-4e8e-8c1f-785ffad32624"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultDirectory_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultDirectory', data: '{"uuid":"ab05b309-f6b5-435b-ba77-4e4bf7588d00"}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultDirectory''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#setup: 'test defaultAdapter''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultAdapter', data: '{"uuid":"f186c216-6a02-443e-9c9d-5dabaf923d91"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultAdapter', data: '{"uuid":"ea9974b2-50ce-46e0-828f-591aea8d1760"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'setup_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'setup_test defaultAdapter', data: '{"uuid":"5ee5bc00-01ea-4c76-9fa2-16f0d1802284"}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#setup ok: 'test defaultAdapter''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#run: 'test defaultAdapter''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultAdapter', data: '{"uuid":"dc9209e8-f5fe-48a3-90e4-f3a0198196cc","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultAdapter', data: '{"uuid":"6d5a8e9f-a9c6-498c-b45d-03dabe800509","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'run_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'run_test defaultAdapter', data: '{"uuid":"ac452019-6163-4309-a3b2-b75180acdff6","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#run ok: 'test defaultAdapter''

2016-10-05 12:12:14 - DEBUG UnitTestFramework: '#teardown: 'test defaultAdapter''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultAdapter', data: '{"uuid":"dd61e690-246c-40de-b63d-cee195ffc694"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultAdapter', data: '{"uuid":"3420ce7b-9fdf-45c9-b4da-235c0ff4e035"}''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_finished''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_skipped''

2016-10-05 12:12:14 - DEBUG Socket: 'we are waiting for event: 'teardown_test defaultAdapter_confirmed''

2016-10-05 12:12:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_test defaultAdapter', data: '{"uuid":"cef0f779-75b8-4183-adbc-44e449b6e7d1"}''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#teardown ok: 'test defaultAdapter''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#setup: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueue and run in order', data: '{"uuid":"5bab3fca-1c93-415e-9367-1c7a90b4b234"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueue and run in order', data: '{"uuid":"8e75ead6-3242-4cca-bb09-834e67a6b54f"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueue and run in order', data: '{"uuid":"36e4c201-dbf4-4fe5-b56f-30985db4836a"}''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#setup ok: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#run: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'run_enqueue and run in order', data: '{"uuid":"1a12736f-f732-4bf9-ac45-e8c63d958acd","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'run_enqueue and run in order', data: '{"uuid":"015bea68-f6b5-47fa-bae4-e59f773d1a21","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'run_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'run_enqueue and run in order', data: '{"uuid":"41d77ef8-7b3b-4361-a2dd-7944fd1c20f9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#run ok: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#teardown: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueue and run in order', data: '{"uuid":"698748f0-5ebd-42e9-a3e9-9dd29a9ef621"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueue and run in order', data: '{"uuid":"7415e2e9-f6de-46ad-8769-924862941209"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueue and run in order_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueue and run in order', data: '{"uuid":"b8d69b1d-131c-459f-86c1-42f71729f1af"}''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#teardown ok: 'enqueue and run in order''

2016-10-05 12:12:15 - DEBUG UnitTestFramework: '#setup: 'enqueueAtTop and run backwards''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"bda3544c-6f7b-4665-9ca6-a03581af096b"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"ca16304e-697c-4b21-93fe-2e62f0791ba2"}''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:15 - DEBUG Socket: 'we are waiting for event: 'setup_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:15 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"b0a406ee-f80b-4c67-9ef1-9b933c1771b9"}''

2016-10-05 12:12:16 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"bda3544c-6f7b-4665-9ca6-a03581af096b"}''

2016-10-05 12:12:16 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"ca16304e-697c-4b21-93fe-2e62f0791ba2"}''

2016-10-05 12:12:16 - DEBUG Socket: 'we are emitting data for event: 'setup_enqueueAtTop and run backwards', data: '{"uuid":"b0a406ee-f80b-4c67-9ef1-9b933c1771b9"}''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#setup ok: 'enqueueAtTop and run backwards''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#run: 'enqueueAtTop and run backwards''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_enqueueAtTop and run backwards', data: '{"uuid":"d1cedc41-87e8-476e-9cf0-2caacd23b812","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_enqueueAtTop and run backwards', data: '{"uuid":"2fda14f4-8f7b-4633-bbc8-5e964fc89b7c","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_enqueueAtTop and run backwards', data: '{"uuid":"5bb2bc3d-2375-423c-9019-de1012b1a49b","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#run ok: 'enqueueAtTop and run backwards''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#teardown: 'enqueueAtTop and run backwards''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueueAtTop and run backwards', data: '{"uuid":"8507a0e3-6c7a-4e20-93ee-7d5bf2c64c8e"}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueueAtTop and run backwards', data: '{"uuid":"4a836f41-37ef-41a1-8f63-913cf3edf28f"}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'teardown_enqueueAtTop and run backwards_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'teardown_enqueueAtTop and run backwards', data: '{"uuid":"3793d469-fda6-4038-a1c5-f40793410a10"}''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#teardown ok: 'enqueueAtTop and run backwards''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#setup: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'setup_mix enqueue and enqueueAtTop', data: '{"uuid":"142ff572-7c2b-4d36-b9f1-7d11a6f7dfd5"}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'setup_mix enqueue and enqueueAtTop', data: '{"uuid":"00ae9259-ae60-4e61-881b-454b2be98898"}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'setup_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'setup_mix enqueue and enqueueAtTop', data: '{"uuid":"3049c0de-d9d4-4c94-ae17-1d46111de8c1"}''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#setup ok: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:17 - DEBUG UnitTestFramework: '#run: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_mix enqueue and enqueueAtTop', data: '{"uuid":"e6b2ec27-e31a-4025-bcec-f56532ee6cd0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_mix enqueue and enqueueAtTop', data: '{"uuid":"b4ca2846-3b92-40f5-8c76-8ce665b6f2ba","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:17 - DEBUG Socket: 'we are waiting for event: 'run_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:17 - DEBUG Socket: 'we are emitting data for event: 'run_mix enqueue and enqueueAtTop', data: '{"uuid":"f1cb1324-39ad-4e4a-aee4-f74ad5688236","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_mix enqueue and enqueueAtTop', data: '{"uuid":"35cc7b22-78a3-453a-85fa-776d757a4454"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_mix enqueue and enqueueAtTop', data: '{"uuid":"2c73a01f-8336-4270-83cd-531c21013de6"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_mix enqueue and enqueueAtTop_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_mix enqueue and enqueueAtTop', data: '{"uuid":"a763b7c4-58b6-47cb-859f-96d4cc96b3c4"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'mix enqueue and enqueueAtTop''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_queues handled independently', data: '{"uuid":"e520583f-2a6e-4ba9-88fb-e1e4494a2356"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_queues handled independently', data: '{"uuid":"dbbc0550-8fc5-49d7-9292-c63d758e92ba"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_queues handled independently', data: '{"uuid":"8d597d40-80ad-4f22-a9b6-1ae784b3856e"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_queues handled independently', data: '{"uuid":"8e3d2fbb-9f9f-4c01-88d8-8e60c967e859","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_queues handled independently', data: '{"uuid":"0e078cce-5af5-4415-b5b3-a2e4dd3c8662","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_queues handled independently', data: '{"uuid":"6b30afb3-b3a5-42a5-ac7b-659b076e91a9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f"}]}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_queues handled independently', data: '{"uuid":"5125292f-821a-4527-bec9-e9781c7d60dd"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_queues handled independently', data: '{"uuid":"b7a922a3-ec70-48b1-b115-9bb9f9d7cb18"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_queues handled independently_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_queues handled independently', data: '{"uuid":"fd2eec95-98c9-4270-acb4-8669ab09ee03"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'queues handled independently''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup: 'basic''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_basic', data: '{"uuid":"da3603eb-c35d-43ba-9072-5fbe2865eeae"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_basic', data: '{"uuid":"cd8729ff-57ec-42b0-bff7-cd8c82bab242"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_basic', data: '{"uuid":"2cf0be34-968e-422c-a1e2-ab66bcb6f4f9"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'basic''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run: 'basic''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_basic', data: '{"uuid":"f98f79f6-c0a3-461c-8341-c5456675a063","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_basic', data: '{"uuid":"2d99373b-f0a3-4b02-aac8-99e11ee59bdc","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_basic', data: '{"uuid":"93fbaf6d-4921-4c78-a00f-e4dfa0133fe0","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'basic''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'basic''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_basic', data: '{"uuid":"adbb8edf-c944-4058-9e10-a81c12bb6fa2"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_basic', data: '{"uuid":"a889e155-e532-4dfb-bb62-b443a09c7d15"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_basic_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_basic', data: '{"uuid":"5ac82a0c-7bbf-4f78-a0a8-e091efeacf47"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'basic''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup: 'another''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_another', data: '{"uuid":"0535cbee-c789-468e-bd31-796141b914ff"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_another', data: '{"uuid":"4c920ade-dba7-4aa6-9166-92838740d6bf"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_another', data: '{"uuid":"31f6b471-da38-4e0f-92bc-646c7c879a9d"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'another''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run: 'another''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_another', data: '{"uuid":"ae57b9cb-ad16-468a-aac9-2abb2e5cdb92","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_another', data: '{"uuid":"f10030e9-a8c3-4a37-958f-a2d337302988","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_another', data: '{"uuid":"247f5615-71e1-40b5-83e2-5c6d7b33b6f4","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run ok: 'another''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown: 'another''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_another', data: '{"uuid":"464cfd4e-43e6-411f-b518-5796ae0b496b"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_another', data: '{"uuid":"5c12798a-ee70-41a0-8668-01dc466afa77"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'teardown_another_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_another', data: '{"uuid":"e898597c-28cc-4fdc-9c56-278b5c0965ac"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#teardown ok: 'another''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup: 'can pass data in setup''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_can pass data in setup', data: '{"uuid":"791406ba-735c-4346-8c5b-c70b18993b1c"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_can pass data in setup', data: '{"uuid":"f64886ae-e066-41e3-bb5e-333cebeaa36c"}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'setup_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'setup_can pass data in setup', data: '{"uuid":"bbf435d2-13b8-430a-97f6-820690daed9b"}''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#setup ok: 'can pass data in setup''

2016-10-05 12:12:18 - DEBUG UnitTestFramework: '#run: 'can pass data in setup''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_can pass data in setup', data: '{"uuid":"74bd02f0-6450-40e4-a796-0da066a75bec","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_can pass data in setup', data: '{"uuid":"78c47523-642d-4f7c-b428-92492142e676","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_finished''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_skipped''

2016-10-05 12:12:18 - DEBUG Socket: 'we are waiting for event: 'run_can pass data in setup_confirmed''

2016-10-05 12:12:18 - DEBUG Socket: 'we are emitting data for event: 'run_can pass data in setup', data: '{"uuid":"8eab4e5c-1149-4900-b643-b1f97a1795d9","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":"custom data"},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":"custom data"},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":"custom data"}]}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#run ok: 'can pass data in setup''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#teardown: 'can pass data in setup''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_can pass data in setup', data: '{"uuid":"ae9debe8-3ec6-4d3c-9125-986113f8e050"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_can pass data in setup', data: '{"uuid":"f96834b9-88bc-4942-b5f4-a94899496390"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_can pass data in setup_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_can pass data in setup', data: '{"uuid":"4b1c6458-6cf6-48e2-8335-777ef34f5e74"}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#teardown ok: 'can pass data in setup''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#setup: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager spies', data: '{"uuid":"ee309cb0-9b54-49f7-952e-cbfc5ae61aff"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager spies', data: '{"uuid":"28ed23e5-1eba-4ce6-8afb-03142d657102"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager spies', data: '{"uuid":"984624b8-9833-45cf-a312-3722adb93ff7"}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#run: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager spies', data: '{"uuid":"eef0ab99-5016-4fe5-a6fb-fa1a74ac8346","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager spies', data: '{"uuid":"3d2223eb-6eb3-47dc-a648-399b2fe2d172","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager spies', data: '{"uuid":"c1af412c-ff76-4091-b8fc-1d3d49f7529e","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#run ok: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#teardown: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager spies', data: '{"uuid":"b9973b49-ce01-4f95-92bf-e32d025d3905"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager spies', data: '{"uuid":"d48f38ae-b454-4c2b-bf12-f1351a6f7926"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager spies_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager spies', data: '{"uuid":"4b6231a5-76f9-4bcd-b4e6-8e29ea4cf295"}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager spies''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#setup: 'test thali manager multiple starts and stops''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager multiple starts and stops', data: '{"uuid":"ca45cd70-2e72-48de-9994-884333245f9b"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager multiple starts and stops', data: '{"uuid":"5be7241e-0a38-41fd-8262-be6643fcffaa"}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'setup_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'setup_test thali manager multiple starts and stops', data: '{"uuid":"d62bc961-5ec4-431d-9d01-469d601ae60d"}''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#setup ok: 'test thali manager multiple starts and stops''

2016-10-05 12:12:19 - DEBUG UnitTestFramework: '#run: 'test thali manager multiple starts and stops''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager multiple starts and stops', data: '{"uuid":"85ad1466-5dcd-44d6-843d-e293bdb1c483","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager multiple starts and stops', data: '{"uuid":"0db37811-f66f-4bec-9ff1-8aa1b34a3396","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:19 - DEBUG Socket: 'we are waiting for event: 'run_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:19 - DEBUG Socket: 'we are emitting data for event: 'run_test thali manager multiple starts and stops', data: '{"uuid":"01670b61-01a7-41be-8480-1b561a9e036c","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,62,194,213,42,208,201,107,18,27,12,236,123,91,242,23,209,97,212,219,234,59,199,41,131,200,58,66,100,219,46,206,143,57,82,234,189,234,27,211,159,127,247,134,188,142,112,210,237,240,63,118,131,134,144,144,30,55,2,74,70,146,85,170,5]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,36,41,68,192,178,160,6,180,154,30,211,122,201,12,55,78,197,207,206,52,94,46,186,85,154,215,63,138,55,195,112,67,209,231,55,200,151,138,64,29,114,115,45,135,0,118,138,198,107,103,14,192,40,196,52,118,208,37,39,235,177,128,57,93]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,247,30,211,57,131,171,193,200,80,68,4,97,163,60,163,240,119,46,214,246,69,208,153,190,29,131,78,161,130,217,97,237,33,100,168,51,11,236,72,224,77,164,62,92,24,174,102,113,115,12,116,83,192,67,50,166,207,94,185,58,68,248,214,247]}]}''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#run ok: 'test thali manager multiple starts and stops''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#teardown: 'test thali manager multiple starts and stops''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager multiple starts and stops', data: '{"uuid":"b20d2923-d8ff-481d-be2f-a4e0d0c520f9"}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager multiple starts and stops', data: '{"uuid":"36cf22b7-a552-4db7-b61f-8d3641f2e77f"}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'teardown_test thali manager multiple starts and stops_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_test thali manager multiple starts and stops', data: '{"uuid":"22aab776-03c0-4b09-87c8-5f2c2305e451"}''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#teardown ok: 'test thali manager multiple starts and stops''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#setup: 'test write''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'setup_test write', data: '{"uuid":"b6941a53-0bd8-41d4-b6ad-990f6f49ace9"}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'setup_test write', data: '{"uuid":"68b8ac0e-8311-496b-a734-c3630c0b4b2f"}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'setup_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'setup_test write', data: '{"uuid":"e115eecf-ca68-45ea-95df-9e4e87018ea2"}''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#setup ok: 'test write''

2016-10-05 12:12:20 - DEBUG UnitTestFramework: '#run: 'test write''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'run_test write', data: '{"uuid":"ca0f227c-f2f2-4442-93c8-ad8d934e7c98","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,209,157,55,2,212,80,149,226,88,203,190,121,32,116,97,121,132,110,53,180,102,206,177,222,93,48,24,65,246,46,218,69,151,208,155,19,247,178,71,206,17,76,182,147,10,116,145,26,231,124,214,147,41,105,76,53,101,164,175,174,68,16,158,123]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,238,116,111,73,234,100,128,115,120,180,6,100,78,15,242,224,174,204,166,170,49,91,50,116,20,25,25,7,98,125,71,150,79,187,74,107,17,38,66,92,81,229,255,196,223,88,182,173,201,78,195,171,114,151,182,35,143,215,226,94,175,109,34,195]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,94,144,214,195,144,58,173,16,77,210,55,173,224,87,83,133,124,207,56,56,150,208,34,2,47,228,87,252,149,160,234,32,51,81,42,61,137,75,74,253,232,76,64,45,109,103,133,29,225,78,178,21,201,162,144,153,166,13,247,204,197,148,145,196]}]}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'run_test write', data: '{"uuid":"5cc57d1b-4b5b-40f9-adb4-3cd6c23c0606","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,209,157,55,2,212,80,149,226,88,203,190,121,32,116,97,121,132,110,53,180,102,206,177,222,93,48,24,65,246,46,218,69,151,208,155,19,247,178,71,206,17,76,182,147,10,116,145,26,231,124,214,147,41,105,76,53,101,164,175,174,68,16,158,123]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,238,116,111,73,234,100,128,115,120,180,6,100,78,15,242,224,174,204,166,170,49,91,50,116,20,25,25,7,98,125,71,150,79,187,74,107,17,38,66,92,81,229,255,196,223,88,182,173,201,78,195,171,114,151,182,35,143,215,226,94,175,109,34,195]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,94,144,214,195,144,58,173,16,77,210,55,173,224,87,83,133,124,207,56,56,150,208,34,2,47,228,87,252,149,160,234,32,51,81,42,61,137,75,74,253,232,76,64,45,109,103,133,29,225,78,178,21,201,162,144,153,166,13,247,204,197,148,145,196]}]}''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_finished''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_skipped''

2016-10-05 12:12:20 - DEBUG Socket: 'we are waiting for event: 'run_test write_confirmed''

2016-10-05 12:12:20 - DEBUG Socket: 'we are emitting data for event: 'run_test write', data: '{"uuid":"1694d92d-9982-4945-bf1f-c084818b90e6","content":[{"uuid":"6eb3bf76-76be-45ec-b637-46cd5317ba7d","data":[4,209,157,55,2,212,80,149,226,88,203,190,121,32,116,97,121,132,110,53,180,102,206,177,222,93,48,24,65,246,46,218,69,151,208,155,19,247,178,71,206,17,76,182,147,10,116,145,26,231,124,214,147,41,105,76,53,101,164,175,174,68,16,158,123]},{"uuid":"4c2516a4-1983-4fee-af18-f2224d6a51e5","data":[4,238,116,111,73,234,100,128,115,120,180,6,100,78,15,242,224,174,204,166,170,49,91,50,116,20,25,25,7,98,125,71,150,79,187,74,107,17,38,66,92,81,229,255,196,223,88,182,173,201,78,195,171,114,151,182,35,143,215,226,94,175,109,34,195]},{"uuid":"9dd87dbc-76ea-45d8-a5f7-9589f58e449f","data":[4,94,144,214,195,144,58,173,16,77,210,55,173,224,87,83,133,124,207,56,56,150,208,34,2,47,228,87,252,149,160,234,32,51,81,42,61,137,75,74,253,232,76,64,45,109,103,133,29,225,78,178,21,201,162,144,153,166,13,247,204,197,148,145,196]}]}''

2016-10-05 12:15:20 - ERROR UnitTestFramework: '#run failed: 'test write', error: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'', stack: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'
    at afterTimeout (/home/pi/Test/server_879664323f02699/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_879664323f02699/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-05 12:15:20 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'', stack: 'TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'
    at afterTimeout (/home/pi/Test/server_879664323f02699/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_879664323f02699/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-05 12:15:20 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-05 12:15:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:20 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-05 12:15:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:20 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-05 12:15:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:23 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:23 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:23 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:24 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:24 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:24 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"59a75a28-73d5-4bf6-b35a-bf5f397fc684","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"a29c94dd-4e98-4d48-aaa9-f4811fac014f","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''

2016-10-05 12:15:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"eeb9863b-b26c-4180-a199-4a84d01f3689","content":"TimeoutError: timeout exceeded, event: 'run_test write_finished', test: 'test write'"}''


 
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/879664323f02699_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/879664323f02699_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/879664323f02699_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)




