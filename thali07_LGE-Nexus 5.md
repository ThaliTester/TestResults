#### Test 648099366fd8e87_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
,04-01 10:26:33.278  1552  2342 I CheckinService: Done disabling old GoogleServicesFramework version
04-01 10:26:33.531  3442  3442 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-01 10:26:33.534  3442  3442 D AndroidRuntime: CheckJNI is OFF
04-01 10:26:33.658  3442  3442 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-01 10:26:33.661   765  1322 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-01 10:26:33.666   765  1322 V WindowManager: addAppToken: AppWindowToken{3ebb16d7 token=Token{1d9e0656 ActivityRecord{3c71871 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-01 10:26:33.669  3442  3442 D AndroidRuntime: Shutting down VM
04-01 10:26:33.672  1378  1400 W SearchService: Abort, client detached.
04-01 10:26:33.676   765   834 V WindowManager: Adding window Window{83f8a2e u0 Starting com.test.thalitest} at 2 of 7 (after Window{2329c8ab u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-01 10:26:33.701   765  1185 I ActivityManager: Start proc 3463:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-01 10:26:33.736  1378  1511 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-01 10:26:33.736   199   199 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 185us total 35.250ms
04-01 10:26:33.757   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 194us total 19.436ms
04-01 10:26:33.764  1378  1378 I MicroDetector: Keeping mic open: false
04-01 10:26:33.765  1378  1378 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@2529ab30
04-01 10:26:33.765  1378  1587 I DeviceStateChecker: DeviceStateChecker cancelled
04-01 10:26:33.784   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 259us total 26.886ms
04-01 10:26:33.818  3463  3463 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
04-01 10:26:33.823   188  1621 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-01 10:26:33.823   188  1621 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-01 10:26:33.829  1378  1617 I MicroRecognitionRunner: Detection finished
04-01 10:26:33.829  3463  3463 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7105-7106)
04-01 10:26:33.830  3463  3463 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 10:26:33.830  1378  1586 I MicroRecognitionRunner: Stopping hotword detection.
04-01 10:26:33.841  3463  3463 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21a846d5}
04-01 10:26:33.842  3463  3463 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-01 10:26:33.842  3463  3463 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
04-01 10:26:33.861  3463  3463 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
04-01 10:26:33.882  3463  3463 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
04-01 10:26:33.883   765  1159 I ActivityManager: Killing 3033:com.google.android.deskclock/u0a33 (adj 15): empty #17
,04-01 10:26:33.927   765   833 D BluetoothManagerService: Message: 20
,04-01 10:26:33.928   765   833 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b53678c:true
,04-01 10:26:33.940  3463  3463 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-01 10:26:33.940  3463  3463 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-01 10:26:33.978  3463  3463 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-01 10:26:33.978  3463  3463 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-01 10:26:33.990  3463  3463 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-01 10:26:33.996  3463  3463 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-01 10:26:33.997  3463  3463 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-01 10:26:34.006  3463  3463 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-01 10:26:34.028  3463  3521 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
04-01 10:26:34.033  3463  3463 D Atlas   : Validating map...
04-01 10:26:34.037   765  1322 V WindowManager: Adding window Window{1fc743cb u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{83f8a2e u0 Starting com.test.thalitest})
,04-01 10:26:34.043   765   867 D WifiService: New client listening to asynchronous messages
,04-01 10:26:34.053   765   780 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-01 10:26:34.053   765   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-01 10:26:34.053   765   868 D ConnectivityService: apparently satisfied.  currentScore=60
,04-01 10:26:34.054  3463  3523 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-01 10:26:34.077  3463  3521 I OpenGLRenderer: Initialized EGL, version 1.4
,04-01 10:26:34.082  3463  3521 D OpenGLRenderer: Enabling debug mode 0
,04-01 10:26:34.139   765   834 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms
,04-01 10:26:34.141  1099  1099 I Keyboard.Facilitator: onFinishInput()
,04-01 10:26:34.190  3463  3528 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-01 10:26:34.243  3463  3463 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3463
,04-01 10:26:34.407  3463  3463 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-01 10:26:34.647  3463  3545 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362701696
,04-01 10:26:34.651  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-01 10:26:34.651  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-01 10:26:34.651  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-01 10:26:34.651  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-01 10:26:34.651  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-01 10:26:34.652  3463  3545 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d41425 added. We now have 1 listener(s)
04-01 10:26:34.652   765   944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 10:26:34.656  3463  3545 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
04-01 10:26:34.657  3463  3545 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,04-01 10:26:34.658  3463  3545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
04-01 10:26:34.659  3463  3545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-01 10:26:34.664  3463  3545 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad29208 added. We now have 1 listener(s)
04-01 10:26:34.664  3463  3545 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-01 10:26:34.667  3463  3545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-01 10:26:34.670  3463  3545 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-01 10:26:34.670  3463  3545 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-01 10:26:34.673  3463  3545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-01 10:26:34.674   765   781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-01 10:26:34.675  3463  3545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:26:34.679  3463  3545 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-01 10:26:34.679  3463  3545 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-01 10:26:34.679  3463  3545 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-01 10:26:34.681  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 10:26:34.682  3463  3545 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-01 10:26:34.683  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-01 10:26:34.704  3463  3463 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-01 10:26:35.292  3463  3549 W jxcore-log: Initializing JXcore engine
04-01 10:26:35.292  3463  3549 W jxcore-log: JXcore engine is ready
,04-01 10:26:35.332  3549  3549 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[7769]" dev="sockfs" ino=7769 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-01 10:26:35.332  3549  3549 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,04-01 10:26:35.332  3549  3549 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[6818]" dev="sockfs" ino=6818 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-01 10:26:35.332  3549  3549 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17835]" dev="sockfs" ino=17835 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-01 10:26:35.349  3463  3549 W jxcore-log: Starting JXcore engine
,04-01 10:26:35.433  3463  3549 W jxcore-log: Platform android
04-01 10:26:35.433  3463  3549 W jxcore-log: 
04-01 10:26:35.433  3463  3549 W jxcore-log: Process ARCH arm
04-01 10:26:35.433  3463  3549 W jxcore-log: 
,04-01 10:26:35.528   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-01 10:26:35.678  3463  3549 I jxcore-log: JXcore Cordova bridge is ready!
04-01 10:26:35.678  3463  3549 I jxcore-log: 
04-01 10:26:35.678  3463  3549 W jxcore-log: JXcore engine is started
,04-01 10:26:35.685  3463  3545 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-01 10:26:35.686  3463  3463 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-01 10:26:37.272  1020  1020 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,04-01 10:26:38.830  3329  3357 W Babel   : aye TOOK TOO LONG! (15017ms > 10000ms)
,04-01 10:26:38.831  3329  3355 W Babel   : aye TOOK TOO LONG! (15030ms > 10000ms)
,04-01 10:26:38.833   765   944 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 10:26:38.835   765  1212 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 10:26:38.863  3329  3329 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-01 10:26:38.863  3329  3329 W Babel   : BAM#gBA: invalid account id: -1
04-01 10:26:38.863  3329  3329 W Babel   : BAM#gBA: invalid account id: -1
04-01 10:26:38.863  3329  3329 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-01 10:26:38.865   765  1322 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-01 10:26:38.866   765  1185 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-01 10:26:38.893  3329  3365 W Babel   : aye TOOK TOO LONG! (15039ms > 10000ms)
,04-01 10:26:38.940  1552  1567 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,04-01 10:26:39.002  1644  1704 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 10:26:39.003  1644  1644 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 10:26:43.129   765  1322 I ActivityManager: Killing 3096:com.android.providers.calendar/u0a1 (adj 15): empty #17
,04-01 10:26:43.210   765  1322 I ActivityManager: Killing 3067:com.google.android.keep/u0a52 (adj 15): empty #18
,04-01 10:26:44.419  1644  1644 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,04-01 10:26:44.440  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:44.450  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:44.452  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:44.983  3463  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-01 10:26:44.983  3463  3549 I jxcore-log: 
04-01 10:26:44.986  3463  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-01 10:26:44.986  3463  3549 I jxcore-log: 
,04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-01 10:26:44.989  3463  3549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-01 10:26:44.990  3463  3549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
04-01 10:26:44.992  3463  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-01 10:26:44.992  3463  3549 I jxcore-log: 
,04-01 10:26:44.993  3463  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-01 10:26:44.993  3463  3549 I jxcore-log: 
,04-01 10:26:45.016  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:45.118  1644  1689 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 10:26:45.118  1644  1689 I qtaguid : Untagging socket 37 failed errno=-22
04-01 10:26:45.118  1644  1689 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 10:26:45.121  1644  1644 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,04-01 10:26:45.163  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:45.191   765   781 I ActivityManager: Start proc 3621:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-01 10:26:45.231  3621  3621 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
04-01 10:26:45.231  3621  3621 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-01 10:26:45.266  3621  3621 I MultiDex: VM with version 2.1.0 has multidex support
04-01 10:26:45.266  3621  3621 I MultiDex: install
04-01 10:26:45.266  3621  3621 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-01 10:26:45.284  3621  3621 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-01 10:26:45.342  3621  3621 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-01 10:26:45.354  3621  3621 D ChimeraCfgMgr: Reading stored module config
,04-01 10:26:45.362  1514  1514 D WearableService: callingUid 10007, callindPid: 1514
,04-01 10:26:45.367  1514  1923 E MDM     : [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-01 10:26:45.384  1514  1514 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-01 10:26:45.384  1552  3653 D LocationInitializer: Restart initialization of location
,04-01 10:26:45.397  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:45.407  1514  1625 W GCoreFlp: No location to return for getLastLocation()
04-01 10:26:45.408  1514  3654 W FusedLocationProvider: location=null
,04-01 10:26:45.457  3621  3651 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-01 10:26:45.470  3621  3621 D CAR.SERVICE: Connecting to CarCallService...
,04-01 10:26:45.482  3621  3621 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 10:26:45.482  3621  3621 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-01 10:26:45.484  1644  1690 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
04-01 10:26:45.484  1644  1690 I qtaguid : Untagging socket 37 failed errno=-22
04-01 10:26:45.484  1644  1690 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
04-01 10:26:45.487  3621  3621 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-01 10:26:45.492  3621  3621 D CAR.TEL.Service: Creating a new CarCallService.
,04-01 10:26:45.493  3621  3621 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-01 10:26:45.494   765  1212 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-01 10:26:45.494  3621  3621 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@27fce5aa
,04-01 10:26:45.494   765   780 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-01 10:26:45.494  3621  3621 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-01 10:26:45.495  3621  3621 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-01 10:26:45.510  3463  3549 I jxcore-log: Unit Test app is loaded
04-01 10:26:45.510  3463  3549 I jxcore-log: 
,04-01 10:26:45.516  3463  3463 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-01 10:26:45.517  3463  3549 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-01 10:26:45.517  3463  3549 I jxcore-log: 
,04-01 10:26:45.521  3463  3549 I jxcore-log: My device name is: LGE-Nexus 5
04-01 10:26:45.521  3463  3549 I jxcore-log: 
,04-01 10:26:45.565  3621  3637 D CAR.SERVICE: Package validated; name: com.android.vending
,04-01 10:26:45.960  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:46.351  1644  1689 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
,04-01 10:26:46.351  1644  1689 I qtaguid : Untagging socket 37 failed errno=-22
04-01 10:26:46.351  1644  1689 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,04-01 10:26:46.416  1644  1644 I Finsky  : [1] com.google.android.finsky.autoupdate.v.e(289): Notifying user that 3 applications have outstanding updates.
,04-01 10:26:46.473  1644  1644 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,04-01 10:26:46.510  1514  1630 D DeviceConnectionService: client connected with version: 8298000
,04-01 10:26:46.514  1644  1644 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-01 10:26:46.515  1644  1644 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,04-01 10:26:48.157   765   829 I ActivityManager: Start proc 3685:com.android.providers.calendar/u0a1 for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,04-01 10:26:48.182  3685  3685 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-01 10:26:48.205  3685  3685 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@32ce1f8c(com.android.providers.calendar.CalendarProvider2@21a846d5)
,04-01 10:26:48.255  3685  3703 E SQLiteLog: (284) automatic index on view_events(_id)
,04-01 10:26:48.275  1644  3704 I Finsky  : [146] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-01 10:26:48.281  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:26:49.305  3685  3685 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-01 10:26:49.305  3685  3685 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-01 10:26:49.411  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-01 10:26:49.411  3463  3549 I jxcore-log: 
,04-01 10:26:49.754  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-01 10:26:49.754  3463  3549 I jxcore-log: 
,04-01 10:26:49.765  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-01 10:26:49.765  3463  3549 I jxcore-log: 
04-01 10:26:49.768  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-01 10:26:49.768  3463  3549 I jxcore-log: 
,04-01 10:26:49.783  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-01 10:26:49.783  3463  3549 I jxcore-log: 
04-01 10:26:49.787  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-01 10:26:49.787  3463  3549 I jxcore-log: 
,04-01 10:26:50.606  3621  3621 D CAR.SERVICE: mConnectedToCar = false, abort
,04-01 10:26:50.620  3621  3621 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dcad523 that was originally bound here
04-01 10:26:50.620  3621  3621 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1dcad523 that was originally bound here
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 10:26:50.620  3621  3621 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 10:26:50.625  3621  3621 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2deb5095 that was originally bound here
04-01 10:26:50.625  3621  3621 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2deb5095 that was originally bound here
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-01 10:26:50.625  3621  3621 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-01 10:26:50.626   765  1212 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@251d2ee0
,04-01 10:26:51.765  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-01 10:26:51.765  3463  3549 I jxcore-log: 
,04-01 10:26:51.786  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-01 10:26:51.786  3463  3549 I jxcore-log: 
,04-01 10:26:51.794  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-01 10:26:51.794  3463  3549 I jxcore-log: 
,04-01 10:26:51.942  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-01 10:26:51.942  3463  3549 I jxcore-log: 
,04-01 10:26:52.024  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-01 10:26:52.024  3463  3549 I jxcore-log: 
,04-01 10:26:52.076  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-01 10:26:52.076  3463  3549 I jxcore-log: 
,04-01 10:26:52.082  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-01 10:26:52.082  3463  3549 I jxcore-log: 
,04-01 10:26:52.213  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-01 10:26:52.213  3463  3549 I jxcore-log: 
,04-01 10:26:52.233  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-01 10:26:52.233  3463  3549 I jxcore-log: 
,04-01 10:26:52.237  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-01 10:26:52.237  3463  3549 I jxcore-log: 
04-01 10:26:52.241  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-01 10:26:52.241  3463  3549 I jxcore-log: 
,04-01 10:26:52.257  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-01 10:26:52.257  3463  3549 I jxcore-log: 
,04-01 10:26:52.275  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-01 10:26:52.275  3463  3549 I jxcore-log: 
,04-01 10:26:52.357  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-01 10:26:52.357  3463  3549 I jxcore-log: 
04-01 10:26:52.362  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-01 10:26:52.362  3463  3549 I jxcore-log: 
,04-01 10:26:52.385  3463  3549 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-01 10:26:52.385  3463  3549 I jxcore-log: 
,04-01 10:26:52.394  3463  3549 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-01 10:26:52.397  3463  3549 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-01 10:26:52.397  3463  3549 I jxcore-log: 
,04-01 10:26:54.466   765   944 I ActivityManager: Killing 3154:com.android.musicfx/u0a13 (adj 15): empty #17
,04-01 10:26:54.483   765   944 I ActivityManager: Killing 3132:com.google.android.partnersetup/u0a11 (adj 15): empty #18
,04-01 10:26:55.529   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
04-01 10:26:55.530   765   866 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 10:27:00.226  1946  2031 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-01 10:27:01.986  1644  1704 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,04-01 10:27:01.986  1644  1644 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,04-01 10:27:15.533   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
,04-01 10:27:17.780   765  1159 I art     : Explicit concurrent mark sweep GC freed 37890(1786KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.584ms total 112.024ms
,04-01 10:27:17.958  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:27:17.962  1514  3723 I VacuumService: Vacuum at: now=1459499237962 tag=VacuumService
,04-01 10:27:34.182  1099  1241 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-01 10:27:34.182  1099  1241 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-01 10:27:34.243  1514  1514 I ConfigService: onCreate
,04-01 10:27:35.537   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 10:27:35.537   765   866 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 10:27:39.317  1514  1514 I ConfigService: onDestroy
,04-01 10:27:55.539   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 10:27:55.540   765   866 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-01 10:28:11.336   765   836 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-01 10:28:11.341   765   836 I PowerManagerService: Sleeping (uid 1000)...
,04-01 10:28:11.391   188  1354 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-01 10:28:11.401   765   836 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-01 10:28:11.402   765   866 E WifiStateMachine: cancelDelayedScan -> 11
,04-01 10:28:11.411   765   866 E native  : do suspend false
,04-01 10:28:11.416   181   854 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (337 us)
,04-01 10:28:11.596   188   873 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-01 10:28:11.598  1099  1099 I Keyboard.Facilitator: onFinishInput()
,04-01 10:28:11.601   765   866 E WifiStateMachine: cancelDelayedScan -> 13
,04-01 10:28:11.603   765   866 E native  : do suspend true
,04-01 10:28:11.904   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 10:28:11.904   765   866 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-01 10:28:11.986   765   834 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-01 10:28:11.991   765   765 V ActivityManager: Display changed displayId=0
04-01 10:28:11.998   181   181 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
04-01 10:28:11.998   181   181 D qdhwcomposer: hwc_blank: Blanking display: 0
,04-01 10:28:12.123   182   182 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-01 10:28:12.123   182   182 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
04-01 10:28:12.123   182   182 I rmt_storage: wakelock acquired: 1, error no: 2
,04-01 10:28:12.123   182   547 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236802816)
,04-01 10:28:12.201   182   547 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
04-01 10:28:12.201   182   547 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
04-01 10:28:12.201   182   547 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236802816) wakelock released: 1, error no: 0
04-01 10:28:12.201   182   547 I rmt_storage: 
,04-01 10:28:12.203   182   182 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-01 10:28:12.263   181   181 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-01 10:28:12.264   765   882 D SurfaceControl: Excessive delay in setPowerMode(): 278ms
04-01 10:28:12.264  1929  1931 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-01 10:28:12.279  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-01 10:28:12.279  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-01 10:28:12.322  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1eddfef2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33b515e, 16908290=android.view.AbsSavedState$1@33b515e}, android:focusedViewId=100}]}]
04-01 10:28:12.322  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-01 10:28:12.322  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-01 10:28:12.322  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-01 10:28:15.541   765   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-49
04-01 10:28:15.541   765   866 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-01 10:28:16.287  1514  1889 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-01 10:28:42.361  1514  3767 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 4317 seconds from now (1459499322361)
,04-01 10:28:42.439  1514  3758 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-01 10:28:42.443  1514  3758 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-01 10:28:44.181  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:44.182  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-01 10:28:46.226  1514  1525 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c3e2df6)
,04-01 10:28:46.227  1514  1525 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@abeb5f7)
,04-01 10:28:46.228  1514  1525 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22aeec64)
,04-01 10:28:46.229  1514  1525 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9d94ecd)
04-01 10:28:46.229  1514  1525 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27173382)
,04-01 10:29:06.551  3463  3549 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-01 10:29:06.551  3463  3549 I jxcore-log: 
,04-01 10:29:06.911  3840  3840 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-01 10:29:06.913  3840  3840 D AndroidRuntime: CheckJNI is OFF
,04-01 10:29:06.998  3840  3840 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-01 10:29:07.004   765   829 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
,04-01 10:29:07.004   765   829 I ActivityManager: Killing 3463:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-01 10:29:07.041   765   867 D WifiService: Client connection lost with reason: 4
,04-01 10:29:07.042   765  1322 I WindowState: WIN DEATH: Window{1fc743cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
04-01 10:29:07.042   765   781 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@14a615be)
,04-01 10:29:07.042   765   868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 10:29:07.043   765   868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-01 10:29:07.056   765   840 W PackageSettings: Skipping PackageSetting{1a6e4402 com.example.hello/10116} due to missing metadata
,04-01 10:29:07.118   765   829 I ActivityManager:   Force finishing activity 3 ActivityRecord{3c71871 u0 com.test.thalitest/.MainActivity t19}
,04-01 10:29:07.121   765  1185 W ActivityManager: Spurious death for ProcessRecord{344b561f 3463:com.test.thalitest/u0a49}, curProc for 3463: null
,04-01 10:29:07.122   765   840 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-01 10:29:07.149  1217  1217 I art     : Explicit concurrent mark sweep GC freed 1701(106KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 735us total 21.422ms
,04-01 10:29:07.151   904   904 I art     : Explicit concurrent mark sweep GC freed 12062(542KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 41MB/57MB, paused 788us total 23.440ms
,04-01 10:29:07.203   765   765 I art     : Explicit concurrent mark sweep GC freed 42741(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/43MB, paused 1.088ms total 50.952ms
,04-01 10:29:07.211  1552  1552 I art     : Explicit concurrent mark sweep GC freed 2437(147KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 824us total 86.218ms
,04-01 10:29:07.212   765   884 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-01 10:29:07.212   765   884 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-01 10:29:07.218  1514  1632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-01 10:29:07.222   765   858 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-01 10:29:07.231  1099  1099 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-01 10:29:07.239  1378  1378 I art     : Explicit concurrent mark sweep GC freed 3209(248KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 22MB/30MB, paused 598us total 107.180ms
,04-01 10:29:07.241  2990  3870 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-01 10:29:07.250  1099  3871 I Keyboard.Facilitator.DecoderInitializer: run()
,04-01 10:29:07.253  1099  3871 I Decoder : createOrResetDecoder
,04-01 10:29:07.277   765  1185 I ActivityManager: Start proc 3877:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-01 10:29:07.285  1514  1514 I ConfigService: onCreate
,04-01 10:29:07.312   765   765 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
04-01 10:29:07.312   765   765 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-01 10:29:07.317  1099  3871 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-01 10:29:07.333   765  1214 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3463 uid 10049
,04-01 10:29:07.335  1099  1099 I Keyboard.Facilitator: onFinishInput()
,04-01 10:29:07.342   765  1159 I ActivityManager: Start proc 3898:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-01 10:29:07.344   765  1154 I ActivityManager: Killing 3188:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-01 10:29:07.348  1099  3871 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-01 10:29:07.349  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,04-01 10:29:07.353  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-01 10:29:07.356  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-01 10:29:07.356  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
04-01 10:29:07.357  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-01 10:29:07.357  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
04-01 10:29:07.357  1099  3871 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-01 10:29:07.357  1099  3871 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-01 10:29:07.357  1099  3871 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-01 10:29:07.358  1099  3871 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-01 10:29:07.358  1099  3871 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-01 10:29:07.358  1099  3871 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-01 10:29:07.360  1217  1217 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-01 10:29:07.371   765   840 I art     : Explicit concurrent mark sweep GC freed 14169(1282KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 1.504ms total 158.635ms
,04-01 10:29:07.424  3840  3840 I art     : System.exit called, status: 0
04-01 10:29:07.424  3840  3840 I AndroidRuntime: VM exiting with result code 0.
,04-01 10:29:07.446  3898  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-01 10:29:07.484   765   840 I ActivityManager: Start proc 3919:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-01 10:29:07.487  1217  1423 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,04-01 10:29:07.497  1552  3937 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-01 10:29:07.497  1552  3937 D AccountUtils: Clearing selected account for com.test.thalitest
,04-01 10:29:07.513  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-01 10:29:07.513  1514  1514 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-01 10:29:07.515  1552  3937 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-01 10:29:07.541   765  1159 I ActivityManager: Start proc 3944:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-01 10:29:07.556   765   781 I ActivityManager: Killing 3257:com.quickoffice.android/u0a65 (adj 15): empty #17

```
