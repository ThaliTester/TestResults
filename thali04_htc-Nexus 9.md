#### Test 72145431fdae11f_thali04_htc-Nexus 9 Logs


```
--------- beginning of main,
06-30 10:35:47.360  1225  1315 I Icing   : Indexing FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4 from com.google.android.googlequicksearchbox
06-30 10:35:47.462  1225  1315 I Icing   : Indexing done FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4
06-30 10:35:47.748  2343  2343 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:35:47.752  2343  2343 D AndroidRuntime: CheckJNI is OFF
06-30 10:35:47.786  2343  2343 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:35:48.075  2343  2343 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:35:48.099  2343  2343 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 10:35:48.105   551  1097 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:35:48.122  1080  1272 W SearchService: Abort, client detached.
06-30 10:35:48.124  1080  1080 I HotwordDetector: Closing mic
06-30 10:35:48.124  1080  1277 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@248cf74
06-30 10:35:48.126  2343  2343 D AndroidRuntime: Shutting down VM
06-30 10:35:48.137   551   752 I ActivityManager: Start proc 2352:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 10:35:48.145   222   646 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-30 10:35:48.147  1080  1297 I MicroRecognitionRnrImpl: Detection finished
06-30 10:35:48.147  1080  1291 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-30 10:35:48.153  1080  1080 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-30 10:35:48.250  2352  2352 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,06-30 10:35:48.385  2352  2352 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 10:35:48.408  2352  2352 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 9860-9874)
06-30 10:35:48.409  2352  2352 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:35:48.453  2352  2352 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35b9f1d}
,06-30 10:35:48.453  2352  2352 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:35:48.453  2352  2352 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:35:48.459  2352  2352 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 10:35:48.460  2352  2352 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 10:35:48.489  2352  2369 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,06-30 10:35:48.497  2352  2352 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 10:35:48.519  2352  2352 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:35:48.519  2352  2352 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 10:35:48.791   551   595 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a18171b:true
,06-30 10:35:48.841  2352  2352 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:35:48.859  2352  2352 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,06-30 10:35:48.906  2352  2393 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:48.914  2352  2380 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 10:35:48.958  2352  2393 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:49.045   551   596 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +919ms
,06-30 10:35:49.051   993   993 I Keyboard.Facilitator: onFinishInput()
,06-30 10:35:49.104  2352  2352 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2352
,06-30 10:35:49.189   551  1156 I ActivityManager: Killing 2024:com.google.android.youtube/u0a81 (adj 15): empty #17
,06-30 10:35:49.221   551  1156 I ActivityManager: Killing 1889:com.google.android.gm.exchange/u0a70 (adj 15): empty #18
,06-30 10:35:49.232  2352  2352 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:35:49.401  2352  2394 D jxcore_app_log: JniHelper::setJavaVM(0xaadea7b8), pthread_self() = -544523984
,06-30 10:35:49.405  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:35:49.405  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:35:49.405  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:35:49.405  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:35:49.405  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 10:35:49.406  2352  2394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fb338 added. We now have 1 listener(s)
,06-30 10:35:49.409  2352  2394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,06-30 10:35:49.412  2352  2394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,06-30 10:35:49.413  2352  2394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 10:35:49.413  2352  2394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:35:49.415  2352  2394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff2fe77 added. We now have 1 listener(s)
06-30 10:35:49.415  2352  2394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:35:49.419   551   665 D WifiService: New client listening to asynchronous messages
,06-30 10:35:49.419  2352  2394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:49.420  2352  2394 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:35:49.421  2352  2394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:35:49.421  2352  2394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:35:49.421  2352  2394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,06-30 10:35:49.421  2352  2394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:35:49.424  2352  2394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:35:49.425  2352  2394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
06-30 10:35:49.427  2352  2394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:35:49.427  2352  2394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 10:35:49.427  2352  2394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:35:49.427  2352  2394 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:35:49.428  2352  2394 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 10:35:49.468  2352  2352 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:35:50.035  2352  2403 W jxcore-log: Initializing JXcore engine
06-30 10:35:50.035  2352  2403 W jxcore-log: JXcore engine is ready
06-30 10:35:50.080  2403  2403 W Thread-55: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=9626 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 10:35:50.083  2403  2403 W Thread-55: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10210]" dev="sockfs" ino=10210 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 10:35:50.083  2403  2403 W Thread-55: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:35:50.083  2403  2403 W Thread-55: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18024]" dev="sockfs" ino=18024 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 10:35:50.094  2352  2403 W jxcore-log: Starting JXcore engine
06-30 10:35:51.301  1099  1099 I ConfigService: onDestroy
,06-30 10:35:52.233  2352  2403 W jxcore-log: Platform android
06-30 10:35:52.233  2352  2403 W jxcore-log: 
06-30 10:35:52.234  2352  2403 W jxcore-log: Process ARCH arm
06-30 10:35:52.234  2352  2403 W jxcore-log: 
06-30 10:35:52.356  2352  2403 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:35:52.356  2352  2403 I jxcore-log: 
06-30 10:35:52.356  2352  2403 W jxcore-log: JXcore engine is started
06-30 10:35:52.360  2352  2394 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 10:35:52.361   551   568 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
06-30 10:35:52.373  2352  2352 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 10:35:52.373  2352  2352 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 10:35:52.377  2352  2394 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
06-30 10:35:52.388   551  1097 I ActivityManager: Start proc 2426:com.android.packageinstaller/u0a64 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 10:35:52.443  2426  2426 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
06-30 10:35:52.515  2426  2439 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:35:52.551  2426  2439 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:35:52.601   993   993 I Keyboard.Facilitator: onFinishInput()
,06-30 10:35:52.613   551  1156 I ActivityManager: Killing 1829:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,06-30 10:35:52.652   551   596 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +276ms
,06-30 10:35:52.868  2352  2352 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b7b43db Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@70c8f36, 16908290=android.view.AbsSavedState$1@70c8f36}, android:focusedViewId=100}]}]
,06-30 10:35:52.868  2352  2352 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 10:36:01.117  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:01.122  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:01.123  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:01.134  1099  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:36:01.134  1099  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:36:01.134  1099  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:36:01.134  1099  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:36:01.148  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:01.148  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:01.148  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 10:36:21.256  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:21.261  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:36:21.262  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:21.280  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
06-30 10:36:21.280  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:36:21.280  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:36:21.280  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:36:21.297  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:36:21.298  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:21.298  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 10:36:52.106   551   599 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 10:36:52.139   551   599 I PowerManagerService: Sleeping (uid 1000)...
,06-30 10:36:52.140   993   993 I Keyboard.Facilitator: onFinishInput()
06-30 10:36:52.142   170   949 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (489 us)
,06-30 10:36:52.285  2352  2352 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 10:36:52.285  2352  2352 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 10:36:52.329   551   561 I art     : Background partial concurrent mark sweep GC freed 8780(646KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 2.666ms total 106.064ms
,06-30 10:36:52.862   551   599 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 10:36:52.870   551   599 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 10:36:52.873   551   596 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 10:36:52.887   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x5595720430
06-30 10:36:52.887   170   170 D hwcomposer: hwc_blank: display 0: blank
06-30 10:36:52.887   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,06-30 10:36:53.201   551   685 D SurfaceControl: Excessive delay in setPowerMode(): 315ms
,06-30 10:36:53.293   551   664 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 10:36:53.304   551   664 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 10:36:53.369   551   664 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 10:36:53.369   551   664 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 10:36:55.731  1011  1448 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:56.287  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:56.293  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:56.294  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:36:56.314  1099  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:36:56.314  1099  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 10:36:56.314  1099  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:36:56.314  1099  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:36:56.330  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 10:36:56.330  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:36:56.330  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 10:37:23.518  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:23.523  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:23.526  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:23.546  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
06-30 10:37:23.546  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:37:23.546  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:37:23.546  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:37:23.604  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:37:23.605  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:37:23.605  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 10:37:52.146   993  1096 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 10:37:52.146   993  1096 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 10:37:52.174  1099  1099 I ConfigService: onCreate
,06-30 10:37:56.312  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:56.319  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:56.320  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:37:56.341  1099  1218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:37:56.341  1099  1218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:37:56.341  1099  1218 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:37:56.341  1099  1218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:37:56.357  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 10:37:56.357  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:37:56.358  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 10:37:57.253  1099  1099 I ConfigService: onDestroy
,06-30 10:38:16.528  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:38:16.534  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:38:16.535  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:38:16.555  1099  1218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:38:16.555  1099  1218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:38:16.555  1099  1218 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:38:16.556  1099  1218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:38:16.572  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:38:16.572  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:38:16.573  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 10:39:23.635  1099  1262 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:39:52.857  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:52.870  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:39:52.873  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:52.903  1099  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:39:52.904  1099  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 10:39:52.904  1099  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:39:52.904  1099  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:39:52.925  1099  1112 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:52.925  1099  1112 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:39:52.931  1718  1753 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:39:52.931  1718  1753 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:39:52.931  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:39:52.931  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:39:52.931  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:39:52.931  1718  1753 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:39:52.931  1718  1753 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:52.992  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:53.003  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:44:53.005  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:53.039  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 10:44:53.039  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:44:53.040  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 10:44:53.040  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:44:53.057  1099  1110 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:53.057  1099  1110 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:53.061  1718  1753 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:44:53.061  1718  1753 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:44:53.061  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:44:53.061  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:44:53.061  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:44:53.061  1718  1753 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:44:53.061  1718  1753 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:45:01.131  1718  1718 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,06-30 10:45:01.158  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:01.172  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:45:01.176  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:01.205  1099  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:45:01.205  1099  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 10:45:01.206  1099  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:01.206  1099  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:01.229  1718  1718 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:45:01.239  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:01.265  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:45:01.266  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:45:01.266  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:01.266  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:01.297  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:01.321  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:45:01.321  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:45:01.322  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:01.322  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:01.340  1718  1718 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:45:01.421  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:01.440  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:45:01.441  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:45:01.441  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:01.441  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:01.458  1718  1718 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 10:45:01.459  1718  1718 D Finsky  : [1] WearSupportService.startHygiene: disabled
,06-30 10:45:01.460  1718  1718 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,06-30 10:45:01.463  1718  1718 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
06-30 10:45:01.463  1718  2228 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446
,06-30 10:45:16.455  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:16.462  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:16.464  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:16.491  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:45:16.491  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 10:45:16.491  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:16.491  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:16.512  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:45:16.513  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:45:16.513  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 10:45:36.613  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:36.619  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:36.621  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:36.640  1099  1218 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:45:36.640  1099  1218 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:45:36.641  1099  1218 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 10:45:36.641  1099  1218 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:36.656  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:45:36.656  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:45:36.657  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 10:45:56.778  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:56.784  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:56.786  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:45:56.807  1099  1164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:45:56.807  1099  1164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:45:56.807  1099  1164 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:45:56.807  1099  1164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:45:56.823  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:45:56.823  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:45:56.824  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 10:46:16.948  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:16.957  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:16.959  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:16.983  1099  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:46:16.984  1099  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:46:16.984  1099  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:46:16.984  1099  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:46:17.005  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:46:17.006  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:46:17.006  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 10:46:37.132  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:37.140  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:37.142  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:37.166  1099  1110 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:46:37.166  1099  1110 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:46:37.166  1099  1110 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:46:37.166  1099  1110 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:46:37.187  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:46:37.188  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 10:46:37.188  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 10:46:57.299  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:57.305  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:57.308  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:46:57.329  1099  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 10:46:57.329  1099  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 10:46:57.329  1099  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:46:57.329  1099  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:46:57.345  1718  1718 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 10:46:57.346  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 10:46:57.346  1718  1718 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 10:49:53.185  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:53.199  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:53.201  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:53.236  1099  1819 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 10:49:53.236  1099  1819 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 10:49:53.236  1099  1819 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:49:53.237  1099  1819 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:49:53.259  1099  1819 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:53.259  1099  1819 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:53.264  1718  1753 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:49:53.264  1718  1753 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:49:53.264  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:49:53.264  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:49:53.264  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:49:53.264  1718  1753 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:49:53.264  1718  1753 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:38.190   551   582 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:53.300  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:53.314  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:53.318  1099  1099 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:53.349  1099  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:54:53.349  1099  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:54:53.349  1099  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 10:54:53.349  1099  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:54:53.369  1099  1112 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:53.369  1099  1112 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:53.374  1718  1753 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:54:53.374  1718  1753 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:54:53.374  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:54:53.374  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:54:53.374  1718  1753 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:54:53.374  1718  1753 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:54:53.374  1718  1753 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
