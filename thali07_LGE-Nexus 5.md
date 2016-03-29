#### Test 63998117de3e24f_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-29 16:20:29.753  1541  2382 I CheckinService: Done disabling old GoogleServicesFramework version
,03-29 16:20:30.055  3451  3451 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-29 16:20:30.066  3451  3451 D AndroidRuntime: CheckJNI is OFF
03-29 16:20:30.181  3451  3451 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-29 16:20:30.184   760  1175 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-29 16:20:30.195   760  1175 V WindowManager: addAppToken: AppWindowToken{43ba903 token=Token{195215b2 ActivityRecord{3d669bbd u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-29 16:20:30.199  3451  3451 D AndroidRuntime: Shutting down VM
03-29 16:20:30.203   760   833 V WindowManager: Adding window Window{3a42a90a u0 Starting com.test.thalitest} at 2 of 7 (after Window{335c68d4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-29 16:20:30.214  1402  1422 W SearchService: Abort, client detached.
03-29 16:20:30.237   760   926 I ActivityManager: Start proc 3472:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-29 16:20:30.252  1402  1586 I DeviceStateChecker: DeviceStateChecker cancelled
03-29 16:20:30.254  1402  1402 I MicroDetector: Keeping mic open: false
03-29 16:20:30.254  1402  1402 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@18c389dd
03-29 16:20:30.266  1402  1580 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
03-29 16:20:30.273   199   199 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 8.965ms total 35.958ms
03-29 16:20:30.287   199   199 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 199us total 9.273ms
03-29 16:20:30.303   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 221us total 14.769ms
03-29 16:20:30.316   188  1593 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-29 16:20:30.316   188  1593 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-29 16:20:30.354  3472  3472 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-29 16:20:30.362  3472  3472 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 7234-7235)
03-29 16:20:30.363  3472  3472 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-29 16:20:30.372  3472  3472 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17cda544}
03-29 16:20:30.372  3472  3472 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-29 16:20:30.372  3472  3472 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-29 16:20:30.377  1402  1589 I MicroRecognitionRunner: Detection finished
03-29 16:20:30.378  1402  1585 I MicroRecognitionRunner: Stopping hotword detection.
03-29 16:20:30.382  3472  3472 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
03-29 16:20:30.401  3472  3472 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-29 16:20:30.426   760  1097 I ActivityManager: Killing 2439:com.google.android.keep/u0a52 (adj 15): empty #17
,03-29 16:20:30.466   760   832 D BluetoothManagerService: Message: 20
03-29 16:20:30.467   760   832 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a8b5e5:true
,03-29 16:20:30.475  3472  3472 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-29 16:20:30.475  3472  3472 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-29 16:20:30.515  3472  3472 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-29 16:20:30.515  3472  3472 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-29 16:20:30.526  3472  3472 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-29 16:20:30.527  3472  3472 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:20:30.532  3472  3472 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-29 16:20:30.533  3472  3472 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-29 16:20:30.533  3472  3472 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-29 16:20:30.534  3472  3472 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-29 16:20:30.539  3472  3472 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-29 16:20:30.543  3472  3472 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-29 16:20:30.547  3472  3472 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-29 16:20:30.547  3472  3472 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-29 16:20:30.563  3472  3529 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-29 16:20:30.568  3472  3472 D Atlas   : Validating map...
,03-29 16:20:30.573   760  1097 V WindowManager: Adding window Window{92299f8 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3a42a90a u0 Starting com.test.thalitest})
,03-29 16:20:30.579   760   864 D WifiService: New client listening to asynchronous messages
,03-29 16:20:30.589   760   776 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 16:20:30.589   760   865 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-29 16:20:30.589   760   865 D ConnectivityService: apparently satisfied.  currentScore=60
03-29 16:20:30.590  3472  3532 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 16:20:30.619  3472  3529 I OpenGLRenderer: Initialized EGL, version 1.4
,03-29 16:20:30.622  3472  3529 D OpenGLRenderer: Enabling debug mode 0
,03-29 16:20:30.691  3472  3539 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-29 16:20:30.775   175   175 D SurfaceFlinger: shader cache generated - 24 shaders in 157.606049 ms
,03-29 16:20:30.785  3472  3472 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-29 16:20:30.793  1099  1099 I Keyboard.Facilitator: onFinishInput()
,03-29 16:20:30.832   760   833 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +617ms
,03-29 16:20:30.849  3472  3472 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-29 16:20:30.852  3472  3472 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3472
,03-29 16:20:31.039  3472  3472 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-29 16:20:31.150  3472  3556 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362830208
,03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-29 16:20:31.160  3472  3556 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20a52127 added. We now have 1 listener(s)
,03-29 16:20:31.161   760  1174 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:20:31.163  3472  3556 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,03-29 16:20:31.165  3472  3556 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-29 16:20:31.166  3472  3556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-29 16:20:31.166  3472  3556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-29 16:20:31.169  3472  3556 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30283c72 added. We now have 1 listener(s)
03-29 16:20:31.169  3472  3556 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-29 16:20:31.171  3472  3556 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-29 16:20:31.173  3472  3556 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-29 16:20:31.173  3472  3556 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-29 16:20:31.175  3472  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-29 16:20:31.176   760  1097 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-29 16:20:31.176  3472  3556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:20:31.180  3472  3556 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-29 16:20:31.180  3472  3556 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-29 16:20:31.180  3472  3556 D io.jxcore.node.ConnectivityMonitor: start: OK
03-29 16:20:31.181  3472  3556 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-29 16:20:31.192  3472  3472 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 16:20:31.195  3472  3472 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-29 16:20:31.204  3472  3472 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-29 16:20:31.317   760   855 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-52
,03-29 16:20:31.746  3472  3557 W jxcore-log: Initializing JXcore engine
03-29 16:20:31.746  3472  3557 W jxcore-log: JXcore engine is ready
,03-29 16:20:31.766  3557  3557 W Thread-356: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9673]" dev="sockfs" ino=9673 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-29 16:20:31.766  3557  3557 W Thread-356: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-29 16:20:31.766  3557  3557 W Thread-356: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[9723]" dev="sockfs" ino=9723 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-29 16:20:31.766  3557  3557 W Thread-356: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[17071]" dev="sockfs" ino=17071 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-29 16:20:31.791  3472  3557 W jxcore-log: Starting JXcore engine
,03-29 16:20:31.868  3472  3557 W jxcore-log: Platform android
03-29 16:20:31.868  3472  3557 W jxcore-log: 
03-29 16:20:31.868  3472  3557 W jxcore-log: Process ARCH arm
03-29 16:20:31.868  3472  3557 W jxcore-log: 
,03-29 16:20:32.058  3472  3557 I jxcore-log: JXcore Cordova bridge is ready!
03-29 16:20:32.058  3472  3557 I jxcore-log: 
03-29 16:20:32.058  3472  3557 W jxcore-log: JXcore engine is started
,03-29 16:20:32.062  3472  3556 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-29 16:20:32.064  3472  3472 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-29 16:20:35.264  3308  3344 W Babel   : aye TOOK TOO LONG! (15027ms > 10000ms)
,03-29 16:20:35.265  3308  3342 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-29 16:20:35.269   760  1205 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-29 16:20:35.272   760   926 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-29 16:20:35.275  3308  3308 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-29 16:20:35.276  3308  3308 W Babel   : BAM#gBA: invalid account id: -1
03-29 16:20:35.276  3308  3308 W Babel   : BAM#gBA: invalid account id: -1
03-29 16:20:35.276  3308  3308 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-29 16:20:35.278   760  1206 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-29 16:20:35.280   760  1098 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-29 16:20:35.307  3308  3352 W Babel   : aye TOOK TOO LONG! (15036ms > 10000ms)
,03-29 16:20:35.477  1541  1552 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-29 16:20:35.526  1641  1703 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-29 16:20:35.527  1641  1641 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-29 16:20:40.292  1641  1641 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-29 16:20:40.320  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:40.326  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:40.328  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:40.417   760  1098 I art     : Explicit concurrent mark sweep GC freed 24895(1185KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.317ms total 56.375ms
,03-29 16:20:41.055  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:41.218  3472  3557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-29 16:20:41.218  3472  3557 I jxcore-log: 
03-29 16:20:41.220  3472  3557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-29 16:20:41.220  3472  3557 I jxcore-log: 
,03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-29 16:20:41.223  3472  3557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-29 16:20:41.225  3472  3557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-29 16:20:41.227  3472  3557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-29 16:20:41.227  3472  3557 I jxcore-log: 
,03-29 16:20:41.228  3472  3557 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-29 16:20:41.228  3472  3557 I jxcore-log: 
,03-29 16:20:41.232  1641  1687 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-29 16:20:41.232  1641  1687 I qtaguid : Untagging socket 37 failed errno=-22
03-29 16:20:41.232  1641  1687 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-29 16:20:41.236  1641  1641 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-29 16:20:41.277  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:41.323   760  1098 I ActivityManager: Start proc 3612:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-29 16:20:41.364  3612  3612 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-29 16:20:41.364  3612  3612 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-29 16:20:41.403  3612  3612 I MultiDex: VM with version 2.1.0 has multidex support
03-29 16:20:41.403  3612  3612 I MultiDex: install
03-29 16:20:41.403  3612  3612 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-29 16:20:41.420  3612  3612 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-29 16:20:41.472  3612  3612 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-29 16:20:41.489  1512  1512 D WearableService: callingUid 10007, callindPid: 1512
,03-29 16:20:41.494  1512  1920 E MDM     : [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-29 16:20:41.498  1512  1512 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-29 16:20:41.501  1541  3638 D LocationInitializer: Restart initialization of location
,03-29 16:20:41.506  3612  3612 D ChimeraCfgMgr: Reading stored module config
,03-29 16:20:41.508  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-29 16:20:41.527  1512  1613 W GCoreFlp: No location to return for getLastLocation()
03-29 16:20:41.527  1512  3641 W FusedLocationProvider: location=null
,03-29 16:20:41.604  3612  3639 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-29 16:20:41.615  3612  3612 D CAR.SERVICE: Connecting to CarCallService...
,03-29 16:20:41.627  3612  3612 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-29 16:20:41.627  3612  3612 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-29 16:20:41.633  3612  3612 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-29 16:20:41.643  3612  3612 D CAR.TEL.Service: Creating a new CarCallService.
,03-29 16:20:41.645  3612  3612 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
03-29 16:20:41.646   760  1098 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-29 16:20:41.646  3612  3612 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@278067ed
,03-29 16:20:41.647   760   926 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-29 16:20:41.647  3612  3612 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-29 16:20:41.647  3612  3612 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-29 16:20:41.697  1641  1686 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-29 16:20:41.697  1641  1686 I qtaguid : Untagging socket 37 failed errno=-22
03-29 16:20:41.697  1641  1686 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
03-29 16:20:41.700  3612  3632 D CAR.SERVICE: Package validated; name: com.android.vending
,03-29 16:20:41.768  3472  3557 I jxcore-log: Unit Test app is loaded
03-29 16:20:41.768  3472  3557 I jxcore-log: 
03-29 16:20:41.771  3472  3557 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-29 16:20:41.771  3472  3557 I jxcore-log: 
03-29 16:20:41.774  3472  3472 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-29 16:20:41.776  3472  3557 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-29 16:20:41.779  3472  3557 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-29 16:20:41.779  3472  3557 I jxcore-log: 
03-29 16:20:41.781  3472  3557 I jxcore-log: logCallback not set !!!!
03-29 16:20:41.781  3472  3557 I jxcore-log: 
,03-29 16:20:41.784  3472  3557 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-29 16:20:41.784  3472  3557 I jxcore-log:   bluetooth: 'on',
03-29 16:20:41.784  3472  3557 I jxcore-log:   wifi: 'on',
03-29 16:20:41.784  3472  3557 I jxcore-log:   cellular: 'doNotCare',
03-29 16:20:41.784  3472  3557 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-29 16:20:41.784  3472  3557 I jxcore-log: 
03-29 16:20:41.784  3472  3557 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-29 16:20:41.784  3472  3557 I jxcore-log: 
,03-29 16:20:42.026  3651  3651 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-29 16:20:42.029  3651  3651 D AndroidRuntime: CheckJNI is OFF
,03-29 16:20:42.117  3651  3651 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-29 16:20:42.123   760   828 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-29 16:20:42.123   760   828 I ActivityManager: Killing 3472:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-29 16:20:42.157   760   864 D WifiService: Client connection lost with reason: 4
,03-29 16:20:42.158   760   926 I WindowState: WIN DEATH: Window{92299f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-29 16:20:42.159   760  1097 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@19c622da)
03-29 16:20:42.159   760   865 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-29 16:20:42.159   760   865 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 16:20:42.164   760   839 W PackageSettings: Skipping PackageSetting{179f710f com.example.hello/10116} due to missing metadata
,03-29 16:20:42.333   760   828 W ActivityManager: Force removing ActivityRecord{3d669bbd u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-29 16:20:42.339   760  1098 W ActivityManager: Spurious death for ProcessRecord{190b85e8 3472:com.test.thalitest/u0a49}, curProc for 3472: null
03-29 16:20:42.339   760   839 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-29 16:20:42.361  1512  1512 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-29 16:20:42.361   760   882 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
,03-29 16:20:42.366  1099  1099 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-29 16:20:42.371   760   847 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-29 16:20:42.380  1512  1629 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-29 16:20:42.388  1099  3666 I Keyboard.Facilitator.DecoderInitializer: run()
,03-29 16:20:42.394  1099  3666 I Decoder : createOrResetDecoder
,03-29 16:20:42.412  1541  1541 I art     : Explicit concurrent mark sweep GC freed 4518(197KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 23MB/38MB, paused 2.035ms total 69.163ms
,03-29 16:20:42.415   903   903 I art     : Explicit concurrent mark sweep GC freed 6878(319KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.673ms total 58.707ms
,03-29 16:20:42.430  1402  1402 I art     : Explicit concurrent mark sweep GC freed 4104(321KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 21MB/29MB, paused 516us total 88.293ms
,03-29 16:20:42.445  1512  1512 I ConfigService: onCreate
,03-29 16:20:42.453  2972  3668 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-29 16:20:42.491   760   760 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-29 16:20:42.491   760   760 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-29 16:20:42.498  1099  3666 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-29 16:20:42.507   760   776 I ActivityManager: Start proc 3678:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-29 16:20:42.511   760  1098 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3472 uid 10049
,03-29 16:20:42.520  1099  1099 I Keyboard.Facilitator: onFinishInput()
,03-29 16:20:42.536  1099  3666 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-29 16:20:42.539  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-29 16:20:42.539  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-29 16:20:42.547  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-29 16:20:42.547  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-29 16:20:42.548  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,03-29 16:20:42.549  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-29 16:20:42.550  1099  3666 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-29 16:20:42.550  1099  3666 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-29 16:20:42.550  1099  3666 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-29 16:20:42.551  1099  3666 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-29 16:20:42.551  1099  3666 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-29 16:20:42.551  1099  3666 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-29 16:20:42.553  1208  1208 I art     : Explicit concurrent mark sweep GC freed 2810(161KB) AllocSpace objects, 7(612KB) LOS objects, 38% free, 25MB/41MB, paused 1.173ms total 22.924ms
,03-29 16:20:42.570  3678  3678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-29 16:20:42.583  1402  1402 W LocationOracle: Best location was null
,03-29 16:20:42.583  1402  1402 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-29 16:20:42.585  1541  3700 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-29 16:20:42.585  1541  3700 D AccountUtils: Clearing selected account for com.test.thalitest
,03-29 16:20:42.599  1541  3700 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-29 16:20:42.601  1512  1512 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,03-29 16:20:42.601  1512  1512 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-29 16:20:42.608  1402  3705 I MicroRecognitionRunner: Starting detection.
,03-29 16:20:42.611  1402  3708 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@66d9ea2
,03-29 16:20:42.622   188  3710 I AudioFlinger: AudioFlinger's thread 0xb4404000 ready to run
,03-29 16:20:42.634  1402  3708 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@66d9ea2
,03-29 16:20:42.644   188  3710 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-29 16:20:42.644   188  3710 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,03-29 16:20:42.644   188  3710 D         : Failed to fetch the lookup information of the device 0000003E 
03-29 16:20:42.644   188  3710 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-29 16:20:42.644   188  3710 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-29 16:20:42.647  1541  3707 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 16:20:42.649   188  3710 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-29 16:20:42.664  1541  3707 W BaseAppContext: Using Auth Proxy for data requests.
,03-29 16:20:42.670  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.671  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.674  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.685  1402  3713 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-29 16:20:42.688   760   839 I art     : Explicit concurrent mark sweep GC freed 30685(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.710ms total 232.079ms
,03-29 16:20:42.692  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.710  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.730   760   760 I ActivityManager: Start proc 3717:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-29 16:20:42.732  1541  3700 I GMPM-SVC: App measurement is starting up, version: 8703
03-29 16:20:42.732  1541  3700 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
03-29 16:20:42.735  1402  1402 I MicroDetectionWorker: onReady
,03-29 16:20:42.739  1208  1439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-29 16:20:42.755  1512  1613 W GCoreFlp: No location to return for getLastLocation()
,03-29 16:20:42.774  1541  3700 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-29 16:20:42.792   760   926 I ActivityManager: Killing 2605:com.google.android.calendar/u0a28 (adj 15): empty #17
,03-29 16:20:42.793  1541  1617 I Icing   : doRemovePackageData com.test.thalitest
,03-29 16:20:42.800  1541  3740 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-29 16:20:42.800  1541  3740 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-29 16:20:42.800  1541  3740 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-29 16:20:42.800  1541  3740 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-29 16:20:42.807  1402  3713 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
03-29 16:20:42.807  1541  3740 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-29 16:20:42.807  1541  3740 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-29 16:20:42.808  1541  3740 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-29 16:20:42.812  1541  3740 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,03-29 16:20:42.812  1541  3740 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
03-29 16:20:42.813  1541  3740 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-29 16:20:42.813  1541  3740 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-29 16:20:42.814  1541  3740 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-29 16:20:42.814  1541  3740 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-29 16:20:42.847  3651  3651 I art     : System.exit called, status: 0
,03-29 16:20:42.847  3651  3651 I AndroidRuntime: VM exiting with result code 0.
,03-29 16:20:42.892   760   839 I ActivityManager: Start proc 3744:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-29 16:20:42.901   760   776 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-29 16:20:42.901   760   865 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-29 16:20:42.901   760   865 D ConnectivityService: apparently satisfied.  currentScore=60
,03-29 16:20:42.903  1541  3760 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-29 16:20:42.945   760  1097 I ActivityManager: Start proc 3764:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-29 16:20:42.950   760   775 I ActivityManager: Killing 2064:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-29 16:20:42.981   760  1175 I ActivityManager: Killing 3042:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-29 16:20:43.029   760  3008 I ActivityManager: Killing 3231:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,03-29 16:20:43.035  1641  1687 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-29 16:20:43.035  1641  1687 I qtaguid : Untagging socket 37 failed errno=-22
03-29 16:20:43.035  1641  1687 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-29 16:20:43.039  1208  1493 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-29 16:20:43.039  1208  1493 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-29 16:20:43.046  3764  3764 D ExternalStorage: After updating volumes, found 1 active roots
,03-29 16:20:43.061  1641  1687 D Volley  : [123] g.a: Could not clean up file /data/data/com.android.vending/cache/main/2602459451202583347
,03-29 16:20:43.100   928  2083 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10049)] disk I/O error
,--------- beginning of crash
03-29 16:20:43.102   928  2083 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
03-29 16:20:43.102   928  2083 E AndroidRuntime: Process: android.process.media, PID: 928
03-29 16:20:43.102   928  2083 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1175)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:117)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:85)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-29 16:20:43.102   928  2083 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-29 16:20:43.131   760  3789 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
03-29 16:20:43.132   760   828 D Atlas   : Validating map...
,03-29 16:20:43.147  1402  1402 E LocationReceiver: Received bad location: null
,03-29 16:20:43.171  1541  3706 W DriveInitializer: Awaiting to be initialized
,03-29 16:20:43.172  1541  3790 W DriveInitializer: Background init thread started

```
