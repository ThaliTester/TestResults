#### Test 581356550b07fff Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":3,"android":21}}
2016-02-08T16:56:07.289Z - info: listening on *:3000

2016-02-08T16:56:10.052Z - debug: Device presented: motorola-Nexus 6 (android) unittest socket:0

2016-02-08T16:56:10.108Z - debug: Device presented: LGE-LG-D722 (android) unittest socket:1

2016-02-08T16:56:10.111Z - info: Required number of android devices presented (2)

2016-02-08T16:56:10.114Z - info: Starting unit test run for platform: android

2016-02-08T16:56:10.182Z - debug: Device presented: LGE-Nexus 5 (android) unittest socket:2

2016-02-08T16:56:10.186Z - info: Discarding surplus device: LGE-Nexus 5

2016-02-08T16:56:10.297Z - debug: Device presented: LGE-LG-H815 (android) unittest socket:3

2016-02-08T16:56:10.298Z - info: Discarding surplus device: LGE-LG-H815

2016-02-08T16:56:10.448Z - debug: Device presented: Apple-Iphone6-1 (ios) unittest socket:4

2016-02-08T16:56:10.482Z - info: Running on android test: multiplex can send data

2016-02-08T16:56:10.504Z - info: ack: LGE-LG-D722 setup_multiplex can send data

2016-02-08T16:56:10.516Z - info: ack: motorola-Nexus 6 setup_multiplex can send data

2016-02-08T16:56:10.536Z - info: ack: motorola-Nexus 6 start_test_multiplex can send data

2016-02-08T16:56:10.540Z - info: ack: LGE-LG-D722 start_test_multiplex can send data

2016-02-08T16:56:10.664Z - debug: Socket disconnected: transport close 2 (LGE-Nexus 5)

2016-02-08T16:56:10.679Z - info: ack: LGE-LG-D722 teardown_multiplex can send data

2016-02-08T16:56:10.688Z - info: ack: motorola-Nexus 6 teardown_multiplex can send data

2016-02-08T16:56:10.694Z - info: Running on android test: enqueue and run in order

2016-02-08T16:56:10.707Z - info: ack: motorola-Nexus 6 setup_enqueue and run in order

2016-02-08T16:56:10.712Z - info: ack: LGE-LG-D722 setup_enqueue and run in order

2016-02-08T16:56:10.743Z - info: ack: LGE-LG-D722 start_test_enqueue and run in order

2016-02-08T16:56:10.747Z - info: ack: motorola-Nexus 6 start_test_enqueue and run in order

2016-02-08T16:56:11.011Z - info: ack: LGE-LG-D722 teardown_enqueue and run in order

2016-02-08T16:56:11.014Z - info: ack: motorola-Nexus 6 teardown_enqueue and run in order

2016-02-08T16:56:11.020Z - info: Running on android test: basic

2016-02-08T16:56:11.034Z - info: ack: LGE-LG-D722 setup_basic

2016-02-08T16:56:11.036Z - info: ack: motorola-Nexus 6 setup_basic

2016-02-08T16:56:11.059Z - info: ack: motorola-Nexus 6 start_test_basic

2016-02-08T16:56:11.068Z - info: ack: LGE-LG-D722 start_test_basic

2016-02-08T16:56:11.097Z - info: ack: LGE-LG-D722 teardown_basic

2016-02-08T16:56:11.111Z - info: ack: motorola-Nexus 6 teardown_basic

2016-02-08T16:56:11.122Z - info: Running on android test: another

2016-02-08T16:56:11.136Z - info: ack: LGE-LG-D722 setup_another

2016-02-08T16:56:11.139Z - info: ack: motorola-Nexus 6 setup_another

2016-02-08T16:56:11.162Z - info: ack: LGE-LG-D722 start_test_another

2016-02-08T16:56:11.165Z - info: ack: motorola-Nexus 6 start_test_another

