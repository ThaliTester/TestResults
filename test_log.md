#### Test 87966432de46e75 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-07 15:08:20 - INFO Server: 'listening on *:3000'

2016-10-07 15:09:59 - DEBUG Server: 'client connected'

2016-10-07 15:09:59 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 15:09:59 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '089cb41b-08f9-4686-822a-733643bbfd21', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 15:09:59 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-07 15:10:00 - DEBUG Server: 'client connected'

2016-10-07 15:10:00 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 15:10:00 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 15:10:00 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-07 15:10:16 - DEBUG Server: 'client connected'

2016-10-07 15:10:16 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 15:10:16 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: 'c7e19229-2448-4b12-9f9f-3f4f682331d6', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 15:10:16 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-07 15:10:16 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-07 15:10:16 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-07 15:10:16 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-07 15:10:16 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 15:10:16 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"a6cce83a-f598-476a-acfc-1ed0b1c2efb0","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 15:10:16 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 15:10:16 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"9cd575ba-0132-4c02-97f4-5754fa0c3f3f","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 15:10:16 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 15:10:16 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"6142d71d-1fdf-4208-95a8-d2922e6b742a","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 15:10:17 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"a6cce83a-f598-476a-acfc-1ed0b1c2efb0","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 15:10:17 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-07 15:10:17 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:17 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"72df189d-1801-4409-877a-b22d9ceb3fb4"}''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:17 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"514e1e41-7592-4dd8-bbc9-577051f86dda"}''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:17 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:17 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"b7f669cc-35d5-4614-ba61-2c87290bdc20"}''

2016-10-07 15:10:18 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"72df189d-1801-4409-877a-b22d9ceb3fb4"}''

2016-10-07 15:10:19 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-07 15:10:19 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:19 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"8559c30a-1b90-45f7-a202-f32dcfb05e98","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:19 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"f83a12ab-28f3-491a-8a64-8fc41cde21b7","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:19 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:19 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"e681eec6-fea7-480d-a07f-28161fd9e74a","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:20 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-07 15:10:20 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"9558db71-a645-46b7-8750-f4065952ba8d"}''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"0f0c4efa-e26b-4e28-b12d-9aa35e22ada2"}''
2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''
2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''
2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"146f2bd7-ae0d-4c04-873b-59ee372a490b"}''

2016-10-07 15:10:20 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-07 15:10:20 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"6b3b90cd-026a-4a84-8055-d0569cb3d5d5"}''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"5d93316b-00ed-4569-80cb-1a19bf4275c3"}''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 15:10:20 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 15:10:20 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"4b0b0431-846e-4484-b759-2d1f314fbf7f"}''

2016-10-07 15:10:21 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-07 15:10:21 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 15:10:21 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"65822034-6306-4240-8307-5fbdca43cc04","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 15:10:21 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"2aae261a-f07b-4653-9e59-76cf54fc4ea8","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 15:10:21 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 15:10:21 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"432f439b-8e35-4747-8a02-3f6d7a13d84d","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:22 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-07 15:10:22 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"7d59d8a1-b81f-47a1-88ef-4e39c742384a"}''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"150c2b8e-6682-497c-a1b2-9fcaf269987a"}''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"a7383e12-ec71-40a5-bbf2-65ce4a3f1b95"}''

2016-10-07 15:10:22 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-07 15:10:22 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"56dd23e1-5088-4469-8ecd-2eb72a25618a"}''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"270cedd8-af09-41dd-b745-079208bac0dc"}''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 15:10:22 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:22 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"b6b0a73f-7b32-43b8-939c-ffb0e830e5f0"}''

