#### Test 58135655812b57f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-08T16:27:27.827Z - info: listening on *:3000

2016-02-08T16:27:28.215Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:0

2016-02-08T16:27:28.246Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:1

2016-02-08T16:27:28.249Z - info: Required number of android devices presented (2)

2016-02-08T16:27:28.252Z - info: Starting unit test run for platform: android

2016-02-08T16:27:28.616Z - info: Running on android test: multiplex can send data

2016-02-08T16:27:28.623Z - info: emit: samsung-SM-G900F setup_multiplex can send data

2016-02-08T16:27:28.626Z - info: emit: LGE-LG-D855 setup_multiplex can send data

2016-02-08T16:27:28.637Z - info: ack: samsung-SM-G900F setup_multiplex can send data

2016-02-08T16:27:28.659Z - info: ack: LGE-LG-D855 setup_multiplex can send data

2016-02-08T16:27:28.676Z - info: emit: samsung-SM-G900F start_test_multiplex can send data

2016-02-08T16:27:28.678Z - info: emit: LGE-LG-D855 start_test_multiplex can send data

2016-02-08T16:27:28.688Z - info: ack: samsung-SM-G900F start_test_multiplex can send data

2016-02-08T16:27:28.691Z - info: ack: LGE-LG-D855 start_test_multiplex can send data

2016-02-08T16:27:28.773Z - info: emit: samsung-SM-G900F teardown_multiplex can send data

2016-02-08T16:27:28.777Z - info: emit: LGE-LG-D855 teardown_multiplex can send data

2016-02-08T16:27:28.799Z - info: ack: samsung-SM-G900F teardown_multiplex can send data

2016-02-08T16:27:28.831Z - info: ack: LGE-LG-D855 teardown_multiplex can send data

2016-02-08T16:27:28.852Z - info: Running on android test: enqueue and run in order

2016-02-08T16:27:28.855Z - info: emit: samsung-SM-G900F setup_enqueue and run in order

2016-02-08T16:27:28.857Z - info: emit: LGE-LG-D855 setup_enqueue and run in order

2016-02-08T16:27:28.872Z - info: ack: LGE-LG-D855 setup_enqueue and run in order

2016-02-08T16:27:28.877Z - info: ack: samsung-SM-G900F setup_enqueue and run in order

2016-02-08T16:27:28.891Z - info: emit: samsung-SM-G900F start_test_enqueue and run in order

2016-02-08T16:27:28.895Z - info: emit: LGE-LG-D855 start_test_enqueue and run in order

2016-02-08T16:27:28.919Z - info: ack: samsung-SM-G900F start_test_enqueue and run in order

2016-02-08T16:27:28.922Z - info: ack: LGE-LG-D855 start_test_enqueue and run in order

2016-02-08T16:27:29.213Z - info: emit: samsung-SM-G900F teardown_enqueue and run in order

2016-02-08T16:27:29.216Z - info: emit: LGE-LG-D855 teardown_enqueue and run in order

2016-02-08T16:27:29.231Z - info: ack: LGE-LG-D855 teardown_enqueue and run in order

2016-02-08T16:27:29.243Z - info: ack: samsung-SM-G900F teardown_enqueue and run in order

2016-02-08T16:27:29.286Z - info: Running on android test: basic

2016-02-08T16:27:29.289Z - info: emit: samsung-SM-G900F setup_basic

2016-02-08T16:27:29.292Z - info: emit: LGE-LG-D855 setup_basic

2016-02-08T16:27:29.340Z - info: ack: samsung-SM-G900F setup_basic

2016-02-08T16:27:29.343Z - info: ack: LGE-LG-D855 setup_basic

2016-02-08T16:27:29.359Z - info: emit: samsung-SM-G900F start_test_basic

2016-02-08T16:27:29.362Z - info: emit: LGE-LG-D855 start_test_basic

2016-02-08T16:27:29.379Z - info: ack: LGE-LG-D855 start_test_basic