2016-02-08T16:56:11.183Z - info: ack: LGE-LG-D722 teardown_another

2016-02-08T16:56:11.186Z - info: ack: motorola-Nexus 6 teardown_another

2016-02-08T16:56:11.193Z - info: Running on android test: successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.206Z - info: ack: motorola-Nexus 6 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.208Z - info: ack: LGE-LG-D722 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.254Z - debug: Socket disconnected: transport close 3 (LGE-LG-H815)

2016-02-08T16:56:11.311Z - info: ack: motorola-Nexus 6 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.317Z - info: ack: LGE-LG-D722 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.485Z - info: ack: LGE-LG-D722 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.514Z - info: ack: motorola-Nexus 6 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:11.544Z - info: Running on android test: successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.555Z - info: ack: motorola-Nexus 6 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.560Z - info: ack: LGE-LG-D722 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.575Z - info: ack: motorola-Nexus 6 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.578Z - info: ack: LGE-LG-D722 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.695Z - info: ack: motorola-Nexus 6 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.702Z - info: ack: LGE-LG-D722 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:11.716Z - info: Running on android test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.730Z - info: ack: motorola-Nexus 6 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.747Z - info: ack: LGE-LG-D722 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.772Z - info: ack: motorola-Nexus 6 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.777Z - info: ack: LGE-LG-D722 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.795Z - info: ack: motorola-Nexus 6 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.806Z - info: ack: LGE-LG-D722 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:11.811Z - info: Running on android test: failed to get mobile documents path

2016-02-08T16:56:11.820Z - info: ack: motorola-Nexus 6 setup_failed to get mobile documents path

2016-02-08T16:56:11.829Z - info: ack: LGE-LG-D722 setup_failed to get mobile documents path

2016-02-08T16:56:11.848Z - info: ack: motorola-Nexus 6 start_test_failed to get mobile documents path

2016-02-08T16:56:11.854Z - info: ack: LGE-LG-D722 start_test_failed to get mobile documents path

2016-02-08T16:56:11.876Z - info: ack: motorola-Nexus 6 teardown_failed to get mobile documents path

2016-02-08T16:56:11.883Z - info: ack: LGE-LG-D722 teardown_failed to get mobile documents path

2016-02-08T16:56:11.894Z - info: Running on android test: #init should register the peerAvailabilityChanged event

2016-02-08T16:56:11.907Z - debug: Device presented: LGE-LG-D855 (android) unittest socket:5

2016-02-08T16:56:11.908Z - info: Discarding surplus device: LGE-LG-D855

2016-02-08T16:56:11.922Z - info: ack: motorola-Nexus 6 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:11.928Z - info: ack: LGE-LG-D722 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:11.943Z - info: ack: motorola-Nexus 6 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:11.990Z - info: ack: LGE-LG-D722 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:12.027Z - info: ack: motorola-Nexus 6 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:12.049Z - info: ack: LGE-LG-D722 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:12.052Z - info: Running on android test: #init should register the networkChanged event

2016-02-08T16:56:12.080Z - info: ack: LGE-LG-D722 setup_#init should register the networkChanged event

2016-02-08T16:56:12.088Z - info: ack: motorola-Nexus 6 setup_#init should register the networkChanged event

2016-02-08T16:56:12.106Z - info: ack: LGE-LG-D722 start_test_#init should register the networkChanged event

2016-02-08T16:56:12.110Z - info: ack: motorola-Nexus 6 start_test_#init should register the networkChanged event

2016-02-08T16:56:12.148Z - info: ack: motorola-Nexus 6 teardown_#init should register the networkChanged event

2016-02-08T16:56:12.153Z - info: ack: LGE-LG-D722 teardown_#init should register the networkChanged event

2016-02-08T16:56:12.173Z - info: Running on android test: #startBroadcasting should throw on null device name

