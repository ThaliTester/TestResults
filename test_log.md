#### Test 58135655a685cd3 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-04T13:07:56.071Z - info: listening on *:3000

2016-02-04T13:07:57.165Z - debug: Device presented: HTC-HTC One M8s (android) unittest socket:0

2016-02-04T13:07:58.730Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-02-04T13:07:58.979Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:2

2016-02-04T13:07:58.982Z - info: Required number of android devices presented (2)

2016-02-04T13:07:58.987Z - info: Starting unit test run for platform: android

2016-02-04T13:07:59.207Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:3

2016-02-04T13:07:59.208Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T13:07:59.328Z - info: Running on android test: multiplex can send data

2016-02-04T13:07:59.335Z - info: emit: HTC-HTC One M8s setup_multiplex can send data %d

2016-02-04T13:07:59.338Z - info: emit: LGE-LG-D855 setup_multiplex can send data %d

2016-02-04T13:07:59.351Z - info: ack: LGE-LG-D855 setup_multiplex can send data

2016-02-04T13:07:59.356Z - info: ack: HTC-HTC One M8s setup_multiplex can send data

2016-02-04T13:07:59.365Z - info: emit: HTC-HTC One M8s start_test_multiplex can send data %d

2016-02-04T13:07:59.369Z - info: emit: LGE-LG-D855 start_test_multiplex can send data %d

2016-02-04T13:07:59.376Z - info: ack: HTC-HTC One M8s start_test_multiplex can send data

2016-02-04T13:07:59.383Z - info: ack: LGE-LG-D855 start_test_multiplex can send data

2016-02-04T13:07:59.463Z - info: emit: HTC-HTC One M8s teardown_multiplex can send data %d

2016-02-04T13:07:59.466Z - info: emit: LGE-LG-D855 teardown_multiplex can send data %d

2016-02-04T13:07:59.474Z - info: ack: HTC-HTC One M8s teardown_multiplex can send data

2016-02-04T13:07:59.498Z - info: ack: LGE-LG-D855 teardown_multiplex can send data

2016-02-04T13:07:59.505Z - info: Running on android test: enqueue and run in order

2016-02-04T13:07:59.507Z - info: emit: HTC-HTC One M8s setup_enqueue and run in order %d

2016-02-04T13:07:59.511Z - info: emit: LGE-LG-D855 setup_enqueue and run in order %d

2016-02-04T13:07:59.527Z - info: ack: LGE-LG-D855 setup_enqueue and run in order

2016-02-04T13:07:59.530Z - info: ack: HTC-HTC One M8s setup_enqueue and run in order

2016-02-04T13:07:59.544Z - info: emit: HTC-HTC One M8s start_test_enqueue and run in order %d

2016-02-04T13:07:59.547Z - info: emit: LGE-LG-D855 start_test_enqueue and run in order %d

2016-02-04T13:07:59.572Z - info: ack: LGE-LG-D855 start_test_enqueue and run in order

2016-02-04T13:07:59.576Z - info: ack: HTC-HTC One M8s start_test_enqueue and run in order

2016-02-04T13:07:59.863Z - info: emit: HTC-HTC One M8s teardown_enqueue and run in order %d

2016-02-04T13:07:59.869Z - info: emit: LGE-LG-D855 teardown_enqueue and run in order %d

2016-02-04T13:07:59.877Z - info: ack: HTC-HTC One M8s teardown_enqueue and run in order

2016-02-04T13:07:59.895Z - info: ack: LGE-LG-D855 teardown_enqueue and run in order

2016-02-04T13:07:59.905Z - info: Running on android test: basic

2016-02-04T13:07:59.907Z - info: emit: HTC-HTC One M8s setup_basic %d

2016-02-04T13:07:59.910Z - info: emit: LGE-LG-D855 setup_basic %d

2016-02-04T13:07:59.921Z - info: ack: LGE-LG-D855 setup_basic

2016-02-04T13:07:59.924Z - info: ack: HTC-HTC One M8s setup_basic

2016-02-04T13:07:59.938Z - info: emit: HTC-HTC One M8s start_test_basic %d

2016-02-04T13:07:59.942Z - info: emit: LGE-LG-D855 start_test_basic %d

2016-02-04T13:07:59.959Z - info: ack: LGE-LG-D855 start_test_basic

2016-02-04T13:07:59.964Z - info: ack: HTC-HTC One M8s start_test_basic

2016-02-04T13:08:00.002Z - info: emit: HTC-HTC One M8s teardown_basic %d

