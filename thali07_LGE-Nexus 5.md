#### Test 639107046bb5f66_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
,03-23 17:54:18.613  3286  3307 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
03-23 17:54:18.616  3286  3309 W Babel   : aye TOOK TOO LONG! (15031ms > 10000ms)
--------- beginning of system
03-23 17:54:18.646   763  1188 W Telecom : TelecomServiceImpl: null is not visible for the calling user
03-23 17:54:18.648   763   939 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
03-23 17:54:18.649  3286  3286 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-23 17:54:18.649  3286  3286 W Babel   : BAM#gBA: invalid account id: -1
03-23 17:54:18.649  3286  3286 W Babel   : BAM#gBA: invalid account id: -1
03-23 17:54:18.649  3286  3286 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
03-23 17:54:18.650   763  1229 W Telecom : TelecomServiceImpl: null is not visible for the calling user
03-23 17:54:18.651   763   779 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
03-23 17:54:18.715  3286  3317 W Babel   : aye TOOK TOO LONG! (15050ms > 10000ms)
03-23 17:54:18.771  1659  1742 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-23 17:54:18.771  1659  1659 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
03-23 17:54:18.845  3480  3480 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-23 17:54:18.848  3480  3480 D AndroidRuntime: CheckJNI is OFF
03-23 17:54:18.939  3480  3480 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-23 17:54:18.942   763  1329 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-23 17:54:18.948   763  1329 V WindowManager: addAppToken: AppWindowToken{30679147 token=Token{25ff2486 ActivityRecord{297e1161 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-23 17:54:18.951  3480  3480 D AndroidRuntime: Shutting down VM
03-23 17:54:18.956   763   836 V WindowManager: Adding window Window{15803e5e u0 Starting com.test.thalitest} at 2 of 7 (after Window{2e176af7 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-23 17:54:18.966  1415  1435 W SearchService: Abort, client detached.
03-23 17:54:19.005   763  1263 I ActivityManager: Start proc 3502:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-23 17:54:19.012  1415  1506 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-23 17:54:19.017  1415  1415 I MicroDetector: Keeping mic open: false
03-23 17:54:19.018  1415  1415 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@316b6b76
03-23 17:54:19.018  1415  1593 I DeviceStateChecker: DeviceStateChecker cancelled
03-23 17:54:19.068   194  1602 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-23 17:54:19.068   194  1602 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-23 17:54:19.073  1415  1599 I MicroRecognitionRunner: Detection finished
03-23 17:54:19.074  1415  1592 I MicroRecognitionRunner: Stopping hotword detection.
03-23 17:54:19.106   763  1188 I art     : Explicit concurrent mark sweep GC freed 24072(1127KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.821ms total 71.515ms
,03-23 17:54:19.187  3502  3502 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,03-23 17:54:19.197  3502  3502 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 3772-3773)
03-23 17:54:19.198  3502  3502 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,03-23 17:54:19.206  3502  3502 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {161f321a}
03-23 17:54:19.206  3502  3502 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-23 17:54:19.207  3502  3502 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,03-23 17:54:19.216  3502  3502 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-23 17:54:19.231   763  1263 I ActivityManager: Killing 1974:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,03-23 17:54:19.237  3502  3502 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-23 17:54:19.288   763   835 D BluetoothManagerService: Message: 20
03-23 17:54:19.288   763   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@272c8d09:true
,03-23 17:54:19.301  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-23 17:54:19.301  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-23 17:54:19.366  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-23 17:54:19.366  3502  3502 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-23 17:54:19.377  3502  3502 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-23 17:54:19.378  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-23 17:54:19.383  3502  3502 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-23 17:54:19.384  3502  3502 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,03-23 17:54:19.385  3502  3502 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-23 17:54:19.385  3502  3502 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-23 17:54:19.391  3502  3502 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-23 17:54:19.395  3502  3502 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-23 17:54:19.399  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-23 17:54:19.399  3502  3502 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-23 17:54:19.415  3502  3555 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-23 17:54:19.419  3502  3502 D Atlas   : Validating map...
,03-23 17:54:19.424   763  1263 V WindowManager: Adding window Window{2322b6c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{15803e5e u0 Starting com.test.thalitest})
,03-23 17:54:19.430   763   867 D WifiService: New client listening to asynchronous messages
,03-23 17:54:19.438   763  1229 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-23 17:54:19.439   763   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-23 17:54:19.439   763   868 D ConnectivityService: apparently satisfied.  currentScore=60
,03-23 17:54:19.439  3502  3557 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-23 17:54:19.578   177   177 D SurfaceFlinger: shader cache generated - 24 shaders in 132.168030 ms
,03-23 17:54:19.598  3502  3555 I OpenGLRenderer: Initialized EGL, version 1.4
,03-23 17:54:19.601  3502  3555 D OpenGLRenderer: Enabling debug mode 0
,03-23 17:54:19.651   763   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +676ms
,03-23 17:54:19.652  3502  3502 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-23 17:54:19.668  1110  1110 I Keyboard.Facilitator: onFinishInput()
,03-23 17:54:19.678  3502  3562 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-23 17:54:19.682  3502  3502 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-23 17:54:19.717  3502  3502 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3502
,03-23 17:54:19.813  3502  3502 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-23 17:54:19.981  3502  3572 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362816768
,03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-23 17:54:19.995  3502  3572 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79c2a15 added. We now have 1 listener(s)
,03-23 17:54:19.996   763   778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 17:54:19.998  3502  3572 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-23 17:54:19.999  3502  3572 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
03-23 17:54:19.999  3502  3572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-23 17:54:20.000  3502  3572 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-23 17:54:20.003  3502  3572 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39654b8 added. We now have 1 listener(s)
,03-23 17:54:20.006  3502  3572 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-23 17:54:20.014  3502  3572 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-23 17:54:20.018  3502  3572 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-23 17:54:20.018  3502  3572 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-23 17:54:20.023  3502  3572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-23 17:54:20.023   763   778 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-23 17:54:20.024  3502  3572 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 17:54:20.027  3502  3572 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-23 17:54:20.027  3502  3572 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-23 17:54:20.027  3502  3572 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-23 17:54:20.029  3502  3502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-23 17:54:20.031  3502  3502 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-23 17:54:20.032  3502  3572 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-23 17:54:20.058  3502  3502 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-23 17:54:20.708  3502  3580 W jxcore-log: Initializing JXcore engine
03-23 17:54:20.708  3502  3580 W jxcore-log: JXcore engine is ready
,03-23 17:54:20.753  3580  3580 W Thread-348: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9654]" dev="sockfs" ino=9654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-23 17:54:20.753  3580  3580 W Thread-348: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-23 17:54:20.753  3580  3580 W Thread-348: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9767]" dev="sockfs" ino=9767 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-23 17:54:20.753  3580  3580 W Thread-348: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17316]" dev="sockfs" ino=17316 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-23 17:54:20.766  3502  3580 W jxcore-log: Starting JXcore engine
,03-23 17:54:20.842  3502  3580 W jxcore-log: Platform android
03-23 17:54:20.842  3502  3580 W jxcore-log: 
03-23 17:54:20.842  3502  3580 W jxcore-log: Process ARCH arm
03-23 17:54:20.842  3502  3580 W jxcore-log: 
,03-23 17:54:21.066  3502  3580 I jxcore-log: JXcore Cordova bridge is ready!
03-23 17:54:21.066  3502  3580 I jxcore-log: 
03-23 17:54:21.066  3502  3580 W jxcore-log: JXcore engine is started
,03-23 17:54:21.073  3502  3572 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-23 17:54:21.075  3502  3502 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-23 17:54:24.306  1553  1567 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-23 17:54:26.168  1659  1659 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-23 17:54:26.198  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:26.207  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:26.209  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:26.388   763   858 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
03-23 17:54:26.389   763   858 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-23 17:54:27.099  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:27.367  1659  1729 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-23 17:54:27.367  1659  1729 I qtaguid : Untagging socket 38 failed errno=-22
03-23 17:54:27.367  1659  1729 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-23 17:54:27.370  1659  1659 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-23 17:54:27.416  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:27.446   763  1269 I ActivityManager: Start proc 3615:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-23 17:54:27.481  3615  3615 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-23 17:54:27.481  3615  3615 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-23 17:54:27.508  3615  3615 I MultiDex: VM with version 2.1.0 has multidex support
03-23 17:54:27.508  3615  3615 I MultiDex: install
03-23 17:54:27.508  3615  3615 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-23 17:54:27.524  3615  3615 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-23 17:54:27.559  3615  3615 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-23 17:54:27.575  1514  1514 D WearableService: callingUid 10007, callindPid: 1514
,03-23 17:54:27.580  1514  2041 E MDM     : [174] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-23 17:54:27.584  1514  1514 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
03-23 17:54:27.584  1553  3641 D LocationInitializer: Restart initialization of location
,03-23 17:54:27.593  3615  3615 D ChimeraCfgMgr: Reading stored module config
,03-23 17:54:27.598  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:27.616  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:27.617  1514  3642 W FusedLocationProvider: location=null
,03-23 17:54:27.707  3615  3640 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-23 17:54:27.717  3615  3615 D CAR.SERVICE: Connecting to CarCallService...
,03-23 17:54:27.727  3615  3615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-23 17:54:27.727  3615  3615 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-23 17:54:27.733  3615  3615 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-23 17:54:27.737   763  1329 I ActivityManager: Killing 3052:com.android.settings/1000 (adj 15): empty #17
,03-23 17:54:27.744   763   867 D WifiService: Client connection lost with reason: 4
,03-23 17:54:27.829  1659  1728 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-23 17:54:27.829  1659  1728 I qtaguid : Untagging socket 38 failed errno=-22
03-23 17:54:27.829  1659  1728 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-23 17:54:27.849  3615  3615 D CAR.TEL.Service: Creating a new CarCallService.
03-23 17:54:27.850  3615  3615 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-23 17:54:27.852   763   779 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-23 17:54:27.853  3615  3615 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@855e10b
,03-23 17:54:27.853   763  1269 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-23 17:54:27.855  3615  3615 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-23 17:54:27.855  3615  3615 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-23 17:54:27.938  3615  3630 D CAR.SERVICE: Package validated; name: com.android.vending
,03-23 17:54:28.324  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:28.817  1659  1729 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-23 17:54:28.817  1659  1729 I qtaguid : Untagging socket 38 failed errno=-22
03-23 17:54:28.817  1659  1729 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-23 17:54:28.892  1659  1659 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler.b(99): Scheduling auto-update check using JobScheduler.
,03-23 17:54:28.900  1659  1659 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-23 17:54:28.944  1514  1625 D DeviceConnectionService: client connected with version: 8298000
,03-23 17:54:28.963  1659  1659 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-23 17:54:28.964  1659  1659 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-23 17:54:30.206  3502  3580 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-23 17:54:30.206  3502  3580 I jxcore-log: 
03-23 17:54:30.208  3502  3580 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-23 17:54:30.208  3502  3580 I jxcore-log: 
,03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-23 17:54:30.211  3502  3580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-23 17:54:30.213  3502  3580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-23 17:54:30.214  3502  3580 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-23 17:54:30.214  3502  3580 I jxcore-log: 
03-23 17:54:30.215  3502  3580 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-23 17:54:30.215  3502  3580 I jxcore-log: 
,03-23 17:54:30.739  3502  3580 I jxcore-log: Unit Test app is loaded
03-23 17:54:30.739  3502  3580 I jxcore-log: 
,03-23 17:54:30.745  3502  3502 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-23 17:54:30.748  3502  3580 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-23 17:54:30.748  3502  3580 I jxcore-log: 
,03-23 17:54:30.756  3502  3580 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-23 17:54:30.759  3502  3580 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-23 17:54:30.759  3502  3580 I jxcore-log: 
,03-23 17:54:30.766  3502  3502 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-23 17:54:30.768  3502  3580 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-23 17:54:30.768  3502  3580 I jxcore-log:   bluetooth: 'on',
03-23 17:54:30.768  3502  3580 I jxcore-log:   wifi: 'on',
03-23 17:54:30.768  3502  3580 I jxcore-log:   cellular: 'doNotCare',
03-23 17:54:30.768  3502  3580 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-23 17:54:30.768  3502  3580 I jxcore-log: 
,03-23 17:54:30.768  3502  3580 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-23 17:54:30.768  3502  3580 I jxcore-log: 
,03-23 17:54:31.015  3673  3673 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-23 17:54:31.017  3673  3673 D AndroidRuntime: CheckJNI is OFF
,03-23 17:54:31.107  3673  3673 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-23 17:54:31.112   763   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-23 17:54:31.113   763   831 I ActivityManager: Killing 3502:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-23 17:54:31.151   763  1188 I WindowState: WIN DEATH: Window{2322b6c u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-23 17:54:31.152   763  1329 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2f89eef4)
03-23 17:54:31.152   763   867 D WifiService: Client connection lost with reason: 4
03-23 17:54:31.152   763   868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-23 17:54:31.153   763   868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-23 17:54:31.170   763   842 W PackageSettings: Skipping PackageSetting{193d1ffc com.example.hello/10116} due to missing metadata
,03-23 17:54:31.234   763   831 W ActivityManager: Force removing ActivityRecord{297e1161 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-23 17:54:31.239   763  1332 W ActivityManager: Spurious death for ProcessRecord{941461d 3502:com.test.thalitest/u0a49}, curProc for 3502: null
03-23 17:54:31.239   763   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-23 17:54:31.275  1415  1415 I art     : Explicit concurrent mark sweep GC freed 4187(324KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 21MB/29MB, paused 599us total 32.357ms
,03-23 17:54:31.288  1553  1553 I art     : Explicit concurrent mark sweep GC freed 4163(180KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 1.124ms total 25.640ms
,03-23 17:54:31.313   906   906 I art     : Explicit concurrent mark sweep GC freed 6869(319KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 907us total 29.927ms
,03-23 17:54:31.315   763   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-23 17:54:31.318  1110  1110 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-23 17:54:31.322   763   850 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-23 17:54:31.323  1514  1628 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-23 17:54:31.330  1110  3697 I Keyboard.Facilitator.DecoderInitializer: run()
,03-23 17:54:31.335  1367  3698 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-23 17:54:31.336  1110  3697 I Decoder : createOrResetDecoder
,03-23 17:54:31.382   763   763 I art     : Explicit concurrent mark sweep GC freed 26976(1581KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 6.212ms total 89.206ms
,03-23 17:54:31.383   763   842 I art     : WaitForGcToComplete blocked for 36.000ms for cause Explicit
,03-23 17:54:31.391   763  1224 I ActivityManager: Start proc 3704:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-23 17:54:31.399   206   206 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 213us total 11.795ms
,03-23 17:54:31.409   206   206 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 209us total 9.289ms
,03-23 17:54:31.419   206   206 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 204us total 9.307ms
,03-23 17:54:31.432  3704  3704 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-23 17:54:31.442  1553  3725 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-23 17:54:31.442  1553  3725 D AccountUtils: Clearing selected account for com.test.thalitest
,03-23 17:54:31.457  1553  3725 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-23 17:54:31.459  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-23 17:54:31.459  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-23 17:54:31.496   763   763 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-23 17:54:31.496   763   763 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-23 17:54:31.499  1553  3730 W BaseAppContext: Using Auth Proxy for data requests.
,03-23 17:54:31.509  1553  3730 W BaseAppContext: Using Auth Proxy for data requests.
,03-23 17:54:31.517   763  1269 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3502 uid 10049
,03-23 17:54:31.519  1110  1110 I Keyboard.Facilitator: onFinishInput()
,03-23 17:54:31.530  1553  3725 I GMPM-SVC: App measurement is starting up, version: 8703
03-23 17:54:31.530  1553  3725 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-23 17:54:31.533  1415  3734 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-23 17:54:31.560  1415  1415 W LocationOracle: Best location was null
03-23 17:54:31.561  1415  1415 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-23 17:54:31.576  1415  3742 I MicroRecognitionRunner: Starting detection.
,03-23 17:54:31.577  1415  3743 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@3e380c80
,03-23 17:54:31.584   194  3745 I AudioFlinger: AudioFlinger's thread 0xb4424000 ready to run
,03-23 17:54:31.586  1415  3743 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@3e380c80
,03-23 17:54:31.596   194  3745 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-23 17:54:31.596   194  3745 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-23 17:54:31.596   194  3745 D         : Failed to fetch the lookup information of the device 0000003E 
03-23 17:54:31.596   194  3745 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-23 17:54:31.596   194  3745 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-23 17:54:31.597   763   763 I ActivityManager: Start proc 3747:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-23 17:54:31.599   194  3745 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-23 17:54:31.605  1553  1629 I Icing   : doRemovePackageData com.test.thalitest
,03-23 17:54:31.628  1553  3725 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-23 17:54:31.651   763  1332 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-23 17:54:31.654   763   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-23 17:54:31.654   763   868 D ConnectivityService: apparently satisfied.  currentScore=60
03-23 17:54:31.654  1553  3769 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-23 17:54:31.658   763   842 I art     : Explicit concurrent mark sweep GC freed 16601(1252KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 5.142ms total 269.611ms
,03-23 17:54:31.675  1553  3770 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-23 17:54:31.675  1553  3770 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-23 17:54:31.676  1553  3770 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-23 17:54:31.676  1553  3770 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-23 17:54:31.679  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.683  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.683  1553  3770 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,03-23 17:54:31.684  1553  3770 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-23 17:54:31.684  1553  3770 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-23 17:54:31.687  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.691  1415  1415 I MicroDetectionWorker: onReady
,03-23 17:54:31.695  1553  3770 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-23 17:54:31.695  1553  3770 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-23 17:54:31.698  1553  3770 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-23 17:54:31.698  1553  3770 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-23 17:54:31.699  1553  3770 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-23 17:54:31.699  1553  3770 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-23 17:54:31.708  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.734  1280  1451 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-23 17:54:31.741  1415  3734 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
,03-23 17:54:31.745  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.760  1514  1613 W GCoreFlp: No location to return for getLastLocation()
,03-23 17:54:31.779  1110  3697 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-23 17:54:31.790  3673  3673 I art     : System.exit called, status: 0
03-23 17:54:31.790  3673  3673 I AndroidRuntime: VM exiting with result code 0.
,03-23 17:54:31.801  1110  3697 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-23 17:54:31.803  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-23 17:54:31.803  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-23 17:54:31.805  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-23 17:54:31.805  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-23 17:54:31.805  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,03-23 17:54:31.805  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-23 17:54:31.806  1110  3697 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-23 17:54:31.806  1110  3697 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-23 17:54:31.806  1110  3697 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-23 17:54:31.807  1110  3697 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-23 17:54:31.807  1110  3697 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-23 17:54:31.807  1110  3697 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-23 17:54:31.817   763  1269 I ActivityManager: Start proc 3777:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-23 17:54:31.839   763   842 I ActivityManager: Start proc 3795:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-23 17:54:31.845   763  1332 I ActivityManager: Killing 2753:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-23 17:54:31.881   763  1329 I ActivityManager: Killing 3138:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-23 17:54:31.900  1659  3816 I Finsky  : [145] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-23 17:54:31.905   763  1263 I ActivityManager: Killing 2695:com.google.android.calendar/u0a28 (adj 15): empty #17
03-23 17:54:31.905  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-23 17:54:31.944  3777  3777 D ExternalStorage: After updating volumes, found 1 active roots
,03-23 17:54:31.967  1415  1415 E LocationReceiver: Received bad location: null
,03-23 17:54:31.969  1553  3729 W DriveInitializer: Awaiting to be initialized
03-23 17:54:31.970  1553  3818 W DriveInitializer: Background init thread started
,03-23 17:54:31.972  1553  3818 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,03-23 17:54:31.975  1553  3818 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-23 17:54:31.975  1553  3818 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-23 17:54:31.975  1553  3818 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-23 17:54:31.975  1553  3818 W DriveInitializer: Background init thread ended
03-23 17:54:31.975  1553  3729 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-23 17:54:31.976  1553  3729 E DriveAsyncService: disk I/O error (code 3850)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-23 17:54:31.976  1553  3729 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-23 17:54:31.982  1553  3818 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-23 17:54:31.982  1553  3818 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-23 17:54:31.982  1553  3818 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-23 17:54:31.982  1553  3818 I GCore-Chimera-Crash: ==
03-23 17:54:31.982  1553  3818 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-23 17:54:31.982  1553  3818 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-23 17:54:31.982  1553  3818 E AndroidRuntime: Process: com.google.android.gms, PID: 1553
03-23 17:54:31.982  1553  3818 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-23 17:54:31.982  1553  3818 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-23 17:54:31.984  3070  3096 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-23 17:54:31.988  3070  3096 E AndroidRuntime: FATAL EXCEPTION: IcingNotificationHandlerThread
03-23 17:54:31.988  3070  3096 E AndroidRuntime: Process: com.google.android.music:main, PID: 3070
03-23 17:54:31.988  3070  3096 E AndroidRuntime: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.executeWithConnection(AppDataSearchDbOpenHelperBase.java:355)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.onTableChanged(AppDataSearchDbOpenHelperBase.java:273)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.music.search.WriteTxnHandler$1.run(WriteTxnHandler.java:32)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:86)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:687)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase$1.call(AppDataSearchDbOpenHelperBase.java:256)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase$1.call(AppDataSearchDbOpenHelperBase.java:237)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.executeWithConnection(AppDataSearchDbOpenHelperBase.java:353)
03-23 17:54:31.988  3070  3096 E AndroidRuntime: 	... 7 more
03-23 17:54:31.991   763   831 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-23 17:54:31.991   763   831 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-23 17:54:31.994   763  3820 E DropBoxManagerService: Can't write: system_app_crash
03-23 17:54:31.994   763  3820 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-23 17:54:31.994   763  3820 E DropBoxManagerService: 	... 5 more
03-23 17:54:32.011   763  3821 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-23 17:54:32.012   763   831 D Atlas   : Validating map...
,03-23 17:54:32.019   763  3822 E DropBoxManagerService: Can't write: system_app_crash
03-23 17:54:32.019   763  3822 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-23 17:54:32.019   763  3822 E DropBoxManagerService: 	... 5 more
03-23 17:54:32.048  1280  1502 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-23 17:54:32.048  1280  1502 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-23 17:54:32.068   177   177 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-23 17:54:32.068   177   177 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,03-23 17:54:32.068   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-23 17:54:32.068   177   177 E qdoverlay: MdpData failed to play
03-23 17:54:32.068   177   177 E qdoverlay: == Dump MdpData start ==
03-23 17:54:32.068   177   177 E qdoverlay: == Dump OvFD fd=54 path=/dev/graphics/fb0 start/end ==
03-23 17:54:32.068   177   177 E qdoverlay: mOvData msmfb_overlay_data id=64
03-23 17:54:32.068   177   177 E qdoverlay: data msmfb_data offset=0 memid=64 id=0 flags=0x0 priv=0
03-23 17:54:32.068   177   177 E qdoverlay: == Dump MdpData end ==
03-23 17:54:32.068   177   177 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-23 17:54:32.068   177   177 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
03-23 17:54:32.068   177   177 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-23 17:54:32.068   177   177 E qdhwcomposer: hwc_set_primary: display commit fail!
,03-23 17:54:32.071   763  3821 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-23 17:54:32.072   763  3821 I OpenGLRenderer: Initialized EGL, version 1.4
,03-23 17:54:32.075   763  3821 D OpenGLRenderer: Enabling debug mode 0
,03-23 17:54:32.101   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-23 17:54:32.101   177   177 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-23 17:54:32.101   177   177 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-23 17:54:32.101   177   177 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-23 17:54:32.101   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-23 17:54:32.101   177   177 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-23 17:54:32.101   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: Ctrl commit failed set overlay
,03-23 17:54:32.101   177   177 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-23 17:54:32.101   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-23 17:54:32.101   177   177 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-23 17:54:32.101   177   177 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-23 17:54:32.101   177   177 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-23 17:54:32.101   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-23 17:54:32.101   177   177 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-23 17:54:32.101   177   177 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-23 17:54:32.101   177   177 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-23 17:54:32.101   177   177 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
,03-23 17:54:32.101   177   177 E qdoverlay: Ctrl commit failed set overlay
03-23 17:54:32.102   177   177 E qdhwcomposer: configure: commit fails
03-23 17:54:32.102   177   177 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-23 17:54:32.102   177   177 E qdoverlay: MdpCtrl close error in unset

```
