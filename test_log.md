#### Test 58135655a1ee273 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-04T14:50:16.183Z - info: listening on *:3000

2016-02-04T14:50:17.513Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:0

2016-02-04T14:50:17.831Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:2

2016-02-04T14:50:17.834Z - info: Required number of android devices presented (2)

2016-02-04T14:50:17.837Z - info: Starting unit test run for platform: android

2016-02-04T14:50:18.319Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:3

2016-02-04T14:50:18.321Z - info: Discarding surplus device: LGE-LG-D722

2016-02-04T14:50:18.866Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:4

2016-02-04T14:50:18.867Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T14:50:19.274Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:5

2016-02-04T14:50:19.353Z - info: Running on android test: multiplex can send data

2016-02-04T14:50:19.362Z - info: emit: LGE-LG-H815 setup_multiplex can send data

2016-02-04T14:50:19.365Z - info: emit: motorola-Nexus 6 setup_multiplex can send data

2016-02-04T14:50:19.379Z - info: ack: LGE-LG-H815 setup_multiplex can send data

2016-02-04T14:50:19.461Z - info: ack: motorola-Nexus 6 setup_multiplex can send data

2016-02-04T14:50:19.473Z - info: emit: LGE-LG-H815 start_test_multiplex can send data

2016-02-04T14:50:19.475Z - info: emit: motorola-Nexus 6 start_test_multiplex can send data

2016-02-04T14:50:19.486Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:6

2016-02-04T14:50:19.487Z - info: Discarding surplus device: LGE-LG-D855

2016-02-04T14:50:19.492Z - info: ack: motorola-Nexus 6 start_test_multiplex can send data

2016-02-04T14:50:19.502Z - info: ack: LGE-LG-H815 start_test_multiplex can send data

2016-02-04T14:50:19.577Z - info: emit: LGE-LG-H815 teardown_multiplex can send data

2016-02-04T14:50:19.579Z - info: emit: motorola-Nexus 6 teardown_multiplex can send data

2016-02-04T14:50:19.598Z - debug: Socket disconnected: transport close 3 (LGE-LG-D722)

2016-02-04T14:50:19.621Z - info: ack: motorola-Nexus 6 teardown_multiplex can send data

2016-02-04T14:50:19.625Z - info: ack: LGE-LG-H815 teardown_multiplex can send data

2016-02-04T14:50:19.631Z - info: Running on android test: enqueue and run in order

2016-02-04T14:50:19.636Z - info: emit: LGE-LG-H815 setup_enqueue and run in order

2016-02-04T14:50:19.639Z - info: emit: motorola-Nexus 6 setup_enqueue and run in order

2016-02-04T14:50:19.651Z - info: ack: LGE-LG-H815 setup_enqueue and run in order

2016-02-04T14:50:19.666Z - info: ack: motorola-Nexus 6 setup_enqueue and run in order

2016-02-04T14:50:19.684Z - info: emit: LGE-LG-H815 start_test_enqueue and run in order

2016-02-04T14:50:19.686Z - info: emit: motorola-Nexus 6 start_test_enqueue and run in order

2016-02-04T14:50:19.702Z - info: ack: LGE-LG-H815 start_test_enqueue and run in order

2016-02-04T14:50:19.705Z - info: ack: motorola-Nexus 6 start_test_enqueue and run in order

2016-02-04T14:50:19.972Z - info: emit: LGE-LG-H815 teardown_enqueue and run in order

2016-02-04T14:50:19.975Z - info: emit: motorola-Nexus 6 teardown_enqueue and run in order

2016-02-04T14:50:19.983Z - info: ack: LGE-LG-H815 teardown_enqueue and run in order

2016-02-04T14:50:19.986Z - info: ack: motorola-Nexus 6 teardown_enqueue and run in order

2016-02-04T14:50:20.005Z - info: Running on android test: basic

2016-02-04T14:50:20.011Z - debug: Socket disconnected: transport close 4 (samsung-SM-G900F)

2016-02-04T14:50:20.019Z - info: emit: LGE-LG-H815 setup_basic

2016-02-04T14:50:20.022Z - info: emit: motorola-Nexus 6 setup_basic