2016-02-08T16:56:12.187Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.197Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.234Z - debug: Device presented: Apple-IpadAir2-1 (ios) unittest socket:6

2016-02-08T16:56:12.236Z - info: Required number of ios devices presented (2)

2016-02-08T16:56:12.238Z - info: Starting unit test run for platform: ios

2016-02-08T16:56:12.250Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.255Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.279Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.283Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:56:12.298Z - info: Running on android test: #startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.311Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.314Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.339Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.342Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.361Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:7

2016-02-08T16:56:12.362Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T16:56:12.381Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.386Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:12.394Z - info: Running on android test: #startBroadcasting should throw on non-number port

2016-02-08T16:56:12.406Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.409Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.429Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.432Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.473Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.487Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:56:12.490Z - info: Running on android test: #startBroadcasting should throw on NaN port

2016-02-08T16:56:12.506Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.509Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.544Z - debug: Socket disconnected: transport close 5 (LGE-LG-D855)

2016-02-08T16:56:12.552Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.557Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.581Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.587Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:56:12.599Z - info: Running on android test: #startBroadcasting should throw on negative port

2016-02-08T16:56:12.609Z - info: Running on ios test: multiplex can send data

2016-02-08T16:56:12.616Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.624Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.641Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.644Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.647Z - info: ack: Apple-Iphone6-1 setup_multiplex can send data

2016-02-08T16:56:12.669Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.683Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:56:12.685Z - info: Running on android test: #startBroadcasting should throw on too large port

2016-02-08T16:56:12.700Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.703Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.739Z - info: ack: Apple-IpadAir2-1 setup_multiplex can send data

2016-02-08T16:56:12.747Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.755Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.777Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.789Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:56:12.796Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.810Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.833Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.838Z - info: ack: Apple-Iphone6-1 start_test_multiplex can send data

2016-02-08T16:56:12.851Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.897Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.913Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.922Z - info: ack: Apple-IpadAir2-1 start_test_multiplex can send data

2016-02-08T16:56:12.925Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:12.931Z - info: Running on android test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:12.942Z - info: ack: motorola-Nexus 6 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:12.949Z - info: ack: LGE-LG-D722 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:12.969Z - info: ack: motorola-Nexus 6 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:12.972Z - info: ack: LGE-LG-D722 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:13.007Z - info: ack: motorola-Nexus 6 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:13.010Z - info: ack: LGE-LG-D722 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:13.021Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.043Z - info: ack: LGE-LG-D722 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.045Z - info: ack: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.079Z - info: ack: LGE-LG-D722 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.082Z - info: ack: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.087Z - info: ack: Apple-Iphone6-1 teardown_multiplex can send data

2016-02-08T16:56:13.094Z - info: ack: Apple-IpadAir2-1 teardown_multiplex can send data

2016-02-08T16:56:13.109Z - info: ack: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.112Z - info: ack: LGE-LG-D722 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:13.116Z - info: Running on ios test: enqueue and run in order

2016-02-08T16:56:13.122Z - info: Running on android test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.137Z - info: ack: Apple-Iphone6-1 setup_enqueue and run in order

2016-02-08T16:56:13.140Z - info: ack: motorola-Nexus 6 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.154Z - info: ack: LGE-LG-D722 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.170Z - info: ack: motorola-Nexus 6 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.173Z - info: ack: LGE-LG-D722 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.198Z - info: ack: motorola-Nexus 6 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.202Z - info: ack: LGE-LG-D722 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:13.209Z - info: Running on android test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.225Z - info: ack: LGE-LG-D722 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.227Z - info: ack: motorola-Nexus 6 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.246Z - info: ack: LGE-LG-D722 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.249Z - info: ack: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.270Z - info: ack: Apple-IpadAir2-1 setup_enqueue and run in order

2016-02-08T16:56:13.276Z - info: ack: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.279Z - info: ack: LGE-LG-D722 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:13.289Z - info: Running on android test: #connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.306Z - info: ack: motorola-Nexus 6 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.309Z - info: ack: LGE-LG-D722 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.312Z - info: ack: Apple-Iphone6-1 start_test_enqueue and run in order

