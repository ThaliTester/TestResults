#### Test 64941069b7d3db0_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-01 15:26:15.522  1550  2343 I CheckinService: Done disabling old GoogleServicesFramework version
,04-01 15:26:16.371  3520  3520 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 15:26:16.375  3520  3520 D AndroidRuntime: CheckJNI is OFF
04-01 15:26:16.488  3520  3520 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-01 15:26:16.492   754  1245 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 15:26:16.503   754  1245 V WindowManager: addAppToken: AppWindowToken{360e5ede token=Token{33a6de19 ActivityRecord{93f3960 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-01 15:26:16.507  1375  1395 W SearchService: Abort, client detached.
04-01 15:26:16.510  3520  3520 D AndroidRuntime: Shutting down VM
04-01 15:26:16.515   754   836 V WindowManager: Adding window Window{3ad3751 u0 Starting com.test.thalitest} at 2 of 7 (after Window{c26b8d9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 15:26:16.532   754   770 I ActivityManager: Start proc 3541:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-01 15:26:16.540   200   200 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 208us total 9.157ms
04-01 15:26:16.550   200   200 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 196us total 8.537ms
04-01 15:26:16.579  1375  1588 I DeviceStateChecker: DeviceStateChecker cancelled
04-01 15:26:16.586  1375  1375 I MicroDetector: Keeping mic open: false
04-01 15:26:16.586  1375  1375 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@29aa5e8e
04-01 15:26:16.600   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 195us total 48.782ms
04-01 15:26:16.645   189  1602 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 15:26:16.645   189  1602 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 15:26:16.650  1375  1599 I MicroRecognitionRunner: Detection finished
04-01 15:26:16.652  1375  1587 I MicroRecognitionRunner: Stopping hotword detection.
04-01 15:26:16.671  3541  3541 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-01 15:26:16.681  3541  3541 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8028-8029)
04-01 15:26:16.681  3541  3541 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 15:26:16.691  3541  3541 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f82ffeb}
04-01 15:26:16.691  3541  3541 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 15:26:16.692  3541  3541 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-01 15:26:16.700   754  3236 I ActivityManager: Killing 3027:com.google.android.deskclock/u0a33 (adj 15): empty #17
04-01 15:26:16.712  3541  3541 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-01 15:26:16.727  3541  3541 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 15:26:16.768   754   835 D BluetoothManagerService: Message: 20
,04-01 15:26:16.768   754   835 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aed05a7:true
,04-01 15:26:16.774  3541  3541 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-01 15:26:16.774  3541  3541 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-01 15:26:16.813  3541  3541 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-01 15:26:16.813  3541  3541 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-01 15:26:16.825  3541  3541 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-01 15:26:16.831  3541  3541 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 15:26:16.832  3541  3541 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-01 15:26:16.841  3541  3541 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-01 15:26:16.861  3541  3599 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-01 15:26:16.866  3541  3541 D Atlas   : Validating map...
,04-01 15:26:16.870   754  1187 V WindowManager: Adding window Window{29c7d4a2 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3ad3751 u0 Starting com.test.thalitest})
,04-01 15:26:16.877   754   860 D WifiService: New client listening to asynchronous messages
,04-01 15:26:16.887   754   771 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 15:26:16.888   754   867 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,04-01 15:26:16.888   754   867 D ConnectivityService: apparently satisfied.  currentScore=60
,04-01 15:26:16.889  3541  3601 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 15:26:16.917  3541  3599 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 15:26:16.921  3541  3599 D OpenGLRenderer: Enabling debug mode 0
,04-01 15:26:16.964   754   836 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +455ms
,04-01 15:26:16.970  1083  1083 I Keyboard.Facilitator: onFinishInput()
,04-01 15:26:17.012  3541  3609 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-01 15:26:17.043  3541  3541 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3541
,04-01 15:26:17.187   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-01 15:26:17.202  3541  3541 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 15:26:17.263  3541  3614 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362830208
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 15:26:17.265  3541  3614 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20163e4a added. We now have 1 listener(s)
04-01 15:26:17.265   754  1082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 15:26:17.267  3541  3614 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
04-01 15:26:17.268  3541  3614 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-01 15:26:17.268  3541  3614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-01 15:26:17.269  3541  3614 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 15:26:17.272  3541  3614 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169e8a31 added. We now have 1 listener(s)
04-01 15:26:17.272  3541  3614 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 15:26:17.274  3541  3614 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-01 15:26:17.276  3541  3614 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-01 15:26:17.276  3541  3614 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-01 15:26:17.278  3541  3614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
04-01 15:26:17.278   754  1296 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 15:26:17.279  3541  3614 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 15:26:17.282  3541  3614 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 15:26:17.282  3541  3614 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 15:26:17.282  3541  3614 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-01 15:26:17.283  3541  3614 I io.jxcore.node.LifeCycleMonitor: start: OK
04-01 15:26:17.284  3541  3541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 15:26:17.286  3541  3541 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 15:26:17.304  3541  3541 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 15:26:18.027  3541  3615 W jxcore-log: Initializing JXcore engine
04-01 15:26:18.027  3541  3615 W jxcore-log: JXcore engine is ready
,04-01 15:26:18.051  3615  3615 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8460]" dev="sockfs" ino=8460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 15:26:18.051  3615  3615 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,04-01 15:26:18.051  3615  3615 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[6568]" dev="sockfs" ino=6568 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 15:26:18.051  3615  3615 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[14792]" dev="sockfs" ino=14792 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-01 15:26:18.074  3541  3615 W jxcore-log: Starting JXcore engine
,04-01 15:26:18.152  3541  3615 W jxcore-log: Platform android
04-01 15:26:18.152  3541  3615 W jxcore-log: 
04-01 15:26:18.152  3541  3615 W jxcore-log: Process ARCH arm
04-01 15:26:18.152  3541  3615 W jxcore-log: 
,04-01 15:26:18.365  3541  3615 I jxcore-log: JXcore Cordova bridge is ready!
04-01 15:26:18.365  3541  3615 I jxcore-log: 
04-01 15:26:18.365  3541  3615 W jxcore-log: JXcore engine is started
,04-01 15:26:18.369  3541  3614 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 15:26:18.372  3541  3541 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 15:26:18.616   754   850 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 15:26:18.687   754   754 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
04-01 15:26:18.687   754   754 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,04-01 15:26:18.690   754   754 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,04-01 15:26:18.700   754   754 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,04-01 15:26:18.700   754   754 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@9f4c76b
,04-01 15:26:18.710  3318  3318 D Babel   : onCreate: Shutdown runnable posted in onCreate with a delay of 5000 ms.
,04-01 15:26:18.719  3318  3318 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 15:26:18.719  3318  3318 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 15:26:18.728  1550  3631 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,04-01 15:26:18.728  1550  3631 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,04-01 15:26:18.737  1550  3631 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,04-01 15:26:18.739  1550  1616 I Icing   : updateResources: need to parse f{com.google.android.gms}
,04-01 15:26:18.746  3318  3633 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,04-01 15:26:18.752  3318  3318 D Babel   : Idle: Shutdown runnable posted in release with a delay of 5000 ms.
,04-01 15:26:18.760  1375  3643 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,04-01 15:26:18.778  1375  3643 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 19 ms] updated apps [took 19 ms] 
,04-01 15:26:18.795  1509  1509 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,04-01 15:26:18.852  1509  1628 W GCoreFlp: No location to return for getLastLocation()
,04-01 15:26:18.899  1550  1550 I art     : Explicit concurrent mark sweep GC freed 71815(5MB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 23MB/31MB, paused 729us total 40.519ms
,04-01 15:26:18.913  1550  1561 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-01 15:26:19.942  1550  1616 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,04-01 15:26:19.984  1550  1616 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,04-01 15:26:20.134  3318  3353 W Babel   : aye TOOK TOO LONG! (15033ms > 10000ms)
,04-01 15:26:20.135  3318  3351 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,04-01 15:26:20.137   754  1296 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 15:26:20.139   754  1188 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 15:26:20.142  3318  3318 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-01 15:26:20.142  3318  3318 W Babel   : BAM#gBA: invalid account id: -1
,04-01 15:26:20.143  3318  3318 W Babel   : BAM#gBA: invalid account id: -1
,04-01 15:26:20.144  3318  3318 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-01 15:26:20.146   754   952 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 15:26:20.148   754  3236 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 15:26:20.231  3318  3361 W Babel   : aye TOOK TOO LONG! (15032ms > 10000ms)
,04-01 15:26:20.243  1650  1711 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 15:26:20.244  1650  1650 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 15:26:23.792  3318  3318 D Babel   : RefCountedService(com.google.android.apps.hangouts.requestwriter.RequestWriter) onDestroy (count=0, startId=1 stopped=true)
,04-01 15:26:25.352   754  1215 I ActivityManager: Killing 3083:com.android.providers.calendar/u0a1 (adj 15): empty #17
,04-01 15:26:25.784   754  1187 I ActivityManager: Killing 3112:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-01 15:26:26.682  1650  1650 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,04-01 15:26:26.711  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:26.719  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:26.721  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:27.367  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:27.487  1650  1696 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 15:26:27.487  1650  1696 I qtaguid : Untagging socket 37 failed errno=-22
04-01 15:26:27.487  1650  1696 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 15:26:27.490  1650  1650 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,04-01 15:26:27.532  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:27.596   754   754 I art     : Explicit concurrent mark sweep GC freed 30277(1469KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.179ms total 61.567ms
,04-01 15:26:27.621   754   952 I ActivityManager: Start proc 3719:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-01 15:26:27.649  3719  3719 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 15:26:27.649  3719  3719 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 15:26:27.674  3719  3719 I MultiDex: VM with version 2.1.0 has multidex support
04-01 15:26:27.674  3719  3719 I MultiDex: install
04-01 15:26:27.674  3719  3719 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 15:26:27.688  3719  3719 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-01 15:26:27.720  3719  3719 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 15:26:27.721  3541  3615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 15:26:27.721  3541  3615 I jxcore-log: 
,04-01 15:26:27.724  3541  3615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 15:26:27.724  3541  3615 I jxcore-log: 
,04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 15:26:27.727  3541  3615 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 15:26:27.730  3541  3615 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-01 15:26:27.731  3541  3615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 15:26:27.731  3541  3615 I jxcore-log: 
,04-01 15:26:27.733  3541  3615 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 15:26:27.733  3541  3615 I jxcore-log: 
,04-01 15:26:27.738  1509  1509 D WearableService: callingUid 10007, callindPid: 1509
,04-01 15:26:27.742  1509  1931 E MDM     : [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-01 15:26:27.743  3719  3719 D ChimeraCfgMgr: Reading stored module config
,04-01 15:26:27.746  1509  1509 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
04-01 15:26:27.747  1550  3747 D LocationInitializer: Restart initialization of location
,04-01 15:26:27.756  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:27.770  1509  1628 W GCoreFlp: No location to return for getLastLocation()
,04-01 15:26:27.771  1509  3748 W FusedLocationProvider: location=null
,04-01 15:26:27.840  3719  3746 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-01 15:26:27.851  3719  3719 D CAR.SERVICE: Connecting to CarCallService...
,04-01 15:26:27.861  3719  3719 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
04-01 15:26:27.862  3719  3719 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 15:26:27.869  3719  3719 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-01 15:26:27.871  1650  1695 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 15:26:27.871  1650  1695 I qtaguid : Untagging socket 37 failed errno=-22
04-01 15:26:27.871  1650  1695 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 15:26:27.873  3719  3719 D CAR.TEL.Service: Creating a new CarCallService.
,04-01 15:26:27.874  3719  3719 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-01 15:26:27.875   754  1223 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-01 15:26:27.877  3719  3719 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@39fef608
04-01 15:26:27.877   754  1245 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-01 15:26:27.878  3719  3719 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-01 15:26:27.878  3719  3719 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-01 15:26:27.952  3719  3741 D CAR.SERVICE: Package validated; name: com.android.vending
,04-01 15:26:28.269  3541  3615 I jxcore-log: Unit Test app is loaded
04-01 15:26:28.269  3541  3615 I jxcore-log: 
,04-01 15:26:28.275  3541  3541 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 15:26:28.277  3541  3615 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 15:26:28.277  3541  3615 I jxcore-log: 
04-01 15:26:28.280  3541  3615 I jxcore-log: My device name is: LGE-Nexus 5
04-01 15:26:28.280  3541  3615 I jxcore-log: 
,04-01 15:26:28.366  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:28.823  1650  1696 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 15:26:28.824  1650  1696 I qtaguid : Untagging socket 37 failed errno=-22
04-01 15:26:28.824  1650  1696 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 15:26:28.902  1650  1650 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,04-01 15:26:28.931  1509  1632 D DeviceConnectionService: client connected with version: 8298000
,04-01 15:26:28.945  1650  1650 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-01 15:26:28.946  1650  1650 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,04-01 15:26:30.385   754   831 I ActivityManager: Start proc 3767:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,04-01 15:26:30.419  3767  3767 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-01 15:26:30.440  3767  3767 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@36e6573a(com.android.providers.calendar.CalendarProvider2@3f82ffeb)
,04-01 15:26:30.456  3767  3785 E SQLiteLog: (284) automatic index on view_events(_id)
,04-01 15:26:30.480  1650  3786 I Finsky  : [145] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 15:26:30.485  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:26:31.535  3767  3767 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-01 15:26:31.535  3767  3767 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-01 15:26:32.059  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 15:26:32.059  3541  3615 I jxcore-log: 
,04-01 15:26:32.406  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 15:26:32.406  3541  3615 I jxcore-log: 
,04-01 15:26:32.417  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 15:26:32.417  3541  3615 I jxcore-log: 
04-01 15:26:32.420  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 15:26:32.420  3541  3615 I jxcore-log: 
,04-01 15:26:32.436  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 15:26:32.436  3541  3615 I jxcore-log: 
04-01 15:26:32.439  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 15:26:32.439  3541  3615 I jxcore-log: 
,04-01 15:26:33.011  3719  3719 D CAR.SERVICE: mConnectedToCar = false, abort
,04-01 15:26:33.028  3719  3719 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1db8f8f0 that was originally bound here
04-01 15:26:33.028  3719  3719 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1db8f8f0 that was originally bound here
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 15:26:33.028  3719  3719 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 15:26:33.033  3719  3719 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@25b00fab that was originally bound here
04-01 15:26:33.033  3719  3719 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@25b00fab that was originally bound here
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 15:26:33.033  3719  3719 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 15:26:33.035   754   952 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@a857e8d
,04-01 15:26:34.386  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 15:26:34.386  3541  3615 I jxcore-log: 
,04-01 15:26:34.407  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 15:26:34.407  3541  3615 I jxcore-log: 
,04-01 15:26:34.414  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 15:26:34.414  3541  3615 I jxcore-log: 
,04-01 15:26:34.658  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 15:26:34.658  3541  3615 I jxcore-log: 
,04-01 15:26:34.728  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 15:26:34.728  3541  3615 I jxcore-log: 
,04-01 15:26:34.781  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 15:26:34.781  3541  3615 I jxcore-log: 
,04-01 15:26:34.787  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 15:26:34.787  3541  3615 I jxcore-log: 
,04-01 15:26:34.796  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 15:26:34.796  3541  3615 I jxcore-log: 
,04-01 15:26:34.799  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 15:26:34.799  3541  3615 I jxcore-log: 
,04-01 15:26:34.804  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 15:26:34.804  3541  3615 I jxcore-log: 
,04-01 15:26:34.819  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 15:26:34.819  3541  3615 I jxcore-log: 
,04-01 15:26:34.837  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 15:26:34.837  3541  3615 I jxcore-log: 
,04-01 15:26:34.920  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 15:26:34.920  3541  3615 I jxcore-log: 
,04-01 15:26:34.924  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 15:26:34.924  3541  3615 I jxcore-log: 
,04-01 15:26:34.948  3541  3615 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 15:26:34.948  3541  3615 I jxcore-log: 
,04-01 15:26:34.954  3541  3615 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-01 15:26:34.956  3541  3615 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-01 15:26:34.956  3541  3615 I jxcore-log: 
,04-01 15:26:36.718   754   770 I ActivityManager: Killing 3166:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-01 15:26:36.732   754   770 I ActivityManager: Killing 3135:com.android.musicfx/u0a13 (adj 15): empty #18
,04-01 15:26:37.191   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 15:26:37.192   754   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 15:26:52.680  1550  3795 I EventLogService: Aggregate from 1459517160448 (log), 1459515412522 (data)
,04-01 15:26:52.786  1650  1711 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 15:26:52.786  1650  1650 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 15:26:57.194   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,04-01 15:27:00.545  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:27:00.548  1509  3836 I VacuumService: Vacuum at: now=1459517220548 tag=VacuumService
,04-01 15:27:00.594  1939  2036 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 15:27:01.491  1509  1509 I art     : Explicit concurrent mark sweep GC freed 97331(6MB) AllocSpace objects, 37(592KB) LOS objects, 39% free, 24MB/40MB, paused 917us total 56.448ms
,04-01 15:27:01.511  1509  3848 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 10898 seconds from now (1459517221511)
,04-01 15:27:01.593  1509  3846 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-01 15:27:01.597  1509  3846 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 15:27:03.206  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:27:03.207  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 15:27:16.971  1083  1280 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-01 15:27:16.972  1083  1280 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 15:27:17.024  1509  1509 I ConfigService: onCreate
,04-01 15:27:17.196   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-01 15:27:17.196   754   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 15:27:22.074  1509  1509 I ConfigService: onDestroy
,04-01 15:27:37.200   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-01 15:27:37.200   754   859 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 15:27:53.174   754   838 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,04-01 15:27:53.179   754   838 I PowerManagerService: Sleeping (uid 1000)...
,04-01 15:27:53.239   754   838 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 15:27:53.247   189   875 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-01 15:27:53.257   182   851 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (110 us)
,04-01 15:27:53.270   754   859 E WifiStateMachine: cancelDelayedScan -> 11
,04-01 15:27:53.277   754   859 E native  : do suspend false
,04-01 15:27:53.426  1083  1083 I Keyboard.Facilitator: onFinishInput()
04-01 15:27:53.426   189   869 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-01 15:27:53.434   754   859 E WifiStateMachine: cancelDelayedScan -> 13
,04-01 15:27:53.436   754   859 E native  : do suspend true
,04-01 15:27:53.761   754   836 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
04-01 15:27:53.764   754   754 V ActivityManager: Display changed displayId=0
,04-01 15:27:53.775   182   182 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
,04-01 15:27:53.777   182   182 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-01 15:27:53.778   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
,04-01 15:27:53.779   754   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-01 15:27:53.891   183   183 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-01 15:27:53.892   183   183 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-01 15:27:53.892   183   183 I rmt_storage: wakelock acquired: 1, error no: 2
04-01 15:27:53.892   183   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-01 15:27:53.963   183   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-01 15:27:53.963   183   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,04-01 15:27:53.963   183   560 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-01 15:27:53.963   183   560 I rmt_storage: 
,04-01 15:27:53.965   183   183 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-01 15:27:54.061   182   182 D qdhwcomposer: hwc_blank: Done blanking display: 0
,04-01 15:27:54.061   754   885 D SurfaceControl: Excessive delay in setPowerMode(): 301ms
04-01 15:27:54.062  1937  1978 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-01 15:27:54.074  3541  3541 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-01 15:27:54.074  3541  3541 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-01 15:27:54.095   754   754 W ProcessCpuTracker: Skipping unknown process pid 3907
,04-01 15:27:54.096   754   754 W ProcessCpuTracker: Skipping unknown process pid 3910
,04-01 15:27:54.100  3541  3541 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@40f290 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@18a73a44, 16908290=android.view.AbsSavedState$1@18a73a44}, android:focusedViewId=100}]}]
04-01 15:27:54.100  3541  3541 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-01 15:27:54.100  3541  3541 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-01 15:27:54.101  3541  3541 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-01 15:27:57.201   754   859 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-50
04-01 15:27:57.201   754   859 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-01 15:27:58.781  1509  1866 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-01 15:28:49.922  3541  3615 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 15:28:49.922  3541  3615 I jxcore-log: 
,04-01 15:28:50.315  3937  3937 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 15:28:50.318  3937  3937 D AndroidRuntime: CheckJNI is OFF
,04-01 15:28:50.409  3937  3937 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 15:28:50.414   754   831 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-01 15:28:50.415   754   831 I ActivityManager: Killing 3541:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-01 15:28:50.450   754  1296 I WindowState: WIN DEATH: Window{29c7d4a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,04-01 15:28:50.451   754   771 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@399fed69)
04-01 15:28:50.451   754   867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 15:28:50.451   754   860 D WifiService: Client connection lost with reason: 4
04-01 15:28:50.451   754   867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 15:28:50.466   754   842 W PackageSettings: Skipping PackageSetting{1e38e220 com.example.hello/10116} due to missing metadata
,04-01 15:28:50.628   754   831 I ActivityManager:   Force finishing activity 3 ActivityRecord{93f3960 u0 com.test.thalitest/.MainActivity t19}
,04-01 15:28:50.631   754   952 W ActivityManager: Spurious death for ProcessRecord{ba443ee 3541:com.test.thalitest/u0a49}, curProc for 3541: null
04-01 15:28:50.632   754   842 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-01 15:28:50.633   754   842 I ActivityManager:   Force finishing activity 3 ActivityRecord{93f3960 u0 com.test.thalitest/.MainActivity t19 f}
04-01 15:28:50.633   754   842 W ActivityManager: Duplicate finish request for ActivityRecord{93f3960 u0 com.test.thalitest/.MainActivity t19 f}
,04-01 15:28:50.686  1227  1227 I art     : Explicit concurrent mark sweep GC freed 2026(121KB) AllocSpace objects, 8(739KB) LOS objects, 38% free, 25MB/41MB, paused 954us total 32.370ms
,04-01 15:28:50.691  1550  1550 I art     : Explicit concurrent mark sweep GC freed 3363(220KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 23MB/30MB, paused 938us total 51.951ms
,04-01 15:28:50.696  1083  1083 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-01 15:28:50.698  1509  1637 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-01 15:28:50.702   754   850 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 15:28:50.703   754   887 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-01 15:28:50.703   754   887 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-01 15:28:50.738  1083  3966 I Keyboard.Facilitator.DecoderInitializer: run()
,04-01 15:28:50.744  1083  3966 I Decoder : createOrResetDecoder
,04-01 15:28:50.746   908   908 I art     : Explicit concurrent mark sweep GC freed 42200(1736KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 2.267ms total 35.333ms
,04-01 15:28:50.755  1375  1375 I art     : Explicit concurrent mark sweep GC freed 3678(270KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 22MB/30MB, paused 80.044ms total 118.025ms
,04-01 15:28:50.756  2747  3971 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
04-01 15:28:50.758   754  1223 I ActivityManager: Start proc 3972:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-01 15:28:50.761  1509  1509 I ConfigService: onCreate
,04-01 15:28:50.786   754   754 I art     : Explicit concurrent mark sweep GC freed 65679(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 29MB/44MB, paused 2.266ms total 98.081ms
,04-01 15:28:50.787   754   842 I art     : WaitForGcToComplete blocked for 23.579ms for cause Explicit
,04-01 15:28:50.809  1083  3966 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-01 15:28:50.832  1083  3966 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,04-01 15:28:50.834  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,04-01 15:28:50.834  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-01 15:28:50.835   754  1297 I ActivityManager: Start proc 3995:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-01 15:28:50.838  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-01 15:28:50.838  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-01 15:28:50.838  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-01 15:28:50.838  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-01 15:28:50.839  1083  3966 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-01 15:28:50.839  1083  3966 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-01 15:28:50.839  1083  3966 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-01 15:28:50.839  1083  3966 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-01 15:28:50.839  1083  3966 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,04-01 15:28:50.839  1083  3966 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-01 15:28:50.845   754  1245 I ActivityManager: Killing 3054:com.google.android.keep/u0a52 (adj 15): empty #17
,04-01 15:28:50.860   754  1296 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3541 uid 10049
,04-01 15:28:50.861  1083  1083 I Keyboard.Facilitator: onFinishInput()
,04-01 15:28:50.871  1227  1227 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
04-01 15:28:50.871   754   754 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 15:28:50.871   754   754 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-01 15:28:50.905   754   842 I art     : Explicit concurrent mark sweep GC freed 15167(1369KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 1.432ms total 118.308ms
,04-01 15:28:50.925  3995  3995 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-01 15:28:50.933  1550  4015 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-01 15:28:50.934  1550  4015 D AccountUtils: Clearing selected account for com.test.thalitest
,04-01 15:28:50.945  1550  4015 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-01 15:28:50.946  1509  1509 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-01 15:28:50.946  1509  1509 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-01 15:28:50.962  1227  1445 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-01 15:28:50.983   754  1215 I ActivityManager: Start proc 4020:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-01 15:28:51.027  3937  3937 I art     : System.exit called, status: 0
04-01 15:28:51.027  3937  3937 I AndroidRuntime: VM exiting with result code 0.
,04-01 15:28:51.054   754   842 I ActivityManager: Start proc 4039:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-01 15:28:51.061  1550  4037 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 15:28:51.068  1550  4037 W BaseAppContext: Using Auth Proxy for data requests.
,04-01 15:28:51.085  1550  4015 I GMPM-SVC: App measurement is starting up, version: 8703
04-01 15:28:51.085  1550  4015 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-01 15:28:51.113  1550  1616 I Icing   : doRemovePackageData com.test.thalitest
,04-01 15:28:51.118  1550  4015 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,04-01 15:28:51.131   754  1187 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 15:28:51.131   754   867 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-01 15:28:51.131   754   771 I ActivityManager: Killing 3247:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-01 15:28:51.132   754   867 D ConnectivityService: apparently satisfied.  currentScore=60
,04-01 15:28:51.132  1550  4065 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 15:28:51.214  1550  4061 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,04-01 15:28:51.222  1550  4061 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(:com.google.android.gms:321)
,04-01 15:28:51.225  1550  1913 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,04-01 15:28:51.228  1550  4068 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
04-01 15:28:51.228  1550  4068 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
04-01 15:28:51.229  1550  4068 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 15:28:51.232  1550  4068 W SQLiteOpenHelper: Opened metrics.db in read-only mode
04-01 15:28:51.232  1550  4068 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
04-01 15:28:51.232  1550  4068 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
04-01 15:28:51.233  1550  4068 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
04-01 15:28:51.233  1550  4068 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
04-01 15:28:51.251  1550  4068 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-01 15:28:51.251  1550  4068 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-01 15:28:51.251  1550  4068 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-01 15:28:51.251  1550  4068 I GCore-Chimera-Crash: ==
04-01 15:28:51.251  1550  4068 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-01 15:28:51.251  1550  4068 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryChimeraIntentService]
04-01 15:28:51.251  1550  4068 E AndroidRuntime: Process: com.google.android.gms, PID: 1550
04-01 15:28:51.251  1550  4068 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:280)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-01 15:28:51.251  1550  4068 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-01 15:28:51.252  4020  4071 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
04-01 15:28:51.252  4020  4071 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
04-01 15:28:51.252  4020  4071 I GAv4    :   adb logcat -s GAv4
04-01 15:28:51.253  1550  4068 I Process : Sending signal. PID: 1550 SIG: 9
04-01 15:28:51.258   754  4076 E DropBoxManagerService: Can't write: system_app_crash
04-01 15:28:51.258   754  4076 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-01 15:28:51.258   754  4076 E DropBoxManagerService: 	... 5 more
,04-01 15:28:51.268   754  1215 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3faa991f)
04-01 15:28:51.268   754   867 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 15:28:51.269   754   867 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 15:28:51.270   754   860 D WifiService: Client connection lost with reason: 4

```
