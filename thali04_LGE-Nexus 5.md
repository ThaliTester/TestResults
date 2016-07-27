#### Test 78968685da35147_thali04_LGE-Nexus 5 Logs


```
--------- beginning of main
07-27 08:54:00.978  1592  1769 I Icing   : Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
07-27 08:54:01.054  1592  1769 I Icing   : Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,07-27 08:54:03.104  3014  3014 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:54:03.108  3014  3014 D AndroidRuntime: CheckJNI is OFF
07-27 08:54:03.143  3014  3014 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:54:03.180  3014  3014 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:54:03.199  3014  3014 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 08:54:03.201   790  1066 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:54:03.223   790  1066 I ActivityManager: Start proc 3030:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 08:54:03.228  3014  3014 D AndroidRuntime: Shutting down VM
07-27 08:54:03.300  3030  3030 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-27 08:54:03.336  3030  3030 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5805-5808)
07-27 08:54:03.336  3030  3030 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.358  3030  3030 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f79dbba}
07-27 08:54:03.358  3030  3030 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.359  3030  3030 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:54:03.364  3030  3030 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:54:03.365  3030  3030 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:54:03.370  3030  3046 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-27 08:54:03.374  3030  3030 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 08:54:03.379  3030  3030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:03.379  3030  3030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:03.380  3030  3030 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
07-27 08:54:03.415   790   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@518fba0:true
,07-27 08:54:03.490  3030  3030 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:54:03.499  3030  3030 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,07-27 08:54:03.543  3030  3068 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:54:03.562  3030  3055 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-27 08:54:03.586  3030  3068 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 08:54:03.612  1232  1232 I Keyboard.Facilitator: onFinishInput()
,07-27 08:54:03.631   790   808 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +378ms (total +420ms)
,07-27 08:54:03.716  3030  3030 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3030
,07-27 08:54:03.800  3030  3030 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:54:03.905  3030  3071 D jxcore_app_log: JniHelper::setJavaVM(0xb4cbc000), pthread_self() = -1635776208
,07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 08:54:03.909  3030  3071 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdc2259 added. We now have 1 listener(s)
07-27 08:54:03.911  3030  3071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:AE:67
07-27 08:54:03.911  3030  3071 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:AE:67"
07-27 08:54:03.912  3030  3071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:54:03.912  3030  3071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:AE:67
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:54:03.914  3030  3071 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d56cccc added. We now have 1 listener(s)
07-27 08:54:03.914  3030  3071 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:54:03.916   790   891 D WifiService: New client listening to asynchronous messages
,07-27 08:54:03.916  3030  3071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:54:03.916  3030  3071 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:54:03.917  3030  3071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:54:03.917  3030  3071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:54:03.917  3030  3071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-27 08:54:03.917  3030  3071 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 08:54:03.918  3030  3071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:54:03.918  3030  3071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:AE:67
,07-27 08:54:03.919  3030  3071 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:03.920  3030  3071 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:03.920  3030  3071 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-27 08:54:03.920  3030  3071 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:54:03.920  3030  3071 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:54:03.947  3030  3030 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:54:04.307   790   966 I ActivityManager: Killing 1609:com.google.android.gm/u0a70 (adj 15): empty #17
,07-27 08:54:04.493  3030  3078 W jxcore-log: Initializing JXcore engine
,07-27 08:54:04.493  3030  3078 W jxcore-log: JXcore engine is ready
,07-27 08:54:04.526  3078  3078 W Thread-246: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7105]" dev="sockfs" ino=7105 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-27 08:54:04.526  3078  3078 W Thread-246: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 08:54:04.526  3078  3078 W Thread-246: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19119]" dev="sockfs" ino=19119 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 08:54:04.542  3030  3078 W jxcore-log: Starting JXcore engine
,07-27 08:54:04.621  3030  3078 W jxcore-log: Platform android
07-27 08:54:04.621  3030  3078 W jxcore-log: 
,07-27 08:54:04.622  3030  3078 W jxcore-log: Process ARCH arm
07-27 08:54:04.622  3030  3078 W jxcore-log: 
,07-27 08:54:04.785  3030  3078 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:54:04.785  3030  3078 I jxcore-log: 
,07-27 08:54:04.785  3030  3078 W jxcore-log: JXcore engine is started
,07-27 08:54:04.791  3030  3071 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:54:04.793  3030  3030 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:54:05.890  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(22306): Beginning daily hygiene, foreground = false
,07-27 08:54:05.895  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(366): Probe [UVAT3FEWOLBYQGmBHvKHAcB3G_U] for daily hygiene pass
,07-27 08:54:05.967  1383  3088 W EventLoggerService: Unable to send logs
07-27 08:54:05.967  1383  3088 W EventLoggerService: com.google.android.apps.gsa.shared.exception.GsaIOException: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.c(AbstractHttpEngine.java:309)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.search.core.j.a.a(AbstractHttpEngine.java:94)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.shared.io.k.a(HttpHelper.java:209)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.a(S3LogSender.java:104)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.speech.i.b.br(S3LogSender.java:79)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.a(EventLoggerService.java:575)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.i(EventLoggerService.java:320)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.gB(EventLoggerService.java:245)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at com.google.android.apps.gsa.eventlogger.EventLoggerService.onHandleIntent(EventLoggerService.java:236)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:05.967  1383  3088 W EventLoggerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:54:05.969  1383  3088 W ErrorReporter: reportError [type: 211, code: 262160]: Error code: 262160 | The connection was not attempted due to lack of network connectivity.
,07-27 08:54:05.971  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:54:05.971  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:05.980  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.026  2452  2452 W Finsky  : [1] com.google.android.finsky.services.n.a(457): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 08:54:06.037  2452  2452 I Finsky  : [1] com.google.android.finsky.utils.ch.a(42): Start requesting GCM Reg Id
,07-27 08:54:06.037  2452  2452 D GCMRegistrar: resetting backoff for com.android.vending
,07-27 08:54:06.049  2452  2452 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:54:06.060  1727  3112 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:54:06.063  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.066  1727  3112 I GCM     : GCM config loaded
,07-27 08:54:06.081  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:54:06.081  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:06.081  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:54:06.086  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-1
,07-27 08:54:06.088  2452  3116 E GCMRegistrar: internal error: retry receiver class not set yet
07-27 08:54:06.089  2452  3116 V GCMRegistrar: Registering receiver
,07-27 08:54:06.090  2452  3116 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 08:54:06.090  2452  3116 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:54:06.091  2452  3116 D GCMBaseIntentService: Scheduling registration retry, backoff = 1758 (3000)
,07-27 08:54:06.101  2452  2452 E Finsky  : [1] com.google.android.finsky.utils.bc.a(284): Couldn't upload device config
,07-27 08:54:06.102  2452  2452 W Finsky  : [1] com.google.android.finsky.utils.cl.a(112): Upload device configuration failed - try selfupdate anyway
,07-27 08:54:06.106  2452  3116 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:06.107  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.129  2452  2452 W Finsky  : [1] com.google.android.finsky.services.o.a(541): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 08:54:06.150   790  1501 I ActivityManager: Start proc 3118:com.google.android.gms:car/u0a8 for service com.google.android.gms/.car.CarService
,07-27 08:54:06.153  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.177  2452  2452 W Finsky  : [1] com.google.android.finsky.k.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 08:54:06.192  3118  3118 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:54:06.193  3118  3118 I MultiDex: install
,07-27 08:54:06.193  3118  3118 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:54:06.210  3118  3118 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x785
,07-27 08:54:06.220  3118  3118 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
07-27 08:54:06.220  3118  3118 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,07-27 08:54:06.223  3118  3118 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:54:06.247  3118  3118 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:54:06.259  3118  3118 D ChimeraCfgMgr: Reading stored module config
,07-27 08:54:06.342  3118  3132 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:54:06.345  3118  3118 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,07-27 08:54:06.345  3118  3118 D CAR.SERVICE: onBind
07-27 08:54:06.345  3118  3118 D CAR.SERVICE: CSB onClientsConnected
,07-27 08:54:06.347  3118  3118 D CAR.TEL.Service: Binding to InCallService
,07-27 08:54:06.350   790   801 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
,07-27 08:54:06.350  3118  3118 E CAR.TEL.Service: Failed to bind to InCallService
,07-27 08:54:06.396  3118  3129 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-27 08:54:06.396  3118  3129 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-27 08:54:06.400  3118  3129 W System  : ClassLoader referenced unknown path: /data/user/0/com.google.android.gms/app_chimera/m/00000003/n/armeabi
,07-27 08:54:06.401  3118  3129 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
07-27 08:54:06.402  3118  3129 D ChimeraFileApk: Classloading successful. Optimized code found.
07-27 08:54:06.404  3118  3129 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded,
,07-27 08:54:06.459  3118  3129 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-27 08:54:06.462  3118  3129 D CAR.SERVICE: Package validated; name: com.android.vending
,07-27 08:54:06.462  3118  3129 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
,07-27 08:54:06.573  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.604  2452  2452 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(252): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 08:54:06.607  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(741): Logging device features
,07-27 08:54:06.614  2452  2452 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,07-27 08:54:06.618  2452  2452 W InstanceID/Rpc: Found 10008
,07-27 08:54:06.622  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(946): Scheduling new run in 9 minutes (failures=1)
,07-27 08:54:06.659  1727  1738 D DeviceConnectionService: client connected with version: 8487000
,07-27 08:54:06.664  1727  1727 D WearableService: callingUid 10008, callindPid: 1727
,07-27 08:54:06.667  2452  3143 I Finsky  : [221] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-27 08:54:06.673  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 08:54:06.676  2452  2452 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-27 08:54:06.676  2452  2452 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=hygiene due to Gms not connected
,07-27 08:54:06.687  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:06.687  2452  3144 I PlayCommon: [222] com.google.android.play.a.w.a(27553): Starting to flush logs
07-27 08:54:06.687  2452  3144 I PlayCommon: [222] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,07-27 08:54:06.699  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 08:54:06.701  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 08:54:06.890   790   801 I ActivityManager: Killing 2281:com.google.android.youtube/u0a80 (adj 15): empty #17
,07-27 08:54:11.022   790  1066 I ActivityManager: Killing 2433:com.google.android.deskclock/u0a38 (adj 15): empty #17
,07-27 08:54:11.521  3118  3118 D CAR.SERVICE: onUnbind
,07-27 08:54:11.521  3118  3118 D CAR.SERVICE: CSB onClientsDisconnected
07-27 08:54:11.521  3118  3118 D CAR.SERVICE: tearDown
07-27 08:54:11.521  3118  3118 D CAR.SERVICE: tearDownCarState
07-27 08:54:11.521  3118  3118 D CAR.SERVICE: Skip, car not connected.
,07-27 08:54:11.521  3118  3118 D CAR.SERVICE: tearDownClientState
,07-27 08:54:11.522  3118  3118 D CAR.SERVICE: requestStop
,07-27 08:54:11.525  3118  3118 D CAR.SERVICE: onDestroy
,07-27 08:54:11.526  3118  3118 D CAR.SERVICE: tearDown
,07-27 08:54:11.526  3118  3118 D CAR.SERVICE: tearDownCarState
,07-27 08:54:11.526  3118  3118 D CAR.SERVICE: Skip, car not connected.
07-27 08:54:11.526  3118  3118 D CAR.SERVICE: tearDownClientState
,07-27 08:54:11.526  3118  3118 D CAR.SERVICE: requestStop
,07-27 08:54:11.538  3118  3118 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@12e5d62 that was originally bound here
07-27 08:54:11.538  3118  3118 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.CarCallService@12e5d62 that was originally bound here
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1092)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:986)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1303)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1286)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:604)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at irv.a(:com.google.android.gms:120)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at irv.a(:com.google.android.gms:137)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.google.android.gms.car.CarCallService.h(:com.google.android.gms:76)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.google.android.gms.car.CarCallService.<init>(:com.google.android.gms:64)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at fgl.i(:com.google.android.gms:551)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:163)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:160)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2904)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ActivityThread.-wrap2(ActivityThread.java)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1432)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:11.538  3118  3118 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 08:54:11.538   790   801 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@5b9ffee
,07-27 08:54:14.819  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:54:14.819  3030  3078 I jxcore-log: 
07-27 08:54:14.821  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:54:14.821  3030  3078 I jxcore-log: 
,07-27 08:54:14.822  3030  3078 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:14.822  3030  3078 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:14.822  3030  3078 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:14.822  3030  3078 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:54:14.823  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:54:14.823  3030  3078 I jxcore-log: 
07-27 08:54:14.825  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:54:14.825  3030  3078 I jxcore-log: 
,07-27 08:54:15.156  3030  3078 I jxcore-log: Unit Test app is loaded
07-27 08:54:15.156  3030  3078 I jxcore-log: 
,07-27 08:54:15.160  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:54:15.160  3030  3078 I jxcore-log: 
,07-27 08:54:15.165   790   800 D WifiService: setWifiEnabled: true pid=3030, uid=10000
,07-27 08:54:15.165   790   800 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 08:54:15.166  3030  3030 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:54:15.171  3030  3078 I jxcore-log: My device name is: LGE-Nexus 5
07-27 08:54:15.171  3030  3078 I jxcore-log: 
,07-27 08:54:15.172  3030  3078 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 08:54:15.172  3030  3078 I jxcore-log: 
,07-27 08:54:15.179   194   784 D SoftapController: Softap fwReload - Ok
07-27 08:54:15.181   194   784 D CommandListener: Setting iface cfg
,07-27 08:54:15.182   194   784 D CommandListener: Trying to bring down wlan0
,07-27 08:54:15.188   194   784 D CommandListener: Clearing all IP addresses on wlan0
,07-27 08:54:15.189   790   890 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-27 08:54:15.189   790   807 I ActivityManager: Start proc 3150:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding HeadsetService
,07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding A2dpService
07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding HidService
07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding HealthService
07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding PanService
07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding GattService
07-27 08:54:15.337  3150  3150 D AdapterServiceConfig: Adding BluetoothMapService
,07-27 08:54:15.352   790   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48aed08:true
,07-27 08:54:15.352  3150  3150 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 08:54:15.354  3150  3150 I bt_bluedroid: init
07-27 08:54:15.354  3150  3173 I BluetoothAdapterState: Entering OffState
,07-27 08:54:15.364  3150  3174 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 08:54:15.364  3150  3174 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-27 08:54:15.364  3150  3174 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 08:54:15.364  3150  3174 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 08:54:15.365  3150  3150 I bt_bluedroid: get_profile_interface socket
,07-27 08:54:15.369  3150  3177 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
,07-27 08:54:15.370  3150  3177 D BluetoothAdapterProperties: Name is: Nexus 5
,07-27 08:54:15.370  3150  3150 I bt_bluedroid: get_profile_interface sdp
,07-27 08:54:15.373  3150  3160 I bt_bluedroid: config_hci_snoop_log
,07-27 08:54:15.374   790   807 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 7 receivers.
,07-27 08:54:15.377  3150  3173 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 08:54:15.378  3150  3173 D BluetoothAdapterProperties: Setting state to 14
,07-27 08:54:15.378  3150  3173 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 08:54:15.380  3150  3173 D BluetoothBondStateMachine: make
,07-27 08:54:15.381  3150  3179 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 08:54:15.383  3150  3173 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:54:15.384  3150  3150 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-27 08:54:15.385  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:15.386  3150  3150 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 08:54:15.386  3150  3150 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:54:15.386  3150  3150 D BtGatt.GattService: start()
,07-27 08:54:15.387  3150  3150 I bt_bluedroid: get_profile_interface gatt
,07-27 08:54:15.388  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
07-27 08:54:15.388  3150  3150 D BtGatt.AdvertiseManager: advertise manager created
,07-27 08:54:15.393  3150  3150 V BluetoothAdapterState: isTurningOff()=false
07-27 08:54:15.393  3150  3150 V BluetoothAdapterState: isTurningOn()=false
,07-27 08:54:15.393  3150  3150 V BluetoothAdapterState: isBleTurningOn()=true
,07-27 08:54:15.394  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:54:15.395  3150  3173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 08:54:15.395  3150  3173 I bt_bluedroid: enable
07-27 08:54:15.396  3150  3174 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-27 08:54:15.397  3150  3174 I bt_hci  : start_up
,07-27 08:54:15.402  3150  3174 I bt_vendor: alloc value 0xb3972631
,07-27 08:54:15.402  3150  3174 I bt_vendor: init
07-27 08:54:15.402  3150  3174 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:54:15.402  3150  3174 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 08:54:15.439  3150  3174 D bt_hci  : start_up starting async portion
,07-27 08:54:15.439  3150  3182 I bt_hci  : event_finish_startup
07-27 08:54:15.439  3150  3182 I bt_hci_h4: hal_open
07-27 08:54:15.439  3150  3182 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-27 08:54:15.442  3150  3182 I bt_userial_vendor: device fd = 49 open
,07-27 08:54:15.525  3150  3182 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-27 08:54:15.552  3150  3182 D bt_hwcfg: Chipset BCM4335C0
,07-27 08:54:15.552  3150  3182 D bt_hwcfg: Target name = [BCM4335C0]
07-27 08:54:15.552  3150  3182 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4335c0.hcd
,07-27 08:54:15.732  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 08:54:15.732  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:15.732  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 08:54:15.735  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-2
,07-27 08:54:15.738  2452  3191 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:54:15.741  2452  3191 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:15.763  1727  3194 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:54:15.771  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:54:15.771  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:15.771  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 08:54:15.774  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-3
,07-27 08:54:15.776  2452  3196 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
07-27 08:54:15.776  2452  3196 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:54:15.776  2452  3196 D GCMBaseIntentService: Scheduling registration retry, backoff = 5369 (6000)
,07-27 08:54:15.785  2452  3196 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:15.900  3150  3182 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 08:54:15.900  3150  3182 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:54:15.900  3150  3182 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:54:15.976   790   890 D wifi    : set interface wlan0 flags (UP)
07-27 08:54:15.976   790   890 I WifiHAL : Initializing wifi
,07-27 08:54:15.976   790   890 I WifiHAL : Creating socket
07-27 08:54:15.979   790   807 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 08:54:15.980   790   890 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-27 08:54:15.980   790   890 D wifi    : Did set static halHandle = 0x9a0a5730
,07-27 08:54:15.980   790   890 D wifi    : halHandle = 0x9a0a5730, mVM = 0xb4cbc000, mCls = 0x200c1a
,07-27 08:54:15.980   790   890 D wifi    : array field set
,07-27 08:54:15.980   790   890 I WifiNative-HAL: interface[0] = p2p0
,07-27 08:54:15.980   790   890 I WifiNative-HAL: interface[1] = wlan0
,07-27 08:54:15.984   790   890 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 08:54:15.986  3030  3030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:54:15.993   790   890 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-27 08:54:15.997   790  3197 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1710598352
07-27 08:54:15.997   790  3197 D wifi    : waitForHalEvents called, vm = 0xb4cbc000, obj = 0x200c1a, env = 0x99b8c6a0
,07-27 08:54:15.998   790   803 I ActivityManager: Start proc 3199:com.android.settings/1000 for broadcast com.android.settings/.widget.SettingsAppWidgetProvider
,07-27 08:54:16.016  3150  3182 I bt_hwcfg: bt vendor lib: set UART baud 4000000
,07-27 08:54:16.016  3150  3182 I bt_hwcfg: Setting local bd addr to 34:FC:EF:11:AE:67
,07-27 08:54:16.030  3199  3199 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-27 08:54:16.042   790   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5156c4d:true
,07-27 08:54:16.046  3150  3182 I bt_hwcfg: vendor lib fwcfg completed
,07-27 08:54:16.046  3150  3182 I bt_vendor: firmware callback
07-27 08:54:16.046  3150  3182 I bt_hci  : firmware_config_callback
,07-27 08:54:16.051  3150  3211 I bt_btu  : btu_task pending for preload complete event
,07-27 08:54:16.051  3150  3211 I bt_btu_task: Bluetooth chip preload is complete
07-27 08:54:16.051  3150  3211 I bt_btu  : btu_task received preload complete event
,07-27 08:54:16.053  3199  3199 D LocalBluetoothProfileManager: Adding local MAP profile
,07-27 08:54:16.055  3199  3199 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_HCI
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_GATT
,07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 08:54:16.057  3150  3211 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 08:54:16.058  3150  3211 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 08:54:16.069  3199  3199 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 08:54:16.085  3198  3198 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 08:54:16.088   790  1345 I ActivityManager: Start proc 3225:com.google.android.apps.gcs/u0a82 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-27 08:54:16.089   790  1345 I ActivityManager: Killing 1861:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,07-27 08:54:16.130  3198  3198 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:54:16.250  3198  3198 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 08:54:16.274  3150  3211 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f09b5
07-27 08:54:16.274  3150  3211 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f09b5 
,07-27 08:54:16.274  3225  3225 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-27 08:54:16.279  3150  3177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 08:54:16.279  3150  3177 D BluetoothAdapterProperties: Address is:34:FC:EF:11:AE:67
07-27 08:54:16.280  3150  3177 D BluetoothAdapterProperties: Name is: Nexus 5
,07-27 08:54:16.281  3150  3177 D BluetoothAdapterProperties: Scan Mode:20
,07-27 08:54:16.281  3150  3177 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:54:16.281  3150  3177 D bt_hci  : do_postload posting postload work item
,07-27 08:54:16.281  3150  3182 I bt_hci  : event_postload
,07-27 08:54:16.281  3150  3182 I bt_vendor: sco_config_cb
,07-27 08:54:16.281  3150  3182 I bt_hci  : sco_config_callback postload finished.
,07-27 08:54:16.282  3030  3030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:54:16.282  3150  3177 D bt_bte_conf: Device ID record 1 : primary
07-27 08:54:16.282  3150  3177 D bt_bte_conf:   vendorId            = 000f
07-27 08:54:16.282  3150  3177 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:54:16.282  3150  3177 D bt_bte_conf:   product             = 1200
07-27 08:54:16.282  3150  3177 D bt_bte_conf:   version             = 1436
,07-27 08:54:16.282  3150  3177 D bt_bte_conf:   clientExecutableURL = 
07-27 08:54:16.283  3150  3177 D bt_bte_conf:   serviceDescription  = 
07-27 08:54:16.283  3150  3177 D bt_bte_conf:   documentationURL    = 
07-27 08:54:16.283  3150  3177 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:54:16.283  3150  3174 D bt_stack_manager: event_start_up_stack finished
07-27 08:54:16.283  3150  3173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 08:54:16.283  3150  3173 D BluetoothAdapterProperties: Setting state to 15
,07-27 08:54:16.283  3150  3173 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-27 08:54:16.284  3150  3173 I BluetoothAdapterState: Entering BleOnState
07-27 08:54:16.285  3150  3182 I bt_vendor: low_power_mode_cb
07-27 08:54:16.286  3150  3173 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-27 08:54:16.286  3150  3173 D BluetoothAdapterProperties: Setting state to 11
07-27 08:54:16.286  3150  3173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-27 08:54:16.292  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:16.294  3150  3150 D HeadsetService: Received start request. Starting profile...
07-27 08:54:16.296  3150  3150 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:54:16.300  3150  3173 I BluetoothAdapterState: Entering PendingCommandState
07-27 08:54:16.300  3150  3150 D HeadsetStateMachine: make
07-27 08:54:16.307  3150  3150 D HeadsetStateMachine: max_hf_connections = 1
07-27 08:54:16.307  3150  3150 I bt_bluedroid: get_profile_interface handsfree
07-27 08:54:16.308  3150  3177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-27 08:54:16.309  3150  3177 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-27 08:54:16.311  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:16.313   790   790 D BluetoothA2dp: Proxy object connected
,07-27 08:54:16.313  3150  3150 D A2dpService: Received start request. Starting profile...
,07-27 08:54:16.313  3150  3150 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:54:16.314  3150  3150 I bt_bluedroid: get_profile_interface avrcp
,07-27 08:54:16.320  3150  3150 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 08:54:16.320  3150  3150 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:54:16.321  3150  3150 D A2dpStateMachine: make
07-27 08:54:16.322  3150  3150 I bt_bluedroid: get_profile_interface a2dp
07-27 08:54:16.322  3150  3177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-27 08:54:16.324  3150  3150 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 08:54:16.324  3150  3253 D A2dpStateMachine: Enter Disconnected: -2
,07-27 08:54:16.329  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:16.330  3150  3150 D HidService: Received start request. Starting profile...
,07-27 08:54:16.330   941   941 D BluetoothInputDevice: Proxy object connected
07-27 08:54:16.330  3150  3150 I bt_bluedroid: get_profile_interface hidhost
07-27 08:54:16.330  3150  3150 D HidService: setHidService(): set to: null
07-27 08:54:16.330   941   941 D HidProfile: Bluetooth service connected
07-27 08:54:16.330  3150  3150 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:54:16.331  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
07-27 08:54:16.331  3150  3177 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d2099
,07-27 08:54:16.331  3150  3177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 08:54:16.331  3199  3199 D BluetoothInputDevice: Proxy object connected
,07-27 08:54:16.331  3150  3150 D HealthService: Received start request. Starting profile...
07-27 08:54:16.331  3199  3199 D HidProfile: Bluetooth service connected
07-27 08:54:16.333  3150  3150 I bt_bluedroid: get_profile_interface health
07-27 08:54:16.333  3150  3150 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 08:54:16.337  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:16.337  3225  3225 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-27 08:54:16.338  3150  3150 D PanService: Received start request. Starting profile...
,07-27 08:54:16.339  3150  3150 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:54:16.339  3150  3150 I bt_bluedroid: get_profile_interface pan
07-27 08:54:16.339   941   941 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:54:16.339   941   941 D PanProfile: Bluetooth service connected
07-27 08:54:16.339  3150  3177 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:54:16.344  3199  3199 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:54:16.344  3199  3199 D PanProfile: Bluetooth service connected
,07-27 08:54:16.351  3150  3150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2a0a74
,07-27 08:54:16.352   941   941 D BluetoothMap: Proxy object connected
,07-27 08:54:16.352   941   941 D MapProfile: Bluetooth service connected
,07-27 08:54:16.352   941   941 D BluetoothMap: getConnectedDevices()
07-27 08:54:16.353   941   941 D BluetoothMap: Bluetooth is Not enabled
,07-27 08:54:16.353  3150  3150 D BluetoothMapService: Received start request. Starting profile...
07-27 08:54:16.353  3150  3150 D BluetoothMapService: start()
07-27 08:54:16.355  3150  3150 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
07-27 08:54:16.356  3199  3199 D BluetoothMap: Proxy object connected
07-27 08:54:16.356  3150  3150 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 08:54:16.356  3150  3150 D BluetoothMapAppObserver: createReceiver()
,07-27 08:54:16.357  3150  3150 D BluetoothMapAppObserver: initObservers()
07-27 08:54:16.357  3150  3150 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 08:54:16.364  3199  3199 D MapProfile: Bluetooth service connected
07-27 08:54:16.364  3199  3199 D BluetoothMap: getConnectedDevices()
07-27 08:54:16.365  3199  3199 D BluetoothMap: Bluetooth is Not enabled
,07-27 08:54:16.366  3150  3150 V BluetoothAdapterState: isTurningOff()=false
07-27 08:54:16.366  3150  3150 V BluetoothAdapterState: isTurningOn()=true
07-27 08:54:16.366  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:54:16.366  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:54:16.368  3150  3245 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOn()=true
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOn()=true
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:54:16.369  3150  3150 V BluetoothAdapterState: isTurningOn()=true
07-27 08:54:16.370  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:54:16.370  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:54:16.373  3150  3150 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:54:16.373  3150  3150 V BluetoothAdapterState: isTurningOn()=true
07-27 08:54:16.373  3150  3150 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 08:54:16.373  3150  3150 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:54:16.373  3150  3173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 08:54:16.373  3150  3173 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:54:16.373  3150  3173 D BluetoothAdapterProperties: State =  11
07-27 08:54:16.374  3150  3177 D BluetoothAdapterProperties: Scan Mode:21
,07-27 08:54:16.374  3150  3177 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:54:16.374  3150  3173 D BluetoothAdapterProperties: Setting state to 12
07-27 08:54:16.374  3150  3173 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:54:16.375   790   807 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:16.376  3150  3173 I BluetoothAdapterState: Entering OnState
07-27 08:54:16.376  3199  3209 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 08:54:16.377   790   807 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 08:54:16.377   941   952 D BluetoothMap: onBluetoothStateChange: up=true
07-27 08:54:16.378  3199  3210 D BluetoothMap: onBluetoothStateChange: up=true
07-27 08:54:16.378   941  1389 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 08:54:16.379   790   807 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-27 08:54:16.380  1299  1424 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:16.380  3030  3030 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 08:54:16.380   941   958 D BluetoothPan: onBluetoothStateChange on: true
,07-27 08:54:16.383   941   952 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 08:54:16.383   790   807 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:54:16.384  3199  3209 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 08:54:16.384  3199  3210 D BluetoothPan: onBluetoothStateChange on: true
07-27 08:54:16.384  3150  3150 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 08:54:16.385  3150  3150 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-27 08:54:16.385   790   790 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:16.387  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:54:16.390  3150  3150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:54:16.391  3030  3030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:54:16.392  3199  3199 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:54:16.393  3150  3150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:54:16.394  3150  3150 D ObexServerSockets: Succeed to create listening sockets 
07-27 08:54:16.394  3150  3150 D ObexServerSockets0: startAccept()
,07-27 08:54:16.394  3150  3150 D ObexServerSockets0: prepareForNewConnect()
07-27 08:54:16.394   941  1126 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:54:16.395  3199  3199 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-27 08:54:16.397  3150  3150 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 08:54:16.397  3150  3150 D BluetoothSdpJni: SDP Create record success - handle: 0
07-27 08:54:16.397   941   941 D BluetoothA2dp: Proxy object connected
07-27 08:54:16.397  3150  3265 D ObexServerSockets0: Accepting socket connection...
07-27 08:54:16.397  3150  3150 D BluetoothMapService: onReceive
07-27 08:54:16.397  3150  3150 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:16.397  3150  3150 D BluetoothMapService: STATE_ON
07-27 08:54:16.398   941  1126 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:54:16.400  3150  3266 D ObexServerSockets0: Accepting socket connection...
,07-27 08:54:16.400  3199  3199 D BluetoothA2dp: Proxy object connected
,07-27 08:54:16.409   790  1345 I ActivityManager: Start proc 3267:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 08:54:16.417  3150  3150 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-27 08:54:16.417  3150  3150 D ObexServerSockets0: prepareForNewConnect()
,07-27 08:54:16.454   790  1305 I ActivityManager: Killing 2160:com.google.android.calendar/u0a31 (adj 15): empty #17
,07-27 08:54:16.475   790   807 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.478   790   807 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.480   790   807 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.480  1299  1312 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.498  3199  3210 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.498  3199  3199 D HeadsetProfile: Bluetooth service connected
,07-27 08:54:16.501   941  1389 D BluetoothHeadset: Proxy object connected
,07-27 08:54:16.501   941   941 D HeadsetProfile: Bluetooth service connected
,07-27 08:54:16.873  3267  3267 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.873  3267  3267 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.873  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMod,e: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.k.d(PG:583)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.,content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Nati,ve Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:54:16.874  3267  3267 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:54:16.874  3267  3267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 08:54:16.878   790  1501 I ActivityManager: Killing 2518:com.google.android.music:main/u0a60 (adj 15): empty #17
,07-27 08:54:16.918  3267  3296 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:54:16.926   790   807 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b6ae0d:true
,07-27 08:54:16.988  1727  1727 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 08:54:17.003  1727  1727 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:54:17.003   790   890 D WifiConfigStore: Loading config and enabling all networks 
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:17.006  3030  3030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:54:17.011  3030  3030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:54:17.013  3199  3199 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 08:54:17.023   790   890 D WifiConfigStore: loaded 0 passpoint configs
,07-27 08:54:17.023   790   890 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:54:17.024   790   890 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-27 08:54:17.025   790   890 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-27 08:54:17.026   790   890 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 08:54:17.026   790   890 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-27 08:54:17.026   790   890 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
07-27 08:54:17.026   790   890 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-27 08:54:17.042   941   941 D BluetoothPbap: Proxy object connected
07-27 08:54:17.042   941   941 D PbapServerProfile: Bluetooth service connected
07-27 08:54:17.042   790   890 D WifiNative-HAL: Setting external_sim to 1
07-27 08:54:17.043   790   890 D wifi    : setting dfs flag to true, 0x9b095d10
,07-27 08:54:17.044  2200  2200 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:17.044   790   890 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:54:17.044   790   890 D wifi    : setting scan oui 0x9b095d10
07-27 08:54:17.044   790   890 D WifiHAL : Sending mac address OUI
07-27 08:54:17.045  3150  3313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:54:17.060   790   890 E native  : do suspend true
,07-27 08:54:17.060  3199  3199 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:54:17.064   790   890 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-27 08:54:17.064   790   790 D RttService: SCAN_AVAILABLE : 3
07-27 08:54:17.065   790   904 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:17.065   194   784 D CommandListener: Setting iface cfg
07-27 08:54:17.065   194   784 D CommandListener: Trying to bring up p2p0
07-27 08:54:17.065   790   889 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 08:54:17.068  3199  3199 D BluetoothPbap: Proxy object connected
,07-27 08:54:17.068  3199  3199 D PbapServerProfile: Bluetooth service connected
,07-27 08:54:17.080   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 08:54:17.091   790   889 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 08:54:17.091   790   889 D WifiNative-HAL: p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,07-27 08:54:17.096  1727  1727 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 08:54:17.105  1727  3322 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 08:54:17.105  1727  1727 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:54:17.107  3150  3323 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:17.108  3150  3323 I BtOppRfcommListener: Accept thread started.
,07-27 08:54:17.123  1727  3322 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 08:54:17.124   790   891 D WifiService: New client listening to asynchronous messages
,07-27 08:54:19.467  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:54:19.467  3030  3078 I jxcore-log: 
,07-27 08:54:19.855  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:54:19.855  3030  3078 I jxcore-log: 
,07-27 08:54:19.878  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:54:19.878  3030  3078 I jxcore-log: 
,07-27 08:54:19.882  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:54:19.882  3030  3078 I jxcore-log: 
,07-27 08:54:19.897  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:54:19.897  3030  3078 I jxcore-log: 
,07-27 08:54:19.900  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:54:19.900  3030  3078 I jxcore-log: 
,07-27 08:54:21.482  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 08:54:21.482  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:21.482  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 08:54:21.492  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-4
07-27 08:54:21.493  2452  2489 I Finsky  : [209] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-27 08:54:21.539  2452  3334 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:54:21.542  2452  3334 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:21.559  1727  2596 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:54:21.568  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:54:21.568  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 08:54:21.568  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:54:21.571  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-5
,07-27 08:54:21.574  2452  3350 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 08:54:21.574  2452  3350 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:54:21.574  2452  3350 D GCMBaseIntentService: Scheduling registration retry, backoff = 7946 (12000)
,07-27 08:54:21.587  2452  3350 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:21.618  2452  2489 I Finsky  : [209] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-27 08:54:21.619  2452  2452 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-27 08:54:21.840  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:54:21.840  3030  3078 I jxcore-log: 
,07-27 08:54:21.851  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:54:21.851  3030  3078 I jxcore-log: 
,07-27 08:54:21.861  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:54:21.861  3030  3078 I jxcore-log: 
,07-27 08:54:22.014  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:54:22.014  3030  3078 I jxcore-log: 
,07-27 08:54:22.810  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:54:22.810  3030  3078 I jxcore-log: 
,07-27 08:54:22.865  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:54:22.865  3030  3078 I jxcore-log: 
,07-27 08:54:22.871  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:54:22.871  3030  3078 I jxcore-log: 
,07-27 08:54:23.066  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:54:23.066  3030  3078 I jxcore-log: 
,07-27 08:54:23.086  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:54:23.086  3030  3078 I jxcore-log: 
,07-27 08:54:23.090  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:54:23.090  3030  3078 I jxcore-log: 
,07-27 08:54:23.095  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:54:23.095  3030  3078 I jxcore-log: 
,07-27 08:54:23.111  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:54:23.111  3030  3078 I jxcore-log: 
,07-27 08:54:23.130  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:54:23.130  3030  3078 I jxcore-log: 
,07-27 08:54:23.214  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:54:23.214  3030  3078 I jxcore-log: 
,07-27 08:54:23.219  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:54:23.219  3030  3078 I jxcore-log: 
,07-27 08:54:23.243  3030  3078 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:54:23.243  3030  3078 I jxcore-log: 
,07-27 08:54:23.252  3030  3078 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-27 08:54:23.253  3030  3078 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 08:54:23.253  3030  3078 I jxcore-log: 
,07-27 08:54:23.303  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 08:54:23.303  3030  3078 I jxcore-log: 
,07-27 08:54:23.304  3030  3078 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:54:23.304  3030  3078 I jxcore-log: 
,07-27 08:54:48.985   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:54:49.003   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 08:54:49.024  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 08:54:49.024  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:49.024  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:54:49.027  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-6
,07-27 08:54:49.041  2452  3367 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:54:49.050  2452  3367 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:49.126   790   801 D ConnectivityService: listenForNetwork for Listen from uid/pid:10008/1592 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:54:49.164  1592  3385 W DriveInitializer: Background init thread started
,07-27 08:54:49.198  1727  2631 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:54:49.211  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:54:49.211  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:54:49.211  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:54:49.214  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-7
,07-27 08:54:49.218  2452  3388 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 08:54:49.218  2452  3388 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:54:49.218  2452  3388 D GCMBaseIntentService: Scheduling registration retry, backoff = 28549 (24000)
,07-27 08:54:49.227  2452  3388 V GCMBaseIntentService: Releasing wakelock
,07-27 08:54:49.244  1592  3385 W DriveInitializer: Background init thread ended
,07-27 08:55:03.634  1232  1352 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-27 08:55:03.634  1232  1352 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-27 08:55:29.094  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 08:55:29.094  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 08:55:29.094  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:55:29.104  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-8
,07-27 08:55:29.115  2452  3406 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:55:29.127  2452  3406 V GCMBaseIntentService: Releasing wakelock
,07-27 08:55:29.222  1727  2640 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:55:29.235  1592  3407 I EventLogChimeraService: Aggregate from 1469600728962 (log), 1469600728962 (data)
,07-27 08:55:29.238  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
07-27 08:55:29.238  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:55:29.238  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:55:29.241  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-9
,07-27 08:55:29.243  2452  3432 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 08:55:29.243  2452  3432 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:55:29.243  2452  3432 D GCMBaseIntentService: Scheduling registration retry, backoff = 56411 (48000)
,07-27 08:55:29.255  2452  3432 V GCMBaseIntentService: Releasing wakelock
,07-27 08:55:29.369  1592  3436 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 08:55:29.389  1592  3436 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-27 08:55:29.439  1727  1727 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=2e3197b7-09c6-4290-80d7-1e0941591588
,07-27 08:55:29.442  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:55:29.443  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:55:29.529  1727  1774 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:55:29.558  1592  3428 D UdcContextInitService: registered all accounts: true
,07-27 08:55:29.565  1727  1796 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 08:55:29.572  1727  2608 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-27 08:55:29.619  1727  2608 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-27 08:55:29.659  1727  2608 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,07-27 08:55:31.716  1727  2608 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,07-27 08:55:31.717  1727  2608 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,07-27 08:56:06.585  1727  1879 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 08:56:29.033   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:56:29.058   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-27 08:56:29.105  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
07-27 08:56:29.105  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 08:56:29.105  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 08:56:29.107  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-10
,07-27 08:56:29.110  2452  3454 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:56:29.113  2452  3454 V GCMBaseIntentService: Releasing wakelock
,07-27 08:56:29.132  1727  3112 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:56:29.163  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:56:29.163  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 08:56:29.163  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:56:29.167  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-11
,07-27 08:56:29.169  2452  3470 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
07-27 08:56:29.169  2452  3470 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
,07-27 08:56:29.169  2452  3470 D GCMBaseIntentService: Scheduling registration retry, backoff = 94678 (96000)
,07-27 08:56:29.244  2452  3470 V GCMBaseIntentService: Releasing wakelock
,07-27 08:58:03.853   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:58:03.904   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 08:58:03.923  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
07-27 08:58:03.923  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 08:58:03.923  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 08:58:03.946  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-12
,07-27 08:58:03.949  2452  3490 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 08:58:03.951  2452  3490 V GCMBaseIntentService: Releasing wakelock
,07-27 08:58:03.967  1727  3194 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 08:58:03.981  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 08:58:03.982  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 08:58:03.982  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 08:58:03.984  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-13
,07-27 08:58:03.986  2452  3494 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
07-27 08:58:03.987  2452  3494 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 08:58:03.987  2452  3494 D GCMBaseIntentService: Scheduling registration retry, backoff = 188479 (192000)
,07-27 08:58:04.069  2452  3494 V GCMBaseIntentService: Releasing wakelock
,07-27 08:58:18.942  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 08:58:18.975  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:58:18.995  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:58:18.995  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:58:19.019  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 08:58:19.020  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 09:02:17.449  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 09:02:17.450  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:02:17.450  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:02:17.500  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-14
,07-27 09:02:17.509  2452  3509 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:02:17.512  2452  3509 V GCMBaseIntentService: Releasing wakelock
,07-27 09:02:17.529  1727  2596 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:02:17.548  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
07-27 09:02:17.548  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:02:17.548  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:02:17.550  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-15
,07-27 09:02:17.551  2452  3526 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
07-27 09:02:17.551  2452  3526 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 09:02:17.551  2452  3526 D GCMBaseIntentService: Scheduling registration retry, backoff = 514367 (384000)
,07-27 09:02:17.628  2452  3526 V GCMBaseIntentService: Releasing wakelock
,07-27 09:03:19.025  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:03:19.084  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:03:19.089  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:03:19.089  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:03:19.117  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:03:19.120  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 09:04:05.517  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(22306): Beginning daily hygiene, foreground = false
,07-27 09:04:05.519  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(366): Probe [UVAT3FEWOLBYQGmBHvKHAcB3G_U] for daily hygiene pass
,07-27 09:04:05.545   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 09:04:05.586   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 09:04:05.594  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.598  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 09:04:05.599  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.648  2452  2452 W Finsky  : [1] com.google.android.finsky.services.n.a(457): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 09:04:05.650  2452  2452 I Finsky  : [1] com.google.android.finsky.utils.ch.a(42): Start requesting GCM Reg Id
,07-27 09:04:05.650  2452  2452 D GCMRegistrar: resetting backoff for com.android.vending
,07-27 09:04:05.727  2452  2452 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:04:05.739  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.741  1727  2631 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:04:05.742  1727  2631 V GCM     : not posting request to register com.android.vending because of backoff period
,07-27 09:04:05.744  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
07-27 09:04:05.744  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:04:05.744  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:04:05.749  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-16
,07-27 09:04:05.751  2452  3568 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 09:04:05.751  2452  3568 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 09:04:05.751  2452  3568 D GCMBaseIntentService: Scheduling registration retry, backoff = 2102 (3000)
,07-27 09:04:05.764  2452  3568 V GCMBaseIntentService: Releasing wakelock
,07-27 09:04:05.769  2452  2452 E Finsky  : [1] com.google.android.finsky.utils.bc.a(284): Couldn't upload device config
,07-27 09:04:05.770  2452  2452 W Finsky  : [1] com.google.android.finsky.utils.cl.a(112): Upload device configuration failed - try selfupdate anyway
,07-27 09:04:05.776  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.797  2452  2452 W Finsky  : [1] com.google.android.finsky.services.o.a(541): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 09:04:05.804  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.835  2452  2452 W Finsky  : [1] com.google.android.finsky.k.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 09:04:05.940  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:04:05.986  2452  2452 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(252): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-27 09:04:05.991  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(741): Logging device features
,07-27 09:04:06.000  2452  2452 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,07-27 09:04:06.007  2452  2452 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(946): Scheduling new run in 32 minutes (failures=2)
,07-27 09:04:06.036  1727  1739 D DeviceConnectionService: client connected with version: 8487000
,07-27 09:04:06.047  2452  3574 I Finsky  : [239] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-27 09:04:06.047  2452  3144 I PlayCommon: [222] com.google.android.play.a.w.a(27553): Starting to flush logs
,07-27 09:04:06.047  2452  3144 I PlayCommon: [222] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,07-27 09:04:06.050  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:04:06.071  1727  1727 D WearableService: callingUid 10008, callindPid: 1727
,07-27 09:04:06.077  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 09:04:06.078  2452  2452 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-27 09:04:06.080  2452  2452 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=hygiene due to Gms not connected
,07-27 09:04:06.102  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:04:06.106  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 09:04:20.847  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 09:04:20.847  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:04:20.847  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:04:20.886  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-17
,07-27 09:04:20.895  2452  2489 I Finsky  : [209] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,07-27 09:04:20.907  2452  3583 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:04:20.910  2452  3583 V GCMBaseIntentService: Releasing wakelock
,07-27 09:04:20.924  1727  2640 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:04:20.925  1727  2640 V GCM     : not posting request to register com.android.vending because of backoff period
,07-27 09:04:20.927  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
07-27 09:04:20.927  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:04:20.927  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:04:20.929  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-18
,07-27 09:04:20.934  2452  3586 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 09:04:20.934  2452  3586 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 09:04:20.934  2452  3586 D GCMBaseIntentService: Scheduling registration retry, backoff = 4124 (6000)
,07-27 09:04:20.953  2452  3586 V GCMBaseIntentService: Releasing wakelock
,07-27 09:04:21.012  2452  2489 I Finsky  : [209] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,07-27 09:04:21.013  2452  2452 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,07-27 09:06:05.963  1727  1879 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:08:19.125  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:08:19.160  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:19.184  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:19.184  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:08:19.211  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:08:19.215  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 09:09:16.352  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 09:09:16.352  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:09:16.352  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:09:16.354  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-19
,07-27 09:09:16.358  2452  3628 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:09:16.361  2452  3628 V GCMBaseIntentService: Releasing wakelock
,07-27 09:09:16.381  1727  3112 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:09:16.406  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 09:09:16.406  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:09:16.406  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:09:16.410  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-20
,07-27 09:09:16.412  2452  3645 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 09:09:16.412  2452  3645 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 09:09:16.412  2452  3645 D GCMBaseIntentService: Scheduling registration retry, backoff = 8889 (12000)
,07-27 09:09:16.491  2452  3645 V GCMBaseIntentService: Releasing wakelock
,07-27 09:10:07.198   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 09:10:07.242   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 09:10:07.259  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 09:10:07.261  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:10:07.261  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:10:07.279  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-21
,07-27 09:10:07.282  2452  3663 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:10:07.285  2452  3663 V GCMBaseIntentService: Releasing wakelock
,07-27 09:10:07.302  1727  3194 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:10:07.303  1727  3194 V GCM     : not posting request to register com.android.vending because of backoff period
,07-27 09:10:07.306  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 09:10:07.306  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:10:07.306  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:10:07.309  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-22
,07-27 09:10:07.315  2452  3666 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 09:10:07.315  2452  3666 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
07-27 09:10:07.315  2452  3666 D GCMBaseIntentService: Scheduling registration retry, backoff = 24379 (24000)
,07-27 09:10:07.391  2452  3666 V GCMBaseIntentService: Releasing wakelock
,07-27 09:11:18.970  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,07-27 09:11:18.971  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
,07-27 09:11:18.971  2452  2452 V GCMBaseIntentService: Acquiring wakelock
,07-27 09:11:19.025  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-23
,07-27 09:11:19.029  2452  3697 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:11:19.032  2452  3697 V GCMBaseIntentService: Releasing wakelock
,07-27 09:11:19.049  1727  2596 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:11:19.050  1727  2596 V GCM     : not posting request to register com.android.vending because of backoff period
,07-27 09:11:19.052  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 09:11:19.052  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:11:19.052  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:11:19.055  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-24
,07-27 09:11:19.064  2452  3700 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
07-27 09:11:19.064  2452  3700 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
,07-27 09:11:19.064  2452  3700 D GCMBaseIntentService: Scheduling registration retry, backoff = 55663 (48000)
,07-27 09:11:19.143  2452  3700 V GCMBaseIntentService: Releasing wakelock
,07-27 09:13:03.425   790   802 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:13:19.222  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 09:13:19.258  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:13:19.277  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:13:19.277  1727  1727 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 09:13:19.304  2452  2473 I PlayCommon: [193] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-27 09:13:19.307  2452  2473 E PlayCommon: [193] com.google.android.play.a.al.a(881): Failed to connect to server: java.net.UnknownHostException: Unable to resolve host "play.googleapis.com": No address associated with hostname
,07-27 09:16:08.868   790   890 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 09:16:08.913   790   890 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-27 09:16:08.916  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
07-27 09:16:08.916  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:16:08.916  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:16:08.920  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-25
,07-27 09:16:08.923  2452  3744 V GCMRegistrar: Registering app com.android.vending of senders 932144863878
,07-27 09:16:08.926  2452  3744 V GCMBaseIntentService: Releasing wakelock
,07-27 09:16:08.945  1727  2631 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,07-27 09:16:08.945  1727  2631 V GCM     : not posting request to register com.android.vending because of backoff period
,07-27 09:16:08.948  2452  2452 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,07-27 09:16:08.948  2452  2452 V GCMBroadcastReceiver: GCM IntentService class: com.android.vending.GCMIntentService
07-27 09:16:08.948  2452  2452 V GCMBaseIntentService: Acquiring wakelock
07-27 09:16:08.952  2452  2452 V GCMBaseIntentService: Intent service name: GCMIntentService-932144863878-26
,07-27 09:16:08.958  2452  3747 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,07-27 09:16:08.958  2452  3747 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
,07-27 09:16:08.959  2452  3747 D GCMBaseIntentService: Scheduling registration retry, backoff = 129062 (96000)
,07-27 09:16:09.038  2452  3747 V GCMBaseIntentService: Releasing wakelock
,TIME-OUT KILL (timeout was 1400000ms)
```