2016-02-04T13:08:00.005Z - info: emit: LGE-LG-D855 teardown_basic %d

2016-02-04T13:08:00.021Z - info: ack: HTC-HTC One M8s teardown_basic

2016-02-04T13:08:00.037Z - info: ack: LGE-LG-D855 teardown_basic

2016-02-04T13:08:00.043Z - info: Running on android test: another

2016-02-04T13:08:00.046Z - info: emit: HTC-HTC One M8s setup_another %d

2016-02-04T13:08:00.049Z - info: emit: LGE-LG-D855 setup_another %d

2016-02-04T13:08:00.060Z - info: ack: LGE-LG-D855 setup_another

2016-02-04T13:08:00.063Z - info: ack: HTC-HTC One M8s setup_another

2016-02-04T13:08:00.076Z - info: emit: HTC-HTC One M8s start_test_another %d

2016-02-04T13:08:00.078Z - info: emit: LGE-LG-D855 start_test_another %d

2016-02-04T13:08:00.087Z - info: ack: HTC-HTC One M8s start_test_another

2016-02-04T13:08:00.090Z - info: ack: LGE-LG-D855 start_test_another

2016-02-04T13:08:00.107Z - info: emit: HTC-HTC One M8s teardown_another %d

2016-02-04T13:08:00.110Z - info: emit: LGE-LG-D855 teardown_another %d

2016-02-04T13:08:00.119Z - info: ack: LGE-LG-D855 teardown_another

2016-02-04T13:08:00.122Z - info: ack: HTC-HTC One M8s teardown_another

2016-02-04T13:08:00.131Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.132Z - info: emit: HTC-HTC One M8s setup_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.136Z - info: emit: LGE-LG-D855 setup_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.159Z - info: ack: LGE-LG-D855 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.162Z - info: ack: HTC-HTC One M8s setup_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.189Z - info: emit: HTC-HTC One M8s start_test_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.191Z - info: emit: LGE-LG-D855 start_test_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.203Z - info: ack: LGE-LG-D855 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.207Z - info: ack: HTC-HTC One M8s start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.251Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:4

2016-02-04T13:08:00.254Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-04T13:08:00.330Z - debug: Socket disconnected: transport close 3 (samsung-SM-G900F)

2016-02-04T13:08:00.353Z - info: emit: HTC-HTC One M8s teardown_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.370Z - info: emit: LGE-LG-D855 teardown_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:00.375Z - info: ack: HTC-HTC One M8s teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.387Z - info: ack: LGE-LG-D855 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:00.435Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.437Z - info: emit: HTC-HTC One M8s setup_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.440Z - info: emit: LGE-LG-D855 setup_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.455Z - info: ack: LGE-LG-D855 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.459Z - info: ack: HTC-HTC One M8s setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.472Z - info: emit: HTC-HTC One M8s start_test_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.475Z - info: emit: LGE-LG-D855 start_test_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.486Z - info: ack: HTC-HTC One M8s start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.489Z - info: ack: LGE-LG-D855 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.659Z - info: emit: HTC-HTC One M8s teardown_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.662Z - info: emit: LGE-LG-D855 teardown_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:00.677Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:5

2016-02-04T13:08:00.678Z - info: Required number of ios devices presented (2)

2016-02-04T13:08:00.680Z - info: Starting unit test run for platform: ios

2016-02-04T13:08:00.693Z - info: ack: LGE-LG-D855 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.699Z - info: ack: HTC-HTC One M8s teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:00.709Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.725Z - info: emit: HTC-HTC One M8s setup_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.737Z - info: emit: LGE-LG-D855 setup_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.743Z - info: ack: HTC-HTC One M8s setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.767Z - info: ack: LGE-LG-D855 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.787Z - info: emit: HTC-HTC One M8s start_test_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.790Z - info: emit: LGE-LG-D855 start_test_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.818Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:6

2016-02-04T13:08:00.819Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-04T13:08:00.828Z - info: ack: HTC-HTC One M8s start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.834Z - info: ack: LGE-LG-D855 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.852Z - info: emit: HTC-HTC One M8s teardown_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.856Z - info: emit: LGE-LG-D855 teardown_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:00.875Z - info: ack: HTC-HTC One M8s teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.878Z - info: ack: LGE-LG-D855 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:00.883Z - info: Running on android test: failed to get mobile documents path

2016-02-04T13:08:00.886Z - info: emit: HTC-HTC One M8s setup_failed to get mobile documents path %d