2016-02-04T14:50:20.031Z - info: ack: LGE-LG-H815 setup_basic

2016-02-04T14:50:20.052Z - info: ack: motorola-Nexus 6 setup_basic

2016-02-04T14:50:20.072Z - info: emit: LGE-LG-H815 start_test_basic

2016-02-04T14:50:20.075Z - info: emit: motorola-Nexus 6 start_test_basic

2016-02-04T14:50:20.099Z - info: ack: LGE-LG-H815 start_test_basic

2016-02-04T14:50:20.102Z - info: ack: motorola-Nexus 6 start_test_basic

2016-02-04T14:50:20.121Z - info: emit: LGE-LG-H815 teardown_basic

2016-02-04T14:50:20.124Z - info: emit: motorola-Nexus 6 teardown_basic

2016-02-04T14:50:20.136Z - info: ack: LGE-LG-H815 teardown_basic

2016-02-04T14:50:20.151Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-02-04T14:50:20.152Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-04T14:50:20.164Z - info: ack: motorola-Nexus 6 teardown_basic

2016-02-04T14:50:20.177Z - info: Running on android test: another

2016-02-04T14:50:20.180Z - info: emit: LGE-LG-H815 setup_another

2016-02-04T14:50:20.183Z - info: emit: motorola-Nexus 6 setup_another

2016-02-04T14:50:20.211Z - info: ack: LGE-LG-H815 setup_another

2016-02-04T14:50:20.226Z - info: ack: motorola-Nexus 6 setup_another

2016-02-04T14:50:20.237Z - info: emit: LGE-LG-H815 start_test_another

2016-02-04T14:50:20.241Z - info: emit: motorola-Nexus 6 start_test_another

2016-02-04T14:50:20.250Z - info: ack: motorola-Nexus 6 start_test_another

2016-02-04T14:50:20.255Z - info: ack: LGE-LG-H815 start_test_another

2016-02-04T14:50:20.274Z - info: emit: LGE-LG-H815 teardown_another

2016-02-04T14:50:20.278Z - info: emit: motorola-Nexus 6 teardown_another

2016-02-04T14:50:20.286Z - info: ack: LGE-LG-H815 teardown_another

2016-02-04T14:50:20.310Z - info: ack: motorola-Nexus 6 teardown_another

2016-02-04T14:50:20.316Z - debug: Socket disconnected: transport close 6 (LGE-LG-D855)

2016-02-04T14:50:20.324Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.326Z - info: emit: LGE-LG-H815 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.329Z - info: emit: motorola-Nexus 6 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.345Z - info: ack: LGE-LG-H815 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.352Z - info: ack: motorola-Nexus 6 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.457Z - info: emit: LGE-LG-H815 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.474Z - info: emit: motorola-Nexus 6 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.483Z - info: ack: LGE-LG-H815 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.486Z - info: ack: motorola-Nexus 6 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.616Z - info: emit: LGE-LG-H815 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.620Z - info: emit: motorola-Nexus 6 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.635Z - info: ack: LGE-LG-H815 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.641Z - info: ack: motorola-Nexus 6 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:20.689Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.693Z - info: emit: LGE-LG-H815 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.696Z - info: emit: motorola-Nexus 6 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.706Z - info: ack: motorola-Nexus 6 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.711Z - info: ack: LGE-LG-H815 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.718Z - info: emit: LGE-LG-H815 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.725Z - info: emit: motorola-Nexus 6 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.730Z - info: ack: LGE-LG-H815 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.734Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:1

2016-02-04T14:50:20.736Z - info: Required number of ios devices presented (2)

2016-02-04T14:50:20.738Z - info: Starting unit test run for platform: ios