2016-02-08T16:27:29.389Z - info: ack: samsung-SM-G900F start_test_basic

2016-02-08T16:27:29.430Z - info: emit: samsung-SM-G900F teardown_basic

2016-02-08T16:27:29.432Z - info: emit: LGE-LG-D855 teardown_basic

2016-02-08T16:27:29.437Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:2

2016-02-08T16:27:29.438Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-08T16:27:29.452Z - info: ack: samsung-SM-G900F teardown_basic

2016-02-08T16:27:29.468Z - info: ack: LGE-LG-D855 teardown_basic

2016-02-08T16:27:29.476Z - info: Running on android test: another

2016-02-08T16:27:29.479Z - info: emit: samsung-SM-G900F setup_another

2016-02-08T16:27:29.481Z - info: emit: LGE-LG-D855 setup_another

2016-02-08T16:27:29.496Z - info: ack: samsung-SM-G900F setup_another

2016-02-08T16:27:29.498Z - info: ack: LGE-LG-D855 setup_another

2016-02-08T16:27:29.506Z - info: emit: samsung-SM-G900F start_test_another

2016-02-08T16:27:29.509Z - info: emit: LGE-LG-D855 start_test_another

2016-02-08T16:27:29.519Z - info: ack: LGE-LG-D855 start_test_another

2016-02-08T16:27:29.522Z - info: ack: samsung-SM-G900F start_test_another

2016-02-08T16:27:29.541Z - info: emit: samsung-SM-G900F teardown_another

2016-02-08T16:27:29.544Z - info: emit: LGE-LG-D855 teardown_another

2016-02-08T16:27:29.551Z - info: ack: samsung-SM-G900F teardown_another

2016-02-08T16:27:29.554Z - info: ack: LGE-LG-D855 teardown_another

2016-02-08T16:27:29.569Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.570Z - info: emit: samsung-SM-G900F setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.574Z - info: emit: LGE-LG-D855 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.588Z - info: ack: LGE-LG-D855 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.609Z - info: ack: samsung-SM-G900F setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.619Z - info: emit: samsung-SM-G900F start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.623Z - info: emit: LGE-LG-D855 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.631Z - info: ack: samsung-SM-G900F start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.634Z - info: ack: LGE-LG-D855 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.769Z - info: emit: samsung-SM-G900F teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.772Z - info: emit: LGE-LG-D855 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.778Z - info: ack: samsung-SM-G900F teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.785Z - info: ack: LGE-LG-D855 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:29.840Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.857Z - info: emit: samsung-SM-G900F setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.860Z - info: emit: LGE-LG-D855 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.878Z - info: ack: LGE-LG-D855 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.882Z - info: ack: samsung-SM-G900F setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.895Z - info: emit: samsung-SM-G900F start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.897Z - info: emit: LGE-LG-D855 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.908Z - info: ack: samsung-SM-G900F start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:29.911Z - info: ack: LGE-LG-D855 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:30.045Z - info: emit: samsung-SM-G900F teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:30.048Z - info: emit: LGE-LG-D855 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:30.056Z - info: ack: samsung-SM-G900F teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:30.060Z - info: ack: LGE-LG-D855 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:30.086Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.087Z - info: emit: samsung-SM-G900F setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.090Z - info: emit: LGE-LG-D855 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.111Z - info: ack: samsung-SM-G900F setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.113Z - info: ack: LGE-LG-D855 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.132Z - info: emit: samsung-SM-G900F start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.134Z - info: emit: LGE-LG-D855 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.143Z - info: ack: samsung-SM-G900F start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.146Z - info: ack: LGE-LG-D855 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.171Z - info: emit: samsung-SM-G900F teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.173Z - info: emit: LGE-LG-D855 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.190Z - info: ack: samsung-SM-G900F teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.194Z - info: ack: LGE-LG-D855 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:30.199Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:3

