#### Test 513350288bfb88c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 3100): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3100): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 2601): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  734): Killing 2020:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3100): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3100): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3100): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2020/cgroup.procs: No such file or directory
V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1632): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1632): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1632): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 3167): 
D/AndroidRuntime( 3167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3167): CheckJNI is OFF
D/AndroidRuntime( 3167): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3187 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3167): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
,I/ActivityManager(  734): Killing 2566:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/WebViewFactory( 3187): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2566/cgroup.procs: No such file or directory
,I/LibraryLoader( 3187): Time to load native libraries: 2 ms (timestamps 8913-8915)
,I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3187): Binding Chromium to main looper Looper (main, tid 1) {c6b8562}
,I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
,I/chromium( 3187): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3187): Initializing chromium process, singleProcess=true
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3187): ApplicationContext is null in ApplicationStatus
,W/chromium( 3187): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3187): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@312603e:true
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3187): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3187): CordovaWebView is running on device made by: LGE
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3187): Render dirty regions requested: true
,D/Atlas   ( 3187): Validating map...
,W/chromium( 3187): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3187): Initialized EGL, version 1.4
D/OpenGLRenderer( 3187): Enabling debug mode 0
,W/IInputConnectionWrapper( 3187): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +605ms (total +58s260ms)
,W/BindingManager( 3187): Cannot call determinedVisibility() - never saw a connection for the pid: 3187
,D/JsMessageQueue( 3187): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3187): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3187): jxcore cordova android initializing
,W/jxcore-log( 3187): Initializing JXcore engine
W/jxcore-log( 3187): JXcore engine is ready
,W/jxcore-log( 3187): Starting JXcore engine
,W/.test.thalitest( 3187): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6545]" dev="sockfs" ino=6545 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3187): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3187): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6670]" dev="sockfs" ino=6670 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3187): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19681]" dev="sockfs" ino=19681 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3187): Platform android
W/jxcore-log( 3187): 
W/jxcore-log( 3187): Process ARCH arm
W/jxcore-log( 3187): 
,I/jxcore-log( 3187): JXcore Cordova bridge is ready!
I/jxcore-log( 3187): 
,W/jxcore-log( 3187): JXcore engine is started
I/chromium( 3187): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  734): Killing 2520:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2520/cgroup.procs: No such file or directory
,I/jxcore-log( 3187): Toggling radios to true
I/jxcore-log( 3187): 
,D/BluetoothAdapter( 3187): enable(): BT is already enabled..!
,V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3187): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3187): 
I/jxcore-log( 3187): my name is : LGE-Nexus 5_PT6814
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): attempting to connect to test coordinator
I/jxcore-log( 3187): 
I/jxcore-log( 3187): check test folder
I/jxcore-log( 3187): 
I/jxcore-log( 3187): found test : ./testFindPeers.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): found test : ./testReConnect.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): found test : ./testSendData.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test app app.js loaded
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
I/chromium( 3187): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1452): Vacuum at: now=1448367971204 tag=VacuumService
,D/Finsky  ( 2601): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2601): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UdcCache:FPQuery( 1632): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1452): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 27081(1611KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 19MB/32MB, paused 3.602ms total 54.244ms
,D/GetConfigurationSnapshotOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1452): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1452): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1452):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1452): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector connect called
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Coordinator is now connected to the server!
I/jxcore-log( 3187): 
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3354 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3354): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3354):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3354):   adb logcat -s GAv4
,W/GAv4    ( 3354): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3354): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3354): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2680:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2680/cgroup.procs: No such file or directory
,I/jxcore-log( 3187): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector command called
I/jxcore-log( 3187): 
I/jxcore-log( 3187): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":14,"addressList":[{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0}]}
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Start now : testSendData.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): stop tests now !
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 14
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): check server
I/jxcore-log( 3187): 
I/jxcore-log( 3187): serverPort is 59049
I/jxcore-log( 3187): 
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3187): Stoping All
I/        ( 3187): Stopping services
I/        ( 3187): Stop Bluetooth
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3187): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3187):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}
,D/WifiService(  734): New client listening to asynchronous messages
,I/        ( 3187): All stuff available and enabled
,I/        ( 3187): Stoping All
I/        ( 3187): Stopping services
I/        ( 3187): Stop Bluetooth
I/        ( 3187): Starting All
I/        ( 3187): Stopping services
I/        ( 3187): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@37fee749
I/        ( 3187): Stopping services
,I/        ( 3187): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3187): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6814","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3187): peerDiscoveryTimer timeout value:5403
,I/        ( 3187): Stop Bluetooth
I/        ( 3187): StartBluetooth listener
I/        ( 3187): StartBluetooth listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3187): StartBroadcasting started ok
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:12.611Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:12.611Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:12.611Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3187): Connecting to null, at F8:95:C7:87:85:54
,I/jxcore-log( 3187): 2015-11-24T12:31:12.616Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3187): 
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3187): We already were running, thus doing nothing
I/        ( 3187): Added local service
I/        ( 3187): Cleared service requests
I/        ( 3187): Stopped peer discovery
I/        ( 3187): Started peer discovery
I/        ( 3187): Discovery state changed to Started.
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTListenerThread( 3187): starting to listen
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 5
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:31:13.691Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:13.692Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:13.693Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 1 peers.
I/SS      ( 3187): Peer(1): A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3187): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:31:18.695Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:18.697Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
,I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3187): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT7085
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT7085
,I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:31:20.156Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/jxcore-log( 3187): 2015-11-24T12:31:20.650Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.654Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.689Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.863Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.923Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.933Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:20.945Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3187): 
,I/BTListenerThread( 3187): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT8827
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, samsung-SM-A500FU_PT8827
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
,I/jxcore-log( 3187): 2015-11-24T12:31:20.994Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:31:21.022Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.029Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.035Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.102Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.108Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.146Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.161Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.170Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.243Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.249Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:31:21.288Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.292Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.298Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.303Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.356Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.374Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.381Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.389Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:21.390Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.413Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.421Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.440Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.448Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.473Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.511Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.522Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.538Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.547Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.579Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.598Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.610Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.623Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.663Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.672Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.696Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.706Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.733Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.766Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.770Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:21.814Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 4
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
,I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:31:21.844Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x44
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3187): 2015-11-24T12:31:22.200Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.207Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3187): 
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/jxcore-log( 3187): 2015-11-24T12:31:22.286Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.293Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.302Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.377Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.464Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.470Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/jxcore-log( 3187): 2015-11-24T12:31:22.635Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/BTListenerThread( 3187): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9717","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT9717
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
I/jxcore-log( 3187): 2015-11-24T12:31:22.743Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:31:22.748Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.802Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.808Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.817Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.889Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.897Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.959Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:22.969Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.051Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.073Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.110Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.113Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.137Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.168Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.180Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.184Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.249Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.260Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.317Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.387Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.428Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3187): 2015-11-24T12:31:23.493Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.503Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.514Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.549Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.568Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.587Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.609Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.643Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.678Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.703Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:23.703Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:23.704Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:23.704Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3187): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3187): 2015-11-24T12:31:23.745Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:23.776Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.067Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.080Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.093Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.099Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:85:54]: 0, 0, 0
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:31:25.164Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.180Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.199Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.218Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.243Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.251Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.287Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3187): 
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/jxcore-log( 3187): 2015-11-24T12:31:25.311Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.327Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.363Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.393Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.429Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.436Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.463Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.500Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:25.510Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 7
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3187): Close LocalOutputStream
,I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/jxcore-log( 3187): 2015-11-24T12:31:25.639Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2061): invalid rfc slot id: 6
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT8827
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:31:25.789Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@294ef25f:true
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3187): HandshakeOk : LGE-LG-D722_PT9984
,I/HS      ( 3187): Hand Shake finished outgoing for : LGE-LG-D722_PT9984
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, LGE-LG-D722_PT9984
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 55814
I/BtConnectorHelper( 3187): Request socket is using : 55814
,I/BtToRequestSocket( 3187): Now accepting connections
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x48
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :55814
I/jxcore-log( 3187): 2015-11-24T12:31:26.719Z SendDataConnector.js: CLIENT connected to 55814, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:26.719Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 55814
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:31:26.755Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:26.991Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.153Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.238Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.333Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3187): 2015-11-24T12:31:27.488Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.624Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.737Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3187): 2015-11-24T12:31:27.851Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.926Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.974Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:27.980Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:28.003Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:28.004Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
,I/BtConnectorHelper( 3187): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
,I/jxcore-log( 3187): 2015-11-24T12:31:28.016Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:28.018Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:28.018Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:28.018Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:1F:C9:5E
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 15371 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G3s-1
,I/art     (  734): Explicit concurrent mark sweep GC freed 24907(1128KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.423ms total 115.468ms
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
,I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3187): HandshakeOk : samsung-SM-N9005_PT8756
I/HS      ( 3187): Hand Shake finished outgoing for : samsung-SM-N9005_PT8756
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, samsung-SM-N9005_PT8756
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 33011
I/BtConnectorHelper( 3187): Request socket is using : 33011
I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :33011
I/jxcore-log( 3187): 2015-11-24T12:31:34.869Z SendDataConnector.js: CLIENT connected to 33011, error: null
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:34.870Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 33011
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:31:34.891Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.634Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.699Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.760Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.815Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.884Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.928Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:35.989Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:36.029Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:36.144Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:36.149Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:36.150Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:36.172Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:36.173Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
,I/BtConnectorHelper( 3187): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
,I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:31:36.200Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:36.203Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:36.203Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:36.204Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3187): Connecting to null, at 90:E7:C4:F6:69:77
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 8132 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3187): HandshakeOk : HTC-HTC One M8s_PT9674
I/HS      ( 3187): Hand Shake finished outgoing for : HTC-HTC One M8s_PT9674
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, HTC-HTC One M8s_PT9674
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 48923
I/BtConnectorHelper( 3187): Request socket is using : 48923
I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :48923
I/jxcore-log( 3187): 2015-11-24T12:31:47.422Z SendDataConnector.js: CLIENT connected to 48923, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:47.423Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 48923
I/BtToRequestSocket( 3187): Set local streams
,I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:31:47.449Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3187): 2015-11-24T12:31:47.709Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 3187): 2015-11-24T12:31:47.863Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:47.888Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 3187): 2015-11-24T12:31:47.956Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:48.028Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:48.123Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:48.199Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:48.291Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:48.292Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:48.309Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:48.313Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
,I/BtConnectorHelper( 3187): Disconnect outgoing peer: 90:E7:C4:F6:69:77
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:31:48.338Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:48.343Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:48.344Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:48.345Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3187): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 12089 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9717","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : HUAWEI-ALE-L21_PT9717
I/HS      ( 3187): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT9717
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT9717
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 50371
,I/BtConnectorHelper( 3187): Request socket is using : 50371
,I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :50371
I/jxcore-log( 3187): 2015-11-24T12:31:51.550Z SendDataConnector.js: CLIENT connected to 50371, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:51.551Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 50371
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:31:51.570Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3187): 2015-11-24T12:31:51.798Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:51.842Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3187): 2015-11-24T12:31:51.891Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:51.982Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3187): 2015-11-24T12:31:52.085Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:52.094Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/jxcore-log( 3187): 2015-11-24T12:31:52.273Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC One M8s
,I/jxcore-log( 3187): 2015-11-24T12:31:52.496Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:52.503Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:52.564Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:52.565Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:52.582Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:52.582Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/BtConnectorHelper( 3187): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
,I/jxcore-log( 3187): 2015-11-24T12:31:52.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:52.612Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:52.612Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:52.613Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3187): Connecting to null, at F8:95:C7:87:3C:51
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 4221 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
,I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9595","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : LGE-LG-H815_PT9595
I/HS      ( 3187): Hand Shake finished outgoing for : LGE-LG-H815_PT9595
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, LGE-LG-H815_PT9595
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 58134
I/BtConnectorHelper( 3187): Request socket is using : 58134
I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :58134
I/jxcore-log( 3187): 2015-11-24T12:31:56.834Z SendDataConnector.js: CLIENT connected to 58134, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:31:56.834Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 58134
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:31:56.857Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1,
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3187): 2015-11-24T12:31:57.383Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:31:57.715Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2061): dm_pm_timer expires
W/bt-btif ( 2061): dm_pm_timer expires 0
W/bt-btif ( 2061): proc dm_pm_timer expires
,I/jxcore-log( 3187): 2015-11-24T12:32:07.721Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:07.722Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:07.723Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:07.724Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:07.725Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3187): 
,I/BtToSocketBase( 3187): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3187): Disconnect outgoing peer: LGE-LG-H815_PT9595
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 3187): 2015-11-24T12:32:12.725Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:32:12.729Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 1 peers.
I/SS      ( 3187): Peer(1): A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3187): 2015-11-24T12:32:17.741Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:17.741Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:17.742Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:32:17.743Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9595","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9595","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT9595, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT9595, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3187): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(4): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x43
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 14
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:33:17.722Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:33:17.722Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:33:17.723Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,I/jxcore-log( 3187): 2015-11-24T12:33:22.726Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:33:22.727Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:33:27.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:33:27.731Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:33:27.732Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:33:27.732Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3187): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 15
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:34:20.740Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:20.741Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:20.742Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:34:25.749Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:25.750Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3187): 2015-11-24T12:34:30.754Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:30.755Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:30.758Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:30.761Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 16
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:34:31.972Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:31.973Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:31.974Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,I/jxcore-log( 3187): 2015-11-24T12:34:36.974Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:36.975Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:41.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:41.978Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:41.979Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:41.980Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 17
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:34:43.003Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:43.004Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:43.005Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:43.007Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:43.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:43.009Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:43.009Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:43.009Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3187): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 170392 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-l2cap( 2061): L2CAP - no CCB for conn rsp, LCID: 72 RCID: 74
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
,I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT7562
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, samsung-SM-G900F_PT7562
,I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
,I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:34:49.453Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BTConnectToThread( 3187): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : samsung-SM-G900F_PT7562
I/HS      ( 3187): Hand Shake finished outgoing for : samsung-SM-G900F_PT7562
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, samsung-SM-G900F_PT7562
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 43342
I/BtConnectorHelper( 3187): Request socket is using : 43342
I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :43342
,I/jxcore-log( 3187): 2015-11-24T12:34:49.780Z SendDataConnector.js: CLIENT connected to 43342, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:49.781Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 43342
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:34:49.800Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.037Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.043Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.120Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.209Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.214Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.522Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.608Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.729Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.895Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.914Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:50.920Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:51.060Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:51.247Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:51.857Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:52.165Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3187): 2015-11-24T12:34:53.134Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.516Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.598Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.691Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.780Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.946Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:53.954Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:54.031Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:54.189Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:54.558Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:54.559Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:54.578Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:54.578Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/BtConnectorHelper( 3187): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
,I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:34:54.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:54.614Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:54.614Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:34:54.614Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 11550 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3187): 2015-11-24T12:34:54.621Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3187): 
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3187): 2015-11-24T12:34:54.630Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:55.828Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:34:55.938Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:55.944Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3187): 2015-11-24T12:34:55.954Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.030Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.247Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.555Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.679Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.800Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.900Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.939Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:56.999Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.208Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.223Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.545Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.577Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.730Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.815Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.827Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.910Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:57.951Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:58.011Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:58.112Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:58.123Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:58.204Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:58.239Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3187): 
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/jxcore-log( 3187): 2015-11-24T12:34:58.617Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3187): 2015-11-24T12:34:59.001Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.008Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.018Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.115Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.127Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.205Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:34:59.209Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 8
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT7562
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
,I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT7562
I/BtToSocketBase( 3187): Close LocalOutputStream
,I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x4a
,I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/jxcore-log( 3187): 2015-11-24T12:34:59.410Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: S5-1
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2061): PORT_StartCnf failed result:5
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2061): invalid rfc slot id: 20
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 2061): onReceive
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:35:07.745Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:07.749Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:07.749Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3187): 2015-11-24T12:35:12.751Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:12.751Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:17.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:17.755Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:17.760Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:17.763Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3187): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 21
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:35:22.932Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:22.933Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:22.933Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3187): 2015-11-24T12:35:27.935Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:27.935Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3187): 2015-11-24T12:35:32.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:32.942Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:32.943Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:32.943Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3187): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : samsung-SM-A300FU_PT6406
I/HS      ( 3187): Hand Shake finished outgoing for : samsung-SM-A300FU_PT6406
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, samsung-SM-A300FU_PT6406
,I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 32965
I/BtConnectorHelper( 3187): Request socket is using : 32965
,I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :32965
I/jxcore-log( 3187): 2015-11-24T12:35:34.892Z SendDataConnector.js: CLIENT connected to 32965, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:34.893Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 32965
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:35:34.918Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3187): 2015-11-24T12:35:35.204Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:35.278Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3187): 2015-11-24T12:35:35.379Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:35.490Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3187): 2015-11-24T12:35:35.562Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:35.691Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:35.801Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:35.881Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:35:36.121Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:36.247Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:36.248Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:36.265Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:36.266Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/BtConnectorHelper( 3187): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
,I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:35:36.293Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:36.295Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:36.300Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:36.303Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 41634 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 2 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 23
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:35:41.267Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:41.268Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:41.269Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3187): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:35:46.270Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:46.270Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 79 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT283
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, HTC-HTC One_M8_PT283
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
,I/jxcore-log( 3187): 2015-11-24T12:35:50.150Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:35:50.666Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.735Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.805Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.835Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.843Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.885Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:50.927Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.012Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.041Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.054Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.061Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.087Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.127Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.165Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.213Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:35:51.248Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.271Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:51.271Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:51.271Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:35:51.271Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3187): 2015-11-24T12:35:51.327Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.333Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.359Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.366Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.396Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.505Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.516Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3187): 2015-11-24T12:35:51.558Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.603Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3187): 2015-11-24T12:35:51.641Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3187): 
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/jxcore-log( 3187): 2015-11-24T12:35:51.662Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3187): 
D/WifiP2pManager( 3187): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/jxcore-log( 3187): 2015-11-24T12:35:51.698Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.738Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.770Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.873Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.947Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:51.962Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.008Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.123Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.252Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.299Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.314Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.439Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.463Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.472Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.507Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.571Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.588Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.628Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/jxcore-log( 3187): 2015-11-24T12:35:52.685Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.722Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.765Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:35:52.846Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 19
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT283
I/BtToSocketBase( 3187): Stop ReceivingThread
,I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT283
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Close bt socket
,I/jxcore-log( 3187): 2015-11-24T12:35:53.011Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x42
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 25
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:36:00.771Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:00.772Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:00.773Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(3): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3187): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:36:05.773Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:05.774Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3187): 2015-11-24T12:36:10.780Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:10.780Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:10.781Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:10.781Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 26
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:36:11.262Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:11.262Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:11.263Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:36:16.264Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:16.265Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/jxcore-log( 3187): 2015-11-24T12:36:21.272Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:21.273Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:21.281Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:21.281Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 27
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:36:24.894Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:24.895Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:24.901Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:36:29.903Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:29.904Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:36:34.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:34.911Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:34.911Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:34.912Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 28
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:36:36.621Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:36.622Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:36.638Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:36.641Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:36.644Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:36.645Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:36.645Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 60322 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x49
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 29
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:36:37.838Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:37.839Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:37.839Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3187): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3187): 2015-11-24T12:36:42.841Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:42.843Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:36:47.849Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:47.849Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:47.850Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:47.850Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3187): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9984","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9984, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9984, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8827","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT8827, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT8827, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0xd  CID 0x46
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 30
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:36:58.799Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:58.800Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:36:58.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT6406
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, samsung-SM-A300FU_PT6406
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
,I/jxcore-log( 3187): 2015-11-24T12:37:03.095Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:37:03.540Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.549Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.560Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.566Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.578Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.609Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.622Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.629Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.639Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.669Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.688Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.698Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.707Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.748Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.776Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.792Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.801Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:03.802Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.829Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.839Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.850Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.890Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.924Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.930Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.968Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.975Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:03.989Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:04.000Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:04.030Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:04.041Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:04.080Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:04.091Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 24
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT6406
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 3187): 2015-11-24T12:37:04.166Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/        ( 3187): Started service discovery
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3187): 2015-11-24T12:37:08.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:08.806Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:08.806Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:08.807Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 32
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:37:13.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:13.993Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:13.993Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:18.995Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:18.995Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:24.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:24.004Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:24.004Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:24.005Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 33
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:37:29.183Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:29.183Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:29.184Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 3187): 2015-11-24T12:37:34.185Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:34.186Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:39.190Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:39.190Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:39.191Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:39.191Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 34
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:37:44.371Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:44.372Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:37:44.388Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:44.391Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:44.394Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:44.394Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:37:44.395Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3187): Connecting to null, at 44:80:EB:7B:5A:05
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 67728 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 35
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:38:18.232Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:18.233Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:18.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:23.236Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:23.237Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3187): Found Service, :{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"} -- peerIdentifier:90:E7:C4:F6:69:77, peerName: HTC-HTC One M8s_PT9674, peerAddress: 90:E7:C4:F6:69:77
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 90:E7:C4:F6:69:77, Name: HTC-HTC One M8s_PT9674, WifiDirectName: Android_608e, WifiDirect Address: 92:e7:c4:e6:4c:f8, peerId: 90:E7:C4:F6:69:77
,I/jxcore-log( 3187): 2015-11-24T12:38:28.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:28.241Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:28.241Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:28.242Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3187): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
,I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 3187): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : motorola-XT1072_PT4007
I/HS      ( 3187): Hand Shake finished outgoing for : motorola-XT1072_PT4007
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, motorola-XT1072_PT4007
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 48964
I/BtConnectorHelper( 3187): Request socket is using : 48964
I/BtToRequestSocket( 3187): Now accepting connections
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :48964
I/jxcore-log( 3187): 2015-11-24T12:38:33.480Z SendDataConnector.js: CLIENT connected to 48964, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:33.480Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 48964
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:38:33.483Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3187): 2015-11-24T12:38:34.144Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3187): 2015-11-24T12:38:34.281Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:34.650Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3187): 2015-11-24T12:38:35.083Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:35.502Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:36.941Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:37.140Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:37.856Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:38.260Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:38:38.693Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:38.694Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:38.710Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:38.711Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/BtConnectorHelper( 3187): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:38:38.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:38.740Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:38.740Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:38.741Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 54301 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x41
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 37
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:38:39.335Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:39.338Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:39.341Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 8 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: XT1072
,I/jxcore-log( 3187): 2015-11-24T12:38:44.345Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:44.346Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:49.351Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:49.351Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:49.352Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:49.352Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x42
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 38
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:38:51.962Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:51.963Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:38:51.964Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:56.964Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:38:56.965Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3187): 2015-11-24T12:39:01.972Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:01.972Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:01.973Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:01.973Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 9 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(9): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x43
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 39
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:39:24.039Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:24.040Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:24.040Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:39:29.041Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:29.042Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 9 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(7): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(9): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3187): 2015-11-24T12:39:34.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:34.048Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:34.048Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:34.049Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 8 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3187): Cleared service requests
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x45
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 40
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:39:55.698Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:55.699Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:39:55.700Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:40:00.700Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:00.701Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 8 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3187): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3187): Peer(6): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3187): 2015-11-24T12:40:05.704Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:05.705Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:05.705Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:05.710Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/EventLogService( 1632): Aggregate from 1448367014974 (log), 1448367014974 (data)
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 7 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(7): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x47
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2061): invalid rfc slot id: 41
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:40:29.545Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:29.548Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:29.575Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:29.583Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 1
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:29.584Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:29.584Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:29.585Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 3187): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 110814 ms, rnd: 5, ex: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Cleared service requests
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started peer discovery
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTConnectToThread( 3187): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3187): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : HTC-HTC Desire 820_PT7085
I/HS      ( 3187): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT7085
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT7085
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 38976
I/BtConnectorHelper( 3187): Request socket is using : 38976
I/BtToRequestSocket( 3187): Now accepting connections
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :38976
I/jxcore-log( 3187): 2015-11-24T12:40:31.751Z SendDataConnector.js: CLIENT connected to 38976, error: null
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:31.751Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 38976
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:40:31.770Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 7 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(7): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:40:36.288Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:37.369Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:37.778Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:37.955Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:38.120Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:38.380Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:38.661Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:38.865Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:39.337Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:39.463Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:39.464Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:39.483Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:39.484Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
,I/BtConnectorHelper( 3187): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:40:39.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:39.514Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:39.514Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:39.515Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3187): Connecting to null, at F8:CF:C5:D9:E5:61
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 9880 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2061): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2061): Entering PendingCommandState State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 2061): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2061): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2061): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2061): StableState(): Entering Off State
,W/BluetoothEventManager( 2655): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2655): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2061): L2CAP - no CCB for conn rsp, LCID: 74 RCID: 67
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3187): Starting to Handshake
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3187): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT89
I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, motorola-Nexus 6_PT89
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:40:50.340Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BTConnectToThread( 3187): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3187): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3187): HandshakeOk : motorola-Nexus 6_PT89
I/HS      ( 3187): Hand Shake finished outgoing for : motorola-Nexus 6_PT89
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : false, motorola-Nexus 6_PT89
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3187): mHTTPPort  set to : 36823
I/BtConnectorHelper( 3187): Request socket is using : 36823
I/BtToRequestSocket( 3187): Now accepting connections
,I/BtConnectorHelper( 3187): Calling ConnectionStatusUpdate with port :36823
,I/jxcore-log( 3187): 2015-11-24T12:40:50.675Z SendDataConnector.js: CLIENT connected to 36823, error: null
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.680Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): incoming data from: /127.0.0.1, port: 36823
I/BtToRequestSocket( 3187): Set local streams
I/BtToRequestSocket( 3187): rin ended ---------------------------;
,I/jxcore-log( 3187): 2015-11-24T12:40:50.700Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.751Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.777Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.783Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.790Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.835Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.866Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.909Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.924Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3187): 2015-11-24T12:40:50.963Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:50.997Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.003Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.074Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.079Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.084Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.091Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.127Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3187): 2015-11-24T12:40:51.142Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.150Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.185Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,D/        ( 2061): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3187): 2015-11-24T12:40:51.251Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.257Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.275Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.282Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.306Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.309Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.316Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.348Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.436Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.442Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.480Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.488Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.495Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.500Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.527Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.537Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.548Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.594Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.603Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.668Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.708Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.716Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.724Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.757Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.789Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.804Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.813Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:51.814Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:40:51.829Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:51.830Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3187): 
I/BtConnectorHelper( 3187): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
I/BtToRequestSocket( 3187): Close server socket
I/jxcore-log( 3187): 2015-11-24T12:40:51.855Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:51.864Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:51.864Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:51.864Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 12300 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2061): invalid rfc slot id: 31
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT89
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:40:51.875Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 45
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:40:54.157Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:54.157Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:54.158Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:40:59.159Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:40:59.160Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:04.162Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:04.163Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:04.164Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:04.164Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 46
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:41:04.922Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:04.923Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:04.924Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:41:09.925Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:09.929Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3187): 2015-11-24T12:41:14.934Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:14.935Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:14.939Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:14.940Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 47
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:41:15.782Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:15.783Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:15.783Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [90:e7:c4:f6:69:77]: 7, f, 2205
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/BTListenerThread( 3187): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9674","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : HTC-HTC One M8s_PT9674
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, HTC-HTC One M8s_PT9674
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
,I/jxcore-log( 3187): 2015-11-24T12:41:19.417Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:41:19.833Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.877Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.887Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.909Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.917Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.929Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.939Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.974Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:19.980Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.032Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.069Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.081Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.119Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.126Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.161Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.198Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.218Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.249Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.260Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.287Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.307Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.327Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.344Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.377Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.390Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.401Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.415Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.498Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.503Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.521Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.546Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): invalid rfc slot id: 44
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT9674
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:41:20.670Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:41:20.784Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:20.784Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x40
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: HTC One M8s
,I/jxcore-log( 3187): 2015-11-24T12:41:25.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:25.789Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:25.789Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:41:25.790Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3187): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(5): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 1 peers.
I/SS      ( 3187): Peer(1): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 49
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:42:17.654Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:17.654Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:17.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:42:22.662Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:42:22.663Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(4): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:,
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3187): 2015-11-24T12:42:27.666Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:27.666Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:27.667Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:27.667Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 50
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:42:29.232Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.233Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:42:29.249Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.252Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.254Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.255Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:42:29.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 97370 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [f8:95:c7:87:3c:51]: 7, f, 230f
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,I/        ( 3187): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 51
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:42:29.918Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:29.918Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: G4-1
,I/jxcore-log( 3187): 2015-11-24T12:42:34.918Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:34.918Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:42:39.921Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:39.922Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:39.922Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:42:39.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3187): Peer(4): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 52
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:43:32.002Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:32.003Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:32.004Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [44:80:eb:7b:5a:05]: 7, f, 2205
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: XT1072
,I/jxcore-log( 3187): 2015-11-24T12:43:37.004Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:37.004Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/BTListenerThread( 3187): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : motorola-XT1072_PT4007
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/        ( 3187): Started service discovery
I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, motorola-XT1072_PT4007
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/jxcore-log( 3187): 2015-11-24T12:43:37.662Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
,I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:43:38.072Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.117Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.159Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.225Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.264Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.395Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.417Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.492Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.493Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.504Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.531Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.655Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.764Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3187): 2015-11-24T12:43:38.949Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:38.980Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.001Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.098Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.332Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.457Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.564Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.668Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.681Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.707Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:39.792Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3187): 2015-11-24T12:43:40.074Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.090Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.100Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.139Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.314Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.321Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.417Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6406","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT6406, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT6406, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3187): 2015-11-24T12:43:40.633Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.935Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.942Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.960Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:40.970Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.238Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.279Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.360Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.513Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.622Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.665Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.864Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.871Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:41.959Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:43:42.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:42.008Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:42.008Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:42.009Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
,W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3187): 2015-11-24T12:43:42.076Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,W/bt-btif ( 2061): dm_pm_timer expires
W/bt-btif ( 2061): dm_pm_timer expires 0
W/bt-btif ( 2061): proc dm_pm_timer expires
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 7 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(5): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(7): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 54
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:43:52.059Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:52.059Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:52.060Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3187): 2015-11-24T12:43:57.062Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:43:57.062Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:02.066Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:02.067Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:02.067Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:02.068Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 55
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:44:07.244Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:07.244Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:07.245Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:12.249Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:12.249Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/jxcore-log( 3187): 2015-11-24T12:44:17.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:17.253Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:17.254Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:17.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3187): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 56
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:44:22.435Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:22.438Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:22.456Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:22.459Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:22.461Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:22.462Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:22.462Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 113186 ms, rnd: 5, ex: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 57
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:44:25.207Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:25.208Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:25.208Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:44:30.209Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:30.210Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:35.214Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:35.214Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:35.215Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:35.215Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 58
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:44:40.397Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:40.398Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:40.399Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 3187): 2015-11-24T12:44:45.399Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:45.400Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:50.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:50.405Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:50.410Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:44:50.410Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 59
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:44:52.022Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:52.023Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:52.023Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/UsageStatsService(  734): User[0] Flushing usage stats to disk
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:44:57.025Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:44:57.027Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:45:02.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:02.031Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:02.031Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:02.032Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): invalid rfc slot id: 48
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT4007
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:45:06.117Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 60
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:45:07.044Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:07.045Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:07.045Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:45:12.052Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:12.053Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 3187): 2015-11-24T12:45:17.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:17.059Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:17.059Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:17.060Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3187): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 61
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:45:18.531Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:18.531Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:18.549Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:18.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:18.554Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:18.555Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:18.555Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 56070 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 62
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:45:19.972Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:19.972Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:19.973Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=0
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:45:24.974Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:24.974Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:45:29.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:29.981Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:29.981Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:29.982Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
,I/        ( 3187): Started peer discovery
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 63
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:45:31.433Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:31.433Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:31.434Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3187): 2015-11-24T12:45:36.434Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:36.435Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3187): 2015-11-24T12:45:41.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:41.439Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:41.440Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:41.440Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 64
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:45:42.941Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:42.941Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:42.941Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,I/jxcore-log( 3187): 2015-11-24T12:45:47.942Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:47.943Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2061): new conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2061): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3187): we got incoming connection
I/BTHandshakeSocketThread( 3187): Creating BTHandshakeSocketThread
I/BTListenerThread( 3187): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread started
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 3187): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3187): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3187): MESSAGE_WRITE 77 bytes.
I/HS      ( 3187): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT8756
I/BTHandshakeSocketThread( 3187): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3187): Starting the connected thread incoming : true, samsung-SM-N9005_PT8756
I/BtToSocketBase( 3187): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3187): Creating BTConnectedThread
I/BtConnectorHelper( 3187): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3187): --DoOneRunRound started
,I/BtToRequestSocket( 3187): LocalHost address: localhost/127.0.0.1, port: 59049
I/BtToRequestSocket( 3187): --DoOneRunRound ended
,I/jxcore-log( 3187): 2015-11-24T12:45:50.510Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3187): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/jxcore-log( 3187): 2015-11-24T12:45:50.999Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.018Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.030Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.063Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.070Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.099Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.137Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.139Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.164Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.169Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.173Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.188Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.227Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.249Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.260Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.299Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.316Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.348Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.363Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.387Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.396Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.409Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.428Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.478Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.488Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.522Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.560Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.582Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.613Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:45:51.646Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 2061): invalid rfc slot id: 53
,I/BtToSocketBase( 3187): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3187): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT8756
I/BtToSocketBase( 3187): Stop ReceivingThread
I/BtToSocketBase( 3187): Stop SendingThread
I/BtToSocketBase( 3187): Close local in
I/BtToSocketBase( 3187): Close LocalOutputStream
I/BtToSocketBase( 3187): Close localHostSocket
I/BtToSocketBase( 3187): Close bt in
I/BtToSocketBase( 3187): Close bt out
I/BtToSocketBase( 3187): Close bt socket
,I/BtToSocketBase( 3187): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3187): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3187): 2015-11-24T12:45:51.793Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,W/bt-rfcomm( 2061): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2061): RFCOMM_DisconnectInd LCID:0x43
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3187): 2015-11-24T12:45:52.947Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:52.948Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:52.949Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:52.949Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, f, 6109
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 66
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:45:57.016Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:57.016Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:45:57.016Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,I/jxcore-log( 3187): 2015-11-24T12:46:02.017Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:02.018Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:07.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:07.021Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:07.022Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:07.022Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3187): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 67
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:46:08.549Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:08.550Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:08.560Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:08.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:08.565Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:08.578Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:08.583Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 49995 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2061): onReceive
,I/BTConnectionReceiver( 1345): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1345): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x48
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 68
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:46:25.900Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:25.900Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:25.901Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:30.902Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:30.903Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:46:35.908Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:35.909Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:35.910Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:35.910Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 69
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:46:41.082Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:41.083Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:41.083Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/jxcore-log( 3187): 2015-11-24T12:46:46.084Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:46.085Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:46:51.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:51.088Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:51.089Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:51.089Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x49
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 70
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:46:52.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:52.250Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:52.250Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3187): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(4): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT8756","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT8756, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT8756, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3187): 2015-11-24T12:46:57.251Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:46:57.252Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:02.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:02.257Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:02.258Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:02.258Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 71
I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:47:07.432Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:07.432Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:07.433Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3187): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(5): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3187): 2015-11-24T12:47:12.434Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:12.434Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:17.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:17.438Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:17.438Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:17.439Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3187): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3187): Added service request
,I/        ( 3187): Started service discovery
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4c
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 72
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:47:19.145Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:19.152Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:19.171Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:19.172Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- round done--------
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): do fake peer & start
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:19.173Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:19.173Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:19.173Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback round[0] time: 70575 ms, rnd: 5, ex: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3187): timeout now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): dun
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): weAreDoneNow , resultArray.length: 9
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): done, now sending data to server
I/jxcore-log( 3187): 
I/jxcore-log( 3187): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): -- RESULT DATA {"name:":"LGE-Nexus 5_PT6814","time":1000165,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":15371,"result":"OK","connections":2,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":8132,"result":"OK","connections":1,"tryCount":1},{"name":"90:E7:C4:F6:69:77","time":12089,"result":"OK","connections":1,"tryCount":1},{"name":"58:2A:F7:ED:96:BE","time":4221,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":11550,"result":"OK","connections":1,"tryCount":1},{"name":"08:EC:A9:50:76:27","time":41634,"result":"OK","connections":3,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":54301,"result":"OK","connections":2,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":9880,"result":"OK","connections":1,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":12300,"result":"OK","connections":1,"tryCount":1},{"connections":2,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":2,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":2,"name":"08:EC
,I/jxcore-log( 3187): sendList : 100% : 54301 ms, 99% : 54301 ms, 95 : 54301 ms, 90% : 41634 ms.
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Result count 9, range 4221 ms to  54301 ms.
I/jxcore-log( 3187): 
I/jxcore-log( 3187): sendList failed peers count : 5 [35.714285714285715 %]
I/jxcore-log( 3187): 
I/jxcore-log( 3187): - Peer ID : E0:DB:10:14:E2:C0, Tried : 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): - Peer ID : F8:95:C7:87:3C:51, Tried : 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): - Peer ID : 08:EC:A9:50:75:41, Tried : 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): - Peer ID : 50:2E:6C:AC:21:50, Tried : 2
I/jxcore-log( 3187): 
I/jxcore-log( 3187): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:47:52.695Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:47:52.696Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-smp  ( 2061): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2061): Plain text(LSB ~ MSB) = cf fa 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2061): Encrypted text(LSB ~ MSB) = 1e 46 e8 8d f6 b2 f8 de f2 4b 38 78 ca 4e 58 dd 
W/bt-btm  ( 2061): Stopping oneshot timer
,W/bt-sdp  ( 2061): SDP - Rcvd conn cnf with error: 0x8  CID 0x4d
E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 73
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:48:10.969Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:10.969Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:10.970Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:48:15.971Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:15.972Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 1 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3187): 2015-11-24T12:48:20.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:20.978Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:20.979Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:20.979Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 74
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:48:21.584Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:48:21.585Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:48:21.595Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3187): 2015-11-24T12:48:26.598Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:26.598Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:48:31.602Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:31.602Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:48:31.603Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:31.603Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 75
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:48:32.545Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:32.548Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): 2015-11-24T12:48:32.553Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
I/SS      ( 3187): Found 2 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2061): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=0
E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2061): bta_dm_check_av:0
,W/bt-btif ( 2061): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3187): 2015-11-24T12:48:37.553Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:37.554Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/jxcore-log( 3187): 2015-11-24T12:48:42.559Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:42.559Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:42.560Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:42.560Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 76
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3187): 2015-11-24T12:48:43.442Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:43.443Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:43.443Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3187): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3187): 2015-11-24T12:48:48.444Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:48.445Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3187): 2015-11-24T12:48:53.453Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:53.453Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:53.454Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:53.454Z SendDataConnector.js: do connect now
I/jxcore-log( 3187): 
,I/        ( 3187): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3187): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3187): Starting to connect
W/BluetoothAdapter( 3187): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2061): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2061): info:x10
,D/        ( 2061): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2061): process_service_search_attr_rsp
,E/bt-btif ( 2061): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2061): invalid rfc slot id: 77
,I/BTConnectToThread( 3187): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3187): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3187): 2015-11-24T12:48:54.018Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:54.019Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:54.020Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:48:54.022Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3187): 
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 2061): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2061): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
,I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 5 peers.
I/SS      ( 3187): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3187): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4007","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT4007, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT4007, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 6 peers.
I/SS      ( 3187): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3187): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3187): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT89","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT89, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT89, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3187): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT7562","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT7562, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT7562, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3187): Found 3 peers.
I/SS      ( 3187): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(3): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7085"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT7085, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT7085, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3187): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3187): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT283","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT283, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3187): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT283, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3187): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(4): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 3187): Cleared service requests
I/        ( 3187): Started peer discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3187): Found 4 peers.
I/SS      ( 3187): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3187): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3187): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3187): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3187): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3187): Added service request
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3187): Started service discovery
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3187): DBG, CoordinatorConnector command called
I/jxcore-log( 3187): 
I/jxcore-log( 3187): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): stop tests now !
I/jxcore-log( 3187): 
I/jxcore-log( 3187): stop current!
I/jxcore-log( 3187): 
I/jxcore-log( 3187): testSendData stopped
I/jxcore-log( 3187): 
I/        ( 3187): Stoping All
I/        ( 3187): Stopping services
I/        ( 3187): Stopping services
,I/        ( 3187): Stop Bluetooth
,I/        ( 3187): Stop Bluetooth
I/BTListenerThread( 3187): Stopped
,I/jxcore-log( 3187): StopBroadcasting went ok
I/jxcore-log( 3187): 
I/jxcore-log( 3187): 2015-11-24T12:52:12.153Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3187): 
I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3187): DBG, CoordinatorConnector command called
I/jxcore-log( 3187): 
I/jxcore-log( 3187): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":4221,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":8132,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":9880,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":11550,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":12089,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":12300,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:95:C7:87:85:54\",\"time\":15371,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"08:EC:A9:50:76:27\",\"time\":41634,\"result\":\"OK\",\"connections\":3,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":54301,\"result\":\"OK\",\"connections\":2,\"tryCount\":1}],\"sendError\":{\"failedPeer\":[{\"conn
I/jxcore-log( 3187): ****TEST TOOK:  ms ****
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3187): 
I/jxcore-log( 3187): stop tests now !
I/jxcore-log( 3187): 
I/jxcore-log( 3187): end, event received
I/jxcore-log( 3187): 
I/jxcore-log( 3187): CoordinatorConnector close called
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3187): 
I/jxcore-log( 3187): The Coordinator has disconnected!
I/jxcore-log( 3187): 
I/jxcore-log( 3187): The Coordinator has closed!
I/jxcore-log( 3187): 
I/jxcore-log( 3187): stop tests now !
I/jxcore-log( 3187): 
I/jxcore-log( 3187): turning Radios off
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Toggling radios to false
I/jxcore-log( 3187): 
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c640f98 mBinding = false
,D/BluetoothManagerService(  734): Message: 2
,D/BluetoothManagerService(  734): Sending off request.
,D/BluetoothAdapterState( 2061): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2061): Setting state to 13
I/BluetoothAdapterState( 2061): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2061): onBluetoothDisable()
I/BluetoothAdapterState( 2061): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2061): Scan Mode:20
,D/BluetoothAdapterState( 2061): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2061): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2061): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2061): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2061): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2061): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2061): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2061): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2061): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2061): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2061): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2061): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 2061): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  734): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2061): onReceive
D/BluetoothMapService( 2061): STATE_TURNING_OFF
V/BluetoothMapService( 2061): Handler(): got msg=4
D/BluetoothMapService( 2061): MAP Service closeService in
D/BluetoothMapMasInstance( 2061): MAP Service shutdown
V/BluetoothMapService( 2061): MAP Service closeService out
,I/BtOppRfcommListener( 2061): stopping Accept Thread
,I/BtOppRfcommListener( 2061): BluetoothSocket listen thread finished
,I/chromium( 3187): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 2655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2655): finishStartingService: stopping service
,D/BluetoothPbap( 2655): Proxy object disconnected
,D/PbapServerProfile( 2655): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1452): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_userial( 2061): RX termination
W/bt_userial( 2061): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2061): Leaving userial_read_thread()
,W/bt-btif ( 2061): ag scb idx 1 not allocated
E/bt-btif ( 2061): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2061): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2061): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 2061): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2061): hw_epilog_process
I/bt_userial_vendor( 2061): device fd = 53 close
,I/GKI_LINUX( 2061): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2061): GKI_exit_task 0 done
I/GKI_LINUX( 2061): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2061): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2061): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
,D/HeadsetStateMachine( 2061): Exit Disconnected: -1
D/BluetoothHeadset( 1227): Proxy object disconnected
D/BluetoothHeadset( 2655): Proxy object disconnected
D/HeadsetProfile( 2655): Bluetooth service disconnected
,D/BluetoothHeadset( 1180): Proxy object disconnected
D/BluetoothHeadset( 1180): Proxy object disconnected
,D/A2dpService( 2061): Received stop request...Stopping profile...
,D/BluetoothHeadset(  734): Proxy object disconnected
D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
D/A2dpStateMachine( 2061): Exit Disconnected: -1
,D/BluetoothA2dp(  734): Proxy object disconnected
,D/BluetoothA2dp( 2655): Proxy object disconnected
D/A2dpProfile( 2655): Bluetooth service disconnected
D/HidService( 2061): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
,D/BluetoothInputDevice( 2655): Proxy object disconnected
D/HidProfile( 2655): Bluetooth service disconnected
,D/HeadsetStateMachine( 2061): Unbinding service...
,D/BluetoothAdapterState( 2061): Stopping profile services that were post enabled
,W/BluetoothHeadsetServiceJni( 2061): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 2061): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2061): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
,I/GKI_LINUX( 2061): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2061): GKI_exit_task 2 done
I/GKI_LINUX( 2061): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/PanService( 2061): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
,W/BluetoothHidServiceJni( 2061): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2061): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2061): Cleaning up Bluetooth GID callback object
D/BtGatt.DebugUtils( 2061): handleDebugAction() action=null
,D/BtGatt.GattService( 2061): Received stop request...Stopping profile...
D/BtGatt.GattService( 2061): stop()
D/BtGatt.AdvertiseManager( 2061): advertise clients cleared
,D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
D/BluetoothPan( 2655): BluetoothPAN Proxy object disconnected
D/PanProfile( 2655): Bluetooth service disconnected
,D/BluetoothMapService( 2061): Received stop request...Stopping profile...
D/BluetoothMapService( 2061): stop()
,D/BluetoothMapEmailAppObserver( 2061): deinitObservers()
D/BluetoothMapEmailAppObserver( 2061): removeReceiver()
,D/BluetoothAdapterService( 2061): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1837d6f3
,D/BluetoothMap( 2655): Proxy object disconnected
,D/MapProfile( 2655): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 2061): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2061): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2061): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2061): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2061): Handler(): got msg=4
,D/BluetoothMapService( 2061): MAP Service closeService in
V/BluetoothMapService( 2061): MAP Service closeService out
D/BluetoothMapService( 2061): cleanup()
D/BluetoothMapService( 2061): MAP Service closeService in
V/BluetoothMapService( 2061): MAP Service closeService out
,D/BluetoothAdapterState( 2061): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2061): Setting state to 10
I/BluetoothAdapterState( 2061): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 2061): Entering OffState
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 2655): onBluetoothStateChange: up=false
,D/BluetoothPbap( 2655): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1227): onBluetoothStateChange: up=false
,D/BluetoothMap( 2655): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2655): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  734): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2655): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  734): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  734): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  734): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c640f98 mBinding = false
,D/BluetoothManagerService(  734): Sending unbind request.
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  899): 575987732: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 575987732: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 575987732: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1572): 1032490673: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1572): 1032490673: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2061): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2061): GKI_exit_task 1 done
I/GKI_LINUX( 2061): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2061): cleanupNative: return from cleanup
W/ContextImpl( 2655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 2061): System.exit called, status: 0
I/AndroidRuntime( 2061): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 2655): finishStartingService: stopping service
,D/AndroidRuntime( 3592): 
D/AndroidRuntime( 3592): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3592): CheckJNI is OFF
,I/ActivityManager(  734): Process com.android.bluetooth (pid 2061) has died
,D/AndroidRuntime( 3592): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3187:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  734): Skipping PackageSetting{12be3b0a com.example.hello/10277} due to missing metadata
,I/WindowState(  734): WIN DEATH: Window{1fb554ee u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  734): Client connection lost with reason: 4
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{14eafe9a u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  734): Spurious death for ProcessRecord{2c7d0e2d 3187:com.test.thalitest/u0a270}, curProc for 3187: null
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{14eafe9a u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  734): Duplicate finish request for ActivityRecord{14eafe9a u0 com.test.thalitest/.MainActivity t214 f}
,W/GeofencerStateMachine( 1572): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1088): resetDictionaries() : en_US
I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1271): Explicit concurrent mark sweep GC freed 3935(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.112ms total 42.865ms
,D/BluetoothAdapter( 2655): 649824925: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/Keyboard.Facilitator.DecoderInitializer( 1088): run()
,I/ActivityManager(  734): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3649 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/art     ( 1345): Explicit concurrent mark sweep GC freed 86664(3MB) AllocSpace objects, 19(375KB) LOS objects, 25% free, 19MB/25MB, paused 350us total 132.035ms
,I/art     (  734): Explicit concurrent mark sweep GC freed 78708(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 1.484ms total 129.125ms
,I/art     (  734): WaitForGcToComplete blocked for 38.271ms for cause Explicit
,I/Decoder ( 1088): createOrResetDecoder
,I/ConfigService( 1452): onCreate
,W/InputMethodManagerService(  734): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3825f512 (uid=10034 pid=949)
,W/ResourcesManager( 3649): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1088): run()
,D/AdapterServiceConfig( 3649): Adding HeadsetService
D/AdapterServiceConfig( 3649): Adding A2dpService
D/AdapterServiceConfig( 3649): Adding HidService
D/AdapterServiceConfig( 3649): Adding HealthService
D/AdapterServiceConfig( 3649): Adding PanService
D/AdapterServiceConfig( 3649): Adding GattService
D/AdapterServiceConfig( 3649): Adding BluetoothMapService
I/ActivityManager(  734): Killing 2540:com.google.android.gm/u0a70 (adj 15): empty #17
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1088): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1088): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1088): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1088): run()
I/StatsUtilsManager( 1088): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1088): shouldRecordStats() = Too Soon
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  734): Explicit concurrent mark sweep GC freed 8168(378KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.299ms total 160.009ms
,D/AuthorizationBluetoothService( 1452): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2540/cgroup.procs: No such file or directory
,D/VoicemailCleanupService( 1370): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1345): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1271): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1837d6f3 new=com.google.android.velvet.VelvetApplication@1837d6f3
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3681 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
,I/Launcher( 1271): Deferring update until onResume
,D/AndroidRuntime( 3592): Shutting down VM
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1345): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
,W/ContextImpl( 3681): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1632): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1632): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1452): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1452): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1632): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1271): Deferring update until onResume
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1632): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3712 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1632): App measurement is starting up
,I/PeopleContactsSync( 1632): CP2 sync disabled
,I/Icing   ( 1632): doRemovePackageData com.test.thalitest
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3734 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1959:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1959/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 2701:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10060/pid_2701/cgroup.procs: No such file or directory
,D/ExternalStorage( 3734): After updating volumes, found 1 active roots
,W/ResourcesManager( 3100): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3100): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3712): Update found 7 roots in 221ms

```
