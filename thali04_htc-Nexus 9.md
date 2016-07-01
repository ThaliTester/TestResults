#### Test 757892686fd65a6_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
07-01 08:58:39.553  2323  2348 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-01 08:58:39.657  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:39.658  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of system
07-01 08:58:39.663   565  1095 I ActivityManager: Killing 1900:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,07-01 08:58:39.686  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:39.694  2323  2355 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
07-01 08:58:39.743  2323  2355 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
07-01 08:58:39.769  2323  2355 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-01 08:58:39.981  2362  2362 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 08:58:39.985  2362  2362 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:40.016  2362  2362 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 08:58:40.050  2362  2362 I Radio-JNI: register_android_hardware_Radio DONE
07-01 08:58:40.073  2362  2362 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 08:58:40.078   565   755 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 08:58:40.099  2362  2362 D AndroidRuntime: Shutting down VM
07-01 08:58:40.108  1077  1816 W SearchService: Abort, client detached.
07-01 08:58:40.124  1077  1303 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@669300b
07-01 08:58:40.125  1077  1077 I HotwordDetector: Closing mic
07-01 08:58:40.133   565  1095 I ActivityManager: Start proc 2371:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-01 08:58:40.154   221   645 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-01 08:58:40.159  1077  1305 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-01 08:58:40.159  1077  1077 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-01 08:58:40.158  1077  1307 I MicroRecognitionRnrImpl: Detection finished
07-01 08:58:40.194  1219  1313 I Icing   : Indexing FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4 from com.google.android.googlequicksearchbox
07-01 08:58:40.230  2371  2371 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-01 08:58:40.339  1219  1313 I Icing   : Indexing done FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4
,07-01 08:58:40.377  2371  2371 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-01 08:58:40.402  2371  2371 I LibraryLoader: Time to load native libraries: 15 ms (timestamps 7008-7023)
,07-01 08:58:40.402  2371  2371 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 08:58:40.445  2371  2371 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {77d6159}
07-01 08:58:40.446  2371  2371 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 08:58:40.446  2371  2371 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 08:58:40.453  2371  2371 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 08:58:40.454  2371  2371 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 08:58:40.488  2371  2388 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,07-01 08:58:40.496  2371  2371 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-01 08:58:40.515  2371  2371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:40.516  2371  2371 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-01 08:58:40.781   565   608 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9c0f1d:true
,07-01 08:58:40.826  2371  2371 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 08:58:40.843  2371  2371 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-01 08:58:40.905  2371  2412 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:40.920  2371  2399 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-01 08:58:40.952  2371  2412 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:41.040   565   609 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +930ms
,07-01 08:58:41.044   995   995 I Keyboard.Facilitator: onFinishInput()
,07-01 08:58:41.106  2371  2371 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2371
,07-01 08:58:41.113   565  1090 I ActivityManager: Killing 1470:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-01 08:58:41.139   565  1090 I ActivityManager: Killing 2035:com.google.android.youtube/u0a81 (adj 15): empty #18
,07-01 08:58:41.219  2371  2371 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 08:58:41.399  2371  2414 D jxcore_app_log: JniHelper::setJavaVM(0xab5827b8), pthread_self() = -551950032
,07-01 08:58:41.406  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:41.406  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:41.406  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:41.406  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:41.406  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 08:58:41.407  2371  2414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2e8524 added. We now have 1 listener(s)
,07-01 08:58:41.412  2371  2414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-01 08:58:41.412  2371  2414 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-01 08:58:41.415  2371  2414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 08:58:41.415  2371  2414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:41.420  2371  2414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@642ba53 added. We now have 1 listener(s)
07-01 08:58:41.421  2371  2414 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 08:58:41.439  2371  2414 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-01 08:58:41.440   565   664 D WifiService: New client listening to asynchronous messages
,07-01 08:58:41.440  2371  2414 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-01 08:58:41.448  2371  2414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-01 08:58:41.448  2371  2414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-01 08:58:41.449  2371  2414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-01 08:58:41.449  2371  2414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-01 08:58:41.452  2371  2414 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 08:58:41.453  2371  2414 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-01 08:58:41.455  2371  2414 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:58:41.455  2371  2414 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 08:58:41.455  2371  2414 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-01 08:58:41.455  2371  2414 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 08:58:41.457  2371  2414 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 08:58:41.494  2371  2371 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 08:58:42.046  2371  2421 W jxcore-log: Initializing JXcore engine
,07-01 08:58:42.046  2371  2421 W jxcore-log: JXcore engine is ready
,07-01 08:58:42.090  2421  2421 W Thread-53: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10062 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-01 08:58:42.090  2421  2421 W Thread-53: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[5727]" dev="sockfs" ino=5727 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-01 08:58:42.090  2421  2421 W Thread-53: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 08:58:42.090  2421  2421 W Thread-53: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18507]" dev="sockfs" ino=18507 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-01 08:58:42.106  2371  2421 W jxcore-log: Starting JXcore engine
,07-01 08:58:44.186  1097  1097 I ConfigService: onDestroy
07-01 08:58:44.257  2371  2421 W jxcore-log: Platform android
07-01 08:58:44.257  2371  2421 W jxcore-log: 
07-01 08:58:44.257  2371  2421 W jxcore-log: Process ARCH arm
07-01 08:58:44.257  2371  2421 W jxcore-log: 
07-01 08:58:44.384  2371  2421 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:44.384  2371  2421 I jxcore-log: 
07-01 08:58:44.384  2371  2421 W jxcore-log: JXcore engine is started
07-01 08:58:44.386  2371  2414 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-01 08:58:44.387   565  1096 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
07-01 08:58:44.397  2371  2371 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 08:58:44.398  2371  2371 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-01 08:58:44.410   565   756 I ActivityManager: Start proc 2442:com.android.packageinstaller/u0a64 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
07-01 08:58:44.469  2442  2442 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
07-01 08:58:44.577  2442  2455 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-01 08:58:44.623  2442  2455 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 08:58:44.670   995   995 I Keyboard.Facilitator: onFinishInput()
07-01 08:58:44.715   565   609 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +315ms
07-01 08:58:44.880  2371  2371 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@96e3df7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9688d02, 16908290=android.view.AbsSavedState$1@9688d02}, android:focusedViewId=100}]}]
07-01 08:58:44.880  2371  2371 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-01 08:58:58.658  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:58:58.666  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:58:58.667  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:58:58.687  1097  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:58:58.687  1097  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 08:58:58.687  1097  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:58:58.687  1097  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:58:58.704  1716  1716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:58:58.704  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 08:58:58.705  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-01 08:59:27.863   565   611 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 08:59:27.890   565   611 I PowerManagerService: Sleeping (uid 1000)...
,07-01 08:59:27.896   170   173 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
07-01 08:59:27.899   995   995 I Keyboard.Facilitator: onFinishInput()
,07-01 08:59:28.050  2371  2371 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 08:59:28.050  2371  2371 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 08:59:28.628   565   611 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 08:59:28.650   565   611 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-01 08:59:28.653   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x5590bda430
,07-01 08:59:28.653   170   170 D hwcomposer: hwc_blank: display 0: blank
,07-01 08:59:28.653   565   609 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-01 08:59:28.653   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-01 08:59:28.962   565   682 D SurfaceControl: Excessive delay in setPowerMode(): 310ms
,07-01 08:59:29.051   565   663 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 08:59:29.064   565   663 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 08:59:29.122   565   663 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 08:59:29.122   565   663 E WifiStateMachine:  Fail to set up pno, want false now false
,07-01 08:59:31.333  1010  1469 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 08:59:33.160  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:33.166  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:33.168  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:33.189  1097  1316 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:59:33.189  1097  1316 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 08:59:33.189  1097  1316 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:59:33.189  1097  1316 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:59:33.206  1716  1716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:59:33.206  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 08:59:33.207  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-01 08:59:59.264  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:59.270  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:59.272  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:59.293  1097  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:59:59.293  1097  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 08:59:59.293  1097  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:59:59.293  1097  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:59:59.310  1716  1716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:59:59.310  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 08:59:59.311  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-01 09:00:19.442  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:19.448  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:19.450  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:19.470  1097  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:00:19.471  1097  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:00:19.471  1097  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:00:19.471  1097  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:00:19.488  1716  1716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:00:19.488  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 09:00:19.488  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-01 09:00:27.940   995  1111 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:00:27.941   995  1111 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:00:27.973  1097  1097 I ConfigService: onCreate
,07-01 09:00:33.059  1097  1097 I ConfigService: onDestroy
,07-01 09:00:39.622  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:39.628  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:39.630  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:39.652  1097  1158 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:00:39.652  1097  1158 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:00:39.652  1097  1158 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:00:39.652  1097  1158 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:00:39.673  1716  1716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:00:39.674  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:00:39.675  1716  1716 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-01 09:00:58.101  1219  2465 I EventLogService: Aggregate from 1467354658007 (log), 1467354658007 (data)
,07-01 09:02:28.431  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:28.446  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:28.449  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:28.490  1097  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:02:28.490  1097  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:02:28.490  1097  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:02:28.491  1097  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:02:28.514  1097  1108 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:02:28.514  1097  1108 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:02:28.518  1716  1749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:02:28.518  1716  1749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:02:28.518  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:02:28.518  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:02:28.518  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:02:28.518  1716  1749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:02:28.518  1716  1749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:07:28.690  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:28.715  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:28.721  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:28.778  1097  1315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:07:28.779  1097  1315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:07:28.779  1097  1315 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-01 09:07:28.779  1097  1315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:07:28.811  1097  1315 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:07:28.811  1097  1315 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:07:28.818  1716  1749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:07:28.818  1716  1749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:07:28.818  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:07:28.818  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:07:28.818  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:07:28.818  1716  1749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:07:28.818  1716  1749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:12:28.869  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:28.910  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:28.916  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:28.978  1097  1108 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:12:28.979  1097  1108 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:12:28.979  1097  1108 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:12:28.979  1097  1108 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:12:29.013  1097  1108 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:12:29.013  1097  1108 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:12:29.023  1716  1749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:12:29.023  1716  1749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:12:29.023  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:12:29.023  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:12:29.023  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:12:29.023  1716  1749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:12:29.023  1716  1749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:17:13.366   565   595 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 09:17:29.071  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:29.094  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:29.097  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:29.145  1097  1107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:17:29.145  1097  1107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:17:29.145  1097  1107 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:17:29.145  1097  1107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:17:29.165  1097  1107 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:17:29.165  1097  1107 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:17:29.169  1716  1749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:17:29.169  1716  1749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:17:29.169  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:17:29.169  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:17:29.169  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:17:29.169  1716  1749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:17:29.169  1716  1749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:22:29.310  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:22:29.332  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:22:29.335  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:22:29.366  1097  1158 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:22:29.366  1097  1158 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:22:29.367  1097  1158 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:22:29.367  1097  1158 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:22:29.381  1097  1158 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:22:29.381  1097  1158 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
07-01 09:22:29.384  1716  1749 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:22:29.384  1716  1749 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:22:29.384  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:22:29.384  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:22:29.384  1716  1749 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:22:29.384  1716  1749 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:22:29.384  1716  1749 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
