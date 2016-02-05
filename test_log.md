#### Test 5753124374916c2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-05T14:18:00.622Z - info: listening on *:3000

2016-02-05T14:18:00.999Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-02-05T14:18:01.866Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:2

2016-02-05T14:18:02.121Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-02-05T14:18:02.675Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:4

2016-02-05T14:18:02.935Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:5

2016-02-05T14:18:03.760Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-02-05T14:18:04.006Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-05T14:18:04.007Z - info: Required number of ios devices presented (2)

2016-02-05T14:18:04.012Z - info: Starting unit test run for platform: ios

2016-02-05T14:18:04.150Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:7

2016-02-05T14:18:05.717Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:8

2016-02-05T14:18:06.873Z - info: Running on ios test: multiplex can send data

2016-02-05T14:18:06.881Z - info: emit: Apple-Iphone6-1 setup_multiplex can send data

2016-02-05T14:18:06.884Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-05T14:18:06.902Z - info: ack: Apple-Iphone6-1 setup_multiplex can send data

2016-02-05T14:18:07.240Z - info: ack: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-05T14:18:07.263Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-05T14:18:07.266Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-05T14:18:07.288Z - info: ack: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-05T14:18:08.267Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-05T14:18:09.271Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-05T14:18:09.369Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-02-05T14:18:09.370Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-05T14:18:10.023Z - info: ack: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-05T14:18:10.108Z - info: emit: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-05T14:18:10.111Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-05T14:18:10.132Z - info: ack: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-05T14:18:10.135Z - info: ack: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-05T14:18:10.157Z - info: Running on ios test: enqueue and run in order

2016-02-05T14:18:10.159Z - info: emit: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-05T14:18:10.163Z - info: emit: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-05T14:18:10.171Z - info: ack: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-05T14:18:10.179Z - info: ack: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-05T14:18:10.200Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-05T14:18:10.203Z - info: emit: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-05T14:18:10.214Z - info: ack: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-05T14:18:10.231Z - info: ack: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-05T14:18:10.410Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-05T14:18:10.454Z - info: emit: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-05T14:18:10.457Z - info: emit: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-05T14:18:10.472Z - info: ack: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-05T14:18:10.479Z - info: ack: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-05T14:18:10.497Z - info: Running on ios test: basic

2016-02-05T14:18:10.500Z - info: emit: Apple-Iphone6-1 setup_basic

2016-02-05T14:18:10.512Z - info: emit: Apple-IpadAir2-1 setup_basic

2016-02-05T14:18:10.533Z - info: ack: Apple-Iphone6-1 setup_basic

2016-02-05T14:18:10.541Z - info: ack: Apple-IpadAir2-1 setup_basic

2016-02-05T14:18:10.558Z - info: emit: Apple-Iphone6-1 start_test_basic

2016-02-05T14:18:10.561Z - info: emit: Apple-IpadAir2-1 start_test_basic

2016-02-05T14:18:10.580Z - info: ack: Apple-Iphone6-1 start_test_basic

2016-02-05T14:18:10.591Z - info: ack: Apple-IpadAir2-1 start_test_basic

2016-02-05T14:18:10.607Z - info: emit: Apple-Iphone6-1 teardown_basic

2016-02-05T14:18:10.610Z - info: emit: Apple-IpadAir2-1 teardown_basic

2016-02-05T14:18:10.628Z - info: ack: Apple-Iphone6-1 teardown_basic

2016-02-05T14:18:10.634Z - info: ack: Apple-IpadAir2-1 teardown_basic

2016-02-05T14:18:10.651Z - info: Running on ios test: another

2016-02-05T14:18:10.654Z - info: emit: Apple-Iphone6-1 setup_another

2016-02-05T14:18:10.658Z - info: emit: Apple-IpadAir2-1 setup_another

2016-02-05T14:18:10.677Z - info: ack: Apple-Iphone6-1 setup_another

2016-02-05T14:18:10.682Z - info: ack: Apple-IpadAir2-1 setup_another

2016-02-05T14:18:10.701Z - info: emit: Apple-Iphone6-1 start_test_another

2016-02-05T14:18:10.703Z - info: emit: Apple-IpadAir2-1 start_test_another

2016-02-05T14:18:10.724Z - info: ack: Apple-Iphone6-1 start_test_another

