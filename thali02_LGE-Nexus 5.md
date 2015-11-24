#### Test 5133502860beea6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3094): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3094):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3094):   adb logcat -s GAv4
W/GAv4    ( 3094): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3094): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3094): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3094): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2606): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  733): Killing 2024:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3094): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3094): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2024/cgroup.procs: No such file or directory
V/JNIHelp ( 3094): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 3094): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3094): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1441): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1603): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1603): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1603): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 3174): 
D/AndroidRuntime( 3174): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3174): CheckJNI is OFF
D/AndroidRuntime( 3174): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3195 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3174): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 3195): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3195): Time to load native libraries: 1 ms (timestamps 1168-1169)
I/LibraryLoader( 3195): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3195): Binding Chromium to main looper Looper (main, tid 1) {3da353ba}
I/LibraryLoader( 3195): Expected native library version number "",actual native library version number ""
I/chromium( 3195): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3195): Initializing chromium process, singleProcess=true
W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3195): ApplicationContext is null in ApplicationStatus
,W/chromium( 3195): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3195): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3195): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3195): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39b23b86:true
,W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3195): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3195): CordovaWebView is running on device made by: LGE
,W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3195): Render dirty regions requested: true
,D/Atlas   ( 3195): Validating map...
,W/chromium( 3195): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3195): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3195): Enabling debug mode 0
,I/ActivityManager(  733): Killing 2569:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/Keyboard.Facilitator( 1063): onFinishInput()
,W/BindingManager( 3195): Cannot call determinedVisibility() - never saw a connection for the pid: 3195
W/IInputConnectionWrapper( 3195): showStatusIcon on inactive InputConnection
,W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2569/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +518ms (total +60s565ms)
,D/JsMessageQueue( 3195): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3195): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391936
D/JX-Cordova( 3195): jxcore cordova android initializing
,W/jxcore-log( 3195): Initializing JXcore engine
W/jxcore-log( 3195): JXcore engine is ready
,W/jxcore-log( 3195): Starting JXcore engine
,W/.test.thalitest( 3195): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6586]" dev="sockfs" ino=6586 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3195): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3195): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6706]" dev="sockfs" ino=6706 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3195): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20509]" dev="sockfs" ino=20509 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3195): Platform android
W/jxcore-log( 3195): 
W/jxcore-log( 3195): Process ARCH arm
W/jxcore-log( 3195): 
,I/jxcore-log( 3195): JXcore Cordova bridge is ready!
I/jxcore-log( 3195): 
W/jxcore-log( 3195): JXcore engine is started
,I/Choreographer( 3195): Skipped 119 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3195): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3195): Toggling radios to true
I/jxcore-log( 3195): 
,D/BluetoothAdapter( 3195): enable(): BT is already enabled..!
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3195): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3195): 
I/jxcore-log( 3195): my name is : LGE-Nexus 5_PT6925
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): attempting to connect to test coordinator
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): check test folder
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): found test : ./testFindPeers.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): found test : ./testReConnect.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): found test : ./testSendData.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test app app.js loaded
I/jxcore-log( 3195): 
,I/chromium( 3195): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,V/GLSActivity( 1441): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1441): Vacuum at: now=1448361371146 tag=VacuumService
,D/Finsky  ( 2606): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2606): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UdcCache:FPQuery( 1603): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1441): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1441): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1441): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1441): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1441):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1441): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1063): run()
I/Keyboard.Facilitator( 1063): flushDynamicLanguageModels()
,I/ConfigService( 1441): onCreate
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/ConfigService( 1441): onDestroy
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/ClearcutLoggerApiImpl( 1553): disconnect managed GoogleApiClient
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,E/DataBuffer( 1441): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29b0aa46)
,E/DataBuffer( 1441): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c3e0407)
,E/DataBuffer( 1441): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c0934)
E/DataBuffer( 1441): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@225f35d)
E/DataBuffer( 1441): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@113d24d2)
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector connect called
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Coordinator is now connected to the server!
I/jxcore-log( 3195): 
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3195): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector command called
I/jxcore-log( 3195): 
I/jxcore-log( 3195): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":16,"addressList":[{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Start now : testSendData.js
I/jxcore-log( 3195): 
I/jxcore-log( 3195): stop tests now !
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 16
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): check server
I/jxcore-log( 3195): 
I/jxcore-log( 3195): serverPort is 45968
I/jxcore-log( 3195): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3195): Stoping All
I/        ( 3195): Stopping services
I/        ( 3195): Stop Bluetooth
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3195): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3195):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}
,D/WifiService(  733): New client listening to asynchronous messages
,I/        ( 3195): All stuff available and enabled
I/        ( 3195): Stoping All
I/        ( 3195): Stopping services
I/        ( 3195): Stop Bluetooth
I/        ( 3195): Starting All
I/        ( 3195): Stopping services
I/        ( 3195): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@1df5ef81
,I/        ( 3195): Stopping services
,I/        ( 3195): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3195): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6925","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3195): peerDiscoveryTimer timeout value:6479
,I/        ( 3195): Stop Bluetooth
I/        ( 3195): StartBluetooth listener
I/        ( 3195): StartBluetooth listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3195): StartBroadcasting started ok
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:34.543Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:34.544Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:34.544Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:1F:C9:5E
,I/jxcore-log( 3195): 2015-11-24T10:41:34.549Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 3195): 
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3195): We already were running, thus doing nothing
I/        ( 3195): Added local service
I/        ( 3195): Cleared service requests
,I/        ( 3195): Stopped peer discovery
I/        ( 3195): Started peer discovery
I/        ( 3195): Discovery state changed to Started.
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3195): starting to listen
I/BTListenerThread( 3195): waiting to accept incoming Connection
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2065): No record of the device:null
I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 9 Address: E0:DB:10:1F:C9:5E newState: 0
,E/BluetoothBondStateMachine( 2065): In stable state, received invalid newState: 10
,I/SS      ( 3195): Found 1 peers.
I/SS      ( 3195): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,W/bt-rfcomm( 2065): PORT_StartCnf failed result:5
E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2065): Do not find the bg connection mask for the remote device
,W/bt-btif ( 2065): invalid rfc slot id: 5
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:41:35.994Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:35.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:35.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3195): 2015-11-24T10:41:40.996Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:40.997Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/jxcore-log( 3195): 2015-11-24T10:41:46.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:46.013Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:46.014Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:46.015Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  733): Explicit concurrent mark sweep GC freed 25100(1154KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 894us total 63.208ms
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,I/BTConnectToThread( 3195): Starting to Handshake
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : samsung-SM-N9005_PT6575
I/HS      ( 3195): Hand Shake finished outgoing for : samsung-SM-N9005_PT6575
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, samsung-SM-N9005_PT6575
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 44962
I/BtConnectorHelper( 3195): Request socket is using : 44962
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :44962,
,I/jxcore-log( 3195): 2015-11-24T10:41:47.717Z SendDataConnector.js: CLIENT connected to 44962, error: null
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:47.724Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 44962
I/BtToRequestSocket( 3195): Set local streams
,I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:41:47.750Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:47.947Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:47.996Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.080Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.143Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.180Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.199Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.254Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.365Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.422Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.492Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.497Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:41:48.534Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:48.534Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:41:48.540Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:48.541Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:48.541Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:48.541Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3195): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 13966 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3195): Found 4 peers.
I/SS      ( 3195): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(3): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3195): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37218a0:true
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: Note3-1
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3195): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT1757
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, samsung-SM-G900F_PT1757
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BtToRequestSocket( 3195): Creating BTConnectedThread
,I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/jxcore-log( 3195): 2015-11-24T10:41:57.845Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:41:58.290Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.484Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.509Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.518Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.530Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.592Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.621Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.702Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.721Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.745Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.762Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.791Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.803Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.829Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.841Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.884Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:58.896Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.020Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.036Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.069Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.169Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.291Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3195): 
,I/BTConnectToThread( 3195): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : motorola-XT1039_PT179
I/HS      ( 3195): Hand Shake finished outgoing for : motorola-XT1039_PT179
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 3195): 2015-11-24T10:41:59.311Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, motorola-XT1039_PT179
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 51916
,I/BtConnectorHelper( 3195): Request socket is using : 51916
,I/BtToRequestSocket( 3195): Now accepting connections
,I/jxcore-log( 3195): 2015-11-24T10:41:59.343Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.378Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.385Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.389Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.428Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.516Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.520Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.559Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.562Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.567Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.599Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3195): 
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :51916
I/jxcore-log( 3195): 2015-11-24T10:41:59.631Z SendDataConnector.js: CLIENT connected to 51916, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:41:59.632Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 51916
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:41:59.656Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:41:59.975Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.113Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.127Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.160Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.170Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.193Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.200Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.227Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.238Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.271Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:00.286Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 4
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT1757
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT1757
I/BtToSocketBase( 3195): Close LocalOutputStream
,I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 3195): 2015-11-24T10:42:00.429Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3195): 2015-11-24T10:42:00.592Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3195): 2015-11-24T10:42:01.136Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: S5-1
,I/jxcore-log( 3195): 2015-11-24T10:42:04.737Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3195): 2015-11-24T10:42:07.004Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.067Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.090Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.196Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.226Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.316Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.401Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:07.402Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:07.417Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:07.418Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:42:07.441Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:07.443Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:07.444Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:07.444Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3195): Connecting to null, at 44:80:EB:7B:5A:05
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 18861 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 9
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:42:12.851Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:12.851Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:12.852Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:1f:c9:5e]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT6575
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, samsung-SM-N9005_PT6575
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:42:16.755Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.152Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.160Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.167Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.182Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.193Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.231Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.245Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.255Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.265Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.301Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.314Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.351Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.363Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.373Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.412Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.426Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.451Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.462Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.469Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.489Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.530Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.543Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.559Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:17.591Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 8
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT6575
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:42:17.655Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 3195): 2015-11-24T10:42:17.854Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:17.855Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3195): 2015-11-24T10:42:22.864Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:22.865Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:22.866Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:22.866Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3195): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : motorola-XT1072_PT8689
I/HS      ( 3195): Hand Shake finished outgoing for : motorola-XT1072_PT8689
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, motorola-XT1072_PT8689
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 43963
I/BtConnectorHelper( 3195): Request socket is using : 43963
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :43963
,I/jxcore-log( 3195): 2015-11-24T10:42:28.945Z SendDataConnector.js: CLIENT connected to 43963, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:28.946Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 43963
I/BtToRequestSocket( 3195): Set local streams
,I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:42:28.967Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3195): 2015-11-24T10:42:29.170Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:29.366Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3195): 2015-11-24T10:42:29.480Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:29.647Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3195): 2015-11-24T10:42:29.903Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:29.972Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:29.984Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:30.151Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:30.594Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:30.603Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:30.604Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:30.619Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:30.619Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
,I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:42:30.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:30.653Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:30.654Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:30.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 90:E7:C4:F6:69:77, name: null
,I/        ( 3195): Connecting to null, at 90:E7:C4:F6:69:77
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 23160 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1072
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : HTC-HTC One M8s_PT4125
I/HS      ( 3195): Hand Shake finished outgoing for : HTC-HTC One M8s_PT4125
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, HTC-HTC One M8s_PT4125
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 56938
I/BtConnectorHelper( 3195): Request socket is using : 56938
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :56938
,I/jxcore-log( 3195): 2015-11-24T10:42:53.537Z SendDataConnector.js: CLIENT connected to 56938, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:53.541Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 56938
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:42:53.564Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3195): 2015-11-24T10:42:54.002Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.115Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11837
,I/jxcore-log( 3195): 2015-11-24T10:42:54.157Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3195): 2015-11-24T10:42:54.267Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.318Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.402Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.439Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.759Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.924Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:54.925Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.940Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:54.941Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: 90:E7:C4:F6:69:77
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
I/jxcore-log( 3195): 2015-11-24T10:42:54.966Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:54.977Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:54.982Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:54.983Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3195): Connecting to null, at 80:01:84:8A:B3:68
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 24273 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : HTC-HTC Desire 820_PT6481
I/HS      ( 3195): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT6481
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT6481
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 37290
I/BtConnectorHelper( 3195): Request socket is using : 37290
I/BtToRequestSocket( 3195): Now accepting connections
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :37290
I/jxcore-log( 3195): 2015-11-24T10:42:57.742Z SendDataConnector.js: CLIENT connected to 37290, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:57.743Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 37290
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:42:57.765Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.134Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.209Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.382Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.477Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.555Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/jxcore-log( 3195): 2015-11-24T10:42:58.635Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One M8s
,I/jxcore-log( 3195): 2015-11-24T10:42:58.793Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.883Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:58.924Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
,I/jxcore-log( 3195): 2015-11-24T10:42:58.987Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:58.988Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:59.005Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:59.006Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/BtConnectorHelper( 3195): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
I/jxcore-log( 3195): 2015-11-24T10:42:59.036Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:42:59.046Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:59.046Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:42:59.047Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3195): Connecting to null, at 00:F4:6F:30:E0:6C
I/        ( 3195): Started peer discovery
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 4011 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/SS      ( 3195): Found 3 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/        ( 3195): Started service discovery
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 4 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3195): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(4): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3195): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1372","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT1372, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT1372, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(5): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x8  CID 0x46
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 14
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:43:50.492Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:43:50.493Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:43:50.493Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:43:55.495Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:43:55.495Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 3195): 2015-11-24T10:44:00.501Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:00.502Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:00.502Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:00.503Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3195): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT6835"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : samsung-SM-G800F_PT6835
I/HS      ( 3195): Hand Shake finished outgoing for : samsung-SM-G800F_PT6835
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, samsung-SM-G800F_PT6835
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 49290
I/BtConnectorHelper( 3195): Request socket is using : 49290
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :49290
I/jxcore-log( 3195): 2015-11-24T10:44:04.486Z SendDataConnector.js: CLIENT connected to 49290, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:04.487Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 49290
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:44:04.517Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:05.167Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:05.302Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:05.766Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:05.937Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:06.125Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:06.667Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:06.803Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:07.053Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:07.187Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:07.220Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:07.221Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:07.236Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:07.236Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/BtConnectorHelper( 3195): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
,I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:44:07.263Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:07.265Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:07.266Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3195): 2015-11-24T10:44:07.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3195): Connecting to null, at 50:2E:6C:AC:21:50
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 68175 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT1941","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT1941
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT1941
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
,I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/jxcore-log( 3195): 2015-11-24T10:44:13.121Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:44:13.554Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.563Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.571Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.616Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.628Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.687Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.699Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.746Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.753Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.762Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.811Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.818Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.887Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.954Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:13.990Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.104Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.141Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.171Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.240Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.251Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.310Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.374Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.433Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.490Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.531Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.585Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.644Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.649Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.696Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.730Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.744Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.825Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.877Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.894Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.935Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.944Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.984Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.991Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:14.999Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 10
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT1941
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:44:15.119Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4a
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 16
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:44:19.249Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:19.249Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:19.249Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:24.249Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:24.249Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:29.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:29.254Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:29.255Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:29.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3195): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 3195): Found 2 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : HTC-HTC One_M8_PT5312
I/HS      ( 3195): Hand Shake finished outgoing for : HTC-HTC One_M8_PT5312
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, HTC-HTC One_M8_PT5312
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 51241
,I/BtConnectorHelper( 3195): Request socket is using : 51241
,I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :51241
I/jxcore-log( 3195): 2015-11-24T10:44:39.729Z SendDataConnector.js: CLIENT connected to 51241, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:39.730Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 51241
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:44:39.750Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3195): 2015-11-24T10:44:40.475Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:40.489Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15797
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,I/jxcore-log( 3195): 2015-11-24T10:44:40.574Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,E/BluetoothEventManager( 2662): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3195): 2015-11-24T10:44:40.654Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/jxcore-log( 3195): 2015-11-24T10:44:40.711Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/BTListenerThread( 3195): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT3547
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, samsung-SM-A500FU_PT3547
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
,I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:44:40.796Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:44:40.813Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:40.929Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:40.977Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.215Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.227Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.234Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:44:41.298Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.310Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.316Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.343Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.348Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.384Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.424Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.462Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.478Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:41.480Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:41.481Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.496Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:41.502Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/BtConnectorHelper( 3195): Disconnect outgoing peer: 50:2E:6C:AC:21:50
,I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
,I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:44:41.517Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:41.519Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:41.519Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:41.519Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:3C:51
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 34215 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3195): 2015-11-24T10:44:41.523Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3195): 
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:44:43.152Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.190Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.206Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.215Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.278Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.289Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.361Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.481Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.483Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.494Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.620Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.660Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.778Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.786Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.866Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:43.935Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.069Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.124Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.178Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.211Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.247Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.361Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.382Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.437Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.502Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.511Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.560Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.566Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.580Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.627Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3195): 2015-11-24T10:44:44.695Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:44.700Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2065): invalid rfc slot id: 17
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT3547
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:44:44.903Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-btm  ( 2065): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=2
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x40
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A5-1
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : LGE-LG-H815_PT8697
,I/HS      ( 3195): Hand Shake finished outgoing for : LGE-LG-H815_PT8697
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, LGE-LG-H815_PT8697
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 53473
I/BtConnectorHelper( 3195): Request socket is using : 53473
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :53473
I/jxcore-log( 3195): 2015-11-24T10:44:52.534Z SendDataConnector.js: CLIENT connected to 53473, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:44:52.534Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 53473
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:44:52.579Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:44:53.523Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:53.796Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:54.133Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:54.475Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3195): 2015-11-24T10:44:54.956Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:55.361Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:56.993Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:44:57.004Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-btif ( 2065): dm_pm_timer expires
W/bt-btif ( 2065): dm_pm_timer expires 0
,W/bt-btif ( 2065): proc dm_pm_timer expires
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect outgoing peer: LGE-LG-H815_PT8697
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,W/bt-btif ( 2065): invalid rfc slot id: 20
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,I/jxcore-log( 3195): 2015-11-24T10:45:07.006Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:07.007Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:07.007Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:07.012Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:07.016Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3,
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1039
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : motorola-XT1039_PT179
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, motorola-XT1039_PT179
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:45:07.569Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:07.980Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:07.989Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:07.995Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.001Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.007Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.016Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.053Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.076Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.082Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.140Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.180Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.191Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data,
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.251Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.290Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.299Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.337Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.370Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.455Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.491Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.495Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.515Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.586Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.604Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.613Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.621Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.630Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.670Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.698Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.705Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.712Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.723Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.761Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.797Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.809Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.841Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:08.895Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 19
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT179
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:45:09.291Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  733): Killing 2521:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2521/cgroup.procs: No such file or directory
,I/jxcore-log( 3195): 2015-11-24T10:45:12.017Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:12.017Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:12.017Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1039
,I/jxcore-log( 3195): 2015-11-24T10:45:17.021Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:17.022Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:17.023Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:17.024Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3195): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT1620, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT1620, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3195): Cleared service requests
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3195): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3195): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT1620, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT1620, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-rfcomm( 2065): PORT_StartCnf failed result:5
,E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 2065): invalid rfc slot id: 22
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 2065): Do not find the bg connection mask for the remote device
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothMapService( 2065): onReceive
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:45:55.086Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:55.086Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:45:55.086Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:45:55.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/jxcore-log( 3195): 2015-11-24T10:46:00.088Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:00.089Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:00.089Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 6109
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:46:05.094Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:05.094Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:05.095Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:05.095Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 3195): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3195): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT1620
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, motorola-Nexus 6_PT1620
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
,I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:46:12.777Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:46:13.160Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3195): 2015-11-24T10:46:13.217Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.229Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.273Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.371Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.375Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.408Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.512Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.645Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.699Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.711Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.807Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.851Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.856Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.897Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:13.962Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.126Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.175Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.232Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.239Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.293Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.331Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.380Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.390Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.445Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.477Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.532Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.536Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.622Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.676Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.719Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.777Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.830Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.863Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.873Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.885Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.921Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:14.983Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:15.133Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:46:15.256Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:15.289Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:15.302Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:15.326Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 21
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT1620
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:46:15.503Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F8:95:C7:87:3C:51
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,D/BluetoothMapService( 2065): onReceive
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3195): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : LGE-LG-H815_PT8697
I/HS      ( 3195): Hand Shake finished outgoing for : LGE-LG-H815_PT8697
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, LGE-LG-H815_PT8697
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 41210
I/BtConnectorHelper( 3195): Request socket is using : 41210
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :41210
I/jxcore-log( 3195): 2015-11-24T10:46:24.861Z SendDataConnector.js: CLIENT connected to 41210, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:24.862Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 41210
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:46:24.883Z SendDataConnector.js: CLIENT now sending 20000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:26.413Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:26.491Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:26.492Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:26.508Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:26.508Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
,I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
I/jxcore-log( 3195): 2015-11-24T10:46:26.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:46:26.542Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:26.549Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:26.550Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 104973 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 25
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:46:31.631Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:31.632Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:31.632Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:46:36.634Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:36.635Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/jxcore-log( 3195): 2015-11-24T10:46:41.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:41.639Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:41.640Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:41.641Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 26
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:46:43.064Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:43.065Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:43.066Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:46:48.067Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:48.070Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,I/jxcore-log( 3195): 2015-11-24T10:46:53.071Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:53.071Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:53.071Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:53.071Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 27
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:46:55.952Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:55.953Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:46:55.954Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3195): 2015-11-24T10:47:00.955Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:00.956Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3195): Found 4 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(4): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:47:05.959Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:05.960Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:05.961Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:05.961Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 28
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:47:07.445Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:07.446Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:07.447Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:47:12.447Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:12.450Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,I/jxcore-log( 3195): 2015-11-24T10:47:17.453Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:17.454Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:17.455Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:17.455Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 29
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:47:18.916Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:18.916Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:18.932Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:18.935Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:18.942Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:18.947Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:18.950Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 52368 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread,
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3195): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT5312","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT5312
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, HTC-HTC One_M8_PT5312
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
,I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:47:22.672Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:47:23.146Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.196Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.204Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.240Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.284Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.324Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.411Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.417Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.425Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.449Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.459Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.542Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.548Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.563Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.600Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.607Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.613Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.621Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.650Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.689Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.696Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.702Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.729Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.760Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.766Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.774Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.795Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.805Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.815Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.850Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.871Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.878Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.891Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.922Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.929Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.955Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.990Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:23.997Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:24.044Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:24.055Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:24.079Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:24.110Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 24
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT5312
,I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT5312
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/jxcore-log( 3195): 2015-11-24T10:47:24.192Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x46
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x43
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 30
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:47:25.497Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:25.500Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:25.507Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT6481
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT6481
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:47:26.755Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:47:27.182Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.244Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.253Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:27.255Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.305Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.322Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.350Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.431Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.484Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.494Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.531Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.567Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.577Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.610Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.647Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.661Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.725Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.760Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.866Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.901Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.934Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:27.970Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.005Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.182Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.188Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.233Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.270Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.331Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.346Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.380Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:28.506Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2065): invalid rfc slot id: 31
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT6481
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:47:29.318Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3195): 2015-11-24T10:47:30.511Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:30.512Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,W/bt-btm  ( 2065): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51cfc rs_disc_pending=2
E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : LGE-LG-H815_PT8697
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, LGE-LG-H815_PT8697
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:47:34.926Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.370Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.420Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.476Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.479Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.483Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.487Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.490Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:35.512Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:35.513Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:35.513Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3195): 2015-11-24T10:47:35.567Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.634Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.732Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.798Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.865Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:35.933Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.051Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.121Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.230Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.397Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.431Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.518Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.586Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.656Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.761Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.835Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.922Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:36.987Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.002Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.158Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.211Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.295Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.341Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.398Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.429Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.464Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.475Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.485Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.520Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.572Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.578Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.742Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.922Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:37.935Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:38.056Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:38.125Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 32
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT8697
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
,I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:47:38.223Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4b
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 34
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:47:42.033Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:42.034Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:42.034Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: G4-1
,I/jxcore-log( 3195): 2015-11-24T10:47:47.036Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:47.042Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:47:52.049Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:52.050Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:52.051Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:52.051Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3493 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3493): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3493):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3493):   adb logcat -s GAv4
,W/GAv4    ( 3493): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3493): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3493): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  733): Killing 2682:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2682/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4c
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 35
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:47:57.312Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:57.312Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:47:57.312Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:02.312Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:02.313Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 3 peers.
,I/SS      ( 3195): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:07.317Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:07.317Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:07.321Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:07.324Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x48
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 36
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:48:12.674Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:12.675Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:12.675Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:17.677Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:17.677Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 2065): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2065): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2065): Entering PendingCommandState State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2065): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2065): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2065): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2065): StableState(): Entering Off State
,W/BluetoothEventManager( 2662): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2662): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT2678
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, samsung-SM-A300FU_PT2678
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/jxcore-log( 3195): 2015-11-24T10:48:18.422Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.804Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.813Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.831Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.843Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.879Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.934Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.981Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:18.987Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.033Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.079Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.110Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.121Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.133Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.182Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.219Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.247Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.258Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.288Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.291Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.333Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.362Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.368Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.374Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.408Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.485Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.491Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.498Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.504Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.541Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.586Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.595Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.661Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.697Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.718Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.786Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:19.820Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 33
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT2678
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:48:19.868Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x4a
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3195): 2015-11-24T10:48:22.707Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:22.710Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:22.713Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:22.714Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d525e4 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A3-1
,I/        ( 3195): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT3547, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT3547, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3195): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT1620, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT1620, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4f
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 38
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:48:29.306Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:29.307Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:29.323Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:29.326Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:29.335Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:29.340Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:29.343Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3195): Connecting to A3-1, at 08:EC:A9:50:75:41
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 70362 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2678","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : samsung-SM-A300FU_PT2678
,I/HS      ( 3195): Hand Shake finished outgoing for : samsung-SM-A300FU_PT2678
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, samsung-SM-A300FU_PT2678
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 60217
I/BtConnectorHelper( 3195): Request socket is using : 60217
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :60217
I/jxcore-log( 3195): 2015-11-24T10:48:34.384Z SendDataConnector.js: CLIENT connected to 60217, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:34.384Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 60217
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:48:34.404Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3195): 2015-11-24T10:48:34.731Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:34.790Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 8 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3195): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(5): Android_608e 92:e7:c4:e6:4c:f8
I/SS      ( 3195): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3195): 2015-11-24T10:48:34.949Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.073Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3195): 2015-11-24T10:48:35.119Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.175Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.426Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.492Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.543Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.786Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.787Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:35.815Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:35.816Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
,I/BtConnectorHelper( 3195): Disconnect outgoing peer: 08:EC:A9:50:75:41
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:48:35.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:35.855Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:35.855Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:35.856Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
I/        ( 3195): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3195): Connecting to A5-1, at 7C:F9:0E:37:96:AB
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 6457 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d525e4 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3547","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : samsung-SM-A500FU_PT3547
I/HS      ( 3195): Hand Shake finished outgoing for : samsung-SM-A500FU_PT3547
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, samsung-SM-A500FU_PT3547
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 53228
I/BtConnectorHelper( 3195): Request socket is using : 53228
,I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :53228
I/jxcore-log( 3195): 2015-11-24T10:48:37.442Z SendDataConnector.js: CLIENT connected to 53228, error: null
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:37.443Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 53228
I/BtToRequestSocket( 3195): Set local streams
I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:48:37.462Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3195): 2015-11-24T10:48:37.730Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:37.853Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3195): 2015-11-24T10:48:37.906Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:38.142Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,D/        ( 2065): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3195): 2015-11-24T10:48:38.177Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:38.283Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d525e4 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:48:39.643Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3195): 2015-11-24T10:48:39.751Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:40.163Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:40.163Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/jxcore-log( 3195): 2015-11-24T10:48:40.201Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:40.202Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
,I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
,I/jxcore-log( 3195): 2015-11-24T10:48:40.234Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:40.235Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/jxcore-log( 3195): 2015-11-24T10:48:40.235Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:40.237Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 4309 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d527ac rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d527ac rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 41
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:48:42.283Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:42.283Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:42.284Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: A5-1
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:48:47.286Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:47.287Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:48:52.291Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:52.292Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:52.293Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:52.293Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 42
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:48:53.175Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:53.176Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:53.176Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:48:58.177Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:48:58.180Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:03.183Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:03.184Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:03.185Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:03.185Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 43
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:49:04.599Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:04.599Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:04.600Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:49:09.602Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:09.603Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:14.605Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:14.606Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:14.607Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:14.607Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 44
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:49:15.820Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:15.821Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:15.822Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:49:20.822Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:20.823Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:25.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:25.826Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:25.827Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:25.827Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 45
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:49:29.424Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:29.425Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:29.440Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:29.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:29.446Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:29.446Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:29.447Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 49190 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d527ac rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 46
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:49:30.692Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:30.693Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:30.693Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:49:35.694Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:35.695Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 3 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3195): 2015-11-24T10:49:40.701Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:40.702Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:40.702Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:40.703Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 47
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:49:42.476Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:42.476Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:49:42.480Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:49:47.503Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:47.504Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Cleared service requests
,I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3195): Peer(3): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3195): 2015-11-24T10:49:52.507Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:52.508Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:52.508Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:52.509Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 48
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:49:53.901Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:53.902Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:53.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/jxcore-log( 3195): 2015-11-24T10:49:58.903Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:49:58.904Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:50:03.908Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:03.908Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:03.909Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:03.909Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2065): invalid rfc slot id: 49
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:50:06.415Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:06.416Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:06.416Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:50:11.418Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:11.419Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:16.422Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:16.423Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:16.423Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:16.424Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 50
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:50:18.351Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:18.351Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:18.367Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:18.373Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:18.384Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:18.384Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:18.385Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 48906 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52974 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2065): invalid rfc slot id: 51
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:50:23.802Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:23.803Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:23.803Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:28.804Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:28.805Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:33.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:33.809Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:33.810Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:33.810Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 52
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:50:39.009Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:39.010Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:39.011Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [90:e7:c4:f6:69:77]: 7, f, 2205
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT4125","ra":"90:E7:C4:F6:69:77"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : HTC-HTC One M8s_PT4125
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 3195): 2015-11-24T10:50:44.022Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:44.024Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, HTC-HTC One M8s_PT4125
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:50:44.056Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:50:44.460Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.471Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.486Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.493Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.505Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.557Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.591Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.652Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.690Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.741Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.747Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.759Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.790Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.824Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.841Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.847Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.857Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.943Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:44.979Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.006Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.014Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.024Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.058Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.091Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.100Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.106Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.112Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.149Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.183Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.194Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.204Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.215Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.269Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.276Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.294Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:45.302Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,W/bt-btif ( 2065): invalid rfc slot id: 37
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT4125
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One M8s_PT4125
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/jxcore-log( 3195): 2015-11-24T10:50:45.405Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x40
,I/jxcore-log( 3195): 2015-11-24T10:50:49.027Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:49.027Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:49.032Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:50:49.032Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 2065): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=2
E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: HTC One M8s
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 54
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:50:56.333Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:56.334Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:50:56.334Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3195): 2015-11-24T10:51:01.336Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:01.336Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 4 peers.
I/SS      ( 3195): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:51:06.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:06.341Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:06.341Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:06.342Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 55
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:51:11.515Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:11.515Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:11.515Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3195): 2015-11-24T10:51:16.517Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:16.519Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3195): we got incoming connection
I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3195): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTListenerThread( 3195): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3195): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3195): MESSAGE_WRITE 77 bytes.
I/HS      ( 3195): Incoming connection Hand Shake finished for : motorola-XT1072_PT8689
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : true, motorola-XT1072_PT8689
I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BTConnectedThread
I/BtConnectorHelper( 3195): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3195): --DoOneRunRound started
,I/jxcore-log( 3195): 2015-11-24T10:51:20.798Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): LocalHost address: localhost/127.0.0.1, port: 45968
,I/BtToRequestSocket( 3195): --DoOneRunRound ended
,I/jxcore-log( 3195): 2015-11-24T10:51:21.210Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.224Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.259Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.271Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.284Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.308Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.347Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.369Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.400Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.409Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.446Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.470Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.480Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.493Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.523Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:21.524Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:21.524Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:21.525Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 2015-11-24T10:51:21.547Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.584Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3195): 
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3195): 2015-11-24T10:51:21.597Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.629Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3195): 2015-11-24T10:51:21.865Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.895Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.904Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:21.915Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/jxcore-log( 3195): 2015-11-24T10:51:22.157Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:51:22.379Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:22.581Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:51:22.791Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:22.997Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/jxcore-log( 3195): 2015-11-24T10:51:23.142Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3195): 2015-11-24T10:51:23.470Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:23.697Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:23.825Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.187Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.247Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.254Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.260Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.266Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.284Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.310Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.397Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.826Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:24.937Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3195): 
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2065): invalid rfc slot id: 53
,I/BtToSocketBase( 3195): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3195): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8689
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3195): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3195): 2015-11-24T10:51:25.908Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3195): 
,W/bt-rfcomm( 2065): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2065): RFCOMM_DisconnectInd LCID:0x43
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 57
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:51:26.990Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:26.990Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:27.006Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:27.012Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 1
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:27.015Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:27.015Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:27.016Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3195): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 68607 ms, rnd: 5, ex: Connection to F8:CF:C5:D9:E5:61 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: XT1072
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,W/bt-btif ( 2065): new conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2065): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3195): Starting to Handshake
,I/BTHandshakeSocketThread( 3195): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3195): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread started
,I/BTConnectToThread( 3195): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3195): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3195): HandshakeOk : samsung-SM-G900F_PT1757
I/HS      ( 3195): Hand Shake finished outgoing for : samsung-SM-G900F_PT1757
I/BTHandshakeSocketThread( 3195): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3195): Starting the connected thread incoming : false, samsung-SM-G900F_PT1757
,I/BtToSocketBase( 3195): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3195): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3195): mHTTPPort  set to : 46223
I/BtConnectorHelper( 3195): Request socket is using : 46223
I/BtToRequestSocket( 3195): Now accepting connections
,I/BtConnectorHelper( 3195): Calling ConnectionStatusUpdate with port :46223
I/jxcore-log( 3195): 2015-11-24T10:51:31.572Z SendDataConnector.js: CLIENT connected to 46223, error: null
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:31.591Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3195): 
,I/BtToRequestSocket( 3195): incoming data from: /127.0.0.1, port: 46223
I/BtToRequestSocket( 3195): Set local streams
,I/BtToRequestSocket( 3195): rin ended ---------------------------;
,I/jxcore-log( 3195): 2015-11-24T10:51:31.632Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:31.796Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:31.867Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:31.924Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:31.998Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.101Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.125Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.206Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.213Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.253Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.274Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:32.274Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.291Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:32.292Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3195): 
I/BtConnectorHelper( 3195): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3195): Stop ReceivingThread
I/BtToSocketBase( 3195): Stop SendingThread
I/BtToSocketBase( 3195): Close local in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3195): Close LocalOutputStream
I/BtToSocketBase( 3195): Close localHostSocket
I/BtToSocketBase( 3195): Close bt in
,I/BtToSocketBase( 3195): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3195): Close bt out
I/BtToSocketBase( 3195): Close bt socket
I/BtToRequestSocket( 3195): Close server socket
I/jxcore-log( 3195): 2015-11-24T10:51:32.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.317Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:32.332Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:32.332Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 5260 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2065): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2065): onReceive
,I/BTConnectionReceiver( 1414): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1414): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 59
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:51:37.695Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:37.696Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:37.696Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:42.697Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:42.702Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:47.706Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:47.706Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:47.707Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:47.707Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 60
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:51:49.410Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:49.413Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:49.414Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:51:54.417Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:54.417Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:51:59.424Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:59.425Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:59.426Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:51:59.426Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x13  CID 0x4c
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 61
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:52:07.437Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:07.437Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:07.441Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:12.445Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:12.445Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:17.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:17.452Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:17.452Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:17.452Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 62
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:52:23.149Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:23.157Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:23.157Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:52:28.175Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:28.176Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/        ( 3195): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3195): 2015-11-24T10:52:33.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:33.180Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:33.180Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:33.181Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
,I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 63
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:52:38.353Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:38.354Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:52:38.355Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:38.356Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:38.356Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:38.356Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:38.356Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 66027 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4a
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 64
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:52:48.318Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:48.318Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:48.319Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3195): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/jxcore-log( 3195): 2015-11-24T10:52:53.320Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:53.321Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/        ( 3195): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT1620, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT1620, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:52:58.324Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:58.325Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:58.326Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:52:58.326Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2065): invalid rfc slot id: 65
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:53:03.509Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:03.509Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:03.509Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3195): 2015-11-24T10:53:08.510Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:08.510Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 5 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3195): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:53:13.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:13.523Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:13.524Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:13.524Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4e
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 66
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:53:18.951Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:18.952Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:18.953Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:53:23.954Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:23.955Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:53:28.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:28.959Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:28.959Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:28.960Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x40
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 67
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:53:34.260Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:34.260Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:34.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:53:39.261Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:39.262Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:53:44.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:44.265Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:44.266Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:44.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x41
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 68
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:53:53.367Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:53:53.372Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:53:53.388Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:53.391Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:53.393Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:53.393Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:53.394Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 75017 ms, rnd: 5, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 69
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:53:54.543Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:54.544Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:53:54.544Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:53:59.546Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:53:59.546Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:54:04.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:04.547Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:04.548Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:04.548Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2065): invalid rfc slot id: 70
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:54:05.848Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:05.849Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:05.849Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:54:10.851Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:10.852Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/jxcore-log( 3195): 2015-11-24T10:54:15.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:15.853Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:15.853Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:15.853Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 71
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:54:16.344Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:16.345Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:16.345Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3195): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:54:21.346Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:21.347Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3195): 2015-11-24T10:54:26.372Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:26.373Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:26.374Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:26.374Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 72
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:54:26.915Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:26.916Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:26.916Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/        ( 3195): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 3195): 2015-11-24T10:54:31.917Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:31.918Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:36.921Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:36.922Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:36.923Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:36.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3195): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 73
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:54:37.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:37.774Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:37.790Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:37.792Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : F8:95:C7:87:85:54, try count now: 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:37.795Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:37.795Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:37.796Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 44382 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d527ac rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52974 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 74
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:54:41.113Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:41.114Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:41.114Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
I/SS      ( 3195): Found 8 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3195): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3195): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:54:46.115Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:46.115Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:51.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:51.119Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:51.120Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:51.120Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 75
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:54:52.435Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:52.436Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:54:52.436Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/UsageStatsService(  733): User[0] Flushing usage stats to disk
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:54:57.437Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:54:57.442Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:55:02.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:02.446Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:02.446Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:02.446Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 76
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:55:03.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:03.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:03.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:55:08.786Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:08.787Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:55:13.795Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:13.796Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:13.796Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:13.797Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 77
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:55:15.650Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:15.650Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:15.651Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:55:20.653Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:20.654Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:55:25.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:55:25.661Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:25.662Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:25.662Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3195): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 78
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:55:26.782Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:26.783Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:55:26.799Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:26.801Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:26.803Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:26.804Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:26.804Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 48988 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52974 rs_disc_pending=1
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): tBTM_SEC_DEV:0xa3d52974 rs_disc_pending=0
W/bt-btif ( 2065): bta_dm_check_av:0
,W/bt-btif ( 2065): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d,
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 79
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:55:32.212Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:32.212Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:32.213Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3195): 2015-11-24T10:55:37.215Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:37.216Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 3 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:55:42.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:42.221Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:42.222Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:42.222Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 80
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:55:47.419Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:47.419Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:47.419Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3195): 2015-11-24T10:55:52.419Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:52.420Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3195): 2015-11-24T10:55:57.423Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:57.424Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:57.424Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:55:57.425Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 81
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:56:02.599Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:02.599Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:02.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3195): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:56:07.599Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:07.600Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3195): 2015-11-24T10:56:12.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:12.603Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:12.604Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:12.604Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
,W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 82
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:56:17.781Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:17.781Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:17.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3195): 2015-11-24T10:56:22.781Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:22.782Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:56:27.786Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:27.787Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:27.787Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:56:27.788Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 3195): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 83
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:56:32.963Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:32.963Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:56:32.965Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:32.966Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:32.966Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:32.966Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:32.966Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 66160 ms, rnd: 5, ex: Connection to F8:CF:C5:D9:E5:61 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 84
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:56:33.150Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:33.150Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:33.151Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:56:38.152Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:38.153Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:56:43.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:43.155Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:43.155Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:43.155Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 85
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:56:43.383Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:43.384Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:43.384Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:56:48.385Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:48.386Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:56:53.387Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:53.387Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:53.387Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:53.387Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 86
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:56:53.625Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:53.626Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:53.626Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:56:58.627Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:56:58.627Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:03.631Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:03.632Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:03.632Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:03.633Z SendDataConnector.js: do connect now
,I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 87
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:57:03.865Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:03.866Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:03.866Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3195): 2015-11-24T10:57:08.868Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:08.868Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:13.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:13.872Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:13.873Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:13.873Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3195): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2065): info:x10
,D/        ( 2065): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2065): process_service_search_attr_rsp
,E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 88
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:57:15.402Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:15.402Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:15.418Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:15.421Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- round done--------
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 3
I/jxcore-log( 3195): 
I/jxcore-log( 3195): do fake peer & start
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:15.423Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:15.424Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:15.424Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback round[0] time: 42437 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2065): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2065): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2065): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x47
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 89
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3195): 2015-11-24T10:57:22.668Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:22.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:22.669Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:27.671Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:27.672Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:32.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:32.675Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:32.676Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:32.676Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x45
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 90
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:57:39.225Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:39.225Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:39.226Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:44.227Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:44.227Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:57:49.235Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:49.235Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:49.236Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:49.236Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x49
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 91
,I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:57:58.314Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:58.315Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:57:58.316Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:58:03.316Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:03.317Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:58:08.320Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:08.320Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:08.321Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:08.321Z SendDataConnector.js: do connect now
I/jxcore-log( 3195): 
,I/        ( 3195): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3195): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3195): Starting to connect
W/BluetoothAdapter( 3195): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2065): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2065): SDP - Rcvd conn cnf with error: 0x10  CID 0x4b
E/bt-btif ( 2065): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2065): invalid rfc slot id: 92
I/BTConnectToThread( 3195): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3195): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3195): 2015-11-24T10:58:13.620Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:13.620Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:13.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): timeout now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): dun
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): weAreDoneNow , resultArray.length: 11
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): done, now sending data to server
I/jxcore-log( 3195): 
I/jxcore-log( 3195): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): -- RESULT DATA {"name:":"LGE-Nexus 5_PT6925","time":1000108,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:1F:C9:5E","time":13966,"result":"OK","connections":2,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":18861,"result":"OK","connections":1,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":23160,"result":"OK","connections":2,"tryCount":1},{"name":"90:E7:C4:F6:69:77","time":24273,"result":"OK","connections":1,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":4011,"result":"OK","connections":1,"tryCount":1},{"name":"00:F4:6F:30:E0:6C","time":68175,"result":"OK","connections":2,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":34215,"result":"OK","connections":2,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":104973,"result":"OK","connections":3,"tryCount":1},{"name":"08:EC:A9:50:75:41","time":6457,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:37:96:AB","time":4309,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":5260,"result":"OK","connections":1,"tryCount":1},
I/jxcore-log( 3195): sendList : 100% : 104973 ms, 99% : 104973 ms, 95 : 68175 ms, 90% : 68175 ms.
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Result count 11, range 4011 ms to  104973 ms.
I/jxcore-log( 3195): 
I/jxcore-log( 3195): sendList failed peers count : 5 [31.25 %]
I/jxcore-log( 3195): 
I/jxcore-log( 3195): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 3
I/jxcore-log( 3195): 
I/jxcore-log( 3195): - Peer ID : F8:95:C7:87:85:54, Tried : 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): - Peer ID : E0:DB:10:14:E2:C0, Tried : 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
I/jxcore-log( 3195): 
I/jxcore-log( 3195): - Peer ID : 08:EC:A9:50:76:27, Tried : 3
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:14.618Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3195): 
I/jxcore-log( 3195): 2015-11-24T10:58:14.618Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T10:58:14.619Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3195): 
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6575","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6575, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6575, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3195): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/SS      ( 3195): Found 4 peers.
I/SS      ( 3195): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3195): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Cleared service requests
,I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT8689","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT8689, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT8689, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3195): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3195): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT1757","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT1757, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT1757, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3195): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT179"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT179, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT179, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3195): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8697","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8697, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8697, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1620","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT1620, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT1620, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"}, typeCordovap2p._tcp.local.:
I/        ( 3195): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT6481"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT6481, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3195): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT6481, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/EventLogService( 1603): Aggregate from 1448360821153 (log), 1448360821153 (data)
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 7 peers.
I/SS      ( 3195): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3195): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/        ( 3195): Cleared service requests
I/        ( 3195): Started peer discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1032): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3195): Found 6 peers.
I/SS      ( 3195): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3195): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3195): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3195): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3195): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3195): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3195): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3195): Added service request
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3195): Started service discovery
,I/wpa_supplicant( 1032): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1032): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 3195): DBG, CoordinatorConnector command called
I/jxcore-log( 3195): 
I/jxcore-log( 3195): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): stop tests now !
I/jxcore-log( 3195): 
I/jxcore-log( 3195): stop current!
I/jxcore-log( 3195): 
I/jxcore-log( 3195): testSendData stopped
I/jxcore-log( 3195): 
I/        ( 3195): Stoping All
,I/        ( 3195): Stopping services
I/        ( 3195): Stopping services
,I/wpa_supplicant( 1032): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1032): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3195): Stop Bluetooth
I/        ( 3195): Stop Bluetooth
I/BTListenerThread( 3195): Stopped
,I/jxcore-log( 3195): StopBroadcasting went ok
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): 2015-11-24T11:02:35.446Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3195): 
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 3195): Cleared local services
I/        ( 3195): Cleared service requests
I/        ( 3195): Stopped peer discovery
,I/jxcore-log( 3195): DBG, CoordinatorConnector command called
I/jxcore-log( 3195): 
I/jxcore-log( 3195): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"80:01:84:8A:B3:68\",\"time\":4011,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:37:96:AB\",\"time\":4309,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":5260,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"08:EC:A9:50:75:41\",\"time\":6457,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":13966,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":18861,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":23160,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":24273,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":34215,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\"
I/jxcore-log( 3195): ****TEST TOOK:  ms ****
I/jxcore-log( 3195): 
I/jxcore-log( 3195): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3195): 
I/jxcore-log( 3195): stop tests now !
I/jxcore-log( 3195): 
I/jxcore-log( 3195): end, event received
I/jxcore-log( 3195): 
I/jxcore-log( 3195): CoordinatorConnector close called
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3195): 
I/jxcore-log( 3195): The Coordinator has disconnected!
I/jxcore-log( 3195): 
I/jxcore-log( 3195): The Coordinator has closed!
I/jxcore-log( 3195): 
I/jxcore-log( 3195): stop tests now !
I/jxcore-log( 3195): 
I/jxcore-log( 3195): turning Radios off
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Toggling radios to false
I/jxcore-log( 3195): 
D/BluetoothAdapter( 3195): enable(): BT is already enabled..!
I/chromium( 3195): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime( 3654): 
D/AndroidRuntime( 3654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3654): CheckJNI is OFF
,D/AndroidRuntime( 3654): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  733): Killing 3195:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  733): WIN DEATH: Window{2a5ce537 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,W/PackageSettings(  733): Skipping PackageSetting{3a6c7662 com.example.hello/10277} due to missing metadata
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{5a04462 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  733): Spurious death for ProcessRecord{13677515 3195:com.test.thalitest/u0a270}, curProc for 3195: null
I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{5a04462 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  733): Duplicate finish request for ActivityRecord{5a04462 u0 com.test.thalitest/.MainActivity t214 f}
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1553): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1240): Explicit concurrent mark sweep GC freed 3941(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 895us total 27.560ms
,I/Keyboard.Facilitator( 1063): resetDictionaries() : en_US
,D/VoicemailCleanupService( 1357): Cleaning up data for package: com.test.thalitest
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,I/Keyboard.Facilitator.DecoderInitializer( 1063): run()
,I/Decoder ( 1063): createOrResetDecoder
,D/OpenGLRenderer(  943): Enabling debug mode 0
,I/ConfigService( 1441): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1063): run()
,I/art     ( 1414): Explicit concurrent mark sweep GC freed 95734(4MB) AllocSpace objects, 21(384KB) LOS objects, 25% free, 19MB/25MB, paused 326us total 132.638ms
,I/art     (  733): Explicit concurrent mark sweep GC freed 78877(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/43MB, paused 1.056ms total 140.581ms
,I/art     (  733): WaitForGcToComplete blocked for 65.218ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1063): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Loading LM = contacts
,I/art     (  733): Explicit concurrent mark sweep GC freed 11385(539KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.252ms total 84.147ms
I/art     (  733): WaitForGcToComplete blocked for 123.887ms for cause Explicit
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  733): removeObsoleteFile: deleting file=214_task.xml
,D/AndroidRuntime( 3654): Shutting down VM
,I/art     (  733): Explicit concurrent mark sweep GC freed 6472(356KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 990us total 102.424ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1063): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1063): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1063): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1063): run()
I/StatsUtilsManager( 1063): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1063): shouldRecordStats() = Too Soon
,W/Launcher( 1240): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3de9826b new=com.google.android.velvet.VelvetApplication@3de9826b
,I/UpdateIcingCorporaServi( 1414): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 3195 uid 10270
,I/Keyboard.Facilitator( 1063): onFinishInput()
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3698 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator( 1063): onFinishInput()
,I/Launcher( 1240): Deferring update until onResume
,W/IInputConnectionWrapper( 1240): showStatusIcon on inactive InputConnection
I/UpdateIcingCorporaServi( 1414): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
,W/ResourcesManager( 1240): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 3698): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1603): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1603): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1603): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1603): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1603): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1603): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1441): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1441): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1603): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1240): Deferring update until onResume
,D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1603): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3731 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1603): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1603): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 1603): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,D/gH_CompatibleDatabase( 1603): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,W/BaseAppContext( 1603): Using Auth Proxy for data requests.
,E/SQLiteLog( 1603): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GAv4-SVC( 1603): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/BaseAppContext( 1603): Using Auth Proxy for data requests.
,E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4-SVC( 1603): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 1603): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1603): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1603): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1603): 	at java.lang.Thread.run(Thread.java:818)
,E/ClearPendingStateOp( 1603): Runtime exception while performing operation
E/ClearPendingStateOp( 1603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1603): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1603): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1603): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1603): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1603): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1603): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1603): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1603): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1603): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1603): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1603): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1603): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1603): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1603): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1603): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1603): 	at java.lang.Thread.run(Thread.java:818)
I/GMPM-SVC( 1603): App measurement is starting up
I/PeopleContactsSync( 1603): CP2 sync disabled
I/Icing   ( 1603): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  733): Can't write: system_app_wtf
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop92.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
E/SQLiteLog( 1603): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1603): Local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteLog( 1603): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1603): Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SQLiteDatabase( 1603): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1062)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1603): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 1603): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1603): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1603): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1603): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1603): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.d.k(SourceFile:281)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.d.e(SourceFile:724)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.n(SourceFile:1003)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.k(SourceFile:1014)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.ak.b(SourceFile:263)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.al.run(SourceFile:162)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1603): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1603): 	at com.google.android.gms.measurement.internal.aj.run(SourceFile:272)
E/GMPM-SVC( 1603): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1603): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
E/GMPM-SVC( 1603): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1074)
W/GMPM-SVC( 1603): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/GMPM-SVC( 1603): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1058)
E/SharedPreferencesImpl( 1603): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
--------- beginning of crash
E/AndroidRuntime( 1603): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1603): Process: com.google.android.gms, PID: 1603
E/AndroidRuntime( 1603): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1603): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1603): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 1603): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 1603): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1603): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1603): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1603): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 1603): Sending signal. PID: 1603 SIG: 9
E/DropBoxManagerService(  733): Can't write: system_app_crash
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
,D/ConnectivityService(  733): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1e0ded8f)
D/ConnectivityService(  733): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  733): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/SQLiteDatabase( 3731): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3731): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3731): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3731): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 3731): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3731): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 3731): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 3731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 3731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3731): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3731): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 3731): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3731): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 3731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/AndroidRuntime( 3731): Shutting down VM
E/AndroidRuntime( 3731): FATAL EXCEPTION: main
E/AndroidRuntime( 3731): Process: com.android.documentsui, PID: 3731
E/AndroidRuntime( 3731): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 3731): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 3731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 3731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3731): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3731): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 3731): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3731): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 3731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 3731): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3731): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3731): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3731): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 3731): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3731): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 3731): 	... 9 more

```