2016-02-08T16:56:13.330Z - info: ack: motorola-Nexus 6 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.333Z - info: ack: LGE-LG-D722 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.369Z - info: ack: motorola-Nexus 6 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.374Z - info: ack: LGE-LG-D722 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:13.377Z - info: Running on android test: should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.408Z - info: ack: motorola-Nexus 6 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.422Z - info: ack: LGE-LG-D722 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.426Z - info: ack: Apple-IpadAir2-1 start_test_enqueue and run in order

2016-02-08T16:56:13.438Z - info: ack: motorola-Nexus 6 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.440Z - info: ack: LGE-LG-D722 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.444Z - debug: Socket disconnected: transport close 7 (samsung-SM-G900F)

2016-02-08T16:56:13.468Z - info: ack: motorola-Nexus 6 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.473Z - info: ack: LGE-LG-D722 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:56:13.483Z - info: Running on android test: should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.497Z - info: ack: motorola-Nexus 6 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.523Z - info: ack: LGE-LG-D722 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.549Z - info: ack: motorola-Nexus 6 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.552Z - info: ack: LGE-LG-D722 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.578Z - info: ack: motorola-Nexus 6 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.589Z - info: ack: LGE-LG-D722 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:13.594Z - info: Running on android test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:13.607Z - info: ack: LGE-LG-D722 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:13.610Z - info: ack: motorola-Nexus 6 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:13.638Z - info: ack: motorola-Nexus 6 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:13.641Z - info: ack: LGE-LG-D722 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:13.777Z - info: ack: Apple-IpadAir2-1 teardown_enqueue and run in order

2016-02-08T16:56:14.764Z - debug: Device presented: samsung-SM-G900F (android) unittest socket:8

2016-02-08T16:56:14.766Z - info: Discarding surplus device: samsung-SM-G900F

2016-02-08T16:56:15.818Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F)

2016-02-08T16:56:16.490Z - debug: Device presented: samsung-SM-N910C (android) unittest socket:9

2016-02-08T16:56:16.491Z - info: Discarding surplus device: samsung-SM-N910C

2016-02-08T16:56:17.185Z - debug: Socket disconnected: transport close 9 (samsung-SM-N910C)

2016-02-08T16:56:20.715Z - info: ack: Apple-Iphone6-1 teardown_enqueue and run in order

2016-02-08T16:56:20.741Z - info: Running on ios test: basic

2016-02-08T16:56:20.759Z - info: ack: Apple-Iphone6-1 setup_basic

2016-02-08T16:56:21.502Z - info: ack: Apple-IpadAir2-1 setup_basic

2016-02-08T16:56:21.550Z - info: ack: Apple-IpadAir2-1 start_test_basic

2016-02-08T16:56:23.762Z - info: ack: Apple-Iphone6-1 start_test_basic

2016-02-08T16:56:23.800Z - info: ack: Apple-Iphone6-1 teardown_basic

2016-02-08T16:56:24.815Z - info: ack: Apple-IpadAir2-1 teardown_basic

2016-02-08T16:56:24.833Z - info: Running on ios test: another

2016-02-08T16:56:24.864Z - info: ack: Apple-IpadAir2-1 setup_another

2016-02-08T16:56:27.147Z - info: ack: Apple-Iphone6-1 setup_another

2016-02-08T16:56:27.184Z - info: ack: Apple-Iphone6-1 start_test_another

2016-02-08T16:56:28.993Z - info: ack: Apple-IpadAir2-1 start_test_another

2016-02-08T16:56:29.042Z - info: ack: Apple-IpadAir2-1 teardown_another

2016-02-08T16:56:30.248Z - info: ack: Apple-Iphone6-1 teardown_another