2016-02-05T14:18:10.729Z - info: ack: Apple-IpadAir2-1 start_test_another

2016-02-05T14:18:10.751Z - info: emit: Apple-Iphone6-1 teardown_another

2016-02-05T14:18:10.756Z - info: emit: Apple-IpadAir2-1 teardown_another

2016-02-05T14:18:10.770Z - info: ack: Apple-Iphone6-1 teardown_another

2016-02-05T14:18:10.779Z - info: ack: Apple-IpadAir2-1 teardown_another

2016-02-05T14:18:10.813Z - info: Running on ios test: Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.816Z - info: emit: Apple-Iphone6-1 setup_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.818Z - info: emit: Apple-IpadAir2-1 setup_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.830Z - info: ack: Apple-Iphone6-1 setup_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.840Z - info: ack: Apple-IpadAir2-1 setup_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.861Z - info: emit: Apple-Iphone6-1 start_test_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.863Z - info: emit: Apple-IpadAir2-1 start_test_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.875Z - info: ack: Apple-IpadAir2-1 start_test_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.879Z - info: ack: Apple-Iphone6-1 start_test_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.901Z - info: emit: Apple-Iphone6-1 teardown_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:10.904Z - info: emit: Apple-IpadAir2-1 teardown_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:11.140Z - info: ack: Apple-Iphone6-1 teardown_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:11.157Z - info: ack: Apple-IpadAir2-1 teardown_Can call start/stopListeningForAdvertisements

2016-02-05T14:18:11.163Z - info: Running on ios test: Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.167Z - info: emit: Apple-Iphone6-1 setup_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.171Z - info: emit: Apple-IpadAir2-1 setup_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.223Z - info: ack: Apple-IpadAir2-1 setup_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.238Z - info: ack: Apple-Iphone6-1 setup_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.263Z - info: emit: Apple-Iphone6-1 start_test_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.266Z - info: emit: Apple-IpadAir2-1 start_test_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.294Z - info: ack: Apple-Iphone6-1 start_test_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.348Z - info: ack: Apple-IpadAir2-1 start_test_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.358Z - info: emit: Apple-Iphone6-1 teardown_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.363Z - info: emit: Apple-IpadAir2-1 teardown_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.660Z - info: ack: Apple-Iphone6-1 teardown_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.664Z - info: ack: Apple-IpadAir2-1 teardown_Calling startListeningForAdvertisements twice is an error

2016-02-05T14:18:11.672Z - info: Running on ios test: Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.679Z - info: emit: Apple-Iphone6-1 setup_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.682Z - info: emit: Apple-IpadAir2-1 setup_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.715Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:11

2016-02-05T14:18:11.738Z - info: ack: Apple-IpadAir2-1 setup_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.741Z - info: ack: Apple-Iphone6-1 setup_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.762Z - info: emit: Apple-Iphone6-1 start_test_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.765Z - info: emit: Apple-IpadAir2-1 start_test_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.801Z - info: ack: Apple-IpadAir2-1 start_test_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:11.869Z - info: ack: Apple-Iphone6-1 start_test_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:12.171Z - info: emit: Apple-Iphone6-1 teardown_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:12.174Z - info: emit: Apple-IpadAir2-1 teardown_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:12.311Z - info: ack: Apple-IpadAir2-1 teardown_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:12.393Z - info: ack: Apple-Iphone6-1 teardown_Can call start/stopUpdateAdvertisingAndListening

2016-02-05T14:18:12.417Z - info: Running on ios test: Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:12.418Z - info: emit: Apple-Iphone6-1 setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:12.423Z - info: emit: Apple-IpadAir2-1 setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:12.656Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-02-05T14:18:12.744Z - info: ack: Apple-Iphone6-1 setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.212Z - info: ack: Apple-IpadAir2-1 setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.216Z - info: emit: Apple-Iphone6-1 start_test_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.220Z - info: emit: Apple-IpadAir2-1 start_test_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.241Z - info: ack: Apple-Iphone6-1 start_test_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.315Z - info: ack: Apple-IpadAir2-1 start_test_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.341Z - info: emit: Apple-Iphone6-1 teardown_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.344Z - info: emit: Apple-IpadAir2-1 teardown_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.357Z - info: ack: Apple-Iphone6-1 teardown_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.377Z - info: ack: Apple-IpadAir2-1 teardown_Calling startUpdateAdvertisingAndListening twice is NOT and error