2016-02-04T14:50:20.763Z - info: ack: motorola-Nexus 6 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.809Z - info: emit: LGE-LG-H815 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.813Z - info: emit: motorola-Nexus 6 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.823Z - info: ack: LGE-LG-H815 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.826Z - info: ack: motorola-Nexus 6 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:20.838Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.841Z - info: emit: LGE-LG-H815 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.844Z - info: emit: motorola-Nexus 6 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.852Z - info: ack: LGE-LG-H815 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.855Z - info: ack: motorola-Nexus 6 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.865Z - info: emit: LGE-LG-H815 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.868Z - info: emit: motorola-Nexus 6 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.877Z - info: ack: LGE-LG-H815 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.880Z - info: ack: motorola-Nexus 6 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.889Z - info: emit: LGE-LG-H815 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.896Z - info: emit: motorola-Nexus 6 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.902Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:8

2016-02-04T14:50:20.903Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-04T14:50:20.908Z - info: ack: LGE-LG-H815 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.913Z - info: ack: motorola-Nexus 6 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:20.920Z - info: Running on android test: failed to get mobile documents path

2016-02-04T14:50:20.922Z - info: emit: LGE-LG-H815 setup_failed to get mobile documents path

2016-02-04T14:50:20.931Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-02-04T14:50:20.936Z - info: emit: motorola-Nexus 6 setup_failed to get mobile documents path

2016-02-04T14:50:20.944Z - info: ack: LGE-LG-H815 setup_failed to get mobile documents path

2016-02-04T14:50:20.963Z - info: ack: motorola-Nexus 6 setup_failed to get mobile documents path

2016-02-04T14:50:20.969Z - info: emit: LGE-LG-H815 start_test_failed to get mobile documents path

2016-02-04T14:50:20.971Z - info: emit: motorola-Nexus 6 start_test_failed to get mobile documents path

2016-02-04T14:50:20.985Z - info: ack: LGE-LG-H815 start_test_failed to get mobile documents path

2016-02-04T14:50:21.004Z - info: ack: motorola-Nexus 6 start_test_failed to get mobile documents path

2016-02-04T14:50:21.017Z - info: emit: LGE-LG-H815 teardown_failed to get mobile documents path

2016-02-04T14:50:21.020Z - info: emit: motorola-Nexus 6 teardown_failed to get mobile documents path

2016-02-04T14:50:21.035Z - info: ack: motorola-Nexus 6 teardown_failed to get mobile documents path

2016-02-04T14:50:21.038Z - info: ack: LGE-LG-H815 teardown_failed to get mobile documents path

2016-02-04T14:50:21.046Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.048Z - info: emit: LGE-LG-H815 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.051Z - info: emit: motorola-Nexus 6 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.063Z - info: ack: motorola-Nexus 6 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.069Z - info: ack: LGE-LG-H815 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.083Z - info: emit: LGE-LG-H815 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.085Z - info: emit: motorola-Nexus 6 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.097Z - info: ack: motorola-Nexus 6 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.103Z - info: ack: LGE-LG-H815 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.115Z - info: emit: LGE-LG-H815 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.119Z - info: emit: motorola-Nexus 6 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.128Z - info: ack: LGE-LG-H815 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.135Z - info: ack: motorola-Nexus 6 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:21.140Z - info: Running on android test: #init should register the networkChanged event

2016-02-04T14:50:21.143Z - info: emit: LGE-LG-H815 setup_#init should register the networkChanged event
2016-02-04T14:50:21.146Z - info: emit: motorola-Nexus 6 setup_#init should register the networkChanged event

2016-02-04T14:50:21.159Z - info: ack: LGE-LG-H815 setup_#init should register the networkChanged event

2016-02-04T14:50:21.162Z - info: ack: motorola-Nexus 6 setup_#init should register the networkChanged event

2016-02-04T14:50:21.173Z - info: emit: LGE-LG-H815 start_test_#init should register the networkChanged event

2016-02-04T14:50:21.176Z - info: emit: motorola-Nexus 6 start_test_#init should register the networkChanged event

2016-02-04T14:50:21.186Z - info: ack: LGE-LG-H815 start_test_#init should register the networkChanged event

2016-02-04T14:50:21.188Z - info: ack: motorola-Nexus 6 start_test_#init should register the networkChanged event

2016-02-04T14:50:21.199Z - info: emit: LGE-LG-H815 teardown_#init should register the networkChanged event

2016-02-04T14:50:21.202Z - info: emit: motorola-Nexus 6 teardown_#init should register the networkChanged event