2016-02-08T16:27:30.200Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-08T16:27:30.205Z - info: Running on android test: failed to get mobile documents path

2016-02-08T16:27:30.209Z - info: emit: samsung-SM-G900F setup_failed to get mobile documents path

2016-02-08T16:27:30.211Z - info: emit: LGE-LG-D855 setup_failed to get mobile documents path

2016-02-08T16:27:30.220Z - info: ack: LGE-LG-D855 setup_failed to get mobile documents path

2016-02-08T16:27:30.223Z - info: ack: samsung-SM-G900F setup_failed to get mobile documents path

2016-02-08T16:27:30.234Z - info: emit: samsung-SM-G900F start_test_failed to get mobile documents path

2016-02-08T16:27:30.236Z - info: emit: LGE-LG-D855 start_test_failed to get mobile documents path

2016-02-08T16:27:30.249Z - debug: Socket disconnected: transport close 2 (samsung-SM-N910C)

2016-02-08T16:27:30.267Z - info: ack: LGE-LG-D855 start_test_failed to get mobile documents path

2016-02-08T16:27:30.274Z - info: ack: samsung-SM-G900F start_test_failed to get mobile documents path

2016-02-08T16:27:30.279Z - info: emit: samsung-SM-G900F teardown_failed to get mobile documents path

2016-02-08T16:27:30.281Z - info: emit: LGE-LG-D855 teardown_failed to get mobile documents path

2016-02-08T16:27:30.292Z - info: ack: samsung-SM-G900F teardown_failed to get mobile documents path

2016-02-08T16:27:30.294Z - info: ack: LGE-LG-D855 teardown_failed to get mobile documents path

2016-02-08T16:27:30.308Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.310Z - info: emit: samsung-SM-G900F setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.329Z - info: emit: LGE-LG-D855 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.336Z - info: ack: samsung-SM-G900F setup_#init should register the peerAvailabilityChanged event
2016-02-08T16:27:30.346Z - info: ack: LGE-LG-D855 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.356Z - info: emit: samsung-SM-G900F start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.359Z - info: emit: LGE-LG-D855 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.368Z - info: ack: samsung-SM-G900F start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.371Z - info: ack: LGE-LG-D855 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.417Z - info: emit: samsung-SM-G900F teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.423Z - info: emit: LGE-LG-D855 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.432Z - info: ack: samsung-SM-G900F teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.443Z - info: ack: LGE-LG-D855 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:30.456Z - info: Running on android test: #init should register the networkChanged event

2016-02-08T16:27:30.459Z - info: emit: samsung-SM-G900F setup_#init should register the networkChanged event

2016-02-08T16:27:30.461Z - info: emit: LGE-LG-D855 setup_#init should register the networkChanged event

2016-02-08T16:27:30.466Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:4

2016-02-08T16:27:30.478Z - info: ack: LGE-LG-D855 setup_#init should register the networkChanged event

2016-02-08T16:27:30.484Z - info: ack: samsung-SM-G900F setup_#init should register the networkChanged event

2016-02-08T16:27:30.497Z - info: emit: samsung-SM-G900F start_test_#init should register the networkChanged event

2016-02-08T16:27:30.499Z - info: emit: LGE-LG-D855 start_test_#init should register the networkChanged event

2016-02-08T16:27:30.509Z - info: ack: samsung-SM-G900F start_test_#init should register the networkChanged event

2016-02-08T16:27:30.512Z - info: ack: LGE-LG-D855 start_test_#init should register the networkChanged event

2016-02-08T16:27:30.531Z - info: emit: samsung-SM-G900F teardown_#init should register the networkChanged event

2016-02-08T16:27:30.534Z - info: emit: LGE-LG-D855 teardown_#init should register the networkChanged event

2016-02-08T16:27:30.546Z - info: ack: samsung-SM-G900F teardown_#init should register the networkChanged event

2016-02-08T16:27:30.549Z - info: ack: LGE-LG-D855 teardown_#init should register the networkChanged event