2016-02-08T16:56:30.254Z - info: Running on ios test: successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:30.269Z - info: ack: Apple-Iphone6-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:31.764Z - info: ack: Apple-IpadAir2-1 setup_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:31.804Z - info: ack: Apple-IpadAir2-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:33.295Z - info: ack: Apple-Iphone6-1 start_test_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:33.504Z - info: ack: Apple-Iphone6-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:35.149Z - info: ack: Apple-IpadAir2-1 teardown_successfully create a new pkcs12 file and return hash value

2016-02-08T16:56:35.193Z - info: Running on ios test: successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.244Z - info: ack: Apple-IpadAir2-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.285Z - info: ack: Apple-Iphone6-1 setup_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.332Z - info: ack: Apple-IpadAir2-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.445Z - info: ack: Apple-Iphone6-1 start_test_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.476Z - info: ack: Apple-Iphone6-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.482Z - info: ack: Apple-IpadAir2-1 teardown_successfully read a previous pkcs12 file and return hash value

2016-02-08T16:56:35.497Z - info: Running on ios test: failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.508Z - info: ack: Apple-IpadAir2-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.629Z - info: ack: Apple-Iphone6-1 setup_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.675Z - info: ack: Apple-IpadAir2-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.678Z - info: ack: Apple-Iphone6-1 start_test_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.801Z - info: ack: Apple-Iphone6-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.838Z - info: ack: Apple-IpadAir2-1 teardown_failed to extract public key because of corrupt pkcs12 file

2016-02-08T16:56:35.862Z - info: Running on ios test: failed to get mobile documents path

2016-02-08T16:56:35.882Z - info: ack: Apple-IpadAir2-1 setup_failed to get mobile documents path

2016-02-08T16:56:36.115Z - info: ack: Apple-Iphone6-1 setup_failed to get mobile documents path

2016-02-08T16:56:36.138Z - info: ack: Apple-Iphone6-1 start_test_failed to get mobile documents path

2016-02-08T16:56:36.141Z - info: ack: Apple-IpadAir2-1 start_test_failed to get mobile documents path

2016-02-08T16:56:36.191Z - info: ack: Apple-IpadAir2-1 teardown_failed to get mobile documents path

2016-02-08T16:56:36.312Z - info: ack: Apple-Iphone6-1 teardown_failed to get mobile documents path

2016-02-08T16:56:36.332Z - info: Running on ios test: #init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.355Z - info: ack: Apple-IpadAir2-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.465Z - info: ack: Apple-Iphone6-1 setup_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.501Z - info: ack: Apple-Iphone6-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.504Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.641Z - info: ack: Apple-Iphone6-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.644Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the peerAvailabilityChanged event

2016-02-08T16:56:36.785Z - info: Running on ios test: #init should register the networkChanged event

2016-02-08T16:56:36.801Z - info: ack: Apple-Iphone6-1 setup_#init should register the networkChanged event

2016-02-08T16:56:36.806Z - info: ack: Apple-IpadAir2-1 setup_#init should register the networkChanged event

2016-02-08T16:56:36.853Z - info: ack: Apple-IpadAir2-1 start_test_#init should register the networkChanged event

2016-02-08T16:56:36.982Z - info: ack: Apple-Iphone6-1 start_test_#init should register the networkChanged event

2016-02-08T16:56:37.133Z - info: ack: Apple-Iphone6-1 teardown_#init should register the networkChanged event

2016-02-08T16:56:37.146Z - info: ack: Apple-IpadAir2-1 teardown_#init should register the networkChanged event

2016-02-08T16:56:37.165Z - info: Running on ios test: #startBroadcasting should throw on null device name

2016-02-08T16:56:37.182Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.304Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.339Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.343Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.482Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.485Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on null device name

2016-02-08T16:56:37.502Z - info: Running on ios test: #startBroadcasting should throw on empty string device name

