#### Test 513350282ff9e94_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,--------- beginning of main
D/Finsky  ( 2613): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2070:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3133): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2070/cgroup.procs: No such file or directory
W/System  ( 3133): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3133): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3188): 
D/AndroidRuntime( 3188): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3188): CheckJNI is OFF
D/AndroidRuntime( 3188): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3211 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3188): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/Icing   ( 1630): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1630): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1630): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3211): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3211): Time to load native libraries: 2 ms (timestamps 8001-8003)
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3211): Binding Chromium to main looper Looper (main, tid 1) {20694a2f}
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
I/chromium( 3211): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3211): Initializing chromium process, singleProcess=true
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3211): ApplicationContext is null in ApplicationStatus
,W/chromium( 3211): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3211): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cb01f2d:true
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3211): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3211): CordovaWebView is running on device made by: LGE
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 1474): Explicit concurrent mark sweep GC freed 10197(589KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 1.369ms total 60.402ms
D/OpenGLRenderer( 3211): Render dirty regions requested: true
D/Atlas   ( 3211): Validating map...
W/chromium( 3211): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3211): Initialized EGL, version 1.4
D/OpenGLRenderer( 3211): Enabling debug mode 0
W/BindingManager( 3211): Cannot call determinedVisibility() - never saw a connection for the pid: 3211
W/IInputConnectionWrapper( 3211): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +445ms (total +55s290ms)
D/JsMessageQueue( 3211): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3211): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3211): jxcore cordova android initializing
I/ActivityManager(  760): Killing 2583:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2583/cgroup.procs: No such file or directory
,W/jxcore-log( 3211): Initializing JXcore engine
W/jxcore-log( 3211): JXcore engine is ready
,W/jxcore-log( 3211): Starting JXcore engine
,W/.test.thalitest( 3211): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7984]" dev="sockfs" ino=7984 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3211): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3211): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9496]" dev="sockfs" ino=9496 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3211): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20018]" dev="sockfs" ino=20018 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3211): Platform android
W/jxcore-log( 3211): 
W/jxcore-log( 3211): Process ARCH arm
W/jxcore-log( 3211): 
,I/jxcore-log( 3211): JXcore Cordova bridge is ready!
I/jxcore-log( 3211): 
,W/jxcore-log( 3211): JXcore engine is started
I/chromium( 3211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3211): Toggling radios to true
I/jxcore-log( 3211): 
,D/BluetoothAdapter( 3211): enable(): BT is already enabled..!
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3211): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): my name is : LGE-Nexus 5_PT9877
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): attempting to connect to test coordinator
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): check test folder
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): found test : ./testFindPeers.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): found test : ./testReConnect.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): found test : ./testSendData.js
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Test app app.js loaded
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1474): Vacuum at: now=1448365590585 tag=VacuumService
,D/Finsky  ( 2613): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2613): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UdcCache:FPQuery( 1630): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1474): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1474): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1474): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1474):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1474): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/ClearcutLoggerApiImpl( 1576): disconnect managed GoogleApiClient
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector connect called
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Coordinator is now connected to the server!
I/jxcore-log( 3211): 
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3211): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector command called
I/jxcore-log( 3211): 
I/jxcore-log( 3211): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":16,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0}]}
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Start now : testSendData.js
I/jxcore-log( 3211): 
I/jxcore-log( 3211): stop tests now !
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 16
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): check server
I/jxcore-log( 3211): 
I/jxcore-log( 3211): serverPort is 39187
I/jxcore-log( 3211): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3211): Stoping All
I/        ( 3211): Stopping services
I/        ( 3211): Stop Bluetooth
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3211): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3211):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}
,D/WifiService(  760): New client listening to asynchronous messages
,I/        ( 3211): All stuff available and enabled
I/        ( 3211): Stoping All
I/        ( 3211): Stopping services
I/        ( 3211): Stop Bluetooth
I/        ( 3211): Starting All
I/        ( 3211): Stopping services
,I/        ( 3211): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@16f44bba
I/        ( 3211): Stopping services
,I/        ( 3211): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}
I/        ( 3211): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9877","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3211): peerDiscoveryTimer timeout value:9176
,I/        ( 3211): Stop Bluetooth
I/        ( 3211): StartBluetooth listener
I/        ( 3211): StartBluetooth listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3211): StartBroadcasting started ok
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:51:53.348Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:51:53.348Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:51:53.349Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3211): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3211): 2015-11-24T11:51:53.354Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3211): We already were running, thus doing nothing
I/        ( 3211): Added local service
I/        ( 3211): Cleared service requests
I/        ( 3211): Stopped peer discovery
I/        ( 3211): Started peer discovery
I/        ( 3211): Discovery state changed to Started.
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3211): starting to listen
I/BTListenerThread( 3211): waiting to accept incoming Connection
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/SS      ( 3211): Found 1 peers.
I/SS      ( 3211): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : samsung-SM-G900F_PT4523
I/HS      ( 3211): Hand Shake finished outgoing for : samsung-SM-G900F_PT4523
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, samsung-SM-G900F_PT4523
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 46475
I/BtConnectorHelper( 3211): Request socket is using : 46475
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :46475
I/jxcore-log( 3211): 2015-11-24T11:51:58.840Z SendDataConnector.js: CLIENT connected to 46475, error: null
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:51:58.841Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 46475
I/BtToRequestSocket( 3211): Set local streams
,I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:51:58.951Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:51:59.672Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:51:59.846Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.101Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.159Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.169Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.227Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.256Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.451Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:00.883Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:01.163Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:01.165Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:01.183Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:01.184Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:52:01.201Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:01.202Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:01.203Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:01.203Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3211): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 7818 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-l2cap( 2094): L2CAP got conn_req while connected (state:2). Reject it
,W/bt-btif ( 2094): No ag scb for peer addr
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9302
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9302
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:52:04.304Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:52:04.790Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.797Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.857Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.862Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.911Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.946Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.958Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:04.965Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.026Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.406Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.479Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.661Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.668Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.674Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.791Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.829Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.863Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:05.871Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.069Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.174Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.264Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.271Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.281Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.563Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.595Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.690Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.697Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.865Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:06.907Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.162Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.171Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.181Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.285Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.327Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.362Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.376Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.579Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.615Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x10  CID 0x42
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 6
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:52:07.707Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:07.708Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:07.709Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.784Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.792Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.882Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.915Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.947Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.975Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:07.983Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 4
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9302
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9302
I/BtToSocketBase( 3211): Close LocalOutputStream
,I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/jxcore-log( 3211): 2015-11-24T11:52:08.128Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2094): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cdca0a5:true
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: S5-1
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x45
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3211): 2015-11-24T11:52:12.712Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:12.713Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:17.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:17.729Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:17.729Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:17.730Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3211): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-l2cap( 2094): L2CAP - no CCB for conn rsp, LCID: 73 RCID: 74
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4343
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-N9005_PT4343
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BTConnectToThread( 3211): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : samsung-SM-N9005_PT4343
I/HS      ( 3211): Hand Shake finished outgoing for : samsung-SM-N9005_PT4343
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, samsung-SM-N9005_PT4343
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 48495
I/BtConnectorHelper( 3211): Request socket is using : 48495
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:52:23.020Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :48495
I/jxcore-log( 3211): 2015-11-24T11:52:23.318Z SendDataConnector.js: CLIENT connected to 48495, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:23.318Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 48495
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:52:23.339Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.432Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.454Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.460Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.473Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.490Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.499Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.505Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.544Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.570Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.573Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.648Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.716Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.738Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.777Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.808Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.851Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.863Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:52:23.896Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.902Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.915Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.925Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.940Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.946Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.984Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.987Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:23.994Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.013Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:24.013Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.015Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:24.015Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
,I/BtConnectorHelper( 3211): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:52:24.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:24.022Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:24.022Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:24.022Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3211): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 22810 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3211): 2015-11-24T11:52:24.029Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3211): 2015-11-24T11:52:24.035Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.037Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.074Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.107Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3211): 2015-11-24T11:52:24.177Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.244Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.312Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.379Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.518Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.557Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.657Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.663Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.795Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.805Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.932Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:24.966Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.069Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.209Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.219Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.281Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.347Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.414Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:25.479Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 7
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4343
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
,I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4343
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Close bt socket
,I/jxcore-log( 3211): 2015-11-24T11:52:25.640Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5124c rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 10
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:52:29.170Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:29.171Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:29.171Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3211): 2015-11-24T11:52:34.172Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:34.173Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
I/BTListenerThread( 3211): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3650","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : LGE-LG-D722_PT3650
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, LGE-LG-D722_PT3650
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:52:38.341Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.742Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.751Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.753Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.764Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.771Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.782Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.816Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.826Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.859Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.869Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.881Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.888Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.914Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.938Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.945Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.985Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.987Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:38.989Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:39.024Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:39.040Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:39.044Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:39.074Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 9
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT3650
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4d
,I/jxcore-log( 3211): 2015-11-24T11:52:39.141Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:52:39.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:39.180Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:39.180Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:52:39.180Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3211): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 3 peers.
I/SS      ( 3211): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2094): invalid rfc slot id: 12
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:53:03.348Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:03.348Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:03.349Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:53:08.350Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:08.351Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:13.359Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:13.360Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:13.360Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:13.361Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3211): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  760): Explicit concurrent mark sweep GC freed 27872(1260KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 994us total 70.091ms
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-rfcomm( 2094): PORT_StartCnf failed result:5
,W/bt-btif ( 2094): invalid rfc slot id: 13
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2094): No record of the device:null
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 9 Address: F4:F1:E1:5C:3B:E2 newState: 0
,E/BluetoothBondStateMachine( 2094): In stable state, received invalid newState: 10
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:53:14.108Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:14.109Z SendDataConnector.js: CLIENT Can not Connect: Connection to F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:14.110Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2094): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5587, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5587, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
,I/        ( 3211): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:53:19.110Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:19.111Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7476","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT7476
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-N910C_PT7476
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:53:21.659Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.059Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.068Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.075Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.097Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.108Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.141Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.176Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.202Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.210Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.227Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.235Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.243Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.276Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.290Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.362Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.382Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.406Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.416Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.458Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.490Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.510Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.521Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.529Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.545Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.586Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.598Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.608Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.646Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.666Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.680Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.691Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.700Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.744Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.761Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.772Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.795Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.817Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:22.860Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 11
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT7476
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 3211): 2015-11-24T11:53:22.963Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T11:53:24.117Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:24.118Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:24.118Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:24.119Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3211): Connecting to null, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3211): Starting to connect
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,E/BluetoothEventManager( 2676): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BTListenerThread( 3211): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT3884","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT3884
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT3884
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:53:25.745Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,E/BluetoothEventManager( 2676): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/jxcore-log( 3211): 2015-11-24T11:53:26.149Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/BTConnectToThread( 3211): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : motorola-XT1039_PT2208
I/HS      ( 3211): Hand Shake finished outgoing for : motorola-XT1039_PT2208
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, motorola-XT1039_PT2208
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 53921
I/BtConnectorHelper( 3211): Request socket is using : 53921
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :53921
I/jxcore-log( 3211): 2015-11-24T11:53:26.563Z SendDataConnector.js: CLIENT connected to 53921, error: null
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.568Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 53921
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:53:26.588Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.708Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.713Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.780Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.784Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:53:26.873Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3211): 2015-11-24T11:53:26.925Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:26.979Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3211): 2015-11-24T11:53:27.020Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:53:27.128Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.153Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.166Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.175Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.209Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.253Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.265Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.287Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.303Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/jxcore-log( 3211): 2015-11-24T11:53:27.336Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.347Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.362Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.383Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.399Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.417Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.425Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.431Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:27.432Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.449Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.455Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:53:27.472Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:27.474Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:27.474Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:27.474Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3211): Connecting to null, at 7C:F9:0E:37:96:AB
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 63411 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3211): 2015-11-24T11:53:27.481Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3211): 
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3211): 2015-11-24T11:53:27.542Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.622Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.702Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.784Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:27.788Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3211): 2015-11-24T11:53:29.269Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.280Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.324Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.333Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.342Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.348Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.384Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.397Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:29.437Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T11:53:29.665Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-btif ( 2094): invalid rfc slot id: 14
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT3884
I/BtToSocketBase( 3211): Stop ReceivingThread
,I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:53:29.780Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : samsung-SM-A500FU_PT3421
I/HS      ( 3211): Hand Shake finished outgoing for : samsung-SM-A500FU_PT3421
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, samsung-SM-A500FU_PT3421
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 49038
I/BtConnectorHelper( 3211): Request socket is using : 49038
I/BtToRequestSocket( 3211): Now accepting connections
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :49038
I/jxcore-log( 3211): 2015-11-24T11:53:30.658Z SendDataConnector.js: CLIENT connected to 49038, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:30.658Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 49038
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:53:30.677Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:53:31.041Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:31.186Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3211): 2015-11-24T11:53:31.382Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:31.666Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3211): 2015-11-24T11:53:31.858Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1039
,I/jxcore-log( 3211): 2015-11-24T11:53:33.183Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:53:33.773Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:34.428Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:34.542Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:34.710Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:34.711Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:53:34.729Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:34.730Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
,I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
I/jxcore-log( 3211): 2015-11-24T11:53:34.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:34.759Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:34.760Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:34.760Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3211): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 7237 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4b
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 18
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:53:42.409Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:42.410Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:42.410Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:53:47.411Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:47.412Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:53:52.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:52.417Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:52.417Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:52.418Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3211): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
,I/        ( 3211): Started peer discovery
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 19
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:53:57.590Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:57.590Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:53:57.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:54:02.591Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:02.591Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 9 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3211): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3211): 2015-11-24T11:54:07.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:07.598Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:07.598Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:07.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3211): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-rfcomm( 2094): PORT_StartCnf failed result:5
,W/bt-btif ( 2094): invalid rfc slot id: 20
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2094): No record of the device:null
I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 9 Address: 08:EC:A9:50:76:27 newState: 0
,E/BluetoothBondStateMachine( 2094): In stable state, received invalid newState: 10
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:54:11.919Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:11.920Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:11.920Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2094): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT884
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-A300FU_PT884
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:54:14.718Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:54:15.131Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.167Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.176Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.258Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.292Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.324Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.379Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.437Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.468Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.530Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.556Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.568Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.608Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.620Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.655Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.675Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.773Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.834Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.866Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.878Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:15.926Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.018Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.056Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.088Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.141Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.150Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.164Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.198Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.202Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.224Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.233Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.266Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.325Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.371Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.390Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.425Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.446Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.488Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.512Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.559Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.601Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.628Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.659Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:16.689Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 16
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT884
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:54:16.791Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x40
,I/jxcore-log( 3211): 2015-11-24T11:54:16.922Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:16.922Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A3-1
,I/jxcore-log( 3211): 2015-11-24T11:54:21.927Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:21.928Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:21.929Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:21.930Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3211): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 22
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:54:27.118Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:27.118Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:27.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:54:32.121Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:32.122Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 10 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3211): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3211): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3211): 2015-11-24T11:54:37.126Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:37.127Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:37.128Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:37.128Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3211): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 23
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:54:42.306Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:42.306Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:42.308Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:42.308Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:42.310Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:42.311Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:42.311Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3211): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 67547 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3211): HandshakeOk : HTC-HTC One_M8_PT3120
I/HS      ( 3211): Hand Shake finished outgoing for : HTC-HTC One_M8_PT3120
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, HTC-HTC One_M8_PT3120
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 49145
I/BtConnectorHelper( 3211): Request socket is using : 49145
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :49145
I/jxcore-log( 3211): 2015-11-24T11:54:49.184Z SendDataConnector.js: CLIENT connected to 49145, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:49.185Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 49145
,I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:54:49.222Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:54:49.360Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3211): 2015-11-24T11:54:49.364Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9857
,I/jxcore-log( 3211): 2015-11-24T11:54:49.403Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.406Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3211): 2015-11-24T11:54:49.453Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.464Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.498Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.507Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.543Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.583Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.587Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:49.606Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:49.606Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
,I/BtConnectorHelper( 3211): Disconnect outgoing peer: 50:2E:6C:AC:21:50
,I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
,I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
,I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:54:49.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:49.640Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:49.640Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:49.640Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3211): Connecting to null, at F8:CF:C5:D9:E5:61
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 7284 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5208c rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5208c rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5208c rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3211): Starting to Handshake
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3211): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3211): HandshakeOk : motorola-Nexus 6_PT5587
,I/HS      ( 3211): Hand Shake finished outgoing for : motorola-Nexus 6_PT5587
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, motorola-Nexus 6_PT5587
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 33506
I/BtConnectorHelper( 3211): Request socket is using : 33506
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :33506
I/jxcore-log( 3211): 2015-11-24T11:54:54.438Z SendDataConnector.js: CLIENT connected to 33506, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:54.438Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 33506
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:54:54.458Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:54:54.673Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3211): 2015-11-24T11:54:54.700Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:54.783Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3211): 2015-11-24T11:54:54.843Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:54.943Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:54.982Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.058Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.106Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.165Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.246Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:55.247Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.262Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:55.263Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
,I/BtConnectorHelper( 3211): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
,I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
I/jxcore-log( 3211): 2015-11-24T11:54:55.289Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:54:55.300Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:55.300Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:54:55.300Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3211): Connecting to null, at 90:E7:C4:F6:69:77
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 5607 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 26
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:55:00.440Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:00.441Z SendDataConnector.js: CLIENT Can not Connect: Connection to 90:E7:C4:F6:69:77 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:00.441Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:05.442Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:05.443Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:10.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:10.448Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:10.449Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:10.449Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3211): Connecting to null, at 90:E7:C4:F6:69:77
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : HTC-HTC One M8s_PT5271
I/HS      ( 3211): Hand Shake finished outgoing for : HTC-HTC One M8s_PT5271
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, HTC-HTC One M8s_PT5271
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 34877
I/BtConnectorHelper( 3211): Request socket is using : 34877
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :34877
I/jxcore-log( 3211): 2015-11-24T11:55:11.707Z SendDataConnector.js: CLIENT connected to 34877, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:11.708Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:11.719Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 34877
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:55:11.849Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17777
,I/jxcore-log( 3211): 2015-11-24T11:55:11.910Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10847
,I/jxcore-log( 3211): 2015-11-24T11:55:11.960Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:11.989Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3211): 2015-11-24T11:55:12.066Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.147Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.226Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.262Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.317Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.398Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:12.399Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.415Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:12.416Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 90:E7:C4:F6:69:77
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
,I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
I/jxcore-log( 3211): 2015-11-24T11:55:12.441Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.448Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:12.451Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:12.457Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3211): Connecting to A3-1, at 08:EC:A9:50:75:41
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 17099 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/ActivityManager(  760): Killing 2538:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2538/cgroup.procs: No such file or directory
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : samsung-SM-A300FU_PT884
I/HS      ( 3211): Hand Shake finished outgoing for : samsung-SM-A300FU_PT884
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, samsung-SM-A300FU_PT884
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 46730
I/BtConnectorHelper( 3211): Request socket is using : 46730
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :46730
,I/jxcore-log( 3211): 2015-11-24T11:55:43.498Z SendDataConnector.js: CLIENT connected to 46730, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:43.499Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 46730
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:55:43.524Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:55:43.651Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15797
,I/jxcore-log( 3211): 2015-11-24T11:55:43.709Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:43.716Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3211): 2015-11-24T11:55:43.765Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3211): 2015-11-24T11:55:43.900Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:43.933Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:43.986Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:44.027Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:44.126Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:44.177Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:44.178Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:44.193Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:44.195Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
,I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:55:44.230Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:44.231Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:55:44.231Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:55:44.232Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 31729 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51cfc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A3-1
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT5271","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : HTC-HTC One M8s_PT5271
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, HTC-HTC One M8s_PT5271
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:56:13.270Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:56:13.734Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.807Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.815Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.823Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.888Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.898Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.910Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:13.947Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.009Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.106Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.269Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.282Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.367Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.403Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.687Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.766Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.852Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.970Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:14.978Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.078Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.171Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.271Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.347Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.373Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:56:15.471Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.626Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.639Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:15.755Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.586Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.623Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 29
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:56:16.643Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:16.649Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:16.651Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.668Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.767Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.806Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.889Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.895Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.938Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:16.977Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.002Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.012Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.022Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.186Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.268Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.353Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:17.431Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 230f
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: S5-1
,I/jxcore-log( 3211): 2015-11-24T11:56:18.285Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:56:18.566Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:18.708Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:18.826Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:18.914Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3211): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT4523
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-G900F_PT4523
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:56:19.821Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:56:20.302Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.358Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.365Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 21
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT5271
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:56:20.500Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:56:20.630Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.723Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.780Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.816Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.827Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.832Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.859Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.870Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.876Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.907Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.937Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.947Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.961Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:20.997Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.027Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.087Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.163Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.179Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.185Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.216Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.259Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.330Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.396Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.403Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.413Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.499Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.504Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.552Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.563Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.652Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:21.653Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.700Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.879Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.983Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:21.995Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:22.002Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:22.032Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:22.067Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:22.078Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:22.115Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 30
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4523
I/BtToSocketBase( 3211): Stop ReceivingThread
,I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4523
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/jxcore-log( 3211): 2015-11-24T11:56:22.213Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/jxcore-log( 3211): 2015-11-24T11:56:26.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:26.675Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:26.676Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:26.676Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One M8s
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x10  CID 0x43
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 32
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:56:32.111Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:32.112Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:32.113Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3211): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3211): 2015-11-24T11:56:37.116Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:37.118Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:42.123Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:42.126Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:42.127Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:42.127Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 33
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:56:45.016Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:45.017Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:45.018Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T11:56:50.018Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:50.019Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:56:55.023Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:55.025Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:55.026Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:55.026Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 34
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:56:57.565Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:57.565Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:56:57.566Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T11:57:02.568Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:02.569Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:07.573Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:07.575Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:07.576Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:07.576Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 35
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:57:08.807Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:08.808Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:08.824Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:08.827Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:08.830Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:08.831Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:08.831Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3211): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 84578 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : LGE-LG-H815_PT1012
I/HS      ( 3211): Hand Shake finished outgoing for : LGE-LG-H815_PT1012
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, LGE-LG-H815_PT1012
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 35160
I/BtConnectorHelper( 3211): Request socket is using : 35160
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :35160
I/jxcore-log( 3211): 2015-11-24T11:57:10.859Z SendDataConnector.js: CLIENT connected to 35160, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:10.859Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:10.861Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 35160
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:57:11.049Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.091Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.148Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.187Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.237Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.283Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.326Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.366Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.432Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:11.433Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:11.460Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:11.461Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
I/jxcore-log( 3211): 2015-11-24T11:57:11.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/jxcore-log( 3211): 2015-11-24T11:57:11.504Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:11.505Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:11.505Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 2608 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 37
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:57:14.758Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:14.758Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:14.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G4-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T11:57:19.761Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:19.761Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G4-1
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT5587
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, motorola-Nexus 6_PT5587
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:57:22.467Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52974 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:23.018Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.041Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.048Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.088Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.096Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.106Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.137Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.170Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.225Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.246Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.274Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.277Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.297Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.305Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.344Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.348Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.384Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.386Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.389Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.421Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.472Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.489Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.573Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.582Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:23.618Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 31
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT5587
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:57:23.702Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1012
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, LGE-LG-H815_PT1012
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/jxcore-log( 3211): 2015-11-24T11:57:24.082Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52254 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:24.494Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:24.512Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:24.539Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:24.605Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:24.638Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:24.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:24.767Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:24.767Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:24.768Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3211): 2015-11-24T11:57:24.819Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:25.588Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:26.036Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/jxcore-log( 3211): 2015-11-24T11:57:26.202Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T11:57:26.312Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:26.475Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:26.511Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:26.548Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:26.560Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:26.778Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 40
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:57:26.958Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:26.959Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:26.960Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:27.735Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/jxcore-log( 3211): 2015-11-24T11:57:27.842Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3211): 2015-11-24T11:57:27.931Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:27.938Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:27.942Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:27.948Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:27.971Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.004Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:28.021Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.024Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.064Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.090Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.093Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.125Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.136Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.140Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.146Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.158Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.188Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.192Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.199Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.237Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.246Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:28.277Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52974 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): invalid rfc slot id: 38
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1012
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Close bt out
,I/BtToSocketBase( 3211): Close bt socket,
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:57:28.938Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52974 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f52974 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T11:57:31.960Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:31.961Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G4-1
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3211): 2015-11-24T11:57:36.965Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:36.966Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:36.967Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:57:36.967Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 6109
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5196c rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : motorola-XT1039_PT2208
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, motorola-XT1039_PT2208
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:57:40.991Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:57:41.429Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.436Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.442Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.487Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.578Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.739Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.813Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.821Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.848Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.859Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.870Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.906Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.943Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:41.976Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.063Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.097Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.112Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.233Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.361Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.396Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.437Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.471Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.610Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.635Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.641Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.647Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.694Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.821Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.948Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.961Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:42.967Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:57:42.990Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.000Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.048Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.081Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.089Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.116Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.128Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.206Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.266Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.318Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.419Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.489Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.515Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.525Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.651Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:57:43.796Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 39
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT2208
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:57:43.884Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4e
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1039
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f527ac rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3211): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : motorola-XT1072_PT6558
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, motorola-XT1072_PT6558
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:58:10.357Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:58:10.772Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.779Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.787Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.795Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.807Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.836Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.880Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.894Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:10.928Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.069Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.105Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.116Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.169Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.182Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.191Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.201Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.237Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.267Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.283Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.348Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.357Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.366Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.405Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.469Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.476Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.485Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.543Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.551Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.562Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.574Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.607Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.645Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.651Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:11.685Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 42
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT6558
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:58:11.731Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x44
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1072
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 41
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:58:16.015Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:16.016Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:16.016Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T11:58:21.017Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:21.018Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:26.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:26.021Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:26.022Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:26.022Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 44
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:58:26.946Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:26.946Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:26.947Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T11:58:31.947Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:31.948Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3211): 2015-11-24T11:58:36.955Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:36.956Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:36.956Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:36.957Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2094): invalid rfc slot id: 45
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:58:37.935Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.935Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.936Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.937Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.937Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.937Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:37.938Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 86432 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 230f
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 46
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:58:39.237Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:39.237Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:39.238Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:58:44.238Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:44.239Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2676): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2676): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT4812
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:58:46.775Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 3211): 2015-11-24T11:58:47.241Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.252Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.259Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.271Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.285Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.314Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.317Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.320Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.354Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.391Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.423Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.454Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.458Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.464Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.505Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.512Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.551Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.587Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:47.602Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 43
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3211): Stop ReceivingThread
,I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/jxcore-log( 3211): 2015-11-24T11:58:47.655Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3211): 2015-11-24T11:58:49.242Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:49.243Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:49.243Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:49.248Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51ec4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 48
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:58:51.726Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:51.727Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:51.727Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,W/bt-btm  ( 2094): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51ec4 rs_disc_pending=2
E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T11:58:56.727Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:58:56.728Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT3120
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, HTC-HTC One_M8_PT3120
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/jxcore-log( 3211): 2015-11-24T11:58:59.616Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T11:58:59.991Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:58:59.999Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.037Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.078Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.092Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.128Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.163Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.170Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.208Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.215Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.255Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.301Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.309Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.362Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.406Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.417Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.456Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.462Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.507Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.517Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.559Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.599Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.606Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.647Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.692Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.700Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.732Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.772Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.780Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.819Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.826Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.871Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.912Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.924Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.967Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.976Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:00.992Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.029Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.036Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.078Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.091Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.130Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.138Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.179Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.191Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.228Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.268Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.277Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.329Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.367Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:01.731Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:01.731Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:01.732Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:01.732Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f5208c rs_disc_pending=1
E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): invalid rfc slot id: 47
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT3120
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T11:59:06.552Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 50
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:59:07.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:07.404Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:07.404Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T11:59:12.406Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:12.406Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:17.409Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:17.410Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:17.411Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:17.411Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 51
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:59:18.371Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:18.372Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:18.372Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T11:59:23.373Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:23.373Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:28.380Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:28.381Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:28.382Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:28.382Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 52
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:59:29.755Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:29.755Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:29.757Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:29.758Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:29.760Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:29.760Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:29.760Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3211): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 51819 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [80:01:84:8a:b3:68]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : HTC-HTC Desire 820_PT9302
,I/HS      ( 3211): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9302
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9302
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 60930
I/BtConnectorHelper( 3211): Request socket is using : 60930
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :60930
I/jxcore-log( 3211): 2015-11-24T11:59:32.776Z SendDataConnector.js: CLIENT connected to 60930, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:32.777Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 60930
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:59:32.797Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:32.937Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:32.996Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.093Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.099Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.169Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.244Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.302Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.350Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.388Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:33.389Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:33.406Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:33.406Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:59:33.452Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:33.453Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:33.453Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:33.453Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 3211): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 3630 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [44:80:eb:7b:5a:05]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1072
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f527ac rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT6558","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : motorola-XT1072_PT6558
I/HS      ( 3211): Hand Shake finished outgoing for : motorola-XT1072_PT6558
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, motorola-XT1072_PT6558
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 43623
I/BtConnectorHelper( 3211): Request socket is using : 43623
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :43623
I/jxcore-log( 3211): 2015-11-24T11:59:35.736Z SendDataConnector.js: CLIENT connected to 43623, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:35.737Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 43623
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:59:35.767Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:59:35.874Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17777
,I/jxcore-log( 3211): 2015-11-24T11:59:36.146Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:59:36.402Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 3211): 2015-11-24T11:59:36.455Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:36.553Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/jxcore-log( 3211): 2015-11-24T11:59:36.947Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.022Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.127Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.207Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.352Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:37.353Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.368Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:37.369Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
,I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:59:37.399Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:37.400Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:37.400Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:37.400Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3211): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 3900 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3211): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT3884","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : HUAWEI-ALE-L21_PT3884
I/HS      ( 3211): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT3884
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT3884
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 41471
I/BtConnectorHelper( 3211): Request socket is using : 41471
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :41471
I/jxcore-log( 3211): 2015-11-24T11:59:39.996Z SendDataConnector.js: CLIENT connected to 41471, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:39.997Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 41471
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T11:59:40.017Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T11:59:40.258Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/        ( 3211): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5587, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5587, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3211): 2015-11-24T11:59:40.475Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 3211): 2015-11-24T11:59:40.925Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:41.077Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/jxcore-log( 3211): 2015-11-24T11:59:41.658Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: XT1072
,I/jxcore-log( 3211): 2015-11-24T11:59:41.687Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:41.793Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T11:59:41.958Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:42.173Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:42.278Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:42.279Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T11:59:42.298Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:42.299Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
,I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
,I/jxcore-log( 3211): 2015-11-24T11:59:42.331Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:42.332Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:42.332Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:42.332Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3211): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 4879 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0xd  CID 0x42
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 56
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T11:59:43.822Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:43.822Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:43.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3211): 2015-11-24T11:59:48.824Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:48.825Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 2 peers.
I/SS      ( 3211): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2015-11-24T11:59:53.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:53.829Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:53.829Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:53.830Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3211): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0xd  CID 0x48
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 57
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T11:59:56.619Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:56.619Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T11:59:56.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3539 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3539): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3539):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3539):   adb logcat -s GAv4
,W/GAv4    ( 3539): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3539): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3539): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2702:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2702/cgroup.procs: No such file or directory
,I/jxcore-log( 3211): 2015-11-24T12:00:01.621Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:01.622Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:06.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:06.627Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:06.627Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:06.628Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3211): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3211): Starting to Handshake
I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3211): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTConnectToThread( 3211): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3211): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3211): HandshakeOk : samsung-SM-A300FU_PT4812
I/HS      ( 3211): Hand Shake finished outgoing for : samsung-SM-A300FU_PT4812
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : false, samsung-SM-A300FU_PT4812
I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3211): mHTTPPort  set to : 42059
I/BtConnectorHelper( 3211): Request socket is using : 42059
I/BtToRequestSocket( 3211): Now accepting connections
,I/BtConnectorHelper( 3211): Calling ConnectionStatusUpdate with port :42059
,I/jxcore-log( 3211): 2015-11-24T12:00:07.668Z SendDataConnector.js: CLIENT connected to 42059, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:07.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): incoming data from: /127.0.0.1, port: 42059
I/BtToRequestSocket( 3211): Set local streams
I/BtToRequestSocket( 3211): rin ended ---------------------------;
,I/jxcore-log( 3211): 2015-11-24T12:00:07.689Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3211): 2015-11-24T12:00:07.841Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15797
,I/jxcore-log( 3211): 2015-11-24T12:00:07.885Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:07.891Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3211): 2015-11-24T12:00:07.993Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.052Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.128Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.157Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.196Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.235Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.287Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:08.288Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:08.304Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:08.305Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/BtConnectorHelper( 3211): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
I/BtToRequestSocket( 3211): Close server socket
I/jxcore-log( 3211): 2015-11-24T12:00:08.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:08.331Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:08.331Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:08.332Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 25956 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51ec4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51ec4 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 59
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:00:10.828Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:10.828Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:10.829Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T12:00:15.830Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:15.831Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:20.836Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:20.837Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:20.837Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:20.838Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 60
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:00:21.905Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:21.906Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:21.906Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T12:00:26.907Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:26.908Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:31.916Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:31.917Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:31.918Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:31.918Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51b34 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3211): we got incoming connection
,I/BTHandshakeSocketThread( 3211): Creating BTHandshakeSocketThread
I/BTListenerThread( 3211): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread started
,I/BTListenerThread( 3211): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3211): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3211): MESSAGE_WRITE 77 bytes.
I/HS      ( 3211): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT3421
I/BTHandshakeSocketThread( 3211): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3211): Starting the connected thread incoming : true, samsung-SM-A500FU_PT3421
,I/BtToSocketBase( 3211): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3211): Creating BTConnectedThread
,I/BtConnectorHelper( 3211): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3211): --DoOneRunRound started
,I/BtToRequestSocket( 3211): LocalHost address: localhost/127.0.0.1, port: 39187
,I/jxcore-log( 3211): 2015-11-24T12:00:33.566Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/BtToRequestSocket( 3211): --DoOneRunRound ended
,I/jxcore-log( 3211): 2015-11-24T12:00:34.104Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.199Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.208Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.215Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.232Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.240Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.250Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.287Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.312Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.320Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.330Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.358Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.398Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.403Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.411Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T12:00:34.474Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51b34 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2015-11-24T12:00:34.716Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/jxcore-log( 3211): 2015-11-24T12:00:34.745Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 61
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:00:34.759Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:34.759Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:34.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.784Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.791Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.797Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.835Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.841Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.875Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.877Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.884Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.925Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.966Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.977Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:34.983Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.019Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.030Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.066Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.089Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.094Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.105Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:00:35.145Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2094): invalid rfc slot id: 49
,I/BtToSocketBase( 3211): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3211): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3421
I/BtToSocketBase( 3211): Stop ReceivingThread
I/BtToSocketBase( 3211): Stop SendingThread
I/BtToSocketBase( 3211): Close local in
I/BtToSocketBase( 3211): Close LocalOutputStream
I/BtToSocketBase( 3211): Close localHostSocket
I/BtToSocketBase( 3211): Close bt in
I/BtToSocketBase( 3211): Close bt out
I/BtToSocketBase( 3211): Close bt socket
,I/BtToSocketBase( 3211): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3211): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3211): 2015-11-24T12:00:35.990Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4b
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): 2015-11-24T12:00:39.760Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:39.760Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51b34 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: A5-1
,I/jxcore-log( 3211): 2015-11-24T12:00:44.766Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:44.767Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:44.767Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:00:44.768Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 6 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 7 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 63
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:01:15.974Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:15.974Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:15.975Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T12:01:20.977Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:20.978Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/        ( 3211): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4343","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4343, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4343, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3211): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3211): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3211): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3211): 2015-11-24T12:01:25.981Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:25.982Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:25.983Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:25.983Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 64
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:01:31.161Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:31.161Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:01:31.164Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:01:31.166Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:31.167Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:31.167Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:31.167Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 82831 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 65
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:01:32.727Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:01:32.727Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:32.729Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3211): Found 7 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2015-11-24T12:01:37.730Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:37.731Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2015-11-24T12:01:42.733Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:42.736Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:42.736Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:42.736Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 66
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:01:43.863Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:43.863Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:43.863Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:01:48.865Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:48.866Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:01:53.868Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:53.869Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:53.869Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:53.870Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 67
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:01:54.131Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:54.131Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:54.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:01:59.131Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:01:59.131Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:02:04.134Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:04.135Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:04.135Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:04.136Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 68
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:02:05.813Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:05.813Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed,
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:05.813Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:02:10.815Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:10.816Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:02:15.820Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:15.820Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:15.821Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:15.821Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 69
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:02:17.479Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:17.479Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:02:17.481Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:17.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : F8:95:C7:87:85:54, try count now: 2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:17.483Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:17.483Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:17.483Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 46312 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 70
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:02:18.345Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:18.345Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:18.345Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:02:23.346Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:23.346Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T12:02:28.350Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:28.351Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:28.351Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:28.352Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 71
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:02:28.959Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:28.959Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:28.959Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:02:33.959Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:33.960Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 7 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3211): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3211): 2015-11-24T12:02:38.964Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:38.965Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:38.965Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:38.966Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 72
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:02:39.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:39.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:39.669Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:02:44.670Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:44.670Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3211): 2015-11-24T12:02:49.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:49.672Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:49.672Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:49.672Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 73
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:02:50.080Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:50.081Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:02:50.081Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:02:55.083Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:02:55.088Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:00.089Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:00.090Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:00.090Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:00.090Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 74
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:03:01.263Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:01.263Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:01.270Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:01.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:01.282Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:01.282Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:01.282Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 43780 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x4a
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 75
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:03:34.280Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:34.281Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:34.281Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 6 peers.
I/SS      ( 3211): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3211): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T12:03:39.283Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:39.283Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3211): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4812","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT4812, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT4812, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3211): 2015-11-24T12:03:44.289Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:44.290Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:44.290Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:44.291Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x10  CID 0x4d
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 76
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:03:49.987Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:49.988Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:49.988Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2015-11-24T12:03:54.990Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:03:54.990Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3211): Found 3 peers.
I/SS      ( 3211): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3421","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3421, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3421, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3211): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"}, typeCordovap2p._tcp.local.:
,I/        ( 3211): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9302"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9302, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9302, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3211): 2015-11-24T12:03:59.993Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:59.994Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:03:59.998Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:04:00.001Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 77
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:04:31.549Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:31.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:31.550Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:04:36.551Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:36.552Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:04:41.556Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:41.557Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:41.558Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:41.558Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 78
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:04:46.731Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:46.731Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:46.731Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:04:51.731Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:51.732Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:04:56.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:56.737Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:56.738Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:04:56.738Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 6 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/        ( 3211): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3211): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 79
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:05:31.679Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:31.680Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:31.696Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:31.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 3
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:31.701Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:31.701Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:31.701Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 150399 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 80
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:05:33.077Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:33.077Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:33.077Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:05:38.078Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:38.079Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:43.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:43.083Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:43.088Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:43.089Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 81
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:05:44.231Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:44.231Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:44.231Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:05:49.232Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:49.233Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:05:54.239Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:54.239Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:54.239Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:54.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 82
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:05:54.592Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:54.592Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:54.592Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:05:59.592Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:05:59.592Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:04.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:04.596Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:04.597Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:04.597Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 83
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:06:05.089Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:05.089Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:05.089Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:06:10.089Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:10.089Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:15.091Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.092Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.092Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.093Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3211): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2094): invalid rfc slot id: 84
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:06:15.683Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.683Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:15.685Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : F8:95:C7:87:85:54, try count now: 3
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.694Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.694Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.695Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 43982 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 85
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:06:15.932Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.932Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:15.932Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3211): 2015-11-24T12:06:20.932Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:20.933Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2015-11-24T12:06:25.936Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:25.936Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:25.937Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:25.937Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,I/        ( 3211): Cleared service requests
,I/        ( 3211): Started peer discovery
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 86
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:06:27.148Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:27.148Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:27.148Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=0
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/        ( 3211): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT2208"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT2208, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT2208, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3211): 2015-11-24T12:06:32.149Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:32.150Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:37.153Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:37.153Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:37.157Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:37.157Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 87
I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:06:37.832Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:37.832Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:37.832Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:06:42.833Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:42.838Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3211): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3211): 2015-11-24T12:06:47.841Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:47.842Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:47.842Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:47.842Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 88
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:06:49.187Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:49.187Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:49.187Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3211): 2015-11-24T12:06:54.187Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:54.188Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:59.192Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:59.193Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:06:59.193Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:06:59.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 3211): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2094): invalid rfc slot id: 89
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:07:00.138Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:00.138Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:07:00.149Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:00.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 3
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:00.149Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:00.149Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:00.150Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback round[0] time: 44445 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 90
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:07:31.381Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:31.381Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:31.382Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:07:36.382Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:36.383Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:07:41.387Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:41.387Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:41.388Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:41.388Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3211): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3211): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x10  CID 0x4a
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 91
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3211): 2015-11-24T12:07:47.739Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:47.739Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:47.740Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:07:52.741Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:52.741Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/jxcore-log( 3211): 2015-11-24T12:07:57.746Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:57.747Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:57.747Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:07:57.747Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/        ( 3211): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3211): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3211): Starting to connect
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x22  CID 0x4d
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 92
,I/BTConnectToThread( 3211): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3211): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 2015-11-24T12:08:28.670Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:08:28.670Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:08:28.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): timeout now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): dun
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): weAreDoneNow , resultArray.length: 13
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): done, now sending data to server
I/jxcore-log( 3211): 
I/jxcore-log( 3211): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): -- RESULT DATA {"name:":"LGE-Nexus 5_PT9877","time":1000072,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":7818,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":22810,"result":"OK","connections":2,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":63411,"result":"OK","connections":4,"tryCount":1},{"name":"7C:F9:0E:37:96:AB","time":7237,"result":"OK","connections":1,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":7284,"result":"OK","connections":1,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":5607,"result":"OK","connections":1,"tryCount":1},{"name":"90:E7:C4:F6:69:77","time":17099,"result":"OK","connections":2,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":31729,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":2608,"result":"OK","connections":1,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":3630,"result":"OK","connections":1,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":3900,"result":"OK","connections":1,"tryCount":1},{"na
I/jxcore-log( 3211): sendList : 100% : 63411 ms, 99% : 63411 ms, 95 : 31729 ms, 90% : 31729 ms.
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Result count 13, range 2608 ms to  63411 ms.
I/jxcore-log( 3211): 
I/jxcore-log( 3211): sendList failed peers count : 3 [18.75 %]
I/jxcore-log( 3211): 
I/jxcore-log( 3211): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 4
I/jxcore-log( 3211): 
I/jxcore-log( 3211): - Peer ID : F8:95:C7:87:85:54, Tried : 3
I/jxcore-log( 3211): 
I/jxcore-log( 3211): - Peer ID : E0:DB:10:14:E2:C0, Tried : 3
I/jxcore-log( 3211): 
I/jxcore-log( 3211): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:08:33.413Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2015-11-24T12:08:33.413Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:08:33.415Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3211): 
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3211): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 4 peers.
I/SS      ( 3211): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3211): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3211): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 3 peers.
I/SS      ( 3211): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5587, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5587, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/art     (  760): Explicit concurrent mark sweep GC freed 59778(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 938us total 69.659ms
,I/EventLogService( 1630): Aggregate from 1448365020243 (log), 1448365020243 (data)
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5587, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5587, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3211): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3211): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1012","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1012, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1012, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT5587","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT5587, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT5587, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3211): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT884","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT884, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT884, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3211): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3211): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4523","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4523, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4523, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3211): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3211): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3120","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3120, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3211): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3120, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-smp  ( 2094): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2094): Plain text(LSB ~ MSB) = 12 ba 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2094): Encrypted text(LSB ~ MSB) = c9 5f e1 29 8a d4 c1 92 e7 ee 5c ca 5a fd 4d 47 
,W/bt-btm  ( 2094): Stopping oneshot timer
,I/        ( 3211): Cleared service requests
I/        ( 3211): Started peer discovery
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3211): Found 5 peers.
I/SS      ( 3211): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3211): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3211): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3211): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3211): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3211): Added service request
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1029): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3211): Started service discovery
,I/wpa_supplicant( 1029): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1029): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/jxcore-log( 3211): DBG, CoordinatorConnector command called
I/jxcore-log( 3211): 
I/jxcore-log( 3211): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): stop tests now !
I/jxcore-log( 3211): 
I/jxcore-log( 3211): stop current!
I/jxcore-log( 3211): 
I/jxcore-log( 3211): testSendData stopped
I/jxcore-log( 3211): 
,I/        ( 3211): Stoping All
I/        ( 3211): Stopping services
I/        ( 3211): Stopping services
,I/wpa_supplicant( 1029): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1029): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3211): Stop Bluetooth
I/        ( 3211): Stop Bluetooth
I/BTListenerThread( 3211): Stopped
,I/jxcore-log( 3211): StopBroadcasting went ok
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2015-11-24T12:12:52.819Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 3211): Cleared local services
I/        ( 3211): Cleared service requests
I/        ( 3211): Stopped peer discovery
,I/jxcore-log( 3211): DBG, CoordinatorConnector command called
I/jxcore-log( 3211): 
I/jxcore-log( 3211): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:95:C7:87:3C:51\",\"time\":2608,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":3630,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":3900,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":4879,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":5607,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:37:96:AB\",\"time\":7237,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":7284,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":7818,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":17099,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":228
I/jxcore-log( 3211): ****TEST TOOK:  ms ****
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3211): 
I/jxcore-log( 3211): stop tests now !
I/jxcore-log( 3211): 
I/jxcore-log( 3211): end, event received
I/jxcore-log( 3211): 
I/jxcore-log( 3211): CoordinatorConnector close called
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3211): 
I/jxcore-log( 3211): The Coordinator has disconnected!
I/jxcore-log( 3211): 
I/jxcore-log( 3211): The Coordinator has closed!
I/jxcore-log( 3211): 
I/jxcore-log( 3211): stop tests now !
I/jxcore-log( 3211): 
I/jxcore-log( 3211): turning Radios off
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Toggling radios to false
I/jxcore-log( 3211): 
D/BluetoothAdapter( 3211): enable(): BT is already enabled..!
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime( 3676): 
D/AndroidRuntime( 3676): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3676): CheckJNI is OFF
,D/AndroidRuntime( 3676): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3211:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  760): Client connection lost with reason: 4
,I/WindowState(  760): WIN DEATH: Window{11042d9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  760): Skipping PackageSetting{37c2d737 com.example.hello/10277} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{342747fe u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{2a304646 3211:com.test.thalitest/u0a270}, curProc for 3211: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{342747fe u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{342747fe u0 com.test.thalitest/.MainActivity t214 f}
,W/GeofencerStateMachine( 1576): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 3927(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 278us total 19.703ms
,I/Keyboard.Facilitator( 1097): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1097): run()
,I/Decoder ( 1097): createOrResetDecoder
,D/VoicemailCleanupService( 1354): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1474): onCreate
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 125432(5MB) AllocSpace objects, 27(480KB) LOS objects, 24% free, 19MB/25MB, paused 326us total 73.875ms
,I/Adreno-EGL(  955): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  955): Initialized EGL, version 1.4
,I/art     (  760): Explicit concurrent mark sweep GC freed 28873(1623KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.231ms total 98.757ms
I/art     (  760): WaitForGcToComplete blocked for 19.519ms for cause Explicit
D/OpenGLRenderer(  955): Enabling debug mode 0
,I/UpdateIcingCorporaServi( 1343): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1261): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@30c9183c new=com.google.android.velvet.VelvetApplication@30c9183c
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3211 uid 10270
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3717 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator( 1097): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): run()
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = contacts
,W/ContextImpl( 3717): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1097): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1097): run(),
I/Keyboard.Facilitator.RecurringTaskScheduler( 1097): run()
I/StatsUtilsManager( 1097): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1097): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1630): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1630): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1630): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1630): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1630): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1630): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1343): UpdateCorporaTask done [took 137 ms] updated apps [took 137 ms] 
,I/LocationSettingsChecker( 1630): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1474): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1474): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Launcher( 1261): Deferring update until onResume
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1630): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1630): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1630): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1630): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1630): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1630): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1630): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3750 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1630): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1630): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1630): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/art     (  760): Explicit concurrent mark sweep GC freed 9847(463KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.224ms total 198.963ms
D/gH_CompatibleDatabase( 1630): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1630): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1630): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1261): Deferring update until onResume
,W/BaseAppContext( 1630): Using Auth Proxy for data requests.
W/BaseAppContext( 1630): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1630): App measurement is starting up
,I/Icing   ( 1630): doRemovePackageData com.test.thalitest
I/PeopleContactsSync( 1630): CP2 sync disabled
,D/AndroidRuntime( 3676): Shutting down VM
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3773 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2557:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2557/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2008:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2008/cgroup.procs: No such file or directory
,D/ExternalStorage( 3773): After updating volumes, found 1 active roots
,W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3750): Update found 7 roots in 275ms
,D/Documents( 3750): Update found 7 roots in 172ms

```