2016-02-08T16:27:30.563Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-08T16:27:30.565Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on null device name
2016-02-08T16:27:30.568Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.584Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.588Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.611Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.613Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.640Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.652Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.657Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.659Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.671Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.677Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:30.689Z - debug: Socket disconnected: transport close 3 (LGE-Nexus 5)

2016-02-08T16:27:30.697Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.700Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.703Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.715Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.718Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.734Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.736Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.758Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.761Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.773Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.776Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.786Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.789Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:30.802Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-08T16:27:30.806Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.808Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.821Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.823Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.836Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.838Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.847Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.850Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.867Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.870Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.882Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.891Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:5
2016-02-08T16:27:30.892Z - info: Discarding surplus device: LGE-LG-D722

2016-02-08T16:27:30.907Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:27:30.912Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-08T16:27:30.915Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.919Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.929Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.931Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.943Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.949Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.955Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.961Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.979Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.983Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.992Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:27:30.995Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:27:31.012Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-08T16:27:31.014Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.018Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.035Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.038Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.052Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.055Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.067Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.087Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.093Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.096Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.107Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.113Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on negative port

2016-02-08T16:27:31.121Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-08T16:27:31.123Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.127Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.136Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.140Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.166Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.169Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.181Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.197Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.203Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.207Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.215Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.224Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:27:31.232Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.237Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.240Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.275Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.279Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.283Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.287Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.296Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.299Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.323Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.326Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.337Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.344Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:27:31.349Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.352Z - info: emit: samsung-SM-G900F setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.355Z - info: emit: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.366Z - info: ack: LGE-LG-D855 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.373Z - info: ack: samsung-SM-G900F setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.380Z - info: emit: samsung-SM-G900F start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.384Z - info: emit: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.394Z - info: ack: LGE-LG-D855 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.421Z - info: ack: samsung-SM-G900F start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.425Z - info: emit: samsung-SM-G900F teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.428Z - info: emit: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.440Z - info: ack: LGE-LG-D855 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.443Z - info: ack: samsung-SM-G900F teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:27:31.455Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.457Z - info: emit: samsung-SM-G900F setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.459Z - info: emit: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.473Z - info: ack: samsung-SM-G900F setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.478Z - info: ack: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.490Z - info: emit: samsung-SM-G900F start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error
2016-02-08T16:27:31.492Z - info: emit: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.504Z - info: ack: samsung-SM-G900F start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.514Z - info: ack: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.552Z - info: emit: samsung-SM-G900F teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.559Z - info: emit: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.569Z - info: ack: samsung-SM-G900F teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.578Z - info: ack: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:27:31.600Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.612Z - info: emit: samsung-SM-G900F setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.615Z - info: emit: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.620Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:6

2016-02-08T16:27:31.621Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T16:27:31.626Z - info: ack: LGE-LG-D855 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.629Z - info: ack: samsung-SM-G900F setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.641Z - info: emit: samsung-SM-G900F start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.648Z - info: emit: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.658Z - info: ack: samsung-SM-G900F start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.661Z - info: ack: LGE-LG-D855 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.681Z - info: emit: samsung-SM-G900F teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.689Z - info: emit: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.702Z - info: ack: samsung-SM-G900F teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.705Z - info: ack: LGE-LG-D855 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:27:31.712Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.715Z - info: emit: samsung-SM-G900F setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.718Z - info: emit: LGE-LG-D855 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.727Z - info: ack: LGE-LG-D855 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.731Z - info: ack: samsung-SM-G900F setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.744Z - info: emit: samsung-SM-G900F start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.749Z - info: emit: LGE-LG-D855 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.759Z - info: ack: samsung-SM-G900F start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.763Z - info: ack: LGE-LG-D855 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.787Z - info: emit: samsung-SM-G900F teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.790Z - info: emit: LGE-LG-D855 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.800Z - info: ack: LGE-LG-D855 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.807Z - info: ack: samsung-SM-G900F teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:27:31.816Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.819Z - info: emit: samsung-SM-G900F setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.822Z - info: emit: LGE-LG-D855 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.831Z - info: ack: LGE-LG-D855 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.838Z - info: ack: samsung-SM-G900F setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.853Z - info: emit: samsung-SM-G900F start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.856Z - info: emit: LGE-LG-D855 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.864Z - info: ack: samsung-SM-G900F start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.874Z - info: ack: LGE-LG-D855 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.891Z - info: emit: samsung-SM-G900F teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.895Z - info: emit: LGE-LG-D855 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.906Z - info: ack: LGE-LG-D855 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.913Z - info: ack: samsung-SM-G900F teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:27:31.918Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.921Z - info: emit: samsung-SM-G900F setup_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.926Z - info: emit: LGE-LG-D855 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.936Z - info: ack: LGE-LG-D855 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.940Z - info: ack: samsung-SM-G900F setup_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.949Z - info: emit: samsung-SM-G900F start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.953Z - info: emit: LGE-LG-D855 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.959Z - info: ack: samsung-SM-G900F start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.962Z - info: ack: LGE-LG-D855 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.969Z - debug: Socket disconnected: transport close 5 (LGE-LG-D722)