2016-10-07 15:10:23 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-07 15:10:23 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:23 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"67f1e2cb-2c02-4a53-a097-bcb4af7a2434","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:23 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"664c61ee-08e5-4103-b8bc-3a17e3fb738b","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''
2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 15:10:23 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''
2016-10-07 15:10:23 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"9c683c2f-0c64-464b-9c2f-3d0dca634c53","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''
2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"66aa6c2e-ea44-44e7-995f-f648a3767a60"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"fb8278c0-8c6d-4830-884d-db58084d295f"}''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''
2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"0cf4cca3-3d90-4e2a-acf4-94fe5736a388"}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"38e8cff2-9717-4479-8bc9-65666cece5c2"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"c96b9631-06ea-4ef3-87ff-ababb34715ef"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"885b0a77-e50f-48e8-8e98-f76a1bf8c017"}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"8c9ca86a-55fe-4abe-8563-8618a0e87219","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"dc85176a-5a25-45ee-a774-d41c529d99ef","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"22c6628e-f5c5-4389-9eb5-1d7207fa8036","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"1670b9a4-de41-49ef-8190-e954d3b54ebc"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"35f2657d-8b78-482a-b1e5-0d3959dd0fdc"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"bf538282-3712-4044-b1f9-8e1f06b1fca6"}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"bdc6c855-d53a-4c7e-8278-bae01120f228"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"4bb533fe-25d9-41c2-8777-ea8a0ec800ba"}''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"88197f39-1b80-41c4-93b2-12573ca0adb1"}''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:24 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"b77d38f8-9f93-495a-8697-b8b17e37d549","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''
2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:24 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:24 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"3bf90dbf-cbae-439e-916a-a62406749984","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"f7fdadd0-94f0-461b-9873-500aa6551ae2","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"84d60195-7d55-4a24-b318-b9a49c5652cc"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"e51b166a-5c22-4ae9-8a0b-e319ef544017"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"a3719a46-1869-45f5-b44e-77f095efd07b"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"731aa47e-b4ec-457b-8fa2-d2b052c0f991"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"c0a2676b-ac4e-44db-9476-84e9ee1c4112"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"cb36bda8-5e3b-4dc1-935c-62a8a184e138"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"4ffd6b5a-1a43-4b56-b583-dde510e22e96","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"7c37d164-28b5-429a-b5af-03f013103faf","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"f6562e8a-a5bb-4144-bc53-603e7be589c1","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"666395f7-4a83-41c8-9ca1-432391858037"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"c1fb1e44-7912-44bb-a9f3-bab1d6810ee0"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"7ae8df5f-2ba2-447a-ab8c-47bb9281ddb8"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"db82a179-9e6f-47c4-9eb8-5fdac6650e59"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"30f8896e-428e-439f-bfb6-e15d55e39fa5"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"49da20e7-861b-486d-8939-8c18c9133c59"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"fe4e7e78-7fca-4ff6-8c42-3965b4c222b9","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''
2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''
2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"975a3d13-fa37-460b-b24b-57fa5072de55","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''
2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''
2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''
2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''
2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"ab8f551f-9396-4520-8c1d-091e732ff7e1","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"1edc0c61-42b7-494f-b05b-43385f3a8df4"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"9bc3723c-90b7-40eb-8967-142417210140"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"14edc856-ec77-4f38-b598-4f1e829615fc"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"722ac05e-9ea5-4b03-9c0d-867d29eaeb9d"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"1786fb38-b80e-4a9c-9e88-42ed6ee9339d"}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"f49ba67f-a047-47f7-bee8-62ad3ceb0f9f"}''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:25 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"5240b6ac-35a2-4217-bb26-1c062aa245a4","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"77a12e34-8a6f-4f04-a87a-634225ab962f","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:25 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:25 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"952d7194-2590-4738-bd4d-c3f16a00c7bb","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"3a5563eb-f11b-47df-aad2-06a77a1f1d07"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"4fcbe40e-88e9-4d15-ad99-21ef88da2542"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"b4a5f6ca-b951-43f9-b0c6-2c85a44ed444"}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"d184a6ff-6712-4d85-82ba-431495e75967"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"c70404f5-7dee-49f7-8638-bd4531d07c39"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"0c965617-e62a-4031-81dc-3510e85a1c1a"}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"b0893b54-14db-44f4-b38d-317c907e9fd9","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"065fa8b3-63b9-4e57-913e-a5cac907843e","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"73b1dba5-7ea9-4b91-8e44-e3b476a32901","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"721b17be-67b3-471e-bff2-51cae640c547"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"6782c92b-a947-4813-afe9-3665dadace5d"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"4d30cc5d-ab6e-467d-b4ff-7c9625cbf714"}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"e5951e0c-90d3-4354-b398-b8b05451be1d"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"da77e7ca-0d20-4cda-bf30-2856b7e8b3c2"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"91a5ba40-5a75-4e79-b2f3-bf1bbe8ee989"}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"6e13ac46-2d12-4d47-b022-12aacd912c11","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"107593da-97bf-49a7-b9e1-28a4c1efec12","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"3d39c054-ea67-4ceb-a37d-ed71aead3926","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"4cde06eb-854d-45ad-b2c9-84b415d850d2"}''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"34e3ea7b-f042-4c18-b3e6-4bb4732f592f"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"5215ca00-d211-406c-bd72-a4226401e94c"}''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 15:10:26 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"d4744934-ad22-4142-8bfe-a7c9836f38fc"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"51bd9701-5d27-42d4-a1b9-eab1ecdb2155"}''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:26 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:26 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"b42c345c-41c9-4732-b09f-955a8fc04fc1"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"12e04729-5c66-450b-bbba-082f711ab7e6","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"5fcec276-b97d-44fb-b259-24830ea029f1","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"e6ed6d32-0be7-4758-9039-7435e9a01ed7","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"81db3269-0816-4f08-afc9-d274caf9caef"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"046cd705-f061-4deb-9177-a020b5acf9a6"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"9d80cb7a-5549-4397-9785-49e3468c3508"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"5677c0a5-cf20-4fd5-a3bd-f38c79d94681"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"eb2c9644-bd60-4ab3-950b-e25dd2ebf0ac"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"106a5789-1cbc-42b3-839e-baa9ef8d1375"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"760cebd0-199f-462e-be7e-f2d7731b6c23","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"52920002-0fb3-4828-a50b-d5929a840b61","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"f014e662-4b4c-4fc3-8929-85eb7db107cb","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"2d2e844b-34ee-4204-be45-da485ab42b03"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"c6f1a75e-5e5f-4457-ac80-395aa8008466"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"3a297974-a301-4857-a41a-a1016e87d8f9"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"0040442b-fe46-4690-9877-f32957221a12"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"cf0750c0-0e13-4f8d-bcc8-b459d66d6d82"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"90ecffb3-c9c7-42e7-88b3-fb527d23b32c"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"70df9861-97d8-4952-8d63-2ad4941e9087","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"e06ef613-ce0d-415a-b8b9-38d87366ae40","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"52dfefc2-0249-415b-9e75-7965369c9088","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"360bdba0-2a97-4458-ba30-1df434b5664e"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"236f72a8-9112-4892-a1fc-7f0247b01e01"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"519111f9-6e19-485a-bba0-d24076bc6c5e"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"9ac910b2-72f7-4b6a-aed9-b2365b212d78"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"8632cf26-76d3-468d-975e-8b8e4f8bc6d3"}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"00cad419-d444-436e-93a3-309c67625377"}''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:27 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"9c86f2d0-816f-43ae-9f6b-c836b6c93bb5","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"0ac6eb5a-bdd4-4ac9-bfe1-9816c3c236fe","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:27 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:27 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"1f3d757d-e32a-427d-8e7b-8d52420fa041","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"905012df-20c7-470f-8ea6-ebafbfd0f404"}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"a29a221a-ae6b-461f-89c6-62ba545c7bf3"}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"28d8232a-6b96-4435-b7f3-5019593f18a0"}''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"8c9c3217-c679-47d9-be4b-965b24d686b4"}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"e6c05b1e-46ff-47dc-8c6e-5be732539fb4"}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"044db1b6-bb1c-4289-a9a9-caf73c5d33bc"}''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:28 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"5cb20015-f5e9-49f0-9a3d-b0a93156bcfa","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"40663c46-241e-433e-8e24-1f5df8d6a121","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:28 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:28 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"c5b7a6e0-f819-4322-91d6-6417c6d97609","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"6c88596c-ee38-4657-877d-012669902542"}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"698a28eb-d2d4-4607-8a09-4a995800f550"}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"2ba76cea-4601-42d2-938e-95ba8467f6b0"}''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"e11e8cb2-4cd8-44b5-89f6-548c0bb73b6e"}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"5705a044-8a06-406f-8c61-1c4994ee1eb3"}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"c589a0ab-4ffc-439b-91f8-1ae5eba5edb4"}''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:30 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"9f8f9317-f0ae-494d-a29d-1dd5a09b7f94","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"29126555-606b-4c09-a33f-4c2c5d386a01","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:30 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:30 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"95d4531f-ccf1-4885-991f-969838922847","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''
2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"6b8b9ef6-3926-4168-8346-b077dce7c293"}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"5a8816d6-8347-4946-8cf5-bb5ba39eb857"}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"94557ed3-a5d0-425c-a484-5cbb1f6ea36e"}''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"94715ebf-5119-4bc2-9b3e-22c4dcea1b0e"}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"b8e91e8b-f219-4d56-ba7c-4d01d12264b2"}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"6df672bd-ca2f-4b47-9269-3faa213b7672"}''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:31 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"df368422-fbc4-4ded-b356-bd254d9fb169","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"bd428b9f-2acd-46c2-8c02-168d67c7a40c","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:31 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:31 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"653c8afe-1cd9-4816-8ad4-fc8001ae99ca","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"d29a0b93-4e0b-48d7-8d5d-5d3a51d27ff6"}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"ee157c8c-8561-4222-88b9-1be8842d0ac2"}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"2b1490e0-4f5d-4470-a089-589211ae9ad6"}''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"6d988557-116c-4297-b703-054a0fccf02a"}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"0efb0882-4683-4d13-93b8-ea2f651f7035"}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"aeb52f0c-115a-450e-993f-9a049222ea45"}''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:32 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"9aa37a2a-c00f-4a26-bf20-8c3cda38d9ec","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"e460831a-e927-4f59-96a9-38d403d98191","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:32 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:32 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"68376e33-1ab2-4620-9950-8f0399d94670","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"8b0419e7-8cea-4688-ab4b-537428671da8"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"acead535-5ad1-45fa-9d59-67aec690befd"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"9626805a-6656-40d5-a2ee-d17c7b16aca0"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"b8d82279-0c40-478f-a29a-6a134474e354"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"ad8293b1-e640-44d1-a675-acf252639193"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"5548f21a-800a-40d1-b61a-16977ce4315a"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"ec8593b4-f607-4507-93e2-44f5e568337d","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"04d342e8-aef8-44a4-acaa-6ee2ae61838b","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"6b7469a2-5234-4e4a-aa52-97b870fbbf35","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"095a44d8-14db-4749-8db9-b0e0988b66f1"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"996b71b8-f153-46e8-bef0-b06880025307"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"e4218675-0531-4c6c-9577-9d55b6e5353f"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"b9734956-aa52-49b6-b724-548832cf9b33"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"058190d0-1dd8-4b48-b01e-94cf618ee451"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"532e43c6-f72a-4f43-9869-cf7ebd34d7dc"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"1b37a33b-4569-4520-95e3-c360da2fdf19","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"65c03730-5624-4679-9fd0-387baaffe312","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"b129b769-a084-4c11-951d-a5059e1ebdaa","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"990e01ed-0777-46c1-9717-b717e6e32785"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"33a2625f-0e11-4d50-abcd-9c61233fe0e6"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"f97d0b35-3f90-4112-a049-8969585265ce"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"42a390a6-56e0-47c8-a97f-16d3777ea87d"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"8474ef09-ae48-4050-b2bd-6afed81d9b4b"}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"fb596a80-9087-4fe6-a16c-13c62a5a0770"}''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-07 15:10:33 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"a0bd4710-6c12-485e-ab2b-fb7ff16859a5","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"ef188f72-3126-4de1-ba66-ec4e9a56d98d","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 15:10:33 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 15:10:33 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"abce778c-7207-4fa0-a52c-62f2cbc778ba","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"a29efa25-4e1c-44a2-b2ef-1cc62955766b"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"7b295e4e-e9ff-4636-a817-7492ff81a24d"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"d027e342-b572-46cb-86d0-21765ad1417a"}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"8991be75-6341-4079-9178-37e1a9311ada"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"844e1b24-b14d-49c4-9aea-e3f9810c339b"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"8a60eaca-2556-45e5-a2f7-d5b0ecd75eea"}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"b96a0a55-00f4-4cb3-8745-5bc7d981f608","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"dc72f846-6f95-432c-bb6a-2c1c3ed73b64","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"fb233ebf-708c-4650-ab94-33f8e695b69e","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"1058984d-c9e7-4ed1-a1f6-f2fa90ece9b3"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"eacb94d9-19a9-474b-ba89-96a598b0e2b3"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"d77925dd-efab-4ce6-8d3d-2ac7d11ce3f8"}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"750d9721-91a2-45fe-8668-487b4f9860d2"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"439b8e10-376d-4258-a988-d2a927a9c74e"}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"2ccdc4f3-ab40-4cea-82dd-8720312aac0c"}''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-07 15:10:34 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"74741855-2127-4587-a57a-2cc0215863fa","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"1fdee069-44e5-4570-b434-631448a69574","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:34 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:34 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"3a38675b-7609-4ac8-86c6-8c2ec3c8f801","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"d161dceb-d2b0-40ca-9491-2fcca3d3b6a5"}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"ba734d02-24a7-4de5-a629-126c2eb9d6f6"}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"96d6303c-ddbd-4cd1-9be6-d80796979f59"}''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"afa2beb8-6361-499f-b059-145db5405bc1"}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"c81f455a-5f81-4411-8dac-0876d1fbde14"}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"6489ef9a-8df8-421e-97a8-8a4ee81c87e2"}''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:35 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"e99f4b58-c0fa-4150-9d34-cab73ac907e1","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"6fc65dfd-0eb8-4654-a40a-e8570deeffd1","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:35 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:35 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"6639ccc1-815d-45c2-beb2-da4467b7ef1e","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"d17511a8-91ae-4956-9978-2e7f0b6d76b5"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"c6646f01-90cc-4e6e-b81c-f36f8e8586f9"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"f5523575-8e2d-4960-875d-f0c490ed7826"}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"b69510ec-8137-4ab3-b801-79196689e3af"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"47004502-4d97-42e1-bfae-b2606881436a"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"fb283eae-68cf-4109-8db1-47fa1a9a1d4c"}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"1736295f-083c-4c1f-985c-bab96b31fa11","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"20cd7642-329d-4c12-804a-75ab1656de95","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"5e5bb48d-8397-4da5-8158-b188a9eeb991","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"51d72a26-000f-455f-ad1f-e53bfac5ccbd"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"6984939c-bb97-47b5-80b9-173726d8ae5b"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"152361c4-567e-4794-a082-ddaa8d1787dd"}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"860f0826-a3a5-463d-967a-c7e3fd2d2003"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"f81ba638-5b65-40d3-bb19-5ad6f4ab8d12"}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"56194e72-6c0c-43ee-9b46-9bf8b79b69a0"}''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-07 15:10:36 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"430fae10-aefa-487e-ab6f-36dff6ddf6ae","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"896a7ca7-3afd-43b8-b5c8-24991220c401","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 15:10:36 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:36 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"69abcb35-f3f5-4862-8d93-40b3e309c8a7","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"03762813-d687-4d80-b855-a9347d0c4d0f"}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"bed9bd43-e614-49aa-9d71-697a1101e986"}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"50b0f4c0-33fc-4e2c-b447-96ea2eeaf2b1"}''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"a25602dc-2298-40c0-bdb5-a9e930b32d36"}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"c70ab7e6-0f58-441f-a4c1-47e5f6171ab7"}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"237ada4c-460e-4476-b3bd-8d94cf186a7a"}''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:38 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"8a8a6202-3799-4519-96ba-06e649934686","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"ecc85d29-a473-4b25-901d-028776a17dce","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''
2016-10-07 15:10:38 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''
2016-10-07 15:10:38 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"8fbfc539-808a-47d7-ba66-c25f80e7109a","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21"},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f"},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6"}]}''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"bf6467b7-9af9-4d74-b1a0-e064130a0ae9"}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"51ac6caf-732f-4bf3-bd19-9107de17b962"}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"aa99d144-7307-4485-a3a4-ef3f6895d6a9"}''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"31fe3199-aa2e-4892-8a1b-e8973772272e"}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"7c108468-d459-4908-9b6b-dbbaa1b82866"}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"6f09661e-1f50-4746-a0c2-99f979df19b6"}''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-07 15:10:39 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"315e6464-2d7a-4c16-b418-9def6201ced4","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21","data":[4,89,162,33,244,116,63,85,134,137,218,170,183,137,78,7,221,23,32,42,194,96,167,63,126,17,33,130,248,195,70,68,102,64,42,126,50,108,198,112,29,112,99,79,168,111,161,62,41,66,212,246,30,58,33,254,47,69,243,52,44,57,63,192,76]},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f","data":[4,110,166,7,31,224,219,32,101,233,130,130,225,165,81,61,0,19,216,16,232,233,207,122,217,34,54,245,143,93,12,24,135,83,70,218,2,254,170,93,179,110,62,40,101,132,87,169,101,57,21,26,168,211,148,71,250,36,49,139,251,242,231,9,122]},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6","data":[4,219,167,106,41,59,139,184,65,234,38,124,164,214,254,56,35,98,92,59,216,250,90,112,150,38,35,20,194,73,154,78,134,248,204,8,25,166,110,11,54,216,143,203,18,64,231,236,11,100,130,72,72,47,216,211,31,93,177,29,42,178,253,135,58]}]}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"999130e2-173d-406d-896b-ec1a2e30b8b3","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21","data":[4,89,162,33,244,116,63,85,134,137,218,170,183,137,78,7,221,23,32,42,194,96,167,63,126,17,33,130,248,195,70,68,102,64,42,126,50,108,198,112,29,112,99,79,168,111,161,62,41,66,212,246,30,58,33,254,47,69,243,52,44,57,63,192,76]},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f","data":[4,110,166,7,31,224,219,32,101,233,130,130,225,165,81,61,0,19,216,16,232,233,207,122,217,34,54,245,143,93,12,24,135,83,70,218,2,254,170,93,179,110,62,40,101,132,87,169,101,57,21,26,168,211,148,71,250,36,49,139,251,242,231,9,122]},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6","data":[4,219,167,106,41,59,139,184,65,234,38,124,164,214,254,56,35,98,92,59,216,250,90,112,150,38,35,20,194,73,154,78,134,248,204,8,25,166,110,11,54,216,143,203,18,64,231,236,11,100,130,72,72,47,216,211,31,93,177,29,42,178,253,135,58]}]}''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 15:10:39 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 15:10:39 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"0e6664cd-d6da-43b3-b4c6-86acceb93593","content":[{"uuid":"089cb41b-08f9-4686-822a-733643bbfd21","data":[4,89,162,33,244,116,63,85,134,137,218,170,183,137,78,7,221,23,32,42,194,96,167,63,126,17,33,130,248,195,70,68,102,64,42,126,50,108,198,112,29,112,99,79,168,111,161,62,41,66,212,246,30,58,33,254,47,69,243,52,44,57,63,192,76]},{"uuid":"5e17db30-6a75-4c4d-b2d8-cfec88c2fe6f","data":[4,110,166,7,31,224,219,32,101,233,130,130,225,165,81,61,0,19,216,16,232,233,207,122,217,34,54,245,143,93,12,24,135,83,70,218,2,254,170,93,179,110,62,40,101,132,87,169,101,57,21,26,168,211,148,71,250,36,49,139,251,242,231,9,122]},{"uuid":"c7e19229-2448-4b12-9f9f-3f4f682331d6","data":[4,219,167,106,41,59,139,184,65,234,38,124,164,214,254,56,35,98,92,59,216,250,90,112,150,38,35,20,194,73,154,78,134,248,204,8,25,166,110,11,54,216,143,203,18,64,231,236,11,100,130,72,72,47,216,211,31,93,177,29,42,178,253,135,58]}]}''

2016-10-07 15:13:40 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:40 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:40 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 15:13:40 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:40 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 15:13:40 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:40 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 15:13:40 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:40 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:177:5
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:142:10)
    at TestDevice.error (/home/pi/Test/server_87966432de46e75/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/UnitTestFramework.js:89:23''

2016-10-07 15:13:41 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:41 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:41 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:41 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:41 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:41 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:42 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:42 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:42 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:42 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:42 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:42 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:43 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:43 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:43 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:43 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:43 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:43 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:44 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:44 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:44 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:44 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:44 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:44 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:45 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:45 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:45 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:45 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:45 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:45 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:46 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:46 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:46 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:46 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:46 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:46 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:47 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"f499515f-b462-482b-bbda-2129bf331041","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:47 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:47 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"ecb53413-6839-4847-b218-72ab52ef121a","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:47 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 15:13:47 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"83cb9c15-3335-4376-8ee8-762e7da6b00d","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 15:13:47 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_87966432de46e75/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_87966432de46e75/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_87966432de46e75/test/TestServer/Socket.js:173:22)
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
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/87966432de46e75_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/87966432de46e75_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/87966432de46e75_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)