2016-02-08T16:56:37.520Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:37.656Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:37.849Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:40.127Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:40.173Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:46.045Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on empty string device name

2016-02-08T16:56:46.049Z - info: Running on ios test: #startBroadcasting should throw on non-number port

2016-02-08T16:56:46.190Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:56:46.480Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on non-number port

2016-02-08T16:56:46.519Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:56:48.731Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on non-number port

2016-02-08T16:56:48.777Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:56:49.544Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on non-number port

2016-02-08T16:56:49.562Z - info: Running on ios test: #startBroadcasting should throw on NaN port

2016-02-08T16:56:49.592Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:56:52.120Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on NaN port

2016-02-08T16:56:52.184Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:56:52.938Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on NaN port

2016-02-08T16:56:52.978Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:56:53.005Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on NaN port

2016-02-08T16:56:53.022Z - info: Running on ios test: #startBroadcasting should throw on negative port

2016-02-08T16:56:53.040Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.076Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.171Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.177Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.221Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.257Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on negative port

2016-02-08T16:56:53.260Z - info: Running on ios test: #startBroadcasting should throw on too large port

2016-02-08T16:56:53.280Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.286Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.328Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.444Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.491Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.596Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should throw on too large port

2016-02-08T16:56:53.599Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.618Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.629Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.666Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.782Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.863Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.950Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-02-08T16:56:53.968Z - info: Running on ios test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:53.988Z - info: ack: Apple-IpadAir2-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.109Z - info: ack: Apple-Iphone6-1 setup_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.140Z - info: ack: Apple-IpadAir2-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.148Z - info: ack: Apple-Iphone6-1 start_test_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.324Z - info: ack: Apple-IpadAir2-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.328Z - info: ack: Apple-Iphone6-1 teardown_#startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-02-08T16:56:54.446Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.461Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.472Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.508Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.633Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.675Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.787Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-02-08T16:56:54.792Z - info: Running on ios test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:54.809Z - info: ack: Apple-Iphone6-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:54.813Z - info: ack: Apple-IpadAir2-1 setup_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:54.846Z - info: ack: Apple-IpadAir2-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:54.972Z - info: ack: Apple-Iphone6-1 start_test_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:55.010Z - info: ack: Apple-Iphone6-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:55.014Z - info: ack: Apple-IpadAir2-1 teardown_#stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-02-08T16:56:55.124Z - info: Running on ios test: #connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.150Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.173Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.211Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.310Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.355Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.468Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") with a port and without an error

2016-02-08T16:56:55.472Z - info: Running on ios test: #connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.488Z - info: ack: Apple-Iphone6-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.491Z - info: ack: Apple-IpadAir2-1 setup_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.540Z - info: ack: Apple-IpadAir2-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.651Z - info: ack: Apple-Iphone6-1 start_test_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.693Z - info: ack: Apple-IpadAir2-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.804Z - info: ack: Apple-Iphone6-1 teardown_#connect should call Mobile("Connect") and handle an error

2016-02-08T16:56:55.807Z - info: Running on ios test: should call Mobile("Disconnect") without an error

2016-02-08T16:56:55.826Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:56:55.842Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") without an error

2016-02-08T16:56:55.877Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:56:55.988Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") without an error

2016-02-08T16:56:56.031Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:56:56.144Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") without an error

2016-02-08T16:56:56.147Z - info: Running on ios test: should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.163Z - info: ack: Apple-Iphone6-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.168Z - info: ack: Apple-IpadAir2-1 setup_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.205Z - info: ack: Apple-IpadAir2-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.323Z - info: ack: Apple-Iphone6-1 start_test_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.357Z - info: ack: Apple-IpadAir2-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.364Z - info: ack: Apple-Iphone6-1 teardown_should call Mobile("Disconnect") and handle an error

2016-02-08T16:56:56.482Z - info: Running on ios test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:56.501Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:56.506Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:56.544Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:56.665Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:56.982Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:57.070Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-02-08T16:56:57.073Z - info: Running on ios test: ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.108Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.336Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.395Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.552Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.600Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.887Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter calls startBroadcasting twice with error