2016-02-08T16:27:31.980Z - info: emit: samsung-SM-G900F teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.982Z - info: emit: LGE-LG-D855 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.992Z - info: ack: samsung-SM-G900F teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:27:31.997Z - info: ack: LGE-LG-D855 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:27:32.008Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.011Z - info: emit: samsung-SM-G900F setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.014Z - info: emit: LGE-LG-D855 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.025Z - info: ack: samsung-SM-G900F setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.028Z - info: ack: LGE-LG-D855 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.044Z - info: emit: samsung-SM-G900F start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.046Z - info: emit: LGE-LG-D855 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.064Z - info: ack: samsung-SM-G900F start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.068Z - info: ack: LGE-LG-D855 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.077Z - info: emit: samsung-SM-G900F teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.080Z - info: emit: LGE-LG-D855 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.090Z - info: ack: samsung-SM-G900F teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.094Z - info: ack: LGE-LG-D855 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:27:32.103Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.106Z - info: emit: samsung-SM-G900F setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.109Z - info: emit: LGE-LG-D855 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.121Z - info: ack: samsung-SM-G900F setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.131Z - info: ack: LGE-LG-D855 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.143Z - info: emit: samsung-SM-G900F start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.147Z - info: emit: LGE-LG-D855 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.157Z - info: ack: samsung-SM-G900F start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.163Z - info: ack: LGE-LG-D855 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:27:32.291Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F)

2016-02-08T16:27:32.548Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:7

2016-02-08T16:27:32.549Z - info: Required number of ios devices presented (2)

2016-02-08T16:27:32.551Z - info: Starting unit test run for platform: ios

2016-02-08T16:27:32.670Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:8

2016-02-08T16:27:32.671Z - info: Discarding surplus device: LGE-LG-H815

2016-02-08T16:27:32.907Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:9

2016-02-08T16:27:32.908Z - info: Discarding surplus device: motorola-Nexus 6

2016-02-08T16:27:33.408Z - info: Running on ios test: multiplex can send data

2016-02-08T16:27:33.410Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-08T16:27:33.415Z - info: emit: Apple-Iphone6-1 setup_multiplex can send data

2016-02-08T16:27:33.570Z - info: ack: Apple-Iphone6-1 setup_multiplex can send data

2016-02-08T16:27:33.576Z - debug: Socket disconnected: transport close 9 (motorola-Nexus 6)

2016-02-08T16:27:33.645Z - debug: Socket disconnected: transport close 8 (LGE-LG-H815)

2016-02-08T16:27:34.414Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-08T16:27:35.419Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-08T16:27:35.962Z - info: ack: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-08T16:27:35.987Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-08T16:27:35.991Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:36.000Z - info: ack: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-08T16:27:36.994Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:38.002Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:39.009Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:40.017Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:41.025Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:42.032Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:43.040Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:43.190Z - info: ack: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:27:43.295Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-08T16:27:43.300Z - info: emit: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-08T16:27:43.319Z - info: ack: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-08T16:27:44.300Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-08T16:27:45.305Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-08T16:27:45.371Z - info: ack: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-08T16:27:45.391Z - info: Running on ios test: enqueue and run in order