2016-02-04T13:08:00.889Z - info: emit: LGE-LG-D855 setup_failed to get mobile documents path %d

2016-02-04T13:08:00.913Z - info: ack: HTC-HTC One M8s setup_failed to get mobile documents path

2016-02-04T13:08:00.916Z - info: ack: LGE-LG-D855 setup_failed to get mobile documents path

2016-02-04T13:08:00.925Z - info: emit: HTC-HTC One M8s start_test_failed to get mobile documents path %d

2016-02-04T13:08:00.928Z - info: emit: LGE-LG-D855 start_test_failed to get mobile documents path %d

2016-02-04T13:08:00.943Z - debug: Socket disconnected: transport close 4 (motorola-Nexus 6)

2016-02-04T13:08:00.950Z - info: ack: HTC-HTC One M8s start_test_failed to get mobile documents path

2016-02-04T13:08:00.958Z - info: ack: LGE-LG-D855 start_test_failed to get mobile documents path

2016-02-04T13:08:00.973Z - info: emit: HTC-HTC One M8s teardown_failed to get mobile documents path %d
2016-02-04T13:08:00.976Z - info: emit: LGE-LG-D855 teardown_failed to get mobile documents path %d

2016-02-04T13:08:00.988Z - info: ack: LGE-LG-D855 teardown_failed to get mobile documents path

2016-02-04T13:08:00.991Z - info: ack: HTC-HTC One M8s teardown_failed to get mobile documents path

2016-02-04T13:08:01.005Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.008Z - info: emit: HTC-HTC One M8s setup_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.012Z - info: emit: LGE-LG-D855 setup_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.022Z - info: ack: LGE-LG-D855 setup_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.037Z - info: ack: HTC-HTC One M8s setup_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.051Z - info: emit: HTC-HTC One M8s start_test_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.053Z - info: emit: LGE-LG-D855 start_test_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.062Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:7

2016-02-04T13:08:01.063Z - info: Discarding surplus device: LGE-LG-D722

2016-02-04T13:08:01.068Z - info: ack: HTC-HTC One M8s start_test_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.074Z - info: ack: LGE-LG-D855 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.114Z - info: emit: HTC-HTC One M8s teardown_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.117Z - info: emit: LGE-LG-D855 teardown_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:01.130Z - info: ack: HTC-HTC One M8s teardown_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.133Z - info: ack: LGE-LG-D855 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:01.139Z - info: Running on android test: #init should register the networkChanged event

2016-02-04T13:08:01.142Z - info: emit: HTC-HTC One M8s setup_#init should register the networkChanged event %d

2016-02-04T13:08:01.144Z - info: emit: LGE-LG-D855 setup_#init should register the networkChanged event %d

2016-02-04T13:08:01.157Z - info: ack: HTC-HTC One M8s setup_#init should register the networkChanged event

2016-02-04T13:08:01.160Z - info: ack: LGE-LG-D855 setup_#init should register the networkChanged event

2016-02-04T13:08:01.167Z - info: emit: HTC-HTC One M8s start_test_#init should register the networkChanged event %d

2016-02-04T13:08:01.171Z - info: emit: LGE-LG-D855 start_test_#init should register the networkChanged event %d

2016-02-04T13:08:01.177Z - info: ack: HTC-HTC One M8s start_test_#init should register the networkChanged event

2016-02-04T13:08:01.181Z - info: ack: LGE-LG-D855 start_test_#init should register the networkChanged event

2016-02-04T13:08:01.196Z - info: emit: HTC-HTC One M8s teardown_#init should register the networkChanged event %d

2016-02-04T13:08:01.199Z - info: emit: LGE-LG-D855 teardown_#init should register the networkChanged event %d

2016-02-04T13:08:01.207Z - info: ack: HTC-HTC One M8s teardown_#init should register the networkChanged event

2016-02-04T13:08:01.218Z - info: ack: LGE-LG-D855 teardown_#init should register the networkChanged event

2016-02-04T13:08:01.239Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-04T13:08:01.242Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.244Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.259Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-02-04T13:08:01.260Z - info: Discarding surplus device: LGE-LG-H815

2016-02-04T13:08:01.268Z - debug: Socket disconnected: transport close 6 (LGE-Nexus 5)

2016-02-04T13:08:01.275Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.279Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.284Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.287Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.297Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.300Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.325Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.328Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:01.343Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.350Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on null device name