2016-02-05T14:18:13.392Z - info: Running on ios test: peerAvailabilityChange is called

2016-02-05T14:18:13.395Z - info: emit: Apple-Iphone6-1 setup_peerAvailabilityChange is called

2016-02-05T14:18:13.398Z - info: emit: Apple-IpadAir2-1 setup_peerAvailabilityChange is called

2016-02-05T14:18:13.467Z - info: ack: Apple-Iphone6-1 setup_peerAvailabilityChange is called

2016-02-05T14:18:13.674Z - info: ack: Apple-IpadAir2-1 setup_peerAvailabilityChange is called

2016-02-05T14:18:13.678Z - info: emit: Apple-Iphone6-1 start_test_peerAvailabilityChange is called

2016-02-05T14:18:13.683Z - info: emit: Apple-IpadAir2-1 start_test_peerAvailabilityChange is called

2016-02-05T14:18:13.735Z - info: ack: Apple-IpadAir2-1 start_test_peerAvailabilityChange is called

2016-02-05T14:18:13.782Z - info: ack: Apple-Iphone6-1 start_test_peerAvailabilityChange is called

2016-02-05T14:18:15.481Z - info: emit: Apple-Iphone6-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:15.487Z - info: emit: Apple-IpadAir2-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:16.372Z - info: ack: Apple-IpadAir2-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:16.484Z - info: emit: Apple-Iphone6-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:17.487Z - info: emit: Apple-Iphone6-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:18.496Z - info: emit: Apple-Iphone6-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:18.546Z - info: ack: Apple-Iphone6-1 teardown_peerAvailabilityChange is called

2016-02-05T14:18:18.562Z - info: Running on ios test: Can connect to a remote peer

2016-02-05T14:18:18.572Z - info: emit: Apple-Iphone6-1 setup_Can connect to a remote peer

2016-02-05T14:18:18.578Z - info: emit: Apple-IpadAir2-1 setup_Can connect to a remote peer

2016-02-05T14:18:18.670Z - info: ack: Apple-IpadAir2-1 setup_Can connect to a remote peer

2016-02-05T14:18:18.911Z - info: ack: Apple-Iphone6-1 setup_Can connect to a remote peer

2016-02-05T14:18:18.916Z - info: emit: Apple-Iphone6-1 start_test_Can connect to a remote peer

2016-02-05T14:18:18.919Z - info: emit: Apple-IpadAir2-1 start_test_Can connect to a remote peer

2016-02-05T14:18:18.964Z - info: ack: Apple-Iphone6-1 start_test_Can connect to a remote peer

2016-02-05T14:18:18.997Z - info: ack: Apple-IpadAir2-1 start_test_Can connect to a remote peer

2016-02-05T14:18:24.350Z - info: emit: Apple-Iphone6-1 teardown_Can connect to a remote peer

2016-02-05T14:18:24.356Z - info: emit: Apple-IpadAir2-1 teardown_Can connect to a remote peer

2016-02-05T14:18:25.357Z - info: emit: Apple-Iphone6-1 teardown_Can connect to a remote peer

2016-02-05T14:18:25.366Z - info: emit: Apple-IpadAir2-1 teardown_Can connect to a remote peer

2016-02-05T14:18:25.750Z - info: ack: Apple-IpadAir2-1 teardown_Can connect to a remote peer

2016-02-05T14:18:26.366Z - info: emit: Apple-Iphone6-1 teardown_Can connect to a remote peer

2016-02-05T14:18:26.429Z - info: ack: Apple-Iphone6-1 teardown_Can connect to a remote peer