2016-02-08T16:27:45.394Z - info: emit: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-08T16:27:45.398Z - info: emit: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-08T16:27:45.411Z - info: ack: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-08T16:27:46.303Z - info: ack: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-08T16:27:46.323Z - info: emit: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-08T16:27:46.326Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-08T16:27:46.349Z - info: ack: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-08T16:27:47.328Z - info: emit: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-08T16:27:48.230Z - info: ack: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-08T16:27:48.456Z - info: emit: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-08T16:27:48.459Z - info: emit: Apple-Iphone6-1 teardown_enqueue and run in order
2016-02-08T16:27:48.470Z - info: ack: Apple-Iphone6-1 teardown_enqueue and run in order
2016-02-08T16:27:48.477Z - info: ack: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-08T16:27:48.497Z - info: Running on ios test: basic

2016-02-08T16:27:48.500Z - info: emit: Apple-IpadAir2-1 setup_basic

2016-02-08T16:27:48.503Z - info: emit: Apple-Iphone6-1 setup_basic

2016-02-08T16:27:48.524Z - info: ack: Apple-IpadAir2-1 setup_basic

2016-02-08T16:27:48.644Z - info: ack: Apple-Iphone6-1 setup_basic

2016-02-08T16:27:48.665Z - info: emit: Apple-IpadAir2-1 start_test_basic

2016-02-08T16:27:48.668Z - info: emit: Apple-Iphone6-1 start_test_basic

2016-02-08T16:27:48.731Z - info: ack: Apple-IpadAir2-1 start_test_basic

2016-02-08T16:27:48.805Z - info: ack: Apple-Iphone6-1 start_test_basic

2016-02-08T16:27:48.823Z - info: emit: Apple-IpadAir2-1 teardown_basic

2016-02-08T16:27:48.825Z - info: emit: Apple-Iphone6-1 teardown_basic

2016-02-08T16:27:48.840Z - info: ack: Apple-Iphone6-1 teardown_basic

2016-02-08T16:27:49.826Z - info: emit: Apple-IpadAir2-1 teardown_basic

2016-02-08T16:27:50.831Z - info: emit: Apple-IpadAir2-1 teardown_basic

2016-02-08T16:27:51.627Z - info: ack: Apple-IpadAir2-1 teardown_basic

2016-02-08T16:27:51.647Z - info: Running on ios test: another

2016-02-08T16:27:51.650Z - info: emit: Apple-IpadAir2-1 setup_another

2016-02-08T16:27:51.654Z - info: emit: Apple-Iphone6-1 setup_another

2016-02-08T16:27:51.678Z - info: ack: Apple-IpadAir2-1 setup_another

2016-02-08T16:27:52.335Z - info: ack: Apple-Iphone6-1 setup_another

2016-02-08T16:27:52.354Z - info: emit: Apple-IpadAir2-1 start_test_another

2016-02-08T16:27:52.358Z - info: emit: Apple-Iphone6-1 start_test_another

2016-02-08T16:27:52.394Z - info: ack: Apple-Iphone6-1 start_test_another

2016-02-08T16:27:52.398Z - info: ack: Apple-IpadAir2-1 start_test_another

2016-02-08T16:27:52.535Z - info: emit: Apple-IpadAir2-1 teardown_another

2016-02-08T16:27:52.541Z - info: emit: Apple-Iphone6-1 teardown_another

2016-02-08T16:27:52.554Z - info: ack: Apple-Iphone6-1 teardown_another

2016-02-08T16:27:52.565Z - info: ack: Apple-IpadAir2-1 teardown_another