2016-02-04T14:50:21.219Z - info: ack: motorola-Nexus 6 teardown_#init should register the networkChanged event

2016-02-04T14:50:21.224Z - info: ack: LGE-LG-H815 teardown_#init should register the networkChanged event

2016-02-04T14:50:21.249Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-04T14:50:21.251Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.255Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.268Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.271Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.287Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.293Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.309Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.315Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.324Z - debug: Socket disconnected: transport close 8 (LGE-Nexus 5)

2016-02-04T14:50:21.337Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.340Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.348Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.353Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:50:21.366Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.368Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.372Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.379Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.396Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.410Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.413Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.424Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.427Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.467Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.469Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.480Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.502Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:50:21.511Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-04T14:50:21.512Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-04T14:50:21.517Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-04T14:50:21.520Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.523Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.532Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.535Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.544Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.547Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.556Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.560Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.570Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.574Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.580Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.584Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:50:21.591Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-04T14:50:21.595Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.597Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.607Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.610Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.620Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.623Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.631Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.635Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.650Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.653Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.661Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.664Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:50:21.673Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-04T14:50:21.676Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.679Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.688Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.691Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.701Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.704Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.712Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.719Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.735Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.739Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.747Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.750Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:50:21.757Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-04T14:50:21.758Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.766Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.792Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.798Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.819Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.821Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.840Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.845Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.863Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.865Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.876Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.880Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:50:21.896Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.912Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.915Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.927Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.938Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.949Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-04T14:50:21.956Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.969Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.974Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:21.980Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:22.001Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:22.003Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:22.025Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:22.031Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:50:22.044Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.046Z - info: emit: LGE-LG-H815 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.050Z - info: emit: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.068Z - info: ack: LGE-LG-H815 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.074Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.087Z - info: emit: LGE-LG-H815 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.091Z - info: emit: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.100Z - info: ack: LGE-LG-H815 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.108Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.126Z - info: Running on ios test: multiplex can send data

2016-02-04T14:50:22.129Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T14:50:22.134Z - info: emit: Apple-Iphone6-1 setup_multiplex can send data

2016-02-04T14:50:22.137Z - info: emit: LGE-LG-H815 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.139Z - info: emit: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.149Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.152Z - info: ack: LGE-LG-H815 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:50:22.162Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.165Z - info: emit: LGE-LG-H815 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.170Z - info: emit: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.180Z - info: ack: LGE-LG-H815 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.190Z - info: ack: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.204Z - info: emit: LGE-LG-H815 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.206Z - info: emit: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.223Z - info: ack: LGE-LG-H815 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.226Z - info: ack: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.248Z - info: emit: LGE-LG-H815 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.251Z - info: emit: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.260Z - info: ack: LGE-LG-H815 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.264Z - info: ack: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:50:22.276Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.281Z - info: emit: LGE-LG-H815 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.284Z - info: emit: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.296Z - info: ack: LGE-LG-H815 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.299Z - info: ack: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.313Z - info: emit: LGE-LG-H815 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.316Z - info: emit: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.329Z - info: ack: LGE-LG-H815 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.333Z - info: ack: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.347Z - info: emit: LGE-LG-H815 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.353Z - info: emit: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.359Z - info: ack: LGE-LG-H815 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.367Z - info: ack: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:50:22.378Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.381Z - info: emit: LGE-LG-H815 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.385Z - info: emit: motorola-Nexus 6 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.398Z - info: ack: motorola-Nexus 6 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.402Z - info: ack: LGE-LG-H815 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.420Z - info: emit: LGE-LG-H815 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.422Z - info: emit: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.435Z - info: ack: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.442Z - info: ack: LGE-LG-H815 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.464Z - info: emit: LGE-LG-H815 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.467Z - info: emit: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.476Z - info: ack: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.479Z - info: ack: LGE-LG-H815 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:50:22.487Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.490Z - info: emit: LGE-LG-H815 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.493Z - info: emit: motorola-Nexus 6 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.502Z - info: ack: LGE-LG-H815 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.505Z - info: ack: motorola-Nexus 6 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.532Z - info: emit: LGE-LG-H815 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.535Z - info: emit: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.546Z - info: ack: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.549Z - info: ack: LGE-LG-H815 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.576Z - info: emit: LGE-LG-H815 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.579Z - info: emit: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.595Z - info: ack: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.608Z - info: ack: LGE-LG-H815 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:50:22.618Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.625Z - info: emit: LGE-LG-H815 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.629Z - info: emit: motorola-Nexus 6 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.642Z - info: ack: motorola-Nexus 6 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.670Z - info: ack: LGE-LG-H815 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.678Z - info: emit: LGE-LG-H815 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.681Z - info: emit: motorola-Nexus 6 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.699Z - info: ack: motorola-Nexus 6 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.725Z - info: ack: LGE-LG-H815 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.773Z - info: emit: LGE-LG-H815 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.775Z - info: emit: motorola-Nexus 6 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.792Z - info: ack: motorola-Nexus 6 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.841Z - info: ack: LGE-LG-H815 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:50:22.852Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.857Z - info: emit: LGE-LG-H815 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.861Z - info: emit: motorola-Nexus 6 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.878Z - info: ack: motorola-Nexus 6 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.906Z - info: ack: LGE-LG-H815 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.926Z - info: emit: LGE-LG-H815 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.928Z - info: emit: motorola-Nexus 6 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.950Z - info: ack: motorola-Nexus 6 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.953Z - info: ack: LGE-LG-H815 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.969Z - info: emit: LGE-LG-H815 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.973Z - info: emit: motorola-Nexus 6 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.982Z - info: ack: motorola-Nexus 6 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.985Z - info: ack: LGE-LG-H815 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:50:22.991Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:22.993Z - info: emit: LGE-LG-H815 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:22.997Z - info: emit: motorola-Nexus 6 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.010Z - info: ack: motorola-Nexus 6 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.013Z - info: ack: LGE-LG-H815 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.022Z - info: emit: LGE-LG-H815 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.026Z - info: emit: motorola-Nexus 6 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.036Z - info: ack: motorola-Nexus 6 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.046Z - info: ack: LGE-LG-H815 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:50:23.131Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T14:50:23.139Z - info: emit: Apple-Iphone6-1 setup_multiplex can send data