2016-02-04T13:08:01.363Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.365Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.369Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.381Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.386Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.397Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.400Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.411Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.414Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.439Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.441Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:01.452Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.454Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:01.471Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-04T13:08:01.472Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on non-number port %d
2016-02-04T13:08:01.475Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:01.497Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.507Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.511Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:01.515Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:01.523Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.526Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.547Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:01.550Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:01.560Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.563Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on non-number port

2016-02-04T13:08:01.575Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-04T13:08:01.579Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.582Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.591Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.594Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.607Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.610Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.624Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.632Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.644Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.647Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:01.656Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.659Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on NaN port

2016-02-04T13:08:01.674Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-04T13:08:01.676Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.680Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.701Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.703Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.712Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.716Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.728Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.738Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.752Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.757Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:01.763Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.769Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on negative port

2016-02-04T13:08:01.782Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-04T13:08:01.783Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.788Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.798Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.801Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.826Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.829Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.841Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.854Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.861Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.865Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:01.891Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.897Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on too large port

2016-02-04T13:08:01.910Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:01.913Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:01.916Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:01.927Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:01.930Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:01.943Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:01.946Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:01.962Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:01.970Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:01.983Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:01.987Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:02.002Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:02.010Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:02.024Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.028Z - info: emit: HTC-HTC One M8s setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.032Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.041Z - info: ack: HTC-HTC One M8s setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.048Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.073Z - info: emit: HTC-HTC One M8s start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.083Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.091Z - info: ack: HTC-HTC One M8s start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.096Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.120Z - info: emit: HTC-HTC One M8s teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.122Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:02.132Z - info: ack: HTC-HTC One M8s teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.135Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:02.145Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.148Z - info: emit: HTC-HTC One M8s setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.153Z - info: emit: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.162Z - info: ack: HTC-HTC One M8s setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.169Z - info: ack: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.186Z - debug: Socket disconnected: transport close 7 (LGE-LG-D722)

2016-02-04T13:08:02.196Z - info: emit: HTC-HTC One M8s start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.199Z - info: emit: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.209Z - info: ack: HTC-HTC One M8s start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.217Z - info: Running on ios test: multiplex can send data

2016-02-04T13:08:02.221Z - info: ack: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.223Z - info: emit: Apple-Iphone6-1 setup_multiplex can send data %d

2016-02-04T13:08:02.226Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data %d

2016-02-04T13:08:02.240Z - info: ack: Apple-Iphone6-1 setup_multiplex can send data

2016-02-04T13:08:02.242Z - info: emit: HTC-HTC One M8s teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.244Z - info: emit: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:02.255Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-02-04T13:08:02.270Z - info: ack: HTC-HTC One M8s teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.276Z - info: ack: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:02.278Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.281Z - info: emit: HTC-HTC One M8s setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.283Z - info: emit: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.297Z - info: ack: HTC-HTC One M8s setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.300Z - info: ack: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.312Z - info: emit: HTC-HTC One M8s start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.315Z - info: emit: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.325Z - info: ack: HTC-HTC One M8s start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.328Z - info: ack: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.348Z - info: emit: HTC-HTC One M8s teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.352Z - info: emit: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:02.359Z - info: ack: HTC-HTC One M8s teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.364Z - info: ack: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:02.377Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.382Z - info: emit: HTC-HTC One M8s setup_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.386Z - info: emit: LGE-LG-D855 setup_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.396Z - info: ack: HTC-HTC One M8s setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.399Z - info: ack: LGE-LG-D855 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.412Z - info: emit: HTC-HTC One M8s start_test_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.415Z - info: emit: LGE-LG-D855 start_test_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.424Z - info: ack: HTC-HTC One M8s start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.427Z - info: ack: LGE-LG-D855 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.443Z - info: emit: HTC-HTC One M8s teardown_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.447Z - info: emit: LGE-LG-D855 teardown_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:02.457Z - info: ack: HTC-HTC One M8s teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.460Z - info: ack: LGE-LG-D855 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:02.474Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.476Z - info: emit: HTC-HTC One M8s setup_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.480Z - info: emit: LGE-LG-D855 setup_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.489Z - info: ack: HTC-HTC One M8s setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.522Z - info: ack: LGE-LG-D855 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.527Z - info: emit: HTC-HTC One M8s start_test_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.530Z - info: emit: LGE-LG-D855 start_test_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.539Z - info: ack: HTC-HTC One M8s start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.543Z - info: ack: LGE-LG-D855 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.571Z - info: emit: HTC-HTC One M8s teardown_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.573Z - info: emit: LGE-LG-D855 teardown_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:02.591Z - info: ack: LGE-LG-D855 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.594Z - info: ack: HTC-HTC One M8s teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:02.602Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.604Z - info: emit: HTC-HTC One M8s setup_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.611Z - info: emit: LGE-LG-D855 setup_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.617Z - info: ack: HTC-HTC One M8s setup_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.621Z - info: ack: LGE-LG-D855 setup_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.640Z - info: emit: HTC-HTC One M8s start_test_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.643Z - info: emit: LGE-LG-D855 start_test_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.653Z - info: ack: HTC-HTC One M8s start_test_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.658Z - info: ack: LGE-LG-D855 start_test_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.678Z - info: emit: HTC-HTC One M8s teardown_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.681Z - info: emit: LGE-LG-D855 teardown_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:02.689Z - info: ack: HTC-HTC One M8s teardown_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.692Z - info: ack: LGE-LG-D855 teardown_should call Mobile("Disconnect") without an error