2016-02-05T14:18:26.441Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:26.446Z - info: emit: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:26.449Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:26.809Z - info: ack: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.001Z - info: ack: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.014Z - info: emit: Apple-Iphone6-1 start_test_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.017Z - info: emit: Apple-IpadAir2-1 start_test_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.031Z - info: ack: Apple-Iphone6-1 start_test_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.493Z - info: ack: Apple-IpadAir2-1 start_test_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.498Z - info: emit: Apple-Iphone6-1 teardown_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.501Z - info: emit: Apple-IpadAir2-1 teardown_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.854Z - info: ack: Apple-Iphone6-1 teardown_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.905Z - info: ack: Apple-IpadAir2-1 teardown_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-05T14:18:27.943Z - info: Running on ios test: #startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:27.947Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:27.953Z - info: emit: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.082Z - info: ack: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.347Z - info: ack: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.353Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.355Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.377Z - info: ack: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.627Z - info: ack: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.873Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.880Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.948Z - info: ack: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.978Z - info: ack: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should use different USN after every invocation

2016-02-05T14:18:28.993Z - info: Running on ios test: messages with invalid location or USN should be ignored

2016-02-05T14:18:28.997Z - info: emit: Apple-Iphone6-1 setup_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.001Z - info: emit: Apple-IpadAir2-1 setup_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.037Z - info: ack: Apple-Iphone6-1 setup_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.132Z - info: ack: Apple-IpadAir2-1 setup_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.157Z - info: emit: Apple-Iphone6-1 start_test_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.161Z - info: emit: Apple-IpadAir2-1 start_test_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.177Z - info: ack: Apple-Iphone6-1 start_test_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.496Z - info: ack: Apple-IpadAir2-1 start_test_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.530Z - info: emit: Apple-Iphone6-1 teardown_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.534Z - info: emit: Apple-IpadAir2-1 teardown_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.551Z - info: ack: Apple-Iphone6-1 teardown_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.571Z - info: ack: Apple-IpadAir2-1 teardown_messages with invalid location or USN should be ignored

2016-02-05T14:18:29.605Z - info: Running on ios test: verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.610Z - info: emit: Apple-Iphone6-1 setup_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.613Z - info: emit: Apple-IpadAir2-1 setup_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.631Z - info: ack: Apple-Iphone6-1 setup_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.954Z - info: ack: Apple-IpadAir2-1 setup_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.960Z - info: emit: Apple-Iphone6-1 start_test_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.964Z - info: emit: Apple-IpadAir2-1 start_test_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:29.992Z - info: ack: Apple-Iphone6-1 start_test_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.522Z - info: ack: Apple-IpadAir2-1 start_test_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.542Z - info: emit: Apple-Iphone6-1 teardown_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.546Z - info: emit: Apple-IpadAir2-1 teardown_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.602Z - info: ack: Apple-Iphone6-1 teardown_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.748Z - info: ack: Apple-IpadAir2-1 teardown_verify that Thali-specific messages are filtered correctly

2016-02-05T14:18:30.983Z - info: Running on ios test: #start should fail if called twice in a row

2016-02-05T14:18:30.986Z - info: emit: Apple-Iphone6-1 setup_#start should fail if called twice in a row

2016-02-05T14:18:30.990Z - info: emit: Apple-IpadAir2-1 setup_#start should fail if called twice in a row

2016-02-05T14:18:31.188Z - info: ack: Apple-Iphone6-1 setup_#start should fail if called twice in a row

2016-02-05T14:18:31.221Z - info: ack: Apple-IpadAir2-1 setup_#start should fail if called twice in a row

2016-02-05T14:18:31.268Z - info: emit: Apple-Iphone6-1 start_test_#start should fail if called twice in a row

2016-02-05T14:18:31.273Z - info: emit: Apple-IpadAir2-1 start_test_#start should fail if called twice in a row

2016-02-05T14:18:31.510Z - info: ack: Apple-Iphone6-1 start_test_#start should fail if called twice in a row

2016-02-05T14:18:31.574Z - info: ack: Apple-IpadAir2-1 start_test_#start should fail if called twice in a row

2016-02-05T14:18:31.597Z - info: emit: Apple-Iphone6-1 teardown_#start should fail if called twice in a row

2016-02-05T14:18:31.601Z - info: emit: Apple-IpadAir2-1 teardown_#start should fail if called twice in a row

2016-02-05T14:18:31.624Z - info: ack: Apple-Iphone6-1 teardown_#start should fail if called twice in a row

2016-02-05T14:18:31.757Z - info: ack: Apple-IpadAir2-1 teardown_#start should fail if called twice in a row