2016-02-04T14:50:23.679Z - info: ack: Apple-Iphone6-1 setup_multiplex can send data

2016-02-04T14:50:24.134Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T14:50:25.136Z - info: emit: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T14:50:26.145Z - info: ack: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-04T14:50:26.168Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T14:50:26.173Z - info: emit: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-04T14:50:26.425Z - info: ack: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-04T14:50:27.171Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T14:50:28.176Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T14:50:29.184Z - info: emit: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T14:50:29.276Z - info: ack: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-04T14:50:29.364Z - info: emit: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-04T14:50:29.370Z - info: emit: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-04T14:50:29.481Z - info: ack: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-04T14:50:29.698Z - info: ack: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-04T14:50:29.714Z - info: Running on ios test: enqueue and run in order

2016-02-04T14:50:29.718Z - info: emit: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-04T14:50:29.721Z - info: emit: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-04T14:50:29.845Z - info: ack: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-04T14:50:30.407Z - info: ack: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-04T14:50:30.426Z - info: emit: Apple-IpadAir2-1 start_test_enqueue and run in order
2016-02-04T14:50:30.430Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-04T14:50:30.716Z - info: ack: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-04T14:50:31.432Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-04T14:50:32.438Z - info: emit: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-04T14:50:32.876Z - info: ack: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-04T14:50:33.100Z - info: emit: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-04T14:50:33.104Z - info: emit: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-04T14:50:33.182Z - info: ack: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-04T14:50:34.104Z - info: emit: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-04T14:50:34.194Z - info: ack: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-04T14:50:34.210Z - info: Running on ios test: basic

2016-02-04T14:50:34.214Z - info: emit: Apple-IpadAir2-1 setup_basic

2016-02-04T14:50:34.217Z - info: emit: Apple-Iphone6-1 setup_basic

2016-02-04T14:50:34.291Z - info: ack: Apple-IpadAir2-1 setup_basic

2016-02-04T14:50:35.220Z - info: emit: Apple-Iphone6-1 setup_basic

2016-02-04T14:50:35.834Z - info: ack: Apple-Iphone6-1 setup_basic