2016-02-04T13:08:02.712Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.715Z - info: emit: HTC-HTC One M8s setup_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.718Z - info: emit: LGE-LG-D855 setup_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.728Z - info: ack: HTC-HTC One M8s setup_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.732Z - info: ack: LGE-LG-D855 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.754Z - info: emit: HTC-HTC One M8s start_test_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.757Z - info: emit: LGE-LG-D855 start_test_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.765Z - info: ack: HTC-HTC One M8s start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.773Z - info: ack: LGE-LG-D855 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.786Z - info: emit: HTC-HTC One M8s teardown_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.791Z - info: emit: LGE-LG-D855 teardown_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:02.799Z - info: ack: LGE-LG-D855 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.802Z - info: ack: HTC-HTC One M8s teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:02.812Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:02.814Z - info: emit: HTC-HTC One M8s setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:02.818Z - info: emit: LGE-LG-D855 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:02.828Z - info: ack: HTC-HTC One M8s setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:02.831Z - info: ack: LGE-LG-D855 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:02.844Z - info: emit: HTC-HTC One M8s start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:02.846Z - info: emit: LGE-LG-D855 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:02.856Z - info: ack: HTC-HTC One M8s start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:02.858Z - info: ack: LGE-LG-D855 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:03.115Z - info: ack: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T13:08:03.135Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data %d

2016-02-04T13:08:03.137Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data %d

2016-02-04T13:08:03.151Z - info: ack: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T13:08:03.938Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:9

2016-02-04T13:08:03.940Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-04T13:08:04.137Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data %d

2016-02-04T13:08:05.085Z - info: ack: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-04T13:08:05.115Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:10

2016-02-04T13:08:05.116Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T13:08:05.169Z - info: emit: Apple-Iphone6-1 teardown_multiplex can send data %d

2016-02-04T13:08:05.172Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data %d

2016-02-04T13:08:05.196Z - info: ack: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-04T13:08:05.724Z - debug: Socket disconnected: transport close 10 (samsung-SM-G900F)

2016-02-04T13:08:06.174Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data %d

2016-02-04T13:08:06.330Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:11

2016-02-04T13:08:06.333Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-04T13:08:06.517Z - info: ack: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-04T13:08:06.528Z - info: Running on ios test: enqueue and run in order

2016-02-04T13:08:06.531Z - info: emit: Apple-Iphone6-1 setup_enqueue and run in order %d

2016-02-04T13:08:06.535Z - info: emit: Apple-IpadAir2-1 setup_enqueue and run in order %d

2016-02-04T13:08:06.548Z - info: ack: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-04T13:08:06.798Z - debug: Socket disconnected: transport close 11 (samsung-SM-N910C)

2016-02-04T13:08:07.534Z - info: emit: Apple-Iphone6-1 setup_enqueue and run in order %d

2016-02-04T13:08:08.152Z - info: ack: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-04T13:08:08.177Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order %d

2016-02-04T13:08:08.181Z - info: emit: Apple-IpadAir2-1 start_test_enqueue and run in order %d

2016-02-04T13:08:08.211Z - info: ack: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-04T13:08:08.270Z - info: ack: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-04T13:08:08.602Z - info: emit: Apple-Iphone6-1 teardown_enqueue and run in order %d

2016-02-04T13:08:08.606Z - info: emit: Apple-IpadAir2-1 teardown_enqueue and run in order %d

2016-02-04T13:08:08.624Z - info: ack: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-04T13:08:08.633Z - debug: Socket disconnected: transport close 9 (Apple-Iphone5-1)

2016-02-04T13:08:08.693Z - info: ack: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-04T13:08:08.710Z - info: Running on ios test: basic

2016-02-04T13:08:08.712Z - info: emit: Apple-Iphone6-1 setup_basic %d

2016-02-04T13:08:08.717Z - info: emit: Apple-IpadAir2-1 setup_basic %d