2016-02-05T14:18:31.776Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:31.783Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:31.786Z - info: emit: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:32.028Z - info: ack: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:32.789Z - info: emit: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:33.136Z - info: ack: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:33.147Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:33.151Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:34.151Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:34.157Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:34.219Z - info: ack: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:35.159Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:36.164Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:36.339Z - info: ack: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:36.345Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:36.347Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:37.342Z - info: ack: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:37.347Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:38.351Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:39.361Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:40.371Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:40.622Z - info: ack: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail invalid router has been passed

2016-02-05T14:18:40.641Z - info: Running on ios test: #startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:40.645Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:40.650Z - info: emit: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:41.633Z - info: ack: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:41.650Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:42.659Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:43.679Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:44.688Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:45.698Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:46.300Z - info: ack: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:46.316Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:46.318Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:46.469Z - info: ack: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:47.319Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:48.324Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:49.333Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:50.342Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:51.351Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:51.579Z - info: ack: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:51.624Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:51.628Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:52.629Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:52.635Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:53.637Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:53.643Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:54.051Z - info: ack: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:54.092Z - info: ack: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should fail if router server starting fails

2016-02-05T14:18:54.119Z - info: Running on ios test: #startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:54.121Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:54.125Z - info: emit: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:54.596Z - info: ack: Apple-IpadAir2-1 setup_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:55.123Z - info: emit: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:55.162Z - info: ack: Apple-Iphone6-1 setup_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:55.182Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:55.184Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:56.185Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:56.191Z - info: emit: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:57.078Z - info: ack: Apple-IpadAir2-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:57.191Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.195Z - info: emit: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.241Z - info: ack: Apple-Iphone6-1 start_test_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.353Z - info: emit: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.357Z - info: emit: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.382Z - info: ack: Apple-Iphone6-1 teardown_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.427Z - info: ack: Apple-IpadAir2-1 teardown_#startUpdateAdvertisingAndListening should start hosting given router object

2016-02-05T14:18:58.448Z - info: Running on ios test: #stop can be called multiple times in a row

2016-02-05T14:18:58.451Z - info: emit: Apple-Iphone6-1 setup_#stop can be called multiple times in a row

2016-02-05T14:18:58.453Z - info: emit: Apple-IpadAir2-1 setup_#stop can be called multiple times in a row

2016-02-05T14:18:58.473Z - info: ack: Apple-Iphone6-1 setup_#stop can be called multiple times in a row

2016-02-05T14:18:58.604Z - info: ack: Apple-IpadAir2-1 setup_#stop can be called multiple times in a row

2016-02-05T14:18:58.626Z - info: emit: Apple-Iphone6-1 start_test_#stop can be called multiple times in a row

2016-02-05T14:18:58.631Z - info: emit: Apple-IpadAir2-1 start_test_#stop can be called multiple times in a row

2016-02-05T14:18:58.649Z - info: ack: Apple-Iphone6-1 start_test_#stop can be called multiple times in a row

2016-02-05T14:18:59.117Z - info: ack: Apple-IpadAir2-1 start_test_#stop can be called multiple times in a row

2016-02-05T14:18:59.142Z - info: emit: Apple-Iphone6-1 teardown_#stop can be called multiple times in a row

2016-02-05T14:18:59.146Z - info: emit: Apple-IpadAir2-1 teardown_#stop can be called multiple times in a row

2016-02-05T14:18:59.292Z - info: ack: Apple-IpadAir2-1 teardown_#stop can be called multiple times in a row

2016-02-05T14:19:00.144Z - info: emit: Apple-Iphone6-1 teardown_#stop can be called multiple times in a row

2016-02-05T14:19:00.951Z - info: ack: Apple-Iphone6-1 teardown_#stop can be called multiple times in a row