2016-02-04T14:50:35.853Z - info: emit: Apple-IpadAir2-1 start_test_basic

2016-02-04T14:50:35.855Z - info: emit: Apple-Iphone6-1 start_test_basic

2016-02-04T14:50:36.483Z - info: ack: Apple-Iphone6-1 start_test_basic

2016-02-04T14:50:36.887Z - info: emit: Apple-IpadAir2-1 start_test_basic

2016-02-04T14:50:37.267Z - info: ack: Apple-IpadAir2-1 start_test_basic

2016-02-04T14:50:37.288Z - info: emit: Apple-IpadAir2-1 teardown_basic

2016-02-04T14:50:37.291Z - info: emit: Apple-Iphone6-1 teardown_basic

2016-02-04T14:50:37.318Z - info: ack: Apple-IpadAir2-1 teardown_basic

2016-02-04T14:50:38.293Z - info: emit: Apple-Iphone6-1 teardown_basic

2016-02-04T14:50:39.299Z - info: emit: Apple-Iphone6-1 teardown_basic

2016-02-04T14:50:40.045Z - info: ack: Apple-Iphone6-1 teardown_basic

2016-02-04T14:50:40.065Z - info: Running on ios test: another

2016-02-04T14:50:40.068Z - info: emit: Apple-IpadAir2-1 setup_another

2016-02-04T14:50:40.071Z - info: emit: Apple-Iphone6-1 setup_another

2016-02-04T14:50:40.082Z - info: ack: Apple-Iphone6-1 setup_another

2016-02-04T14:50:40.658Z - info: ack: Apple-IpadAir2-1 setup_another

2016-02-04T14:50:40.683Z - info: emit: Apple-IpadAir2-1 start_test_another

2016-02-04T14:50:40.686Z - info: emit: Apple-Iphone6-1 start_test_another

2016-02-04T14:50:40.706Z - info: ack: Apple-IpadAir2-1 start_test_another

2016-02-04T14:50:40.750Z - info: ack: Apple-Iphone6-1 start_test_another

2016-02-04T14:50:40.769Z - info: emit: Apple-IpadAir2-1 teardown_another

2016-02-04T14:50:40.772Z - info: emit: Apple-Iphone6-1 teardown_another

2016-02-04T14:50:40.783Z - info: ack: Apple-Iphone6-1 teardown_another

2016-02-04T14:50:40.802Z - info: ack: Apple-IpadAir2-1 teardown_another

2016-02-04T14:50:40.909Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.911Z - info: emit: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.916Z - info: emit: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.927Z - info: ack: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.933Z - info: ack: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.952Z - info: emit: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.954Z - info: emit: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:40.964Z - info: ack: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:41.093Z - info: ack: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:41.369Z - info: emit: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:41.372Z - info: emit: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:41.383Z - info: ack: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:41.666Z - debug: Socket disconnected: transport close 10 (NOT YET SET)

2016-02-04T14:50:42.372Z - info: emit: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:43.377Z - info: emit: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:43.411Z - info: ack: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-04T14:50:43.445Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.449Z - info: emit: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.452Z - info: emit: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.463Z - info: ack: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.562Z - info: ack: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.584Z - info: emit: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.588Z - info: emit: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.656Z - info: ack: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.758Z - info: ack: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.896Z - info: emit: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:43.899Z - info: emit: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:44.000Z - info: ack: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:44.618Z - info: ack: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-04T14:50:44.741Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:44.744Z - info: emit: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:44.748Z - info: emit: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:44.817Z - info: ack: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:45.747Z - info: emit: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:46.483Z - info: ack: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:46.505Z - info: emit: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:46.509Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:46.545Z - info: ack: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:47.512Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:48.523Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:49.535Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:50.544Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:51.552Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:52.561Z - info: emit: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:52.679Z - info: ack: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:52.763Z - info: emit: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:52.766Z - info: emit: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:52.805Z - info: ack: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:53.026Z - info: ack: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-04T14:50:53.048Z - info: Running on ios test: failed to get mobile documents path