2016-02-04T13:08:08.730Z - info: ack: Apple-Iphone6-1 setup_basic

2016-02-04T13:08:08.786Z - info: ack: Apple-IpadAir2-1 setup_basic

2016-02-04T13:08:08.850Z - info: emit: Apple-Iphone6-1 start_test_basic %d

2016-02-04T13:08:08.854Z - info: emit: Apple-IpadAir2-1 start_test_basic %d

2016-02-04T13:08:08.866Z - info: ack: Apple-Iphone6-1 start_test_basic

2016-02-04T13:08:08.960Z - info: ack: Apple-IpadAir2-1 start_test_basic

2016-02-04T13:08:08.981Z - info: emit: Apple-Iphone6-1 teardown_basic %d

2016-02-04T13:08:09.019Z - info: emit: Apple-IpadAir2-1 teardown_basic %d

2016-02-04T13:08:09.029Z - info: ack: Apple-Iphone6-1 teardown_basic

2016-02-04T13:08:09.121Z - info: ack: Apple-IpadAir2-1 teardown_basic

2016-02-04T13:08:09.138Z - info: Running on ios test: another

2016-02-04T13:08:09.140Z - info: emit: Apple-Iphone6-1 setup_another %d

2016-02-04T13:08:09.144Z - info: emit: Apple-IpadAir2-1 setup_another %d

2016-02-04T13:08:09.168Z - info: ack: Apple-IpadAir2-1 setup_another

2016-02-04T13:08:09.199Z - info: ack: Apple-Iphone6-1 setup_another

2016-02-04T13:08:09.289Z - info: emit: Apple-Iphone6-1 start_test_another %d

2016-02-04T13:08:09.292Z - info: emit: Apple-IpadAir2-1 start_test_another %d

2016-02-04T13:08:09.310Z - info: ack: Apple-Iphone6-1 start_test_another

2016-02-04T13:08:09.314Z - info: ack: Apple-IpadAir2-1 start_test_another

2016-02-04T13:08:09.335Z - info: emit: Apple-Iphone6-1 teardown_another %d

2016-02-04T13:08:09.338Z - info: emit: Apple-IpadAir2-1 teardown_another %d

2016-02-04T13:08:09.474Z - info: ack: Apple-Iphone6-1 teardown_another

2016-02-04T13:08:09.477Z - info: ack: Apple-IpadAir2-1 teardown_another

2016-02-04T13:08:09.493Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:09.495Z - info: emit: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:09.499Z - info: emit: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:09.508Z - info: ack: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:09.646Z - info: ack: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:09.671Z - info: emit: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:09.673Z - info: emit: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:09.813Z - info: ack: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:09.817Z - info: ack: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:10.017Z - info: emit: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:10.019Z - info: emit: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value %d

2016-02-04T13:08:10.153Z - info: ack: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:10.156Z - info: ack: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T13:08:10.180Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.184Z - info: emit: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.188Z - info: emit: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.327Z - info: ack: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.332Z - info: ack: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.349Z - info: emit: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.353Z - info: emit: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.364Z - info: ack: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.488Z - info: ack: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.649Z - info: emit: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.653Z - info: emit: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value %d

2016-02-04T13:08:10.668Z - info: ack: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.670Z - info: ack: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T13:08:10.689Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:10.691Z - info: emit: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:10.695Z - info: emit: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:10.825Z - info: ack: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:10.828Z - info: ack: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:10.841Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:10.844Z - info: emit: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:10.856Z - info: ack: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:10.866Z - info: ack: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:11.001Z - info: emit: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:11.004Z - info: emit: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file %d

2016-02-04T13:08:11.017Z - info: ack: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:11.023Z - info: ack: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T13:08:11.047Z - info: Running on ios test: failed to get mobile documents path

2016-02-04T13:08:11.050Z - info: emit: Apple-Iphone6-1 setup_failed to get mobile documents path %d

2016-02-04T13:08:11.053Z - info: emit: Apple-IpadAir2-1 setup_failed to get mobile documents path %d

2016-02-04T13:08:11.076Z - info: ack: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-04T13:08:11.169Z - info: ack: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-04T13:08:11.191Z - info: emit: Apple-Iphone6-1 start_test_failed to get mobile documents path %d

2016-02-04T13:08:11.193Z - info: emit: Apple-IpadAir2-1 start_test_failed to get mobile documents path %d

