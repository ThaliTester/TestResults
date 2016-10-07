#### Test 8796643296748b2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":3}}
2016-10-07 14:48:59 - INFO Server: 'listening on *:3000'

2016-10-07 14:50:38 - DEBUG Server: 'client connected'

2016-10-07 14:50:38 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:50:38 - DEBUG Server: 'device presented, name: 'samsung-SM-G930F', uuid: '0ac84495-cc72-4488-a835-b2b36088ad31', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:50:38 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G930F''

2016-10-07 14:50:39 - DEBUG Server: 'client connected'

2016-10-07 14:50:39 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:50:39 - DEBUG Server: 'device presented, name: 'samsung-SM-G935F', uuid: '7cce4670-8cb7-4bc2-bacd-dea840efdb89', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:50:39 - DEBUG TestFramework: 'device added, name: 'samsung-SM-G935F''

2016-10-07 14:50:58 - DEBUG Server: 'client connected'

2016-10-07 14:50:58 - DEBUG Socket: 'we are waiting for event: 'sync''

2016-10-07 14:50:58 - DEBUG Server: 'device presented, name: 'Huawei-Nexus 6P', uuid: '357cf535-fe55-4430-b339-6e04305b8ad5', platformName: 'android', type: 'unittest', hasRequiredHardware: 'true', nativeUTFailed: 'false''

2016-10-07 14:50:58 - DEBUG TestFramework: 'device added, name: 'Huawei-Nexus 6P''

2016-10-07 14:50:58 - INFO TestFramework: 'all required 3 devices are present for platformName: 'android''

2016-10-07 14:50:58 - DEBUG UnitTestFramework: 'starting unit tests on 3 devices, platformName: 'android''

2016-10-07 14:50:58 - DEBUG UnitTestFramework: 'scheduling tests'

2016-10-07 14:50:58 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:50:58 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"bad7ae3f-212b-49de-9236-a28518ba943d","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:50:58 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:50:58 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"d99d3080-b956-498f-a997-b5144ad906b8","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:50:58 - DEBUG Socket: 'we are waiting for event: 'schedule_confirmed''

