#### Test 757892685a40176_thali04_htc-Nexus 9 Logs


```
--------- beginning of system
07-12 17:45:01.027   542   574 I ActivityManager: Start proc 2794:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,--------- beginning of main
07-12 17:45:01.092  2794  2794 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
07-12 17:45:01.135  2794  2794 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-12 17:45:01.135  2794  2794 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:01.135  2794  2794 I GAv4    :   adb logcat -s GAv4
07-12 17:45:01.157  2794  2794 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:01.164  2794  2794 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:01.175  2794  2811 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-12 17:45:01.185   542  1245 I ActivityManager: Killing 2417:com.google.android.apps.photos/u0a66 (adj 15): empty #17
07-12 17:45:01.395  2806  2806 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 17:45:01.399  2806  2806 D AndroidRuntime: CheckJNI is OFF
07-12 17:45:01.431  2806  2806 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 17:45:01.464  2806  2806 I Radio-JNI: register_android_hardware_Radio DONE
07-12 17:45:01.488  2806  2806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 17:45:01.496   542   560 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 17:45:01.512  2806  2806 D AndroidRuntime: Shutting down VM
07-12 17:45:01.521  1075  1101 W SearchService: Abort, client detached.
07-12 17:45:01.536   542   752 I ActivityManager: Start proc 2819:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 17:45:01.542  1075  1075 I HotwordDetector: Closing mic
07-12 17:45:01.543  1075  1307 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c51cfdd
07-12 17:45:01.543  1075  1314 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-12 17:45:01.563   221   643 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-12 17:45:01.566  1075  1313 I MicroRecognitionRnrImpl: Detection finished
07-12 17:45:01.570  1075  1308 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-12 17:45:01.655  2819  2819 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-12 17:45:01.792  2819  2819 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 17:45:01.815  2819  2819 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 8190-8204)
,07-12 17:45:01.815  2819  2819 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:45:01.854  2819  2819 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a8c13aa}
,07-12 17:45:01.854  2819  2819 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:01.854  2819  2819 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 17:45:01.860  2819  2819 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:45:01.861  2819  2819 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:45:01.901  2819  2819 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 17:45:01.928  2819  2819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:45:01.928  2819  2819 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:45:02.141   542   585 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3457357:true
,07-12 17:45:02.224  2819  2819 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:45:02.241  2819  2819 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-12 17:45:02.291  2819  2860 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 17:45:02.296  2819  2847 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-12 17:45:02.338  2819  2860 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 17:45:02.428   542   587 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +905ms
,07-12 17:45:02.429   991   991 I Keyboard.Facilitator: onFinishInput()
,07-12 17:45:02.495  2819  2819 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2819
,07-12 17:45:02.507   542  1341 I ActivityManager: Killing 1962:com.google.android.talk/u0a56 (adj 15): empty #17
,07-12 17:45:02.549   542  1341 I ActivityManager: Killing 2542:com.google.android.gm.exchange/u0a70 (adj 15): empty #18
,07-12 17:45:02.616  2819  2819 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:45:02.783  2819  2861 D jxcore_app_log: JniHelper::setJavaVM(0xab66d7b8), pthread_self() = -558896848
,07-12 17:45:02.790  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:45:02.790  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:45:02.790  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:45:02.790  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:45:02.790  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 17:45:02.792  2819  2861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d430509 added. We now have 1 listener(s)
,07-12 17:45:02.796  2819  2861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-12 17:45:02.797  2819  2861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-12 17:45:02.799  2819  2861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:02.799  2819  2861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:45:02.802  2819  2861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47e533c added. We now have 1 listener(s)
07-12 17:45:02.802  2819  2861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:02.814   542   662 D WifiService: New client listening to asynchronous messages
07-12 17:45:02.816  2819  2861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-12 17:45:02.817  2819  2861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:02.817  2819  2861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-12 17:45:02.817  2819  2861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:45:02.817  2819  2861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 17:45:02.819  2819  2861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:02.819  2819  2861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:02.827  2819  2861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:02.827  2819  2861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:45:02.827  2819  2861 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:02.829  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:02.831  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:02.832  2819  2861 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:45:02.866  2819  2819 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:45:03.414  2819  2870 W jxcore-log: Initializing JXcore engine
,07-12 17:45:03.414  2819  2870 W jxcore-log: JXcore engine is ready
,07-12 17:45:03.478  2870  2870 W Thread-62: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10027 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-12 17:45:03.478  2870  2870 W Thread-62: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[5473]" dev="sockfs" ino=5473 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 17:45:03.478  2870  2870 W Thread-62: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 17:45:03.478  2870  2870 W Thread-62: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20482]" dev="sockfs" ino=20482 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 17:45:03.493  2819  2870 W jxcore-log: Starting JXcore engine
,07-12 17:45:05.659  2819  2870 W jxcore-log: Platform android
07-12 17:45:05.659  2819  2870 W jxcore-log: 
07-12 17:45:05.660  2819  2870 W jxcore-log: Process ARCH arm
07-12 17:45:05.660  2819  2870 W jxcore-log: 
,07-12 17:45:05.787  2819  2870 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:45:05.787  2819  2870 I jxcore-log: 
,07-12 17:45:05.787  2819  2870 W jxcore-log: JXcore engine is started
,07-12 17:45:05.789  2819  2861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:45:05.791  2819  2819 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:45:07.336   542   589 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 17:45:07.337   542   589 I PowerManagerService: Sleeping (uid 1000)...
07-12 17:45:07.340   170  1046 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (859 us)
,07-12 17:45:07.426   991   991 I Keyboard.Facilitator: onFinishInput()
,07-12 17:45:07.461  2819  2819 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:45:07.461  2819  2819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 17:45:07.489  2819  2819 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a16950 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bf79439, 16908290=android.view.AbsSavedState$1@bf79439}, android:focusedViewId=100}]}]
,07-12 17:45:07.489  2819  2819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-12 17:45:07.490  2819  2819 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 17:45:07.490  2819  2819 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 17:45:07.560   542  2260 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153950, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:08.095   542   589 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-12 17:45:08.098   542   589 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-12 17:45:08.103   542   587 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-12 17:45:08.107   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x559fa28430
07-12 17:45:08.107   170   170 D hwcomposer: hwc_blank: display 0: blank
07-12 17:45:08.107   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,07-12 17:45:08.431   542   679 D SurfaceControl: Excessive delay in setPowerMode(): 325ms
,07-12 17:45:08.466   542   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:08.483   542   661 E native  : do suspend false
,07-12 17:45:08.500   542   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 17:45:08.534   542   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:08.539   542   661 E native  : do suspend true
,07-12 17:45:08.971   542   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,07-12 17:45:10.944  1007  1531 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:45:14.876   542   661 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,07-12 17:45:15.555  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 17:45:15.555  2819  2870 I jxcore-log: 
,07-12 17:45:15.560  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 17:45:15.560  2819  2870 I jxcore-log: 
,07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:15.567  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:15.569  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:15.575  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 17:45:15.575  2819  2870 I jxcore-log: 
,07-12 17:45:15.579  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 17:45:15.579  2819  2870 I jxcore-log: 
,07-12 17:45:15.602  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:15.609  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:15.611  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:15.640  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 17:45:15.640  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-12 17:45:15.640  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:15.640  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:15.669  2504  2504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 17:45:15.670  2504  2504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-12 17:45:15.670  2504  2504 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-12 17:45:16.244  1083  1264 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 17:45:17.877  2758  2902 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:45:17.895  2758  2903 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:45:17.922  1083  1179 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:45:17.923  1083  1179 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:45:17.923  1083  1179 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:17.923  1083  1179 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:17.964  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:45:17.964  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:45:17.964  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:17.965  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:17.986  2758  2903 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:45:17.988  2758  2902 E BooksSync: Soft error
07-12 17:45:17.988  2758  2902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:45:17.988  2758  2902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:45:17.988  2758  2902 E BooksSync: Sync error
07-12 17:45:17.988  2758  2902 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:45:17.988  2758  2902 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:45:17.988  2758  2902 I BooksSync: Finished books sync
,07-12 17:45:18.000   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164193, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:45:20.669  2819  2870 I jxcore-log: Unit Test app is loadeded
07-12 17:45:20.669  2819  2870 I jxcore-log: 
,07-12 17:45:20.678  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:45:20.678  2819  2870 I jxcore-log: 
,07-12 17:45:20.681  2819  2819 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 17:45:20.687  2819  2870 I jxcore-log: runUTtestsBefore
07-12 17:45:20.687  2819  2870 I jxcore-log: 
,07-12 17:45:20.687  2819  2870 D JXMOBILE: Running tests
,07-12 17:45:20.798  2819  2870 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-12 17:45:20.799  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-12 17:45:20.799  2819  2870 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-12 17:45:20.800  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-12 17:45:20.800  2819  2870 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-12 17:45:20.800  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-12 17:45:20.802  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:20.802  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-12 17:45:20.803  2819  2870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-12 17:45:20.804  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-12 17:45:20.804  2819  2870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-12 17:45:20.804  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-12 17:45:20.804  2819  2870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-12 17:45:20.804  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:20.805  2819  2870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-12 17:45:20.805  2819  2870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-12 17:45:20.805  2819  2870 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-12 17:45:20.805  2819  2870 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-12 17:45:20.806  2819  2870 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-12 17:45:20.806  2819  2870 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-12 17:45:20.807  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:20.807  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afedd30 added. We now have 2 listener(s)
07-12 17:45:20.807  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:20.809  2819  2870 D BluetoothAdapter: enable(): BT is already enabled..!
,07-12 17:45:20.814   542  1341 D WifiService: setWifiEnabled: true pid=2819, uid=10000
,07-12 17:45:20.814   542  1341 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:20.815  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:20.815  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@908fda9 added. We now have 3 listener(s)
07-12 17:45:20.816  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:20.821  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:20.821  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd3af2e added. We now have 4 listener(s)
07-12 17:45:20.821  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:20.824  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:20.824  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@815cacf added. We now have 5 listener(s)
07-12 17:45:20.824  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:20.827   542   956 D WifiService: setWifiEnabled: false pid=2819, uid=10000
,07-12 17:45:20.827   542   956 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:20.839   542   661 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-12 17:45:20.839   542   661 D IpReachabilityMonitor: clear: iface{wlan0/6}, v{4}, ntable=[]
07-12 17:45:20.839  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:20.842  1620  1666 D BluetoothAdapterState: Current state: ON, message: 23
07-12 17:45:20.842  1620  1666 D BluetoothAdapterProperties: Setting state to 13
07-12 17:45:20.842  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-12 17:45:20.844  1620  1666 D BluetoothAdapterProperties: onBluetoothDisable()
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:20.845  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:20.845  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:20.846  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:20.848  1620  1620 I BtOppRfcommListener: stopping Accept Thread
07-12 17:45:20.852  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:20.856  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:20.860   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:20.860   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:20.861  1620  1666 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:20.865  1620  2215 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-12 17:45:20.866  1620  2215 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:20.871   542   574 I ActivityManager: Start proc 2906:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-12 17:45:20.873   542   661 E native  : do suspend true
,07-12 17:45:20.874  1620  1673 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:20.874  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:20.879  1620  1620 D HeadsetService: Received stop request...Stopping profile...
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:20.885  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:20.892   542  2261 D DhcpClient: Clearing IP address
,07-12 17:45:20.892   217   632 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:20.898  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:20.904   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:20.908  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:20.909   542  2264 D DhcpClient: Receive thread stopped
,07-12 17:45:20.917   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:20.917   706   734 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:20.917   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:20.918   706   706 D HeadsetProfile: Bluetooth service disconnected
,07-12 17:45:20.918  1028  1130 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:20.918   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:20.919  1620  1620 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:20.919  1620  1814 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:20.933  1083  2304 V NativeCrypto: Read error: ssl=0x555db9f670: I/O error during system call, Connection timed out
07-12 17:45:20.946   542   542 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:20.951  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:20.952  1620  1620 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:20.952  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:20.954  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:20.954  1620  1620 D HidService: Received stop request...Stopping profile...
07-12 17:45:20.955  1620  1620 D HidService: Stopping Bluetooth HidService
07-12 17:45:20.958  1083  2304 V NativeCrypto: SSL shutdown failed: ssl=0x555db9f670: I/O error during system call, Broken pipe
07-12 17:45:20.961   542   542 D RttService: SCAN_AVAILABLE : 1
07-12 17:45:20.961   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-12 17:45:20.961   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-12 17:45:20.962   542   676 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 17:45:20.966  1620  1620 D HealthService: Received stop request...Stopping profile...
07-12 17:45:20.974   542   661 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-12 17:45:20.975   542   663 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-12 17:45:20.979   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:20.979   542   661 E native  : do suspend true
07-12 17:45:20.984  1620  1620 D PanService: Received stop request...Stopping profile...
,07-12 17:45:20.995  1620  1620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-12 17:45:20.995  1620  1620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:20.996  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:20.996  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:20.996  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:20.996  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:20.999  1620  1673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-12 17:45:21.000  1620  1673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100020
,07-12 17:45:21.002  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.002  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.002  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.003  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.004  1620  1620 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:21.004  1620  1673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-12 17:45:21.005  1620  1620 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:21.006  1620  1620 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:21.006  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.006  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:21.006  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.007  1620  1620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:21.009  1620  1620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-12 17:45:21.009  1620  1774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.009  1620  1774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:21.010  1620  1774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:21.010  1620  1774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:21.011  1620  1774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:21.011  1620  1774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:21.011  1620  1774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:21.011  1620  1774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:21.012  1620  1673 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:21.012  1620  1673 E bt_btif : btif_hf_upstreams_evt: Invalid index 104
,07-12 17:45:21.012  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:21.012  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.012  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.012  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:21.013  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-12 17:45:21.013  1620  1666 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:21.013  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:21.014   706  2918 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:21.015  1620  1666 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:21.016   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.016   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.016   706  2918 D BluetoothPan: onBluetoothStateChange on: false
07-12 17:45:21.017   706  2918 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-12 17:45:21.017   706  2918 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.018   706  2918 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-12 17:45:21.018  1028  1140 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:21.019   706  2918 D BluetoothMap: onBluetoothStateChange: up=false
,07-12 17:45:21.022   706  2918 E BluetoothMap: 
07-12 17:45:21.022   706  2918 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@49ba8b0
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-12 17:45:21.022   706  2918 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:45:21.022   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:21.023   542   585 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:21.023  1620  1666 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-12 17:45:21.023  1620  1666 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:21.023  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:21.024  1620  1666 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:21.024  1620  1666 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:21.024  1620  1669 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:21.026  1620  1774 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-12 17:45:21.026  1620  1774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.038  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:21.038  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.040  1620  1673 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.040  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:21.041  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.043  1620  1620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-12 17:45:21.043  1620  1620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-12 17:45:21.122  2906  2906 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
07-12 17:45:21.158   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:21.217   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-12 17:45:21.218   542   663 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-12 17:45:21.219   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 17:45:21.225   542   585 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:21.227  1620  1774 W bt_btif : ag scb idx 1 not allocated
07-12 17:45:21.228  1620  1774 E bt_btif : BTA AG is already disabled, ignoring ...
07-12 17:45:21.230  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:21.237   217   632 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:21.232  1620  1673 I bt_hci  : shut_down
07-12 17:45:21.233  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:21.245  1620  1679 I bt_vendor: low_power_mode_cb
07-12 17:45:21.252  1620  1679 D bt_hwcfg: hw_epilog_process
07-12 17:45:21.254  1075  1075 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-12 17:45:21.259  1620  1679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-12 17:45:21.259  1620  1679 I bt_vendor: epilog_cb
,07-12 17:45:21.259  1620  1679 I bt_hci  : epilog_finished_callback
,07-12 17:45:21.263  1620  1673 I bt_hci_h4: hal_close
,07-12 17:45:21.264  1620  1673 I bt_userial_vendor: device fd = 49 close
,07-12 17:45:21.342  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:21.402   217   632 E Netd    : netlink response contains error (No such file or directory)
07-12 17:45:21.404   542   661 D DhcpClient: doQuit
,07-12 17:45:21.405   542   661 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:21.405   542  2261 D DhcpClient: onQuitting
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.413  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:21.415  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:21.418  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:21.420  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:21.421  1074  1074 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,07-12 17:45:21.468  1074  1074 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:21.468   542   585 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb488:true
,07-12 17:45:21.475  1074  1074 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-12 17:45:21.488  1083  2283 I art     : Waiting for a blocking GC DisableMovingGc
,07-12 17:45:21.489  1083  2304 I art     : Waiting for a blocking GC DisableMovingGc
,07-12 17:45:21.511  1083  2283 I art     : WaitForGcToComplete blocked for 22.127ms for cause DisableMovingGc
,07-12 17:45:21.511  1083  2283 I art     : Starting a blocking GC DisableMovingGc
07-12 17:45:21.512  1074  1074 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-12 17:45:21.512  1083  2304 I art     : WaitForGcToComplete blocked for 22.755ms for cause DisableMovingGc
07-12 17:45:21.512  1083  2304 I art     : Starting a blocking GC DisableMovingGc
07-12 17:45:21.514  1620  1669 D bt_stack_manager: event_shut_down_stack finished.
07-12 17:45:21.515  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-12 17:45:21.515  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:21.517  1620  1666 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17:45:21.517  1620  1620 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:21.518  1620  1620 D BtGatt.GattService: Received stop request...Stopping profile...
07-12 17:45:21.518  1620  1620 D BtGatt.GattService: stop()
07-12 17:45:21.518  1620  1620 D BtGatt.AdvertiseManager: advertise clients cleared
07-12 17:45:21.521  1074  1074 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-12 17:45:21.536   542  1342 I ActivityManager: Start proc 2931:com.google.android.apps.maps/u0a60 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 17:45:21.539  1620  1620 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:21.539  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:21.539  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:21.539  1620  1620 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:21.539  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-12 17:45:21.540  1620  1666 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:21.540  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:21.541   542   585 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,07-12 17:45:21.541  1620  1666 I BluetoothAdapterState: Entering OffState
07-12 17:45:21.564  1620  1620 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-12 17:45:21.567  1620  1620 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-12 17:45:21.567  1620  1620 I BluetoothServiceJni: cleanupNative: return from cleanup
07-12 17:45:21.568  1620  1669 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:21.569  2906  2906 D LocalBluetoothProfileManager: Adding local MAP profile
07-12 17:45:21.573  2906  2906 D BluetoothMap: Create BluetoothMap proxy object
07-12 17:45:21.580  1620  1669 D bt_stack_manager: event_clean_up_stack finished.
,07-12 17:45:21.582  2906  2906 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-12 17:45:21.588  2906  2906 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 17:45:21.593  1620  1620 I art     : System.exit called, status: 0
07-12 17:45:21.593  1620  1620 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:21.601  2906  2906 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:21.607   542  1341 I ActivityManager: Killing 2563:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-12 17:45:21.641   542   560 I ActivityManager: Process com.android.bluetooth (pid 1620) has died
,07-12 17:45:21.645   542   661 D wifi    : In wifi stop Hal
,07-12 17:45:21.645   542   661 D wifi    : halHandle = 0x555dbe8490, mVM = 0x555d788c30, mCls = 0x100aee
07-12 17:45:21.646   542  1073 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:21.646   542  1073 D WifiHAL : Got a signal to exit!!!
07-12 17:45:21.646   542  1073 I WifiHAL : Exit wifi_event_loop
07-12 17:45:21.648   542   661 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-12 17:45:21.648   542   661 E WifiHAL : Event processing terminated
07-12 17:45:21.648   542   661 D wifi    : In wifi cleaned up handler
07-12 17:45:21.648   542   661 I WifiHAL : Internal cleanup completed
,07-12 17:45:21.650  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:21.651  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:21.664  1007  1289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 17:45:21.668  2931  2931 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,07-12 17:45:21.764   542  1073 D wifi    : set interface wlan0 flags (DOWN)
,07-12 17:45:21.765   542   661 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:22.005  2931  2931 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.005  2931  2931 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.005  2931  2931 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.005  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.006  2931  2931 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.006  2931  2931 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.006  2931  2931 D Stri,ctMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.006  2931  2931 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at an,droid.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.006  2931  2931 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invo,ke(Native Method)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.006  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.007  2931  2931 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 17:45:22.007  2931  2931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 17:45:22.016  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:22.046   542  1240 I ActivityManager: Start proc 2960:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-12 17:45:22.056  2906  2906 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:22.060   542   560 I ActivityManager: Killing 1652:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-12 17:45:22.227  2931  2951 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 17:45:22.247  2960  2960 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:22.249  2960  2960 D AdapterServiceConfig: Adding A2dpService
,07-12 17:45:22.249  2960  2960 D AdapterServiceConfig: Adding HidService
07-12 17:45:22.249  2960  2960 D AdapterServiceConfig: Adding HealthService
07-12 17:45:22.250  2960  2960 D AdapterServiceConfig: Adding PanService
07-12 17:45:22.250  2960  2960 D AdapterServiceConfig: Adding GattService
,07-12 17:45:22.257   542   585 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c557185:true
,07-12 17:45:22.261  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:22.300  1213  1213 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-12 17:45:22.307  1213  2288 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:22.310  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:22.312  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-12 17:45:22.315  1213  2288 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:22.316  1213  2288 I iu.SyncManager: NEXT; no task
,07-12 17:45:22.325   542   752 I ActivityManager: Start proc 2975:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-12 17:45:22.457   542  1066 I ActivityManager: Start proc 2989:com.google.android.talk/u0a56 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,07-12 17:45:22.458   542  1066 I ActivityManager: Killing 2606:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-12 17:45:22.558  2989  2989 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-12 17:45:22.733  2989  3006 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-12 17:45:22.733  2989  3006 I Babel_SMS: MmsConfig.loadMmsSettings
,07-12 17:45:22.739  2989  3006 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=, mUaProfUrl=
,07-12 17:45:22.739  2989  3006 I Babel_SMS: MmsConfig.loadFromDatabase
,07-12 17:45:22.798  2989  3006 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-12 17:45:22.800  2989  3006 I Babel_SMS: MmsConfig.loadFromResources
,07-12 17:45:22.804  2989  3006 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-12 17:45:22.805  2989  3006 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Hangouts/4.1.102314611, mUaProfUrl=https://ssl.gstatic.com/android/hangouts/hangouts_mms_ua_profile.xml
,07-12 17:45:22.834  2989  2989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 17:45:22.853  2989  2989 I Babel_Crash: startup - clean
,07-12 17:45:22.944   542  1342 I ActivityManager: Start proc 3009:com.google.android.apps.magazines/u0a62 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 17:45:23.047  3009  3009 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm64
,07-12 17:45:23.055  2989  2989 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-12 17:45:23.088  2989  2989 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-12 17:45:23.098  2989  2989 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-12 17:45:23.102  2989  2989 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-12 17:45:23.108  2989  2989 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-12 17:45:23.114  2989  2989 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-12 17:45:23.128  2989  2989 I vclib   : onServiceConnected
,07-12 17:45:23.134  2989  3021 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-12 17:45:23.160   542   752 I ActivityManager: Killing 2480:android.process.acore/u0a3 (adj 15): empty #17
,07-12 17:45:23.210  3009  3009 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 17:45:23.210  3009  3009 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 17:45:23.210  3009  3009 I GAv4    :   adb logcat -s GAv4
,07-12 17:45:23.223  3009  3009 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:23.229  3009  3009 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:23.236  3009  3028 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 17:45:23.365  3009  3009 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-12 17:45:23.427  3009  3009 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-12 17:45:23.438  3009  3009 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9823-9827)
07-12 17:45:23.438  3009  3009 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:45:23.457  3009  3009 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fd775ca}
,07-12 17:45:23.460  3009  3009 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:45:23.460  3009  3009 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 17:45:23.468  3009  3009 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 17:45:23.482  3009  3009 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 17:45:23.549  3009  3009 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 17:45:23.557  3009  3009 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:45:23.557  3009  3009 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 17:45:23.733  3009  3056 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 17:45:23.740  3009  3009 I NSApplication: Starting up...
,07-12 17:45:23.760   542  1245 I ActivityManager: Start proc 3061:com.google.android.apps.photos/u0a66 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 17:45:23.761   542  1245 I ActivityManager: Killing 2660:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-12 17:45:23.828  3061  3061 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 17:45:24.023   542  1245 I ActivityManager: Killing 2676:com.android.musicfx/u0a14 (adj 15): empty #17
,07-12 17:45:25.850   542  1240 D WifiService: setWifiEnabled: true pid=2819, uid=10000
,07-12 17:45:25.851   542  1240 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:25.859   217   632 D SoftapController: Softap fwReload - Ok
,07-12 17:45:25.864   217   632 D CommandListener: Setting iface cfg
07-12 17:45:25.864   217   632 D CommandListener: Trying to bring down wlan0
07-12 17:45:25.866   217   632 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:25.870   542   661 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:26.541   542   661 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:26.541   542   661 I WifiHAL : Initializing wifi
07-12 17:45:26.541   542   661 I WifiHAL : Creating socket
07-12 17:45:26.544   542   661 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 17:45:26.545   542   661 D wifi    : Did set static halHandle = 0x555df67dd0
,07-12 17:45:26.545   542   661 D wifi    : halHandle = 0x555df67dd0, mVM = 0x555d788c30, mCls = 0x1019be
,07-12 17:45:26.545   542   661 D wifi    : array field set
07-12 17:45:26.545   542   661 I WifiNative-HAL: interface[0] = wlan0
07-12 17:45:26.551   542  3079 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=366648655312
07-12 17:45:26.551   542  3079 D wifi    : waitForHalEvents called, vm = 0x555d788c30, obj = 0x1019be, env = 0x555e05e340
,07-12 17:45:26.619  3080  3080 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:26.647   542   661 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 17:45:26.651  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:26.652  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:26.707  3080  3080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:26.763  3080  3080 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:26.763  3080  3080 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:26.805  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:26.805  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:26.806  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:26.806  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:26.809   542   661 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:26.838   542   661 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:26.843   542   661 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-12 17:45:26.844   542   661 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 17:45:26.845   542   661 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:26.845   542   661 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 17:45:26.845   542   661 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 17:45:26.845   542   661 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 17:45:26.852   542   661 D WifiNative-HAL: Setting external_sim to 1
,07-12 17:45:26.852   542   661 D wifi    : setting dfs flag to true, 0x555dd0fb50
,07-12 17:45:26.853   542   661 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 17:45:26.853  2989  2989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:26.853   542   661 D wifi    : setting scan oui 0x555dd0fb50
07-12 17:45:26.853   542   661 D WifiHAL : Sending mac address OUI
,07-12 17:45:26.872   542   661 E native  : do suspend true
,07-12 17:45:26.879   217   632 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-12 17:45:26.880   217   632 D CommandListener: Setting iface cfg
07-12 17:45:26.881   542   542 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:26.881   542   661 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-12 17:45:26.881   542   660 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '60 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 60 Failed to set address (No such device)'
,07-12 17:45:26.882   542   660 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-12 17:45:26.882   542   661 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-12 17:45:26.882   542   676 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 17:45:26.894   542   660 D WifiNative-HAL: p2pGetDeviceAddress
07-12 17:45:26.895   542   660 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-12 17:45:26.927   542   577 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=173316 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=24 mControllerEnergyUsed=91 }
,07-12 17:45:27.383   542   957 I ActivityManager: Killing 2220:com.google.android.gms.wearable/u0a7 (adj 15): empty #17
,07-12 17:45:29.335  3080  3080 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 17:45:29.366   542   661 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 17:45:29.378   542   661 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
07-12 17:45:29.378   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:29.391   542   661 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-12 17:45:29.445   542   661 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 17:45:29.767  3080  3080 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 17:45:29.804  3080  3080 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 17:45:29.805  3080  3080 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-12 17:45:29.814   542   661 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 17:45:29.825   542   661 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:29.825   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-12 17:45:29.825   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:29.844   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:29.859   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:29.871   542   661 D WifiStateMachine: Start Dhcp Watchdog 2
,07-12 17:45:29.884   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-12 17:45:29.901   542  3088 D DhcpClient: Receive thread started
,07-12 17:45:29.991   542   661 E native  : do suspend false
,07-12 17:45:30.011   542  3087 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 17:45:30.029   542  3088 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172665, domain null
,07-12 17:45:30.030   542  3087 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172665 seconds
,07-12 17:45:30.032   542  3087 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-12 17:45:30.052   542  3088 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 17:45:30.053   542  3087 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-12 17:45:30.056   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:30.064   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
,07-12 17:45:30.067   542   661 E native  : do suspend true
,07-12 17:45:30.068   542  3087 D DhcpClient: Scheduling renewal in 86399s
,07-12 17:45:30.083   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 17:45:30.086   542   661 D WifiConfigStore: No blacklist allowed without epno enabled
,07-12 17:45:30.087   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 17:45:30.089   542   663 D ConnectivityService: Adding iface wlan0 to network 101
07-12 17:45:30.095   542   661 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 17:45:30.156   542   663 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-12 17:45:30.156   542   663 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-12 17:45:30.158   542   663 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-12 17:45:30.161   542   663 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-12 17:45:30.162   542   663 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-12 17:45:30.177   542   663 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-12 17:45:30.185   542   663 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-12 17:45:30.185   542   663 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-12 17:45:30.186   542   661 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 17:45:30.186   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 17:45:30.186   542   663 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-12 17:45:30.187   542   663 D ConnectivityService:    accepting network in place of null
07-12 17:45:30.188   542   663 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:30.207   542  3086 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176596, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:30.235   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:30.282   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:30.287   542   663 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-12 17:45:30.289   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:30.296   542   585 D Tethering: MasterInitialState.processMessage what=3
,07-12 17:45:30.302   542  3085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:809::200e
,07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:30.304  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:30.305  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:30.307  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 17:45:30.307  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 17:45:30.311   542   663 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-12 17:45:30.320  1075  1075 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-12 17:45:30.352  1213  1213 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 17:45:30.360  1213  2288 I iu.UploadsManager: num queued entries: 0
,07-12 17:45:30.360  1213  2288 I iu.UploadsManager: num updated entries: 0
,07-12 17:45:30.363  1213  2288 I iu.SyncManager: NEXT; no task
,07-12 17:45:30.364  1213  3100 I MDM     : [203] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
07-12 17:45:30.364  1213  3100 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 17:45:30.366  1213  3100 V GoogleAuthProtoRequest: [203] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:45:30.367  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:30.368  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
07-12 17:45:30.370   542  3085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 15:45:30 GMT], X-Android-Received-Millis=[1468338330369], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468338330340]}
07-12 17:45:30.371   542   663 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 17:45:30.371   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-12 17:45:30.373   542   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
07-12 17:45:30.374   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 17:45:30.391  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:30.396  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:30.451  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-12 17:45:30.451  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-12 17:45:30.451  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:30.451  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:30.469  1213  3100 E MDM     : [203] SitrepService.a: Error sending sitrep.
,07-12 17:45:30.536  2989  3103 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-12 17:45:30.728  1213  1213 I GCM     : Message from null null
,07-12 17:45:30.728  1213  1213 E GCM     : Dropping message from null
,07-12 17:45:30.858   542  1066 D WifiService: setWifiEnabled: false pid=2819, uid=10000
,07-12 17:45:30.858   542  1066 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:30.869   542   661 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-12 17:45:30.870   542   661 D IpReachabilityMonitor: clear: iface{wlan0/6}, v{4}, ntable=[]
07-12 17:45:30.870   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 17:45:30.871   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:30.885   542   661 E native  : do suspend true
,07-12 17:45:30.896   542  3087 D DhcpClient: Clearing IP address
,07-12 17:45:30.897   217   632 D CommandListener: Clearing all IP addresses on wlan0
07-12 17:45:30.900   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:30.902  1083  3107 V NativeCrypto: Read error: ssl=0x555dc93030: I/O error during system call, Connection timed out
,07-12 17:45:30.910  1083  3107 V NativeCrypto: SSL shutdown failed: ssl=0x555dc93030: I/O error during system call, Broken pipe
07-12 17:45:30.912   542  3088 D DhcpClient: Receive thread stopped
07-12 17:45:30.918   542   752 D ConnectivityService: reportNetworkConnectivity(101, false) by 10007
07-12 17:45:30.918   542  3085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10007
07-12 17:45:30.919   542  3085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:809::200e
07-12 17:45:30.932   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-12 17:45:30.932   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-12 17:45:30.937   542   542 D RttService: SCAN_AVAILABLE : 1
,07-12 17:45:30.939   542   676 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:30.939   542  3085 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:809::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,07-12 17:45:30.952   542   663 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,07-12 17:45:30.953   542   661 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-12 17:45:30.965   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:30.965   542   661 E native  : do suspend true
,07-12 17:45:31.011   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:31.055   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:31.055   217   632 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:31.056   542   663 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-12 17:45:31.056   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 17:45:31.059   542   585 D Tethering: MasterInitialState.processMessage what=3
,07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.064  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:31.064  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.067  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.067  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.069   542   661 D DhcpClient: doQuit
07-12 17:45:31.069   542   661 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-12 17:45:31.070   542  3087 D DhcpClient: onQuitting
07-12 17:45:31.072  3080  3080 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.075  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:31.075  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:31.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:31.076  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:31.086  1075  1075 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-12 17:45:31.099  1213  1213 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-12 17:45:31.102  1213  2288 I iu.UploadsManager: num queued entries: 0
07-12 17:45:31.102  1213  2288 I iu.UploadsManager: num updated entries: 0
07-12 17:45:31.110  1213  2288 I iu.SyncManager: NEXT; no task
,07-12 17:45:31.114  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-12 17:45:31.115  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
07-12 17:45:31.129  3080  3080 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
07-12 17:45:31.135  3080  3080 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-12 17:45:31.161  3080  3080 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-12 17:45:31.161  3080  3080 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-12 17:45:31.198  2989  3119 I Babel   : connection state changed from CONNECTED to DISCONNECTED
07-12 17:45:31.204   217   632 E Netd    : netlink response contains error (No such file or directory)
07-12 17:45:31.206   542   663 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
07-12 17:45:31.206   542   663 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:31.266   542   661 D wifi    : In wifi stop Hal
,07-12 17:45:31.266   542   661 D wifi    : halHandle = 0x555df67dd0, mVM = 0x555d788c30, mCls = 0x1019be
07-12 17:45:31.268   542  3079 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-12 17:45:31.268   542  3079 D WifiHAL : Got a signal to exit!!!
07-12 17:45:31.268   542  3079 I WifiHAL : Exit wifi_event_loop
07-12 17:45:31.268  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:31.270  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:31.270   542   661 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-12 17:45:31.270   542   661 E WifiHAL : Event processing terminated
07-12 17:45:31.271   542   661 D wifi    : In wifi cleaned up handler
07-12 17:45:31.271   542   661 I WifiHAL : Internal cleanup completed
07-12 17:45:31.272  2989  2989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:31.279  1007  1289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 17:45:31.288   542   663 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-12 17:45:31.388   542  3079 D wifi    : set interface wlan0 flags (DOWN)
07-12 17:45:31.389   542   661 D WifiNative-HAL: HAL event thread stopped successfully
,07-12 17:45:35.903   542   585 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f57d49:true
,07-12 17:45:35.904  2960  2960 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:35.911  2960  2960 I bt_bluedroid: init
07-12 17:45:35.911  2960  3126 I BluetoothAdapterState: Entering OffState
,07-12 17:45:35.916  2960  3127 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 17:45:35.916  2960  3127 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:35.916  2960  3127 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:35.916  2960  3127 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:35.919  2960  2960 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:35.922  2960  2960 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:35.925  2960  3130 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-12 17:45:35.927  2960  2971 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:35.928  2960  3130 D BluetoothAdapterProperties: Name is: Nexus 9
,07-12 17:45:35.930   542   585 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-12 17:45:35.936  2960  3126 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 17:45:35.936  2960  3126 D BluetoothAdapterProperties: Setting state to 14
07-12 17:45:35.936  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 17:45:35.939  2960  3126 D BluetoothBondStateMachine: make
,07-12 17:45:35.944  2960  3131 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:35.948  2960  3126 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:35.949  2960  2960 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 17:45:35.952  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:35.954  2960  2960 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-12 17:45:35.955  2960  2960 D BtGatt.GattService: Received start request. Starting profile...
,07-12 17:45:35.955  2960  2960 D BtGatt.GattService: start()
07-12 17:45:35.955  2960  2960 I bt_bluedroid: get_profile_interface gatt
,07-12 17:45:35.956  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
07-12 17:45:35.956  2960  2960 D BtGatt.AdvertiseManager: advertise manager created
,07-12 17:45:35.966  2960  2960 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:35.967  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:35.967  2960  2960 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:35.967  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:35.967  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-12 17:45:35.968  2960  3126 I bt_bluedroid: enable
,07-12 17:45:35.968  2960  3127 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 17:45:35.969  2960  3127 I bt_hci  : start_up
,07-12 17:45:35.983  2960  3127 I bt_vendor: alloc value 0xf3d7e889
,07-12 17:45:35.983  2960  3127 I bt_vendor: init
07-12 17:45:35.983  2960  3127 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-12 17:45:36.186  2960  3127 D bt_hci  : start_up starting async portion
,07-12 17:45:36.186  2960  3134 I bt_hci  : event_finish_startup
,07-12 17:45:36.186  2960  3134 I bt_hci_h4: hal_open
07-12 17:45:36.186  2960  3134 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
07-12 17:45:36.187  2960  3134 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:36.198  2960  3134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:36.234  2960  3134 D bt_hwcfg: Chipset BCM4350C0
,07-12 17:45:36.235  2960  3134 D bt_hwcfg: Target name = [BCM4350C0]
,07-12 17:45:36.235  2960  3134 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-12 17:45:36.841  2960  3134 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-12 17:45:36.841  2960  3134 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:36.842  2960  3134 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:36.949  2960  3134 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:36.949  2960  3134 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-12 17:45:36.987  2960  3134 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:36.987  2960  3134 I bt_vendor: firmware callback
07-12 17:45:36.987  2960  3134 I bt_hci  : firmware_config_callback
,07-12 17:45:36.999  2960  3136 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:36.999  2960  3136 I bt_btu_task: Bluetooth chip preload is complete
07-12 17:45:37.000  2960  3136 I bt_btu  : btu_task received preload complete event
,07-12 17:45:37.010  2960  3136 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:37.010  2960  3136 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 17:45:37.011  2960  3136 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_PAN
,07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-12 17:45:37.012  2960  3136 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:37.237  2960  3136 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cfca31
,07-12 17:45:37.237  2960  3136 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cfca31 
,07-12 17:45:37.269  2960  3130 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-12 17:45:37.273  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:37.273  2960  3130 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-12 17:45:37.276  2960  3130 D BluetoothAdapterProperties: Name is: Nexus 9
07-12 17:45:37.282  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:37.285  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:37.285  2960  3130 D BluetoothAdapterProperties: Scan Mode:20
,07-12 17:45:37.286  2960  3130 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:37.286  2960  3130 D bt_hci  : do_postload posting postload work item
07-12 17:45:37.287  2960  3134 I bt_hci  : event_postload
07-12 17:45:37.287  2960  3134 I bt_vendor: sco_config_cb
,07-12 17:45:37.287  2960  3134 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:37.293  2960  3130 D bt_bte_conf: Device ID record 1 : primary
,07-12 17:45:37.293  2960  3130 D bt_bte_conf:   vendorId            = 000f
,07-12 17:45:37.293  2960  3130 D bt_bte_conf:   vendorIdSource      = 0001
07-12 17:45:37.293  2960  3130 D bt_bte_conf:   product             = 1200
07-12 17:45:37.293  2960  3130 D bt_bte_conf:   version             = 1436
07-12 17:45:37.293  2960  3130 D bt_bte_conf:   clientExecutableURL = 
,07-12 17:45:37.293  2960  3130 D bt_bte_conf:   serviceDescription  = 
07-12 17:45:37.293  2960  3130 D bt_bte_conf:   documentationURL    = 
07-12 17:45:37.294  2960  3130 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-12 17:45:37.294  2960  3127 D bt_stack_manager: event_start_up_stack finished
,07-12 17:45:37.294  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 17:45:37.295  2960  3126 D BluetoothAdapterProperties: Setting state to 15
,07-12 17:45:37.295  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 17:45:37.298  2960  3134 I bt_vendor: low_power_mode_cb
,07-12 17:45:37.298  2960  3126 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:37.301  2960  3126 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 17:45:37.301  2960  3126 D BluetoothAdapterProperties: Setting state to 11
,07-12 17:45:37.301  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:37.308  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
07-12 17:45:37.313  2960  2960 D HeadsetService: Received start request. Starting profile...
07-12 17:45:37.317  2960  2960 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 17:45:37.323  2960  2960 D HeadsetStateMachine: make
07-12 17:45:37.332  2960  3126 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:37.340  2960  2960 D HeadsetStateMachine: max_hf_connections = 1
07-12 17:45:37.341  2960  2960 I bt_bluedroid: get_profile_interface handsfree
,07-12 17:45:37.341  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-12 17:45:37.342  2960  3130 E bt_btif : btif_hf_upstreams_evt: Invalid index 15676
,07-12 17:45:37.355  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:37.356  2960  2960 D A2dpService: Received start request. Starting profile...
,07-12 17:45:37.357  2960  2960 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:37.357  2960  2960 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:37.371  2960  2960 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:37.371  2960  2960 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:37.371  2960  2960 D A2dpStateMachine: make
,07-12 17:45:37.374  2960  2960 I bt_bluedroid: get_profile_interface a2dp
,07-12 17:45:37.375  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-12 17:45:37.380  2960  3145 D A2dpStateMachine: Enter Disconnected: -2
,07-12 17:45:37.380  2960  2960 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 17:45:37.383  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:37.386  2906  2906 D BluetoothInputDevice: Proxy object connected
,07-12 17:45:37.386  2960  2960 D HidService: Received start request. Starting profile...
07-12 17:45:37.386  2960  2960 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:37.387  2906  2906 D HidProfile: Bluetooth service connected
07-12 17:45:37.387  2960  3130 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cde099
07-12 17:45:37.387  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-12 17:45:37.387  2960  2960 D HidService: setHidService(): set to: null
07-12 17:45:37.388  2960  2960 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 17:45:37.392  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:37.393  2960  2960 D HealthService: Received start request. Starting profile...
,07-12 17:45:37.396  2960  2960 I bt_bluedroid: get_profile_interface health
,07-12 17:45:37.397  2960  2960 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 17:45:37.398  2960  2960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:37.401  2906  2906 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 17:45:37.401  2960  2960 D PanService: Received start request. Starting profile...
,07-12 17:45:37.402  2906  2906 D PanProfile: Bluetooth service connected
07-12 17:45:37.402  2960  2960 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:37.402  2960  2960 I bt_bluedroid: get_profile_interface pan
,07-12 17:45:37.403  2960  3130 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 17:45:37.413  2960  2960 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:37.413  2960  2960 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:37.413  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.413  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.417  2960  3142 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-12 17:45:37.418  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:37.418  2960  2960 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:37.421  2960  2960 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:37.421  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.421  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:37.422  2960  2960 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:37.422  2960  2960 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:37.422  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.422  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.422  2960  2960 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:37.423  2960  2960 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:37.423  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:37.423  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:37.424  2960  2960 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:37.424  2960  2960 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:37.424  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:37.425  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:37.425  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 17:45:37.425  2960  3126 D BluetoothAdapterProperties: ScanMode =  20
,07-12 17:45:37.426  2960  3126 D BluetoothAdapterProperties: State =  11
07-12 17:45:37.427  2960  3126 D BluetoothAdapterProperties: Setting state to 12
07-12 17:45:37.427  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-12 17:45:37.430   706   730 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 17:45:37.435  2960  3130 D BluetoothAdapterProperties: Scan Mode:21
,07-12 17:45:37.435  2960  3130 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 17:45:37.436  2960  3126 I BluetoothAdapterState: Entering OnState
07-12 17:45:37.437  2906  2917 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:37.438  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:37.440   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 17:45:37.442   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:37.442   706  2922 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:37.443  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:37.448   706   706 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:37.448  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:37.448   706   706 D PanProfile: Bluetooth service connected
07-12 17:45:37.450   706  2918 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:37.451  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:37.455   706   706 D BluetoothA2dp: Proxy object connected
,07-12 17:45:37.455   706   891 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:37.456  2906  2919 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:37.456   706   730 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:37.457   706   706 D BluetoothInputDevice: Proxy object connected
,07-12 17:45:37.458   706   706 D HidProfile: Bluetooth service connected
07-12 17:45:37.461  1028  1130 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:37.462   706  2922 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:37.462   706  2922 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-12 17:45:37.462  2906  2917 D BluetoothMap: onBluetoothStateChange: up=true
,07-12 17:45:37.463  2906  2917 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-12 17:45:37.463   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:37.463   542   585 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:37.464   542   542 D BluetoothA2dp: Proxy object connected
07-12 17:45:37.464  2906  2919 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 17:45:37.468   542   542 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 17:45:37.470  2906  2906 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 17:45:37.475  2906  2906 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 17:45:37.483  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:37.487  2906  2906 D BluetoothA2dp: Proxy object connected
,07-12 17:45:37.492  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 17:45:37.505   706   706 D BluetoothPbap: Proxy object connected
,07-12 17:45:37.505   706   706 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:37.507  2906  2906 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:37.508  2906  2906 D BluetoothPbap: Proxy object connected
07-12 17:45:37.512  2906  2906 D PbapServerProfile: Bluetooth service connected
,07-12 17:45:37.563   542   542 D BluetoothHeadset: Proxy object connected
,07-12 17:45:37.563   542   585 D BluetoothHeadset: Proxy object connected
07-12 17:45:37.563   706   734 D BluetoothHeadset: Proxy object connected
07-12 17:45:37.564   706   706 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:37.564   542   542 D BluetoothHeadset: Proxy object connected
07-12 17:45:37.564  1028  1054 D BluetoothHeadset: Proxy object connected
07-12 17:45:37.565   542   542 D BluetoothHeadset: Proxy object connected
,07-12 17:45:37.573  2960  3154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 17:45:37.579  2906  2917 D BluetoothHeadset: Proxy object connected
,07-12 17:45:37.580  2906  2906 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:37.584  2960  3158 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:37.586  2960  3158 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:38.193   542   663 D ConnectivityService: handlePromptUnvalidated 101
,07-12 17:45:38.712  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:38.717  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:38.719  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:38.740  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 17:45:38.740  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 17:45:38.740  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:38.740  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:45:38.757  2504  2504 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-12 17:45:38.757  2504  2504 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 17:45:38.757  2504  2504 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-12 17:45:40.875  2960  3126 D BluetoothAdapterState: Current state: ON, message: 23
,07-12 17:45:40.875  2960  3126 D BluetoothAdapterProperties: Setting state to 13
,07-12 17:45:40.875  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-12 17:45:40.877  2960  3126 D BluetoothAdapterProperties: onBluetoothDisable()
,07-12 17:45:40.880  2960  3126 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:40.882  2960  3130 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:40.882  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:40.896  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:40.898  2960  2960 D HeadsetService: Received stop request...Stopping profile...
,07-12 17:45:40.898  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:40.900  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:40.902  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:40.906  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:40.914   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.917   706   730 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.917  2960  2960 D A2dpService: Received stop request...Stopping profile...
07-12 17:45:40.918  2960  3145 D A2dpStateMachine: Exit Disconnected: -1
07-12 17:45:40.919   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.919  2906  2917 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.920  1028  1060 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.920   542   542 D BluetoothHeadset: Proxy object disconnected
07-12 17:45:40.922   542   542 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:40.923  2960  2960 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:40.923  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:40.923  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:40.923  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:40.925  2960  2960 D HidService: Received stop request...Stopping profile...
,07-12 17:45:40.925   706   706 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:40.925  2960  2960 D HidService: Stopping Bluetooth HidService
07-12 17:45:40.925   706   706 D BluetoothA2dp: Proxy object disconnected
,07-12 17:45:40.925   706   706 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:40.926   706   706 D HidProfile: Bluetooth service disconnected
07-12 17:45:40.929  2960  2960 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-12 17:45:40.929  2960  2960 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-12 17:45:40.929  2960  3136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:40.930  2960  3136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-12 17:45:40.930  2960  2960 I BtOppRfcommListener: stopping Accept Thread
07-12 17:45:40.930  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-12 17:45:40.930  2960  3130 E bt_btif : btif_hf_upstreams_evt: Invalid index 25349
07-12 17:45:40.936  2906  2906 D DockEventReceiver: finishStartingService: stopping service
07-12 17:45:40.937  2960  3158 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-12 17:45:40.939  2906  2906 D HeadsetProfile: Bluetooth service disconnected
07-12 17:45:40.941  2960  3158 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-12 17:45:40.941  2906  2906 D BluetoothA2dp: Proxy object disconnected
07-12 17:45:40.941  2906  2906 D BluetoothInputDevice: Proxy object disconnected
07-12 17:45:40.941  2906  2906 D HidProfile: Bluetooth service disconnected
07-12 17:45:40.945  2960  2960 D HealthService: Received stop request...Stopping profile...
07-12 17:45:40.948  2960  2960 D PanService: Received stop request...Stopping profile...
07-12 17:45:40.950   706   706 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:40.950   706   706 D PanProfile: Bluetooth service disconnected
07-12 17:45:40.951  2960  2960 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:40.951  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:40.951  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:40.951  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:40.953  2960  2960 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:40.953  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:40.953  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:40.953  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:40.953  2960  2960 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-12 17:45:40.954  2960  2960 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-12 17:45:40.955  2960  3136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:40.955  2960  3136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:40.955  2960  3136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:40.955  2960  3136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:40.955  2960  3136 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-12 17:45:40.955  2960  3136 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-12 17:45:40.956  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-12 17:45:40.956  2960  3130 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-12 17:45:40.956  2906  2906 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-12 17:45:40.956  2906  2906 D PanProfile: Bluetooth service disconnected
07-12 17:45:40.961  2960  2960 V BluetoothAdapterState: isTurningOff()=true
07-12 17:45:40.961  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:40.961  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:40.961  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:40.961  2960  2960 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-12 17:45:40.961  2960  3130 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-12 17:45:40.962  2960  2960 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-12 17:45:40.962  2960  2960 V BluetoothAdapterState: isTurningOff()=true
,07-12 17:45:40.962  2960  2960 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:40.962  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:40.962  2960  2960 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:40.963  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-12 17:45:40.963  2960  3126 D BluetoothAdapterProperties: Setting state to 15
07-12 17:45:40.963  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-12 17:45:40.964  2960  3126 I BluetoothAdapterState: Entering BleOnState
,07-12 17:45:40.964  2960  2960 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-12 17:45:40.965  2960  2960 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-12 17:45:40.976   706  2922 D BluetoothPbap: onBluetoothStateChange: up=false
,07-12 17:45:40.978  2906  2906 D BluetoothPbap: Proxy object disconnected
07-12 17:45:40.979  2906  2906 D PbapServerProfile: Bluetooth service disconnected
,07-12 17:45:40.985  2906  2919 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:40.986  2906  2917 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-12 17:45:40.986   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:40.986   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:40.987   706   891 D BluetoothPan: onBluetoothStateChange on: false
,07-12 17:45:40.987   706   734 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:40.988   706   730 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:40.988  2906  2919 D BluetoothPan: onBluetoothStateChange on: false
,07-12 17:45:40.989   706  2918 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-12 17:45:40.990  1028  1140 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-12 17:45:40.990   706  2920 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:40.991   706  2920 E BluetoothMap: 
07-12 17:45:40.991   706  2920 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@49ba8b0
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-12 17:45:40.991   706  2920 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:45:40.991  2906  2917 D BluetoothMap: onBluetoothStateChange: up=false
07-12 17:45:40.992  2906  2917 E BluetoothMap: 
07-12 17:45:40.992  2906  2917 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@d3bca7c
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-12 17:45:40.992  2906  2917 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:45:40.992  2906  2919 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:40.992   542   585 D BluetoothHeadset: onBluetoothStateChange: up=false
07-12 17:45:40.993   542   585 D BluetoothA2dp: onBluetoothStateChange: up=false
07-12 17:45:41.002  2906  2917 D BluetoothPbap: onBluetoothStateChange: up=false
07-12 17:45:41.005  2960  3126 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-12 17:45:41.005  2960  3126 D BluetoothAdapterProperties: Setting state to 16
07-12 17:45:41.005  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-12 17:45:41.006  2960  3126 D BluetoothAdapterProperties: onBleDisable
07-12 17:45:41.007  2960  3126 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:41.007  2960  3127 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-12 17:45:41.009  2960  3136 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-12 17:45:41.009  2960  3136 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-12 17:45:41.011  2960  3130 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:41.014  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:41.019  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:41.023  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:41.035  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 17:45:41.042  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:41.047  2906  2906 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:41.218  2960  3136 W bt_btif : ag scb idx 1 not allocated
,07-12 17:45:41.219  2960  3136 E bt_btif : BTA AG is already disabled, ignoring ...
,07-12 17:45:41.219  2960  3130 I bt_hci  : shut_down
,07-12 17:45:41.219  2960  3134 D bt_hwcfg: hw_epilog_process
,07-12 17:45:41.241  2960  3134 I bt_vendor: low_power_mode_cb
,07-12 17:45:41.252  2960  3134 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-12 17:45:41.252  2960  3134 I bt_vendor: epilog_cb
07-12 17:45:41.253  2960  3134 I bt_hci  : epilog_finished_callback
,07-12 17:45:41.257  2960  3130 I bt_hci_h4: hal_close
,07-12 17:45:41.258  2960  3130 I bt_userial_vendor: device fd = 49 close
,07-12 17:45:41.463  2960  3127 D bt_stack_manager: event_shut_down_stack finished.
,07-12 17:45:41.463  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-12 17:45:41.465  2960  2960 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:41.465  2960  3126 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-12 17:45:41.466  2960  2960 D BtGatt.GattService: Received stop request...Stopping profile...
07-12 17:45:41.466  2960  2960 D BtGatt.GattService: stop()
,07-12 17:45:41.466  2960  2960 D BtGatt.AdvertiseManager: advertise clients cleared
07-12 17:45:41.467  2960  2960 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:41.467  2960  2960 V BluetoothAdapterState: isTurningOn()=false
,07-12 17:45:41.467  2960  2960 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:41.468  2960  2960 V BluetoothAdapterState: isBleTurningOff()=true
07-12 17:45:41.468  2960  3126 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-12 17:45:41.468  2960  3126 D BluetoothAdapterProperties: Setting state to 10
07-12 17:45:41.468  2960  3126 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-12 17:45:41.468  2960  3126 I BluetoothAdapterState: Entering OffState
,07-12 17:45:41.469   542   585 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-12 17:45:41.476  2960  2960 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-12 17:45:41.476  2960  2960 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-12 17:45:41.476  2960  3127 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-12 17:45:41.476  2960  2960 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-12 17:45:41.479  2960  3127 D bt_stack_manager: event_clean_up_stack finished.
,07-12 17:45:41.481  2960  2960 I art     : System.exit called, status: 0
,07-12 17:45:41.481  2960  2960 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-12 17:45:41.514   542  1240 I ActivityManager: Process com.android.bluetooth (pid 2960) has died
,07-12 17:45:45.873  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:45.874  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:45.882  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:45.883  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5cacb65 added. We now have 6 listener(s)
07-12 17:45:45.883  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:45.887  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:45.887  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66f903a added. We now have 7 listener(s)
07-12 17:45:45.887  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:45.888  2819  2870 I System.out: IsBluetoothEnabled
,07-12 17:45:45.896  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:45.921   542   585 I ActivityManager: Start proc 3166:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 17:45:46.046  3166  3166 D AdapterServiceConfig: Adding HeadsetService
,07-12 17:45:46.046  3166  3166 D AdapterServiceConfig: Adding A2dpService
07-12 17:45:46.046  3166  3166 D AdapterServiceConfig: Adding HidService
07-12 17:45:46.046  3166  3166 D AdapterServiceConfig: Adding HealthService
07-12 17:45:46.047  3166  3166 D AdapterServiceConfig: Adding PanService
07-12 17:45:46.047  3166  3166 D AdapterServiceConfig: Adding GattService
,07-12 17:45:46.064   542   585 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8745ec5:true
,07-12 17:45:46.064  3166  3166 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 17:45:46.069  3166  3166 I bt_bluedroid: init
07-12 17:45:46.069  3166  3178 I BluetoothAdapterState: Entering OffState
,07-12 17:45:46.072  3166  3179 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 17:45:46.072  3166  3179 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-12 17:45:46.072  3166  3179 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 17:45:46.072  3166  3179 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 17:45:46.073  3166  3166 I bt_bluedroid: get_profile_interface socket
,07-12 17:45:46.076  3166  3166 I bt_bluedroid: get_profile_interface sdp
,07-12 17:45:46.079  3166  3182 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-12 17:45:46.079  3166  3176 I bt_bluedroid: config_hci_snoop_log
07-12 17:45:46.080  3166  3182 D BluetoothAdapterProperties: Name is: Nexus 9
,07-12 17:45:46.081   542   585 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-12 17:45:46.085  3166  3178 D BluetoothAdapterState: Current state: OFF, message: 0
07-12 17:45:46.086  3166  3178 D BluetoothAdapterProperties: Setting state to 14
,07-12 17:45:46.086  3166  3178 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-12 17:45:46.087  3166  3178 D BluetoothBondStateMachine: make
,07-12 17:45:46.091  3166  3183 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 17:45:46.094  3166  3178 I BluetoothAdapterState: Entering PendingCommandState
,07-12 17:45:46.095  3166  3166 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 17:45:46.098  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:46.099  3166  3166 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 17:45:46.099  3166  3166 D BtGatt.GattService: Received start request. Starting profile...
07-12 17:45:46.099  3166  3166 D BtGatt.GattService: start()
,07-12 17:45:46.099  3166  3166 I bt_bluedroid: get_profile_interface gatt
,07-12 17:45:46.100  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:46.100  3166  3166 D BtGatt.AdvertiseManager: advertise manager created
,07-12 17:45:46.109  3166  3166 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:46.109  3166  3166 V BluetoothAdapterState: isTurningOn()=false
07-12 17:45:46.109  3166  3166 V BluetoothAdapterState: isBleTurningOn()=true
07-12 17:45:46.109  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:46.109  3166  3178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 17:45:46.110  3166  3178 I bt_bluedroid: enable
,07-12 17:45:46.110  3166  3179 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-12 17:45:46.110  3166  3179 I bt_hci  : start_up
,07-12 17:45:46.121  3166  3179 I bt_vendor: alloc value 0xf3d8a889
07-12 17:45:46.121  3166  3179 I bt_vendor: init
07-12 17:45:46.121  3166  3179 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-12 17:45:46.323  3166  3179 D bt_hci  : start_up starting async portion
,07-12 17:45:46.323  3166  3186 I bt_hci  : event_finish_startup
07-12 17:45:46.323  3166  3186 I bt_hci_h4: hal_open
07-12 17:45:46.323  3166  3186 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
,07-12 17:45:46.325  3166  3186 I bt_userial_vendor: device fd = 49 open
,07-12 17:45:46.335  3166  3186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 17:45:46.372  3166  3186 D bt_hwcfg: Chipset BCM4350C0
,07-12 17:45:46.372  3166  3186 D bt_hwcfg: Target name = [BCM4350C0]
07-12 17:45:46.373  3166  3186 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-12 17:45:46.989  3166  3186 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-12 17:45:46.990  3166  3186 D bt_hwcfg: Settlement delay -- 100 ms
07-12 17:45:46.990  3166  3186 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 17:45:47.098  3166  3186 I bt_hwcfg: bt vendor lib: set UART baud 3000000
07-12 17:45:47.098  3166  3186 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-12 17:45:47.134  3166  3186 I bt_hwcfg: vendor lib fwcfg completed
,07-12 17:45:47.134  3166  3186 I bt_vendor: firmware callback
,07-12 17:45:47.135  3166  3186 I bt_hci  : firmware_config_callback
,07-12 17:45:47.145  3166  3188 I bt_btu  : btu_task pending for preload complete event
,07-12 17:45:47.146  3166  3188 I bt_btu_task: Bluetooth chip preload is complete
,07-12 17:45:47.146  3166  3188 I bt_btu  : btu_task received preload complete event
,07-12 17:45:47.157  3166  3188 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_AVDT
07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_AVRC
07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_A2D
07-12 17:45:47.158  3166  3188 I         : BTE_InitTraceLevels -- TRC_BNEP
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_GATT
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 17:45:47.159  3166  3188 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 17:45:47.160  3166  3188 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 17:45:47.255   542   552 I art     : Background partial concurrent mark sweep GC freed 52858(3MB) AllocSpace objects, 5(116KB) LOS objects, 33% free, 17MB/26MB, paused 1.261ms total 101.141ms
,07-12 17:45:47.399  3166  3188 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d08a31
,07-12 17:45:47.400  3166  3188 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d08a31 
,07-12 17:45:47.410  3166  3182 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-12 17:45:47.411  3166  3182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-12 17:45:47.412  3166  3182 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-12 17:45:47.415  3166  3182 D BluetoothAdapterProperties: Name is: Nexus 9
07-12 17:45:47.420  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:47.421  3166  3182 D BluetoothAdapterProperties: Scan Mode:20
07-12 17:45:47.421  3166  3182 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:47.422  3166  3182 D bt_hci  : do_postload posting postload work item
,07-12 17:45:47.422  3166  3186 I bt_hci  : event_postload
,07-12 17:45:47.422  3166  3186 I bt_vendor: sco_config_cb
07-12 17:45:47.422  3166  3186 I bt_hci  : sco_config_callback postload finished.
07-12 17:45:47.426  3166  3182 D bt_bte_conf: Device ID record 1 : primary
,07-12 17:45:47.426  3166  3182 D bt_bte_conf:   vendorId            = 000f
07-12 17:45:47.426  3166  3182 D bt_bte_conf:   vendorIdSource      = 0001
07-12 17:45:47.427  3166  3182 D bt_bte_conf:   product             = 1200
,07-12 17:45:47.427  3166  3182 D bt_bte_conf:   version             = 1436
07-12 17:45:47.427  3166  3182 D bt_bte_conf:   clientExecutableURL = 
,07-12 17:45:47.428  3166  3182 D bt_bte_conf:   serviceDescription  = 
,07-12 17:45:47.428  3166  3182 D bt_bte_conf:   documentationURL    = 
,07-12 17:45:47.428  3166  3182 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 17:45:47.429  3166  3179 D bt_stack_manager: event_start_up_stack finished
07-12 17:45:47.430  3166  3178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-12 17:45:47.431  3166  3178 D BluetoothAdapterProperties: Setting state to 15
,07-12 17:45:47.431  3166  3178 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-12 17:45:47.434  3166  3186 I bt_vendor: low_power_mode_cb
07-12 17:45:47.437  3166  3178 I BluetoothAdapterState: Entering BleOnState
07-12 17:45:47.437  3166  3178 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-12 17:45:47.437  3166  3178 D BluetoothAdapterProperties: Setting state to 11
,07-12 17:45:47.437  3166  3178 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-12 17:45:47.442  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:47.444  3166  3166 D HeadsetService: Received start request. Starting profile...
,07-12 17:45:47.458  3166  3166 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-12 17:45:47.458  3166  3166 D HeadsetStateMachine: make
07-12 17:45:47.472  3166  3178 I BluetoothAdapterState: Entering PendingCommandState
07-12 17:45:47.482  3166  3166 D HeadsetStateMachine: max_hf_connections = 1
,07-12 17:45:47.482  3166  3166 I bt_bluedroid: get_profile_interface handsfree
07-12 17:45:47.483  3166  3182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
,07-12 17:45:47.484  3166  3182 E bt_btif : btif_hf_upstreams_evt: Invalid index 111
07-12 17:45:47.490  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
07-12 17:45:47.491  3166  3166 D A2dpService: Received start request. Starting profile...
,07-12 17:45:47.492  3166  3166 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 17:45:47.492  3166  3166 I bt_bluedroid: get_profile_interface avrcp
,07-12 17:45:47.501  3166  3166 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 17:45:47.501  3166  3166 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 17:45:47.502  3166  3166 D A2dpStateMachine: make
,07-12 17:45:47.505  3166  3166 I bt_bluedroid: get_profile_interface a2dp
,07-12 17:45:47.506  3166  3182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-12 17:45:47.511  3166  3199 D A2dpStateMachine: Enter Disconnected: -2
,07-12 17:45:47.511  3166  3166 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 17:45:47.513  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:47.514  3166  3166 D HidService: Received start request. Starting profile...
,07-12 17:45:47.515  3166  3166 I bt_bluedroid: get_profile_interface hidhost
07-12 17:45:47.515  3166  3182 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cea099
07-12 17:45:47.515  3166  3182 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-12 17:45:47.516  3166  3166 D HidService: setHidService(): set to: null
07-12 17:45:47.516  3166  3166 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 17:45:47.518  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:47.519  3166  3166 D HealthService: Received start request. Starting profile...
,07-12 17:45:47.522  3166  3166 I bt_bluedroid: get_profile_interface health
,07-12 17:45:47.525  3166  3166 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 17:45:47.528  3166  3166 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:47.528  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:47.529  3166  3166 D PanService: Received start request. Starting profile...
07-12 17:45:47.529  3166  3166 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 17:45:47.529  3166  3166 I bt_bluedroid: get_profile_interface pan
07-12 17:45:47.530  3166  3182 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 17:45:47.536  3166  3196 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 17:45:47.537  3166  3166 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:47.537  3166  3166 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:47.537  3166  3166 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:47.537  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isTurningOn()=true
,07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isBleTurningOn()=false
,07-12 17:45:47.542  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 17:45:47.543  3166  3166 V BluetoothAdapterState: isTurningOff()=false
,07-12 17:45:47.543  3166  3166 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:47.543  3166  3166 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:47.543  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:47.543  3166  3166 V BluetoothAdapterState: isTurningOff()=false
07-12 17:45:47.544  3166  3166 V BluetoothAdapterState: isTurningOn()=true
07-12 17:45:47.544  3166  3166 V BluetoothAdapterState: isBleTurningOn()=false
07-12 17:45:47.544  3166  3166 V BluetoothAdapterState: isBleTurningOff()=false
07-12 17:45:47.544  3166  3178 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 17:45:47.544  3166  3178 D BluetoothAdapterProperties: ScanMode =  20
07-12 17:45:47.544  3166  3178 D BluetoothAdapterProperties: State =  11
07-12 17:45:47.548  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:47.549  3166  3182 D BluetoothAdapterProperties: Scan Mode:21
07-12 17:45:47.549  3166  3182 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 17:45:47.549  3166  3178 D BluetoothAdapterProperties: Setting state to 12
07-12 17:45:47.550  3166  3178 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 17:45:47.550   706   891 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:47.553  3166  3178 I BluetoothAdapterState: Entering OnState
07-12 17:45:47.554  2906  2919 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:47.558  2906  2917 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:47.559   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.560   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.560   706   734 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:47.567   706   730 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:47.569   706   706 D BluetoothA2dp: Proxy object connected
07-12 17:45:47.569   706  2922 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.572  2906  2917 D BluetoothPan: onBluetoothStateChange on: true
07-12 17:45:47.573   706   706 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:47.573   706   706 D PanProfile: Bluetooth service connected
07-12 17:45:47.573  2906  2906 D BluetoothA2dp: Proxy object connected
07-12 17:45:47.574   706  2920 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-12 17:45:47.575  2906  2906 D BluetoothInputDevice: Proxy object connected
07-12 17:45:47.576  2906  2906 D HidProfile: Bluetooth service connected
07-12 17:45:47.576   706   706 D BluetoothInputDevice: Proxy object connected
07-12 17:45:47.576   706   706 D HidProfile: Bluetooth service connected
07-12 17:45:47.577  1028  1140 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.577   706  2922 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:47.578   706  2922 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-12 17:45:47.578  2906  2917 D BluetoothMap: onBluetoothStateChange: up=true
07-12 17:45:47.578  2906  2917 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-12 17:45:47.579  2906  2919 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.580   542   585 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 17:45:47.580   542   585 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 17:45:47.581  2906  2906 D BluetoothPan: BluetoothPAN Proxy object connected
07-12 17:45:47.581  2906  2906 D PanProfile: Bluetooth service connected
07-12 17:45:47.582   542   542 D BluetoothA2dp: Proxy object connected
07-12 17:45:47.582  2906  3191 D BluetoothPbap: onBluetoothStateChange: up=true
07-12 17:45:47.586   542   542 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 17:45:47.604  2906  2906 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 17:45:47.616  1083  1083 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 17:45:47.627  2906  2906 D DockEventReceiver: finishStartingService: stopping service
,07-12 17:45:47.634   706   706 D BluetoothPbap: Proxy object connected
07-12 17:45:47.635   706   706 D PbapServerProfile: Bluetooth service connected
07-12 17:45:47.638  2906  2906 D BluetoothPbap: Proxy object connected
07-12 17:45:47.638  2906  2906 D PbapServerProfile: Bluetooth service connected
07-12 17:45:47.659  3166  3208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:47.668   542   542 D BluetoothHeadset: Proxy object connected
,07-12 17:45:47.669   706   891 D BluetoothHeadset: Proxy object connected
,07-12 17:45:47.669   706   706 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:47.670   542   542 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.670  2906  3191 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.671  2906  2906 D HeadsetProfile: Bluetooth service connected
07-12 17:45:47.671   706   734 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.672  1028  1130 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.672   542   542 D BluetoothHeadset: Proxy object connected
,07-12 17:45:47.677   706   706 D HeadsetProfile: Bluetooth service connected
07-12 17:45:47.677  1028  1054 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.680  2906  2917 D BluetoothHeadset: Proxy object connected
07-12 17:45:47.680   542   585 D BluetoothHeadset: Proxy object connected
,07-12 17:45:47.685  2906  2906 D HeadsetProfile: Bluetooth service connected
,07-12 17:45:47.692  3166  3212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 17:45:47.695  3166  3212 I BtOppRfcommListener: Accept thread started.
,07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:47.911  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:47.915  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:47.917  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-12 17:45:47.917  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24e44eb added. We now have 8 listener(s)
07-12 17:45:47.917  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:47.921   542   957 D WifiService: setWifiEnabled: false pid=2819, uid=10000
,07-12 17:45:47.921   542   957 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:47.931  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:47.932   542  1341 D WifiService: setWifiEnabled: true pid=2819, uid=10000
07-12 17:45:47.932   542  1341 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 17:45:47.939   217   632 D SoftapController: Softap fwReload - Ok
07-12 17:45:47.942   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:47.943   217   632 D CommandListener: Trying to bring down wlan0
07-12 17:45:47.944   217   632 D CommandListener: Clearing all IP addresses on wlan0
,07-12 17:45:47.948   542   661 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-12 17:45:48.614   542   661 D wifi    : set interface wlan0 flags (UP)
,07-12 17:45:48.616   542   661 I WifiHAL : Initializing wifi
07-12 17:45:48.616   542   661 I WifiHAL : Creating socket
,07-12 17:45:48.620   542   661 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-12 17:45:48.620   542   661 D wifi    : Did set static halHandle = 0x555de71870
,07-12 17:45:48.620   542   661 D wifi    : halHandle = 0x555de71870, mVM = 0x555d788c30, mCls = 0x1016c2
07-12 17:45:48.620   542   661 D wifi    : array field set
,07-12 17:45:48.620   542   661 I WifiNative-HAL: interface[0] = wlan0
,07-12 17:45:48.623   542  3216 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=366647646320
,07-12 17:45:48.623   542  3216 D wifi    : waitForHalEvents called, vm = 0x555d788c30, obj = 0x1016c2, env = 0x555df6ebb0
07-12 17:45:48.628   542   661 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-12 17:45:48.629   542   661 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:48.631  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:48.636  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:48.719  3217  3217 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 17:45:48.789  3217  3217 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:48.838  3217  3217 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 17:45:48.838  3217  3217 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-12 17:45:49.653   542   661 D WifiConfigStore: Loading config and enabling all networks 
,07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:49.654  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:49.656  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:49.669   542   661 D WifiConfigStore: loaded 0 passpoint configs
,07-12 17:45:49.671   542   661 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-12 17:45:49.672   542   661 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-12 17:45:49.673   542   661 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 17:45:49.673   542   661 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 17:45:49.673   542   661 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 17:45:49.673   542   661 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-12 17:45:49.680  2989  2989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-12 17:45:49.680   542   661 D WifiNative-HAL: Setting external_sim to 1
07-12 17:45:49.681   542   661 D wifi    : setting dfs flag to true, 0x555daf17a0
,07-12 17:45:49.681   542   661 D WifiStateMachine: Setting OUI to DA-A1-19
,07-12 17:45:49.682   542   661 D wifi    : setting scan oui 0x555daf17a0
07-12 17:45:49.682   542   661 D WifiHAL : Sending mac address OUI
,07-12 17:45:49.703   542   661 E native  : do suspend true
,07-12 17:45:49.712   217   632 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-12 17:45:49.712   542   542 D RttService: SCAN_AVAILABLE : 3
07-12 17:45:49.713   542   676 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-12 17:45:49.714   217   632 D CommandListener: Setting iface cfg
07-12 17:45:49.714   542   661 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-12 17:45:49.714   542   661 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-12 17:45:49.715   542   660 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '91 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 91 Failed to set address (No such device)'
07-12 17:45:49.715   542   660 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 17:45:49.726   542   660 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 17:45:49.727   542   660 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-12 17:45:49.757   542   577 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=196146 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=25 mControllerEnergyUsed=95 }
,07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:49.950  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:49.954  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:49.960  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-12 17:45:49.961  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-12 17:45:49.968  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a16950 Bundle[{}]
,07-12 17:45:49.969  2819  2870 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:45:49.970  2819  2870 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:45:49.971  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-12 17:45:49.974  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-12 17:45:49.975  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:45:49.976  2819  2870 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-12 17:45:49.986  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-12 17:45:49.986  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:49.987  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-12 17:45:49.987  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-12 17:45:49.987  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-12 17:45:49.987  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:49.992  2819  2870 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 89)
07-12 17:45:49.993  2819  2870 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 89)
,07-12 17:45:49.993  2819  2870 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 89)
07-12 17:45:49.993  2819  2870 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 89)
,07-12 17:45:49.996  2819  2870 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 95)
,07-12 17:45:49.996  2819  2870 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 95)
07-12 17:45:49.997  2819  2870 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 95)
07-12 17:45:49.997  2819  2870 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 96)
,07-12 17:45:49.999  2819  2870 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 98)
,07-12 17:45:50.001  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-12 17:45:50.001  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d152248 added. We now have 2 listener(s)
,07-12 17:45:50.004  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-12 17:45:50.004  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.004  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.004  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.004  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21b8e1 added. We now have 9 listener(s)
,07-12 17:45:50.004  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.007  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:50.010  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.013  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.014  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:50.014  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:50.015  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.015  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94a44c7 added. We now have 3 listener(s)
,07-12 17:45:50.015  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.017  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.017  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.018  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.018  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.018  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.018  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7e1af4 added. We now have 10 listener(s)
07-12 17:45:50.018  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.020  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.020  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.021  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.021  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.021  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.021  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.021  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:50.021  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d152248 removed from the list
,07-12 17:45:50.022  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.022  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21b8e1 removed from the list
07-12 17:45:50.022  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.022  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.022  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.022  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.023  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.023  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e21b8e1 not in the list
07-12 17:45:50.023  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.023  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.023  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.023  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7e1af4 removed from the list
07-12 17:45:50.023  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.023  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.023  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.023  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.023  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94a44c7 removed from the list
07-12 17:45:50.024  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-12 17:45:50.024  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a0021d added. We now have 2 listener(s)
07-12 17:45:50.026  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.026  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:50.026  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.026  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.026  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@833ec92 added. We now have 9 listener(s)
07-12 17:45:50.026  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.029  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 17:45:50.032  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.035  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.037  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.037  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:50.038  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.039  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.039  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dbf260 added. We now have 3 listener(s)
,07-12 17:45:50.039  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.041  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.041  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:50.041  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.041  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.042  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bfa319 added. We now have 10 listener(s)
07-12 17:45:50.042  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.042  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:50.042  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.042  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.042  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:50.048  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:50.049  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:50.057  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:50.061  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:50.061  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.061  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-12 17:45:50.061  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-12 17:45:50.062  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-12 17:45:50.063  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.074  3166  3197 D BtGatt.GattService: registerClient() - UUID=3905cb37-07b2-4b9b-b143-2558a069c383
,07-12 17:45:50.075  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=3905cb37-07b2-4b9b-b143-2558a069c383, clientIf=5
,07-12 17:45:50.075  2819  2831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 17:45:50.076  3166  3204 D BtGatt.GattService: start scan with filters
,07-12 17:45:50.083  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:50.083  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.083  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:50.083  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-12 17:45:50.084  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:50.084  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.084  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:50.084  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:50.085  3166  3185 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32502e4
,07-12 17:45:50.090  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.090  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-12 17:45:50.090  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-12 17:45:50.092  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:50.093  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.094  2819  2870 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-12 17:45:50.094  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.094  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.094  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.094  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:50.095  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.095  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.095  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-12 17:45:50.098  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-12 17:45:50.098  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-12 17:45:50.099  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.100  3166  3177 D BtGatt.GattService: stopScan() - queue size =1
,07-12 17:45:50.100  3166  3197 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:50.101  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.101  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.101  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.101  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.101  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-12 17:45:50.101  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.101  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.102  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.102  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:50.102  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:50.102  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.103  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.103  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.103  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.106  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.106  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.107  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:50.107  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.108  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.108  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.112  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:50.113  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.113  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.113  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.115  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.115  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-12 17:45:50.115  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.118  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.118  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.118  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.119  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.119  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.119  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.119  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.119  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a0021d removed from the list
07-12 17:45:50.119  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.119  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@833ec92 removed from the list
07-12 17:45:50.119  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.119  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.120  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.120  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:50.120  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.120  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-12 17:45:50.120  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.120  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@833ec92 not in the list
07-12 17:45:50.121  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:50.121  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-12 17:45:50.122  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.122  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.122  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.122  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.123  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.123  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bfa319 removed from the list
07-12 17:45:50.123  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.123  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.123  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.123  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-12 17:45:50.123  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5dbf260 removed from the list
07-12 17:45:50.124  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.124  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379ad78 added. We now have 2 listener(s)
07-12 17:45:50.125  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.126  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 17:45:50.126  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.126  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.127  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:50.127  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@799c51 added. We now have 9 listener(s)
07-12 17:45:50.127  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.127  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:45:50.130  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:50.135  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.138  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:50.138  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.151  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.151  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:50.151  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.152  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.153  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.154  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.155  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.155  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07edb7 added. We now have 3 listener(s)
07-12 17:45:50.156  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.156  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.157  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.157  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.157  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.157  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f582924 added. We now have 10 listener(s)
,07-12 17:45:50.157  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.157  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.158  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.158  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.158  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.158  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-12 17:45:50.164  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-12 17:45:50.164  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.165  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.165  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.168  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.168  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:50.175  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:50.175  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.175  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.176  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:50.176  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.176  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:50.176  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:50.176  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:50.177  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.179  3166  3177 D BtGatt.GattService: registerClient() - UUID=1a0e4b20-25cd-44d3-aee9-80dc988cf4e0
,07-12 17:45:50.179  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=1a0e4b20-25cd-44d3-aee9-80dc988cf4e0, clientIf=5
,07-12 17:45:50.180  2819  2830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 17:45:50.180  3166  3197 D BtGatt.GattService: start scan with filters
07-12 17:45:50.183  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:50.183  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.183  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:50.183  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:50.183  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:50.183  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.183  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:50.183  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.185  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.185  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.185  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:50.185  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.185  2819  2870 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:50.186  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.186  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.186  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.186  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.186  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.186  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.186  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.187  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@379ad78 removed from the list
07-12 17:45:50.187  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.187  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@799c51 removed from the list
07-12 17:45:50.187  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.187  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.187  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.187  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:50.187  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.187  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.188  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.188  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@799c51 not in the list
07-12 17:45:50.188  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:50.188  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.188  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:50.188  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.188  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:50.189  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.189  3166  3204 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:50.190  3166  3177 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-12 17:45:50.190  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.191  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.191  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.191  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.191  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:50.191  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.191  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.191  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.191  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-12 17:45:50.193  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:45:50.193  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-12 17:45:50.193  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.193  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.193  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.193  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-12 17:45:50.193  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.194  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.198  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.198  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.202  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.203  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.203  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.203  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.204  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.204  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:50.204  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.204  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.206  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.206  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.207  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.207  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.208  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.208  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.208  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.208  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.208  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f582924 removed from the list
,07-12 17:45:50.208  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.208  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.208  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.208  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.208  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b07edb7 removed from the list
07-12 17:45:50.209  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.209  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@130dcaf added. We now have 2 listener(s)
07-12 17:45:50.211  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.211  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.211  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.211  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.211  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36578bc added. We now have 9 listener(s)
07-12 17:45:50.211  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.214  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:50.216  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.221  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:50.223  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:50.223  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.226  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.226  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.228  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.229  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.227  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.234  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:50.234  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.234  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213b39a added. We now have 3 listener(s)
07-12 17:45:50.245  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.245  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.245  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.245  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.245  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-12 17:45:50.245  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63894cb added. We now have 10 listener(s)
07-12 17:45:50.246  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.246  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.246  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.246  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.246  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.246  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.246  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.248  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.248  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.253  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.253  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.253  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.254  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:50.254  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:50.254  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:50.255  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.256  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:50.256  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.256  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.258  3166  3204 D BtGatt.GattService: registerClient() - UUID=b7419089-b486-428a-9aea-183c341caaea
,07-12 17:45:50.258  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=b7419089-b486-428a-9aea-183c341caaea, clientIf=5
,07-12 17:45:50.259  2819  2830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 17:45:50.259  3166  3177 D BtGatt.GattService: start scan with filters
,07-12 17:45:50.262  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-12 17:45:50.262  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:50.262  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:50.262  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-12 17:45:50.262  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:50.263  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:50.263  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-12 17:45:50.264  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.265  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.266  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:50.266  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.266  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.268  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.269  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.269  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.269  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.270  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.270  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.270  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.270  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.270  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@130dcaf removed from the list
07-12 17:45:50.270  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.270  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36578bc removed from the list
,07-12 17:45:50.270  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.270  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.271  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.271  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.271  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.271  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.271  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.271  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36578bc not in the list
,07-12 17:45:50.271  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:50.271  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.272  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:50.272  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.272  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:50.272  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.273  3166  3176 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:50.273  3166  3197 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.274  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.274  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.274  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.275  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-12 17:45:50.275  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-12 17:45:50.275  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.275  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.275  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.275  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.279  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:50.279  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.280  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.283  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.283  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.287  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.288  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.288  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12, 17:45:50.288  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.290  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.290  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.290  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:50.290  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.291  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.291  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.291  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.292  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.292  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.292  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.292  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.292  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.292  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63894cb removed from the list
07-12 17:45:50.292  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.292  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.292  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.292  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.292  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@213b39a removed from the list
07-12 17:45:50.293  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.293  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faa2354 added. We now have 2 listener(s)
07-12 17:45:50.295  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.295  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.295  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.295  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.295  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92cd2fd added. We now have 9 listener(s)
07-12 17:45:50.295  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.298  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:50.300  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.305  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:50.307  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.307  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.308  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:50.308  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.309  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.310  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.310  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.310  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44d243 added. We now have 3 listener(s)
07-12 17:45:50.312  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.312  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.312  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.312  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.312  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43020c0 added. We now have 10 listener(s)
07-12 17:45:50.312  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.312  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.312  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.313  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.313  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.314  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.314  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.314  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.314  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faa2354 removed from the list
07-12 17:45:50.314  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.314  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92cd2fd removed from the list
07-12 17:45:50.314  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.314  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.315  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.315  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.316  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.316  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.316  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.316  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92cd2fd not in the list
07-12 17:45:50.316  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.316  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.316  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.316  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.316  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.316  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43020c0 removed from the list
07-12 17:45:50.316  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.316  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.316  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.316  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.316  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44d243 removed from the list
07-12 17:45:50.317  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-12 17:45:50.317  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 added. We now have 2 listener(s)
07-12 17:45:50.318  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:50.318  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.319  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-12 17:45:50.319  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:45:50.319  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:45:50.319  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-12 17:45:50.319  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e added. We now have 9 listener(s)
07-12 17:45:50.319  2819  2870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 17:45:50.322  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:45:50.325  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.331  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-12 17:45:50.331  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.331  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.332  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:50.334  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.334  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.336  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.337  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.338  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:50.340  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:50.340  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:50.340  2819  2870 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-12 17:45:50.340  2819  2870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-12 17:45:50.340  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:50.342  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:50.343  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.343  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.341  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:50.343  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:50.343  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.344  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.344  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.344  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.344  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.344  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.345  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:45:50.345  2819  2870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 removed from the list
07-12 17:45:50.345  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.345  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e removed from the list
07-12 17:45:50.345  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.345  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.346  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.346  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.346  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.346  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.346  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.346  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.348  2819  2870 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-12 17:45:50.352  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.352  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.352  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.353  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.354  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.354  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.354  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.354  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.354  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.354  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.354  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.354  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.354  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.354  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.355  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.355  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.355  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.355  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.356  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.357  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.359  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.360  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:50.360  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:50.360  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:50.366  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:50.366  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:50.366  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:50.367  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-12 17:45:50.368  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:50.368  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.368  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.369  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.369  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.369  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.369  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.369  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.369  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.369  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.369  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.369  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.370  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.370  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.370  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.370  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.370  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.370  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.371  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.371  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.371  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.371  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.371  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.371  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.371  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.372  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.372  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.372  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.372  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.372  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.373  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.373  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.373  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.373  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.373  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.373  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.375  2819  2870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:50.377  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.384  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:50.385  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.386  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.386  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.386  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.386  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.386  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.389  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.389  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.390  2819  2870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.390  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.394  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.394  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.395  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.395  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:50.395  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:50.395  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:50.395  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.399  3166  3177 D BtGatt.GattService: registerClient() - UUID=9b4e6a18-3e98-4067-a718-fd6cf6c754d1
07-12 17:45:50.399  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=9b4e6a18-3e98-4067-a718-fd6cf6c754d1, clientIf=5
07-12 17:45:50.399  2819  2869 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:50.400  3166  3197 D BtGatt.GattService: start scan with filters
07-12 17:45:50.403  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:50.403  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.403  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:50.403  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:50.403  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:50.403  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.403  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:50.405  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.405  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-12 17:45:50.405  2819  2870 I io.jxcore.node.ConnectionHelper: start: OK
,07-12 17:45:50.406  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.406  2819  2819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.406  2819  2819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-12 17:45:50.406  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.411  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.411  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.411  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.411  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.411  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:50.411  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.411  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-12 17:45:50.412  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.412  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:50.413  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.414  3166  3176 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:50.414  3166  3204 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:50.415  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.415  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.415  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.415  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.415  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-12 17:45:50.416  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:50.416  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.417  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.417  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-12 17:45:50.418  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.418  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-12 17:45:50.418  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.419  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.419  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-12 17:45:50.419  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.419  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.419  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.420  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.423  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.427  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.427  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.428  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
,07-12 17:45:50.428  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.428  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.429  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.429  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-12 17:45:50.433  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-12 17:45:50.434  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-12 17:45:50.434  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-12 17:45:50.434  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.440  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.440  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-12 17:45:50.440  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.440  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.440  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.440  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.440  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.441  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-12 17:45:50.441  2819  2870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:50.443  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.447  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 17:45:50.449  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-12 17:45:50.449  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.461  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 17:45:50.461  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-12 17:45:50.461  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.461  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:45:50.462  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.465  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:45:50.465  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:50.465  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.468  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.469  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:50.469  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-12 17:45:50.469  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:50.469  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.472  3166  3197 D BtGatt.GattService: registerClient() - UUID=1f07b630-9fc1-4652-a70f-a64bc8eff9aa
07-12 17:45:50.474  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=1f07b630-9fc1-4652-a70f-a64bc8eff9aa, clientIf=5
,07-12 17:45:50.474  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:50.474  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.474  2819  2830 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-12 17:45:50.475  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.475  3166  3204 D BtGatt.GattService: start scan with filters
07-12 17:45:50.480  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:50.480  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-12 17:45:50.480  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:50.480  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:50.480  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.480  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-12 17:45:50.480  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:50.482  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.482  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:50.483  2819  2819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-12 17:45:50.483  2819  2819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:50.483  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.483  2819  2870 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:50.486  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.486  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-12 17:45:50.486  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.486  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.487  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.487  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.487  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.487  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-12 17:45:50.487  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.487  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:50.488  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.488  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:50.488  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.489  3166  3176 D BtGatt.GattService: stopScan() - queue size =0
07-12 17:45:50.490  3166  3177 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:50.490  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.490  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.490  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.491  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.491  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.493  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.493  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.493  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.493  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.496  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.496  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.498  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.498  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.500  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.500  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.501  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.501  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.501  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: ,false, start advertiser: false
07-12 17:45:50.504  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.505  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.505  2819  2819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.505  2819  2819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:50.505  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.505  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.505  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.505  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.506  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.506  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.506  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.506  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.506  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.506  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.506  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.506  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.507  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.507  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.508  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.508  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.508  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.508  2819  2870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-12 17:45:50.511  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.512  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:50.512  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.512  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 17:45:50.514  2819  2870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 17:45:50.516  2819  2870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 17:45:50.516  2819  2870 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 17:45:50.517  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:45:50.517  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-12 17:45:50.517  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.518  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.519  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-12 17:45:50.517  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.523  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.523  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-12 17:45:50.523  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.523  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-12 17:45:50.523  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.523  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-12 17:45:50.523  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:50.523  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.524  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.526  3166  3177 D BtGatt.GattService: registerClient() - UUID=29d91cb9-cfd3-442c-9aab-b6270154683a
07,-12 17:45:50.527  3166  3182 D BtGatt.GattService: onClientRegistered() - UUID=29d91cb9-cfd3-442c-9aab-b6270154683a, clientIf=5
07-12 17:45:50.527  2819  2831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-12 17:45:50.528  3166  3197 D BtGatt.GattService: start scan with filters
07-12 17:45:50.533  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-12 17:45:50.533  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-12 17:45:50.533  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-12 17:45:50.533  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-12 17:45:50.533  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.533  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-12 17:45:50.535  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.535  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-12 17:45:50.535  2819  2870 I io.jxcore.node.ConnectionHelper: start: OK
07-12 17:45:50.535  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.535  2819  2870 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-12 17:45:50.535  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.535  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.535  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.535  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-12 17:45:50.535  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.535  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:50.536  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.536  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-12 17:45:50.536  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-12 17:45:50.537  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.538  3166  3177 D BtGatt.GattService: stopScan() - queue size =1
07-12 17:45:50.538  3166  3176 D BtGatt.GattService: unregisterClient() - clientIf=5
07-12 17:45:50.539  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.540  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-12 17:45:50.540  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-12 17:45:50.540  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-12 17:45:50.540  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [,SCANNING] -> [NOT_STARTED]
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.541  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.541  2819  2819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.541  2819  2819 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-12 17:45:50.541  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-12 17:45:50.542  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.542  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:45:50.542  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.544  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.544  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.548  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:50.548  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.548  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.548  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.549  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.549  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.549  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.549  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-12 17:45:50.549  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.549  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.549  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.549  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.549  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.551  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.552  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.552  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-12 17:45:50.552  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.561  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:50.561  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.568  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.576  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:50.576  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.576  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-12 17:45:50.576  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.576  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.576  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.577  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.577  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.577  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.577  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.577  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.578  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.578  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.578  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.578  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.578  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.578  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.578  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.579  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.579  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.579  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.579  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.576  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.579  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.579  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.579  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.580  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.580  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.580  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.580  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.581  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.581  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.581  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.581  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.581  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.582  2819  2870 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-12 17:45:50.583  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.583  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.583  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.583  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.583  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.583  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.584  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.584  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.584  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.584  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.584  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.584  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.584  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.584  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:50.584  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.584  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.584  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.586  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.586  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.586  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.586  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.586  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.588  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-12 17:45:50.588  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.588  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.588  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.588  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.588  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.588  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.588  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.588  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.588  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.589  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.589  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.589  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.589  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.589  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.589  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.589  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.589  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.589  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-12 17:45:50.589  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.589  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.590  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.590  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.590  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.590  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.590  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.591  2819  2870 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-12 17:45:50.595  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.595  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.595  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.595  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.595  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.596  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.596  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.596  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.596  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.596  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.596  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.597  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.597  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.597  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.597  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.597  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.597  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.598  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.598  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.598  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.598  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.598  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.599  2819  2870 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.599  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.599  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.599  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.599  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.599  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.599  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.600  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.600  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.600  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.600  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.600  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.600  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.600  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.600  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:50.600  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.600  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.600  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.601  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.601  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.601  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.601  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.601  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.602  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.602  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.603  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:50.604  3166  3185 D BtGatt.ScanManager: handling starting scan
07-12 17:45:50.604  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:50.605  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:50.606  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:50.606  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-12 17:45:50.607  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-12 17:45:50.607  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.607  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.607  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.608  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.608  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.608  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.608  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.608  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.609  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.609  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.609  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.609  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.609  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.609  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.609  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.609  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.609  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.610  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.610  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.610  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.610  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.610  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.611  2819  2870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:50.611  2819  2870 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-12 17:45:50.611  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:50.613  2819  2870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:50.613  2819  2870 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-12 17:45:50.613  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-12 17:45:50.616  3166  3182 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-12 17:45:50.614  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-12 17:45:50.616  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.616  3166  3185 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-12 17:45:50.616  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-12 17:45:50.618  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-12 17:45:50.619  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-12 17:45:50.619  2819  2870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-12 17:45:50.619  2819  2870 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-12 17:45:50.619  2819  2870 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-12 17:45:50.619  2819  2870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-12 17:45:50.620  2819  2870 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-12 17:45:50.621  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.621  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.621  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.621  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.621  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.622  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.622  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.622  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.622  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.622  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.622  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.622  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.622  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.622  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.622  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.623  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.623  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.624  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.624  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.625  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.625  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.625  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.625  2819  2870 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-12 17:45:50.626  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.626  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.626  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.627  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-12 17:45:50.626  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.627  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.627  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.627  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.627  3166  3185 D BtGatt.ScanManager: Starting BLE batch scan
07-12 17:45:50.627  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.627  3166  3185 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-12 17:45:50.627  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.628  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.628  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.628  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.628  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.628  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.628  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:50.628  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.628  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.628  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.635  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.635  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.635  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.635  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.635  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.637  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.637  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.637  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.638  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.638  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.638  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.638  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.638  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.638  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.639  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.639  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.639  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.639  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.639  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.639  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.639  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.639  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.640  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.640  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.641  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.641  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.641  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.641  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.641  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.641  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.642  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.642  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.642  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.642  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.642  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.643  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.643  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.643  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.643  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.643  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.643  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.643  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.643  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.643  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.644  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.644  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.649  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.649  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.650  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.651  3166  3182 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-12 17:45:50.651  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-12 17:45:50.650  2819  2870 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-12 17:45:50.661  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-12 17:45:50.661  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.663  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-12 17:45:50.663  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.663  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.667  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.668  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.668  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.668  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.668  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.668  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.668  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.668  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.668  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.668  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.668  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.668  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.668  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.668  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.669  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.669  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.669  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.669  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.669  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.670  2819  2870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-12 17:45:50.670  2819  2870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,07-12 17:45:50.670  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-12 17:45:50.670  2819  2870 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-12 17:45:50.671  2819  2870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:50.671  2819  2870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,07-12 17:45:50.671  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:50.671  2819  2870 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-12 17:45:50.671  2819  2870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-12 17:45:50.671  2819  2870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,07-12 17:45:50.671  2819  2870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-12 17:45:50.671  2819  2870 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-12 17:45:50.671  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.671  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.671  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.672  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.672  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.672  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.672  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.672  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.672  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.674  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.674  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.674  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.674  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.674  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.674  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.674  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.674  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.675  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.675  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.675  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.675  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.675  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.676  3166  3182 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-12 17:45:50.676  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.676  3166  3185 D BtGatt.ScanManager: stopping BLe Batch
07-12 17:45:50.676  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:45:50.676  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.676  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.676  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.677  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.677  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.677  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.677  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.678  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.678  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.678  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.678  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.678  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.679  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.679  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.679  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.679  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.679  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.680  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.680  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.680  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.680  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.680  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.681  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.681  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.681  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.681  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.681  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.681  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.681  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.681  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.681  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.682  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.682  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.683  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.683  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.683  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.685  2819  2870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-12 17:45:50.687  3166  3182 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-12 17:45:50.687  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.687  3166  3185 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-12 17:45:50.688  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.689  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-12 17:45:50.690  2819  2870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-12 17:45:50.690  2819  2870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-12 17:45:50.690  2819  2819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-12 17:45:50.690  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-12 17:45:50.691  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.691  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:50.691  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-12 17:45:50.691  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-12 17:45:50.691  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
07-12 17:45:50.691  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.691  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.691  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.691  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-12 17:45:50.691  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-12 17:45:50.691  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-12 17:45:50.693  2819  2870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-12 17:45:50.694  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.694  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.694  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.695  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.695  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-12 17:45:50.695  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.695  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.695  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.695  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.695  2819  2870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-12 17:45:50.695  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.695  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:45:50.695  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-12 17:45:50.699  3166  3182 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-12 17:45:50.699  3166  3182 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-12 17:45:50.700  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-12 17:45:50.700  2819  2819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-12 17:45:50.704  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-12 17:45:50.705  2819  2819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-12 17:45:50.705  2819  2819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-12 17:45:50.705  2819  2819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-12 17:45:50.705  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.705  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.706  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.706  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-12 17:45:50.706  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.706  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-12 17:45:50.706  2819  3222 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-12 17:45:50.707  2819  3222 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-12 17:45:50.711  2819  2819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-12 17:45:50.711  2819  2819 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-12 17:45:50.711  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.711  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.712  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.712  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-12 17:45:50.712  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.712  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.712  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.712  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.712  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.712  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.712  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.712  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.712  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.712  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.713  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.713  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.713  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.714  2819  2819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-12 17:45:50.714  2819  2819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-12 17:45:50.714  2819  2819 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-12 17:45:50.714  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.714  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.714  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.714  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.715  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.715  2819  2870 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-12 17:45:50.716  2819  2870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-12 17:45:50.716  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-12 17:45:50.718  2819  2870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-12 17:45:50.721  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.721  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.721  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.721  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.721  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.722  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.723  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.723  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.723  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.723  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
,07-12 17:45:50.723  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.723  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.723  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.724  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:50.724  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.725  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.725  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.727  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.727  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.727  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.727  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.727  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.732  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.732  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.732  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.732  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.732  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.732  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.733  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.733  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.733  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.733  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.733  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.733  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.733  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.733  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.733  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.733  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.733  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.734  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.734  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.734  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.734  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.734  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.735  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.735  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-12 17:45:50.735  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-12 17:45:50.735  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.735  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.735  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-12 17:45:50.735  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.735  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.735  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.735  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.735  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.735  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.735  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.735  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.736  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.736  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.736  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.736  2819  2870 D BluetoothAdapter: STATE_ON
,07-12 17:45:50.736  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.736  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.736  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.736  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.737  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.737  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.737  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.737  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.737  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.737  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.738  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
07-12 17:45:50.739  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.739  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.739  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.739  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.739  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.739  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.739  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.739  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.739  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.739  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-12 17:45:50.741  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.742  2819  2870 D BluetoothLeScanner: could not find callback wrapper
,07-12 17:45:50.742  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.742  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.742  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
,07-12 17:45:50.742  2819  2870 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
07-12 17:45:50.742  2819  2870 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-12 17:45:50.743  2819  2819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-12 17:45:50.744  2819  2870 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
,07-12 17:45:50.744  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.744  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.744  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.745  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.745  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.745  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.745  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.745  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.745  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.745  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.745  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.745  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.745  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.745  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-12 17:45:50.745  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.745  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.745  2819  2870 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-12 17:45:50.745  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.746  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.746  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.746  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-12 17:45:50.746  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.746  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.747  2819  2870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-12 17:45:50.747  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:45:50.747  2819  2870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-12 17:45:50.747  2819  2870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:45:50.747  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.747  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.747  2819  2870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f8a1f9 not in the list
,07-12 17:45:50.747  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:45:50.747  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.747  2819  2870 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:45:50.747  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-12 17:45:50.747  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.747  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.748  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-12 17:45:50.748  2819  2870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:45:50.748  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-12 17:45:50.748  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-12 17:45:50.749  2819  2870 D BluetoothAdapter: STATE_ON
07-12 17:45:50.750  2819  2870 D BluetoothLeScanner: could not find callback wrapper
07-12 17:45:50.750  2819  2870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-12 17:45:50.750  2819  2870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-12 17:45:50.750  2819  2870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cd053e not in the list
07-12 17:45:50.751  2819  2870 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-12 17:45:50.751  2819  2870 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-12 17:45:50.751  2819  2870 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,07-12 17:45:50.751  2819  2870 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-12 17:45:50.751  2819  2870 E com.test.thalitest.ThaliTestRunner: Total duration: 29958 ms
07-12 17:45:50.753  2819  2870 I jxcore-log: PromiseSuccess
07-12 17:45:50.753  2819  2870 I jxcore-log: 
07-12 17:45:50.757  2819  2870 I jxcore-log: My device name is: htc-Nexus 9
07-12 17:45:50.757  2819  2870 I jxcore-log: 
,07-12 17:45:52.156  3217  3217 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 17:45:52.175   542   661 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 17:45:52.180   542   661 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,07-12 17:45:52.181   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:52.198   542   661 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-12 17:45:52.235   542   661 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 17:45:52.573  3217  3217 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-12 17:45:52.594  3217  3217 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-12 17:45:52.595  3217  3217 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-12 17:45:52.597   542   661 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 17:45:52.608   542   661 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:52.608   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 17:45:52.608   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 17:45:52.619   542   661 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 17:45:52.634   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:52.639   542   661 D WifiStateMachine: Start Dhcp Watchdog 3
,07-12 17:45:52.648   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-12 17:45:52.673   542  3228 D DhcpClient: Receive thread started
,07-12 17:45:52.758   542   661 E native  : do suspend false
,07-12 17:45:52.772   542  3227 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 17:45:52.781   542  3228 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172777, domain null
,07-12 17:45:52.781   542  3227 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172777 seconds
,07-12 17:45:52.782   542  3227 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-12 17:45:52.790   542  3228 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 17:45:52.790   542  3227 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-12 17:45:52.792   217   632 D CommandListener: Setting iface cfg
,07-12 17:45:52.796   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
,07-12 17:45:52.803   542  3227 D DhcpClient: Scheduling renewal in 86399s
,07-12 17:45:52.804   542   661 E native  : do suspend true
,07-12 17:45:52.820   542   661 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 17:45:52.821   542   661 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 17:45:52.821   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-12 17:45:52.822   542   663 D ConnectivityService: Adding iface wlan0 to network 102
07-12 17:45:52.826   542   661 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 17:45:52.886   542   663 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 17:45:52.886   542   663 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-12 17:45:52.894   542   663 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-12 17:45:52.899   542   663 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-12 17:45:52.901   542   663 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-12 17:45:52.910   542   663 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-12 17:45:52.916   542   663 D ConnectivityService: scheduleUnvalidatedPrompt 102
07-12 17:45:52.917   542   663 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-12 17:45:52.918   542   661 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-12 17:45:52.918   542   661 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-12 17:45:52.918   542   663 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,07-12 17:45:52.918   542   663 D ConnectivityService:    accepting network in place of null
,07-12 17:45:52.919   542   663 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 17:45:52.933   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=199322, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 17:45:52.994   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:53.003   542  3225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:809::200e
,07-12 17:45:53.058   217   632 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 17:45:53.062   542   663 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-12 17:45:53.063   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 17:45:53.064   542   663 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
07-12 17:45:53.068   542   585 D Tethering: MasterInitialState.processMessage what=3
07-12 17:45:53.071   542  3225 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 15:45:53 GMT], X-Android-Received-Millis=[1468338353070], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468338353037]}
,07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:45:53.076  2819  2819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:45:53.078  2819  2819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-12 17:45:53.080   542   663 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-12 17:45:53.080   542   663 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
07-12 17:45:53.081   542   663 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-12 17:45:53.085   542   663 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 17:45:53.174  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:53.178  1213  1213 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-12 17:45:53.182  1213  2288 I iu.UploadsManager: num queued entries: 0
07-12 17:45:53.182  1213  2288 I iu.UploadsManager: num updated entries: 0
07-12 17:45:53.183  1213  2288 I iu.SyncManager: NEXT; no task
,07-12 17:45:53.188  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:45:53.206  2621  3238 V GoogleAuthProtoRequest: [253] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:45:53.208  1075  1075 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-12 17:45:53.224  1213  1213 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 17:45:53.225  1213  1213 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-12 17:45:53.232  1213  3239 I MDM     : [206] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
07-12 17:45:53.232  1213  3239 W BaseAppContext: Using Auth Proxy for data requests.
07-12 17:45:53.234  1213  3239 V GoogleAuthProtoRequest: [206] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:45:53.268  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-12 17:45:53.268  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-12 17:45:53.268  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:45:53.268  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:53.289  1213  3239 E MDM     : [206] SitrepService.a: Error sending sitrep.
07-12 17:45:53.388  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 17:45:53.388  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 17:45:53.388  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:45:53.388  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: [253] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: [253] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 17:45:53.418  2621  3238 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 17:45:53.550   542   552 I art     : Background partial concurrent mark sweep GC freed 41270(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/26MB, paused 2.009ms total 312.277ms
,07-12 17:45:53.560  2989  3243 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-12 17:45:53.582  1083  3247 I GCM     : Ack for not saved message 139
,07-12 17:46:00.926   542   663 D ConnectivityService: handlePromptUnvalidated 102
,07-12 17:46:04.816  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 17:46:04.816  2819  2870 I jxcore-log: 
,07-12 17:46:05.500  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 17:46:05.500  2819  2870 I jxcore-log: 
,07-12 17:46:05.529  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 17:46:05.529  2819  2870 I jxcore-log: 
,07-12 17:46:05.535  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 17:46:05.535  2819  2870 I jxcore-log: 
,07-12 17:46:05.554  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 17:46:05.554  2819  2870 I jxcore-log: 
,07-12 17:46:05.559  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 17:46:05.559  2819  2870 I jxcore-log: 
,07-12 17:46:07.467   991  1106 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-12 17:46:07.467   991  1106 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 17:46:07.488  1083  1083 I ConfigService: onCreate
,07-12 17:46:12.026  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 17:46:12.026  2819  2870 I jxcore-log: 
,07-12 17:46:12.053  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 17:46:12.053  2819  2870 I jxcore-log: 
,07-12 17:46:12.075  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 17:46:12.075  2819  2870 I jxcore-log: 
,07-12 17:46:12.248  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 17:46:12.248  2819  2870 I jxcore-log: 
,07-12 17:46:12.556  1083  1083 I ConfigService: onDestroy
,07-12 17:46:13.175  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 17:46:13.175  2819  2870 I jxcore-log: 
,07-12 17:46:13.237  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 17:46:13.237  2819  2870 I jxcore-log: 
,07-12 17:46:13.249  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 17:46:13.249  2819  2870 I jxcore-log: 
,07-12 17:46:13.465  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 17:46:13.465  2819  2870 I jxcore-log: 
,07-12 17:46:13.492  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 17:46:13.492  2819  2870 I jxcore-log: 
,07-12 17:46:13.499  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 17:46:13.499  2819  2870 I jxcore-log: 
,07-12 17:46:13.508  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 17:46:13.508  2819  2870 I jxcore-log: 
,07-12 17:46:13.526  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 17:46:13.526  2819  2870 I jxcore-log: 
,07-12 17:46:13.549  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 17:46:13.549  2819  2870 I jxcore-log: 
,07-12 17:46:13.639  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 17:46:13.639  2819  2870 I jxcore-log: 
,07-12 17:46:13.647  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 17:46:13.647  2819  2870 I jxcore-log: 
,07-12 17:46:13.678  2819  2870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 17:46:13.678  2819  2870 I jxcore-log: 
,07-12 17:46:13.693  2819  2870 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 17:46:13.698  2819  2870 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 17:46:13.698  2819  2870 I jxcore-log: 
,07-12 17:46:13.787  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:46:13.787  2819  2870 I jxcore-log: 
,07-12 17:46:13.788  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:46:13.788  2819  2870 I jxcore-log: 
07-12 17:46:13.789  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.789  2819  2870 I jxcore-log: 
07-12 17:46:13.790  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.790  2819  2870 I jxcore-log: 
,07-12 17:46:13.794  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.794  2819  2870 I jxcore-log: 
,07-12 17:46:13.796  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.796  2819  2870 I jxcore-log: 
07-12 17:46:13.797  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.797  2819  2870 I jxcore-log: 
,07-12 17:46:13.798  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.798  2819  2870 I jxcore-log: 
07-12 17:46:13.800  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:46:13.800  2819  2870 I jxcore-log: 
,07-12 17:46:13.801  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:46:13.801  2819  2870 I jxcore-log: 
07-12 17:46:13.802  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.802  2819  2870 I jxcore-log: 
,07-12 17:46:13.803  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.803  2819  2870 I jxcore-log: 
07-12 17:46:13.804  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.804  2819  2870 I jxcore-log: 
,07-12 17:46:13.805  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.805  2819  2870 I jxcore-log: 
,07-12 17:46:13.807  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.807  2819  2870 I jxcore-log: 
,07-12 17:46:13.808  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.808  2819  2870 I jxcore-log: 
,07-12 17:46:13.809  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.809  2819  2870 I jxcore-log: 
07-12 17:46:13.810  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.810  2819  2870 I jxcore-log: 
07-12 17:46:13.810  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.810  2819  2870 I jxcore-log: 
,07-12 17:46:13.811  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-12 17:46:13.811  2819  2870 I jxcore-log: 
,07-12 17:46:13.813  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.813  2819  2870 I jxcore-log: 
,07-12 17:46:13.814  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.814  2819  2870 I jxcore-log: 
,07-12 17:46:13.815  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.815  2819  2870 I jxcore-log: 
,07-12 17:46:13.817  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.817  2819  2870 I jxcore-log: 
,07-12 17:46:13.818  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.818  2819  2870 I jxcore-log: 
,07-12 17:46:13.819  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.819  2819  2870 I jxcore-log: 
07-12 17:46:13.819  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-12 17:46:13.820  2819  2870 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-12 17:46:13.821  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.821  2819  2870 I jxcore-log: 
,07-12 17:46:13.823  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.823  2819  2870 I jxcore-log: 
,07-12 17:46:13.825  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.825  2819  2870 I jxcore-log: 
07-12 17:46:13.826  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.826  2819  2870 I jxcore-log: 
,07-12 17:46:13.828  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.828  2819  2870 I jxcore-log: 
,07-12 17:46:13.830  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.830  2819  2870 I jxcore-log: 
,07-12 17:46:13.832  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.832  2819  2870 I jxcore-log: 
,07-12 17:46:13.833  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.833  2819  2870 I jxcore-log: 
,07-12 17:46:13.833  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.833  2819  2870 I jxcore-log: 
07-12 17:46:13.835  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.835  2819  2870 I jxcore-log: 
,07-12 17:46:13.835  2819  2870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-12 17:46:13.835  2819  2870 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-12 17:46:13.836  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.836  2819  2870 I jxcore-log: 
,07-12 17:46:13.837  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.837  2819  2870 I jxcore-log: 
,07-12 17:46:13.838  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.838  2819  2870 I jxcore-log: 
,07-12 17:46:13.839  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.839  2819  2870 I jxcore-log: 
,07-12 17:46:13.840  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.840  2819  2870 I jxcore-log: 
07-12 17:46:13.841  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.841  2819  2870 I jxcore-log: 
07-12 17:46:13.842  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.842  2819  2870 I jxcore-log: 
07-12 17:46:13.842  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.842  2819  2870 I jxcore-log: 
07-12 17:46:13.843  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.843  2819  2870 I jxcore-log: 
07-12 17:46:13.843  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.843  2819  2870 I jxcore-log: 
,07-12 17:46:13.844  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.844  2819  2870 I jxcore-log: 
07-12 17:46:13.845  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.845  2819  2870 I jxcore-log: 
,07-12 17:46:13.846  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.846  2819  2870 I jxcore-log: 
,07-12 17:46:13.847  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.847  2819  2870 I jxcore-log: 
,07-12 17:46:13.849  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 17:46:13.849  2819  2870 I jxcore-log: 
,07-12 17:46:13.850  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.850  2819  2870 I jxcore-log: 
07-12 17:46:13.850  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-12 17:46:13.850  2819  2870 I jxcore-log: 
,07-12 17:46:13.851  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.851  2819  2870 I jxcore-log: 
,07-12 17:46:13.852  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.852  2819  2870 I jxcore-log: 
,07-12 17:46:13.853  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-12 17:46:13.853  2819  2870 I jxcore-log: 
,07-12 17:46:13.854  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-12 17:46:13.854  2819  2870 I jxcore-log: 
,07-12 17:46:13.856  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-12 17:46:13.856  2819  2870 I jxcore-log: 
07-12 17:46:13.857  2819  2870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 17:46:13.857  2819  2870 I jxcore-log: 
,07-12 17:46:22.965   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229354, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:46:48.228  2064  3250 V KeepSync: Connecting to GoogleApiClient
,07-12 17:46:48.229   542   752 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 17:46:48.271  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:48.273  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:46:48.294  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:46:48.294  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:46:48.294  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:46:48.294  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:48.308  1213  3251 V BaseAuthAsyncOperation: access token request failed
,07-12 17:46:48.309  2064  3250 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:46:48.361  1083  1179 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:46:48.361  1083  1179 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:46:48.362  1083  1179 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:46:48.362  1083  1179 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:46:48.377  2064  3250 E KeepSync: IOException
07-12 17:46:48.377  2064  3250 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:46:48.377  2064  3250 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:46:48.377  2064  3250 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:46:48.377  2064  3250 E KeepSync: 	... 10 more
,07-12 17:46:48.377  2064  3250 W KeepSync: Sync result 2
,07-12 17:46:48.382   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 254277, reason: 10072, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:47:20.117   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286507, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:47:20.143  2758  3252 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:47:20.161  2758  3253 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:47:20.174  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:20.176  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:20.200  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:47:20.200  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:47:20.200  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:20.200  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:20.225  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:20.226  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:20.246  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:47:20.247  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:47:20.247  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:20.247  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:20.262  2758  3253 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:47:20.265  2758  3252 E BooksSync: Soft error
07-12 17:47:20.265  2758  3252 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:47:20.265  2758  3252 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:47:20.265  2758  3252 E BooksSync: Sync error
07-12 17:47:20.265  2758  3252 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:47:20.265  2758  3252 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:47:20.266  2758  3252 I BooksSync: Finished books sync
,07-12 17:47:20.273   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286402, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:47:49.612   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=316000, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:47:50.505  2064  3254 V KeepSync: Connecting to GoogleApiClient
07-12 17:47:50.506   542  1240 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 17:47:50.565  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:50.568  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:47:50.587  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:47:50.588  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:47:50.588  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:50.588  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:50.601  1213  3255 V BaseAuthAsyncOperation: access token request failed
,07-12 17:47:50.602  2064  3254 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:47:50.694  1083  1292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 17:47:50.694  1083  1292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:47:50.694  1083  1292 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:47:50.694  1083  1292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:50.711  2064  3254 E KeepSync: IOException
07-12 17:47:50.711  2064  3254 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:47:50.711  2064  3254 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:47:50.711  2064  3254 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:47:50.711  2064  3254 E KeepSync: 	... 10 more
07-12 17:47:50.711  2064  3254 W KeepSync: Sync result 2
,07-12 17:47:50.718   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 286771, reason: 10072, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:47:53.483  2621  3256 V GoogleAuthProtoRequest: [254] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:47:53.518  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 17:47:53.519  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 17:47:53.519  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:47:53.519  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:47:53.544  2621  3256 W ExperimentUpdateService: [254] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: [254] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 17:47:53.545  2621  3256 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 17:48:09.425   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335814, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:48:19.245  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:19.261  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:19.267  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:19.325  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 17:48:19.326  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 17:48:19.326  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:19.326  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:19.376  1083  1349 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-12 17:48:19.376  1083  1349 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:48:19.382  2504  2533 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 17:48:19.382  2504  2533 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-12 17:48:19.382  2504  2533 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-12 17:48:19.382  2504  2533 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-12 17:48:19.382  2504  2533 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-12 17:48:19.382  2504  2533 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-12 17:48:19.382  2504  2533 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 17:48:20.819  2758  3260 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:48:20.838  2758  3261 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:48:20.865  1083  1292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:48:20.865  1083  1292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:48:20.866  1083  1292 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:48:20.866  1083  1292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:20.901  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:48:20.901  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:48:20.901  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:20.901  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:20.916  2758  3261 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:48:20.918  2758  3260 E BooksSync: Soft error
07-12 17:48:20.918  2758  3260 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:48:20.918  2758  3260 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:48:20.918  2758  3260 E BooksSync: Sync error
07-12 17:48:20.918  2758  3260 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:48:20.918  2758  3260 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:48:20.918  2758  3260 I BooksSync: Finished books sync
,07-12 17:48:20.923   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317291, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:48:49.185   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375574, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:48:54.987  2064  3262 V KeepSync: Connecting to GoogleApiClient
,07-12 17:48:54.989   542   957 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 17:48:55.041  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:55.043  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:48:55.071  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:48:55.071  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:48:55.071  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:55.072  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:55.087   542   552 I art     : Background partial concurrent mark sweep GC freed 35416(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 17MB/26MB, paused 2.029ms total 113.856ms
,07-12 17:48:55.089  1213  3263 V BaseAuthAsyncOperation: access token request failed
,07-12 17:48:55.093  2064  3262 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:48:55.149  1083  1292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:48:55.149  1083  1292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:48:55.149  1083  1292 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:48:55.150  1083  1292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:48:55.165  2064  3262 E KeepSync: IOException
07-12 17:48:55.165  2064  3262 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:48:55.165  2064  3262 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:48:55.165  2064  3262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:48:55.165  2064  3262 E KeepSync: 	... 10 more
07-12 17:48:55.165  2064  3262 W KeepSync: Sync result 2
,07-12 17:48:55.171   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 381105, reason: 10072, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:49:25.298  2758  3264 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:49:25.319  2758  3265 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:49:25.332  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:25.334  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:25.356  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:49:25.356  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:49:25.356  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:49:25.356  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:25.378  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:25.380  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:49:25.400  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:49:25.401  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:49:25.401  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:49:25.401  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:49:25.416  2758  3265 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:49:25.418  2758  3264 E BooksSync: Soft error
07-12 17:49:25.418  2758  3264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:49:25.418  2758  3264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:49:25.418  2758  3264 E BooksSync: Sync error
07-12 17:49:25.418  2758  3264 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:49:25.418  2758  3264 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:49:25.419  2758  3264 I BooksSync: Finished books sync
,07-12 17:49:25.423   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 408571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:49:35.586   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421975, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:50:05.079   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=451467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:50:58.079   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=504467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:51:03.270  2064  3267 V KeepSync: Connecting to GoogleApiClient
,07-12 17:51:03.270   542  1066 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 17:51:03.313  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:03.315  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:03.336  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:51:03.336  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:51:03.336  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:03.336  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:03.350  1213  3268 V BaseAuthAsyncOperation: access token request failed
,07-12 17:51:03.351  2064  3267 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:51:03.402  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:51:03.402  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:51:03.402  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:03.402  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:03.418  2064  3267 E KeepSync: IOException
07-12 17:51:03.418  2064  3267 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:51:03.418  2064  3267 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:51:03.418  2064  3267 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:51:03.418  2064  3267 E KeepSync: 	... 10 more
,07-12 17:51:03.418  2064  3267 W KeepSync: Sync result 2
,07-12 17:51:03.423   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 509556, reason: 10072, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:51:27.532   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=533920, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:51:33.544  2758  3269 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:51:33.589  2758  3270 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:51:33.614  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:33.619  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:33.662  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 17:51:33.662  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 17:51:33.662  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:33.662  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:33.689  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:33.691  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:33.709  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:51:33.709  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:51:33.709  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:51:33.709  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:33.723  2758  3270 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:51:33.724  2758  3269 E BooksSync: Soft error
07-12 17:51:33.724  2758  3269 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:51:33.724  2758  3269 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:51:33.724  2758  3269 E BooksSync: Sync error
07-12 17:51:33.724  2758  3269 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:51:33.724  2758  3269 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:51:33.724  2758  3269 I BooksSync: Finished books sync
,07-12 17:51:33.728   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 534329, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:51:53.630  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:53.638  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:51:53.666  2621  3271 V GoogleAuthProtoRequest: [255] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 17:51:53.729  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 17:51:53.729  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 17:51:53.730  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:51:53.730  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:51:53.769  2621  3271 W ExperimentUpdateService: [255] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: [255] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 17:51:53.772  2621  3271 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 17:51:55.905   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=562294, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:52:25.452   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=591841, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:53:24.733   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=651121, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 17:53:54.198   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=680587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 17:55:19.591  2064  3277 V KeepSync: Connecting to GoogleApiClient
,07-12 17:55:19.592   542  1066 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 17:55:19.626  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:19.628  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:19.649  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 17:55:19.649  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 17:55:19.649  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 17:55:19.649  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:19.662  1213  3278 V BaseAuthAsyncOperation: access token request failed
,07-12 17:55:19.663  2064  3277 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 17:55:19.713  1083  1349 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 17:55:19.713  1083  1349 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 17:55:19.713  1083  1349 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:55:19.714  1083  1349 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:19.731  2064  3277 E KeepSync: IOException
07-12 17:55:19.731  2064  3277 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 17:55:19.731  2064  3277 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 17:55:19.731  2064  3277 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 17:55:19.731  2064  3277 E KeepSync: 	... 10 more
,07-12 17:55:19.731  2064  3277 W KeepSync: Sync result 2
,07-12 17:55:19.738   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 765805, reason: 10072, SyncResult: stats [ numIoExceptions: 1]
,07-12 17:55:49.939  2758  3279 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 17:55:49.998  2758  3280 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 17:55:50.008  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:50.011  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:50.035  1083  1099 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:55:50.035  1083  1099 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:55:50.035  1083  1099 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:55:50.036  1083  1099 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:50.068  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:50.070  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 17:55:50.079   542   552 I art     : Background partial concurrent mark sweep GC freed 34871(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 17MB/26MB, paused 3.557ms total 120.212ms
,07-12 17:55:50.093  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 17:55:50.093  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 17:55:50.093  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 17:55:50.093  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 17:55:50.109  2758  3280 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 17:55:50.110  2758  3279 E BooksSync: Soft error
07-12 17:55:50.110  2758  3279 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:55:50.110  2758  3279 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 17:55:50.110  2758  3279 E BooksSync: Sync error
07-12 17:55:50.110  2758  3279 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 17:55:50.110  2758  3279 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 17:55:50.110  2758  3279 I BooksSync: Finished books sync
,07-12 17:55:50.115   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 785151, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 18:00:53.698  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:00:53.704  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:00:53.715  2621  3282 V GoogleAuthProtoRequest: [256] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 18:00:53.745  1083  1179 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 18:00:53.745  1083  1179 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 18:00:53.745  1083  1179 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 18:00:53.745  1083  1179 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:00:53.763  2621  3282 W ExperimentUpdateService: [256] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: [256] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 18:00:53.765  2621  3282 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 18:00:58.705   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1105094, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 18:01:15.799   542  3226 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1122187, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 18:02:53.517   542   573 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 18:03:51.907  2064  3283 V KeepSync: Connecting to GoogleApiClient
,07-12 18:03:51.908   542   956 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-12 18:03:51.941  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:03:51.943  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:03:51.963  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 18:03:51.964  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 18:03:51.964  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:03:51.964  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:03:51.977  1213  3284 V BaseAuthAsyncOperation: access token request failed
,07-12 18:03:51.979  2064  3283 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 18:03:52.027  1083  1292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 18:03:52.027  1083  1292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 18:03:52.028  1083  1292 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:03:52.028  1083  1292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:03:52.042  2064  3283 E KeepSync: IOException
07-12 18:03:52.042  2064  3283 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 18:03:52.042  2064  3283 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 18:03:52.042  2064  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 18:03:52.042  2064  3283 E KeepSync: 	... 10 more
,07-12 18:03:52.042  2064  3283 W KeepSync: Sync result 2
,07-12 18:03:52.047   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1278111, reason: 10072, SyncResult: stats [ numIoExceptions: 1],
,07-12 18:04:22.158  2758  3285 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 18:04:22.177  2758  3286 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-12 18:04:22.186  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:22.188  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:22.209  1083  2315 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 18:04:22.209  1083  2315 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 18:04:22.209  1083  2315 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 18:04:22.209  1083  2315 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:22.230  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:22.231  1083  1083 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 18:04:22.250  1083  1102 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 18:04:22.250  1083  1102 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 18:04:22.251  1083  1102 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 18:04:22.251  1083  1102 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 18:04:22.265  2758  3286 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 18:04:22.266  2758  3285 E BooksSync: Soft error
07-12 18:04:22.266  2758  3285 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 18:04:22.266  2758  3285 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 18:04:22.266  2758  3285 E BooksSync: Sync error
07-12 18:04:22.266  2758  3285 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 18:04:22.266  2758  3285 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 18:04:22.266  2758  3285 I BooksSync: Finished books sync
,07-12 18:04:22.271   542   573 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1286568, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),07-12 18:08:35.880  3288  3288 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 18:08:35.889  3288  3288 D AndroidRuntime: CheckJNI is OFF
07-12 18:08:35.975  3288  3288 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 18:08:36.046  3288  3288 I Radio-JNI: register_android_hardware_Radio DONE
07-12 18:08:36.104  3288  3288 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 18:08:36.119   542   574 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 18:08:36.119   542   574 I ActivityManager: Killing 2819:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-12 18:08:36.196   542  1066 I WindowState: WIN DEATH: Window{ab3e047 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 18:08:36.196   542   956 D GraphicsStats: Buffer count: 2
07-12 18:08:36.197   542   662 D WifiService: Client connection lost with reason: 4
07-12 18:08:36.331   542   574 E libprocessgroup: failed to kill 1 processes for processgroup 2819
07-12 18:08:36.336   542   599 W PackageSettings: Skipping PackageSetting{cb18192 com.example.hello/10095} due to missing metadata
07-12 18:08:36.379   542   574 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 18:08:36.380   542   574 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 18:08:36.396   542   599 I art     : Starting a blocking GC Explicit
07-12 18:08:36.396   542   574 E ActivityManager: Failure starting process com.test.thalitest
07-12 18:08:36.396   542   574 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 18:08:36.396   542   574 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 18:08:36.396   542   574 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 18:08:36.396   542   574 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 18:08:36.396   542   574 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 18:08:36.398   542   574 I ActivityManager:   Force finishing activity ActivityRecord{f988649 u0 com.test.thalitest/.MainActivity t67}
07-12 18:08:36.430   542  1341 W ActivityManager: Spurious death for ProcessRecord{8969b27 0:com.test.thalitest/u0a0}, curProc for 2819: null
07-12 18:08:36.556   542   599 I art     : Explicit concurrent mark sweep GC freed 31740(2045KB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 17MB/26MB, paused 1.724ms total 146.438ms
07-12 18:08:36.576   542   599 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 18:08:36.582  3288  3288 I art     : System.exit called, status: 0
07-12 18:08:36.582  3288  3288 I AndroidRuntime: VM exiting with result code 0.
07-12 18:08:36.602   542   599 I ActivityManager: Start proc 3298:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
07-12 18:08:36.607   542   599 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-12 18:08:36.669   542   574 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 18:08:36.676  1028  1028 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 18:08:36.681  1007  1266 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 18:08:36.689   542   653 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 18:08:36.698   542   574 I ActivityManager: Start proc 3312:android.process.acore/u0a3 for broadcast com.android.providers.contacts/.PackageIntentReceiver

```