2016-02-04T14:50:53.051Z - info: emit: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-04T14:50:53.055Z - info: emit: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-04T14:50:53.247Z - info: ack: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-04T14:50:54.059Z - info: emit: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-04T14:50:54.863Z - debug: Device presented: Apple-Iphone5-1 (ios) unittest socket:11

2016-02-04T14:50:54.864Z - info: Discarding surplus device: Apple-Iphone5-1

2016-02-04T14:50:55.065Z - info: emit: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-04T14:50:55.501Z - info: ack: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-04T14:50:55.529Z - info: emit: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-04T14:50:55.533Z - info: emit: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-04T14:50:55.554Z - info: ack: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-04T14:50:55.898Z - info: ack: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-04T14:50:55.912Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T14:50:55.916Z - info: emit: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-04T14:50:55.930Z - info: ack: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-04T14:50:56.917Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T14:50:57.922Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T14:50:58.931Z - info: emit: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T14:50:59.167Z - info: ack: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-04T14:50:59.194Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.197Z - info: emit: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.201Z - info: emit: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.251Z - info: ack: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.313Z - info: ack: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.332Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.335Z - info: emit: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.436Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.617Z - info: ack: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.742Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.747Z - info: emit: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:50:59.781Z - info: ack: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:51:00.746Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:51:01.751Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:51:02.352Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-04T14:51:02.368Z - info: Running on ios test: #init should register the networkChanged event

2016-02-04T14:51:02.371Z - info: emit: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-04T14:51:02.375Z - info: emit: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-04T14:51:02.407Z - info: ack: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-04T14:51:02.546Z - info: ack: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-04T14:51:02.550Z - info: emit: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-04T14:51:02.553Z - info: emit: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-04T14:51:02.582Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-04T14:51:02.593Z - info: ack: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-04T14:51:02.721Z - info: emit: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-04T14:51:02.724Z - info: emit: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-04T14:51:02.866Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-04T14:51:02.876Z - info: ack: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-04T14:51:02.887Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-04T14:51:02.890Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-04T14:51:02.893Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-04T14:51:02.918Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-04T14:51:02.921Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.058Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.060Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.581Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.771Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.776Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.779Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.800Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.861Z - debug: Socket disconnected: transport close 11 (Apple-Iphone5-1)

2016-02-04T14:51:03.907Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-04T14:51:03.927Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-04T14:51:03.929Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:03.933Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:03.954Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:04.421Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:04.439Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:04.443Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:04.595Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:05.445Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:06.451Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:07.460Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:08.470Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:09.479Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:10.486Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:10.698Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:10.721Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:10.724Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:10.747Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:11.724Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:12.468Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-04T14:51:12.487Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-04T14:51:12.491Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:51:12.494Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.077Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.357Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.377Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.381Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.393Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.401Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.425Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.428Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.445Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.476Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-04T14:51:13.493Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-04T14:51:13.497Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.500Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.520Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.550Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.570Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.573Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.593Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.624Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.647Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.650Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.670Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.703Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-04T14:51:13.722Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-04T14:51:13.726Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.729Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.744Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.775Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.796Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.798Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.817Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.850Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.872Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.874Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.897Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.927Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-04T14:51:13.945Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-04T14:51:13.946Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-04T14:51:13.950Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-04T14:51:13.981Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.013Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.032Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.036Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.053Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.089Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.112Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.114Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.129Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.166Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-04T14:51:14.185Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.186Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.190Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.216Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.222Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.239Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.241Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.256Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.302Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.329Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.331Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.350Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.383Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-04T14:51:14.402Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.405Z - info: emit: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.407Z - info: emit: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.427Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.459Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.479Z - info: emit: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.481Z - info: emit: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.501Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.537Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.566Z - info: emit: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.568Z - info: emit: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.581Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.614Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-04T14:51:14.634Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.636Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.638Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.656Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.691Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.711Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.713Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.731Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.761Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.786Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.788Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.807Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.819Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-04T14:51:14.832Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.835Z - info: emit: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.837Z - info: emit: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.851Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.858Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.878Z - info: emit: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.880Z - info: emit: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.895Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.900Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.933Z - info: emit: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.937Z - info: emit: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.949Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.954Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-04T14:51:14.972Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:14.975Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:14.977Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:14.990Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:14.999Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.019Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.021Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.036Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.040Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.065Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.067Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.077Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.082Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-04T14:51:15.101Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.103Z - info: emit: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.105Z - info: emit: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.116Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.131Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.152Z - info: emit: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.156Z - info: emit: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.166Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.177Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.201Z - info: emit: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.205Z - info: emit: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.218Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.221Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-04T14:51:15.239Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.242Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.244Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.254Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.258Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.278Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.280Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.290Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.293Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.317Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.321Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:15.559Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:16.323Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:17.328Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:18.333Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:18.519Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-04T14:51:18.536Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:18.540Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:18.542Z - info: emit: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:18.561Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:19.542Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:20.546Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:21.554Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:22.561Z - info: emit: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:23.534Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:23.551Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:23.555Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:24.556Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:24.566Z - info: emit: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:24.649Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:25.564Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:26.569Z - info: emit: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:26.593Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:26.628Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:26.631Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:27.632Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:27.639Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:28.640Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:28.645Z - info: emit: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:28.958Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:29.649Z - info: emit: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:29.975Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-04T14:51:29.995Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:29.996Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:30.000Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:30.028Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:31.002Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:31.925Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:31.947Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:31.950Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:31.979Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:32.735Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:32.995Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:32.998Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:33.066Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:34.015Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:34.983Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-04T14:51:35.002Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.005Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.007Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.064Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.273Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.293Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.295Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.322Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.324Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.567Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.569Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.716Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.719Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-04T14:51:35.736Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.739Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.741Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.779Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.782Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.799Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.802Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:35.825Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.174Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.213Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.215Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.225Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.284Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-04T14:51:36.287Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.289Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.292Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.352Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.377Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.666Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.668Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.716Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.741Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.783Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.785Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.823Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.849Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-04T14:51:36.898Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-04T14:51:36.899Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:36.903Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.175Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.232Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.253Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.255Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.271Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:37.296Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:42.557Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:42.560Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:42.594Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:42.597Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-04T14:51:43.084Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.088Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.090Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.104Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.140Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.186Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.188Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.615Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:43.691Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:47.805Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:47.809Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:47.840Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:47.860Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-04T14:51:47.870Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:47.871Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:47.875Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:47.893Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:47.901Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:48.053Z - debug: Socket disconnected: ping timeout 0 (LGE-LG-H815)