2016-10-07 14:50:58 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"8bf5413f-7986-4ad9-b744-97b8ee4f3758","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:50:59 - DEBUG Socket: 'we are emitting data for event: 'schedule', data: '{"uuid":"d99d3080-b956-498f-a997-b5144ad906b8","content":["calling createNativeListener directly rejects","emits incomingConnectionState","emits routerPortConnectionFailed","native server connections all up","native server - closing incoming stream cleans outgoing socket","native server - closing incoming connection cleans outgoing socket","native server - closing outgoing socket cleans associated mux stream","native server - closing the whole server cleans everything up","native server - we can get a ton of connections and data through and still clean up the server completely","native server - simulate mux failure, make sure everything is cleaned up","native server - timing out the incoming connection cleans everything up","#_doImmediateSeqUpdate - server is not there","#_doImmediateSeqUpdate - server accepts & closes connection","#_doImmediateSeqUpdate - server always returns 500","#_doImmediateSeqUpdate - create new seq doc","#_doImmediateSeqUpdate - doc exists, need to get rev and update","#_doImmediateSeqUpdate - update seq three times","#_doImmediateSeqUpdate - rev got changed under us","#_doImmediateSeqUpdate - fail if stop is called","#_doImmediateSeqUpdate - stop after get but before put fails right","#update - fail if stop is called","#update - set seq for first time","#update - Fail on bad seq value","#update - do we cancel timer properly on an immediate?","#update - do we wait for blocked update","#update - test that we wait long enough","#update - test that we pick up new sequences while we wait","Coordinated seq test","closeAll can close even when connections open","closeAll with promise","closeAll properly throws when closing a non open server with eatNotRunning set to false","closeAll works even with a server that is not listening yet witheatNotRunning set to true","onPeerLost calls jxcore","onPeerDiscovered calls jxcore","Call of onCheckpointReached handler on a single db change","Call of multiple onCheckpointReached handlers on a single db change","Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval","Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval","test defaultDirectory","test defaultAdapter","enqueue and run in order","enqueueAtTop and run backwards","mix enqueue and enqueueAtTop","queues handled independently","basic","another","can pass data in setup","test thali manager spies","test thali manager multiple starts and stops","test write","test repeat write 1","test repeat write 2","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","should be able to call #stopListeningForAdvertisements many times","should be able to call #startListeningForAdvertisements many times","should be able to call #startUpdateAdvertisingAndListening many times","should be able to call #stopAdvertisingAndListening many times","#start should fail if called twice in a row","does not emit duplicate discoveryAdvertisingStateUpdate","does not send duplicate availability changes","can get the network status","wifi peer is marked unavailable if announcements stop","Client to server request coordinated","Test BEACONS_RETRIEVED_AND_PARSED locally","Test HTTP_BAD_RESPONSE locally","Test NETWORK_PROBLEM locally","Call the start two times","Call the kill before calling the start","Call the kill immediately after the start","Call the kill while waiting a response from the server","Test to exceed the max content size locally","Close the server socket while the client is waiting a response from the server. Local test.","Close the client socket while the client is waiting a response from the server. Local test.","#generatePreambleAndBeacons bad args","#generatePreambleAndBeacons empty keys to notify","#generatePreambleAndBeacons multiple keys to notify","#parseBeacons invalid ECDH public key in beaconStreamWithPreAmble","#parseBeacons invalid expiration in beaconStreamWithPreAmble","#parseBeacons expiration out of range lower","#parseBeacons expiration out of range lower","#parseBeacons no beacons returns null","#parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble","#parseBeacons addressBookCallback fails decrypt","#parseBeacons addressBookCallback returns no matches","#parseBeacons addressBookCallback returns spurious match","#parseBeacons addressBookCallback returns public key","validate generatePskIdentityField","validate generatePskSecret","validate generatePskSecrets","validate generateBeaconStreamAndSecrets","Add two Peers.","TCP_NATIVE peer loses DNS","Received beacons with no values for us","Resolves an action locally","Resolves an action locally using ThaliPeerPoolDefault","Action fails because of a bad hostname.","hostaddress is removed when the action is running. ","Client to server request locally","Test ThaliPskMapCache clean and expiration","Test ThaliPskMapCache getSecret and getPublic","Test ThaliPskMapCache multiple entries","Start and stop ThaliNotificationServer","Pass an empty array to ThaliNotificationServer.start","Pass a string to ThaliNotificationServer.start","Pass an empty parameter to ThaliNotificationServer.start","Make an HTTP request to /NotificationBeacons","Make an HTTP request to /NotificationBeacons (no keys)","Make an HTTP request to /NotificationBeaconsbefore calling start","#testThaliPeerAction - test getters","#testThaliPeerAction - start and kill","#testThaliPeerAction - double start","#testThaliPeerAction - start after kill","#testThaliPeerAction - make sure ids are unique","Test PeerConnectionInformation basics","Test PeerDictionary basic functionality","Test PeerDictionary with multiple entries.","RESOLVED entries are removed before WAITING state entry.","WAITING entries are removed before CONTROLLED_BY_POOL state entry.","When CONTROLLED_BY_POOL entry is removed and kill is called.","#ThaliPeerPoolDefault - single action","#ThaliPeerPoolDefault - multiple actions","#ThaliPeerPoolDefault - PSK Pool works","#ThaliPeerPoolDefault - stop","#ThaliPeerPoolInterface - make sure that start verifies queue length","#ThaliPeerPoolInterface - bad enqueues","#ThaliPeerPoolInterface - do not allow same object type","#ThaliPeerPoolInterface - make sure we catch kill and dequeue","#ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent","#ThaliPeerPoolInterface - make sure that stop removes all actions","Make sure peerDictionaryKey is reasonable","Make sure start works","Make sure stop works","Simple peer event","Coordinated pull replication from notification test","Server is not there","Server accepts & closes connection","Server always returns 500","Server always returns 401","Server always returns 403","Make sure docs replicate","Do nothing and make sure we time out","Do something and make sure we time out","Start replicating and then catch error when server goes","Coordinated replication action test","compareBufferArrays","Call start twice and get error","Start and make sure it runs","Make sure getTimeWhenRun is right after start","Make sure getTimeWhenRun is -1 after function is called","Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running","Test TransientState","No peers and empty database","One peer and empty DB","One peer with _Local set behind current seq","One peer with _Local set equal to current seq","One peer with _Local set ahead of current seq (and no this should not happen)","Three peers, one not in DB, one behind and one ahead","More than maximum peers, make sure we only send maximum allowed","two peers with empty DB, update the doc","add doc and make sure tokens refresh when they expire","start and stop and start and stop","two identical starts in a row","two different starts in a row","two stops and a start and two stops","we properly enqueue requests so no then needed","test calculateSeqPointKeyId","can create servers manager","calling stop without start causes error","can start/stop servers manager","starting twice resolves with listening port","terminateIncomingConnection will terminate a connection","terminate an Outgoing connection will terminate the server","terminate an Outgoing connection with wrong arguments is not harmful","After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted","#startUpdateAdvertisingAndListening should use different USN after every invocation","messages with invalid location or USN should be ignored","verify that Thali-specific messages are filtered correctly","#startListeningForAdvertisements should fail if start not called","#startUpdateAdvertisingAndListening should fail if start not called","#start should fail if called twice in a row","should not be started after stop is called","#startUpdateAdvertisingAndListening should fail invalid router has been passed","#startUpdateAdvertisingAndListening should fail if router server starting fails","#startUpdateAdvertisingAndListening should start hosting given router object","#startUpdateAdvertisingAndListening bad psk should be rejected object","#stop can be called multiple times in a row","#startListeningForAdvertisements can be called multiple times in a row","#stopListeningForAdvertisements can be called multiple times in a row","#stopAdvertisingAndListening can be called multiple times in a row","functions are run from a queue in the right order","does not get peer changes from self"]}''

2016-10-07 14:51:00 - DEBUG UnitTestFramework: 'tests scheduled'

2016-10-07 14:51:00 - DEBUG UnitTestFramework: '#setup: 'calling createNativeListener directly rejects''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:00 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"58b38e8a-861b-47df-9513-02bdb76d0a14"}''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:00 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"5cf94f98-00ee-4270-b65d-41cb1ee9d822"}''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:00 - DEBUG Socket: 'we are waiting for event: 'setup_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:00 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"c022fd79-7714-4510-8a80-9e6f73d63d4a"}''

2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'setup_calling createNativeListener directly rejects', data: '{"uuid":"5cf94f98-00ee-4270-b65d-41cb1ee9d822"}''

2016-10-07 14:51:01 - DEBUG UnitTestFramework: '#setup ok: 'calling createNativeListener directly rejects''

2016-10-07 14:51:01 - DEBUG UnitTestFramework: '#run: 'calling createNativeListener directly rejects''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"bbdb1ee7-be1b-4177-8331-411ead5d56a8","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"575a56ae-99d0-409a-ba44-bfefaaa788a6","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'run_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'run_calling createNativeListener directly rejects', data: '{"uuid":"87a9c2e9-9e78-47b6-80f4-995f4126a58e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:01 - DEBUG UnitTestFramework: '#run ok: 'calling createNativeListener directly rejects''

2016-10-07 14:51:01 - DEBUG UnitTestFramework: '#teardown: 'calling createNativeListener directly rejects''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''

2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"1d560672-51e7-46e3-8b82-577542c4ca38"}''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''

