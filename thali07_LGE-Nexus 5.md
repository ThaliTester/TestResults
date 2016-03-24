#### Test 63968542e6bfc69_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
,03-24 21:14:09.245  1555  2442 I CheckinService: Done disabling old GoogleServicesFramework version
03-24 21:14:09.459  3509  3509 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 21:14:09.461  3509  3509 D AndroidRuntime: CheckJNI is OFF
03-24 21:14:09.556  3509  3509 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-24 21:14:09.560   768  1199 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-24 21:14:09.567   768  1199 V WindowManager: addAppToken: AppWindowToken{3391c342 token=Token{19e9458d ActivityRecord{313d8624 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-24 21:14:09.575   768   837 V WindowManager: Adding window Window{257e9945 u0 Starting com.test.thalitest} at 2 of 7 (after Window{36f9a7e4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-24 21:14:09.578  3509  3509 D AndroidRuntime: Shutting down VM
03-24 21:14:09.588  1341  1690 W SearchService: Abort, client detached.
03-24 21:14:09.628   768   784 I ActivityManager: Start proc 3530:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-24 21:14:09.643  1341  1341 I MicroDetector: Keeping mic open: false
03-24 21:14:09.643  1341  1341 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@3317b54
03-24 21:14:09.643  1341  1589 I DeviceStateChecker: DeviceStateChecker cancelled
03-24 21:14:09.646   198   198 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 199us total 16.221ms
03-24 21:14:09.659   198   198 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 214us total 12.568ms
03-24 21:14:09.681   198   198 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 203us total 20.337ms
03-24 21:14:09.687   187  1601 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-24 21:14:09.687   187  1601 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-24 21:14:09.692  1341  1596 I MicroRecognitionRunner: Detection finished
03-24 21:14:09.693  1341  1588 I MicroRecognitionRunner: Stopping hotword detection.
03-24 21:14:09.730  3530  3530 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-24 21:14:09.740  3530  3530 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 6844-6846)
03-24 21:14:09.740  3530  3530 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-24 21:14:09.745   768  1199 I ActivityManager: Killing 3112:com.google.android.deskclock/u0a33 (adj 15): empty #17
03-24 21:14:09.749  3530  3530 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12c9d8d}
03-24 21:14:09.749  3530  3530 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-24 21:14:09.750  3530  3530 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-24 21:14:09.761  3530  3530 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-24 21:14:09.779  3530  3530 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-24 21:14:09.820   768   836 D BluetoothManagerService: Message: 20
03-24 21:14:09.820   768   836 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1563c5ec:true
,03-24 21:14:09.823  3530  3530 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-24 21:14:09.823  3530  3530 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-24 21:14:09.882  3530  3530 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-24 21:14:09.883  3530  3530 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-24 21:14:09.894  3530  3530 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
03-24 21:14:09.895  3530  3530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 21:14:09.900  3530  3530 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-24 21:14:09.901  3530  3530 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-24 21:14:09.901  3530  3530 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
03-24 21:14:09.902  3530  3530 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-24 21:14:09.907  3530  3530 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-24 21:14:09.912  3530  3530 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-24 21:14:09.916  3530  3530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-24 21:14:09.916  3530  3530 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-24 21:14:09.934  3530  3589 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-24 21:14:09.939  3530  3530 D Atlas   : Validating map...
,03-24 21:14:09.943   768  1240 V WindowManager: Adding window Window{bab5ab u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{257e9945 u0 Starting com.test.thalitest})
,03-24 21:14:09.951   768   869 D WifiService: New client listening to asynchronous messages
,03-24 21:14:09.961   768  1242 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-24 21:14:09.961   768   872 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-24 21:14:09.961   768   872 D ConnectivityService: apparently satisfied.  currentScore=60
,03-24 21:14:09.962  3530  3591 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 21:14:10.002  3530  3589 I OpenGLRenderer: Initialized EGL, version 1.4
,03-24 21:14:10.007  3530  3589 D OpenGLRenderer: Enabling debug mode 0
,03-24 21:14:10.069   768   837 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms
,03-24 21:14:10.070  3530  3530 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-24 21:14:10.073  1077  1077 I Keyboard.Facilitator: onFinishInput()
,03-24 21:14:10.084  3530  3530 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
03-24 21:14:10.093  3530  3598 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-24 21:14:10.117  3530  3530 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3530
,03-24 21:14:10.248  3530  3530 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-24 21:14:10.479  3530  3606 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362801920
,03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-24 21:14:10.489  3530  3606 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a3eb0b4 added. We now have 1 listener(s)
03-24 21:14:10.489   768  1149 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-24 21:14:10.492  3530  3606 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-24 21:14:10.493  3530  3606 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
03-24 21:14:10.495  3530  3606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-24 21:14:10.495  3530  3606 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-24 21:14:10.498  3530  3606 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16ff4723 added. We now have 1 listener(s)
03-24 21:14:10.498  3530  3606 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-24 21:14:10.511  3530  3606 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
03-24 21:14:10.516  3530  3606 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-24 21:14:10.516  3530  3606 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
03-24 21:14:10.524  3530  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-24 21:14:10.525   768  1148 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
03-24 21:14:10.526  3530  3606 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-24 21:14:10.618   768  1149 I art     : Explicit concurrent mark sweep GC freed 21820(1069KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.513ms total 73.749ms
,03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:14:10.622  3530  3606 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-24 21:14:10.622  3530  3606 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-24 21:14:10.622  3530  3606 D io.jxcore.node.ConnectivityMonitor: start: OK
03-24 21:14:10.623  3530  3606 I io.jxcore.node.LifeCycleMonitor: start: OK
03-24 21:14:10.623  3530  3530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-24 21:14:10.624  3530  3530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-24 21:14:10.674  3530  3530 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-24 21:14:10.750   768   862 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-52
,03-24 21:14:11.330  3530  3616 W jxcore-log: Initializing JXcore engine
03-24 21:14:11.330  3530  3616 W jxcore-log: JXcore engine is ready
,03-24 21:14:11.367  3616  3616 W Thread-356: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8185]" dev="sockfs" ino=8185 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-24 21:14:11.367  3616  3616 W Thread-356: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,03-24 21:14:11.367  3616  3616 W Thread-356: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9412]" dev="sockfs" ino=9412 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-24 21:14:11.367  3616  3616 W Thread-356: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[14279]" dev="sockfs" ino=14279 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-24 21:14:11.391  3530  3616 W jxcore-log: Starting JXcore engine
,03-24 21:14:11.501  3530  3616 W jxcore-log: Platform android
03-24 21:14:11.501  3530  3616 W jxcore-log: 
03-24 21:14:11.501  3530  3616 W jxcore-log: Process ARCH arm
03-24 21:14:11.501  3530  3616 W jxcore-log: 
,03-24 21:14:11.697  3530  3616 I jxcore-log: JXcore Cordova bridge is ready!
03-24 21:14:11.697  3530  3616 I jxcore-log: 
03-24 21:14:11.697  3530  3616 W jxcore-log: JXcore engine is started
,03-24 21:14:11.700  3530  3606 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-24 21:14:11.702  3530  3530 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-24 21:14:13.818  3388  3419 W Babel   : aye TOOK TOO LONG! (15025ms > 10000ms)
,03-24 21:14:13.820  3388  3421 W Babel   : aye TOOK TOO LONG! (15024ms > 10000ms)
,03-24 21:14:13.857   768  1148 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-24 21:14:13.861   768   783 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-24 21:14:13.875  3388  3388 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-24 21:14:13.875  3388  3388 W Babel   : BAM#gBA: invalid account id: -1
03-24 21:14:13.875  3388  3388 W Babel   : BAM#gBA: invalid account id: -1
03-24 21:14:13.875  3388  3388 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-24 21:14:13.878   768  1240 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-24 21:14:13.880   768  1200 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-24 21:14:13.884  3388  3429 W Babel   : aye TOOK TOO LONG! (15035ms > 10000ms)
,03-24 21:14:13.985  1646  1708 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-24 21:14:13.986  1646  1646 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-24 21:14:14.848  1555  1566 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-24 21:14:20.148  1646  1646 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-24 21:14:20.160  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:20.165  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:20.166  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:20.685  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:20.730  3530  3616 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-24 21:14:20.730  3530  3616 I jxcore-log: 
03-24 21:14:20.732  3530  3616 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-24 21:14:20.732  3530  3616 I jxcore-log: 
,03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-24 21:14:20.735  3530  3616 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-24 21:14:20.737  3530  3616 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-24 21:14:20.738  3530  3616 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-24 21:14:20.738  3530  3616 I jxcore-log: 
03-24 21:14:20.740  3530  3616 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-24 21:14:20.740  3530  3616 I jxcore-log: 
,03-24 21:14:20.841  1646  1689 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-24 21:14:20.841  1646  1689 I qtaguid : Untagging socket 37 failed errno=-22
03-24 21:14:20.841  1646  1689 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-24 21:14:20.849  1646  1646 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-24 21:14:20.897  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:20.936   768  1240 I ActivityManager: Start proc 3702:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-24 21:14:20.960  3702  3702 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-24 21:14:20.960  3702  3702 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-24 21:14:20.986  3702  3702 I MultiDex: VM with version 2.1.0 has multidex support
03-24 21:14:20.986  3702  3702 I MultiDex: install
03-24 21:14:20.986  3702  3702 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-24 21:14:21.000  3702  3702 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-24 21:14:21.034  3702  3702 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-24 21:14:21.045  1535  1535 D WearableService: callingUid 10007, callindPid: 1535
,03-24 21:14:21.050  1535  1885 E MDM     : [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-24 21:14:21.052  1535  1535 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-24 21:14:21.052  1555  3723 D LocationInitializer: Restart initialization of location
,03-24 21:14:21.056  3702  3702 D ChimeraCfgMgr: Reading stored module config
,03-24 21:14:21.064  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:21.074  1535  1620 W GCoreFlp: No location to return for getLastLocation()
03-24 21:14:21.075  1535  3724 W FusedLocationProvider: location=null
,03-24 21:14:21.157  3702  3702 D CAR.SERVICE: Connecting to CarCallService...
,03-24 21:14:21.160  3702  3722 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-24 21:14:21.174  3702  3702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-24 21:14:21.175  3702  3702 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-24 21:14:21.184  3702  3702 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-24 21:14:21.189  3702  3702 D CAR.TEL.Service: Creating a new CarCallService.
,03-24 21:14:21.190  3702  3702 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-24 21:14:21.191   768  1199 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-24 21:14:21.191  3702  3702 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@1b91fa02
,03-24 21:14:21.191   768  1240 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-24 21:14:21.191  3702  3702 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-24 21:14:21.192  3702  3702 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-24 21:14:21.255  3530  3616 I jxcore-log: Unit Test app is loaded
03-24 21:14:21.255  3530  3616 I jxcore-log: 
,03-24 21:14:21.259  3530  3616 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-24 21:14:21.259  3530  3616 I jxcore-log: 
,03-24 21:14:21.260  3530  3530 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-24 21:14:21.265  3530  3616 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-24 21:14:21.266  3530  3616 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-24 21:14:21.266  3530  3616 I jxcore-log: 
,03-24 21:14:21.271  3530  3530 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-24 21:14:21.273  3530  3616 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-24 21:14:21.273  3530  3616 I jxcore-log:   bluetooth: 'on',
03-24 21:14:21.273  3530  3616 I jxcore-log:   wifi: 'on',
03-24 21:14:21.273  3530  3616 I jxcore-log:   cellular: 'doNotCare',
03-24 21:14:21.273  3530  3616 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-24 21:14:21.273  3530  3616 I jxcore-log: 
03-24 21:14:21.273  3530  3616 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-24 21:14:21.273  3530  3616 I jxcore-log: 
,03-24 21:14:21.303  3702  3718 D CAR.SERVICE: Package validated; name: com.android.vending
,03-24 21:14:21.418  1646  1688 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-24 21:14:21.418  1646  1688 I qtaguid : Untagging socket 37 failed errno=-22
03-24 21:14:21.418  1646  1688 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-24 21:14:21.567  3742  3742 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-24 21:14:21.570  3742  3742 D AndroidRuntime: CheckJNI is OFF
,03-24 21:14:21.656  3742  3742 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-24 21:14:21.661   768   832 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-24 21:14:21.661   768   832 I ActivityManager: Killing 3530:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-24 21:14:21.705   768  1149 I WindowState: WIN DEATH: Window{bab5ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-24 21:14:21.705   768  1199 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@23e0a455)
,03-24 21:14:21.706   768   872 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-24 21:14:21.706   768   869 D WifiService: Client connection lost with reason: 4
03-24 21:14:21.706   768   872 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-24 21:14:21.713   768   843 W PackageSettings: Skipping PackageSetting{6f3734d com.example.hello/10116} due to missing metadata
,03-24 21:14:21.870   768   832 E libprocessgroup: failed to kill 1 processes for processgroup 3530
03-24 21:14:21.870   768   832 W ActivityManager: Force removing ActivityRecord{313d8624 u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-24 21:14:21.875   768   947 W ActivityManager: Spurious death for ProcessRecord{27760e6a 3530:com.test.thalitest/u0a49}, curProc for 3530: null
,03-24 21:14:21.878   768   843 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-24 21:14:21.912  1555  1555 I art     : Explicit concurrent mark sweep GC freed 4178(185KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 743us total 25.475ms
,03-24 21:14:21.921  1341  1341 I art     : Explicit concurrent mark sweep GC freed 4243(338KB) AllocSpace objects, 7(154KB) LOS objects, 25% free, 21MB/29MB, paused 445us total 28.548ms
,03-24 21:14:21.947   909   909 I art     : Explicit concurrent mark sweep GC freed 39506(1636KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 58MB/74MB, paused 1.290ms total 28.958ms
,03-24 21:14:21.948   768   888 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-24 21:14:21.958   768   851 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-24 21:14:21.964  1077  1077 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-24 21:14:21.972  1535  1634 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-24 21:14:21.980  1077  3774 I Keyboard.Facilitator.DecoderInitializer: run()
,03-24 21:14:21.984  1077  3774 I Decoder : createOrResetDecoder
,03-24 21:14:21.989   768   768 I art     : Explicit concurrent mark sweep GC freed 24152(1552KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 1.424ms total 73.588ms
,03-24 21:14:21.991   768   843 I art     : WaitForGcToComplete blocked for 42.425ms for cause Explicit
,03-24 21:14:21.998  3040  3777 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-24 21:14:22.015   768  1240 I ActivityManager: Start proc 3779:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-24 21:14:22.021  1535  1535 I ConfigService: onCreate
,03-24 21:14:22.039   768   957 I ActivityManager: Killing 3166:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-24 21:14:22.052  3779  3779 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-24 21:14:22.065  1077  3774 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-24 21:14:22.080   768   768 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-24 21:14:22.080   768   768 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-24 21:14:22.086  1077  3774 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-24 21:14:22.087  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-24 21:14:22.087  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-24 21:14:22.089  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-24 21:14:22.089  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-24 21:14:22.089  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,03-24 21:14:22.089  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-24 21:14:22.090  1077  3774 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-24 21:14:22.090  1077  3774 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-24 21:14:22.090  1077  3774 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-24 21:14:22.090  1077  3774 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-24 21:14:22.090  1077  3774 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-24 21:14:22.090  1077  3774 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-24 21:14:22.115   768   957 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3530 uid 10049
,03-24 21:14:22.116  1077  1077 I Keyboard.Facilitator: onFinishInput()
,03-24 21:14:22.124  1555  3802 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-24 21:14:22.125  1555  3802 D AccountUtils: Clearing selected account for com.test.thalitest
,03-24 21:14:22.140  1535  1535 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-24 21:14:22.140  1535  1535 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-24 21:14:22.147  1555  3802 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-24 21:14:22.158  1203  1203 I art     : Explicit concurrent mark sweep GC freed 2789(158KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 1.004ms total 25.985ms
,03-24 21:14:22.158   768   843 I art     : Explicit concurrent mark sweep GC freed 10697(864KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.603ms total 155.780ms
,03-24 21:14:22.185  1341  1341 W LocationOracle: Best location was null
03-24 21:14:22.185  1341  1341 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-24 21:14:22.200  1341  3811 I MicroRecognitionRunner: Starting detection.
,03-24 21:14:22.202  1341  3812 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@c510bcb
,03-24 21:14:22.211   187  3815 I AudioFlinger: AudioFlinger's thread 0xb447f000 ready to run
,03-24 21:14:22.216  1555  3808 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 21:14:22.228  1535  1620 W GCoreFlp: No location to return for getLastLocation()
,03-24 21:14:22.230  1555  3802 I GMPM-SVC: App measurement is starting up, version: 8703
03-24 21:14:22.230  1555  3802 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
03-24 21:14:22.232  1555  3808 W BaseAppContext: Using Auth Proxy for data requests.
,03-24 21:14:22.239  1341  3812 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@c510bcb
,03-24 21:14:22.246  1535  1620 W GCoreFlp: No location to return for getLastLocation()
03-24 21:14:22.246   187  3815 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-24 21:14:22.246   187  3815 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-24 21:14:22.246   187  3815 D         : Failed to fetch the lookup information of the device 0000003E 
03-24 21:14:22.246   187  3815 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-24 21:14:22.246   187  3815 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-24 21:14:22.248  1535  1620 W GCoreFlp: No location to return for getLastLocation()
,03-24 21:14:22.252  1535  1620 W GCoreFlp: No location to return for getLastLocation()
,03-24 21:14:22.254   187  3815 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-24 21:14:22.277  1555  3802 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-24 21:14:22.287  1535  1620 W GCoreFlp: No location to return for getLastLocation()
,03-24 21:14:22.295  1535  1620 W GCoreFlp: No location to return for getLastLocation()
,03-24 21:14:22.311  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-24 21:14:22.314   768  1240 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-24 21:14:22.315   768   872 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-24 21:14:22.315   768   872 D ConnectivityService: apparently satisfied.  currentScore=60
,03-24 21:14:22.317  1555  3826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-24 21:14:22.329  1555  1618 I Icing   : doRemovePackageData com.test.thalitest
,03-24 21:14:22.343  1555  3825 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-24 21:14:22.343  1555  3825 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-24 21:14:22.343  1555  3825 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-24 21:14:22.343  1555  3825 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-24 21:14:22.349  1341  1341 I MicroDetectionWorker: onReady
,03-24 21:14:22.352  3742  3742 I art     : System.exit called, status: 0
03-24 21:14:22.352  3742  3742 I AndroidRuntime: VM exiting with result code 0.
,03-24 21:14:22.354  1555  3825 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-24 21:14:22.354  1555  3825 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-24 21:14:22.355  1555  3825 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-24 21:14:22.360  1341  3827 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-24 21:14:22.364  1555  3825 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-24 21:14:22.364  1555  3825 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-24 21:14:22.366  1555  3825 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-24 21:14:22.366  1555  3825 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-24 21:14:22.367  1555  3825 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-24 21:14:22.367  1555  3825 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-24 21:14:22.373  1203  1457 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-24 21:14:22.390   768   843 I ActivityManager: Start proc 3830:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-24 21:14:22.421   768   768 I ActivityManager: Start proc 3848:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-24 21:14:22.457  1555  3806 W DriveInitializer: Awaiting to be initialized
,03-24 21:14:22.457  1555  3866 W DriveInitializer: Background init thread started
,03-24 21:14:22.458   768   947 I ActivityManager: Killing 3133:com.google.android.keep/u0a52 (adj 15): empty #17
,03-24 21:14:22.545   768  1242 I ActivityManager: Start proc 3870:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-24 21:14:22.551   768  1240 I ActivityManager: Killing 2917:com.google.android.apps.photos/u0a83 (adj 15): empty #17
,03-24 21:14:22.577   768  1200 I ActivityManager: Killing 2579:com.google.android.gm/u0a41 (adj 15): empty #17
,03-24 21:14:22.589  1341  3827 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 229 ms] updated apps [took 229 ms] 
,03-24 21:14:22.621   930  2087 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10049)] disk I/O error
,--------- beginning of crash
03-24 21:14:22.629   930  2087 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-24 21:14:22.629   930  2087 E AndroidRuntime: Process: android.process.media, PID: 930
03-24 21:14:22.629   930  2087 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-24 21:14:22.629   930  2087 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-24 21:14:22.634  1555  3890 E SQLiteLog: (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
03-24 21:14:22.636  1555  3890 E DocListDatabase: Failed to delete from FileContent163 table
03-24 21:14:22.636  1555  3890 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at com.google.android.gms.drive.database.f.a(:com.google.android.gms:987)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at com.google.android.gms.drive.b.e.run(:com.google.android.gms:74)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at com.google.android.gms.drive.j.ah.run(:com.google.android.gms:51)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:14:22.636  1555  3890 E DocListDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: Can't write: system_app_crash
03-24 21:14:22.641   768  3894 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 21:14:22.641   768  3894 E DropBoxManagerService: 	... 5 more
03-24 21:14:22.641  1203  1505 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-24 21:14:22.641  1203  1505 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-24 21:14:22.652   768  3899 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-24 21:14:22.653   768   832 D Atlas   : Validating map...
,03-24 21:14:22.664  3870  3870 D ExternalStorage: After updating volumes, found 1 active roots
03-24 21:14:22.666  1555  3901 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-24 21:14:22.669  1555  3890 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-24 21:14:22.669  1555  3890 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-24 21:14:22.669  1555  3890 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-24 21:14:22.669  1555  3890 I GCore-Chimera-Crash: ==
03-24 21:14:22.669  1555  3890 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-24 21:14:22.669  1555  3890 E AndroidRuntime: FATAL EXCEPTION: pool-16-thread-1
03-24 21:14:22.669  1555  3890 E AndroidRuntime: Process: com.google.android.gms, PID: 1555
03-24 21:14:22.669  1555  3890 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.a(:com.google.android.gms:987)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at com.google.android.gms.drive.b.e.run(:com.google.android.gms:74)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at com.google.android.gms.drive.j.ah.run(:com.google.android.gms:51)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-24 21:14:22.669  1555  3890 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: Can't write: system_app_crash
03-24 21:14:22.671   768  3903 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-24 21:14:22.671   768  3903 E DropBoxManagerService: 	... 5 more
03-24 21:14:22.674  1555  3901 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-24 21:14:22.674  1555  3901 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-24 21:14:22.674  1555  3901 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-24 21:14:22.674  1555  3901 I GCore-Chimera-Crash: ==
03-24 21:14:22.674  1555  3901 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-24 21:14:22.674  1555  3901 I Process : Sending signal. PID: 1555 SIG: 9
03-24 21:14:22.683   768  3899 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
03-24 21:14:22.684   768  3899 I OpenGLRenderer: Initialized EGL, version 1.4
03-24 21:14:22.688  1341  1341 E LocationReceiver: Received bad location: null
03-24 21:14:22.689   768  3899 D OpenGLRenderer: Enabling debug mode 0
03-24 21:14:22.693   768   869 D WifiService: Client connection lost with reason: 4
03-24 21:14:22.693   768   957 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3c6fa51c)
03-24 21:14:22.693   768   872 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-24 21:14:22.694   768   872 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-24 21:14:22.700   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-24 21:14:22.700   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-24 21:14:22.700   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-24 21:14:22.700   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-24 21:14:22.700   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-24 21:14:22.700   176   176 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-24 21:14:22.700   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: Ctrl commit failed set overlay
03-24 21:14:22.700   176   176 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-24 21:14:22.700   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-24 21:14:22.700   176   176 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-24 21:14:22.700   176   176 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-24 21:14:22.700   176   176 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-24 21:14:22.700   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-24 21:14:22.700   176   176 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-24 21:14:22.700   176   176 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-24 21:14:22.700   176   176 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
03-24 21:14:22.700   176   176 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-24 21:14:22.700   176   176 E qdoverlay: Ctrl commit failed set overlay
03-24 21:14:22.700   176   176 E qdhwcomposer: configure: commit fails
03-24 21:14:22.700   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-24 21:14:22.700   176   176 E qdoverlay: MdpCtrl close error in unset
,03-24 21:14:22.725   768   783 I ActivityManager: Process com.google.android.gms (pid 1555) has died
03-24 21:14:22.726   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.chimera.GmsIntentOperationService in 21000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 21000ms
03-24 21:14:22.727   768   783 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 21000ms
,03-24 21:14:22.756  1646  1689 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-24 21:14:22.756  1646  1689 I qtaguid : Untagging socket 37 failed errno=-22
03-24 21:14:22.756  1646  1689 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-24 21:14:22.974   176   176 E qdoverlay: GenericPipe failed to close ctrl
03-24 21:14:22.974   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-24 21:14:22.974   176   176 E qdoverlay: MdpCtrl close error in unset
03-24 21:14:22.974   176   176 E qdoverlay: GenericPipe failed to close ctrl
03-24 21:14:22.974   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-24 21:14:22.974   176   176 E qdoverlay: MdpCtrl close error in unset
03-24 21:14:22.974   176   176 E qdoverlay: GenericPipe failed to close ctrl
03-24 21:14:22.974   176   176 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-24 21:14:22.974   176   176 E qdoverlay: MdpCtrl close error in unset
03-24 21:14:22.974   176   176 E qdoverlay: GenericPipe failed to close ctrl
,03-24 21:14:22.978   176   176 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-24 21:14:22.978   176   176 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=13 dpy=0 numHwLayers=5
03-24 21:14:22.978   176   176 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-24 21:14:22.978   176   176 E qdhwcomposer: hwc_set_primary: display commit fail!

```