2016-02-08T16:27:52.688Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.690Z - info: emit: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.694Z - info: emit: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.717Z - info: ack: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.720Z - info: ack: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.741Z - info: emit: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.744Z - info: emit: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.769Z - info: ack: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:52.812Z - info: ack: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:53.002Z - info: emit: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:53.005Z - info: emit: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:53.025Z - info: ack: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:53.135Z - info: ack: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:27:53.138Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.142Z - info: emit: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.144Z - info: emit: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.161Z - info: ack: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.165Z - info: ack: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.184Z - info: emit: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.189Z - info: emit: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.216Z - info: ack: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.313Z - info: ack: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.479Z - info: emit: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.481Z - info: emit: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.495Z - info: ack: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.498Z - info: ack: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:27:53.521Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.522Z - info: emit: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.526Z - info: emit: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.545Z - info: ack: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.654Z - info: ack: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.672Z - info: emit: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.674Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.685Z - info: ack: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.690Z - info: ack: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.828Z - info: emit: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.830Z - info: emit: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.846Z - info: ack: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.851Z - info: ack: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:27:53.874Z - info: Running on ios test: failed to get mobile documents path

2016-02-08T16:27:53.877Z - info: emit: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-08T16:27:53.880Z - info: emit: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-08T16:27:53.905Z - info: ack: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-08T16:27:54.015Z - info: ack: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-08T16:27:54.035Z - info: emit: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-08T16:27:54.038Z - info: emit: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-08T16:27:54.049Z - info: ack: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-08T16:27:54.166Z - info: ack: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-08T16:27:54.169Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-08T16:27:54.175Z - info: emit: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-08T16:27:54.191Z - info: ack: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-08T16:27:54.199Z - info: ack: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-08T16:27:54.222Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.223Z - info: emit: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.227Z - info: emit: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.254Z - info: ack: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.381Z - info: ack: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.386Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.390Z - info: emit: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.412Z - info: ack: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.521Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.546Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.549Z - info: emit: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.561Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.567Z - info: ack: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:27:54.685Z - info: Running on ios test: #init should register the networkChanged event