2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"6352d966-fba4-43e8-9433-6d4cfbac210c"}''
2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_finished''
2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_skipped''
2016-10-07 14:51:01 - DEBUG Socket: 'we are waiting for event: 'teardown_calling createNativeListener directly rejects_confirmed''
2016-10-07 14:51:01 - DEBUG Socket: 'we are emitting data for event: 'teardown_calling createNativeListener directly rejects', data: '{"uuid":"7f6ce294-5433-494b-b55f-67dc9b5cc6ca"}''

2016-10-07 14:51:02 - DEBUG UnitTestFramework: '#teardown ok: 'calling createNativeListener directly rejects''

2016-10-07 14:51:02 - DEBUG UnitTestFramework: '#setup: 'emits incomingConnectionState''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:51:02 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"9224e0db-2024-4843-8c8c-34fde9db1bc7"}''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:51:02 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"1c66fe3d-235e-4e5d-b1ca-aff69bc05c8b"}''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_finished''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_skipped''

2016-10-07 14:51:02 - DEBUG Socket: 'we are waiting for event: 'setup_emits incomingConnectionState_confirmed''

2016-10-07 14:51:02 - DEBUG Socket: 'we are emitting data for event: 'setup_emits incomingConnectionState', data: '{"uuid":"97acd2b2-0bd3-49ca-ac60-5e0479b3968b"}''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#setup ok: 'emits incomingConnectionState''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#run: 'emits incomingConnectionState''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"9e6bafee-0d97-412a-a873-ae24fd836d01","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"b2c77e5d-039a-46cd-b819-8109124cad91","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'run_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'run_emits incomingConnectionState', data: '{"uuid":"072b6df4-0a43-46b9-993c-9c789e0c1792","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#run ok: 'emits incomingConnectionState''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#teardown: 'emits incomingConnectionState''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"88ea17a2-a4c4-4d16-acea-0dde6e12419c"}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"3deb23ba-638e-4c92-993c-d42f74508700"}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'teardown_emits incomingConnectionState_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits incomingConnectionState', data: '{"uuid":"0a3dd3c2-221a-46f1-a960-5058641f1fa5"}''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#teardown ok: 'emits incomingConnectionState''