2016-02-04T14:51:48.323Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:48.325Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:48.357Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:48.395Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:52.520Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:52.524Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:52.547Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:52.552Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-04T14:51:52.577Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-04T14:51:52.580Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-04T14:51:52.585Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-04T14:51:52.599Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-04T14:51:52.606Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-04T14:51:52.632Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-04T14:51:52.637Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-04T14:51:52.866Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-04T14:51:53.055Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-04T14:51:57.841Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-04T14:51:57.846Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-04T14:51:57.867Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-04T14:51:57.875Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-04T14:51:58.284Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.288Z - info: emit: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.291Z - info: emit: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.313Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.319Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.345Z - info: emit: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.347Z - info: emit: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.362Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:51:58.368Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:52:20.823Z - info: emit: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:52:20.826Z - info: emit: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:52:20.853Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:52:20.858Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-04T14:52:20.914Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-04T14:52:20.916Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-04T14:52:20.919Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-04T14:52:20.936Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.154Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.158Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.162Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.177Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.185Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.358Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.360Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.384Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.387Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-04T14:52:21.391Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-04T14:52:21.394Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-04T14:52:21.396Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-04T14:52:21.419Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-04T14:52:21.443Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-04T14:52:21.470Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-04T14:52:21.473Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-04T14:52:21.726Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-04T14:52:21.769Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-04T14:52:21.892Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-04T14:52:21.896Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-04T14:52:21.911Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-04T14:52:21.947Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-04T14:52:21.949Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-04T14:52:21.952Z - info: emit: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-04T14:52:21.954Z - info: emit: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-04T14:52:21.985Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-04T14:52:21.990Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-04T14:52:22.204Z - info: emit: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-04T14:52:22.206Z - info: emit: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-04T14:52:22.269Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-04T14:52:22.291Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-04T14:52:43.923Z - info: emit: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database

2016-02-04T14:52:43.926Z - info: emit: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database

2016-02-04T14:52:44.413Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager replicates database

2016-02-04T14:52:44.418Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager replicates database

2016-02-04T14:52:47.134Z - debug: Socket disconnected: transport close 1 (Apple-Iphone6-1)

2016-02-04T15:03:08.905Z - debug: Socket disconnected: transport close 5 (Apple-IpadAir2-1)

2016-02-04T15:06:35.392Z - debug: Socket disconnected: transport close 2 (motorola-Nexus 6)


 
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
ios: child process exited with code 254 on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:0 
child process exited with code 0 on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/58135655a1ee273_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)




