#### Test 636801181df08af_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-22 09:05:13.753  1038  1038 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,03-22 09:05:13.938  1646  1714 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
03-22 09:05:13.940  1646  1646 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
03-22 09:05:14.005  3373  3373 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-22 09:05:14.007  3373  3373 D AndroidRuntime: CheckJNI is OFF
03-22 09:05:14.065   762   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-22 09:05:14.090  2315  2315 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
03-22 09:05:14.112  3373  3373 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-22 09:05:14.115   762  1245 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-22 09:05:14.118  1572  3402 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-22 09:05:14.118  1572  3402 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
03-22 09:05:14.121   762  1245 V WindowManager: addAppToken: AppWindowToken{367591bf token=Token{aab7bde ActivityRecord{4424f19 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-22 09:05:14.126  3373  3373 D AndroidRuntime: Shutting down VM
03-22 09:05:14.128  1395  1413 W SearchService: Abort, client detached.
03-22 09:05:14.133   762   836 V WindowManager: Adding window Window{332d988d u0 Starting com.test.thalitest} at 2 of 7 (after Window{39013668 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-22 09:05:14.136  1572  3402 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-22 09:05:14.176   762   762 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-22 09:05:14.176   762   762 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-22 09:05:14.191   762  1189 I ActivityManager: Start proc 3413:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-22 09:05:14.197  2315  3403 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
03-22 09:05:14.200  1572  1616 I Icing   : updateResources: need to parse f{com.google.android.gms}
03-22 09:05:14.202  1395  1544 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-22 09:05:14.223   762   762 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-22 09:05:14.234   762   762 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-22 09:05:14.234   762   762 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2390894c
03-22 09:05:14.240  2315  2315 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
03-22 09:05:14.241  1395  1570 I DeviceStateChecker: DeviceStateChecker cancelled
03-22 09:05:14.241  1395  1395 I MicroDetector: Keeping mic open: false
03-22 09:05:14.241  1395  1395 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@1076b8bf
03-22 09:05:14.261  1546  1546 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-22 09:05:14.275  3413  3413 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-22 09:05:14.284   191  1593 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-22 09:05:14.284   191  1593 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-22 09:05:14.286  3413  3413 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 9912-9913)
03-22 09:05:14.286  3413  3413 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-22 09:05:14.289  1395  1582 I MicroRecognitionRunner: Detection finished
03-22 09:05:14.292  1395  1569 I MicroRecognitionRunner: Stopping hotword detection.
03-22 09:05:14.299  3413  3413 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f7cb8ab}
03-22 09:05:14.300  3413  3413 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-22 09:05:14.300  3413  3413 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-22 09:05:14.306  1395  3440 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-22 09:05:14.310  3413  3413 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-22 09:05:14.335  3413  3413 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-22 09:05:14.342  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:14.349  1395  3440 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 42 ms] updated apps [took 42 ms] 
,03-22 09:05:14.379   762   835 D BluetoothManagerService: Message: 20
,03-22 09:05:14.380   762   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10ae88f1:true
,03-22 09:05:14.388  3413  3413 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-22 09:05:14.388  3413  3413 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-22 09:05:14.432  3413  3413 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-22 09:05:14.432  3413  3413 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-22 09:05:14.443  3413  3413 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-22 09:05:14.444  3413  3413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:05:14.449  3413  3413 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-22 09:05:14.450  3413  3413 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-22 09:05:14.450  3413  3413 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-22 09:05:14.451  3413  3413 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-22 09:05:14.456  3413  3413 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-22 09:05:14.460  3413  3413 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-22 09:05:14.464  3413  3413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-22 09:05:14.464  3413  3413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:05:14.481  3413  3466 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-22 09:05:14.486  3413  3413 D Atlas   : Validating map...
,03-22 09:05:14.490   762  1167 V WindowManager: Adding window Window{2bd87874 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{332d988d u0 Starting com.test.thalitest})
,03-22 09:05:14.496   762   866 D WifiService: New client listening to asynchronous messages
,03-22 09:05:14.504   762  1188 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-22 09:05:14.504   762   867 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-22 09:05:14.504   762   867 D ConnectivityService: apparently satisfied.  currentScore=60
,03-22 09:05:14.504  3413  3469 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-22 09:05:14.521  3413  3466 I OpenGLRenderer: Initialized EGL, version 1.4
,03-22 09:05:14.524  3413  3466 D OpenGLRenderer: Enabling debug mode 0
,03-22 09:05:14.547  3413  3413 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-22 09:05:14.549  1079  1079 I Keyboard.Facilitator: onFinishInput()
03-22 09:05:14.549  3413  3472 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-22 09:05:14.669   178   178 D SurfaceFlinger: shader cache generated - 24 shaders in 132.605316 ms
,03-22 09:05:14.691   762   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +537ms
,03-22 09:05:14.694  3413  3413 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-22 09:05:14.695  3413  3413 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3413
,03-22 09:05:14.845  3413  3413 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-22 09:05:14.956  3413  3484 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362778496
,03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-22 09:05:14.963  3413  3484 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36a41275 added. We now have 1 listener(s)
,03-22 09:05:14.967   762  1189 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-22 09:05:14.969  3413  3484 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-22 09:05:14.971  3413  3484 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-22 09:05:14.972  3413  3484 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-22 09:05:14.972  3413  3484 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-22 09:05:14.980  3413  3484 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113060f1 added. We now have 1 listener(s)
03-22 09:05:14.980  3413  3484 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-22 09:05:14.983  3413  3484 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-22 09:05:14.987  3413  3484 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-22 09:05:14.987  3413  3484 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-22 09:05:14.992  3413  3484 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-22 09:05:14.993   762  1188 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-22 09:05:14.995  3413  3484 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 09:05:15.000  3413  3484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-22 09:05:15.001  3413  3484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-22 09:05:15.001  3413  3484 D io.jxcore.node.ConnectivityMonitor: start: OK
03-22 09:05:15.001  3413  3484 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-22 09:05:15.018  3413  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-22 09:05:15.020  3413  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-22 09:05:15.041  3413  3413 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-22 09:05:15.414  1572  1616 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,03-22 09:05:15.480  1572  1616 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,03-22 09:05:15.728  3413  3486 W jxcore-log: Initializing JXcore engine
,03-22 09:05:15.728  3413  3486 W jxcore-log: JXcore engine is ready
,03-22 09:05:15.754  3486  3486 W Thread-327: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[6551]" dev="sockfs" ino=6551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-22 09:05:15.754  3486  3486 W Thread-327: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-22 09:05:15.754  3486  3486 W Thread-327: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[6608]" dev="sockfs" ino=6608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-22 09:05:15.764  3486  3486 W Thread-327: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[14312]" dev="sockfs" ino=14312 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-22 09:05:15.781  3413  3486 W jxcore-log: Starting JXcore engine
,03-22 09:05:15.875  3413  3486 W jxcore-log: Platform android
03-22 09:05:15.875  3413  3486 W jxcore-log: 
,03-22 09:05:15.875  3413  3486 W jxcore-log: Process ARCH arm
03-22 09:05:15.875  3413  3486 W jxcore-log: 
,03-22 09:05:16.082  3413  3486 I jxcore-log: JXcore Cordova bridge is ready!
03-22 09:05:16.082  3413  3486 I jxcore-log: 
03-22 09:05:16.082  3413  3486 W jxcore-log: JXcore engine is started
,03-22 09:05:16.091  3413  3484 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-22 09:05:16.092  3413  3413 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-22 09:05:19.281  2315  2315 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,03-22 09:05:19.284   762  1173 I ActivityManager: Killing 3055:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
,03-22 09:05:20.150  1572  1584 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-22 09:05:23.616   762  3412 I ActivityManager: Start proc 3510:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,03-22 09:05:23.672  3510  3510 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-22 09:05:23.723  3510  3510 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@23c47afa(com.android.providers.calendar.CalendarProvider2@2f7cb8ab)
,03-22 09:05:23.731   762  3412 I ActivityManager: Killing 2477:com.google.android.deskclock/u0a33 (adj 15): empty #17
,03-22 09:05:23.827   762  1173 I ActivityManager: Killing 2503:com.google.android.keep/u0a52 (adj 15): empty #17
,03-22 09:05:24.304  1646  1646 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-22 09:05:24.405   762   845 I art     : Explicit concurrent mark sweep GC freed 30546(1513KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.622ms total 84.103ms
,03-22 09:05:24.415  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:24.421  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:24.422  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:24.863  3510  3510 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-22 09:05:24.863  3510  3510 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-22 09:05:25.068  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:25.209  3413  3486 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-22 09:05:25.209  3413  3486 I jxcore-log: 
,03-22 09:05:25.211  3413  3486 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-22 09:05:25.211  3413  3486 I jxcore-log: 
,03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 09:05:25.214  3413  3486 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-22 09:05:25.215  3413  3486 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-22 09:05:25.217  3413  3486 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-22 09:05:25.217  3413  3486 I jxcore-log: 
,03-22 09:05:25.218  3413  3486 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-22 09:05:25.218  3413  3486 I jxcore-log: 
,03-22 09:05:25.288  1646  1697 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-22 09:05:25.288  1646  1697 I qtaguid : Untagging socket 37 failed errno=-22
03-22 09:05:25.288  1646  1697 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-22 09:05:25.290  1646  1646 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-22 09:05:25.291  1546  1631 I art     : Explicit concurrent mark sweep GC freed 48355(3MB) AllocSpace objects, 51(816KB) LOS objects, 40% free, 22MB/37MB, paused 1.221ms total 39.248ms
,03-22 09:05:25.352   762  1188 I ActivityManager: Start proc 3569:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-22 09:05:25.355  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:25.388  3569  3569 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 09:05:25.389  3569  3569 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-22 09:05:25.414  3569  3569 I MultiDex: VM with version 2.1.0 has multidex support
03-22 09:05:25.414  3569  3569 I MultiDex: install
,03-22 09:05:25.414  3569  3569 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-22 09:05:25.432  3569  3569 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-22 09:05:25.478  3569  3569 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-22 09:05:25.487  3569  3569 D ChimeraCfgMgr: Reading stored module config
,03-22 09:05:25.496  1546  1546 D WearableService: callingUid 10007, callindPid: 1546
,03-22 09:05:25.500  1546  1893 E MDM     : [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-22 09:05:25.503  1546  1546 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-22 09:05:25.504  1572  3590 D LocationInitializer: Restart initialization of location
,03-22 09:05:25.514  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:25.529  1546  1618 W GCoreFlp: No location to return for getLastLocation()
03-22 09:05:25.530  1546  3591 W FusedLocationProvider: location=null
,03-22 09:05:25.590  3569  3589 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-22 09:05:25.604  3569  3569 D CAR.SERVICE: Connecting to CarCallService...
,03-22 09:05:25.615  3569  3569 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-22 09:05:25.616  3569  3569 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-22 09:05:25.623  3569  3569 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-22 09:05:25.628  1646  1696 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-22 09:05:25.628  1646  1696 I qtaguid : Untagging socket 37 failed errno=-22
03-22 09:05:25.628  1646  1696 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-22 09:05:25.629  3569  3569 D CAR.TEL.Service: Creating a new CarCallService.
,03-22 09:05:25.631  3569  3569 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-22 09:05:25.632   762   777 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-22 09:05:25.632  3569  3569 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@13cdfc8
,03-22 09:05:25.633   762  1188 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-22 09:05:25.633  3569  3569 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-22 09:05:25.633  3569  3569 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-22 09:05:25.704  3569  3585 D CAR.SERVICE: Package validated; name: com.android.vending
,03-22 09:05:25.760  3413  3486 I jxcore-log: Unit Test app is loaded
03-22 09:05:25.760  3413  3486 I jxcore-log: 
,03-22 09:05:25.767  3413  3413 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-22 09:05:25.769  3413  3486 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-22 09:05:25.769  3413  3486 I jxcore-log: 
,03-22 09:05:25.775  3413  3486 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-22 09:05:25.776  3413  3486 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-22 09:05:25.776  3413  3486 I jxcore-log: 
,03-22 09:05:25.782  3413  3413 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-22 09:05:25.787  3413  3486 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-22 09:05:25.787  3413  3486 I jxcore-log:   bluetooth: 'on',
03-22 09:05:25.787  3413  3486 I jxcore-log:   wifi: 'on',
03-22 09:05:25.787  3413  3486 I jxcore-log:   cellular: 'doNotCare',
03-22 09:05:25.787  3413  3486 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-22 09:05:25.787  3413  3486 I jxcore-log: 
03-22 09:05:25.787  3413  3486 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-22 09:05:25.787  3413  3486 I jxcore-log: 
,03-22 09:05:25.999  3602  3602 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-22 09:05:26.002  3602  3602 D AndroidRuntime: CheckJNI is OFF
,03-22 09:05:26.093  3602  3602 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-22 09:05:26.100   762   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,03-22 09:05:26.100   762   831 I ActivityManager: Killing 3413:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-22 09:05:26.144   762   842 W PackageSettings: Skipping PackageSetting{3a9256e5 com.example.hello/10116} due to missing metadata
,03-22 09:05:26.162   762   866 D WifiService: Client connection lost with reason: 4
03-22 09:05:26.162   762  1189 I WindowState: WIN DEATH: Window{2bd87874 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-22 09:05:26.162   762  3407 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f47bee8)
03-22 09:05:26.163   762   867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-22 09:05:26.163   762   867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-22 09:05:26.312   762   831 W ActivityManager: Force removing ActivityRecord{4424f19 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-22 09:05:26.319   762  3412 W ActivityManager: Spurious death for ProcessRecord{1ff0f3a6 3413:com.test.thalitest/u0a49}, curProc for 3413: null
,03-22 09:05:26.322   762   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-22 09:05:26.324  1546  1546 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:05:26.349   762   849 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-22 09:05:26.354   762   883 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-22 09:05:26.355  1546  1635 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-22 09:05:26.357  1079  1079 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-22 09:05:26.367  1079  3621 I Keyboard.Facilitator.DecoderInitializer: run()
,03-22 09:05:26.400  1572  1572 I art     : Explicit concurrent mark sweep GC freed 7540(347KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 23MB/38MB, paused 1.188ms total 74.132ms
,03-22 09:05:26.407   904   904 I art     : Explicit concurrent mark sweep GC freed 6994(323KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 14.594ms total 66.906ms
,03-22 09:05:26.416  1079  3621 I Decoder : createOrResetDecoder
,03-22 09:05:26.418   762   762 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-22 09:05:26.418   762   762 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-22 09:05:26.446  1301  3623 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-22 09:05:26.457   762   925 I ActivityManager: Start proc 3630:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-22 09:05:26.464  1395  1395 I art     : Explicit concurrent mark sweep GC freed 4078(327KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 692us total 138.025ms
,03-22 09:05:26.472  1546  1546 I ConfigService: onCreate
,03-22 09:05:26.490   762  3407 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3413 uid 10049
,03-22 09:05:26.491  1079  1079 I Keyboard.Facilitator: onFinishInput()
,03-22 09:05:26.516  3630  3630 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-22 09:05:26.533  1572  3653 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-22 09:05:26.533  1572  3653 D AccountUtils: Clearing selected account for com.test.thalitest
,03-22 09:05:26.535  1395  1395 W LocationOracle: Best location was null
03-22 09:05:26.535  1395  1395 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-22 09:05:26.536  1198  1198 I art     : Explicit concurrent mark sweep GC freed 3923(218KB) AllocSpace objects, 6(577KB) LOS objects, 38% free, 25MB/41MB, paused 2.575ms total 28.151ms
,03-22 09:05:26.549  1079  3621 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-22 09:05:26.549  1395  3658 I MicroRecognitionRunner: Starting detection.
,03-22 09:05:26.550  1395  3659 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@6e792ff
,03-22 09:05:26.555  1572  3653 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-22 09:05:26.556   191  3661 I AudioFlinger: AudioFlinger's thread 0xb442f000 ready to run
,03-22 09:05:26.564  1546  1546 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-22 09:05:26.564  1546  1546 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-22 09:05:26.567  1395  3659 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@6e792ff
,03-22 09:05:26.576   191  3661 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-22 09:05:26.576   191  3661 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-22 09:05:26.576   191  3661 D         : Failed to fetch the lookup information of the device 0000003E 
03-22 09:05:26.576   191  3661 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-22 09:05:26.576   191  3661 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-22 09:05:26.585   191  3661 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-22 09:05:26.587  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.590  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.592  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.604  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.619  1572  3663 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 09:05:26.628  1079  3621 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-22 09:05:26.629  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-22 09:05:26.629  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-22 09:05:26.638  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-22 09:05:26.638  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-22 09:05:26.639  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-22 09:05:26.639  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-22 09:05:26.640  1079  3621 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-22 09:05:26.640  1079  3621 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-22 09:05:26.640  1079  3621 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-22 09:05:26.640  1079  3621 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-22 09:05:26.640  1079  3621 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-22 09:05:26.640  1079  3621 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-22 09:05:26.641   762   842 I art     : Explicit concurrent mark sweep GC freed 33730(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 2.504ms total 221.841ms
,03-22 09:05:26.645  1395  3668 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
03-22 09:05:26.646  1572  3663 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 09:05:26.654  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.656  1572  3653 I GMPM-SVC: App measurement is starting up, version: 8703
03-22 09:05:26.656  1572  3653 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-22 09:05:26.674   762   762 I ActivityManager: Start proc 3670:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-22 09:05:26.678  1395  1395 I MicroDetectionWorker: onReady
,03-22 09:05:26.714  1198  1418 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-22 09:05:26.721  1546  1618 W GCoreFlp: No location to return for getLastLocation()
,03-22 09:05:26.738  3602  3602 I art     : System.exit called, status: 0
03-22 09:05:26.738  3602  3602 I AndroidRuntime: VM exiting with result code 0.
,03-22 09:05:26.756  1572  3653 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-22 09:05:26.778  1572  3697 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-22 09:05:26.778  1572  3697 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-22 09:05:26.778  1572  3697 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-22 09:05:26.779  1572  3697 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-22 09:05:26.781  1572  1616 I Icing   : doRemovePackageData com.test.thalitest
,03-22 09:05:26.783   762  1245 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-22 09:05:26.783   762   867 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-22 09:05:26.783   762   867 D ConnectivityService: apparently satisfied.  currentScore=60
,03-22 09:05:26.785  1572  3699 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-22 09:05:26.786  1395  3668 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 141 ms] updated apps [took 141 ms] 
,03-22 09:05:26.789  1572  3697 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-22 09:05:26.789  1572  3697 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-22 09:05:26.789  1572  3697 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-22 09:05:26.860   762  1245 I ActivityManager: Start proc 3703:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-22 09:05:26.878  1572  3697 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-22 09:05:26.878  1572  3697 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-22 09:05:26.881  1572  3662 W DriveInitializer: Awaiting to be initialized
,03-22 09:05:26.882  1572  3722 W DriveInitializer: Background init thread started
,03-22 09:05:26.882  1572  3697 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-22 09:05:26.883  1572  3697 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-22 09:05:26.883  1572  3697 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-22 09:05:26.883  1572  3697 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-22 09:05:26.887   762  3412 I ActivityManager: Killing 3100:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-22 09:05:26.894  3703  3703 D ExternalStorage: After updating volumes, found 1 active roots
,03-22 09:05:26.938  1572  3722 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-22 09:05:26.938  1572  3722 W DriveInitializer: Background init thread ended
03-22 09:05:26.939  1572  3662 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-22 09:05:26.942  1572  3662 E DriveAsyncService: disk I/O error (code 3850)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-22 09:05:26.942  1572  3662 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-22 09:05:26.943  1572  3722 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-22 09:05:26.943  1572  3722 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-22 09:05:26.943  1572  3722 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-22 09:05:26.943  1572  3722 I GCore-Chimera-Crash: ==
03-22 09:05:26.943  1572  3722 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-22 09:05:26.943  1572  3722 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-22 09:05:26.943  1572  3722 E AndroidRuntime: Process: com.google.android.gms, PID: 1572
03-22 09:05:26.943  1572  3722 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.e(:com.google.android.gms:858)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.events.av.b(:com.google.android.gms:192)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.events.av.a(:com.google.android.gms:158)
03-22 09:05:26.943  1572  3722 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:65)
,03-22 09:05:26.950   762  3728 E DropBoxManagerService: Can't write: system_app_crash
03-22 09:05:26.950   762  3728 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-22 09:05:26.950   762  3728 E DropBoxManagerService: 	... 5 more
03-22 09:05:26.953   762   831 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 09:05:26.953   762   831 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-22 09:05:26.968   762  3729 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-22 09:05:26.968   762   831 D Atlas   : Validating map...
03-22 09:05:26.976  1395  1395 E LocationReceiver: Received bad location: null
,03-22 09:05:27.001   762  3729 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-22 09:05:27.001   762  3729 I OpenGLRenderer: Initialized EGL, version 1.4
,03-22 09:05:27.005   762  3729 D OpenGLRenderer: Enabling debug mode 0
,03-22 09:05:27.011  1198  1514 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml to backup file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/reflection_multi_process.xml.bak
,03-22 09:05:27.011  1198  1496 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-22 09:05:27.011  1198  1496 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-22 09:05:27.016  3670  3702 D Documents: Update found 7 roots in 196ms
,03-22 09:05:27.025  3670  3723 D Documents: Update found 7 roots in 129ms
,03-22 09:05:27.051  1646  1697 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-22 09:05:27.051  1646  1697 I qtaguid : Untagging socket 37 failed errno=-22
03-22 09:05:27.051  1646  1697 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22

```