2016-10-07 14:51:03 - DEBUG UnitTestFramework: '#setup: 'emits routerPortConnectionFailed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"fb0c225b-0410-41a4-a90c-9a0982672413"}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"31743e32-e40a-4760-8ec4-1fb3b8a12660"}''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:03 - DEBUG Socket: 'we are waiting for event: 'setup_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:03 - DEBUG Socket: 'we are emitting data for event: 'setup_emits routerPortConnectionFailed', data: '{"uuid":"57be73bd-8fdf-45ed-ad14-4140dc879b5d"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup ok: 'emits routerPortConnectionFailed''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run: 'emits routerPortConnectionFailed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"1f0d1072-aefc-49c6-a52e-219f785bf769","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"729e0888-26f9-46d9-b052-55c4f1ad9c3e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_finished''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_skipped''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_emits routerPortConnectionFailed', data: '{"uuid":"642f3388-2c4e-4124-a695-b3ce2fb0c31e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run ok: 'emits routerPortConnectionFailed''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown: 'emits routerPortConnectionFailed''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"9262fd2c-f720-41c2-b92d-093db0b5afdb"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"24557fbd-ca42-4fa4-8f29-0ec1cf7c3a97"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_emits routerPortConnectionFailed_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_emits routerPortConnectionFailed', data: '{"uuid":"df1cebed-4a09-4aa6-8858-c0827cb200e9"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'emits routerPortConnectionFailed''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"5ebb47ba-260b-4b73-b7fc-4f04a08aa52f"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"93834ece-0309-4dbf-95ea-657b5cb3cf19"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server connections all up', data: '{"uuid":"4fd9e3f5-9278-475d-a28e-d6969c9fa58e"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup ok: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"1e49045b-9d95-4fb8-9170-f1c7dbc5cc90","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"2947eaae-1b11-435d-948c-417886d95b13","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server connections all up', data: '{"uuid":"d0913edd-8d0f-4e08-85dc-a170ecc7f1f5","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run ok: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"59a17c8d-f35b-4c8f-9680-5451f21990fb"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"bc684e93-e81a-4d52-a7b3-215ad9ecdd5c"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server connections all up_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server connections all up', data: '{"uuid":"2f3adc23-35f1-415e-8a32-84f40b271ff3"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'native server connections all up''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"c6d37edd-7949-430d-91ae-89571b6101fc"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"6af4dcf5-7617-4cba-9e2c-2c8278a838f8"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_skipped''
2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming stream cleans outgoing socket_confirmed''
2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"2072a262-810c-474a-8f59-0de40403dffe"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"c5346bf3-6360-4cec-9e35-e0f61e767617","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"f15ea803-c965-4d79-8610-329634a442a4","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"2d38b625-c624-4927-8592-c400d547d9c1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"49dfc2e9-8708-4e99-bd00-5790ef243f49"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"23febc1b-8d53-4fc8-8184-476d41e4f80a"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming stream cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming stream cleans outgoing socket', data: '{"uuid":"045d5701-8d99-47e4-b4c4-b4a96f96938b"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming stream cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"cdbe9f9c-d9f9-452b-aaf7-2a80ca1659a5"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"02ce0d17-a38f-4571-978d-dc1f057ff4ec"}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"3b020264-c921-4f80-97a6-e52c5d468e51"}''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG UnitTestFramework: '#run: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"fc121757-e792-43b8-82aa-0d9d396b480c","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:04 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:04 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"3efd7c17-5597-430d-b671-93734b1d1739","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"025cb58a-6d30-4cf2-9fd5-3cb0d5db4c27","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"727bb77a-b9f5-43eb-ae66-278d33882a5c"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"553d50e8-fe6b-4d9f-a318-00faf157c73c"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing incoming connection cleans outgoing socket_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing incoming connection cleans outgoing socket', data: '{"uuid":"f7938288-1d59-4d17-9836-bb828475ffcf"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing incoming connection cleans outgoing socket''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"a477f7be-3280-4ffa-980a-cfbc390308e1"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"e2c41a95-0379-4663-92aa-77f192a6a7a2"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"b7df00f8-3229-4f74-b33c-7b6b9219b947"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"4c8717af-b461-4c08-8502-961ffc1a94c8","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"8ab23027-5d32-41a5-9742-e0f0691f004b","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"1347ce77-baa0-479b-8a9c-b6a2f04b9d4f","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"56fefb65-ab22-4fca-97ce-4ddced67afb0"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"15282b27-b3fb-48fa-97db-a25d68d98249"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing outgoing socket cleans associated mux stream_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing outgoing socket cleans associated mux stream', data: '{"uuid":"4b8bd82b-49c8-47fc-9dac-0b832d519e73"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing outgoing socket cleans associated mux stream''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"3fcd4f29-2ae8-4d8c-a47a-2666277b37eb"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"b69defd9-4cf2-4282-95be-ca09472c3e6d"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - closing the whole server cleans everything up', data: '{"uuid":"de561ba1-bb40-4523-8a4f-bc9b2955c7de"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"5d5dfa07-1a31-46d3-942b-7747c3bb3e13","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"a39467e5-a73b-4631-a6fd-d61ea0d1f0e4","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - closing the whole server cleans everything up', data: '{"uuid":"bf556015-1bad-45f5-b275-e2e059dd6d93","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"9ab2820e-32ba-4c37-9ee7-1e0a25c2778f"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"f28f48dc-5419-48b0-b680-22efa84381f8"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - closing the whole server cleans everything up_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - closing the whole server cleans everything up', data: '{"uuid":"45209c09-3850-463b-a4a9-2a7ad75e8bf7"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#teardown ok: 'native server - closing the whole server cleans everything up''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"ffa24a45-608e-45e5-8bf2-476b505aac40"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"b506d07f-3be7-4a07-9f0f-98325c18c126"}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"889a20b6-d939-4082-8597-e167257358bb"}''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#setup ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:51:05 - DEBUG UnitTestFramework: '#run: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"a61fad31-b56a-4d21-9409-946ac68d972d","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"c8d9a167-f95c-478a-89d1-54090d49f317","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:05 - DEBUG Socket: 'we are waiting for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:05 - DEBUG Socket: 'we are emitting data for event: 'run_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"326b3757-3bfd-4333-91c3-362747e1c8bd","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#run ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#teardown: 'native server - we can get a ton of connections and data through and still clean up the server completely''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"a35864df-6e7e-4fe0-894b-4fc036e7d441"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"456c6b51-f909-42c9-99f5-5c301ebe35a4"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - we can get a ton of connections and data through and still clean up the server completely', data: '{"uuid":"177a2fa5-e022-4c3c-be85-f8e4b37785d2"}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#teardown ok: 'native server - we can get a ton of connections and data through and still clean up the server completely''
2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#setup: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"eba4a2d2-7953-46c0-b4ed-72798695b5fd"}''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"89659742-4597-4b27-974a-4f56f99527e4"}''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_finished''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"b544ae8d-70c1-4365-872d-db17a5649bd6"}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#setup ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#run: 'native server - simulate mux failure, make sure everything is cleaned up''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''
2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"84121dc0-0426-4a9b-8659-64acff758707","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''
2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"74028652-e7ca-4c9b-8d85-8d11b672eb4a","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"d7f26703-8fa7-4989-91d4-b20201217cb0","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#run ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#teardown: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"a7577833-6b2e-4c1d-887a-77fa893ccdd3"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"3c365642-4217-4a03-a2cd-f63f44482ca9"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - simulate mux failure, make sure everything is cleaned up', data: '{"uuid":"95a50a18-a820-490b-8e3e-8b1c51183306"}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#teardown ok: 'native server - simulate mux failure, make sure everything is cleaned up''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#setup: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"61b05ee0-6b99-45b1-9752-c7d4059d57e7"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"375960c1-5e0a-408b-80cc-dae103629615"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'setup_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'setup_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"563107dc-9431-4656-b2d4-e32e2b2cf0ea"}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#setup ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#run: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"e4fd3d8f-e4dc-474a-8efb-ca4c874f7636","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"9bed0c36-9e99-48cd-89a0-366a4a73017b","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'run_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'run_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"e55a55d1-8934-44f1-8892-a90623752512","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#run ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:06 - DEBUG UnitTestFramework: '#teardown: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"8ab13fc2-8431-4733-989f-a7be8c7fa591"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:06 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"390b0324-9533-4fe3-be66-49385f5b9df5"}''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_finished''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_skipped''

2016-10-07 14:51:06 - DEBUG Socket: 'we are waiting for event: 'teardown_native server - timing out the incoming connection cleans everything up_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_native server - timing out the incoming connection cleans everything up', data: '{"uuid":"26c176b7-6c7f-492e-b462-8ace0f2a627c"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown ok: 'native server - timing out the incoming connection cleans everything up''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"82acf2d0-3064-4fce-aa8a-6b7eae4eec87"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"5586751b-a686-411d-a4fd-9753a372e461"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"a42a12b1-6774-46be-8b6e-204262bd62b9"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server is not there''
2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''
2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''
2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"0d46b103-0ef6-40ba-bf85-9ec8d6f8b828","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"f0c60a4d-e94f-4758-803e-ea2b3be06ce4","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"f3f1939a-1fc4-4f46-90aa-f644c8f0adb1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"b4897563-6b47-45cb-b758-462714acbabe"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"1b492350-be2c-4b62-831f-801a3e44b724"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server is not there_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server is not there', data: '{"uuid":"480dc61f-d0b4-4c03-a711-164b983474b2"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server is not there''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"c145c966-d2d2-4245-b7d1-fdef3652b107"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"4b508d50-b806-496a-8ac1-e802807bffbe"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"2ff44975-2496-4d04-b849-e4e068388886"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"be87a253-ff67-4df4-be8f-69e2f58cce04","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"d6185e13-867a-45fd-b2be-0ed0bc74def9","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"aec63c25-a468-43a4-8d51-2ac408c21f96","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"2692a61e-be5f-459f-9088-c45adeeccac9"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"207ad052-200b-407a-afc7-8398f1fe8d6e"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server accepts & closes connection', data: '{"uuid":"84c2835b-c215-46bc-bdfd-8a50353b2b7e"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server accepts & closes connection''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"ac01bca6-6631-4835-abef-5cb2386ad81f"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"51cdedf9-3083-4aa1-b104-2fcd386c298e"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"42606609-0f78-4a15-a755-0289e144380e"}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"b6075320-c3f7-4f85-89a6-8e8da43354cb","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"910e1fce-5d28-43a3-8dc7-5039d72be1ad","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"d48458f2-6814-4657-9423-7459a31d2d76","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:07 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"355a7b8b-6211-479e-a4b1-532f59dfb5d7"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"44f30f25-afa9-4907-b26d-89d92dec9676"}''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_finished''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_skipped''

2016-10-07 14:51:07 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500_confirmed''

2016-10-07 14:51:07 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - server always returns 500', data: '{"uuid":"52bf10bc-985d-4a5f-807d-7cb3749e452b"}''

2016-10-07 14:51:08 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - server always returns 500''

2016-10-07 14:51:08 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"b80bc514-c1c7-415b-8196-e57e7fe5d71a"}''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"c6b7e5eb-5f9f-4b03-9b57-10dc78768a8e"}''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"10afce5c-87b0-4705-aefa-2405db5b9c4a"}''

2016-10-07 14:51:08 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:08 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"46fe9b90-7f6c-4355-9e90-2bac7228f8b3","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"f08617de-5e8d-41ca-ba02-3b4e18d63670","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:08 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:08 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"ee33db2b-58c2-4c2e-b88d-5dfa606bbd62","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:09 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:09 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"f5df9448-6c4c-4bd7-9c44-b8e3a41ac57a"}''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"208b0632-7436-499d-9b47-c7e9a80612fc"}''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_finished''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_skipped''

2016-10-07 14:51:09 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc_confirmed''

2016-10-07 14:51:09 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - create new seq doc', data: '{"uuid":"a4e057ef-529d-4190-b78a-5c714c5cadb6"}''

2016-10-07 14:51:10 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - create new seq doc''

2016-10-07 14:51:10 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"968f88fc-6fbb-439e-b687-da7bb87c9ca9"}''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"6fd634ce-2549-4c7d-84d8-6d2e206e6bc0"}''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"4d3f181e-cc3d-4835-b795-9914f6651486"}''

