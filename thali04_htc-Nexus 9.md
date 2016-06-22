#### Test 721454317367600_thali04_htc-Nexus 9 Logs


```
--------- beginning of system
06-22 07:44:53.718   561   609 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-22 07:44:53.721   561   609 I PowerManagerService: Sleeping (uid 1000)...
--------- beginning of main
06-22 07:44:53.755   985   985 I Keyboard.Facilitator: onFinishInput()
06-22 07:44:53.762  1073  1084 W SearchService: Abort, client detached.
06-22 07:44:53.777  1073  1073 I HotwordDetector: Closing mic
06-22 07:44:53.778  1073  1318 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6de064
06-22 07:44:53.789   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-22 07:44:53.791  1073  1329 I MicroRecognitionRnrImpl: Detection finished
06-22 07:44:53.792  1073  1324 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-22 07:44:53.851  1073  1073 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-22 07:44:53.863   170  1209 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
06-22 07:44:53.905   561   581 I ActivityManager: Killing 1464:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
06-22 07:44:53.942   561   581 I ActivityManager: Killing 1989:com.google.android.youtube/u0a81 (adj 15): empty #18
06-22 07:44:54.215  2314  2314 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-22 07:44:54.220  2314  2314 D AndroidRuntime: CheckJNI is OFF
06-22 07:44:54.256  2314  2314 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-22 07:44:54.293  2314  2314 I Radio-JNI: register_android_hardware_Radio DONE
06-22 07:44:54.318  2314  2314 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:44:54.323   561   962 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-22 07:44:54.344   561   962 I ActivityManager: Start proc 2327:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-22 07:44:54.356  2314  2314 D AndroidRuntime: Shutting down VM
,06-22 07:44:54.604   561   609 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-22 07:44:54.610   561   609 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
06-22 07:44:54.611   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55ba275430
,06-22 07:44:54.611   561   606 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
06-22 07:44:54.611   170   170 D hwcomposer: hwc_blank: display 0: blank
06-22 07:44:54.611   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,06-22 07:44:54.684   561   571 I art     : Background partial concurrent mark sweep GC freed 27161(2043KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/25MB, paused 689us total 132.534ms
,06-22 07:44:54.898   561   681 D SurfaceControl: Excessive delay in setPowerMode(): 286ms
,06-22 07:44:54.964   561   662 D WifiConfigStore: Retrieve network priorities after PNO.
,06-22 07:44:54.984   561   662 E WifiStateMachine:  Fail to set up pno, want false now false
,06-22 07:44:54.998   561   662 D WifiConfigStore: Retrieve network priorities after PNO.
,06-22 07:44:55.002   561   662 E WifiStateMachine:  Fail to set up pno, want false now false
,06-22 07:44:55.030  2327  2327 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,06-22 07:44:55.101   561   593 W ActivityManager: Activity pause timeout for ActivityRecord{a0ae72b u0 com.test.thalitest/.MainActivity t62}
,06-22 07:44:55.204  2327  2327 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-22 07:44:55.246  2327  2327 I LibraryLoader: Time to load native libraries: 23 ms (timestamps 1833-1856)
,06-22 07:44:55.246  2327  2327 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-22 07:44:55.304  2327  2327 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {59e616e}
,06-22 07:44:55.305  2327  2327 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:44:55.305  2327  2327 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-22 07:44:55.316  2327  2327 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-22 07:44:55.318  2327  2327 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-22 07:44:55.355  2327  2342 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,06-22 07:44:55.373  2327  2327 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-22 07:44:55.398  2327  2327 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:44:55.399  2327  2327 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:44:55.790   561   605 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8296893:true
,06-22 07:44:55.870  2327  2327 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:44:55.897  2327  2327 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,06-22 07:44:55.996  2327  2365 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:44:56.016  2327  2352 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-22 07:44:56.054  2327  2365 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:44:56.114   985   985 I Keyboard.Facilitator: onFinishInput()
,06-22 07:44:56.232   561   606 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s630ms (total +1s898ms)
,06-22 07:44:56.323  2327  2327 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2327
,06-22 07:44:56.499  2327  2327 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:44:56.734  2327  2366 D jxcore_app_log: JniHelper::setJavaVM(0xab1fd7b8), pthread_self() = -550508240
,06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:44:56.741  2327  2366 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d831d added. We now have 1 listener(s)
,06-22 07:44:56.744  2327  2366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,06-22 07:44:56.747  2327  2366 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,06-22 07:44:56.748  2327  2366 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-22 07:44:56.748  2327  2366 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-22 07:44:56.752  2327  2366 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e342760 added. We now have 1 listener(s)
06-22 07:44:56.752  2327  2366 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-22 07:44:56.756   561   663 D WifiService: New client listening to asynchronous messages
,06-22 07:44:56.757  2327  2366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-22 07:44:56.757  2327  2366 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-22 07:44:56.759  2327  2366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-22 07:44:56.759  2327  2366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:44:56.759  2327  2366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:44:56.759  2327  2366 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-22 07:44:56.761  2327  2366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:44:56.762  2327  2366 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
06-22 07:44:56.764  2327  2366 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:56.765  2327  2366 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-22 07:44:56.765  2327  2366 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:44:56.765  2327  2366 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:44:56.765  2327  2366 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:44:56.811  2327  2327 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:44:57.509  1050  1462 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-22 07:44:57.643  2327  2373 W jxcore-log: Initializing JXcore engine
06-22 07:44:57.643  2327  2373 W jxcore-log: JXcore engine is ready
,06-22 07:44:57.750  2373  2373 W Thread-49: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=7114 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,06-22 07:44:57.750  2373  2373 W Thread-49: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10603]" dev="sockfs" ino=10603 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-22 07:44:57.750  2373  2373 W Thread-49: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-22 07:44:57.750  2373  2373 W Thread-49: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17779]" dev="sockfs" ino=17779 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-22 07:44:57.772  2327  2373 W jxcore-log: Starting JXcore engine
,06-22 07:44:57.948  2327  2373 W jxcore-log: Platform android
06-22 07:44:57.948  2327  2373 W jxcore-log: 
,06-22 07:44:57.948  2327  2373 W jxcore-log: Process ARCH arm
06-22 07:44:57.948  2327  2373 W jxcore-log: 
,06-22 07:44:58.377  2327  2373 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:44:58.377  2327  2373 I jxcore-log: 
,06-22 07:44:58.378  2327  2373 W jxcore-log: JXcore engine is started
,06-22 07:44:58.393  2327  2366 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:44:58.396   561  1216 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-22 07:44:58.423   561  1216 I ActivityManager: Start proc 2374:com.android.packageinstaller/u0a64 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-22 07:44:58.429  2327  2366 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,06-22 07:44:58.529  2374  2374 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
,06-22 07:44:58.671  2374  2386 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:44:58.763  2374  2386 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:44:58.865   985   985 I Keyboard.Facilitator: onFinishInput()
,06-22 07:44:58.977  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:44:58.985  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:44:58.987  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:44:59.015  1092  1162 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-22 07:44:59.015  1092  1162 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-22 07:44:59.015  1092  1162 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:44:59.015  1092  1162 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:44:59.044  1700  1700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:44:59.045  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-22 07:44:59.045  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-22 07:44:59.246   561   606 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +758ms (total +836ms)
,06-22 07:45:25.365  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:25.371  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:25.373  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:25.395  1092  1214 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-22 07:45:25.395  1092  1214 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-22 07:45:25.395  1092  1214 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:45:25.395  1092  1214 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:45:25.413  1700  1700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:45:25.413  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-22 07:45:25.413  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-22 07:45:58.877  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:58.883  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:45:58.885  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:45:58.904   985  1088 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-22 07:45:58.904   985  1088 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-22 07:45:58.909  1092  1162 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
06-22 07:45:58.909  1092  1162 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-22 07:45:58.909  1092  1162 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-22 07:45:58.909  1092  1162 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:45:58.927  1092  1092 I ConfigService: onCreate
,06-22 07:45:58.934  1700  1700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-22 07:45:58.934  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-22 07:45:58.934  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-22 07:46:04.001  1092  1092 I ConfigService: onDestroy
,06-22 07:46:19.080  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:46:19.087  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:46:19.089  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:46:19.110  1092  1162 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-22 07:46:19.111  1092  1162 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-22 07:46:19.111  1092  1162 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:46:19.111  1092  1162 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:46:19.127  1700  1700 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-22 07:46:19.128  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-22 07:46:19.128  1700  1700 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-22 07:47:54.767  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:47:54.784  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:47:54.786  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:47:54.820  1092  1106 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-22 07:47:54.820  1092  1106 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-22 07:47:54.820  1092  1106 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:47:54.821  1092  1106 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:47:54.877  1092  1106 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 07:47:54.877  1092  1106 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 07:47:54.894  1700  1733 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 07:47:54.894  1700  1733 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 07:47:54.894  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 07:47:54.894  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 07:47:54.894  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 07:47:54.894  1700  1733 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 07:47:54.894  1700  1733 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 07:52:54.942  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:52:54.956  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:52:54.959  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:52:54.993  1092  1214 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-22 07:52:54.993  1092  1214 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-22 07:52:54.993  1092  1214 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:52:54.993  1092  1214 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 07:52:55.013  1092  1214 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 07:52:55.013  1092  1214 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
06-22 07:52:55.018  1700  1733 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 07:52:55.018  1700  1733 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 07:52:55.018  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 07:52:55.018  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 07:52:55.018  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 07:52:55.018  1700  1733 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 07:52:55.018  1700  1733 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 07:57:55.043  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:57:55.058  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:57:55.063  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 07:57:55.095  1092  1104 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-22 07:57:55.095  1092  1104 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-22 07:57:55.095  1092  1104 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-22 07:57:55.095  1092  1104 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:57:55.116  1092  1104 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 07:57:55.116  1092  1104 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 07:57:55.123  1700  1733 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 07:57:55.123  1700  1733 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 07:57:55.123  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 07:57:55.123  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 07:57:55.123  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 07:57:55.123  1700  1733 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 07:57:55.123  1700  1733 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 07:57:55.168   561   571 I art     : Background partial concurrent mark sweep GC freed 26597(2MB) AllocSpace objects, 6(136KB) LOS objects, 33% free, 17MB/25MB, paused 1.630ms total 116.825ms
,06-22 08:02:43.112   561   592 I UsageStatsService: User[0] Flushing usage stats to disk
,06-22 08:02:55.247  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:02:55.260  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:02:55.262  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:02:55.294  1092  1162 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-22 08:02:55.295  1092  1162 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-22 08:02:55.295  1092  1162 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 08:02:55.295  1092  1162 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 08:02:55.314  1092  1162 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 08:02:55.314  1092  1162 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 08:02:55.319  1700  1733 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 08:02:55.319  1700  1733 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 08:02:55.319  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 08:02:55.319  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 08:02:55.319  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 08:02:55.319  1700  1733 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 08:02:55.319  1700  1733 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 08:07:55.340  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:07:55.354  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:07:55.357  1092  1092 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-22 08:07:55.388  1092  1813 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-22 08:07:55.388  1092  1813 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-22 08:07:55.388  1092  1813 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 08:07:55.388  1092  1813 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-22 08:07:55.406  1092  1813 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 08:07:55.406  1092  1813 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-22 08:07:55.411  1700  1733 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 08:07:55.411  1700  1733 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 08:07:55.411  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 08:07:55.411  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 08:07:55.411  1700  1733 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 08:07:55.411  1700  1733 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 08:07:55.411  1700  1733 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