2016-02-05T14:19:00.967Z - info: Running on ios test: #startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:00.969Z - info: emit: Apple-Iphone6-1 setup_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:00.973Z - info: emit: Apple-IpadAir2-1 setup_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.116Z - info: ack: Apple-IpadAir2-1 setup_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.250Z - info: ack: Apple-Iphone6-1 setup_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.270Z - info: emit: Apple-Iphone6-1 start_test_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.274Z - info: emit: Apple-IpadAir2-1 start_test_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.286Z - info: ack: Apple-Iphone6-1 start_test_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.295Z - info: ack: Apple-IpadAir2-1 start_test_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.321Z - info: emit: Apple-Iphone6-1 teardown_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.325Z - info: emit: Apple-IpadAir2-1 teardown_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.345Z - info: ack: Apple-Iphone6-1 teardown_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.413Z - info: ack: Apple-IpadAir2-1 teardown_#startListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.437Z - info: Running on ios test: #stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.440Z - info: emit: Apple-Iphone6-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.448Z - info: emit: Apple-IpadAir2-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:01.471Z - info: ack: Apple-Iphone6-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:02.452Z - info: emit: Apple-IpadAir2-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:03.461Z - info: emit: Apple-IpadAir2-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.236Z - info: ack: Apple-IpadAir2-1 setup_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.251Z - info: emit: Apple-Iphone6-1 start_test_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.255Z - info: emit: Apple-IpadAir2-1 start_test_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.459Z - info: ack: Apple-IpadAir2-1 start_test_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.548Z - info: ack: Apple-Iphone6-1 start_test_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.555Z - info: emit: Apple-Iphone6-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.559Z - info: emit: Apple-IpadAir2-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:04.578Z - info: ack: Apple-Iphone6-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:05.561Z - info: emit: Apple-IpadAir2-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:06.570Z - info: emit: Apple-IpadAir2-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:07.579Z - info: emit: Apple-IpadAir2-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:07.620Z - info: ack: Apple-IpadAir2-1 teardown_#stopListeningForAdvertisements can be called multiple times in a row

2016-02-05T14:19:07.644Z - info: Running on ios test: #stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.648Z - info: emit: Apple-Iphone6-1 setup_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.650Z - info: emit: Apple-IpadAir2-1 setup_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.728Z - info: ack: Apple-IpadAir2-1 setup_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.880Z - info: ack: Apple-Iphone6-1 setup_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.897Z - info: emit: Apple-Iphone6-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.900Z - info: emit: Apple-IpadAir2-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:07.912Z - info: ack: Apple-Iphone6-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:08.902Z - info: emit: Apple-IpadAir2-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:09.908Z - info: emit: Apple-IpadAir2-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:10.363Z - info: ack: Apple-IpadAir2-1 start_test_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:10.386Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:10.388Z - info: emit: Apple-IpadAir2-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:11.388Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:11.397Z - info: emit: Apple-IpadAir2-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:11.432Z - info: ack: Apple-IpadAir2-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:12.396Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:13.401Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:14.410Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:15.418Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:16.425Z - info: emit: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:16.763Z - info: ack: Apple-Iphone6-1 teardown_#stopAdvertisingAndListening can be called multiple times in a row

2016-02-05T14:19:16.783Z - info: Running on ios test: functions are run from a queue in the right order

2016-02-05T14:19:16.788Z - info: emit: Apple-Iphone6-1 setup_functions are run from a queue in the right order

2016-02-05T14:19:16.791Z - info: emit: Apple-IpadAir2-1 setup_functions are run from a queue in the right order

2016-02-05T14:19:16.914Z - info: ack: Apple-Iphone6-1 setup_functions are run from a queue in the right order

2016-02-05T14:19:17.795Z - info: emit: Apple-IpadAir2-1 setup_functions are run from a queue in the right order

2016-02-05T14:19:17.946Z - info: ack: Apple-IpadAir2-1 setup_functions are run from a queue in the right order

2016-02-05T14:19:17.966Z - info: emit: Apple-Iphone6-1 start_test_functions are run from a queue in the right order

2016-02-05T14:19:17.970Z - info: emit: Apple-IpadAir2-1 start_test_functions are run from a queue in the right order

2016-02-05T14:19:18.008Z - info: ack: Apple-IpadAir2-1 start_test_functions are run from a queue in the right order

2016-02-05T14:19:18.968Z - info: emit: Apple-Iphone6-1 start_test_functions are run from a queue in the right order

2016-02-05T14:19:19.785Z - info: ack: Apple-Iphone6-1 start_test_functions are run from a queue in the right order

2016-02-05T14:19:19.831Z - info: emit: Apple-Iphone6-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:19.834Z - info: emit: Apple-IpadAir2-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:20.671Z - info: ack: Apple-Iphone6-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:20.837Z - info: emit: Apple-IpadAir2-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:21.844Z - info: emit: Apple-IpadAir2-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:22.247Z - info: ack: Apple-IpadAir2-1 teardown_functions are run from a queue in the right order