2016-10-07 14:51:10 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:10 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"425e6bdb-794b-41f0-953d-0487c0e2058e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''
2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"fe95bb19-2cb5-4db8-bc54-5c22af24adba","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''
2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:10 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:10 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"fcf20a18-2228-420c-90e3-4e8ed2ba24ae","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"d3af0e44-8c35-4be8-afbc-98df0821939b"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"87d1fca2-cb1e-493e-abd8-abac310b4580"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - doc exists, need to get rev and update', data: '{"uuid":"5f0d56e7-9290-4c4b-88a2-76890d592cb7"}''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - doc exists, need to get rev and update''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"1a0267cb-0ef0-49fd-a679-a10f1cbb8241"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"d1bfc09c-de1c-40a4-9d1c-c97abb2b0897"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"6f225b5d-ffbe-4114-8bea-13c3c6cb7c5a"}''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"7d9bda10-a9f3-40bd-8d46-844ccd154057","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"45f909e3-0a34-4e25-a5f9-496538b5c874","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"f5954afc-d181-4302-b063-0e46f04f0ce7","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:11 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"fdb3cf4c-a477-4fa0-8691-6501dfa56bca"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"9443944b-2470-4c86-96d7-bf49586986f2"}''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_finished''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_skipped''

2016-10-07 14:51:11 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - update seq three times_confirmed''

