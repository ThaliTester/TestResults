#### Test 64613803adf70b9_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-31 16:26:53.374  1510  2443 I CheckinService: Done disabling old GoogleServicesFramework version
,03-31 16:26:53.797  3376  3376 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-31 16:26:53.799  3376  3376 D AndroidRuntime: CheckJNI is OFF
03-31 16:26:53.904  3376  3376 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-31 16:26:53.907   769  1247 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-31 16:26:53.914   769  1247 V WindowManager: addAppToken: AppWindowToken{65fe7a6 token=Token{4e96d01 ActivityRecord{275892e8 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-31 16:26:53.919   769   838 V WindowManager: Adding window Window{2e05bb39 u0 Starting com.test.thalitest} at 2 of 7 (after Window{5ea1889 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-31 16:26:53.925  1366  1386 W SearchService: Abort, client detached.
03-31 16:26:53.926  3376  3376 D AndroidRuntime: Shutting down VM
03-31 16:26:53.948   769  1191 I ActivityManager: Start proc 3397:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-31 16:26:53.984  1366  1366 I MicroDetector: Keeping mic open: false
03-31 16:26:53.984  1366  1366 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@2113c060
03-31 16:26:53.984  1366  1553 I DeviceStateChecker: DeviceStateChecker cancelled
03-31 16:26:54.034   190  1563 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-31 16:26:54.034   190  1563 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-31 16:26:54.039  1366  1556 I MicroRecognitionRunner: Detection finished
03-31 16:26:54.041  1366  1552 I MicroRecognitionRunner: Stopping hotword detection.
03-31 16:26:54.062  3397  3397 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
03-31 16:26:54.072  3397  3397 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7910-7911)
03-31 16:26:54.072  3397  3397 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 16:26:54.081  3397  3397 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {224ba3c4}
03-31 16:26:54.081  3397  3397 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
03-31 16:26:54.082  3397  3397 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
03-31 16:26:54.092  3397  3397 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-31 16:26:54.097   769  1287 I ActivityManager: Killing 2489:com.google.android.deskclock/u0a33 (adj 15): empty #17
03-31 16:26:54.109  3397  3397 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 16:26:54.156  3397  3397 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-31 16:26:54.157  3397  3397 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-31 16:26:54.161   769   837 D BluetoothManagerService: Message: 20
03-31 16:26:54.161   769   837 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d789cf:true
,03-31 16:26:54.193  3397  3397 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-31 16:26:54.193  3397  3397 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-31 16:26:54.206  3397  3397 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-31 16:26:54.212  3397  3397 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-31 16:26:54.213  3397  3397 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-31 16:26:54.222  3397  3397 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-31 16:26:54.243  3397  3454 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-31 16:26:54.249  3397  3397 D Atlas   : Validating map...
,03-31 16:26:54.251   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,03-31 16:26:54.260   769   785 V WindowManager: Adding window Window{35c546ea u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2e05bb39 u0 Starting com.test.thalitest})
,03-31 16:26:54.271   769   861 D WifiService: New client listening to asynchronous messages
,03-31 16:26:54.285   769  1191 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 16:26:54.286   769   862 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 16:26:54.286   769   862 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 16:26:54.287  3397  3458 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 16:26:54.317  3397  3454 I OpenGLRenderer: Initialized EGL, version 1.4
03-31 16:26:54.323  3397  3454 D OpenGLRenderer: Enabling debug mode 0
,03-31 16:26:54.417   769   838 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +492ms
,03-31 16:26:54.421  1078  1078 I Keyboard.Facilitator: onFinishInput()
,03-31 16:26:54.443  3397  3465 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-31 16:26:54.491  3397  3397 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3397
,03-31 16:26:54.663  3397  3397 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-31 16:26:54.784  3397  3470 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362794880
,03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-31 16:26:54.791  3397  3470 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@257f0e54 added. We now have 1 listener(s)
,03-31 16:26:54.793   769  1156 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:26:54.797  3397  3470 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-31 16:26:54.800  3397  3470 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-31 16:26:54.801  3397  3470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-31 16:26:54.802  3397  3470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-31 16:26:54.804  3397  3470 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3762f943 added. We now have 1 listener(s)
03-31 16:26:54.805  3397  3470 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-31 16:26:54.807  3397  3470 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-31 16:26:54.810  3397  3470 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-31 16:26:54.810  3397  3470 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-31 16:26:54.813  3397  3470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-31 16:26:54.815   769  1191 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-31 16:26:54.816  3397  3470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:26:54.823  3397  3470 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-31 16:26:54.823  3397  3470 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-31 16:26:54.823  3397  3470 D io.jxcore.node.ConnectivityMonitor: start: OK
03-31 16:26:54.823  3397  3470 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-31 16:26:54.825  3397  3397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 16:26:54.827  3397  3397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-31 16:26:54.847  3397  3397 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-31 16:26:55.522  3397  3471 W jxcore-log: Initializing JXcore engine
,03-31 16:26:55.522  3397  3471 W jxcore-log: JXcore engine is ready
,03-31 16:26:55.557  3471  3471 W Thread-347: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7492]" dev="sockfs" ino=7492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-31 16:26:55.557  3471  3471 W Thread-347: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-31 16:26:55.557  3471  3471 W Thread-347: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8459]" dev="sockfs" ino=8459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-31 16:26:55.557  3471  3471 W Thread-347: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17596]" dev="sockfs" ino=17596 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-31 16:26:55.571  3397  3471 W jxcore-log: Starting JXcore engine
,03-31 16:26:55.647  3397  3471 W jxcore-log: Platform android
03-31 16:26:55.647  3397  3471 W jxcore-log: 
03-31 16:26:55.647  3397  3471 W jxcore-log: Process ARCH arm
03-31 16:26:55.647  3397  3471 W jxcore-log: 
,03-31 16:26:55.840  3397  3471 I jxcore-log: JXcore Cordova bridge is ready!
03-31 16:26:55.840  3397  3471 I jxcore-log: 
03-31 16:26:55.840  3397  3471 W jxcore-log: JXcore engine is started
,03-31 16:26:55.845  3397  3470 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-31 16:26:55.847  3397  3397 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-31 16:26:56.567  3236  3259 W Babel   : aye TOOK TOO LONG! (15032ms > 10000ms)
,03-31 16:26:56.568  3236  3257 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-31 16:26:56.572   769  1247 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 16:26:56.576   769  1121 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 16:26:56.579  3236  3236 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-31 16:26:56.579  3236  3236 W Babel   : BAM#gBA: invalid account id: -1
03-31 16:26:56.579  3236  3236 W Babel   : BAM#gBA: invalid account id: -1
03-31 16:26:56.579  3236  3236 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-31 16:26:56.581   769   933 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-31 16:26:56.583   769  1122 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-31 16:26:56.660  3236  3267 W Babel   : aye TOOK TOO LONG! (15031ms > 10000ms)
,03-31 16:26:56.666  1567  1645 I Finsky  : [120] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-31 16:26:56.668  1567  1567 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 16:26:59.160  1510  1522 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-31 16:27:03.233   769  1192 I ActivityManager: Killing 3033:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-31 16:27:03.387   769  1192 I ActivityManager: Killing 3010:com.android.providers.calendar/u0a1 (adj 15): empty #18
,03-31 16:27:04.512  1567  1567 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-31 16:27:04.521  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:04.526  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:04.526  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:04.984  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:05.002  3397  3471 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-31 16:27:05.002  3397  3471 I jxcore-log: 
03-31 16:27:05.004  3397  3471 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-31 16:27:05.004  3397  3471 I jxcore-log: 
,03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-31 16:27:05.007  3397  3471 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-31 16:27:05.008  3397  3471 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-31 16:27:05.009  3397  3471 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-31 16:27:05.009  3397  3471 I jxcore-log: 
03-31 16:27:05.011  3397  3471 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-31 16:27:05.011  3397  3471 I jxcore-log: 
,03-31 16:27:05.105  1567  1628 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 16:27:05.105  1567  1628 I qtaguid : Untagging socket 38 failed errno=-22
03-31 16:27:05.105  1567  1628 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 16:27:05.107  1567  1567 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-31 16:27:05.143  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:05.172   769  1122 I ActivityManager: Start proc 3523:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-31 16:27:05.259   769  1122 I art     : Explicit concurrent mark sweep GC freed 31578(1545KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.476ms total 58.467ms
,03-31 16:27:05.269  3523  3523 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-31 16:27:05.269  3523  3523 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-31 16:27:05.300  3523  3523 I MultiDex: VM with version 2.1.0 has multidex support
03-31 16:27:05.300  3523  3523 I MultiDex: install
03-31 16:27:05.300  3523  3523 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-31 16:27:05.316  3523  3523 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-31 16:27:05.355  3523  3523 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-31 16:27:05.367  3523  3523 D ChimeraCfgMgr: Reading stored module config
,03-31 16:27:05.374  1309  1309 D WearableService: callingUid 10007, callindPid: 1309
,03-31 16:27:05.380  1309  1926 E MDM     : [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-31 16:27:05.385  1309  1309 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-31 16:27:05.386  1510  3551 D LocationInitializer: Restart initialization of location
,03-31 16:27:05.397  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:05.412  1309  1509 W GCoreFlp: No location to return for getLastLocation()
,03-31 16:27:05.413  1309  3552 W FusedLocationProvider: location=null
,03-31 16:27:05.475  1567  1627 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 16:27:05.475  1567  1627 I qtaguid : Untagging socket 38 failed errno=-22
03-31 16:27:05.475  1567  1627 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 16:27:05.494  3523  3523 D CAR.SERVICE: Connecting to CarCallService...
,03-31 16:27:05.503  3523  3550 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
03-31 16:27:05.505  3523  3523 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-31 16:27:05.505  3523  3523 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-31 16:27:05.518  3523  3523 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-31 16:27:05.523  3523  3523 D CAR.TEL.Service: Creating a new CarCallService.
03-31 16:27:05.524  3523  3523 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-31 16:27:05.525   769   785 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-31 16:27:05.525  3523  3523 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@2fa1446d
03-31 16:27:05.525   769  1156 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-31 16:27:05.525  3523  3523 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
,03-31 16:27:05.525  3523  3523 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-31 16:27:05.538  3397  3471 I jxcore-log: Unit Test app is loaded
03-31 16:27:05.538  3397  3471 I jxcore-log: 
,03-31 16:27:05.542  3397  3471 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-31 16:27:05.542  3397  3471 I jxcore-log: 
03-31 16:27:05.544  3397  3397 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
03-31 16:27:05.545  3397  3471 I jxcore-log: My device name is: LGE-Nexus 5
03-31 16:27:05.545  3397  3471 I jxcore-log: 
,03-31 16:27:05.618  3523  3543 D CAR.SERVICE: Package validated; name: com.android.vending
,03-31 16:27:06.000  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:06.577  1567  1628 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-31 16:27:06.577  1567  1628 I qtaguid : Untagging socket 38 failed errno=-22
03-31 16:27:06.577  1567  1628 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-31 16:27:06.659  1567  1567 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-31 16:27:06.691  1309  1328 D DeviceConnectionService: client connected with version: 8298000
,03-31 16:27:06.705  1567  1567 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-31 16:27:06.705  1567  1567 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-31 16:27:08.257   769   833 I ActivityManager: Start proc 3567:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,03-31 16:27:08.285   201   201 I art     : Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 1.469ms total 27.104ms
,03-31 16:27:08.297   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 197us total 10.835ms
,03-31 16:27:08.307   201   201 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 194us total 8.497ms
,03-31 16:27:08.314  3567  3567 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-31 16:27:08.350  3567  3567 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@4482ed7(com.android.providers.calendar.CalendarProvider2@224ba3c4)
,03-31 16:27:08.358  3567  3592 E SQLiteLog: (284) automatic index on view_events(_id)
,03-31 16:27:08.380  1567  3593 I Finsky  : [130] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-31 16:27:08.384  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:09.411  3567  3567 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-31 16:27:09.411  3567  3567 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-31 16:27:09.434  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-31 16:27:09.434  3397  3471 I jxcore-log: 
,03-31 16:27:09.787  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-31 16:27:09.787  3397  3471 I jxcore-log: 
,03-31 16:27:09.797  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-31 16:27:09.797  3397  3471 I jxcore-log: 
,03-31 16:27:09.801  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-31 16:27:09.801  3397  3471 I jxcore-log: 
,03-31 16:27:09.839  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-31 16:27:09.839  3397  3471 I jxcore-log: 
,03-31 16:27:09.855  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-31 16:27:09.855  3397  3471 I jxcore-log: 
03-31 16:27:09.859  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-31 16:27:09.859  3397  3471 I jxcore-log: 
,03-31 16:27:10.740  3523  3523 D CAR.SERVICE: mConnectedToCar = false, abort
,03-31 16:27:10.754  3523  3523 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32ad53b5 that was originally bound here
03-31 16:27:10.754  3523  3523 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32ad53b5 that was originally bound here
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 16:27:10.754  3523  3523 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 16:27:10.759  3523  3523 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@19acb484 that was originally bound here
03-31 16:27:10.759  3523  3523 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@19acb484 that was originally bound here
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-31 16:27:10.759  3523  3523 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,03-31 16:27:10.760   769   933 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@39bd38f3
,03-31 16:27:11.819  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-31 16:27:11.819  3397  3471 I jxcore-log: 
,03-31 16:27:11.835  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-31 16:27:11.835  3397  3471 I jxcore-log: 
,03-31 16:27:11.843  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
03-31 16:27:11.843  3397  3471 I jxcore-log: 
,03-31 16:27:12.089  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-31 16:27:12.089  3397  3471 I jxcore-log: 
,03-31 16:27:12.161  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-31 16:27:12.161  3397  3471 I jxcore-log: 
,03-31 16:27:12.215  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
03-31 16:27:12.215  3397  3471 I jxcore-log: 
,03-31 16:27:12.220  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-31 16:27:12.220  3397  3471 I jxcore-log: 
,03-31 16:27:12.229  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-31 16:27:12.229  3397  3471 I jxcore-log: 
,03-31 16:27:12.233  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-31 16:27:12.233  3397  3471 I jxcore-log: 
03-31 16:27:12.238  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
03-31 16:27:12.238  3397  3471 I jxcore-log: 
,03-31 16:27:12.253  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-31 16:27:12.253  3397  3471 I jxcore-log: 
,03-31 16:27:12.271  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-31 16:27:12.271  3397  3471 I jxcore-log: 
,03-31 16:27:12.356  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-31 16:27:12.356  3397  3471 I jxcore-log: 
,03-31 16:27:12.360  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-31 16:27:12.360  3397  3471 I jxcore-log: 
,03-31 16:27:12.384  3397  3471 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-31 16:27:12.384  3397  3471 I jxcore-log: 
,03-31 16:27:12.391  3397  3471 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-31 16:27:12.392  3397  3471 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-31 16:27:12.392  3397  3471 I jxcore-log: 
,03-31 16:27:14.256   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 16:27:14.256   769   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 16:27:14.624   769   784 I ActivityManager: Killing 3094:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,03-31 16:27:14.651   769   784 I ActivityManager: Killing 3055:com.android.musicfx/u0a13 (adj 15): empty #18
,03-31 16:27:21.131  1567  1645 I Finsky  : [120] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-31 16:27:21.131  1567  1567 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-31 16:27:34.261   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 16:27:37.249  1949  2034 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-31 16:27:37.273  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:37.278  1309  3638 I VacuumService: Vacuum at: now=1459434457278 tag=VacuumService
,03-31 16:27:38.287  1309  3644 I art     : Explicit concurrent mark sweep GC freed 106951(6MB) AllocSpace objects, 48(768KB) LOS objects, 39% free, 24MB/40MB, paused 1.462ms total 74.044ms
,03-31 16:27:38.342  1309  3647 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 5770 seconds from now (1459434458342)
,03-31 16:27:38.406  1309  3644 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-31 16:27:38.410  1309  3644 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-31 16:27:39.667  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:39.668  1309  1309 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-31 16:27:54.266   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 16:27:54.266   769   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 16:27:54.460  1078  1222 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-31 16:27:54.461  1078  1222 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-31 16:27:54.513  1309  1309 I ConfigService: onCreate
,03-31 16:27:59.557  1309  1309 I ConfigService: onDestroy
,03-31 16:28:14.272   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 16:28:14.273   769   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,03-31 16:28:30.698   769   840 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-31 16:28:30.709   769   840 I PowerManagerService: Sleeping (uid 1000)...
,03-31 16:28:30.755   769   840 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-31 16:28:30.765   190   873 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-31 16:28:30.776   175   582 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (110 us)
,03-31 16:28:30.785   769   860 E WifiStateMachine: cancelDelayedScan -> 11
,03-31 16:28:30.791   769   860 E native  : do suspend false
,03-31 16:28:30.966   190  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-31 16:28:30.967  1078  1078 I Keyboard.Facilitator: onFinishInput()
,03-31 16:28:30.977   769   860 E WifiStateMachine: cancelDelayedScan -> 13
,03-31 16:28:30.979   769   860 E native  : do suspend true
,03-31 16:28:31.288   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-31 16:28:31.288   769   860 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,03-31 16:28:31.339   769   838 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-31 16:28:31.344   769   769 V ActivityManager: Display changed displayId=0
,03-31 16:28:31.365   175   175 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
,03-31 16:28:31.366   175   175 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-31 16:28:31.478   176   176 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
03-31 16:28:31.479   176   176 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
03-31 16:28:31.479   176   176 I rmt_storage: wakelock acquired: 1, error no: 2
,03-31 16:28:31.479   176   561 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236803456)
,03-31 16:28:31.593   176   561 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
03-31 16:28:31.593   176   561 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
03-31 16:28:31.593   176   561 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236803456) wakelock released: 1, error no: 0
03-31 16:28:31.593   176   561 I rmt_storage: 
,03-31 16:28:31.596   176   176 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,03-31 16:28:31.632   175   175 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-31 16:28:31.632   769   885 D SurfaceControl: Excessive delay in setPowerMode(): 293ms
03-31 16:28:31.632  1932  1934 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,03-31 16:28:31.644  3397  3397 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-31 16:28:31.645  3397  3397 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-31 16:28:31.663  3397  3397 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9cfc6d5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2a660529, 16908290=android.view.AbsSavedState$1@2a660529}, android:focusedViewId=100}]}]
03-31 16:28:31.663  3397  3397 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
03-31 16:28:31.663  3397  3397 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
03-31 16:28:31.663  3397  3397 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,03-31 16:28:34.277   769   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,03-31 16:28:34.277   769   860 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,03-31 16:28:35.663  1309  1919 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-31 16:29:27.331  3397  3471 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-31 16:29:27.331  3397  3471 I jxcore-log: 
,03-31 16:29:27.755  3739  3739 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-31 16:29:27.758  3739  3739 D AndroidRuntime: CheckJNI is OFF
,03-31 16:29:27.855  3739  3739 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-31 16:29:27.861   769   833 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-31 16:29:27.861   769   833 I ActivityManager: Killing 3397:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-31 16:29:27.904   769  1156 I WindowState: WIN DEATH: Window{35c546ea u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-31 16:29:27.905   769  1287 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31a22cd3)
03-31 16:29:27.905   769   861 D WifiService: Client connection lost with reason: 4
03-31 16:29:27.905   769   862 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 16:29:27.906   769   862 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 16:29:27.914   769   844 W PackageSettings: Skipping PackageSetting{1009b41c com.example.hello/10116} due to missing metadata
,03-31 16:29:27.971   769   833 I ActivityManager:   Force finishing activity 3 ActivityRecord{275892e8 u0 com.test.thalitest/.MainActivity t19}
,03-31 16:29:27.974   769   933 W ActivityManager: Spurious death for ProcessRecord{9e79010 3397:com.test.thalitest/u0a49}, curProc for 3397: null
,03-31 16:29:27.975   769   844 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-31 16:29:27.977   769   844 I ActivityManager:   Force finishing activity 3 ActivityRecord{275892e8 u0 com.test.thalitest/.MainActivity t19 f}
03-31 16:29:27.977   769   844 W ActivityManager: Duplicate finish request for ActivityRecord{275892e8 u0 com.test.thalitest/.MainActivity t19 f}
,03-31 16:29:28.005  1510  1510 I art     : Explicit concurrent mark sweep GC freed 2404(146KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/30MB, paused 566us total 25.204ms
,03-31 16:29:28.070   769   769 I art     : Explicit concurrent mark sweep GC freed 60968(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 1.224ms total 53.300ms
,03-31 16:29:28.079  1197  1197 I art     : Explicit concurrent mark sweep GC freed 1772(110KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 2.245ms total 75.989ms
,03-31 16:29:28.082   926   926 I art     : Explicit concurrent mark sweep GC freed 9671(426KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.046ms total 72.426ms
,03-31 16:29:28.085   769   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
03-31 16:29:28.085   769   887 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,03-31 16:29:28.090  1078  1078 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-31 16:29:28.092  1309  1549 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-31 16:29:28.097   769   852 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-31 16:29:28.116  1078  3760 I Keyboard.Facilitator.DecoderInitializer: run()
,03-31 16:29:28.117  1078  3760 I Decoder : createOrResetDecoder
,03-31 16:29:28.125  2711  3761 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-31 16:29:28.138  1366  1366 I art     : Explicit concurrent mark sweep GC freed 2903(245KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 459us total 156.489ms
,03-31 16:29:28.155   769  1122 I ActivityManager: Start proc 3762:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-31 16:29:28.158  1309  1309 I ConfigService: onCreate
,03-31 16:29:28.174   769   769 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-31 16:29:28.174   769   769 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-31 16:29:28.220  1078  3760 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-31 16:29:28.234   769  1156 I ActivityManager: Start proc 3794:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-31 16:29:28.236   769  1192 I ActivityManager: Killing 3158:com.quickoffice.android/u0a65 (adj 15): empty #17
,03-31 16:29:28.244   769  1246 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3397 uid 10049
,03-31 16:29:28.246  1078  1078 I Keyboard.Facilitator: onFinishInput()
,03-31 16:29:28.251  1078  3760 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-31 16:29:28.253  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-31 16:29:28.253  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-31 16:29:28.254  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-31 16:29:28.254  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-31 16:29:28.255  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-31 16:29:28.255  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-31 16:29:28.255  1078  3760 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-31 16:29:28.255  1078  3760 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-31 16:29:28.255  1078  3760 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-31 16:29:28.256  1078  3760 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-31 16:29:28.256  1078  3760 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-31 16:29:28.256  1078  3760 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-31 16:29:28.270  1197  1197 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-31 16:29:28.289   769   844 I art     : Explicit concurrent mark sweep GC freed 17934(1565KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 1.401ms total 116.399ms
,03-31 16:29:28.312  3794  3794 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-31 16:29:28.321  1510  3816 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-31 16:29:28.321  1510  3816 D AccountUtils: Clearing selected account for com.test.thalitest
,03-31 16:29:28.331  1309  1309 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-31 16:29:28.331  1309  1309 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-31 16:29:28.352  1197  1415 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-31 16:29:28.352   769  1122 I ActivityManager: Start proc 3821:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,03-31 16:29:28.356  1510  3816 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-31 16:29:28.391  1510  3816 I GMPM-SVC: App measurement is starting up, version: 8703
03-31 16:29:28.391  1510  3816 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-31 16:29:28.393  1510  3839 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 16:29:28.399  1510  3839 W BaseAppContext: Using Auth Proxy for data requests.
,03-31 16:29:28.410  3739  3739 I art     : System.exit called, status: 0
03-31 16:29:28.410  3739  3739 I AndroidRuntime: VM exiting with result code 0.
,03-31 16:29:28.445   769   844 I ActivityManager: Start proc 3844:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-31 16:29:28.454  1510  3816 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-31 16:29:28.511  1510  1591 I Icing   : doRemovePackageData com.test.thalitest
,03-31 16:29:28.520   769  1247 I ActivityManager: Killing 2532:com.google.android.keep/u0a52 (adj 15): empty #17
,03-31 16:29:28.538  1510  3868 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-31 16:29:28.538  1510  3868 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-31 16:29:28.538  1510  3868 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-31 16:29:28.538  1510  3868 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-31 16:29:28.543  1510  3868 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-31 16:29:28.543  1510  3868 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,03-31 16:29:28.543  1510  3868 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-31 16:29:28.567  1510  3868 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-31 16:29:28.567  1510  3868 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-31 16:29:28.568  1510  3868 E SQLiteLog: (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,03-31 16:29:28.569  1510  3868 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-31 16:29:28.569  1510  3842 E SQLiteLog: (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
03-31 16:29:28.569  1510  3869 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-31 16:29:28.569  1510  3842 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:1775)
,03-31 16:29:28.571  1510  1894 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,03-31 16:29:28.578   769  1192 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-31 16:29:28.578   769   862 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-31 16:29:28.578   769   862 D ConnectivityService: apparently satisfied.  currentScore=60
,03-31 16:29:28.578  1510  3874 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-31 16:29:28.582  1510  3868 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-31 16:29:28.582  1510  3868 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-31 16:29:28.582  1510  3868 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-31 16:29:28.582  1510  3868 I GCore-Chimera-Crash: ==
03-31 16:29:28.582  1510  3868 I GCore-Chimera-Crash: GCore-Chimera-Crash
,--------- beginning of crash
03-31 16:29:28.585  1510  3868 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryChimeraIntentService]
03-31 16:29:28.585  1510  3868 E AndroidRuntime: Process: com.google.android.gms, PID: 1510
03-31 16:29:28.585  1510  3868 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(:com.google.android.gms:105)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:46)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-31 16:29:28.585  1510  3868 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-31 16:29:28.590  1510  3868 I Process : Sending signal. PID: 1510 SIG: 9
,03-31 16:29:28.594   769  3877 E DropBoxManagerService: Can't write: system_app_crash
03-31 16:29:28.594   769  3877 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-31 16:29:28.594   769  3877 E DropBoxManagerService: 	... 5 more
,03-31 16:29:28.595  3821  3872 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
03-31 16:29:28.595  3821  3872 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-31 16:29:28.595  3821  3872 I GAv4    :   adb logcat -s GAv4
,03-31 16:29:28.606   769  1191 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1f6b8119)
03-31 16:29:28.606   769   862 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 16:29:28.607   769   861 D WifiService: Client connection lost with reason: 4
03-31 16:29:28.607   769   862 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-31 16:29:28.608  1309  1328 W Icing   : Error while brokering service: android.os.DeadObjectException

```