2016-02-05T14:19:22.269Z - info: Test run on ios complete

2016-02-05T14:19:22.271Z - info: 

-== UNIT TEST RESULTS ==-
2016-02-05T14:19:22.272Z - info: PLATFORM: ios
2016-02-05T14:19:22.273Z - info: RESULT: PASS
2016-02-05T14:19:22.274Z - info: 23 of 23 tests completed
2016-02-05T14:19:22.275Z - info: 23/23 passed (0 failures)
2016-02-05T14:19:22.276Z - info: --- Test Details ---


2016-02-05T14:19:22.279Z - info: multiplex can send data - pass
2016-02-05T14:19:22.281Z - info: enqueue and run in order - pass
2016-02-05T14:19:22.282Z - info: basic - pass
2016-02-05T14:19:22.282Z - info: another - pass
2016-02-05T14:19:22.290Z - info: Can call start/stopListeningForAdvertisements - pass
2016-02-05T14:19:22.291Z - info: Calling startListeningForAdvertisements twice is an error - pass
2016-02-05T14:19:22.291Z - info: Can call start/stopUpdateAdvertisingAndListening - pass
2016-02-05T14:19:22.292Z - info: Calling startUpdateAdvertisingAndListening twice is NOT and error - pass
2016-02-05T14:19:22.292Z - info: peerAvailabilityChange is called - pass
2016-02-05T14:19:22.293Z - info: Can connect to a remote peer - pass
2016-02-05T14:19:22.294Z - info: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted - pass
2016-02-05T14:19:22.294Z - info: #startUpdateAdvertisingAndListening should use different USN after every invocation - pass
2016-02-05T14:19:22.295Z - info: messages with invalid location or USN should be ignored - pass
2016-02-05T14:19:22.295Z - info: verify that Thali-specific messages are filtered correctly - pass
2016-02-05T14:19:22.296Z - info: #start should fail if called twice in a row - pass

2016-02-05T14:19:22.329Z - info: #startUpdateAdvertisingAndListening should fail invalid router has been passed - pass

2016-02-05T14:19:22.331Z - info: #startUpdateAdvertisingAndListening should fail if router server starting fails - pass
2016-02-05T14:19:22.331Z - info: #startUpdateAdvertisingAndListening should start hosting given router object - pass

2016-02-05T14:19:22.333Z - info: #stop can be called multiple times in a row - pass
2016-02-05T14:19:22.333Z - info: #startListeningForAdvertisements can be called multiple times in a row - pass

2016-02-05T14:19:22.334Z - info: #stopListeningForAdvertisements can be called multiple times in a row - pass
2016-02-05T14:19:22.335Z - info: #stopAdvertisingAndListening can be called multiple times in a row - pass

2016-02-05T14:19:22.335Z - info: functions are run from a queue in the right order - pass
2016-02-05T14:19:22.336Z - info: 

-== END ==-

2016-02-05T14:19:24.958Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-05T14:19:26.666Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-02-05T14:25:18.326Z - debug: Socket disconnected: ping timeout 4 (LGE-LG-D855)

2016-02-05T14:34:21.526Z - debug: Socket disconnected: transport close 2 (LGE-LG-H815)

2016-02-05T14:34:24.808Z - debug: Socket disconnected: transport close 7 (motorola-Nexus 6)

2016-02-05T14:34:36.487Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-02-05T14:34:38.353Z - debug: Socket disconnected: transport close 8 (LGE-Nexus 5)

2016-02-05T14:34:40.710Z - debug: Socket disconnected: transport close 0 (samsung-SM-G900F)

2016-02-05T14:35:25.107Z - debug: Socket disconnected: transport close 5 (HTC-HTC One M8s)

2016-02-05T14:38:15.576Z - debug: Socket disconnected: transport close 11 (samsung-SM-N910C)

2016-02-05T14:38:17.826Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/thali09_LGE-Nexus 5.md)




###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5753124374916c2_Merge_back_vNext_thaliMobileNative_for_ios__tobybrad/iOS_Iphone5-1.md)