2016-10-07 14:51:11 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - update seq three times', data: '{"uuid":"59da2341-40a8-474b-b371-f2a06d9b99be"}''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - update seq three times''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"8885a399-41ba-4661-afdc-95c6ab55ca8c"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"7d50ca9a-d5e0-4025-8905-08efd8bbe16b"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"c3815f6a-1cb4-48a5-b8f8-c9b84fa3b30a"}''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"527967ab-da0a-49ab-87d5-3f1fea6c465e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"53423dd4-1eff-40c1-afb0-b429c07a34b3","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"1430f97b-967b-491b-9ed0-417ca93cfb24","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"4d71b116-2333-4a21-92b6-a3026bea0145"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"35d2f909-9fcc-4f35-aa10-b4d22a00ece0"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - rev got changed under us', data: '{"uuid":"20016da6-1f42-489c-99b8-f235b3225c94"}''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - rev got changed under us''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"cd591811-f530-490c-8451-8c047da5f8cb"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"75f1fda6-5101-4ca1-8f58-62a97e21ea55"}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"0fa47931-04a0-4278-8963-93da3fb11f8e"}''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:12 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"80c0dd4f-3958-46e1-80a6-9e124cfb4ef4","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"19b413e4-e4a2-4f68-82a2-412d6a72c87a","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:12 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:12 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"15103899-af29-428d-b1fb-c7c6d7a9f632","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"f91a842c-d299-40fc-a8e2-e5bd4f47c515"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"3bc55195-74d7-4cb2-b5e3-a4a99cdf789d"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - fail if stop is called', data: '{"uuid":"79b39bd8-d3a5-4085-ba21-d0366ea9d422"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - fail if stop is called''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"b331f52b-6fbc-4ec3-a100-94328843b836"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"3017ff40-5459-4d02-bbae-2e5666e5c0e2"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"d7a0a247-302f-49d6-9c44-a25dcf2e5dce"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"24e333a2-0f1b-42aa-9539-70b715391800","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"c9b98987-87f0-4f98-b5b7-5139f8f4d7a5","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"378bf283-3605-4f0e-96ec-5530af13a9d1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"680206ee-be1f-4601-bad4-ce501a1ebff5"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"16c5094e-9850-4f23-b590-7d1460c8966b"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#_doImmediateSeqUpdate - stop after get but before put fails right', data: '{"uuid":"450e30ca-2f49-488d-b68a-4a23b9b108a8"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown ok: '#_doImmediateSeqUpdate - stop after get but before put fails right''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"07e22239-9622-448a-81fb-8dd21928e8e0"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"d69c8367-4ccf-4b5a-a3e7-e116f2a5a8c1"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - fail if stop is called', data: '{"uuid":"fda5567e-3e76-4bf5-95d8-e855333336ee"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup ok: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"beca1493-a208-4c72-89c0-87e4c37fb751","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"14474c8a-788e-42d1-892b-fc7e66122bf3","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#update - fail if stop is called', data: '{"uuid":"d3b33575-e739-4c89-b4f3-642060c8add0","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run ok: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"3ee0408d-629d-4968-8e15-01fdf6e3a05c"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"61c98eba-af90-4cac-bbfe-5f5adede0171"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - fail if stop is called_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - fail if stop is called', data: '{"uuid":"07dd975c-33a8-4b2a-8b03-e58ca7210bfa"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#teardown ok: '#update - fail if stop is called''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup: '#update - set seq for first time''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"39fc3da7-1236-4ab0-b410-960973e4d9dc"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"a18b9932-e516-4caf-8982-451480ea5cb9"}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'setup_#update - set seq for first time_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - set seq for first time', data: '{"uuid":"6a66b08c-d1a3-4eed-9993-cb5cc0766f74"}''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#setup ok: '#update - set seq for first time''

2016-10-07 14:51:13 - DEBUG UnitTestFramework: '#run: '#update - set seq for first time''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"6840e8e8-7976-43c3-b7b2-c6457142dd62","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:51:13 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"65044103-74d5-4911-bc8e-1d53a107dd03","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:13 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - set seq for first time_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'run_#update - set seq for first time', data: '{"uuid":"6489f644-bbaf-4ea6-b22c-5669b1ce0fbe","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#run ok: '#update - set seq for first time''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#teardown: '#update - set seq for first time''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"3ac80039-3b2f-4873-8b96-e8068586e930"}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"376023bc-fa02-4ceb-af31-8930ac1cea98"}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - set seq for first time_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - set seq for first time', data: '{"uuid":"52b4efe2-848b-483b-bc62-c9380803d180"}''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#teardown ok: '#update - set seq for first time''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#setup: '#update - Fail on bad seq value''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"3dd9affa-1610-4393-bfc5-d3c8de173a1f"}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"f4c1f87f-b2f1-46b2-ae94-d13ccfefe136"}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'setup_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - Fail on bad seq value', data: '{"uuid":"d50233e3-6bed-4d5b-9819-2d3df10e1f87"}''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#setup ok: '#update - Fail on bad seq value''

2016-10-07 14:51:14 - DEBUG UnitTestFramework: '#run: '#update - Fail on bad seq value''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"54b6808e-fa7f-4c0e-9d89-fbb6b8159a1e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"cd1b1b49-95b2-422b-a1f4-60c49203d18d","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_finished''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:14 - DEBUG Socket: 'we are waiting for event: 'run_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:14 - DEBUG Socket: 'we are emitting data for event: 'run_#update - Fail on bad seq value', data: '{"uuid":"9be58701-14a9-40b1-a1dd-4f9991d62ae2","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#run ok: '#update - Fail on bad seq value''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#teardown: '#update - Fail on bad seq value''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"884ce4ea-1440-4149-8217-0dbda76cfba6"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"898a3189-5cc1-4857-9618-44b9e1b2fb08"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - Fail on bad seq value_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - Fail on bad seq value', data: '{"uuid":"6d4fc8bd-245d-47de-a5fd-7652c104853d"}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#teardown ok: '#update - Fail on bad seq value''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#setup: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"57c4a22f-5fc4-4661-9e34-8469a48bb899"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"a028df82-045e-4261-b018-3aa73977e32f"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"864ac994-6b22-4b1b-b8cb-cbc09c26741b"}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#setup ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#run: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"7fdc78b3-1a6e-48b8-bfda-91644b4f009d","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"46a9ea1e-0cbc-44b1-a529-6d66a8dc3838","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"b178a191-2401-4a46-a1d0-1580edfad014","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#run ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#teardown: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"5cd0cae5-dcc8-410d-bc40-d2eed1d787f7"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"acb71ca9-4208-4e05-ac43-45c5e3b59c0c"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we cancel timer properly on an immediate?_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we cancel timer properly on an immediate?', data: '{"uuid":"056476fc-7404-48fa-93ff-74fb44b8948f"}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we cancel timer properly on an immediate?''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#setup: '#update - do we wait for blocked update''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"7c7c318d-9c7a-473b-8c70-13293ee6454d"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"8c497f37-11e5-464e-adda-c3164c53df24"}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'setup_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - do we wait for blocked update', data: '{"uuid":"64187c51-f766-44a7-89d7-1b0fc02d2a3b"}''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#setup ok: '#update - do we wait for blocked update''

2016-10-07 14:51:15 - DEBUG UnitTestFramework: '#run: '#update - do we wait for blocked update''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"65442988-4abd-45b0-add3-d0c547881f70","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:15 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:15 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"12de8da2-7efc-40ec-b97f-225fdeed4ac2","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'run_#update - do we wait for blocked update', data: '{"uuid":"edc2de0d-07e9-4e79-bde9-854823855a1e","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#run ok: '#update - do we wait for blocked update''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#teardown: '#update - do we wait for blocked update''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"0325bff5-cd8a-4f9c-8f9c-fa2190adcaba"}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"1c433e14-b9de-4239-b1cc-08b01dbcbcaf"}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - do we wait for blocked update_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - do we wait for blocked update', data: '{"uuid":"04c41e68-7bdf-4e87-98e0-60a57c36359c"}''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#teardown ok: '#update - do we wait for blocked update''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#setup: '#update - test that we wait long enough''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"18d071cf-d4f8-4277-aeeb-1a24219829aa"}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"1b644830-b35f-4d5b-8f32-2931f9d99197"}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we wait long enough', data: '{"uuid":"c6b8b7fe-0467-4068-937d-5d090dad849e"}''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we wait long enough''

2016-10-07 14:51:16 - DEBUG UnitTestFramework: '#run: '#update - test that we wait long enough''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"f0035df8-38f0-4a26-a881-6016f64b9197","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"1ff305a6-0a80-4319-a844-82b2227b8039","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_finished''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_skipped''

2016-10-07 14:51:16 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:16 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we wait long enough', data: '{"uuid":"281f77cf-8e6f-4e99-ba70-9503a8938b99","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#run ok: '#update - test that we wait long enough''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#teardown: '#update - test that we wait long enough''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"d338355b-6266-44e0-8e69-bf6ef4eb9183"}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"b84c0771-33f8-4b28-94cf-96c5a649e351"}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we wait long enough_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we wait long enough', data: '{"uuid":"8e249cfc-6576-41a6-8013-70b776610ec5"}''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we wait long enough''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#setup: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"cefeaa77-d602-4c1a-a0ef-daa9a1d17407"}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"ef1346fb-87f9-46d2-ad26-66c55a6587e1"}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'setup_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'setup_#update - test that we pick up new sequences while we wait', data: '{"uuid":"1aa8c18a-1c96-4c79-8247-4fe98f245ceb"}''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#setup ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:18 - DEBUG UnitTestFramework: '#run: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"de1bc896-4e74-4f75-a74d-fbf0e1f7b6e1","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"93799703-8324-431e-bb75-c8c112877046","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:18 - DEBUG Socket: 'we are waiting for event: 'run_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:18 - DEBUG Socket: 'we are emitting data for event: 'run_#update - test that we pick up new sequences while we wait', data: '{"uuid":"2386d749-585a-47f2-926d-a2159ca2c410","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31"},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89"},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5"}]}''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#run ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#teardown: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"a9f9bd74-d88b-4ed9-853e-ce4a358db129"}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"40041fc6-817b-43ec-80e4-387342caf44f"}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'teardown_#update - test that we pick up new sequences while we wait_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'teardown_#update - test that we pick up new sequences while we wait', data: '{"uuid":"ca59a6ab-b1ee-4563-8d21-8333e4c71047"}''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#teardown ok: '#update - test that we pick up new sequences while we wait''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#setup: 'Coordinated seq test''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''
2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"bb890631-7d84-4be6-9030-a0ec726075d3"}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"86e1be8b-38d7-466a-bcc4-17596f5e633b"}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'setup_Coordinated seq test_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'setup_Coordinated seq test', data: '{"uuid":"8f104aa9-4592-4069-958d-3057982360ed"}''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#setup ok: 'Coordinated seq test''