2016-02-04T13:08:11.206Z - info: ack: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-04T13:08:11.213Z - info: ack: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-04T13:08:11.328Z - info: emit: Apple-Iphone6-1 teardown_failed to get mobile documents path %d

2016-02-04T13:08:11.331Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path %d

2016-02-04T13:08:11.346Z - info: ack: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-04T13:08:11.356Z - info: ack: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T13:08:11.377Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.380Z - info: emit: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.383Z - info: emit: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.406Z - info: ack: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.512Z - info: ack: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.531Z - info: emit: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.534Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.547Z - info: ack: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.557Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.668Z - info: emit: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.672Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event %d

2016-02-04T13:08:11.687Z - info: ack: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.690Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T13:08:11.707Z - info: Running on ios test: #init should register the networkChanged event

2016-02-04T13:08:11.710Z - info: emit: Apple-Iphone6-1 setup_#init should register the networkChanged event %d

2016-02-04T13:08:11.713Z - info: emit: Apple-IpadAir2-1 setup_#init should register the networkChanged event %d

2016-02-04T13:08:11.723Z - info: ack: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-04T13:08:11.844Z - info: ack: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-04T13:08:11.864Z - info: emit: Apple-Iphone6-1 start_test_#init should register the networkChanged event %d

2016-02-04T13:08:11.867Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the networkChanged event %d

2016-02-04T13:08:11.880Z - info: ack: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-04T13:08:11.885Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-04T13:08:12.009Z - info: emit: Apple-Iphone6-1 teardown_#init should register the networkChanged event %d

2016-02-04T13:08:12.012Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the networkChanged event %d

2016-02-04T13:08:12.033Z - info: ack: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-04T13:08:12.037Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-04T13:08:12.053Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-04T13:08:12.055Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.057Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.071Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-04T13:08:12.207Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-04T13:08:12.226Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.228Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.247Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T13:08:12.356Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T13:08:12.380Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.493Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:12.513Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T13:08:13.496Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:14.501Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:15.510Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:16.519Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name %d

2016-02-04T13:08:16.635Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T13:08:16.659Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-04T13:08:16.661Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:16.666Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:16.677Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:17.664Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:18.669Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:19.678Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:20.687Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:20.996Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:21.020Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:21.024Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:21.036Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:22.028Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:23.034Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:23.102Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:23.116Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:23.120Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name %d

2016-02-04T13:08:23.133Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:23.643Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T13:08:23.663Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-04T13:08:23.667Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:23.671Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:23.694Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T13:08:24.678Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:25.560Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T13:08:25.582Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:25.586Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:25.600Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T13:08:26.586Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:26.864Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T13:08:26.908Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:26.912Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:26.932Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T13:08:27.927Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port %d

2016-02-04T13:08:28.087Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T13:08:28.107Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-04T13:08:28.110Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:28.116Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:28.145Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T13:08:29.114Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:30.119Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:30.459Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T13:08:30.480Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:30.483Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:30.497Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T13:08:31.484Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:31.982Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T13:08:32.008Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:32.012Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port %d

2016-02-04T13:08:32.024Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T13:08:32.113Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T13:08:32.132Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-04T13:08:32.135Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.140Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.161Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.302Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.321Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.325Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.347Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.450Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.476Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.480Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port %d

2016-02-04T13:08:32.490Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.498Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T13:08:32.607Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-04T13:08:32.610Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.612Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.624Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.629Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.648Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.652Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.673Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.805Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.815Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.818Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port %d

2016-02-04T13:08:32.832Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.837Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T13:08:32.949Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:32.951Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:32.953Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:32.965Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:33.955Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:34.962Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:35.248Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:35.269Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:35.271Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:35.289Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:35.584Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:35.609Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:35.612Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error %d

2016-02-04T13:08:35.624Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:35.627Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T13:08:35.650Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.651Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.654Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.664Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.675Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.693Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.696Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.711Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.714Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.742Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.744Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error %d

2016-02-04T13:08:35.758Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.768Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T13:08:35.785Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.788Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.790Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.804Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.815Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.827Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.829Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.843Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.853Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.877Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.879Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error %d

2016-02-04T13:08:35.894Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.896Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T13:08:35.914Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:35.917Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:35.919Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:35.932Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:35.934Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:35.954Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:35.956Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:35.969Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:35.979Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:36.005Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:36.007Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error %d

2016-02-04T13:08:36.021Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:36.024Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T13:08:36.043Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.046Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.048Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.059Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.063Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.082Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.084Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.098Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.107Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.132Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.134Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error %d

2016-02-04T13:08:36.148Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.152Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T13:08:36.192Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.194Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.196Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.212Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.214Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.233Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.235Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.247Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.250Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.273Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.277Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error %d

2016-02-04T13:08:36.287Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.293Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T13:08:36.310Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.311Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.315Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.332Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.337Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.357Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.359Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.371Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.378Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.402Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.404Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error %d

2016-02-04T13:08:36.417Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.423Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T13:08:36.444Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.445Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.449Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.460Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.468Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.488Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.492Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.504Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.509Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.534Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.539Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error %d