2016-02-08T16:56:57.904Z - info: Running on ios test: ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:57.942Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.014Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.071Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.369Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.406Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.543Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on connection to bad peer

2016-02-08T16:56:58.560Z - info: Running on ios test: ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:58.640Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:58.912Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:58.968Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:59.187Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:59.225Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:59.370Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter throws on disconnect to bad peer

2016-02-08T16:56:59.389Z - info: Running on ios test: ThaliEmitter can discover and connect to peers

2016-02-08T16:56:59.426Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:56:59.534Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers

2016-02-08T16:56:59.628Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:56:59.645Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers

2016-02-08T16:57:06.366Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:57:06.373Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers

2016-02-08T16:57:06.392Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:06.426Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:06.445Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:06.467Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:06.483Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:10.674Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:11.079Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double connect

2016-02-08T16:57:11.082Z - info: Running on ios test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:11.152Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:11.175Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:11.616Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:11.698Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:16.331Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:16.414Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-02-08T16:57:16.915Z - info: Running on ios test: ThaliEmitter can connect and send data

2016-02-08T16:57:16.939Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:57:16.955Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter can connect and send data

2016-02-08T16:57:17.399Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:57:17.462Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter can connect and send data

2016-02-08T16:57:23.690Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:57:23.725Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter can connect and send data

2016-02-08T16:57:24.182Z - info: Running on ios test: ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:24.224Z - info: ack: Apple-IpadAir2-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:24.721Z - info: ack: Apple-Iphone6-1 setup_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:24.813Z - info: ack: Apple-IpadAir2-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:25.664Z - info: ack: Apple-Iphone6-1 start_test_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:33.131Z - info: ack: Apple-IpadAir2-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:33.150Z - info: ack: Apple-Iphone6-1 teardown_ThaliEmitter handles socket disconnect correctly

2016-02-08T16:57:33.177Z - info: Running on ios test: ThaliReplicationManager can call start without error

2016-02-08T16:57:33.207Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.423Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.472Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.476Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.652Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.661Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager can call start without error

2016-02-08T16:57:33.687Z - info: Running on ios test: ThaliReplicationManager receives identity

2016-02-08T16:57:33.705Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:57:33.709Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager receives identity

2016-02-08T16:57:33.946Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:57:33.952Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager receives identity

2016-02-08T16:57:33.967Z - info: ack: Apple-IpadAir2-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:57:33.999Z - info: ack: Apple-Iphone6-1 teardown_ThaliReplicationManager receives identity

2016-02-08T16:57:34.017Z - info: Running on ios test: ThaliReplicationManager replicates database

2016-02-08T16:57:34.037Z - info: ack: Apple-IpadAir2-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:57:34.047Z - info: ack: Apple-Iphone6-1 setup_ThaliReplicationManager replicates database

2016-02-08T16:57:34.069Z - info: ack: Apple-Iphone6-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:57:34.071Z - info: ack: Apple-IpadAir2-1 start_test_ThaliReplicationManager replicates database

2016-02-08T16:57:38.652Z - debug: Socket disconnected: ping timeout 0 (motorola-Nexus 6)

2016-02-08T16:58:03.443Z - debug: Socket disconnected: transport close 4 (Apple-Iphone6-1)

2016-02-08T16:58:13.813Z - debug: Socket disconnected: transport close 6 (Apple-IpadAir2-1)

2016-02-08T17:12:35.992Z - debug: Socket disconnected: transport close 1 (LGE-LG-D722)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/iOS_Iphone6-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/iOS_Iphone5-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali03_samsung-SM-G800F.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali04_samsung-SM-G900F.md)

[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali04_samsung-SM-N910C.md)

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
[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali05_motorola-Nexus 6.md)

[samsung-SM-G800H](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali05_samsung-SM-G800H.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/581356550b07fff_Remove_race_in_tests_tobybrad/thali09_LGE-Nexus 5.md)