2016-10-07 14:51:19 - DEBUG UnitTestFramework: '#run: 'Coordinated seq test''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"140607e7-26b8-48f3-82c8-5a217ec0210c","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31","data":[4,13,2,237,65,107,95,43,25,150,7,81,216,172,217,146,13,25,143,47,92,228,230,207,74,101,202,139,180,102,88,214,109,106,199,86,243,1,201,221,213,232,91,169,96,149,233,196,50,233,166,165,125,176,11,109,33,244,144,10,240,108,44,62,158]},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89","data":[4,138,110,77,59,243,2,252,183,176,15,78,90,206,73,47,234,153,195,144,153,249,192,31,121,73,93,151,43,147,141,30,247,251,230,44,11,228,28,127,158,82,84,3,249,113,221,73,228,193,244,85,21,79,221,249,33,19,113,98,114,70,218,47,38]},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5","data":[4,161,207,4,87,39,129,101,238,62,80,166,85,125,90,180,9,57,150,171,139,11,241,22,247,66,174,165,112,54,36,21,113,203,255,80,70,17,72,219,196,163,61,145,20,4,70,73,30,41,130,228,53,57,91,27,200,230,120,171,223,128,163,158,241]}]}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"d267a442-fd53-4a93-add4-8b0dca592885","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31","data":[4,13,2,237,65,107,95,43,25,150,7,81,216,172,217,146,13,25,143,47,92,228,230,207,74,101,202,139,180,102,88,214,109,106,199,86,243,1,201,221,213,232,91,169,96,149,233,196,50,233,166,165,125,176,11,109,33,244,144,10,240,108,44,62,158]},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89","data":[4,138,110,77,59,243,2,252,183,176,15,78,90,206,73,47,234,153,195,144,153,249,192,31,121,73,93,151,43,147,141,30,247,251,230,44,11,228,28,127,158,82,84,3,249,113,221,73,228,193,244,85,21,79,221,249,33,19,113,98,114,70,218,47,38]},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5","data":[4,161,207,4,87,39,129,101,238,62,80,166,85,125,90,180,9,57,150,171,139,11,241,22,247,66,174,165,112,54,36,21,113,203,255,80,70,17,72,219,196,163,61,145,20,4,70,73,30,41,130,228,53,57,91,27,200,230,120,171,223,128,163,158,241]}]}''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_finished''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_skipped''

