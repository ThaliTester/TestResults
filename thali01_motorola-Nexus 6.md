#### Test 82912030be204d2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-08 19:00:39.383   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-08 19:00:40.063  3749  3749 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 19:00:40.068  3749  3749 D AndroidRuntime: CheckJNI is OFF
09-08 19:00:40.111  3749  3749 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 19:00:40.161  3749  3749 I Radio-JNI: register_android_hardware_Radio DONE
09-08 19:00:40.184  3749  3749 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 19:00:40.188   874  2290 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 19:00:40.215  2039  2056 W SearchService: Abort, client detached.
09-08 19:00:40.218  2039  2357 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2cfc5ed
09-08 19:00:40.218  2039  2369 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 19:00:40.218  2039  2039 I HotwordDetector: Closing mic
09-08 19:00:40.237  3749  3749 D AndroidRuntime: Shutting down VM
09-08 19:00:40.276   874   885 I ActivityManager: Start proc 3758:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 19:00:40.286   377  2373 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 19:00:40.288   377  2373 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 19:00:40.297   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 19:00:40.301  2039  2368 I MicroRecognitionRnrImpl: Detection finished
09-08 19:00:40.301  2039  2363 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 19:00:40.403  3758  3758 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 19:00:40.438  3758  3758 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 19:00:40.446  3758  3758 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1842-1845)
09-08 19:00:40.446  3758  3758 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 19:00:40.467  3758  3758 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d3f0fc}
09-08 19:00:40.467  3758  3758 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 19:00:40.468  3758  3758 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 19:00:40.476  3758  3758 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 19:00:40.477  3758  3758 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 19:00:40.499  3758  3758 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 19:00:40.514  3758  3758 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 19:00:40.514  3758  3758 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 19:00:40.514  3758  3758 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 19:00:40.514  3758  3758 I Adreno  : Build Date                       : 10/20/15
09-08 19:00:40.514  3758  3758 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 19:00:40.514  3758  3758 I Adreno  : Local Branch                     : M14
09-08 19:00:40.514  3758  3758 I Adreno  : Remote Branch                    : 
09-08 19:00:40.514  3758  3758 I Adreno  : Remote Branch                    : 
09-08 19:00:40.514  3758  3758 I Adreno  : Reconstruct Branch               : 
09-08 19:00:40.597   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dfd1527:true
09-08 19:00:40.657  3758  3758 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 19:00:40.675  3758  3758 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-08 19:00:40.779  3758  3796 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-08 19:00:40.789  3758  3782 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-08 19:00:40.833  3758  3796 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 19:00:40.905   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +657ms
09-08 19:00:40.911  1887  1887 I Keyboard.Facilitator: onFinishInput()
09-08 19:00:40.978  3758  3758 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3758
09-08 19:00:41.105  3758  3758 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-08 19:00:41.117   874  2290 I ActivityManager: Killing 3196:com.google.android.gm/u0a78 (adj 15): empty #17
09-08 19:00:41.191   874  2290 I ActivityManager: Killing 3092:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-08 19:00:41.320  3758  3798 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1715996368
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 19:00:41.326  3758  3798 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a44a743 added. We now have 1 listener(s)
09-08 19:00:41.329  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-08 19:00:41.329  3758  3798 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 19:00:41.330  3758  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:00:41.330  3758  3798 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 19:00:41.333  3758  3798 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9e3e added. We now have 1 listener(s)
09-08 19:00:41.334  3758  3798 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:00:41.336   874  1312 D WifiService: New client listening to asynchronous messages
09-08 19:00:41.336  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 19:00:41.336  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 19:00:41.337  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 19:00:41.337  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 19:00:41.337  3758  3798 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 19:00:41.339  3758  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:00:41.339  3758  3798 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-08 19:00:41.344  3758  3798 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:00:41.344  3758  3798 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:00:41.344  3758  3798 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 19:00:41.344  3758  3798 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 19:00:41.344  3758  3798 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 19:00:41.346  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:00:41.347  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:00:41.361  1512  1512 I ConfigService: onDestroy
09-08 19:00:41.496  3758  3758 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-08 19:00:42.345  3758  3805 W jxcore-log: Initializing JXcore engine
09-08 19:00:42.345  3758  3805 W jxcore-log: JXcore engine is ready
09-08 19:00:42.378  3805  3805 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8931 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-08 19:00:42.378  3805  3805 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11883]" dev="sockfs" ino=11883 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 19:00:42.378  3805  3805 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 19:00:42.378  3805  3805 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26959]" dev="sockfs" ino=26959 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-08 19:00:42.397  3758  3805 W jxcore-log: Starting JXcore engine
09-08 19:00:42.409   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-08 19:00:42.522  3758  3805 W jxcore-log: Platform android
09-08 19:00:42.522  3758  3805 W jxcore-log: 
09-08 19:00:42.522  3758  3805 W jxcore-log: Process ARCH arm
09-08 19:00:42.522  3758  3805 W jxcore-log: 
,09-08 19:00:42.724  3758  3805 I jxcore-log: JXcore Cordova bridge is ready!
09-08 19:00:42.724  3758  3805 I jxcore-log: 
,09-08 19:00:42.725  3758  3805 W jxcore-log: JXcore engine is started
,09-08 19:00:42.740  3758  3798 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 19:00:42.746  3758  3758 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 19:00:50.474   874   887 I ActivityManager: Waited long enough for: ServiceRecord{a44a113 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-08 19:00:50.827  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:00:50.832  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:00:50.834  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:00:50.853  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 19:00:50.853  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 19:00:50.853  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:00:50.853  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:00:50.872  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 19:00:50.872  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 19:00:50.872  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-08 19:00:51.743   874  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 19:00:57.160  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 19:00:57.160  3758  3805 I jxcore-log: 
,09-08 19:00:57.164  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 19:00:57.164  3758  3805 I jxcore-log: 
,09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:00:57.176  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:00:57.182  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:00:57.188  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 19:00:57.188  3758  3805 I jxcore-log: 
,09-08 19:00:57.195  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 19:00:57.195  3758  3805 I jxcore-log: 
,09-08 19:00:57.578  3758  3805 I jxcore-log: Running unit tests
09-08 19:00:57.578  3758  3805 I jxcore-log: 
,09-08 19:00:57.579  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 19:00:57.579  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2233240 added. We now have 2 listener(s)
,09-08 19:00:57.580  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:00:57.580  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:00:57.580  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:00:57.580  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 19:00:57.580  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcc1579 added. We now have 2 listener(s)
09-08 19:00:57.580  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:00:57.581  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 19:00:57.583  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:00:57.589  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:00:57.592  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:00:57.593  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:00:57.593  3758  3805 D executeNativeTests: Running unit tests,
,09-08 19:00:57.601  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:00:57.609  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:00:57.684  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 19:00:57.684  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f added. We now have 3 listener(s)
,09-08 19:00:57.685  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:00:57.685  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:00:57.685  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 19:00:57.685  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:00:57.685  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c added. We now have 3 listener(s)
,09-08 19:00:57.685  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:00:57.686  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 19:00:57.690  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:00:57.700  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:00:57.703  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:00:57.704  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:00:57.706  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 19:00:57.706  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 19:00:57.706  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 19:00:57.706  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 19:00:57.707  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:00:57.708  3758  3805 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 19:00:57.708  3758  3805 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 19:00:57.708  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 19:00:57.708  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 19:00:57.708  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 19:00:57.708  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 19:00:57.708  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:00:57.709  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:00:57.709  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:00:57.709  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:00:57.709  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.709  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:00:57.709  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:00:57.710  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f removed from the list
09-08 19:00:57.710  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.710  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:00:57.710  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c removed from the list
,09-08 19:00:57.710  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:00:57.710  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.710  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.710  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.712  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:00:57.712  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:00:57.712  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.712  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:00:57.715  3758  3805 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 19:00:57.716  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:00:57.716  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:00:57.717  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:00:57.717  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:00:57.717  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.717  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.717  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:00:57.717  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.717  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:00:57.717  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:00:57.718  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.718  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.718  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.718  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:00:57.720  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:00:57.720  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:00:57.720  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.720  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:00:57.728  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 19:00:57.728  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 19:00:57.728  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 19:00:57.729  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 19:00:57.730  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 19:00:57.731  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 19:00:57.731  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:00:57.731  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:00:57.731  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:00:57.731  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:00:57.731  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.731  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.731  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:00:57.731  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.732  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:00:57.732  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:00:57.732  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.732  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.732  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:00:57.732  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:00:57.733  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:00:57.733  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:00:57.733  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:00:57.733  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:00:57.737  3758  3805 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 19:00:57.739  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:00:57.744  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:00:57.745  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 19:00:57.745  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 19:00:57.746  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 19:00:57.746  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 19:00:57.746  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 19:00:57.746  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:00:57.746  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 19:00:57.747  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:00:57.750  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:00:57.752  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 19:00:57.752  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 19:00:57.757  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 19:00:57.759  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 19:00:57.759  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 19:00:57.762  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 19:00:57.765  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 19:00:57.766  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 19:00:57.766  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 19:00:57.767  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 19:00:57.768  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:00:57.772  2721  2735 D BtGatt.GattService: registerClient() - UUID=a084c013-fcc0-4f2f-bcf1-d82b156e8a24
09-08 19:00:57.773  2721  2774 D BtGatt.GattService: onClientRegistered() - UUID=a084c013-fcc0-4f2f-bcf1-d82b156e8a24, clientIf=5
09-08 19:00:57.774  3758  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 19:00:57.775  2721  2734 D BtGatt.GattService: start scan with filters
,09-08 19:00:57.778  2721  2780 D BtGatt.ScanManager: handling starting scan
,09-08 19:00:57.778  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 19:00:57.779  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 19:00:57.779  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 19:00:57.779  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 19:00:57.779  2721  2780 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:00:57.782  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 19:00:57.782  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 19:00:57.783  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 19:00:57.785  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:00:57.787  2721  2774 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 19:00:57.787  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:00:57.788  2721  2780 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 19:00:57.793  3758  3805 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 19:00:57.798  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 19:00:57.798  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:00:57.799  2721  2780 D BtGatt.ScanManager: Starting BLE batch scan
09-08 19:00:57.799  2721  2780 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 19:00:57.814  2721  2774 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 19:00:57.815  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:00:57.821  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 19:00:57.822  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:00:58.189  3034  3812 V KeepSync: Connecting to GoogleApiClient
,09-08 19:00:58.190   874  2285 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 19:00:58.284  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 19:00:58.284  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 19:00:58.285  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed,
,09-08 19:00:58.295  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:00:58.302  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:00:58.326  2721  2721 D BtGatt.ScanManager: awakened up at time 129726
,09-08 19:00:58.329  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:00:58.372  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-08 19:00:58.372  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:00:58.372  2721  2774 D BtGatt.GattService: current time is 129772216842
,09-08 19:00:58.373  2721  2774 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -95, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 19:00:58.378  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 19:00:58.380  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 19:00:58.381  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 19:00:58.382  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 19:00:58.382  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:00:58.383  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:00:58.428  1701  3813 V BaseAuthAsyncOperation: access token request failed
09-08 19:00:58.430  3034  3812 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 19:00:58.526  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 19:00:58.526  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 19:00:58.526  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:00:58.527  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:00:58.571  3034  3812 E KeepSync: IOException
09-08 19:00:58.571  3034  3812 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 19:00:58.571  3034  3812 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:00:58.571  3034  3812 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 19:00:58.571  3034  3812 E KeepSync: 	... 10 more
09-08 19:00:58.571  3034  3812 W KeepSync: Sync result 2
,09-08 19:00:58.587   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129406, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:00:58.878  2721  2721 D BtGatt.ScanManager: awakened up at time 130278
,09-08 19:00:58.880  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:00:58.934  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-08 19:00:58.934  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:00:58.935  2721  2774 D BtGatt.GattService: current time is 130334566430
09-08 19:00:58.936  2721  2774 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -75, 112, 8, 38, 113, -28, 1, -128, -106, 6, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -55, -78, -6, 2, 2, -29, 23, 62, -4, 110, -86, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 19:00:58.936  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 19:00:58.939  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -55, -78, -6, 2, 2, -29, 23, 62, -4, 110, -86]
,09-08 19:00:58.940  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 19:00:58.942  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 19:01:00.440  2721  2721 D BtGatt.ScanManager: awakened up at time 131839
,09-08 19:01:00.442  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:00.470  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 19:01:00.471  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:00.471  2721  2774 D BtGatt.GattService: current time is 131870937362
09-08 19:01:00.471  2721  2774 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -96, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:01:00.472  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:01:01.977  2721  2721 D BtGatt.ScanManager: awakened up at time 133376
,09-08 19:01:01.982  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:02.026  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 19:01:02.027  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:02.028  2721  2774 D BtGatt.GattService: current time is 133427536738
09-08 19:01:02.029  2721  2774 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -88, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -95, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 19:01:02.030  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 19:01:02.031  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 19:01:02.031  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 19:01:02.032  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 19:01:02.032  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 19:01:02.033  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:01:02.803  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:02.804  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:01:02.804  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 19:01:02.805  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:02.806  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 19:01:02.806  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 19:01:02.806  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:01:02.807  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 19:01:02.807  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 19:01:02.809  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 19:01:02.810  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 19:01:02.813  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:01:02.815  2721  2734 D BtGatt.GattService: stopScan() - queue size =1
,09-08 19:01:02.818  2721  2927 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 19:01:02.820  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 19:01:02.820  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 19:01:02.821  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 19:01:02.821  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 19:01:02.822  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 19:01:02.826  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:01:02.827  2721  2721 D BtGatt.ScanManager: awakened up at time 134226
,09-08 19:01:02.828  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 19:01:02.828  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 19:01:02.828  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 19:01:02.829  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:01:02.831  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:02.831  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:01:02.831  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:02.831  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:01:02.831  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
,09-08 19:01:02.831  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:01:02.831  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:02.832  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:02.832  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-08 19:01:02.832  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:02.832  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:02.837  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 19:01:02.837  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:02.837  2721  2780 D BtGatt.ScanManager: stopping BLe Batch
,09-08 19:01:02.851  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 19:01:02.851  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:02.851  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:02.865  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 19:01:02.865  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:02.866  2721  2774 D BtGatt.GattService: current time is 134265462029
09-08 19:01:02.866  2721  2774 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -64, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
09-08 19:01:02.866  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,09-08 19:01:03.332  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:01:07.833  3758  3805 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 19:01:07.839  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:07.853  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:07.860  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:01:07.861  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:01:07.863  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 19:01:07.864  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 19:01:07.864  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 19:01:07.864  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:01:07.865  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 19:01:07.869  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:07.878  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 19:01:07.878  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 19:01:07.878  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:07.892  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 19:01:07.895  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 19:01:07.895  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 19:01:07.906  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 19:01:07.906  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 19:01:07.907  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 19:01:07.909  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:01:07.917  2721  2735 D BtGatt.GattService: registerClient() - UUID=d4825f48-aa28-4cb2-9e0d-a556d7da2a38
,09-08 19:01:07.919  2721  2774 D BtGatt.GattService: onClientRegistered() - UUID=d4825f48-aa28-4cb2-9e0d-a556d7da2a38, clientIf=5
09-08 19:01:07.920  3758  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 19:01:07.921  2721  2734 D BtGatt.GattService: start scan with filters
,09-08 19:01:07.931  2721  2780 D BtGatt.ScanManager: handling starting scan
09-08 19:01:07.932  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 19:01:07.932  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 19:01:07.932  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 19:01:07.933  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 19:01:07.943  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 19:01:07.944  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 19:01:07.944  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 19:01:07.951  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:01:07.953  2721  2774 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 19:01:07.953  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:07.953  2721  2780 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 19:01:07.958  3758  3805 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 19:01:07.962  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:07.962  3758  3805 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 19:01:07.962  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:07.962  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 19:01:07.962  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:07.962  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 19:01:07.962  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 19:01:07.962  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:01:07.962  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 19:01:07.962  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 19:01:07.963  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 19:01:07.963  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 19:01:07.965  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:01:07.966  2721  2735 D BtGatt.GattService: stopScan() - queue size =1
,09-08 19:01:07.966  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 19:01:07.967  2721  2926 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 19:01:07.967  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:07.967  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 19:01:07.967  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 19:01:07.967  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 19:01:07.967  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 19:01:07.968  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 19:01:07.968  2721  2780 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 19:01:07.970  2721  2780 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 19:01:07.971  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:01:07.971  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 19:01:07.971  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 19:01:07.971  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 19:01:07.972  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 19:01:07.974  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 19:01:07.975  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:01:07.975  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:01:07.975  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:07.975  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:07.975  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:01:07.975  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:07.976  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:07.976  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:07.976  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:07.976  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:07.976  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:07.976  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:07.977  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:07.977  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:07.977  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:07.978  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:07.978  3758  3805 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 19:01:07.981  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:07.986  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:07.989  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:01:07.990  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:01:07.990  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 19:01:07.990  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 19:01:07.990  2721  2774 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 19:01:07.990  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 19:01:07.990  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:01:07.990  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:07.990  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 19:01:07.992  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:07.995  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:07.998  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 19:01:07.998  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:07.999  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 19:01:07.999  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 19:01:08.004  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 19:01:08.006  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 19:01:08.006  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 19:01:08.008  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 19:01:08.008  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:08.009  2721  2780 D BtGatt.ScanManager: stopping BLe Batch
,09-08 19:01:08.014  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 19:01:08.014  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 19:01:08.014  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 19:01:08.015  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:01:08.019  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 19:01:08.020  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:08.020  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:08.020  2721  2917 D BtGatt.GattService: registerClient() - UUID=bbec4a7a-6546-44be-b294-f9bea7683056
09-08 19:01:08.020  2721  2774 D BtGatt.GattService: onClientRegistered() - UUID=bbec4a7a-6546-44be-b294-f9bea7683056, clientIf=5
09-08 19:01:08.021  3758  3768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 19:01:08.021  2721  2735 D BtGatt.GattService: start scan with filters
,09-08 19:01:08.027  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 19:01:08.027  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 19:01:08.027  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 19:01:08.027  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 19:01:08.029  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 19:01:08.029  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:08.031  2721  2780 D BtGatt.ScanManager: handling starting scan
,09-08 19:01:08.031  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 19:01:08.031  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 19:01:08.031  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-08 19:01:08.033  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:01:08.036  3758  3805 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 19:01:08.038  2721  2774 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 19:01:08.038  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:08.038  2721  2780 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 19:01:08.045  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 19:01:08.045  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:08.045  2721  2780 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 19:01:08.045  2721  2780 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 19:01:08.058  2721  2774 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 19:01:08.058  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:08.066  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 19:01:08.066  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:08.533  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 19:01:08.533  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 19:01:08.534  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 19:01:09.572  2721  2721 D BtGatt.ScanManager: awakened up at time 140971
,09-08 19:01:09.578  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:09.637  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-08 19:01:09.638  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:09.638  2721  2774 D BtGatt.GattService: current time is 141037607809
09-08 19:01:09.638  2721  2774 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -97, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -75, 112, 8, 38, 113, -28, 1, -128, -107, 13, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -44, -78, -6, 2, 2, -29, 23, 62, 50, 79, -126, 0]
,09-08 19:01:09.638  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 19:01:09.638  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 19:01:09.639  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 19:01:09.639  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 19:01:09.639  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 19:01:09.639  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 19:01:09.639  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -44, -78, -6, 2, 2, -29, 23, 62, 50, 79, -126]
,09-08 19:01:11.140  2721  2721 D BtGatt.ScanManager: awakened up at time 142539
,09-08 19:01:11.143  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:11.184  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 19:01:11.185  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:11.400  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:11.412  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:11.415  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:11.473  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 19:01:11.474  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 19:01:11.474  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:01:11.474  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:11.523  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 19:01:11.526  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 19:01:11.529  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-08 19:01:12.670  2721  2721 D BtGatt.ScanManager: awakened up at time 144070
,09-08 19:01:12.674  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:12.716  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 19:01:12.717  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:12.717  2721  2774 D BtGatt.GattService: current time is 144116780565
,09-08 19:01:12.717  2721  2774 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -68, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -88, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -94, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:01:12.717  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 19:01:12.718  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 19:01:12.718  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 19:01:12.718  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 19:01:12.718  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 19:01:12.719  2721  2774 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:01:13.037  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:13.037  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:13.038  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 19:01:13.038  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:13.038  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 19:01:13.039  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 19:01:13.039  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:01:13.039  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 19:01:13.040  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 19:01:13.040  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 19:01:13.040  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 19:01:13.043  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:01:13.045  2721  2927 D BtGatt.GattService: stopScan() - queue size =1
,09-08 19:01:13.047  2721  2734 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 19:01:13.049  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 19:01:13.049  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 19:01:13.049  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 19:01:13.050  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 19:01:13.050  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 19:01:13.056  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:01:13.057  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 19:01:13.058  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 19:01:13.058  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 19:01:13.060  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 19:01:13.063  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 19:01:13.064  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:01:13.064  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 19:01:13.071  2721  2774 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 19:01:13.071  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:01:13.071  2721  2780 D BtGatt.ScanManager: stopping BLe Batch
,09-08 19:01:13.087  2721  2774 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 19:01:13.088  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:13.088  2721  2780 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:01:13.100  2721  2774 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 19:01:13.100  2721  2774 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:01:13.565  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:01:13.566  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:13.566  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 19:01:16.884   874  1854 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148283, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:01:18.064  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:18.065  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.065  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 19:01:18.066  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:18.066  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.066  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:01:18.067  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
,09-08 19:01:18.067  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.067  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.068  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:18.068  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.069  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.070  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.073  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.073  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:01:18.074  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.074  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:18.076  3758  3805 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 19:01:18.078  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.079  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:01:18.079  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.079  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.080  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.080  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.080  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.081  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.081  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:18.081  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.081  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.082  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.082  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.082  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.086  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 19:01:18.086  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.086  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.086  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.088  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 19:01:18.089  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.089  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.089  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.090  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.090  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:18.090  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.090  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.090  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.091  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.091  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.091  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:18.091  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.091  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.091  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.093  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.093  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:01:18.094  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.094  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:18.095  3758  3805 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 19:01:18.096  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:18.096  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.096  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.096  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.096  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.097  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.097  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.097  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.097  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.098  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.098  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:18.098  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.098  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.098  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.100  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.100  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.100  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:18.101  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:18.102  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 19:01:18.102  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.102  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.103  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 19:01:18.103  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.103  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.103  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.104  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.104  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:18.104  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.104  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.104  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.104  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.104  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.104  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.106  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.106  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.106  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.106  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.106  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 19:01:18.107  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 19:01:18.107  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 19:01:18.107  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 19:01:18.108  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.108  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.108  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.108  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.108  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.108  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.108  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
,09-08 19:01:18.108  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.108  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.108  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.108  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.108  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.109  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.109  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.111  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.111  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.111  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:18.111  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.112  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 19:01:18.112  3758  3805 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 19:01:18.113  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 19:01:18.116  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 19:01:18.116  3758  3805 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 19:01:18.117  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 19:01:18.118  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 19:01:18.119  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-08 19:01:18.119  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-08 19:01:18.120  3758  3805 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 19:01:18.120  3758  3805 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 19:01:18.120  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 19:01:18.120  3758  3805 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 19:01:18.121  3758  3805 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,09-08 19:01:18.121  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 19:01:18.121  3758  3805 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 19:01:18.121  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 19:01:18.125  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-08 19:01:18.126  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 19:01:18.126  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 19:01:18.127  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 19:01:18.127  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-08 19:01:18.127  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 19:01:18.127  3758  3805 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 19:01:18.127  3758  3805 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 19:01:18.128  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:18.128  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:01:18.128  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.129  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.129  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.129  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.129  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 19:01:18.129  3758  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 381)
,09-08 19:01:18.130  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
,09-08 19:01:18.130  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 19:01:18.130  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.130  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.130  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.130  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:18.130  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.131  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.131  3758  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 381
09-08 19:01:18.135  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.135  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.135  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.135  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.136  3758  3805 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 19:01:18.137  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.137  3758  3816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 19:01:18.137  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.137  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.137  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.137  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.137  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.138  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.138  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.138  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.138  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.138  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.138  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.138  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.138  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.140  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.140  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.140  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.140  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.142  3758  3805 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 19:01:18.142  3758  3805 I io.jx,core.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.142  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.142  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.143  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.143  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.143  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.143  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.143  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.143  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.144  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.144  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.144  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.144  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.144  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.145  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.145  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.145  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.145  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.146  3758  3805 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 19:01:18.146  3758  3805 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 19:01:18.146  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 19:01:18.146  3758  3805 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 19:01:18.146  3758  3805 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 19:01:18.146  3758  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 19:01:18.146  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 19:01:18.146  3758  3805 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 19:01:18.147  3758  3805 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 19:01:18.147  3758  3805 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 19:01:18.147  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 19:01:18.147  3758  3805 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 19:01:18.147  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:18.147  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:18.147  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:18.147  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.147  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.147  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.147  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.148  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.148  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.148  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.148  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.148  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.148  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.148  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.149  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:18.149  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:18.149  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.149  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.150  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:18.150  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.150  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:18.150  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:18.150  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:18.150  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:18.150  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:18.150  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:18.150  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:21.546   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 19:01:21.558  1887  1887 I Keyboard.Facilitator: onFinishInput()
,09-08 19:01:21.565   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 19:01:21.565   874   894 I Adreno  : Build Date                       : 10/20/15
09-08 19:01:21.565   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 19:01:21.565   874   894 I Adreno  : Local Branch                     : M14
09-08 19:01:21.565   874   894 I Adreno  : Remote Branch                    : 
09-08 19:01:21.565   874   894 I Adreno  : Remote Branch                    : 
09-08 19:01:21.565   874   894 I Adreno  : Reconstruct Branch               : 
,09-08 19:01:21.617   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (389 us)
,09-08 19:01:22.307  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 19:01:22.307  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 19:01:22.342   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 19:01:22.348  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c52f632 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@865e81e, 16908290=android.view.AbsSavedState$1@865e81e}, android:focusedViewId=100}]}]
,09-08 19:01:22.348  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-08 19:01:22.349  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 19:01:22.349  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 19:01:22.357   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-08 19:01:22.362   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-08 19:01:22.362   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-08 19:01:22.363   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-08 19:01:22.591   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 19:01:22.594   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 19:01:22.600   874  1335 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-08 19:01:22.604   874   894 I DreamManagerService: Entering dreamland.
,09-08 19:01:22.606   874   894 I PowerManagerService: Dozing...
09-08 19:01:22.608   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 19:01:22.663   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-08 19:01:22.664   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 19:01:22.675   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:01:22.685  1952  3823 D NfcService: Discovery configuration equal, not updating.
,09-08 19:01:22.689   874  1311 E native  : do suspend false
,09-08 19:01:22.706   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 19:01:22.714   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:01:22.718   874  1311 E native  : do suspend true
,09-08 19:01:22.805   377  1319 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 19:01:22.805   377  1319 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 19:01:23.151  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:23.152  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.152  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:23.152  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:23.152  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.153  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
,09-08 19:01:23.153  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:23.154  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:01:23.154  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 19:01:23.154  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:23.155  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:23.155  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.155  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.156  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.156  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.156  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:23.156  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.157  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.157  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.157  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.161  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:23.162  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:23.162  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.163  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.169  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 19:01:23.170  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:01:23.173  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 19:01:23.175  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 19:01:23.175  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 19:01:23.177  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 19:01:23.177  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 19:01:23.177   874  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
09-08 19:01:23.177  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 19:01:23.178  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:23.179  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 19:01:23.179  3758  3827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 19:01:23.179  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 19:01:23.179  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 19:01:23.179  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.180  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 19:01:23.180  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 19:01:23.180  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.181  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.181  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 19:01:23.181  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 19:01:23.181  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 19:01:23.182  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.182  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.183  3758  3827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 19:01:23.183  3758  3827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 19:01:23.183  3758  3827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 19:01:23.185  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 19:01:23.186  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.186  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 19:01:23.187  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:23.187  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:01:23.187  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:23.187  3758  3758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 19:01:23.187  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:23.187  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:01:23.187  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:01:23.188  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.188  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.188  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.188  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.189  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.189  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:23.189  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.189  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.189  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.190  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.192  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 19:01:23.192  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:23.193  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.193  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:23.196  3758  3805 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-08 19:01:23.196  3758  3805 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 19:01:23.197  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 19:01:23.199  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 19:01:23.199  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 19:01:23.199  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 19:01:23.199  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:23.199  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:23.199  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:23.199  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.200  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.200  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.200  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.200  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.200  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:23.200  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.200  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.200  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.200  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.202  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:01:23.202  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:23.202  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.202  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list,
,09-08 19:01:23.212  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:23.212  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:23.212  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:01:23.212  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:23.212  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.212  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.212  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.212  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:23.212  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.212  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:23.212  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.213  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.213  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 19:01:23.213  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.215  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 19:01:23.215  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:01:23.215  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:23.215  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.216  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:01:23.216  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:01:23.217  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 19:01:23.217  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:01:23.217  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:23.217  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:23.217  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2869e0f not in the list
09-08 19:01:23.217  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:23.217  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
09-08 19:01:23.217  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:23.217  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:23.218  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.218  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 19:01:23.218  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:23.219  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 19:01:23.219  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:01:23.219  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:23.220  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6140e9c not in the list
,09-08 19:01:23.221  3758  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 19:01:23.221  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 19:01:23.221  3758  3805 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 19:01:23.222  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 19:01:23.222  3758  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 19:01:23.222  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 19:01:23.226  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 19:01:23.226  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 19:01:23.227  3758  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 19:01:23.227  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 19:01:23.227  3758  3805 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 19:01:23.227  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-08 19:01:23.227  3758  3805 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 19:01:23.227  3758  3805 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 19:01:23.228  3758  3805 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 19:01:23.228  3758  3805 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 19:01:23.229  3758  3805 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 19:01:23.229  3758  3805 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 19:01:23.229  3758  3805 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 19:01:23.229  3758  3805 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 19:01:23.231  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:01:23.231  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55128ff added. We now have 3 listener(s)
09-08 19:01:23.231  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:01:23.234  3758  3805 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 19:01:23.235   874  1400 D WifiService: setWifiEnabled: true pid=3758, uid=10000
09-08 19:01:23.235   874  1400 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 19:01:23.269  2721  2901 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 19:01:23.269  2721  2913 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 19:01:23.270  3758  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 381)
,09-08 19:01:23.689  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:01:26.611  1900  2654 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 19:01:28.244  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 19:01:28.245  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24656cc added. We now have 4 listener(s)
09-08 19:01:28.245  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:01:28.266  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:28.266  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24656cc removed from the list
09-08 19:01:28.267  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:28.267  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:28.267  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:28.270  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:01:28.270  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42d4d15 added. We now have 4 listener(s)
09-08 19:01:28.271  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:01:28.275  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:28.276  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@42d4d15 removed from the list
,09-08 19:01:28.276  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:01:28.276  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:28.277  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:28.280  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 19:01:28.281  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@804682a added. We now have 4 listener(s)
09-08 19:01:28.281  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:01:28.290   874  2290 D WifiService: setWifiEnabled: false pid=3758, uid=10000
,09-08 19:01:28.290   874  2290 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 19:01:28.306  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:01:28.306  2721  2770 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 19:01:28.306  2721  2770 D BluetoothAdapterProperties: Setting state to 13
,09-08 19:01:28.307  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 19:01:28.309  2721  2770 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 19:01:28.311  2721  2770 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:28.320  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:28.320  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:01:28.322  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.322  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:28.322  2721  2721 D BluetoothMapService: onReceive
09-08 19:01:28.322  2721  2721 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 19:01:28.322  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 19:01:28.323  2721  2721 D BluetoothMapService: STATE_TURNING_OFF
09-08 19:01:28.324  2721  2721 D BluetoothMapService: MAP Service closeService in
09-08 19:01:28.324  2721  2721 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 19:01:28.324  2721  2721 D ObexServerSockets0: shutdown(block = true)
09-08 19:01:28.325  2721  2721 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 19:01:28.325  2721  2721 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 19:01:28.325  2721  2929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 19:01:28.327  2721  2913 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 19:01:28.327  2721  2928 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 19:01:28.328  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:28.328  2721  2721 I BtOppRfcommListener: stopping Accept Thread
09-08 19:01:28.328  2721  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 19:01:28.329  2721  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 19:01:28.331  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:28.335  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:28.335  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:01:28.336  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.336  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:01:28.342  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:28.342  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:01:28.343  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 19:01:28.343  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.343  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:01:28.344   874  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 19:01:28.344   874  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 19:01:28.344   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 19:01:28.345   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 19:01:28.346  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:28.352   874   887 I ActivityManager: Start proc 3832:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 19:01:28.353  2721  2774 D BluetoothAdapterProperties: Scan Mode:20
,09-08 19:01:28.353  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 19:01:28.357  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:28.359  2721  2721 D HeadsetService: Received stop request...Stopping profile...
,09-08 19:01:28.360  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:28.361  1367  1381 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:28.361   874   874 D BluetoothHeadset: Proxy object disconnected
,09-08 19:01:28.361   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:28.361  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-08 19:01:28.361   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:28.361  2721  2721 D A2dpService: Received stop request...Stopping profile...
,09-08 19:01:28.362  1966  1977 D BluetoothHeadset: Proxy object disconnected
,09-08 19:01:28.362  2721  2921 D A2dpStateMachine: Exit Disconnected: -1
09-08 19:01:28.363   874  1311 E native  : do suspend true
09-08 19:01:28.363  1367  1367 D BluetoothA2dp: Proxy object disconnected
,09-08 19:01:28.364   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 19:01:28.364  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:28.364  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.364  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.364  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:01:28.364  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.366  2721  2721 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 19:01:28.367  2721  2721 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 19:01:28.367  2721  2774 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-08 19:01:28.367  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 19:01:28.367  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:28.367  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 19:01:28.367  2721  2721 D HidService: Received stop request...Stopping profile...
,09-08 19:01:28.367  2721  2774 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 19:01:28.367  2721  2721 D HidService: Stopping Bluetooth HidService
,09-08 19:01:28.369  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.369  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.369  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:01:28.369  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.369  1367  1367 D BluetoothInputDevice: Proxy object disconnected
,09-08 19:01:28.369  1367  1367 D HidProfile: Bluetooth service disconnected
09-08 19:01:28.371  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 19:01:28.371  2721  2721 D HealthService: Received stop request...Stopping profile...
,09-08 19:01:28.371  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:28.371  2721  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 19:01:28.371  2721  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 19:01:28.371  2721  2901 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 19:01:28.371  2721  2901 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 19:01:28.371  2721  2774 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 19:01:28.374  2721  2721 D PanService: Received stop request...Stopping profile...
09-08 19:01:28.375  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 19:01:28.375  1367  1367 D PanProfile: Bluetooth service disconnected
,09-08 19:01:28.376  2721  2721 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 19:01:28.376  2721  2721 D BluetoothMapService: stop()
,09-08 19:01:28.377   874  1863 D DhcpClient: Clearing IP address
09-08 19:01:28.377  2721  2721 D BluetoothMapAppObserver: deinitObservers()
09-08 19:01:28.377  2721  2721 D BluetoothMapAppObserver: removeReceiver()
09-08 19:01:28.377   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 19:01:28.380  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.380  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.380  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:28.380  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.380  1367  1367 D BluetoothMap: Proxy object disconnected
,09-08 19:01:28.380  1367  1367 D MapProfile: Bluetooth service disconnected
09-08 19:01:28.381   373   872 D CommandListener: Setting iface cfg
09-08 19:01:28.384  1512  2447 V NativeCrypto: Read error: ssl=0x9af10600: I/O error during system call, Connection timed out
09-08 19:01:28.386   874  1866 D DhcpClient: Receive thread stopped
,09-08 19:01:28.386  1512  2447 V NativeCrypto: SSL shutdown failed: ssl=0x9af10600: I/O error during system call, Broken pipe
09-08 19:01:28.388  2721  2721 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-08 19:01:28.389  2721  2774 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 19:01:28.389  2721  2721 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 19:01:28.390   874  1695 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-08 19:01:28.390   874  1853 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-08 19:01:28.394   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 19:01:28.394  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.394  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.394   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 19:01:28.394  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:01:28.394  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.395  2721  2721 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 19:01:28.395  2721  2774 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 19:01:28.396  2721  2721 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 19:01:28.397  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.397  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.397  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:01:28.397  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.397   874  1853 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-08 19:01:28.397  2721  2721 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 19:01:28.398  2721  2721 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 19:01:28.399  2721  2721 D BluetoothMapService: MAP Service closeService in
,09-08 19:01:28.399  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:28.399  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:28.399  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:01:28.399  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:28.399  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-08 19:01:28.399  2721  2721 D BluetoothMapService: cleanup()
09-08 19:01:28.400  2721  2721 D BluetoothMapService: MAP Service closeService in
09-08 19:01:28.402   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 19:01:28.403   874  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 19:01:28.403   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 19:01:28.404   874  1311 E native  : do suspend true
,09-08 19:01:28.405  2721  2770 D BluetoothAdapterProperties: Setting state to 15
09-08 19:01:28.406  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 19:01:28.406   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:28.406  2721  2770 I BluetoothAdapterState: Entering BleOnState
09-08 19:01:28.406  1966  2113 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:28.407  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 19:01:28.407  1367  1381 D BluetoothPan: onBluetoothStateChange on: false
09-08 19:01:28.408  1367  2081 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 19:01:28.409   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:28.409  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 19:01:28.409   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:28.409   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 19:01:28.409  1367  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-08 19:01:28.409   874  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-08 19:01:28.410  1367  2081 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 19:01:28.410  2721  2770 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-08 19:01:28.410  2721  2770 D BluetoothAdapterProperties: Setting state to 16
09-08 19:01:28.411  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 19:01:28.411  2721  2770 D BluetoothAdapterProperties: onBleDisable
,09-08 19:01:28.414  2721  2771 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 19:01:28.414  2721  2770 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:28.414  2721  2901 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 19:01:28.415  2721  2901 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:28.415   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 19:01:28.417  2721  2774 D BluetoothAdapterProperties: Scan Mode:20
09-08 19:01:28.417  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.417  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:28.418   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 19:01:28.418  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.418  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:28.422  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.422  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 19:01:28.422  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.422  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:28.425  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.425  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:28.426  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.426  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:28.427  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.427  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:28.429  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.429  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:28.430  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:28.433   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:01:28.437  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.437  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 19:01:28.437  1900  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 19:01:28.437  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.438  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:28.438   874  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 19:01:28.439  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.439  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:28.439  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.439  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:28.441  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:28.441  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:28.442  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:28.442  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:28.443   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:28.448  3832  3832 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 19:01:28.459   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:28.460   874  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 19:01:28.460   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:28.461   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 19:01:28.464  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:28.465  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:28.468  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:28.470  3374  3374 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@260e866 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-08 19:01:28.475  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 19:01:28.478   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af32c0:true
,09-08 19:01:28.480  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:01:28.492   874  2290 I ActivityManager: Start proc 3851:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 19:01:28.501  3832  3832 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 19:01:28.503  3832  3832 D BluetoothMap: Create BluetoothMap proxy object
,09-08 19:01:28.523  3851  3851 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 19:01:28.524  3832  3832 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 19:01:28.524   373   872 E Netd    : netlink response contains error (No such file or directory)
09-08 19:01:28.525   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 19:01:28.535  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,09-08 19:01:28.543   874  1985 I ActivityManager: Killing 2993:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 19:01:28.623  2721  2774 I bt_hci  : shut_down
,09-08 19:01:28.624  2721  2781 D bt_hwcfg: hw_epilog_process
,09-08 19:01:28.643  2721  2781 I bt_vendor: low_power_mode_cb
,09-08 19:01:28.667  2721  2781 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 19:01:28.667  2721  2781 I bt_vendor: epilog_cb
,09-08 19:01:28.668  2721  2781 I bt_hci  : epilog_finished_callback
,09-08 19:01:28.674  2721  2774 I bt_hci_h4: hal_close
,09-08 19:01:28.675  2721  2774 I bt_userial_vendor: device fd = 51 close
,09-08 19:01:28.701  3851  3851 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.701  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.702  3851  3851 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 19:01:28.702  3851  3851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 19:01:28.717  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 19:01:28.726  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:01:28.727  3832  3832 D DockEventReceiver: finishStartingService: stopping service
09-08 19:01:28.728   874  2285 I ActivityManager: Killing 3374:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 19:01:28.884   874  2285 I ActivityManager: Start proc 3885:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 19:01:28.893  3851  3877 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 19:01:28.896  2721  2771 D bt_stack_manager: event_shut_down_stack finished.
,09-08 19:01:28.897  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 19:01:28.906  2721  2721 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 19:01:28.906  2721  2770 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 19:01:28.906  2721  2721 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 19:01:28.906  2721  2721 D BtGatt.GattService: stop()
,09-08 19:01:28.906  2721  2721 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 19:01:28.909  2721  2721 V BluetoothAdapterState: isTurningOff()=false
,09-08 19:01:28.909  2721  2721 V BluetoothAdapterState: isTurningOn()=false
,09-08 19:01:28.909  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:28.909  2721  2721 V BluetoothAdapterState: isBleTurningOff()=true
09-08 19:01:28.910  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25,
09-08 19:01:28.910  2721  2770 D BluetoothAdapterProperties: Setting state to 10
,09-08 19:01:28.910  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 19:01:28.910  2721  2770 I BluetoothAdapterState: Entering OffState
,09-08 19:01:28.912   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 19:01:28.933  2721  2721 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-08 19:01:28.933  2721  2721 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 19:01:28.933  2721  2721 I BluetoothServiceJni: cleanupNative: return from cleanup
09-08 19:01:28.934  2721  2771 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 19:01:28.936  2721  2771 D bt_stack_manager: event_clean_up_stack finished.
,09-08 19:01:28.951  2721  2721 I art     : System.exit called, status: 0
,09-08 19:01:28.954  2721  2721 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 19:01:28.965  3885  3885 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 19:01:29.000   874   884 I ActivityManager: Process com.android.bluetooth (pid 2721) has died
,09-08 19:01:29.019   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@40dc823:true
,09-08 19:01:29.035  3885  3885 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 19:01:29.052  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 19:01:29.055  1701  1701 D SystemUpdateService: onCreate
,09-08 19:01:29.059  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 19:01:29.062  1701  3912 I SystemUpdateService: active receiver: enabled
,09-08 19:01:29.065  1701  3912 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 19:01:29.066  1701  3912 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 19:01:29.066  1701  3912 I SystemUpdateService: now status is 0 (complete)
,09-08 19:01:29.066  1701  3912 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 19:01:29.066  1701  3912 I SystemUpdateService: file has been verified
09-08 19:01:29.066  1701  3912 I SystemUpdateService: OTA package size = 12249756
,09-08 19:01:29.072  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 19:01:29.076  1701  2415 I iu.UploadsManager: num queued entries: 0
,09-08 19:01:29.077  1701  2415 I iu.UploadsManager: num updated entries: 0
,09-08 19:01:29.078  1701  2415 I iu.SyncManager: NEXT; no task
,09-08 19:01:29.079  1701  3912 I SystemUpdateService: showing system update notification
,09-08 19:01:29.094  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 19:01:29.095  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 19:01:29.096  1701  1701 D SystemUpdateService: onDestroy
,09-08 19:01:29.120   874  1694 I ActivityManager: Start proc 3914:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 19:01:29.159  3914  3914 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 19:01:29.161  3914  3914 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:29.167  3914  3914 D SprintDMHelper: simOperator: 
09-08 19:01:29.167  3914  3914 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 19:01:29.207   874  1694 I ActivityManager: Start proc 3926:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-08 19:01:29.208   874  1694 I ActivityManager: Killing 3437:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 19:01:29.385   874   884 I ActivityManager: Start proc 3941:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 19:01:29.389   874   884 I ActivityManager: Killing 3596:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-08 19:01:29.467  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 19:01:29.546  3941  3941 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 19:01:29.546  3941  3941 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 19:01:29.546  3941  3941 I GAv4    :   adb logcat -s GAv4
,09-08 19:01:29.573  3941  3941 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 19:01:29.582  3941  3941 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 19:01:29.617  3941  3959 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 19:01:29.734  3941  3941 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 19:01:29.784  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 19:01:29.791  3941  3941 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1188-1190)
,09-08 19:01:29.791  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 19:01:29.801  3941  3941 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c8f2af0}
,09-08 19:01:29.802  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 19:01:29.802  3941  3941 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 19:01:29.808  3941  3941 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 19:01:29.809  3941  3941 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 19:01:29.823  3941  3941 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 19:01:29.833  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 19:01:29.833  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 19:01:29.833  3941  3941 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 19:01:29.833  3941  3941 I Adreno  : Build Date                       : 10/20/15
09-08 19:01:29.833  3941  3941 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 19:01:29.833  3941  3941 I Adreno  : Local Branch                     : M14
09-08 19:01:29.833  3941  3941 I Adreno  : Remote Branch                    : 
09-08 19:01:29.833  3941  3941 I Adreno  : Remote Branch                    : 
09-08 19:01:29.833  3941  3941 I Adreno  : Reconstruct Branch               : 
,09-08 19:01:29.891  3941  3941 I NSApplication: Starting up...
,09-08 19:01:29.908  3941  3987 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 19:01:29.931   874  1985 I ActivityManager: Start proc 3992:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 19:01:29.933   874  1985 I ActivityManager: Killing 1720:android.process.acore/u0a5 (adj 15): empty #17
,09-08 19:01:30.009  3992  3992 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 19:01:30.208   874  2291 I ActivityManager: Killing 3647:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 19:01:33.328   874  2291 D WifiService: setWifiEnabled: true pid=3758, uid=10000
,09-08 19:01:33.329   874  2291 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 19:01:33.342   874  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 19:01:33.353  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:33.353  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:33.354  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.354  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:33.356  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:33.356  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:33.357  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.357  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:33.359  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:33.359  3758  3758 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-08 19:01:33.360  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:33.360  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:33.376   874  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 19:01:33.377   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 19:01:33.378   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 19:01:33.379   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 19:01:33.379   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 19:01:33.380   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 19:01:33.380   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 19:01:33.398   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 19:01:33.399   874  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=12.88 delta 1000 -> 994
,09-08 19:01:33.399   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 19:01:33.400   373   872 D CommandListener: Setting iface cfg
,09-08 19:01:33.401   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 19:01:33.401   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 19:01:33.417   874  1311 E native  : do suspend true
09-08 19:01:33.418   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 19:01:33.425   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 19:01:33.438   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 19:01:33.439   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 19:01:33.454   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 19:01:33.531   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 19:01:33.534  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 19:01:34.014  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 19:01:34.046   874  2285 I ActivityManager: Killing 3663:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 19:01:34.125  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 19:01:34.125  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 19:01:34.134   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:01:34.151   874  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 19:01:34.152   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 19:01:34.152   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 19:01:34.171   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 19:01:34.180   373   872 D CommandListener: Setting iface cfg
,09-08 19:01:34.181   874  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 19:01:34.196   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 19:01:34.222   874  4015 D DhcpClient: Receive thread started
,09-08 19:01:34.304   874  1311 E native  : do suspend false
,09-08 19:01:34.327   874  1863 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 19:01:34.370   874  4015 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172657, domain null
,09-08 19:01:34.371   874  1863 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172657 seconds
,09-08 19:01:34.376   874  1863 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 19:01:34.398   874  4015 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 19:01:34.400   874  1863 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 19:01:34.404   373   872 D CommandListener: Setting iface cfg
,09-08 19:01:34.410   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 19:01:34.415   874  1311 E native  : do suspend true
,09-08 19:01:34.416   874  1863 D DhcpClient: Scheduling renewal in 86399s
,09-08 19:01:34.432   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 19:01:34.434   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 19:01:34.435   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 19:01:34.437   874  1313 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 19:01:34.445   874  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 19:01:34.525   874  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 19:01:34.525   874  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 19:01:34.530   874  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 19:01:34.537   874  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 19:01:34.538   874  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 19:01:34.544   874  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 19:01:34.549   874  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 19:01:34.549   874  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-08 19:01:34.549   874  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 19:01:34.549   874  1313 D ConnectivityService:    accepting network in place of null
,09-08 19:01:34.549   874  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 19:01:34.550   874  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 19:01:34.551   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 19:01:34.565   874  4014 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165964, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:01:34.577   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:34.625   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:34.635   874  4013 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 19:01:34.636   874  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 19:01:34.636   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:34.648   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 19:01:34.654   874  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 19:01:34.661  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:34.661  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:34.661  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:34.661  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:34.664  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:34.664  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:34.664  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:34.664  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:01:34.667  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:01:34.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:01:34.667  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:34.667  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-08 19:01:34.684  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 19:01:34.690  1701  1701 D SystemUpdateService: onCreate
,09-08 19:01:34.693  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 19:01:34.700   874  4013 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 17:01:34 GMT], X-Android-Received-Millis=[1473354094699], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473354094673]}
,09-08 19:01:34.700   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 19:01:34.701   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-08 19:01:34.701   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 19:01:34.702   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 19:01:34.724  1701  4025 I SystemUpdateService: active receiver: enabled
,09-08 19:01:34.729  1701  4025 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 19:01:34.732  1701  4025 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 19:01:34.732  1701  4025 I SystemUpdateService: now status is 0 (complete)
09-08 19:01:34.732  1701  4025 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 19:01:34.732  1701  4025 I SystemUpdateService: file has been verified
09-08 19:01:34.732  1701  4025 I SystemUpdateService: OTA package size = 12249756
,09-08 19:01:34.739  1701  4025 I SystemUpdateService: showing system update notification
,09-08 19:01:34.754   874   886 I ActivityManager: Start proc 4028:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-08 19:01:34.773  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-08 19:01:34.782  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 19:01:34.785  1701  1701 D SystemUpdateService: onDestroy
,09-08 19:01:34.785  1701  2415 I iu.UploadsManager: num queued entries: 0
,09-08 19:01:34.794  1701  2415 I iu.UploadsManager: num updated entries: 0
09-08 19:01:34.794  1701  2415 I iu.SyncManager: NEXT; no task
,09-08 19:01:34.796  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 19:01:34.797  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 19:01:34.799  3914  3914 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:34.802  1701  4042 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 19:01:34.802  1701  4042 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 19:01:34.804  3914  3914 D SprintDMHelper: simOperator: 
,09-08 19:01:34.805  3914  3914 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 19:01:34.811  1701  4042 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 19:01:34.875  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:34.877  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:34.892  4028  4028 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-08 19:01:34.899  4028  4028 I BooksApp: Created application version: 3.6.9 (30609)
,09-08 19:01:34.935  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 19:01:34.935  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 19:01:34.935  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:34.935  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:34.940  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 19:01:34.940  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
09-08 19:01:34.940  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:34.940  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:34.960  3009  4044 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 19:01:34.960  3009  4044 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at blb.a(PG:3937)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at czp.a(PG:18188)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:01:34.960  3009  4044 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	... 12 more
09-08 19:01:34.960  3009  4044 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at fal.a(PG:38)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:01:34.960  3009  4044 E HttpOperation: 	... 14 more
,09-08 19:01:35.005  2244  4047 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 19:01:35.026  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:01:35.026  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:01:35.026  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:35.026  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:35.050  3009  4044 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 19:01:35.050  3009  4044 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at hec.a(PG:42)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at hee.a(PG:102)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at czr.a(PG:65)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at kka.a(PG:108)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at czp.a(PG:19176)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:01:35.050  3009  4044 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	... 15 more
09-08 19:01:35.050  3009  4044 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at fal.a(PG:38)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:01:35.050  3009  4044 E HttpOperation: 	... 17 more
09-08 19:01:35.050  3009  4044 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 19:01:35.050  3009  4044 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at hec.a(PG:42)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at hee.a(PG:102)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at czr.a(PG:65)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at kka.a(PG:108)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	... 15 more
09-08 19:01:35.050  3009  4044 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at fal.a(PG:38)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 19:01:35.050  3009  4044 E ExperimentLoader: 	... 17 more
,09-08 19:01:35.060  1701  4042 E MDM     : [172] SitrepService.a: Error sending sitrep.
,09-08 19:01:35.177  4028  4056 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 19:01:35.228  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:35.233   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 163207, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:01:35.385  1512  4063 I VacuumService: Vacuum at: now=1473354095385 tag=VacuumService
,09-08 19:01:35.517  1512  4064 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 19:01:35.529  1512  4064 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 19:01:35.601  1512  4064 W Uploader:  no longer exists, so no auth token.
,09-08 19:01:35.635   874  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 19:01:35.695  4028  4072 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 19:01:35.741  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 19:01:35.742  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 19:01:35.742  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:35.742  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:35.776  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 19:01:35.776  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 19:01:35.776  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:35.776  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:35.789  4028  4072 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 19:01:35.791  4028  4056 E BooksSync: Soft error
09-08 19:01:35.791  4028  4056 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:01:35.791  4028  4056 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:01:35.791  4028  4056 E BooksSync: Sync error
09-08 19:01:35.791  4028  4056 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:01:35.791  4028  4056 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:01:35.791  4028  4056 I BooksSync: Finished books sync
,09-08 19:01:35.801   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162919, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:01:35.842  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:35.869  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 19:01:35.870  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 19:01:35.870  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:35.873  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:35.894  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 19:01:35.894  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 19:01:35.894  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-08 19:01:35.903   874  2290 I ActivityManager: Killing 3457:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 19:01:36.966  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 19:01:36.967  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-08 19:01:36.967  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:01:36.967  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:36.982  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 19:01:36.982  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 19:01:36.982  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 19:01:37.568  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 19:01:37.568  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-08 19:01:37.569  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:01:37.569  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:37.590  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 19:01:37.590  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 19:01:37.590  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 19:01:37.765  1512  4064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 19:01:37.766  1512  4064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 19:01:37.766  1512  4064 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:01:37.766  1512  4064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:37.786  1512  4064 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 19:01:37.786  1512  4064 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 19:01:37.786  1512  4064 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 19:01:38.336   874  1695 D WifiService: setWifiEnabled: false pid=3758, uid=10000
,09-08 19:01:38.336   874  1695 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 19:01:38.368  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 19:01:38.371   874  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 19:01:38.372   874  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 19:01:38.372   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 19:01:38.372   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 19:01:38.409   874  1311 E native  : do suspend true
,09-08 19:01:38.420   874  1863 D DhcpClient: Clearing IP address
,09-08 19:01:38.421   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 19:01:38.427   373   872 D CommandListener: Setting iface cfg
,09-08 19:01:38.430   874  4015 D DhcpClient: Receive thread stopped
,09-08 19:01:38.434   396   396 E Parcel  : Reading a NULL string not supported here.
,09-08 19:01:38.434  1512  4054 V NativeCrypto: Read error: ssl=0x9aeb2a00: I/O error during system call, Connection timed out
,09-08 19:01:38.434   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 19:01:38.435   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 19:01:38.436  1512  4054 V NativeCrypto: SSL shutdown failed: ssl=0x9aeb2a00: I/O error during system call, Broken pipe
,09-08 19:01:38.437   874  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-08 19:01:38.441   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 19:01:38.441   874  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 19:01:38.441   874  1311 E native  : do suspend true
,09-08 19:01:38.488   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:38.516   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:01:38.517   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 19:01:38.518   874  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 19:01:38.518   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:38.520   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 19:01:38.524  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.524  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:38.525  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:38.525  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:38.526  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.526  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:38.526  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.526  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:38.543   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 19:01:38.543  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 19:01:38.543  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.543  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:38.544  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.544  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:38.550  1701  1701 D SystemUpdateService: onCreate
,09-08 19:01:38.554  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 19:01:38.561   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:01:38.563  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.563  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:38.564  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:38.564  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:38.564  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.564  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 19:01:38.564  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:38.565  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:38.565  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:38.565  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:38.565  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:38.565  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:38.567   874  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 19:01:38.568  1900  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 19:01:38.569  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 19:01:38.571  1701  2415 I iu.UploadsManager: num queued entries: 0
09-08 19:01:38.572  1701  2415 I iu.UploadsManager: num updated entries: 0
,09-08 19:01:38.576  1701  2415 I iu.SyncManager: NEXT; no task
,09-08 19:01:38.577  1701  4086 I SystemUpdateService: active receiver: enabled
,09-08 19:01:38.580  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 19:01:38.580  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 19:01:38.582  3914  3914 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:01:38.585  1701  4086 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 19:01:38.586  3914  3914 D SprintDMHelper: simOperator: 
,09-08 19:01:38.586  3914  3914 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 19:01:38.598  1701  4086 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 19:01:38.598  1701  4086 I SystemUpdateService: now status is 0 (complete)
,09-08 19:01:38.601   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 19:01:38.602   874  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 19:01:38.598  1701  4086 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 19:01:38.611  1701  4086 I SystemUpdateService: file has been verified
,09-08 19:01:38.611  1701  4086 I SystemUpdateService: OTA package size = 12249756
,09-08 19:01:38.616  2244  4091 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 19:01:38.628  1701  4086 I SystemUpdateService: showing system update notification
,09-08 19:01:38.637  1701  1701 D SystemUpdateService: onDestroy
,09-08 19:01:39.919  4028  4052 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-08 19:01:42.553   874  1313 D ConnectivityService: handlePromptUnvalidated 101
,09-08 19:01:43.393   874   891 I ActivityManager: Start proc 4098:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 19:01:43.516  4098  4098 D AdapterServiceConfig: Adding HeadsetService
,09-08 19:01:43.517  4098  4098 D AdapterServiceConfig: Adding A2dpService
09-08 19:01:43.517  4098  4098 D AdapterServiceConfig: Adding HidService
09-08 19:01:43.518  4098  4098 D AdapterServiceConfig: Adding HealthService
,09-08 19:01:43.519  4098  4098 D AdapterServiceConfig: Adding PanService
09-08 19:01:43.519  4098  4098 D AdapterServiceConfig: Adding GattService
,09-08 19:01:43.520  4098  4098 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 19:01:43.551   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@68b17db:true
,09-08 19:01:43.551  4098  4098 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 19:01:43.558  4098  4098 I bt_bluedroid: init
,09-08 19:01:43.559  4098  4110 I BluetoothAdapterState: Entering OffState
,09-08 19:01:43.564  4098  4111 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 19:01:43.565  4098  4111 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 19:01:43.565  4098  4111 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 19:01:43.565  4098  4111 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 19:01:43.567  4098  4098 I bt_bluedroid: get_profile_interface socket
,09-08 19:01:43.570  4098  4114 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 19:01:43.571  4098  4098 I bt_bluedroid: get_profile_interface sdp
,09-08 19:01:43.572  4098  4114 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 19:01:43.579  4098  4109 I bt_bluedroid: config_hci_snoop_log
09-08 19:01:43.581   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 19:01:43.591  4098  4110 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 19:01:43.592  4098  4110 D BluetoothAdapterProperties: Setting state to 14
,09-08 19:01:43.592  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 19:01:43.599  4098  4110 D BluetoothBondStateMachine: make
,09-08 19:01:43.605  4098  4115 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 19:01:43.615  4098  4110 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:43.619  4098  4098 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 19:01:43.628  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:01:43.632  4098  4098 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 19:01:43.634  4098  4098 D BtGatt.GattService: Received start request. Starting profile...
09-08 19:01:43.634  4098  4098 D BtGatt.GattService: start()
09-08 19:01:43.635  4098  4098 I bt_bluedroid: get_profile_interface gatt
,09-08 19:01:43.637  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:01:43.638  4098  4098 D BtGatt.AdvertiseManager: advertise manager created
,09-08 19:01:43.651  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:43.651  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:43.651  4098  4098 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 19:01:43.651  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:43.652  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 19:01:43.653  4098  4110 I bt_bluedroid: enable
09-08 19:01:43.653  4098  4111 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 19:01:43.654  4098  4111 I bt_hci  : start_up
,09-08 19:01:43.674  4098  4111 I bt_vendor: alloc value 0xb39be189
09-08 19:01:43.674  4098  4111 I bt_vendor: init
09-08 19:01:43.674  4098  4111 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 19:01:43.675  4098  4111 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 19:01:43.782  4098  4111 D bt_hci  : start_up starting async portion
,09-08 19:01:43.783  4098  4118 I bt_hci  : event_finish_startup
09-08 19:01:43.783  4098  4118 I bt_hci_h4: hal_open
,09-08 19:01:43.784  4098  4118 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 19:01:43.794  4098  4118 I bt_userial_vendor: device fd = 51 open
,09-08 19:01:43.824  4098  4118 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 19:01:43.856  4098  4118 D bt_hwcfg: Chipset BCM4354A2
09-08 19:01:43.857  4098  4118 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 19:01:43.858  4098  4118 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 19:01:44.519  4098  4118 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 19:01:44.521  4098  4118 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 19:01:44.521  4098  4118 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 19:01:44.638  4098  4118 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 19:01:44.639  4098  4118 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 19:01:44.668  4098  4118 I bt_hwcfg: vendor lib fwcfg completed
,09-08 19:01:44.669  4098  4118 I bt_vendor: firmware callback
09-08 19:01:44.669  4098  4118 I bt_hci  : firmware_config_callback
,09-08 19:01:44.680  4098  4120 I bt_btu  : btu_task pending for preload complete event
09-08 19:01:44.681  4098  4120 I bt_btu_task: Bluetooth chip preload is complete
,09-08 19:01:44.681  4098  4120 I bt_btu  : btu_task received preload complete event
,09-08 19:01:44.691  4098  4120 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 19:01:44.691  4098  4120 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 19:01:44.692  4098  4120 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 19:01:44.692  4098  4120 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 19:01:44.692  4098  4120 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 19:01:44.692  4098  4120 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 19:01:44.693  4098  4120 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 19:01:44.693  4098  4120 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 19:01:44.693  4098  4120 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 19:01:44.694  4098  4120 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 19:01:44.694  4098  4120 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 19:01:44.694  4098  4120 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 19:01:44.694  4098  4120 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 19:01:44.695  4098  4120 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 19:01:44.695  4098  4120 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 19:01:44.828  4098  4120 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393bd9d
,09-08 19:01:44.828  4098  4120 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393bd9d 
,09-08 19:01:44.840  4098  4114 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 19:01:44.842  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 19:01:44.842  4098  4114 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-08 19:01:44.845  4098  4114 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 19:01:44.849  4098  4114 D BluetoothAdapterProperties: Scan Mode:20
,09-08 19:01:44.849  4098  4114 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 19:01:44.849  4098  4114 D bt_hci  : do_postload posting postload work item
,09-08 19:01:44.850  4098  4118 I bt_hci  : event_postload
,09-08 19:01:44.850  4098  4118 I bt_vendor: sco_config_cb,
09-08 19:01:44.850  4098  4118 I bt_hci  : sco_config_callback postload finished.
,09-08 19:01:44.853  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.854  4098  4114 D bt_bte_conf: Device ID record 1 : primary
09-08 19:01:44.854  4098  4114 D bt_bte_conf:   vendorId            = 000f
09-08 19:01:44.854  4098  4114 D bt_bte_conf:   vendorIdSource      = 0001
09-08 19:01:44.854  4098  4114 D bt_bte_conf:   product             = 1200
09-08 19:01:44.855  4098  4114 D bt_bte_conf:   version             = 1436
09-08 19:01:44.855  4098  4114 D bt_bte_conf:   clientExecutableURL = 
09-08 19:01:44.855  4098  4114 D bt_bte_conf:   serviceDescription  = 
09-08 19:01:44.855  4098  4114 D bt_bte_conf:   documentationURL    = 
09-08 19:01:44.855  4098  4114 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 19:01:44.856  4098  4111 D bt_stack_manager: event_start_up_stack finished
09-08 19:01:44.856  4098  4118 I bt_vendor: low_power_mode_cb
09-08 19:01:44.857  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.858  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 19:01:44.858  4098  4110 D BluetoothAdapterProperties: Setting state to 15
09-08 19:01:44.859  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 19:01:44.861  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.862  4098  4110 I BluetoothAdapterState: Entering BleOnState
,09-08 19:01:44.871  4098  4110 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 19:01:44.871  4098  4110 D BluetoothAdapterProperties: Setting state to 11
,09-08 19:01:44.871  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 19:01:44.883  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:01:44.886  4098  4098 D HeadsetService: Received start request. Starting profile...
,09-08 19:01:44.889  4098  4098 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 19:01:44.889  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:44.889  4098  4098 D HeadsetStateMachine: make
,09-08 19:01:44.893  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:44.896  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.904  4098  4110 I BluetoothAdapterState: Entering PendingCommandState
09-08 19:01:44.908  4098  4098 D HeadsetStateMachine: max_hf_connections = 1
09-08 19:01:44.908  4098  4098 I bt_bluedroid: get_profile_interface handsfree
,09-08 19:01:44.909  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 19:01:44.909  4098  4114 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-08 19:01:44.911  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:01:44.912  4098  4098 D A2dpService: Received start request. Starting profile...
09-08 19:01:44.912  4098  4098 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 19:01:44.913  4098  4098 I bt_bluedroid: get_profile_interface avrcp
,09-08 19:01:44.918  4098  4098 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 19:01:44.919  4098  4098 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-08 19:01:44.919  4098  4098 D A2dpStateMachine: make
,09-08 19:01:44.920  4098  4098 I bt_bluedroid: get_profile_interface a2dp
09-08 19:01:44.920  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 19:01:44.924  4098  4130 D A2dpStateMachine: Enter Disconnected: -2
,09-08 19:01:44.927  4098  4098 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 19:01:44.927  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 19:01:44.928  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:01:44.932  3832  3832 D BluetoothInputDevice: Proxy object connected
,09-08 19:01:44.932  4098  4098 D HidService: Received start request. Starting profile...
09-08 19:01:44.932  4098  4098 I bt_bluedroid: get_profile_interface hidhost
09-08 19:01:44.932  4098  4098 D HidService: setHidService(): set to: null,
09-08 19:01:44.932  3832  3832 D HidProfile: Bluetooth service connected
09-08 19:01:44.932  4098  4114 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391d3e5
09-08 19:01:44.932  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 19:01:44.933  4098  4098 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 19:01:44.933  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:01:44.934  4098  4098 D HealthService: Received start request. Starting profile...
,09-08 19:01:44.935  4098  4098 I bt_bluedroid: get_profile_interface health
,09-08 19:01:44.936  4098  4098 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-08 19:01:44.936  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:01:44.938  4098  4098 D PanService: Received start request. Starting profile...
,09-08 19:01:44.938  4098  4098 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 19:01:44.938  4098  4098 I bt_bluedroid: get_profile_interface pan
09-08 19:01:44.938  4098  4114 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 19:01:44.941  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:01:44.942  3832  3832 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 19:01:44.942  4098  4098 D BluetoothMapService: Received start request. Starting profile...
09-08 19:01:44.942  4098  4098 D BluetoothMapService: start()
09-08 19:01:44.942  3832  3832 D PanProfile: Bluetooth service connected
09-08 19:01:44.942  3832  3832 D BluetoothMap: Proxy object connected
,09-08 19:01:44.943  3832  3832 D MapProfile: Bluetooth service connected
09-08 19:01:44.943  3832  3832 D BluetoothMap: getConnectedDevices()
,09-08 19:01:44.943  3832  3832 D BluetoothMap: Bluetooth is Not enabled
09-08 19:01:44.944  4098  4098 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-08 19:01:44.944  4098  4098 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 19:01:44.944  4098  4098 D BluetoothMapAppObserver: createReceiver()
09-08 19:01:44.945  4098  4098 D BluetoothMapAppObserver: initObservers()
09-08 19:01:44.945  4098  4098 D BluetoothMapAppObserver: getEnabledAccountItems()
09-08 19:01:44.952  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.952  4098  4098 V BluetoothAdapterState: isTurningOn()=true
09-08 19:01:44.952  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.952  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:44.955  4098  4127 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 19:01:44.955  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.956  4098  4098 V BluetoothAdapterState: isTurningOn()=true
09-08 19:01:44.956  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.956  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:44.957  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.957  4098  4098 V BluetoothAdapterState: isTurningOn()=true
,09-08 19:01:44.957  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.957  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:44.958  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.958  4098  4098 V BluetoothAdapterState: isTurningOn()=true
09-08 19:01:44.958  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.958  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:44.959  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.959  4098  4098 V BluetoothAdapterState: isTurningOn()=true
09-08 19:01:44.959  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.959  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:44.960  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:44.960  4098  4098 V BluetoothAdapterState: isTurningOn()=true
09-08 19:01:44.960  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:44.960  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:44.960  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 19:01:44.961  4098  4110 D BluetoothAdapterProperties: ScanMode =  20
09-08 19:01:44.961  4098  4110 D BluetoothAdapterProperties: State =  11
,09-08 19:01:44.962  4098  4114 D BluetoothAdapterProperties: Scan Mode:21
,09-08 19:01:44.962  4098  4114 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 19:01:44.963  4098  4110 D BluetoothAdapterProperties: Setting state to 12
09-08 19:01:44.963  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 19:01:44.964  4098  4110 I BluetoothAdapterState: Entering OnState
09-08 19:01:44.964  3832  3842 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 19:01:44.965   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 19:01:44.965  1966  2113 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:44.965  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:44.966  1367  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 19:01:44.967  1367  1367 D BluetoothInputDevice: Proxy object connected
09-08 19:01:44.967  1367  1367 D HidProfile: Bluetooth service connected
09-08 19:01:44.967  3832  3844 D BluetoothPan: onBluetoothStateChange on: true
09-08 19:01:44.968  1367  2081 D BluetoothPan: onBluetoothStateChange on: true
,09-08 19:01:44.968  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:44.969  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 19:01:44.969  1367  1367 D PanProfile: Bluetooth service connected
,09-08 19:01:44.970  1367  1381 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:44.971  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:44.971   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:01:44.971  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 19:01:44.971  4098  4098 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 19:01:44.972  4098  4098 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 19:01:44.973  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:44.973   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 19:01:44.973  3832  3842 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 19:01:44.973  3832  3844 D BluetoothMap: onBluetoothStateChange: up=true
09-08 19:01:44.973   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 19:01:44.974  4098  4098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:01:44.974  1367  2081 D BluetoothMap: onBluetoothStateChange: up=true
09-08 19:01:44.975  1367  1367 D BluetoothMap: Proxy object connected
09-08 19:01:44.975  1367  1367 D MapProfile: Bluetooth service connected
09-08 19:01:44.975  1367  1367 D BluetoothMap: getConnectedDevices()
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:44.976  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:44.976  4098  4098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 19:01:44.976  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:01:44.977  4098  4098 D ObexServerSockets: Succeed to create listening sockets 
09-08 19:01:44.977  4098  4098 D ObexServerSockets0: startAccept()
09-08 19:01:44.977  4098  4098 D ObexServerSockets0: prepareForNewConnect()
09-08 19:01:44.978  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:44.978   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 19:01:44.979  4098  4098 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 19:01:44.979  4098  4098 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 19:01:44.980  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:44.981   874   874 D BluetoothA2dp: Proxy object connected
09-08 19:01:44.981  4098  4137 D ObexServerSockets0: Accepting socket connection...
09-08 19:01:44.981  4098  4098 D BluetoothMapService: onReceive
09-08 19:01:44.981  4098  4098 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 19:01:44.981  4098  4098 D BluetoothMapService: STATE_ON
09-08 19:01:44.982  1367  1367 D BluetoothA2dp: Proxy object connected
09-08 19:01:44.982  4098  4136 D ObexServerSockets0: Accepting socket connection...
09-08 19:01:44.982  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.983  3832  3832 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 19:01:44.983  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:44.987  3832  3832 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 19:01:44.991  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 19:01:44.993  3832  3832 D BluetoothA2dp: Proxy object connected
,09-08 19:01:44.996  3507  3552 D Finsky  : [290] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-08 19:01:44.998  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:01:45.005  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,09-08 19:01:45.006  3832  3832 D BluetoothPbap: Proxy object connected
09-08 19:01:45.007  3832  3832 D PbapServerProfile: Bluetooth service connected
09-08 19:01:45.007  4098  4098 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 19:01:45.007  4098  4098 D ObexServerSockets0: prepareForNewConnect()
,09-08 19:01:45.010  1367  1367 D BluetoothPbap: Proxy object connected
,09-08 19:01:45.010  1367  1367 D PbapServerProfile: Bluetooth service connected
09-08 19:01:45.014  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:45.014  4098  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:01:45.019  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:45.021  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:01:45.033  4098  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:01:45.034  4098  4148 I BtOppRfcommListener: Accept thread started.
,09-08 19:01:45.040  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 19:01:45.040  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 19:01:45.040  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:01:45.040  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:01:45.053  3507  3552 D Finsky  : [290] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-08 19:01:45.067  1367  2081 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.067   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:01:45.067   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:01:45.067  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-08 19:01:45.067   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:01:45.068  1966  1984 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.070   874   891 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.072   874   891 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.077  1367  1379 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.077  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-08 19:01:45.089  3832  3842 D BluetoothHeadset: Proxy object connected
,09-08 19:01:45.090  3832  3832 D HeadsetProfile: Bluetooth service connected
,09-08 19:01:48.356  4098  4110 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 19:01:48.356  4098  4110 D BluetoothAdapterProperties: Setting state to 13
,09-08 19:01:48.356  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 19:01:48.358  4098  4110 D BluetoothAdapterProperties: onBluetoothDisable(),
09-08 19:01:48.360  4098  4110 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:48.366  4098  4114 D BluetoothAdapterProperties: Scan Mode:20
,09-08 19:01:48.367  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 19:01:48.372  4098  4098 D BluetoothMapService: onReceive
,09-08 19:01:48.373  4098  4098 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 19:01:48.373  4098  4098 D BluetoothMapService: STATE_TURNING_OFF
,09-08 19:01:48.374  4098  4098 D BluetoothMapService: MAP Service closeService in
09-08 19:01:48.374  4098  4098 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 19:01:48.374  4098  4098 D ObexServerSockets0: shutdown(block = true)
09-08 19:01:48.375  4098  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 19:01:48.376  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:48.376  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:48.377  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:48.377  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:01:48.378  4098  4098 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 19:01:48.378  4098  4123 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 19:01:48.378  4098  4137 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 19:01:48.379  4098  4098 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 19:01:48.379  4098  4098 I BtOppRfcommListener: stopping Accept Thread
09-08 19:01:48.380  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:48.380  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:01:48.380  4098  4148 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 19:01:48.381  4098  4148 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 19:01:48.381  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 19:01:48.381  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:48.385  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:01:48.385  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 19:01:48.386  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 19:01:48.386  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:01:48.388  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 19:01:48.389  4098  4098 D HeadsetService: Received stop request...Stopping profile...
09-08 19:01:48.392  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:48.394  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:48.396  1367  1381 D BluetoothHeadset: Proxy object disconnected
,09-08 19:01:48.397  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-08 19:01:48.397  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:48.397   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:48.397   874   874 D BluetoothHeadset: Proxy object disconnected
,09-08 19:01:48.397   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:48.398  1966  1977 D BluetoothHeadset: Proxy object disconnected
09-08 19:01:48.399  3832  3842 D BluetoothHeadset: Proxy object disconnected
,09-08 19:01:48.400  4098  4098 D A2dpService: Received stop request...Stopping profile...
,09-08 19:01:48.400  4098  4130 D A2dpStateMachine: Exit Disconnected: -1
09-08 19:01:48.401  3832  3832 D DockEventReceiver: finishStartingService: stopping service
09-08 19:01:48.403  3832  3832 D HeadsetProfile: Bluetooth service disconnected
09-08 19:01:48.403  1367  1367 D BluetoothA2dp: Proxy object disconnected
09-08 19:01:48.403   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 19:01:48.404  4098  4098 D HidService: Received stop request...Stopping profile...
09-08 19:01:48.404  4098  4098 D HidService: Stopping Bluetooth HidService
,09-08 19:01:48.407  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-08 19:01:48.407  1367  1367 D HidProfile: Bluetooth service disconnected
09-08 19:01:48.408  3832  3832 D BluetoothA2dp: Proxy object disconnected
09-08 19:01:48.409  4098  4098 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:48.409  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.409  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.409  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:48.410  4098  4098 D HealthService: Received stop request...Stopping profile...
,09-08 19:01:48.412  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:01:48.415  3832  3832 D BluetoothInputDevice: Proxy object disconnected
,09-08 19:01:48.415  3832  3832 D HidProfile: Bluetooth service disconnected
09-08 19:01:48.415  4098  4098 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 19:01:48.415  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-08 19:01:48.415  4098  4098 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 19:01:48.416  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:48.416  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:48.416  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:48.416  4098  4114 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 19:01:48.416  4098  4098 D PanService: Received stop request...Stopping profile...
,09-08 19:01:48.418  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 19:01:48.418  1367  1367 D PanProfile: Bluetooth service disconnected
09-08 19:01:48.419  4098  4098 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 19:01:48.419  4098  4098 D BluetoothMapService: stop()
09-08 19:01:48.419  3832  3832 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 19:01:48.419  3832  3832 D PanProfile: Bluetooth service disconnected
09-08 19:01:48.419  4098  4098 D BluetoothMapAppObserver: deinitObservers()
09-08 19:01:48.419  4098  4098 D BluetoothMapAppObserver: removeReceiver()
,09-08 19:01:48.421  1367  1367 D BluetoothMap: Proxy object disconnected
09-08 19:01:48.421  1367  1367 D MapProfile: Bluetooth service disconnected
,09-08 19:01:48.421  3832  3832 D BluetoothMap: Proxy object disconnected
09-08 19:01:48.421  4098  4098 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:48.421  4098  4098 V BluetoothAdapterState: isTurningOn()=false
,09-08 19:01:48.421  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.421  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:48.421  3832  3832 D MapProfile: Bluetooth service disconnected
,09-08 19:01:48.423  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 19:01:48.423  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:48.423  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 19:01:48.423  4098  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 19:01:48.423  4098  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 19:01:48.423  4098  4120 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 19:01:48.423  4098  4120 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 19:01:48.423  4098  4098 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:48.423  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.423  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.424  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:48.424  4098  4098 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 19:01:48.424  4098  4114 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 19:01:48.424  4098  4098 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-08 19:01:48.428  1367  1367 D BluetoothPbap: Proxy object disconnected
,09-08 19:01:48.428  1367  1367 D PbapServerProfile: Bluetooth service disconnected
09-08 19:01:48.428  3832  3832 D BluetoothPbap: Proxy object disconnected
09-08 19:01:48.428  4098  4098 V BluetoothAdapterState: isTurningOff()=true
,09-08 19:01:48.428  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.428  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.428  3832  3832 D PbapServerProfile: Bluetooth service disconnected
,09-08 19:01:48.428  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:48.428  4098  4098 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 19:01:48.428  4098  4114 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 19:01:48.429  4098  4098 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 19:01:48.429  4098  4098 V BluetoothAdapterState: isTurningOff()=true
09-08 19:01:48.429  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.429  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.429  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:48.430  4098  4098 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 19:01:48.430  4098  4098 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 19:01:48.430  4098  4098 D BluetoothMapService: MAP Service closeService in
09-08 19:01:48.431  4098  4098 V BluetoothAdapterState: isTurningOff()=true
,09-08 19:01:48.431  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.431  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.431  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:01:48.431  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-08 19:01:48.431  4098  4110 D BluetoothAdapterProperties: Setting state to 15
09-08 19:01:48.431  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 19:01:48.432  4098  4110 I BluetoothAdapterState: Entering BleOnState
09-08 19:01:48.432  4098  4098 D BluetoothMapService: cleanup()
09-08 19:01:48.432  4098  4098 D BluetoothMapService: MAP Service closeService in
09-08 19:01:48.433  3832  3844 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 19:01:48.433   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 19:01:48.434  1966  2152 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:48.434  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 19:01:48.436  3832  3842 D BluetoothPan: onBluetoothStateChange on: false
,09-08 19:01:48.437  1367  1381 D BluetoothPan: onBluetoothStateChange on: false
,09-08 19:01:48.438  1367  2081 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 19:01:48.438   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:48.438  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 19:01:48.439  3832  3844 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:48.439   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 19:01:48.439  3832  3842 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 19:01:48.440  3832  3844 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 19:01:48.441  3832  3842 D BluetoothMap: onBluetoothStateChange: up=false
09-08 19:01:48.441   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 19:01:48.442  1367  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-08 19:01:48.442  1367  2081 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 19:01:48.442  4098  4110 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 19:01:48.443  4098  4110 D BluetoothAdapterProperties: Setting state to 16
09-08 19:01:48.443  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 19:01:48.443  4098  4110 D BluetoothAdapterProperties: onBleDisable
,09-08 19:01:48.443  4098  4110 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:48.444  4098  4111 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 19:01:48.445  4098  4120 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 19:01:48.445  4098  4120 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 19:01:48.448  4098  4114 D BluetoothAdapterProperties: Scan Mode:20
,09-08 19:01:48.448  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:48.450  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:48.450  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 19:01:48.451  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:48.452  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:48.453  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:01:48.455  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:48.455  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:01:48.459  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,09-08 19:01:48.650  4098  4114 I bt_hci  : shut_down
,09-08 19:01:48.650  4098  4118 D bt_hwcfg: hw_epilog_process
09-08 19:01:48.652  4098  4118 I bt_vendor: low_power_mode_cb
,09-08 19:01:48.674  4098  4118 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 19:01:48.674  4098  4118 I bt_vendor: epilog_cb
,09-08 19:01:48.675  4098  4118 I bt_hci  : epilog_finished_callback
,09-08 19:01:48.685  4098  4114 I bt_hci_h4: hal_close
,09-08 19:01:48.687  4098  4114 I bt_userial_vendor: device fd = 51 close
,09-08 19:01:48.815  4098  4111 D bt_stack_manager: event_shut_down_stack finished.
,09-08 19:01:48.816  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 19:01:48.822  4098  4110 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 19:01:48.823  4098  4098 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 19:01:48.824  4098  4098 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 19:01:48.825  4098  4098 D BtGatt.GattService: stop()
09-08 19:01:48.825  4098  4098 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 19:01:48.831  4098  4098 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:48.831  4098  4098 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:48.831  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:01:48.832  4098  4098 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 19:01:48.832  4098  4110 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 19:01:48.833  4098  4110 D BluetoothAdapterProperties: Setting state to 10
,09-08 19:01:48.833  4098  4110 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 19:01:48.835  4098  4110 I BluetoothAdapterState: Entering OffState
,09-08 19:01:48.836   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 19:01:48.866  4098  4098 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 19:01:48.867  4098  4098 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 19:01:48.867  4098  4111 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 19:01:48.876  4098  4111 D bt_stack_manager: event_clean_up_stack finished.
,09-08 19:01:48.876  4098  4098 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 19:01:48.881  4098  4098 I art     : System.exit called, status: 0
,09-08 19:01:48.881  4098  4098 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 19:01:48.965   874  1695 I ActivityManager: Process com.android.bluetooth (pid 4098) has died
,09-08 19:01:53.352  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:53.352  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:53.357  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:01:53.358  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@804682a removed from the list
,09-08 19:01:53.358  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:53.358  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:01:53.358  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:01:53.361  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:01:53.362  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e813b8 added. We now have 4 listener(s)
,09-08 19:01:53.362  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:01:53.364  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:01:53.364  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e813b8 removed from the list
,09-08 19:01:53.364  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:01:53.365  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:01:53.365  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:01:53.367  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 19:01:53.368  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b22a591 added. We now have 4 listener(s)
,09-08 19:01:53.368  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:01:58.381  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:01:58.433   874   891 I ActivityManager: Start proc 4159:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 19:01:58.603  4159  4159 D AdapterServiceConfig: Adding HeadsetService
,09-08 19:01:58.604  4159  4159 D AdapterServiceConfig: Adding A2dpService
,09-08 19:01:58.606  4159  4159 D AdapterServiceConfig: Adding HidService
,09-08 19:01:58.608  4159  4159 D AdapterServiceConfig: Adding HealthService
09-08 19:01:58.608  4159  4159 D AdapterServiceConfig: Adding PanService
09-08 19:01:58.609  4159  4159 D AdapterServiceConfig: Adding GattService
09-08 19:01:58.609  4159  4159 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 19:01:58.637   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c3b9d8b:true
09-08 19:01:58.637  4159  4159 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 19:01:58.643  4159  4159 I bt_bluedroid: init
,09-08 19:01:58.643  4159  4171 I BluetoothAdapterState: Entering OffState
,09-08 19:01:58.651  4159  4172 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 19:01:58.651  4159  4172 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 19:01:58.651  4159  4172 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 19:01:58.652  4159  4172 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 19:01:58.656  4159  4159 I bt_bluedroid: get_profile_interface socket
,09-08 19:01:58.659  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 19:01:58.659  4159  4159 I bt_bluedroid: get_profile_interface sdp
,09-08 19:01:58.660  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 19:01:58.668  4159  4170 I bt_bluedroid: config_hci_snoop_log
,09-08 19:01:58.672   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 19:01:58.687  4159  4171 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 19:01:58.688  4159  4171 D BluetoothAdapterProperties: Setting state to 14
,09-08 19:01:58.688  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 19:01:58.694  4159  4171 D BluetoothBondStateMachine: make
,09-08 19:01:58.700  4159  4176 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 19:01:58.708  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,09-08 19:01:58.713  4159  4159 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 19:01:58.723  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:01:58.725  4159  4159 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 19:01:58.727  4159  4159 D BtGatt.GattService: Received start request. Starting profile...
,09-08 19:01:58.727  4159  4159 D BtGatt.GattService: start()
,09-08 19:01:58.728  4159  4159 I bt_bluedroid: get_profile_interface gatt
,09-08 19:01:58.730  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:01:58.731  4159  4159 D BtGatt.AdvertiseManager: advertise manager created
,09-08 19:01:58.741  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:01:58.742  4159  4159 V BluetoothAdapterState: isTurningOn()=false
09-08 19:01:58.742  4159  4159 V BluetoothAdapterState: isBleTurningOn()=true
09-08 19:01:58.742  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:01:58.742  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 19:01:58.743  4159  4171 I bt_bluedroid: enable
09-08 19:01:58.744  4159  4172 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 19:01:58.746  4159  4172 I bt_hci  : start_up
,09-08 19:01:58.768  4159  4172 I bt_vendor: alloc value 0xb39be189
,09-08 19:01:58.768  4159  4172 I bt_vendor: init
09-08 19:01:58.768  4159  4172 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 19:01:58.768  4159  4172 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 19:01:58.876  4159  4172 D bt_hci  : start_up starting async portion
,09-08 19:01:58.877  4159  4179 I bt_hci  : event_finish_startup
,09-08 19:01:58.877  4159  4179 I bt_hci_h4: hal_open
09-08 19:01:58.878  4159  4179 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 19:01:58.885  4159  4179 I bt_userial_vendor: device fd = 51 open
,09-08 19:01:58.919  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 19:01:58.950  4159  4179 D bt_hwcfg: Chipset BCM4354A2
,09-08 19:01:58.951  4159  4179 D bt_hwcfg: Target name = [BCM4354A2]
09-08 19:01:58.952  4159  4179 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 19:01:59.688  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 19:01:59.689  4159  4179 D bt_hwcfg: Settlement delay -- 100 ms
09-08 19:01:59.689  4159  4179 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 19:01:59.806  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 19:01:59.807  4159  4179 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 19:01:59.837  4159  4179 I bt_hwcfg: vendor lib fwcfg completed
,09-08 19:01:59.837  4159  4179 I bt_vendor: firmware callback
09-08 19:01:59.838  4159  4179 I bt_hci  : firmware_config_callback
,09-08 19:01:59.849  4159  4181 I bt_btu  : btu_task pending for preload complete event
,09-08 19:01:59.849  4159  4181 I bt_btu_task: Bluetooth chip preload is complete
09-08 19:01:59.849  4159  4181 I bt_btu  : btu_task received preload complete event
,09-08 19:01:59.859  4159  4181 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 19:01:59.859  4159  4181 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 19:01:59.859  4159  4181 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 19:01:59.860  4159  4181 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 19:01:59.860  4159  4181 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 19:01:59.860  4159  4181 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 19:01:59.861  4159  4181 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 19:01:59.861  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 19:01:59.861  4159  4181 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 19:01:59.862  4159  4181 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 19:01:59.862  4159  4181 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 19:01:59.862  4159  4181 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 19:01:59.863  4159  4181 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 19:01:59.863  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 19:01:59.863  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 19:01:59.998  4159  4181 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393bd9d
,09-08 19:01:59.999  4159  4181 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393bd9d ,
,09-08 19:02:00.011  4159  4175 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 19:02:00.012  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 19:02:00.013  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 19:02:00.018  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 19:02:00.023  4159  4175 D BluetoothAdapterProperties: Scan Mode:20
,09-08 19:02:00.023  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 19:02:00.024  4159  4175 D bt_hci  : do_postload posting postload work item
,09-08 19:02:00.024  4159  4179 I bt_hci  : event_postload
,09-08 19:02:00.025  4159  4179 I bt_vendor: sco_config_cb
,09-08 19:02:00.025  4159  4179 I bt_hci  : sco_config_callback postload finished.
,09-08 19:02:00.028  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:00.029  4159  4175 D bt_bte_conf: Device ID record 1 : primary
09-08 19:02:00.029  4159  4175 D bt_bte_conf:   vendorId            = 000f
09-08 19:02:00.029  4159  4175 D bt_bte_conf:   vendorIdSource      = 0001
09-08 19:02:00.029  4159  4175 D bt_bte_conf:   product             = 1200
09-08 19:02:00.029  4159  4175 D bt_bte_conf:   version             = 1436
09-08 19:02:00.030  4159  4175 D bt_bte_conf:   clientExecutableURL = 
,09-08 19:02:00.030  4159  4175 D bt_bte_conf:   serviceDescription  = 
09-08 19:02:00.030  4159  4175 D bt_bte_conf:   documentationURL    = 
09-08 19:02:00.031  4159  4175 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 19:02:00.031  4159  4172 D bt_stack_manager: event_start_up_stack finished
09-08 19:02:00.033  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 19:02:00.034  4159  4171 D BluetoothAdapterProperties: Setting state to 15
09-08 19:02:00.034  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 19:02:00.034  4159  4179 I bt_vendor: low_power_mode_cb
09-08 19:02:00.034  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:00.035  4159  4171 I BluetoothAdapterState: Entering BleOnState
09-08 19:02:00.042  4159  4171 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 19:02:00.042  4159  4171 D BluetoothAdapterProperties: Setting state to 11
09-08 19:02:00.042  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 19:02:00.049  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:02:00.050  4159  4159 D HeadsetService: Received start request. Starting profile...
,09-08 19:02:00.053  4159  4159 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 19:02:00.053  4159  4159 D HeadsetStateMachine: make
09-08 19:02:00.063  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
09-08 19:02:00.063  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:00.066  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:00.068  4159  4159 D HeadsetStateMachine: max_hf_connections = 1
09-08 19:02:00.068  4159  4159 I bt_bluedroid: get_profile_interface handsfree
09-08 19:02:00.068  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 19:02:00.069  4159  4175 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-08 19:02:00.071  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
09-08 19:02:00.072  4159  4159 D A2dpService: Received start request. Starting profile...
,09-08 19:02:00.073  4159  4159 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 19:02:00.073  4159  4159 I bt_bluedroid: get_profile_interface avrcp
,09-08 19:02:00.081  4159  4159 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 19:02:00.081  4159  4159 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 19:02:00.082  4159  4159 D A2dpStateMachine: make
,09-08 19:02:00.084  4159  4159 I bt_bluedroid: get_profile_interface a2dp
,09-08 19:02:00.085  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 19:02:00.087  4159  4159 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 19:02:00.088  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6,
09-08 19:02:00.088  4159  4190 D A2dpStateMachine: Enter Disconnected: -2
,09-08 19:02:00.088  4159  4159 D HidService: Received start request. Starting profile...
,09-08 19:02:00.089  4159  4159 I bt_bluedroid: get_profile_interface hidhost
09-08 19:02:00.089  4159  4159 D HidService: setHidService(): set to: null
,09-08 19:02:00.089  4159  4175 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391d3e5
09-08 19:02:00.089  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 19:02:00.090  4159  4159 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 19:02:00.091  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:02:00.092  4159  4159 D HealthService: Received start request. Starting profile...
,09-08 19:02:00.094  4159  4159 I bt_bluedroid: get_profile_interface health
,09-08 19:02:00.096  4159  4159 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 19:02:00.098  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:02:00.099  4159  4159 D PanService: Received start request. Starting profile...
09-08 19:02:00.099  4159  4159 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 19:02:00.100  4159  4159 I bt_bluedroid: get_profile_interface pan
,09-08 19:02:00.101  4159  4175 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 19:02:00.106  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:02:00.107  4159  4159 D BluetoothMapService: Received start request. Starting profile...
09-08 19:02:00.107  4159  4159 D BluetoothMapService: start()
,09-08 19:02:00.110  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 19:02:00.111  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 19:02:00.111  4159  4159 D BluetoothMapAppObserver: createReceiver()
09-08 19:02:00.112  4159  4159 D BluetoothMapAppObserver: initObservers()
09-08 19:02:00.112  4159  4159 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 19:02:00.119  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:02:00.120  4159  4159 V BluetoothAdapterState: isTurningOn()=true
09-08 19:02:00.120  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:02:00.120  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:02:00.120  4159  4187 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 19:02:00.121  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOff()=false
,09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:02:00.122  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isTurningOn()=true
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isTurningOff()=false
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isTurningOn()=true,
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
09-08 19:02:00.123  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
09-08 19:02:00.124  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 19:02:00.124  4159  4171 D BluetoothAdapterProperties: ScanMode =  20
09-08 19:02:00.124  4159  4171 D BluetoothAdapterProperties: State =  11
09-08 19:02:00.124  4159  4171 D BluetoothAdapterProperties: Setting state to 12
09-08 19:02:00.125  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 19:02:00.125  4159  4171 I BluetoothAdapterState: Entering OnState
09-08 19:02:00.125  3832  3842 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 19:02:00.129  4159  4175 D BluetoothAdapterProperties: Scan Mode:21
09-08 19:02:00.129  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 19:02:00.130   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:02:00.130  1966  1984 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:02:00.131  1367  2081 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:02:00.133  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:02:00.135  3832  3844 D BluetoothPan: onBluetoothStateChange on: true
,09-08 19:02:00.135  1367  1367 D BluetoothInputDevice: Proxy object connected
09-08 19:02:00.135  1367  1367 D HidProfile: Bluetooth service connected
09-08 19:02:00.136  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:02:00.138  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 19:02:00.139  4159  4159 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 19:02:00.139  1367  1379 D BluetoothPan: onBluetoothStateChange on: true
,09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:02:00.141  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:02:00.141  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:02:00.144  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:02:00.144  1367  2081 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 19:02:00.144  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:02:00.146  4159  4159 D ObexServerSockets: Succeed to create listening sockets 
09-08 19:02:00.146  4159  4159 D ObexServerSockets0: startAccept()
,09-08 19:02:00.146  4159  4159 D ObexServerSockets0: prepareForNewConnect()
09-08 19:02:00.146   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 19:02:00.146  1367  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 19:02:00.148  4159  4159 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 19:02:00.148  4159  4159 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 19:02:00.149  3832  3842 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:02:00.149  4159  4196 D ObexServerSockets0: Accepting socket connection...
09-08 19:02:00.150  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 19:02:00.150  1367  1367 D PanProfile: Bluetooth service connected
09-08 19:02:00.151   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 19:02:00.151  3832  3832 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 19:02:00.151  3832  3844 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 19:02:00.151  3832  3832 D PanProfile: Bluetooth service connected
09-08 19:02:00.151  1367  1367 D BluetoothA2dp: Proxy object connected
09-08 19:02:00.151  4159  4197 D ObexServerSockets0: Accepting socket connection...
,09-08 19:02:00.154  3832  3842 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 19:02:00.156  3832  3844 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 19:02:00.155  3832  3832 D BluetoothInputDevice: Proxy object connected
,09-08 19:02:00.157  3832  3832 D HidProfile: Bluetooth service connected
,09-08 19:02:00.159   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 19:02:00.159  3832  3832 D BluetoothA2dp: Proxy object connected
,09-08 19:02:00.160   874   874 D BluetoothA2dp: Proxy object connected
,09-08 19:02:00.160  1367  1381 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 19:02:00.161  1367  1367 D BluetoothMap: Proxy object connected
09-08 19:02:00.161  1367  1367 D MapProfile: Bluetooth service connected
,09-08 19:02:00.161  1367  1367 D BluetoothMap: getConnectedDevices()
09-08 19:02:00.162  1367  2081 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 19:02:00.163   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 19:02:00.164  4159  4159 D BluetoothMapService: onReceive
09-08 19:02:00.164  4159  4159 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 19:02:00.164  4159  4159 D BluetoothMapService: STATE_ON
09-08 19:02:00.165  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:00.165  3832  3832 D BluetoothMap: Proxy object connected
09-08 19:02:00.165  3832  3832 D MapProfile: Bluetooth service connected
09-08 19:02:00.165  3832  3832 D BluetoothMap: getConnectedDevices()
09-08 19:02:00.166  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:00.172  3832  3832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 19:02:00.178  1512  1512 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 19:02:00.178  3832  3832 D DockEventReceiver: finishStartingService: stopping service
,09-08 19:02:00.185  3832  3832 D BluetoothPbap: Proxy object connected
,09-08 19:02:00.185  3832  3832 D PbapServerProfile: Bluetooth service connected
,09-08 19:02:00.189  1367  1367 D BluetoothPbap: Proxy object connected
,09-08 19:02:00.191  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 19:02:00.192  4159  4159 D ObexServerSockets0: prepareForNewConnect()
09-08 19:02:00.189  1367  1367 D PbapServerProfile: Bluetooth service connected
,09-08 19:02:00.197  4159  4204 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 19:02:00.214  4159  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 19:02:00.215  4159  4208 I BtOppRfcommListener: Accept thread started.
,09-08 19:02:00.232  1367  1381 D BluetoothHeadset: Proxy object connected
,09-08 19:02:00.232  1367  1367 D HeadsetProfile: Bluetooth service connected
09-08 19:02:00.232   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:02:00.232   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:02:00.232   874   874 D BluetoothHeadset: Proxy object connected
09-08 19:02:00.233  1966  1977 D BluetoothHeadset: Proxy object connected
,09-08 19:02:00.234  3832  3842 D BluetoothHeadset: Proxy object connected
09-08 19:02:00.234  3832  3832 D HeadsetProfile: Bluetooth service connected
,09-08 19:02:00.247   874   891 D BluetoothHeadset: Proxy object connected
,09-08 19:02:00.249  3832  3844 D BluetoothHeadset: Proxy object connected
,09-08 19:02:00.250  3832  3832 D HeadsetProfile: Bluetooth service connected
,09-08 19:02:00.251   874   891 D BluetoothHeadset: Proxy object connected
,09-08 19:02:00.263  1367  1379 D BluetoothHeadset: Proxy object connected
09-08 19:02:00.264  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:02:03.396  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 19:02:03.402  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 19:02:03.403  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 19:02:03.403  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:03.403  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b22a591 removed from the list
,09-08 19:02:03.404  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:03.404  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:03.404  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:03.406  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:02:03.406  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b58dcf6 added. We now have 4 listener(s)
09-08 19:02:03.406  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:02:03.409   874  2291 D WifiService: setWifiEnabled: false pid=3758, uid=10000
09-08 19:02:03.409   874  2291 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 19:02:03.410  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:03.413  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:03.458  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 19:02:03.458  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 19:02:03.459  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:02:03.459  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:03.511  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 19:02:03.511  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 19:02:03.512  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 19:02:08.420  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:08.422   874  1696 D WifiService: setWifiEnabled: true pid=3758, uid=10000
09-08 19:02:08.422   874  1696 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 19:02:08.433   874  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:02:08.453  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 19:02:08.459  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 19:02:08.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 19:02:08.468  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 19:02:08.469   874  1311 D WifiConfigStore: loaded 0 passpoint configs
09-08 19:02:08.470   874  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 19:02:08.470   874  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 19:02:08.471   874  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 19:02:08.472   874  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 19:02:08.472   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 19:02:08.472   874  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 19:02:08.487   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 19:02:08.487   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-08 19:02:08.488   373   872 D CommandListener: Setting iface cfg
,09-08 19:02:08.540   874  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 19:02:08.540   874  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 19:02:08.543   874  1311 E native  : do suspend true
,09-08 19:02:08.560   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:02:08.577   874  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 19:02:08.578   874  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 19:02:09.840   874  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 19:02:11.435   874  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=4.47 delta 1000 -> 1000
,09-08 19:02:11.438   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 19:02:11.438   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 19:02:11.454   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 19:02:11.491   874  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 19:02:11.492  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 19:02:11.914  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 19:02:11.957  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 19:02:11.957  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 19:02:11.962   874  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 19:02:11.970   874  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 19:02:11.970   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 19:02:11.971   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 19:02:11.988   874  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 19:02:12.002   373   872 D CommandListener: Setting iface cfg
,09-08 19:02:12.004   874  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 19:02:12.009   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 19:02:12.042   874  4218 D DhcpClient: Receive thread started
,09-08 19:02:12.135   874  1311 E native  : do suspend false
,09-08 19:02:12.159   874  1863 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 19:02:12.180   874  4218 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-08 19:02:12.181   874  1863 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-08 19:02:12.186   874  1863 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 19:02:12.199   874  4218 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 19:02:12.201   874  1863 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 19:02:12.208   373   872 D CommandListener: Setting iface cfg
,09-08 19:02:12.219   874  1863 D DhcpClient: Scheduling renewal in 86399s
,09-08 19:02:12.220   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-08 19:02:12.222   874  1311 E native  : do suspend true
,09-08 19:02:12.244   874  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 19:02:12.246   874  1311 D WifiConfigStore: No blacklist allowed without epno enabled
09-08 19:02:12.248   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 19:02:12.250   874  1313 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 19:02:12.258   874  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 19:02:12.314   874  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 19:02:12.315   874  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 19:02:12.316   874  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 19:02:12.318   874  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 19:02:12.321   874  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 19:02:12.342   874  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 19:02:12.359   874  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 19:02:12.359   874  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 19:02:12.360   874  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-08 19:02:12.360   874  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 19:02:12.360   874  1313 D ConnectivityService:    accepting network in place of null
,09-08 19:02:12.362   874  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 19:02:12.363   874  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 19:02:12.379   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=203778, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:02:12.411   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:02:12.444   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 19:02:12.453   874  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 19:02:12.454   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 19:02:12.457   874  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 19:02:12.461   874  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 19:02:12.465   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:12.482  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:12.486  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:12.491  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:12.495  1701  1701 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 19:02:12.495  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:12.498  1701  1701 D SystemUpdateService: onCreate
,09-08 19:02:12.505  1701  1701 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 19:02:12.520  1701  4227 I SystemUpdateService: active receiver: enabled
,09-08 19:02:12.522   874  4216 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 17:02:12 GMT], X-Android-Received-Millis=[1473354132522], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473354132500]}
09-08 19:02:12.523   874  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 19:02:12.523   874  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 19:02:12.523   874  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 19:02:12.525   874  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 19:02:12.527  1701  1701 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-08 19:02:12.530  1701  2415 I iu.UploadsManager: num queued entries: 0
09-08 19:02:12.530  1701  2415 I iu.UploadsManager: num updated entries: 0
,09-08 19:02:12.539  1701  1701 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 19:02:12.540  1701  4227 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 19:02:12.540  1701  1701 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 19:02:12.543  3914  3914 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 19:02:12.548  3914  3914 D SprintDMHelper: simOperator: 
,09-08 19:02:12.548  3914  3914 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 19:02:12.554  1701  4229 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 19:02:12.554  1701  4229 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 19:02:12.555  1701  4229 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 19:02:12.559  1701  4227 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 19:02:12.559  1701  4227 I SystemUpdateService: now status is 0 (complete)
,09-08 19:02:12.560  1701  4227 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 19:02:12.560  1701  2415 I iu.SyncManager: NEXT; no task
09-08 19:02:12.560  1701  4227 I SystemUpdateService: file has been verified
09-08 19:02:12.561  1701  4227 I SystemUpdateService: OTA package size = 12249756
,09-08 19:02:12.568  1701  4227 I SystemUpdateService: showing system update notification
,09-08 19:02:12.577  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:12.580  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:12.596  4028  4235 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 19:02:12.747  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:02:12.747  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:02:12.747  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:02:12.747  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:12.756  2244  4233 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,09-08 19:02:12.768  3009  4237 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 19:02:12.768  3009  4237 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at blb.a(PG:3937)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at czp.a(PG:18188)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:02:12.768  3009  4237 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	... 12 more
09-08 19:02:12.768  3009  4237 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at fal.a(PG:38)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:02:12.768  3009  4237 E HttpOperation: 	... 14 more
,09-08 19:02:12.778  4028  4241 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 19:02:12.806  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 19:02:12.806  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 19:02:12.806  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:12.806  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:12.814  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 19:02:12.814  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 19:02:12.814  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:12.814  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:12.850  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:02:12.850  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:02:12.850  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:02:12.850  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:12.868  1701  1701 D SystemUpdateService: onDestroy
,09-08 19:02:12.889  3009  4237 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 19:02:12.889  3009  4237 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at hec.a(PG:42)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at hee.a(PG:102)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at czr.a(PG:65)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at kka.a(PG:108)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at czp.a(PG:19176)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:02:12.889  3009  4237 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	... 15 more
09-08 19:02:12.889  3009  4237 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at fal.a(PG:38)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:02:12.889  3009  4237 E HttpOperation: 	... 17 more
,09-08 19:02:12.890  3009  4237 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 19:02:12.890  3009  4237 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at hec.a(PG:42)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at hee.a(PG:102)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at czr.a(PG:65)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at kka.a(PG:108)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	... 15 more
09-08 19:02:12.890  3009  4237 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at fal.a(PG:38)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 19:02:12.890  3009  4237 E ExperimentLoader: 	... 17 more
,09-08 19:02:12.916  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 19:02:12.916  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 19:02:12.916  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:02:12.916  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:12.932  4028  4241 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 19:02:12.941  4028  4235 E BooksSync: Soft error
09-08 19:02:12.941  4028  4235 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:02:12.941  4028  4235 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:02:12.941  4028  4235 E BooksSync: Sync error
09-08 19:02:12.941  4028  4235 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:02:12.941  4028  4235 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:02:12.941  4028  4235 I BooksSync: Finished books sync
,09-08 19:02:12.960   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199979, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:02:12.973  1701  4229 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-08 19:02:13.051   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 199239, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:13.446  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:13.453   874  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 19:02:13.455  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:13.457  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:13.458  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b58dcf6 removed from the list
,09-08 19:02:13.458  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:13.458  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:13.458  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:13.470  3758  4244 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 19:02:13.471  3758  4244 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 19:02:16.478  3758  4245 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 19:02:16.479  3758  4244 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 19:02:16.480  3758  4244 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 19:02:16.481  3758  4245 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 19:02:16.481  3758  4244 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 19:02:16.481  3758  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 19:02:16.482  3758  4244 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 19:02:16.483  3758  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 19:02:16.484  3758  4244 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 19:02:16.487  3758  4245 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 19:02:16.487  3758  4247 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 412, name: OutgoingSocketThread/Sender)
,09-08 19:02:16.488  3758  4248 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 413, name: IncomingSocketThread/Sender)
09-08 19:02:16.489  3758  4249 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 414, name: OutgoingSocketThread/Receiver)
09-08 19:02:16.489  3758  4249 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 414, thread name: OutgoingSocketThread/Receiver)
09-08 19:02:16.489  3758  4249 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 19:02:16.490  3758  4249 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 414, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 19:02:16.491  3758  4250 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 415, name: IncomingSocketThread/Receiver)
,09-08 19:02:16.492  3758  4250 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 415, thread name: IncomingSocketThread/Receiver)
,09-08 19:02:16.492  3758  4250 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 19:02:16.493  3758  4250 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 415, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 19:02:19.477  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 19:02:19.479  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 19:02:19.485  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c52f632 Bundle[{}]
,09-08 19:02:19.486  3758  3805 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 19:02:19.486  3758  3805 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 19:02:19.487  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 19:02:19.487  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 19:02:19.488  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 19:02:19.488  3758  3805 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 19:02:19.493  3758  3805 I System.out: Running OutgoingSocketThread
,09-08 19:02:19.497  3758  4251 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-08 19:02:19.498  3758  4251 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 19:02:20.366   874  1313 D ConnectivityService: handlePromptUnvalidated 102
,09-08 19:02:21.598  1887  1999 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 19:02:21.599  1887  1999 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 19:02:21.648  1512  1512 I ConfigService: onCreate
,09-08 19:02:22.506  3758  4253 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 19:02:22.506  3758  4253 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 19:02:22.507  3758  4253 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
09-08 19:02:22.507  3758  4251 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 19:02:22.508  3758  4251 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 19:02:22.508  3758  4253 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 19:02:22.508  3758  4251 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 19:02:22.511  3758  4255 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Sender)
,09-08 19:02:22.511  3758  4253 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 19:02:22.517  3758  4251 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 19:02:22.517  3758  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Receiver)
,09-08 19:02:22.519  3758  4251 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 19:02:22.520  3758  4256 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: IncomingSocketThread/Receiver)
09-08 19:02:22.520  3758  4256 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 19:02:22.521  3758  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 19:02:22.522  3758  4257 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-08 19:02:22.526  3758  4258 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,09-08 19:02:22.529  3758  4258 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
09-08 19:02:22.529  3758  4258 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 19:02:22.529  3758  4258 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 19:02:23.799  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:23.816  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:23.820  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:23.906  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 19:02:23.907  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 19:02:23.908  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:23.908  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:23.979  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 19:02:23.981  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 19:02:23.982  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 19:02:25.508  3758  3805 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 436)
,09-08 19:02:25.511  3758  3805 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 19:02:25.511  3758  3805 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 437)
,09-08 19:02:25.517  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 19:02:25.517  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46d38f7 added. We now have 3 listener(s)
09-08 19:02:25.519  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:02:25.519  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:02:25.519  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 19:02:25.519  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 19:02:25.519  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe6b364 added. We now have 4 listener(s)
,09-08 19:02:25.520  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:02:25.520  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 19:02:25.523  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:25.533  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:25.535  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:25.536  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:02:25.538  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:02:25.538  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:25.538  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:02:25.538  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:02:25.539  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:25.539  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:25.539  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 19:02:25.540  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:02:25.540  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:25.540  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46d38f7 removed from the list
,09-08 19:02:25.540  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:25.541  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe6b364 removed from the list
09-08 19:02:25.541  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:25.541  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:25.543  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:25.543  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:25.544  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:25.545  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:25.545  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:25.545  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe6b364 not in the list
,09-08 19:02:25.545  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:25.545  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:25.546  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:25.546  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:25.546  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:02:25.546  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe6b364 not in the list
09-08 19:02:25.546  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:02:25.546  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:25.546  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:25.546  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46d38f7 not in the list
09-08 19:02:25.547  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 19:02:25.547  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eadd282 added. We now have 3 listener(s)
09-08 19:02:25.549  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 19:02:25.549  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 19:02:25.549  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:02:25.549  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:02:25.550  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b26d93 added. We now have 4 listener(s)
09-08 19:02:25.550  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:02:25.550  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 19:02:25.553  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:25.558  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:25.561  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:25.562  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 19:02:25.562  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 19:02:25.562  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 19:02:25.562  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 19:02:25.562  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:02:25.562  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 19:02:25.564  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:25.567  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 19:02:25.567  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 19:02:25.567  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:25.572  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 19:02:25.573  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 19:02:25.573  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 19:02:25.577  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 19:02:25.578  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 19:02:25.578  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 19:02:25.578  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:02:25.582  4159  4195 D BtGatt.GattService: registerClient() - UUID=da32bff9-bc1c-4415-abdf-725c9ca79d53
,09-08 19:02:25.583  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=da32bff9-bc1c-4415-abdf-725c9ca79d53, clientIf=5
,09-08 19:02:25.585  3758  3768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 19:02:25.586  4159  4169 D BtGatt.GattService: start scan with filters
,09-08 19:02:25.590  4159  4178 D BtGatt.ScanManager: handling starting scan
,09-08 19:02:25.590  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 19:02:25.590  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 19:02:25.591  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 19:02:25.591  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 19:02:25.592  4159  4178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bba25a6
,09-08 19:02:25.600  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 19:02:25.601  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 19:02:25.601  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 19:02:25.603  4159  4175 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 19:02:25.603  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:25.604  4159  4178 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 19:02:25.608  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:02:25.612  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 19:02:25.612  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:25.613  4159  4178 D BtGatt.ScanManager: Starting BLE batch scan
09-08 19:02:25.613  4159  4178 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 19:02:25.617  3758  3805 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 19:02:25.618  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 19:02:25.618  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 19:02:25.618  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:25.618  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 19:02:25.618  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 19:02:25.618  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:02:25.618  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 19:02:25.618  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 19:02:25.618  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 19:02:25.619  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 19:02:25.620  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:02:25.621  4159  4169 D BtGatt.GattService: stopScan() - queue size =1
,09-08 19:02:25.622  4159  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 19:02:25.622  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 19:02:25.622  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 19:02:25.622  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 19:02:25.623  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 19:02:25.623  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 19:02:25.624  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 19:02:25.624  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 19:02:25.625  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 19:02:25.625  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 19:02:25.625  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:02:25.627  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:02:25.627  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 19:02:25.627  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 19:02:25.630  4159  4175 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 19:02:25.630  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:25.637  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 19:02:25.638  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:25.652  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 19:02:25.652  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:25.653  4159  4178 D BtGatt.ScanManager: stopping BLe Batch
,09-08 19:02:25.663  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 19:02:25.663  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:25.663  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:02:25.672  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 19:02:25.672  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:26.129  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:02:26.129  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:02:26.129  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 19:02:26.742  1512  1512 I ConfigService: onDestroy
,09-08 19:02:28.628  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:02:28.629  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:02:28.629  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 19:02:28.630  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:02:28.631  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:28.631  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:02:28.631  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:02:28.632  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eadd282 removed from the list
09-08 19:02:28.632  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:28.632  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b26d93 removed from the list
09-08 19:02:28.632  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:28.633  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:28.634  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:28.635  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:28.638  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:28.638  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:28.639  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:28.639  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b26d93 not in the list
09-08 19:02:28.639  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:28.640  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:28.643  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:02:28.643  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:28.643  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:28.644  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b26d93 not in the list
,09-08 19:02:28.644  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:28.644  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:28.645  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:28.645  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eadd282 not in the list
09-08 19:02:28.647  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 19:02:28.648  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9730afc added. We now have 3 listener(s)
,09-08 19:02:28.652  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 19:02:28.652  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 19:02:28.652  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:02:28.652  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:02:28.652  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ca585 added. We now have 4 listener(s)
09-08 19:02:28.652  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:02:28.653  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 19:02:28.657  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:28.663  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:28.667  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:28.667  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 19:02:28.667  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 19:02:28.668  3758  3805 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 19:02:28.668  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 19:02:28.670  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 19:02:28.671  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 19:02:28.671  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 19:02:28.671  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-08 19:02:28.673  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:28.674  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 19:02:28.675  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 19:02:28.675  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 19:02:28.675  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 19:02:28.675  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 19:02:28.675  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-08 19:02:28.675  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 19:02:28.677  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:28.677  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 19:02:28.678  3758  4260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 19:02:28.679  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 19:02:28.679  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 19:02:28.684  3758  4260 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 19:02:28.686  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 19:02:28.687  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 19:02:28.687  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 19:02:28.691  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 19:02:28.692  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:02:28.694  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 19:02:28.696  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 19:02:28.697  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 19:02:28.697  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 19:02:28.699  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:02:28.704  4159  4200 D BtGatt.GattService: registerClient() - UUID=32f9e68d-45fa-4eec-b5f2-aadfed3a9547
,09-08 19:02:28.704  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=32f9e68d-45fa-4eec-b5f2-aadfed3a9547, clientIf=5
09-08 19:02:28.705  3758  3769 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 19:02:28.709  4159  4177 D BtGatt.AdvertiseManager: message : 0
,09-08 19:02:28.713  4159  4177 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 19:02:28.724  4159  4175 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 19:02:28.733  4159  4175 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 19:02:28.734  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 19:02:28.735  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 19:02:28.737  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:02:28.740  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 19:02:28.740  3758  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 19:02:28.740  3758  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 19:02:28.740  3758  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 19:02:28.740  3758  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 19:02:28.741  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 19:02:28.744  3758  3758 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 19:02:28.744  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 19:02:28.745  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 19:02:28.745  3758  3805 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 19:02:29.245  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 19:02:31.747  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:02:31.747  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 19:02:31.748  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 19:02:31.748  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 19:02:31.748  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 19:02:31.749  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 19:02:31.749  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 19:02:31.750  3758  3805 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 19:02:31.750  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 19:02:31.750  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 19:02:31.750  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:02:31.751  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 19:02:31.751  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 19:02:31.751  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 19:02:31.752  3758  4260 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 19:02:31.752  3758  4260 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 19:02:31.753  3758  4260 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 19:02:31.754  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:02:31.754  3758  3805 D BluetoothLeScanner: could not find callback wrapper
09-08 19:02:31.754  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 19:02:31.754  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 19:02:31.757  4159  4177 D BtGatt.AdvertiseManager: message : 1
09-08 19:02:31.758  4159  4177 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 19:02:31.769  4159  4175 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 19:02:31.770  4159  4175 D BtGatt.GattService: Client app is not null!
,09-08 19:02:31.771  4159  4169 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 19:02:31.772  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 19:02:31.772  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 19:02:31.772  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 19:02:31.772  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 19:02:31.773  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 19:02:31.775  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:02:31.776  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 19:02:31.776  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 19:02:31.777  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 19:02:31.779  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:31.779  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:02:31.779  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:02:31.779  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:02:31.779  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9730afc removed from the list
09-08 19:02:31.779  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:31.779  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ca585 removed from the list
09-08 19:02:31.780  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:31.780  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:31.780  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:02:31.780  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:02:31.780  3758  3758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 19:02:31.780  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:02:31.781  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:02:31.781  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:31.784  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:31.784  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:31.785  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 19:02:31.785  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ca585 not in the list
09-08 19:02:31.785  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:31.785  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:31.787  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:02:31.788  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:31.788  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:31.788  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ca585 not in the list
09-08 19:02:31.788  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:02:31.789  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:31.789  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:31.789  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9730afc not in the list
09-08 19:02:31.791  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 19:02:31.791  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@506fa6 added. We now have 3 listener(s)
,09-08 19:02:31.798  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:02:31.798  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:02:31.799  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:02:31.799  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:02:31.799  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a84de7 added. We now have 4 listener(s)
09-08 19:02:31.800  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 19:02:31.801  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 19:02:31.805  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:31.810  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:31.812  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:31.812  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:02:31.812  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 19:02:31.812  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 19:02:31.812  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 19:02:31.812  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 19:02:31.813  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 19:02:31.815  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:31.816  3758  3805 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 19:02:31.816  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 19:02:31.818  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:31.820  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-08 19:02:31.821  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 19:02:31.821  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 19:02:31.824  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 19:02:31.824  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 19:02:31.824  3758  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 19:02:31.825  3758  3805 D BluetoothAdapter: STATE_ON
,09-08 19:02:31.827  4159  4188 D BtGatt.GattService: registerClient() - UUID=2591e300-584f-4e1e-9e52-2a15f099db3e
09-08 19:02:31.827  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=2591e300-584f-4e1e-9e52-2a15f099db3e, clientIf=5
09-08 19:02:31.828  3758  3768 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 19:02:31.828  4159  4169 D BtGatt.GattService: start scan with filters
,09-08 19:02:31.831  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 19:02:31.831  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 19:02:31.831  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 19:02:31.831  4159  4178 D BtGatt.ScanManager: handling starting scan
09-08 19:02:31.831  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 19:02:31.834  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 19:02:31.834  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 19:02:31.834  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 19:02:31.836  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 19:02:31.842  4159  4175 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 19:02:31.842  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:31.842  4159  4178 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 19:02:31.851  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 19:02:31.852  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:31.852  4159  4178 D BtGatt.ScanManager: Starting BLE batch scan
09-08 19:02:31.852  4159  4178 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 19:02:31.872  4159  4175 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 19:02:31.872  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:31.887  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 19:02:31.888  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:32.281  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:02:32.335  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 19:02:32.336  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 19:02:32.336  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 19:02:33.392  4159  4159 D BtGatt.ScanManager: awakened up at time 224791
,09-08 19:02:33.394  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:02:33.452  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 19:02:33.452  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 19:02:33.453  4159  4175 D BtGatt.GattService: current time is 224852711338
,09-08 19:02:33.455  4159  4175 D BtGatt.GattService: Batch record : [-75, 112, 8, 38, 113, -28, 1, 0, -106, 30, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 39, -77, -6, 2, 2, -29, 23, 62, 6, -63, 49, 28, 6, 8, 116, 105, 115, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -95, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:02:33.458  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, 39, -77, -6, 2, 2, -29, 23, 62, 6, -63, 49, 6, 8, 116, 105, 115, 55, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
09-08 19:02:33.460  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 19:02:33.461  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 19:02:33.462  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 19:02:33.462  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 19:02:33.463  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 19:02:33.464  4159  4175 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 19:02:34.847  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:02:34.847  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 19:02:34.848  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 19:02:34.848  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:02:34.848  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 19:02:34.849  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 19:02:34.849  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 19:02:34.849  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 19:02:34.849  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 19:02:34.850  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 19:02:34.850  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 19:02:34.852  3758  3805 D BluetoothAdapter: STATE_ON
09-08 19:02:34.855  4159  4188 D BtGatt.GattService: stopScan() - queue size =1
09-08 19:02:34.857  4159  4169 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 19:02:34.858  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 19:02:34.858  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 19:02:34.859  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 19:02:34.859  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 19:02:34.859  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 19:02:34.865  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 19:02:34.865  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 19:02:34.866  3758  3805 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 19:02:34.866  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 19:02:34.867  4159  4159 D BtGatt.ScanManager: awakened up at time 226266
09-08 19:02:34.868  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 19:02:34.872  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 19:02:34.872  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 19:02:34.872  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 19:02:34.873  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:34.874  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.874  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:02:34.874  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:02:34.875  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@506fa6 removed from the list
09-08 19:02:34.875  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.875  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a84de7 removed from the list
09-08 19:02:34.875  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
09-08 19:02:34.876  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.877  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 19:02:34.878  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.882  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 19:02:34.882  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:34.882  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:34.883  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:34.883  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.883  4159  4178 D BtGatt.ScanManager: stopping BLe Batch
,09-08 19:02:34.883  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a84de7 not in the list
09-08 19:02:34.883  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.884  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.885  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 19:02:34.885  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:34.885  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.885  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a84de7 not in the list
09-08 19:02:34.885  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:34.885  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.886  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.886  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@506fa6 not in the list
,09-08 19:02:34.886  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 19:02:34.887  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af51f00 added. We now have 3 listener(s)
,09-08 19:02:34.889  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 19:02:34.889  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 19:02:34.889  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 19:02:34.889  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 19:02:34.889  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d06339 added. We now have 4 listener(s)
09-08 19:02:34.889  3758  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 19:02:34.890  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 19:02:34.892  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 19:02:34.894  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 19:02:34.894  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:34.894  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 19:02:34.897  3758  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 19:02:34.899  3758  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 19:02:34.900  3758  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 19:02:34.902  3758  3805 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 19:02:34.902  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 19:02:34.902  3758  3805 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 19:02:34.902  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 19:02:34.902  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.902  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 19:02:34.902  3758  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 19:02:34.902  3758  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af51f00 removed from the list
09-08 19:02:34.902  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.902  3758  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d06339 removed from the list
09-08 19:02:34.903  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 19:02:34.904  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 19:02:34.904  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 19:02:34.906  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 19:02:34.906  3758  3805 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 19:02:34.906  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.906  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.906  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:34.907  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:34.907  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:34.907  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.908  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d06339 not in the list
09-08 19:02:34.908  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.908  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 19:02:34.909  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 19:02:34.909  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 19:02:34.909  3758  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 19:02:34.909  3758  3805 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d06339 not in the list
,09-08 19:02:34.909  3758  3805 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 19:02:34.909  3758  3805 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 19:02:34.909  3758  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 19:02:34.909  3758  3805 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af51f00 not in the list
09-08 19:02:34.910  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-08 19:02:34.910  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 19:02:34.910  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 19:02:34.911  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 19:02:34.911  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 19:02:34.911  3758  3805 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 19:02:35.374  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 19:02:36.926  3758  4262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
,09-08 19:02:38.924  3758  3805 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 446
,09-08 19:02:38.924  3758  3805 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 446, name: My test thread name)
,09-08 19:02:38.931  3758  4263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: My test thread name)
,09-08 19:02:38.931  3758  4263 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: My test thread name)
09-08 19:02:38.932  3758  4263 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-08 19:02:38.935  3758  3805 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 19:02:38.944  3758  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,09-08 19:02:38.945  3758  4264 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 451, thread name: My test thread name): Test exception.
09-08 19:02:38.945  3758  4264 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 19:02:38.952  3758  3805 I jxcore-log: Total number of executed tests:  82
09-08 19:02:38.952  3758  3805 I jxcore-log: 
,09-08 19:02:38.954  3758  3805 I jxcore-log: Number of passed tests:  82
09-08 19:02:38.954  3758  3805 I jxcore-log: 
09-08 19:02:38.955  3758  3805 I jxcore-log: Number of failed tests:  0
09-08 19:02:38.955  3758  3805 I jxcore-log: 
,09-08 19:02:38.955  3758  3805 I jxcore-log: Number of ignored tests:  0
09-08 19:02:38.955  3758  3805 I jxcore-log: 
09-08 19:02:38.956  3758  3805 I jxcore-log: Total duration:  101265
09-08 19:02:38.956  3758  3805 I jxcore-log: 
,09-08 19:02:38.965  3758  3805 I jxcore-log: Unit Test app is loaded
09-08 19:02:38.965  3758  3805 I jxcore-log: 
,09-08 19:02:38.988  3758  3758 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 19:02:38.992  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:38.992  3758  3805 I jxcore-log: 
,09-08 19:02:39.005  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.005  3758  3805 I jxcore-log: 
,09-08 19:02:39.006  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.006  3758  3805 I jxcore-log: 
,09-08 19:02:39.007  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.007  3758  3805 I jxcore-log: 
,09-08 19:02:39.009  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 19:02:39.009  3758  3805 I jxcore-log: 
,09-08 19:02:39.011  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.011  3758  3805 I jxcore-log: 
,09-08 19:02:39.013  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.013  3758  3805 I jxcore-log: 
,09-08 19:02:39.016  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.016  3758  3805 I jxcore-log: 
,09-08 19:02:39.017  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 19:02:39.017  3758  3805 I jxcore-log: 
,09-08 19:02:39.018  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.018  3758  3805 I jxcore-log: 
,09-08 19:02:39.019  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.019  3758  3805 I jxcore-log: 
,09-08 19:02:39.021  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.021  3758  3805 I jxcore-log: 
,09-08 19:02:39.022  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.022  3758  3805 I jxcore-log: 
09-08 19:02:39.022  3758  4262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,09-08 19:02:39.024  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.024  3758  3805 I jxcore-log: 
,09-08 19:02:39.025  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.025  3758  3805 I jxcore-log: 
09-08 19:02:39.027  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.027  3758  3805 I jxcore-log: 
,09-08 19:02:39.028  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.028  3758  3805 I jxcore-log: 
09-08 19:02:39.029  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.029  3758  3805 I jxcore-log: 
,09-08 19:02:39.029  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.029  3758  3805 I jxcore-log: 
09-08 19:02:39.030  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.030  3758  3805 I jxcore-log: 
,09-08 19:02:39.031  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.031  3758  3805 I jxcore-log: 
09-08 19:02:39.032  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.032  3758  3805 I jxcore-log: 
,09-08 19:02:39.033  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.033  3758  3805 I jxcore-log: 
09-08 19:02:39.034  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.034  3758  3805 I jxcore-log: 
,09-08 19:02:39.035  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.035  3758  3805 I jxcore-log: 
09-08 19:02:39.036  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.036  3758  3805 I jxcore-log: 
,09-08 19:02:39.037  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.037  3758  3805 I jxcore-log: 
09-08 19:02:39.038  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.038  3758  3805 I jxcore-log: 
,09-08 19:02:39.039  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.039  3758  3805 I jxcore-log: 
09-08 19:02:39.040  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.040  3758  3805 I jxcore-log: 
09-08 19:02:39.041  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.041  3758  3805 I jxcore-log: 
,09-08 19:02:39.042  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.042  3758  3805 I jxcore-log: 
,09-08 19:02:39.043  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.043  3758  3805 I jxcore-log: 
09-08 19:02:39.045  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.045  3758  3805 I jxcore-log: 
,09-08 19:02:39.045  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.045  3758  3805 I jxcore-log: 
09-08 19:02:39.046  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.046  3758  3805 I jxcore-log: 
09-08 19:02:39.046  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.046  3758  3805 I jxcore-log: 
,09-08 19:02:39.047  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.047  3758  3805 I jxcore-log: 
09-08 19:02:39.047  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.047  3758  3805 I jxcore-log: 
09-08 19:02:39.048  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.048  3758  3805 I jxcore-log: 
,09-08 19:02:39.049  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 19:02:39.049  3758  3805 I jxcore-log: 
09-08 19:02:39.049  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.049  3758  3805 I jxcore-log: 
09-08 19:02:39.050  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 19:02:39.050  3758  3805 I jxcore-log: 
,09-08 19:02:39.050  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.050  3758  3805 I jxcore-log: 
09-08 19:02:39.051  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.051  3758  3805 I jxcore-log: 
09-08 19:02:39.052  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.052  3758  3805 I jxcore-log: 
,09-08 19:02:39.052  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.052  3758  3805 I jxcore-log: 
09-08 19:02:39.053  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.053  3758  3805 I jxcore-log: 
,09-08 19:02:39.053  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.053  3758  3805 I jxcore-log: 
09-08 19:02:39.054  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.054  3758  3805 I jxcore-log: 
,09-08 19:02:39.054  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 19:02:39.054  3758  3805 I jxcore-log: 
09-08 19:02:39.055  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.055  3758  3805 I jxcore-log: 
09-08 19:02:39.056  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.056  3758  3805 I jxcore-log: 
,09-08 19:02:39.056  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 19:02:39.056  3758  3805 I jxcore-log: 
09-08 19:02:39.057  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 19:02:39.057  3758  3805 I jxcore-log: 
09-08 19:02:39.057  3758  3805 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 19:02:39.057  3758  3805 I jxcore-log: 
,09-08 19:02:39.061  3758  3805 I jxcore-log: My device name is: motorola-Nexus 6
09-08 19:02:39.061  3758  3805 I jxcore-log: 
09-08 19:02:39.062  3758  3805 I jxcore-log: Running for WIFI network type
09-08 19:02:39.062  3758  3805 I jxcore-log: 
,09-08 19:02:41.578  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 19:02:41.578  3758  3805 I jxcore-log: 
,09-08 19:02:42.054  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 19:02:42.054  3758  3805 I jxcore-log: 
,09-08 19:02:42.088  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 19:02:42.088  3758  3805 I jxcore-log: 
,09-08 19:02:43.591  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 19:02:43.591  3758  3805 I jxcore-log: 
,09-08 19:02:43.843  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 19:02:43.843  3758  3805 I jxcore-log: 
,09-08 19:02:43.848  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 19:02:43.848  3758  3805 I jxcore-log: 
,09-08 19:02:43.855  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 19:02:43.855  3758  3805 I jxcore-log: 
,09-08 19:02:44.121  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 19:02:44.121  3758  3805 I jxcore-log: 
,09-08 19:02:44.139  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 19:02:44.139  3758  3805 I jxcore-log: 
,09-08 19:02:44.144  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 19:02:44.144  3758  3805 I jxcore-log: 
,09-08 19:02:44.225  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:44.232  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:44.234  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:02:44.234  4028  4265 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 19:02:44.249  4028  4266 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 19:02:44.254  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 19:02:44.254  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 19:02:44.254  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:44.254  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:44.270  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 19:02:44.270  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 19:02:44.270  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
09-08 19:02:44.273  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 19:02:44.273  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 19:02:44.273  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:44.274  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:44.310  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 19:02:44.310  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 19:02:44.310  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:02:44.310  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:02:44.320  4028  4266 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 19:02:44.321  4028  4265 E BooksSync: Soft error
09-08 19:02:44.321  4028  4265 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:02:44.321  4028  4265 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:02:44.321  4028  4265 E BooksSync: Sync error
09-08 19:02:44.321  4028  4265 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:02:44.321  4028  4265 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:02:44.321  4028  4265 I BooksSync: Finished books sync
,09-08 19:02:44.326   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 235436, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:02:44.896  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 19:02:44.896  3758  3805 I jxcore-log: 
,09-08 19:02:45.070  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 19:02:45.070  3758  3805 I jxcore-log: 
,09-08 19:02:45.419  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 19:02:45.419  3758  3805 I jxcore-log: 
,09-08 19:02:45.430  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 19:02:45.430  3758  3805 I jxcore-log: 
,09-08 19:02:45.438  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 19:02:45.438  3758  3805 I jxcore-log: 
,09-08 19:02:45.445  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 19:02:45.445  3758  3805 I jxcore-log: 
,09-08 19:02:45.487  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 19:02:45.487  3758  3805 I jxcore-log: 
,09-08 19:02:45.536  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 19:02:45.536  3758  3805 I jxcore-log: 
,09-08 19:02:45.544  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 19:02:45.544  3758  3805 I jxcore-log: 
,09-08 19:02:45.552  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 19:02:45.552  3758  3805 I jxcore-log: 
,09-08 19:02:45.572  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 19:02:45.572  3758  3805 I jxcore-log: 
,09-08 19:02:45.578  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 19:02:45.578  3758  3805 I jxcore-log: 
,09-08 19:02:45.584  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 19:02:45.584  3758  3805 I jxcore-log: 
,09-08 19:02:45.601  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 19:02:45.601  3758  3805 I jxcore-log: 
,09-08 19:02:45.628  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 19:02:45.628  3758  3805 I jxcore-log: 
,09-08 19:02:45.640  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 19:02:45.640  3758  3805 I jxcore-log: 
,09-08 19:02:45.654  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 19:02:45.654  3758  3805 I jxcore-log: 
,09-08 19:02:45.665  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 19:02:45.665  3758  3805 I jxcore-log: 
,09-08 19:02:45.682  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 19:02:45.682  3758  3805 I jxcore-log: 
,09-08 19:02:45.693  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 19:02:45.693  3758  3805 I jxcore-log: 
,09-08 19:02:45.699  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 19:02:45.699  3758  3805 I jxcore-log: 
,09-08 19:02:45.730  3758  3805 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 19:02:45.730  3758  3805 I jxcore-log: 
,09-08 19:02:45.743  3758  3805 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 19:02:45.744  3758  3805 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 19:02:45.744  3758  3805 I jxcore-log: 
,09-08 19:02:45.746  3758  3805 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 19:02:45.746  3758  3805 I jxcore-log: 
,09-08 19:02:45.747  3758  3805 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 19:02:45.747  3758  3805 I jxcore-log: 
,09-08 19:02:45.752  3758  3805 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 19:02:45.752  3758  3805 I jxcore-log: 
,09-08 19:02:45.823  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:02:45.823  3758  3805 I jxcore-log: 
,09-08 19:02:45.823  3758  3805 I jxcore-log: websocket error
09-08 19:02:45.823  3758  3805 I jxcore-log: 
09-08 19:02:45.824  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:02:45.824  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:02:45.824  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:02:45.824  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:45.824  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:02:45.824  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:45.824  3758  3805 I jxcore-log: 
,09-08 19:02:47.269  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:02:47.269  3758  3805 I jxcore-log: 
,09-08 19:02:47.272  3758  3805 I jxcore-log: websocket error
09-08 19:02:47.272  3758  3805 I jxcore-log: 
,09-08 19:02:47.272  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:02:47.272  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:02:47.272  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:02:47.272  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:47.272  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:02:47.272  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:47.272  3758  3805 I jxcore-log: 
,09-08 19:02:48.925  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:02:48.925  3758  3805 I jxcore-log: 
09-08 19:02:48.927  3758  3805 I jxcore-log: websocket error
09-08 19:02:48.927  3758  3805 I jxcore-log: 
,09-08 19:02:48.927  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:02:48.927  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:02:48.927  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:02:48.927  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:48.927  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:02:48.927  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:48.927  3758  3805 I jxcore-log: 
,09-08 19:02:52.123  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:02:52.123  3758  3805 I jxcore-log: 
,09-08 19:02:52.126  3758  3805 I jxcore-log: websocket error
09-08 19:02:52.126  3758  3805 I jxcore-log: 
09-08 19:02:52.126  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:02:52.126  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:02:52.126  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:02:52.126  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:52.126  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:02:52.126  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:52.126  3758  3805 I jxcore-log: 
,09-08 19:02:53.311   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244710, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:02:56.653  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:02:56.653  3758  3805 I jxcore-log: 
,09-08 19:02:56.653  3758  3805 I jxcore-log: websocket error
09-08 19:02:56.653  3758  3805 I jxcore-log: 
09-08 19:02:56.653  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:02:56.653  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:02:56.653  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:02:56.653  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:56.653  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:02:56.653  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:02:56.653  3758  3805 I jxcore-log: 
,09-08 19:03:01.625   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 19:03:01.710  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:01.710  3758  3805 I jxcore-log: 
,09-08 19:03:01.710  3758  3805 I jxcore-log: websocket error
09-08 19:03:01.710  3758  3805 I jxcore-log: 
,09-08 19:03:01.710  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:01.710  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:01.710  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:01.710  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:01.710  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:01.710  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:01.710  3758  3805 I jxcore-log: 
,09-08 19:03:06.766  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:06.766  3758  3805 I jxcore-log: 
,09-08 19:03:06.766  3758  3805 I jxcore-log: websocket error
09-08 19:03:06.766  3758  3805 I jxcore-log: 
09-08 19:03:06.766  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:06.766  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:06.766  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:06.766  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:06.766  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:06.766  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:06.766  3758  3805 I jxcore-log: 
,09-08 19:03:11.820  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:11.820  3758  3805 I jxcore-log: 
,09-08 19:03:11.820  3758  3805 I jxcore-log: websocket error
09-08 19:03:11.820  3758  3805 I jxcore-log: 
,09-08 19:03:11.820  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:11.820  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:11.820  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:11.820  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:11.820  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:11.820  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:11.820  3758  3805 I jxcore-log: 
,09-08 19:03:14.809  3034  4269 V KeepSync: Connecting to GoogleApiClient
,09-08 19:03:14.809   874  2290 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 19:03:14.842  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:14.848  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:14.887  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:03:14.887  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 19:03:14.887  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:03:14.888  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:14.906  3009  4270 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 19:03:14.906  3009  4270 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at blb.a(PG:3937)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at czp.a(PG:18188)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:03:14.906  3009  4270 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	... 12 more
09-08 19:03:14.906  3009  4270 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at fal.a(PG:38)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:03:14.906  3009  4270 E HttpOperation: 	... 14 more
,09-08 19:03:14.957  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 19:03:14.957  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 19:03:14.958  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:03:14.958  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:14.971  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:03:14.971  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 19:03:14.971  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:03:14.971  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:14.987  3009  4270 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 19:03:14.987  3009  4270 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at hec.a(PG:42)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at hee.a(PG:102)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at czr.a(PG:65)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at kka.a(PG:108)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at czp.a(PG:19176)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:03:14.987  3009  4270 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	... 15 more
09-08 19:03:14.987  3009  4270 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at fal.a(PG:38)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:03:14.987  3009  4270 E HttpOperation: 	... 17 more
09-08 19:03:14.987  3009  4270 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 19:03:14.987  3009  4270 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at hec.a(PG:42)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at hee.a(PG:102)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at czr.a(PG:65)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at kka.a(PG:108)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	... 15 more
09-08 19:03:14.987  3009  4270 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at fal.a(PG:38)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 19:03:14.987  3009  4270 E ExperimentLoader: 	... 17 more
,09-08 19:03:14.997  1701  4271 V BaseAuthAsyncOperation: access token request failed
,09-08 19:03:15.000  3034  4269 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 19:03:15.091  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 19:03:15.092  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 19:03:15.092  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:03:15.092  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:15.116  3034  4269 E KeepSync: IOException
09-08 19:03:15.116  3034  4269 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 19:03:15.116  3034  4269 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:03:15.116  3034  4269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 19:03:15.116  3034  4269 E KeepSync: 	... 10 more
,09-08 19:03:15.116  3034  4269 W KeepSync: Sync result 2
,09-08 19:03:15.137   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 253791, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:03:15.164   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 235810, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:03:16.877  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:16.877  3758  3805 I jxcore-log: 
09-08 19:03:16.877  3758  3805 I jxcore-log: websocket error
09-08 19:03:16.877  3758  3805 I jxcore-log: 
,09-08 19:03:16.878  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:16.878  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:16.878  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:16.878  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:16.878  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:16.878  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:16.878  3758  3805 I jxcore-log: 
,09-08 19:03:21.939  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:21.939  3758  3805 I jxcore-log: 
,09-08 19:03:21.939  3758  3805 I jxcore-log: websocket error
09-08 19:03:21.939  3758  3805 I jxcore-log: 
09-08 19:03:21.940  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:21.940  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:21.940  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:21.940  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:21.940  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:21.940  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:21.940  3758  3805 I jxcore-log: 
,09-08 19:03:27.036  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:27.036  3758  3805 I jxcore-log: 
09-08 19:03:27.036  3758  3805 I jxcore-log: websocket error
09-08 19:03:27.036  3758  3805 I jxcore-log: 
09-08 19:03:27.037  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:27.037  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:27.037  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:27.037  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:27.037  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:27.037  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:27.037  3758  3805 I jxcore-log: 
,09-08 19:03:32.098  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:32.098  3758  3805 I jxcore-log: 
09-08 19:03:32.098  3758  3805 I jxcore-log: websocket error
09-08 19:03:32.098  3758  3805 I jxcore-log: 
09-08 19:03:32.098  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:32.098  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:32.098  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:32.098  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:32.098  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:32.098  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:32.098  3758  3805 I jxcore-log: 
,09-08 19:03:37.174  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:37.174  3758  3805 I jxcore-log: 
09-08 19:03:37.174  3758  3805 I jxcore-log: websocket error
09-08 19:03:37.174  3758  3805 I jxcore-log: 
09-08 19:03:37.175  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:37.175  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:37.175  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:37.175  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:37.175  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:37.175  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:37.175  3758  3805 I jxcore-log: 
,09-08 19:03:42.092   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=293490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:03:42.288  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:42.288  3758  3805 I jxcore-log: 
09-08 19:03:42.289  3758  3805 I jxcore-log: websocket error
09-08 19:03:42.289  3758  3805 I jxcore-log: 
,09-08 19:03:42.290  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:42.290  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:42.290  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:42.290  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:42.290  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:42.290  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:42.290  3758  3805 I jxcore-log: 
,09-08 19:03:46.569  4028  4278 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 19:03:46.602  4028  4279 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 19:03:46.621  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:46.623  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:46.657  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 19:03:46.657  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 19:03:46.658  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:03:46.658  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:46.703  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:46.707  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:46.751  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 19:03:46.751  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 19:03:46.751  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:03:46.752  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:46.778  4028  4279 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:03:46.779  4028  4278 E BooksSync: Soft error
09-08 19:03:46.779  4028  4278 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:03:46.779  4028  4278 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 19:03:46.780  4028  4278 E BooksSync: Sync error
09-08 19:03:46.780  4028  4278 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:03:46.780  4028  4278 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 19:03:46.780  4028  4278 I BooksSync: Finished books sync
,09-08 19:03:46.795   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297878, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:03:46.954  3034  4280 V KeepSync: Connecting to GoogleApiClient
,09-08 19:03:46.955   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 19:03:47.007  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:47.009  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:03:47.046  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 19:03:47.046  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 19:03:47.046  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:03:47.046  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:47.068  1701  4281 V BaseAuthAsyncOperation: access token request failed
,09-08 19:03:47.069  3034  4280 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 19:03:47.133  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 19:03:47.133  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 19:03:47.133  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:03:47.133  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:03:47.158  3034  4280 E KeepSync: IOException,
09-08 19:03:47.158  3034  4280 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 19:03:47.158  3034  4280 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:03:47.158  3034  4280 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 19:03:47.158  3034  4280 E KeepSync: 	... 10 more
09-08 19:03:47.158  3034  4280 W KeepSync: Sync result 2
,09-08 19:03:47.166   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 298221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:03:47.225   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=298624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 19:03:47.347  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:47.347  3758  3805 I jxcore-log: 
,09-08 19:03:47.348  3758  3805 I jxcore-log: websocket error
09-08 19:03:47.348  3758  3805 I jxcore-log: 
09-08 19:03:47.349  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:47.349  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:47.349  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:47.349  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:47.349  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:47.349  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:47.349  3758  3805 I jxcore-log: 
,09-08 19:03:52.403  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:52.403  3758  3805 I jxcore-log: 
,09-08 19:03:52.404  3758  3805 I jxcore-log: websocket error
09-08 19:03:52.404  3758  3805 I jxcore-log: 
09-08 19:03:52.404  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:52.404  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:52.404  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:52.404  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:52.404  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:52.404  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:52.404  3758  3805 I jxcore-log: 
,09-08 19:03:57.464  3758  3805 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-08 19:03:57.464  3758  3805 I jxcore-log: 
,09-08 19:03:57.465  3758  3805 I jxcore-log: websocket error
09-08 19:03:57.465  3758  3805 I jxcore-log: 
09-08 19:03:57.466  3758  3805 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-08 19:03:57.466  3758  3805 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-08 19:03:57.466  3758  3805 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-08 19:03:57.466  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:57.466  3758  3805 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-08 19:03:57.466  3758  3805 I jxcore-log: emit@events.js:82:1
09-08 19:03:57.466  3758  3805 I jxcore-log: 
,09-08 19:04:02.798  3758  3805 I jxcore-log: ThaliTape :: Reconnected to the test server
09-08 19:04:02.798  3758  3805 I jxcore-log: 
,09-08 19:04:02.813  3758  3805 I jxcore-log: ThaliTape :: Connected to the test server
09-08 19:04:02.813  3758  3805 I jxcore-log: 
,09-08 19:04:18.248  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:18.252  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:18.292  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 19:04:18.292  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 19:04:18.292  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:04:18.292  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:04:18.317  3009  4292 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 19:04:18.317  3009  4292 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at blb.a(PG:3937)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at czp.a(PG:18188)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:04:18.317  3009  4292 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	... 12 more
09-08 19:04:18.317  3009  4292 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at fal.a(PG:38)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:04:18.317  3009  4292 E HttpOperation: 	... 14 more
,09-08 19:04:18.398  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:04:18.398  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:04:18.398  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:04:18.398  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:04:18.420  3009  4292 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 19:04:18.420  3009  4292 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at hec.a(PG:42)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at hee.a(PG:102)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at czr.a(PG:65)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at kka.a(PG:108)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at czp.a(PG:19176)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:04:18.420  3009  4292 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	... 15 more
09-08 19:04:18.420  3009  4292 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at fal.a(PG:38)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:04:18.420  3009  4292 E HttpOperation: 	... 17 more
,09-08 19:04:18.421  3009  4292 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 19:04:18.421  3009  4292 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at hec.a(PG:42)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at hee.a(PG:102)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at czr.a(PG:65)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at kka.a(PG:108)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	... 15 more
09-08 19:04:18.421  3009  4292 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at fal.a(PG:38)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 19:04:18.421  3009  4292 E ExperimentLoader: 	... 17 more
,09-08 19:04:18.551   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 329282, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:04:32.872  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:32.882  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:32.884  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:32.928  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 19:04:32.929  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-08 19:04:32.929  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:04:32.929  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:04:32.953  1512  2057 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 19:04:32.953  1512  2057 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 19:04:32.959  3507  3539 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 19:04:32.959  3507  3539 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 19:04:32.959  3507  3539 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 19:04:32.959  3507  3539 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 19:04:32.959  3507  3539 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 19:04:32.959  3507  3539 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 19:04:32.959  3507  3539 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 19:04:50.680  3034  4298 V KeepSync: Connecting to GoogleApiClient
,09-08 19:04:50.681   874  1696 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 19:04:50.751  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:50.752  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:04:50.784  1512  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 19:04:50.784  1512  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 19:04:50.784  1512  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:04:50.784  1512  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:04:50.801  1701  4299 V BaseAuthAsyncOperation: access token request failed
,09-08 19:04:50.802  3034  4298 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 19:04:50.841  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 19:04:50.841  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 19:04:50.841  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:04:50.841  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:04:50.864  3034  4298 E KeepSync: IOException
09-08 19:04:50.864  3034  4298 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 19:04:50.864  3034  4298 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:04:50.864  3034  4298 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 19:04:50.864  3034  4298 E KeepSync: 	... 10 more
,09-08 19:04:50.864  3034  4298 W KeepSync: Sync result 2
,09-08 19:04:50.879   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 361933, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:05:51.158  4028  4303 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 19:05:51.195  4028  4304 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 19:05:51.207  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:05:51.209  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:05:51.245  1512  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 19:05:51.246  1512  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 19:05:51.246  1512  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:05:51.246  1512  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:05:51.277  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:05:51.279  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:05:51.312  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 19:05:51.312  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 19:05:51.312  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:05:51.312  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:05:51.332  4028  4304 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 19:05:51.333  4028  4303 E BooksSync: Soft error
09-08 19:05:51.333  4028  4303 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:05:51.333  4028  4303 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 19:05:51.334  4028  4303 E BooksSync: Sync error
09-08 19:05:51.334  4028  4303 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 19:05:51.334  4028  4303 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 19:05:51.334  4028  4303 I BooksSync: Finished books sync
,09-08 19:05:51.346   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 422498, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:06:24.336  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:06:24.338  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:06:24.378  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:06:24.378  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:06:24.378  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:06:24.378  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:06:24.394  3009  4307 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 19:06:24.394  3009  4307 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at blb.a(PG:3937)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at czp.a(PG:18188)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:06:24.394  3009  4307 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	... 12 more
09-08 19:06:24.394  3009  4307 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at fal.a(PG:38)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:06:24.394  3009  4307 E HttpOperation: 	... 14 more
,09-08 19:06:24.467  1512  2058 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 19:06:24.467  1512  2058 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 19:06:24.467  1512  2058 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 19:06:24.467  1512  2058 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:06:24.485  3009  4307 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 19:06:24.485  3009  4307 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jdm.a(PG:82)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jcs.o(PG:406)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jcn.a(PG:1379)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jcs.i(PG:143)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at hec.a(PG:42)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at hee.a(PG:102)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at czr.a(PG:65)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at kka.a(PG:108)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at czp.a(PG:19176)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at czp.a(PG:9081)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at czq.run(PG:1686)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:06:24.485  3009  4307 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jdj.a(PG:4091)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jdj.a(PG:1125)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jdm.a(PG:77)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	... 15 more
09-08 19:06:24.485  3009  4307 E HttpOperation: Caused by: faj: BadAuthentication
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at fal.a(PG:38)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	at jdj.a(PG:4089)
09-08 19:06:24.485  3009  4307 E HttpOperation: 	... 17 more
,09-08 19:06:24.485  3009  4307 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 19:06:24.485  3009  4307 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at hec.a(PG:42)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at hee.a(PG:102)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at czr.a(PG:65)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at kka.a(PG:108)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	... 15 more
09-08 19:06:24.485  3009  4307 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at fal.a(PG:38)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 19:06:24.485  3009  4307 E ExperimentLoader: 	... 17 more
,09-08 19:06:24.615   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 455387, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:06:57.728  3034  4312 V KeepSync: Connecting to GoogleApiClient
09-08 19:06:57.728   874  2288 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 19:06:57.786  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:06:57.788  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 19:06:57.823  1512  2287 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 19:06:57.823  1512  2287 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 19:06:57.824  1512  2287 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:06:57.824  1512  2287 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:06:57.848  1701  4313 V BaseAuthAsyncOperation: access token request failed
,09-08 19:06:57.849  3034  4312 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 19:06:57.917  1512  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 19:06:57.917  1512  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 19:06:57.917  1512  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 19:06:57.917  1512  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 19:06:57.939  3034  4312 E KeepSync: IOException
09-08 19:06:57.939  3034  4312 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 19:06:57.939  3034  4312 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 19:06:57.939  3034  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 19:06:57.939  3034  4312 E KeepSync: 	... 10 more
09-08 19:06:57.939  3034  4312 W KeepSync: Sync result 2
,09-08 19:06:57.954   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 489014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 19:13:31.825   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=883224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:13:44.385   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:13:56.918   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=908317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:14:09.451   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:14:21.985   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=933384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:14:34.518   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:14:47.051   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=958450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:14:59.571   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:15:12.118   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=983517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:15:24.664   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:15:37.185   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1008584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:15:49.705   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:16:02.251   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1033650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:16:14.772   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046171, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:16:27.318   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:16:39.838   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:16:52.331   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1083730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:17:04.891   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1096290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:17:17.398   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:17:29.958   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:17:42.465   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1133864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:17:55.025   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:18:07.531   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1158930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:18:20.078   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:18:32.598   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1183997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:18:45.145   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:18:56.011   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1207410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:19:07.866   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 19:19:10.224   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:19:21.078   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1232477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:19:35.278   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:19:46.145   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1257544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:20:00.358   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1271757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:20:11.238   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1282637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:20:25.425   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:20:36.278   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1307677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:20:50.518   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1321917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:21:01.397   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1332796, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:21:15.584   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1346983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:21:26.464   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1357863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:21:40.665   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1372064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:21:51.531   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1382930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:22:05.744   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:22:16.598   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1407997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:22:30.811   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:22:41.664   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1433063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:22:55.878   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:23:06.732   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1458130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:23:20.931   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:23:31.798   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1483197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:23:45.985   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1497384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 19:24:02.038   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1513436, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 19:24:11.051   874  4217 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1522450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms)
```