2016-02-04T13:08:36.546Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.550Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T13:08:36.570Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:36.572Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:36.575Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:36.606Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:36.608Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:36.621Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:36.624Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:36.645Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:36.660Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:37.001Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:37.003Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error %d

2016-02-04T13:08:37.035Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:37.038Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T13:08:37.077Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.079Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.082Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.105Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.112Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.131Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.133Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.426Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.443Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.484Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.486Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error %d

2016-02-04T13:08:37.515Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.518Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T13:08:37.542Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:37.545Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:37.547Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:37.580Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:37.592Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:37.604Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:37.607Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:37.618Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:37.635Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:37.989Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:37.991Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer %d

2016-02-04T13:08:38.041Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:38.204Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T13:08:38.474Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:38.477Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:38.479Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:39.042Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:39.078Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:39.099Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:39.102Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:39.197Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:39.608Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:39.646Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:39.649Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer %d

2016-02-04T13:08:39.730Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:40.012Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T13:08:40.033Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-04T13:08:40.034Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:40.039Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:40.102Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:40.275Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:40.509Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:40.511Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:40.550Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:40.672Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:45.425Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:45.429Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers %d

2016-02-04T13:08:45.454Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:45.486Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T13:08:45.491Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:08:45.493Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:45.496Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:45.953Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:08:46.484Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:08:46.487Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:46.490Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:47.490Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:47.495Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:48.495Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:48.502Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:49.502Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:49.519Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:50.520Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:50.527Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:51.527Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:51.533Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:52.534Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:52.540Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:53.542Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:53.546Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:54.554Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:54.557Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:55.565Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:55.571Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:08:57.777Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:08:59.216Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:09:02.825Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:09:02.831Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect %d

2016-02-04T13:09:03.240Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:09:03.275Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T13:09:03.851Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:03.854Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:03.860Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:04.108Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:04.859Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:05.188Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:05.209Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:05.211Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:05.277Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:05.280Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:10.057Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:10.060Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect %d

2016-02-04T13:09:10.087Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:10.090Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T13:09:10.117Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-04T13:09:10.118Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data %d

2016-02-04T13:09:10.121Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data %d

2016-02-04T13:09:10.136Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-04T13:09:10.143Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-04T13:09:10.163Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data %d

2016-02-04T13:09:10.165Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data %d

2016-02-04T13:09:10.399Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-04T13:09:10.578Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-04T13:09:15.347Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data %d

2016-02-04T13:09:15.349Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data %d

2016-02-04T13:09:15.359Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-04T13:09:15.369Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-04T13:09:15.416Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:15.418Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:15.421Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:15.851Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:16.249Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:16.266Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:16.269Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:16.357Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:16.360Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:26.830Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:26.832Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly %d

2016-02-04T13:09:26.860Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:26.862Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T13:09:26.890Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-04T13:09:26.893Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:26.895Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:26.914Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-04T13:09:26.925Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-04T13:09:26.949Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:26.953Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:27.171Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T13:09:27.190Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T13:09:27.372Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:27.374Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error %d

2016-02-04T13:09:27.448Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T13:09:27.464Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T13:09:27.686Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-04T13:09:27.689Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.692Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.707Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-04T13:09:27.716Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-04T13:09:27.738Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.740Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.790Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-04T13:09:27.793Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-04T13:09:27.862Z - debug: Socket disconnected: ping timeout 0 (HTC-HTC One M8s)

2016-02-04T13:09:27.917Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.920Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity %d

2016-02-04T13:09:27.950Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-04T13:09:28.208Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-04T13:09:28.210Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-04T13:09:28.213Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database %d

2016-02-04T13:09:28.216Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database %d

2016-02-04T13:09:28.241Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-04T13:09:28.248Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-04T13:09:28.270Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database %d

2016-02-04T13:09:28.272Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database %d

2016-02-04T13:09:28.298Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-04T13:09:28.301Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-04T13:09:51.985Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database %d

2016-02-04T13:09:51.989Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database %d

2016-02-04T13:09:52.058Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database

2016-02-04T13:09:52.518Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database

2016-02-04T13:09:52.520Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-04T13:09:52.523Z - info: emit: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted %d

2016-02-04T13:09:52.525Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted %d

2016-02-04T13:09:52.568Z - info: ack: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-04T13:09:52.582Z - info: ack: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-04T13:09:54.712Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-02-04T13:12:29.844Z - debug: Socket disconnected: ping timeout 5 (Apple-IpadAir2-1)

2016-02-04T13:14:24.313Z - debug: Socket disconnected: ping timeout 2 (LGE-LG-D855)

2016-02-04T13:21:04.972Z - debug: Socket disconnected: transport close 12 (NOT YET SET)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-04T13:08:55.568Z - error: test server: Device undefined

2016-02-04T13:08:55.573Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on 41006f95c8139173 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655a685cd3_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)