2016-02-08T16:27:54.687Z - info: emit: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-08T16:27:54.690Z - info: emit: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-08T16:27:54.704Z - info: ack: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-08T16:27:54.712Z - info: ack: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-08T16:27:54.729Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-08T16:27:54.735Z - info: emit: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-08T16:27:54.754Z - info: ack: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-08T16:27:54.860Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-08T16:27:54.880Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-08T16:27:54.883Z - info: emit: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-08T16:27:54.894Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-08T16:27:54.905Z - info: ack: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-08T16:27:55.027Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-08T16:27:55.030Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.033Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.045Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.058Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.075Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.078Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.105Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.209Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.233Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.236Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.247Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.250Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:27:55.379Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-08T16:27:55.491Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:55.495Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:55.559Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:56.497Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:57.423Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:57.447Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:57.449Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:57.475Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:58.451Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:27:59.455Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:00.462Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:01.470Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:02.479Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:03.486Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:04.202Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:04.236Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:04.240Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:04.254Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:05.243Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:06.250Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:06.778Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:28:06.799Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-08T16:28:06.803Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:28:06.806Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:28:06.817Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:28:07.807Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:28:07.813Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:28:07.826Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:07.830Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:07.844Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:08.834Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:09.843Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:09.865Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:28:09.893Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:28:09.897Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:28:09.922Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:28:10.753Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:28:10.772Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-08T16:28:10.776Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:10.779Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:10.801Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:11.783Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:12.792Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:12.910Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:28:12.927Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:28:12.931Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:28:12.948Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.847Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.873Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.875Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.887Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.970Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:28:13.985Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-08T16:28:13.986Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:28:13.990Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.012Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.070Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.075Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.078Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.107Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.243Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.264Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.267Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.296Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.407Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:28:14.425Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-08T16:28:14.428Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.430Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.444Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.447Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.567Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.569Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.580Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.584Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.610Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.612Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.621Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.745Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:28:14.764Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.767Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.769Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.783Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.785Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.906Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.908Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.919Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.921Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.947Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.949Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:14.962Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:15.088Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:28:15.107Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.110Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.112Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.124Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.127Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.271Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.274Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.288Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.291Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.412Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.414Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.432Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.434Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:28:15.453Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.456Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.458Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.470Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.599Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.618Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.622Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.633Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.762Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.793Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.796Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.811Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.929Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:28:15.948Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:15.950Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:15.953Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:15.963Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:15.967Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.089Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.092Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.099Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.103Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.128Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.131Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.152Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.270Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:28:16.290Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.292Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.294Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.309Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.316Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.437Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.439Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.459Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.533Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.595Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.597Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.632Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.635Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:28:16.645Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.648Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.650Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.672Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.789Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.808Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.810Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.821Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.952Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.977Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.979Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:16.995Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:17.118Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:28:17.138Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.141Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.145Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.163Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.280Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.285Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.287Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.352Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.453Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.497Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.499Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.512Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.631Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:28:17.648Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.650Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.653Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.664Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.666Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.684Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.686Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.701Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.704Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.727Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.729Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.740Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.743Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:28:17.761Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.764Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.766Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.789Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.800Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.813Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.815Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.826Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:17.830Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:18.093Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:18.095Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:18.128Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:18.133Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:28:18.151Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.154Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.156Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.189Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.192Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.209Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.213Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.244Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.246Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.303Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.307Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.317Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.322Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:28:18.736Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.738Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.740Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.773Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.775Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.793Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.796Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.848Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.912Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.915Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:18.917Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:19.142Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:19.207Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:28:19.209Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.211Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.214Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.247Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.280Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.299Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.303Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.338Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.357Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.393Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.395Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.760Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.787Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:28:19.790Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.792Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.795Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.846Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.866Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.904Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:19.908Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:20.157Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:20.210Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:24.040Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:24.043Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:24.058Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:24.066Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:28:24.515Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.517Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.520Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.556Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.564Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.577Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.587Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.601Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:24.613Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:28.708Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:28.710Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:28.733Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:28.758Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:28:28.802Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:28.804Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:28.808Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.232Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.261Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.281Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.285Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.297Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:29.300Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:33.424Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:33.427Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:33.446Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:33.448Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:28:33.482Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-08T16:28:33.486Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:28:33.489Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:28:33.502Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:28:33.507Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:28:33.536Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:28:33.539Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:28:33.784Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:28:33.960Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:28:39.714Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:28:39.718Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:28:39.738Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:28:39.745Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:28:40.238Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.242Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.244Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.268Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.270Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.278Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.281Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.305Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:40.309Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:47.700Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:47.703Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:48.129Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:48.156Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:28:48.197Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-08T16:28:48.200Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.202Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.543Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.636Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.657Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.661Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.681Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.692Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.981Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:28:48.985Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:28:49.013Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:28:49.017Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:28:49.035Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-08T16:28:49.038Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:28:49.043Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:28:49.073Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:28:49.469Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:28:49.481Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:28:49.484Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:28:49.509Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:28:49.515Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:28:49.633Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:28:49.637Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:28:49.671Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:28:49.674Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:28:49.692Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-08T16:28:49.693Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:28:49.697Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:28:49.730Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:28:50.159Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:28:50.162Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:28:50.164Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:28:50.224Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:28:50.241Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:28:57.168Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-G900F)

2016-02-08T16:29:09.707Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database

2016-02-08T16:29:09.711Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database

2016-02-08T16:29:10.131Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database

2016-02-08T16:29:10.212Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database

2016-02-08T16:29:10.636Z - info: Running on ios test: After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:10.640Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:10.642Z - info: emit: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:10.662Z - info: ack: Apple-Iphone6-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:11.643Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:12.648Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:12.709Z - debug: Socket disconnected: transport close 4 (Apple-IpadAir2-1)

2016-02-08T16:29:13.655Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:14.662Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:15.668Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:16.676Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:17.683Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:18.690Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:29:19.697Z - info: emit: Apple-IpadAir2-1 setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

2016-02-08T16:34:56.270Z - debug: Socket disconnected: ping timeout 7 (Apple-Iphone6-1)

2016-02-08T16:40:31.304Z - debug: Socket disconnected: ping timeout 10 (NOT YET SET)

2016-02-08T16:45:12.003Z - debug: Socket disconnected: transport close 1 (LGE-LG-D855)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m
2016-02-08T16:29:19.699Z - error: test server: Device undefined


```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali05
Console output:
```
Error! Unexpected exit on device 954a12ed app:com.test.thalitest code:0 
child process exited with code 0 on device 954a12ed 
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Android task is completed. [FAILED]
```
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655812b57f_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)