2016-10-07 14:51:19 - DEBUG Socket: 'we are waiting for event: 'run_Coordinated seq test_confirmed''

2016-10-07 14:51:19 - DEBUG Socket: 'we are emitting data for event: 'run_Coordinated seq test', data: '{"uuid":"48a1ec86-97d5-4789-a7e7-af826e10dad3","content":[{"uuid":"0ac84495-cc72-4488-a835-b2b36088ad31","data":[4,13,2,237,65,107,95,43,25,150,7,81,216,172,217,146,13,25,143,47,92,228,230,207,74,101,202,139,180,102,88,214,109,106,199,86,243,1,201,221,213,232,91,169,96,149,233,196,50,233,166,165,125,176,11,109,33,244,144,10,240,108,44,62,158]},{"uuid":"7cce4670-8cb7-4bc2-bacd-dea840efdb89","data":[4,138,110,77,59,243,2,252,183,176,15,78,90,206,73,47,234,153,195,144,153,249,192,31,121,73,93,151,43,147,141,30,247,251,230,44,11,228,28,127,158,82,84,3,249,113,221,73,228,193,244,85,21,79,221,249,33,19,113,98,114,70,218,47,38]},{"uuid":"357cf535-fe55-4430-b339-6e04305b8ad5","data":[4,161,207,4,87,39,129,101,238,62,80,166,85,125,90,180,9,57,150,171,139,11,241,22,247,66,174,165,112,54,36,21,113,203,255,80,70,17,72,219,196,163,61,145,20,4,70,73,30,41,130,228,53,57,91,27,200,230,120,171,223,128,163,158,241]}]}''

2016-10-07 14:54:19 - ERROR UnitTestFramework: '#run failed: 'Coordinated seq test', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:19 - ERROR UnitTestFramework: 'failed to run unit tests, platformName: 'android', error: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'', stack: 'TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'
    at afterTimeout (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/timers.js:49:15)
    at timeoutTimeout [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/timers.js:76:13)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:19 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:54:19 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:19 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:54:19 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:19 - DEBUG Socket: 'we are waiting for event: 'error_confirmed''

2016-10-07 14:54:19 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:19 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:177:5
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Socket.emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:142:10)
    at TestDevice.error (/home/pi/Test/server_8796643296748b2/test/TestServer/TestDevice.js:134:23)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/UnitTestFramework.js:89:23''

2016-10-07 14:54:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:20 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:20 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:20 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:20 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:21 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:21 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:21 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:21 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:22 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:22 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:22 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:22 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:23 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:23 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:24 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:24 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:24 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:24 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:25 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:25 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:25 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:25 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:26 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:26 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:26 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:26 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"1d58970e-267b-44a0-8e45-00b7ddc423b6","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:27 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"5c028132-0549-4fb3-8592-fbc4b5944559","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:27 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
    at Timer.listOnTimeout [as ontimeout] (timers.js:120:15)''

2016-10-07 14:54:27 - DEBUG Socket: 'we are emitting data for event: 'error', data: '{"uuid":"611ac46c-bea2-4a11-80c5-1a4cd373de16","content":"TimeoutError: timeout exceeded, event: 'run_Coordinated seq test_finished', test: 'Coordinated seq test'"}''

2016-10-07 14:54:27 - ERROR Server: 'socket error: 'Error: NsSocket: sending on a bad socket', stack: 'Error: NsSocket: sending on a bad socket
    at send (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/nssocket/lib/nssocket.js:147:31)
    at /home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:99:12
    at Promise._execute (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/debuggability.js:299:9)
    at Promise._resolveFromExecutor (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:481:18)
    at new Promise (/home/pi/Test/server_8796643296748b2/test/TestServer/node_modules/bluebird/js/release/promise.js:77:14)
    at Server._emitData (/home/pi/Test/server_8796643296748b2/test/TestServer/Server.js:98:10)
    at updatedHandler (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:108:29)
    at Socket._apply (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:114:3)
    at emit [as _onTimeout] (/home/pi/Test/server_8796643296748b2/test/TestServer/Socket.js:173:22)
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
STOP log received from ce061606e320561102
Test has FAILED

STOP log received from ce0616068b9f212302
Test has FAILED

Device test finished on ce061606e320561102 
Device test finished on ce0616068b9f212302 
Android task is completed. [FAILED]
```
[samsung-SM-G930F](https://github.com/ThaliTester/TestResults/blob/8796643296748b2_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G930F.md)

[samsung-SM-G935F](https://github.com/ThaliTester/TestResults/blob/8796643296748b2_Do_not_merge__CI_test_andrew-aladev/thali05_samsung-SM-G935F.md)

[Huawei-Nexus 6P](https://github.com/ThaliTester/TestResults/blob/8796643296748b2_Do_not_merge__CI_test_andrew-aladev/thali05_Huawei-Nexus 6P.md)




