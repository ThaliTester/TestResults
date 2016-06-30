#### Test 7578926851a8f91_thali04_htc-Nexus 9 Logs


```
--------- beginning of main,
06-30 12:52:02.703  1211  1309 I Icing   : Indexing FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4 from com.google.android.googlequicksearchbox
06-30 12:52:02.761  1211  1309 I Icing   : Indexing done FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4
06-30 12:52:03.130  2348  2348 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:52:03.135  2348  2348 D AndroidRuntime: CheckJNI is OFF
06-30 12:52:03.142   999  1091 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 12:52:03.142   999  1091 I Keyboard.Facilitator: flushDynamicLanguageModels()
06-30 12:52:03.171  2348  2348 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:52:03.511  2348  2348 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:52:03.535  2348  2348 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 12:52:03.540   470  1707 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:52:03.559  2348  2348 D AndroidRuntime: Shutting down VM
06-30 12:52:03.565  1078  1089 W SearchService: Abort, client detached.
06-30 12:52:03.577   470  1706 I ActivityManager: Start proc 2357:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 12:52:03.581  1078  1078 I HotwordDetector: Closing mic
06-30 12:52:03.581  1078  1313 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7d624bd
06-30 12:52:03.581  1078  1324 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 12:52:03.611  1078  1078 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-30 12:52:03.622   224   664 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-30 12:52:03.626  1078  1321 I MicroRecognitionRnrImpl: Detection finished
06-30 12:52:03.637  1078  1317 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-30 12:52:03.705  2357  2357 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,06-30 12:52:03.839  2357  2357 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,06-30 12:52:03.862  2357  2357 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 2322-2336)
,06-30 12:52:03.862  2357  2357 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 12:52:03.916  2357  2357 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cde031}
,06-30 12:52:03.917  2357  2357 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:52:03.917  2357  2357 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:52:03.922  2357  2357 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 12:52:03.923  2357  2357 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 12:52:03.952  2357  2373 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,06-30 12:52:03.960  2357  2357 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 12:52:03.977  2357  2357 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:03.977  2357  2357 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 12:52:04.221   470   522 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1e94a:true
,06-30 12:52:04.284  2357  2357 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 12:52:04.302  2357  2357 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,06-30 12:52:04.359  2357  2397 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 12:52:04.374  2357  2384 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 12:52:04.405  2357  2397 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 12:52:04.495   470   523 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +929ms
,06-30 12:52:04.500   999   999 I Keyboard.Facilitator: onFinishInput()
,06-30 12:52:04.565  2357  2357 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2357
,06-30 12:52:04.597   470  1706 I ActivityManager: Killing 2024:com.google.android.youtube/u0a81 (adj 15): empty #17
,06-30 12:52:04.641   470  1706 I ActivityManager: Killing 1899:com.google.android.gm.exchange/u0a70 (adj 15): empty #18
,06-30 12:52:04.695  2357  2357 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 12:52:04.855  2357  2398 D jxcore_app_log: JniHelper::setJavaVM(0xab2d87b8), pthread_self() = -538891984
,06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:52:04.863  2357  2398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2b6adc added. We now have 1 listener(s)
06-30 12:52:04.865  2357  2398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,06-30 12:52:04.867  2357  2398 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
06-30 12:52:04.867  2357  2398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:52:04.868  2357  2398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 12:52:04.871  2357  2398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79c456b added. We now have 1 listener(s)
06-30 12:52:04.872  2357  2398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 12:52:04.876   470   670 D WifiService: New client listening to asynchronous messages
,06-30 12:52:04.876  2357  2398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:04.876  2357  2398 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 12:52:04.878  2357  2398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,06-30 12:52:04.878  2357  2398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 12:52:04.878  2357  2398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:52:04.878  2357  2398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 12:52:04.881  2357  2398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 12:52:04.881  2357  2398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
06-30 12:52:04.883  2357  2398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:04.884  2357  2398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-30 12:52:04.884  2357  2398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,06-30 12:52:04.885  2357  2398 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:52:04.885  2357  2398 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 12:52:04.917  2357  2357 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:52:05.470  2357  2406 W jxcore-log: Initializing JXcore engine
06-30 12:52:05.470  2357  2406 W jxcore-log: JXcore engine is ready
06-30 12:52:05.510  2406  2406 W Thread-53: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10107 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 12:52:05.510  2406  2406 W Thread-53: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[5569]" dev="sockfs" ino=5569 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 12:52:05.510  2406  2406 W Thread-53: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 12:52:05.510  2406  2406 W Thread-53: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18314]" dev="sockfs" ino=18314 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 12:52:05.524  2357  2406 W jxcore-log: Starting JXcore engine
,06-30 12:52:07.581  2357  2406 W jxcore-log: Platform android
06-30 12:52:07.581  2357  2406 W jxcore-log: 
06-30 12:52:07.581  2357  2406 W jxcore-log: Process ARCH arm
06-30 12:52:07.581  2357  2406 W jxcore-log: 
06-30 12:52:07.703  2357  2406 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:52:07.703  2357  2406 I jxcore-log: 
06-30 12:52:07.704  2357  2406 W jxcore-log: JXcore engine is started
06-30 12:52:07.709  2357  2398 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:52:07.711   470   951 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
06-30 12:52:07.722  2357  2357 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 12:52:07.723  2357  2357 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 12:52:07.727  2357  2398 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
06-30 12:52:07.737   470   760 I ActivityManager: Start proc 2428:com.android.packageinstaller/u0a64 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 12:52:07.788  2428  2428 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
06-30 12:52:07.863  2428  2441 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 12:52:07.897  2428  2441 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:52:07.945   999   999 I Keyboard.Facilitator: onFinishInput()
06-30 12:52:07.987   470   523 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +261ms
06-30 12:52:08.051   470   951 I ActivityManager: Killing 1470:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,06-30 12:52:08.179  2357  2357 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@db56f8f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3652d7a, 16908290=android.view.AbsSavedState$1@3652d7a}, android:focusedViewId=100}]}]
,06-30 12:52:08.179  2357  2357 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 12:52:08.193  1095  1095 I ConfigService: onDestroy
,06-30 12:52:16.578  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:16.581  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:16.582  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:16.592  1095  1244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:52:16.592  1095  1244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:52:16.592  1095  1244 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:52:16.592  1095  1244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:52:16.622  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:52:16.623  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 12:52:16.623  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 12:52:36.729  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:36.734  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:36.736  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:36.755  1095  1819 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:52:36.755  1095  1819 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:52:36.756  1095  1819 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:52:36.756  1095  1819 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:52:36.768  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 12:52:36.768  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 12:52:36.769  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 12:52:56.864  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:56.893  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:56.897  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:56.924  1095  1244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
06-30 12:52:56.924  1095  1244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 12:52:56.924  1095  1244 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:52:56.924  1095  1244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:52:56.938  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:52:56.938  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 12:52:56.939  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 12:53:07.946   999  1091 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 12:53:07.946   999  1091 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 12:53:07.973  1095  1095 I ConfigService: onCreate
,06-30 12:53:10.206   470   526 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 12:53:10.210   470   526 I PowerManagerService: Sleeping (uid 1000)...
06-30 12:53:10.224   171  1285 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (313 us)
06-30 12:53:10.225   999   999 I Keyboard.Facilitator: onFinishInput()
,06-30 12:53:10.391  2357  2357 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 12:53:10.391  2357  2357 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 12:53:10.927   470   526 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 12:53:10.936   470   526 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 12:53:10.938   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x5568aa4430
,06-30 12:53:10.939   171   171 D hwcomposer: hwc_blank: display 0: blank
06-30 12:53:10.939   470   523 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
06-30 12:53:10.939   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,06-30 12:53:11.264   470   689 D SurfaceControl: Excessive delay in setPowerMode(): 325ms
,06-30 12:53:11.366   470   669 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 12:53:11.383   470   669 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 12:53:11.433   470   669 D WifiConfigStore: Retrieve network priorities after PNO.
06-30 12:53:11.433   470   669 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 12:53:13.054  1095  1095 I ConfigService: onDestroy
,06-30 12:53:13.720  1061  1468 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:53:17.060  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:17.066  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:17.068  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:17.088  1095  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
06-30 12:53:17.088  1095  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:53:17.088  1095  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 12:53:17.088  1095  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:53:17.103  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:53:17.103  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:53:17.103  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 12:53:41.569  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:41.574  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:41.576  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:41.596  1095  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:53:41.596  1095  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:53:41.596  1095  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 12:53:41.596  1095  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:53:41.613  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:53:41.613  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 12:53:41.614  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 12:54:01.753  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:54:01.761  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 12:54:01.762  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:54:01.788  1095  1244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:54:01.788  1095  1244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:54:01.788  1095  1244 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 12:54:01.788  1095  1244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:54:01.809  1709  1709 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:54:01.809  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:54:01.810  1709  1709 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 12:54:10.234   999  1091 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 12:54:10.234   999  1091 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 12:54:10.260  1095  1095 I ConfigService: onCreate
,06-30 12:54:15.340  1095  1095 I ConfigService: onDestroy
,06-30 12:56:10.914  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:56:10.931  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:56:10.934  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:56:10.963  1095  1787 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 12:56:10.964  1095  1787 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 12:56:10.964  1095  1787 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:56:10.964  1095  1787 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:56:10.986  1095  1787 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 12:56:10.986  1095  1787 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 12:56:11.023  1709  1744 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 12:56:11.023  1709  1744 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 12:56:11.023  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 12:56:11.023  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 12:56:11.023  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 12:56:11.023  1709  1744 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 12:56:11.023  1709  1744 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:01:11.178  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:01:11.194  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:01:11.198  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:01:11.230  1095  1819 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 13:01:11.230  1095  1819 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:01:11.230  1095  1819 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:01:11.230  1095  1819 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:01:11.247  1095  1819 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:01:11.247  1095  1819 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:01:11.251  1709  1744 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:01:11.251  1709  1744 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:01:11.251  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:01:11.251  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:01:11.251  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:01:11.251  1709  1744 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:01:11.251  1709  1744 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:06:11.378  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:06:11.395  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:06:11.399  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:06:11.451  1095  1244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 13:06:11.451  1095  1244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:06:11.451  1095  1244 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:06:11.452  1095  1244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:06:11.469  1095  1244 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:06:11.469  1095  1244 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:06:11.473  1709  1744 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:06:11.473  1709  1744 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:06:11.473  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:06:11.473  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:06:11.473  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:06:11.473  1709  1744 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:06:11.473  1709  1744 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:10:56.848   470   509 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:11:11.501  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:11:11.512  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:11:11.514  1095  1095 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:11:11.545  1095  1244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 13:11:11.546  1095  1244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:11:11.546  1095  1244 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:11:11.546  1095  1244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:11:11.566  1095  1244 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:11:11.566  1095  1244 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:11:11.572  1709  1744 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:11:11.572  1709  1744 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:11:11.572  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:11:11.572  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:11:11.572  1709  1744 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:11:11.572  1709  1744 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:11:11.572  1709  1744 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
