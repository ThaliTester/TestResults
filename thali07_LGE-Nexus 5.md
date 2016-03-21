#### Test 625481240f1d9b8_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
03-21 16:43:43.731  1560  2407 I CheckinService: Done disabling old GoogleServicesFramework version
,03-21 16:43:44.369  3391  3391 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 16:43:44.371  3391  3391 D AndroidRuntime: CheckJNI is OFF
03-21 16:43:44.478  3391  3391 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-21 16:43:44.482   764  2233 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 16:43:44.488   764  2233 V WindowManager: addAppToken: AppWindowToken{3b55a8ec token=Token{1dfef9f ActivityRecord{6af253e u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
03-21 16:43:44.493   764   833 V WindowManager: Adding window Window{9fa3397 u0 Starting com.test.thalitest} at 2 of 7 (after Window{16e86ce0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-21 16:43:44.502  3391  3391 D AndroidRuntime: Shutting down VM
03-21 16:43:44.507  1403  1423 W SearchService: Abort, client detached.
03-21 16:43:44.540   764   779 I ActivityManager: Start proc 3412:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
03-21 16:43:44.567  1403  1403 I MicroDetector: Keeping mic open: false
03-21 16:43:44.567  1403  1403 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@d269de5
03-21 16:43:44.567  1403  1588 I DeviceStateChecker: DeviceStateChecker cancelled
03-21 16:43:44.627   188  1597 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-21 16:43:44.627   188  1597 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-21 16:43:44.632  1403  1593 I MicroRecognitionRunner: Detection finished
03-21 16:43:44.633  1403  1587 I MicroRecognitionRunner: Stopping hotword detection.
03-21 16:43:44.648  3412  3412 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
03-21 16:43:44.657  3412  3412 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 6688-6689)
03-21 16:43:44.657  3412  3412 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
03-21 16:43:44.725   764   992 I art     : Explicit concurrent mark sweep GC freed 23074(1086KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.166ms total 55.774ms
,03-21 16:43:44.729  3412  3412 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25e2b203}
03-21 16:43:44.729  3412  3412 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106",
03-21 16:43:44.729  3412  3412 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 16:43:44.732   764  1278 I ActivityManager: Killing 3011:com.google.android.deskclock/u0a33 (adj 15): empty #17
,03-21 16:43:44.741  3412  3412 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,03-21 16:43:44.755  3412  3412 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-21 16:43:44.804   764   832 D BluetoothManagerService: Message: 20
03-21 16:43:44.804   764   832 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f22b8c6:true
03-21 16:43:44.806  3412  3412 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
03-21 16:43:44.806  3412  3412 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,03-21 16:43:44.856  3412  3412 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
03-21 16:43:44.856  3412  3412 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,03-21 16:43:44.868  3412  3412 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,03-21 16:43:44.869  3412  3412 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:43:44.874  3412  3412 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
03-21 16:43:44.875  3412  3412 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
03-21 16:43:44.875  3412  3412 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,03-21 16:43:44.876  3412  3412 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,03-21 16:43:44.881  3412  3412 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,03-21 16:43:44.885  3412  3412 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-21 16:43:44.889  3412  3412 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 16:43:44.889  3412  3412 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 16:43:44.905  3412  3467 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 16:43:44.910  3412  3412 D Atlas   : Validating map...
,03-21 16:43:44.920   764  1175 V WindowManager: Adding window Window{218ace4d u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{9fa3397 u0 Starting com.test.thalitest})
,03-21 16:43:44.927   764   867 D WifiService: New client listening to asynchronous messages
,03-21 16:43:44.940   764   944 D ConnectivityService: listenForNetwork for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 16:43:44.940   764   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-21 16:43:44.940   764   868 D ConnectivityService: apparently satisfied.  currentScore=60
03-21 16:43:44.941  3412  3471 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 16:43:45.048   179   179 D SurfaceFlinger: shader cache generated - 24 shaders in 133.554230 ms
,03-21 16:43:45.086  3412  3467 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 16:43:45.091  3412  3467 D OpenGLRenderer: Enabling debug mode 0
,03-21 16:43:45.152   764   833 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +632ms
03-21 16:43:45.153  3412  3412 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-21 16:43:45.171  1095  1095 I Keyboard.Facilitator: onFinishInput()
,03-21 16:43:45.175  3412  3474 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 16:43:45.184  3412  3412 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,03-21 16:43:45.224  3412  3412 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3412
,03-21 16:43:45.409  3412  3412 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 16:43:45.458   764   866 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-54
,03-21 16:43:45.537  3412  3481 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362632064
,03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 16:43:45.540  3412  3481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36cb73c2 added. We now have 1 listener(s)
,03-21 16:43:45.541   764  1197 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 16:43:45.550  3412  3481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
03-21 16:43:45.550  3412  3481 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
,03-21 16:43:45.552  3412  3481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 16:43:45.552  3412  3481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 16:43:45.556  3412  3481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13997809 added. We now have 1 listener(s)
,03-21 16:43:45.557  3412  3481 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 16:43:45.559  3412  3481 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-21 16:43:45.562  3412  3481 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-21 16:43:45.562  3412  3481 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-21 16:43:45.565  3412  3481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 16:43:45.565   764  1175 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-21 16:43:45.566  3412  3481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:43:45.569  3412  3481 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 16:43:45.569  3412  3481 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 16:43:45.569  3412  3481 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 16:43:45.569  3412  3481 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 16:43:45.587  3412  3412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 16:43:45.589  3412  3412 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 16:43:45.594  3412  3412 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 16:43:46.188  3412  3482 W jxcore-log: Initializing JXcore engine
,03-21 16:43:46.189  3412  3482 W jxcore-log: JXcore engine is ready
,03-21 16:43:46.223  3482  3482 W Thread-351: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[8068]" dev="sockfs" ino=8068 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,03-21 16:43:46.223  3482  3482 W Thread-351: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
03-21 16:43:46.223  3482  3482 W Thread-351: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[8124]" dev="sockfs" ino=8124 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
03-21 16:43:46.223  3482  3482 W Thread-351: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18470]" dev="sockfs" ino=18470 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,03-21 16:43:46.246  3412  3482 W jxcore-log: Starting JXcore engine
,03-21 16:43:46.333  3412  3482 W jxcore-log: Platform android
03-21 16:43:46.333  3412  3482 W jxcore-log: 
03-21 16:43:46.334  3412  3482 W jxcore-log: Process ARCH arm
03-21 16:43:46.334  3412  3482 W jxcore-log: 
,03-21 16:43:46.541  3412  3482 I jxcore-log: JXcore Cordova bridge is ready!
03-21 16:43:46.541  3412  3482 I jxcore-log: 
,03-21 16:43:46.541  3412  3482 W jxcore-log: JXcore engine is started
,03-21 16:43:46.546  3412  3481 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 16:43:46.547  3412  3412 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 16:43:48.187  3262  3287 W Babel   : aye TOOK TOO LONG! (15037ms > 10000ms)
,03-21 16:43:48.188  3262  3285 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,03-21 16:43:48.192   764   779 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 16:43:48.196   764   992 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-21 16:43:48.199  3262  3262 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
03-21 16:43:48.199  3262  3262 W Babel   : BAM#gBA: invalid account id: -1
03-21 16:43:48.199  3262  3262 W Babel   : BAM#gBA: invalid account id: -1
03-21 16:43:48.199  3262  3262 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,03-21 16:43:48.201   764  1278 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,03-21 16:43:48.203   764  1197 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,03-21 16:43:48.238  3262  3295 W Babel   : aye TOOK TOO LONG! (15038ms > 10000ms)
,03-21 16:43:48.355  1643  1706 I Finsky  : [135] com.google.android.finsky.b.c.a(289): Completed 0 account content syncs with 0 successful.
,03-21 16:43:48.356  1643  1643 I Finsky  : [1] com.google.android.finsky.services.j.a(150): Installation state replication succeeded.
,03-21 16:43:49.779  1560  1571 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-21 16:43:54.064  1643  1643 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-21 16:43:54.093  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.101  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.103  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.477  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.668  1643  1686 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-21 16:43:54.668  1643  1686 I qtaguid : Untagging socket 38 failed errno=-22
03-21 16:43:54.668  1643  1686 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-21 16:43:54.682  1643  1643 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-21 16:43:54.730  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.775   764  1270 I ActivityManager: Start proc 3564:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,03-21 16:43:54.787   199   199 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 650us total 11.823ms
,03-21 16:43:54.797   199   199 I art     : Explicit concurrent mark sweep GC freed 7(208B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 215us total 8.657ms
,03-21 16:43:54.807   199   199 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 209us total 8.744ms
,03-21 16:43:54.814  3564  3564 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 16:43:54.814  3564  3564 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 16:43:54.846  3564  3564 I MultiDex: VM with version 2.1.0 has multidex support
03-21 16:43:54.846  3564  3564 I MultiDex: install
03-21 16:43:54.846  3564  3564 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 16:43:54.863  3564  3564 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 16:43:54.901  3564  3564 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 16:43:54.914  3564  3564 D ChimeraCfgMgr: Reading stored module config
,03-21 16:43:54.939  1511  1511 D WearableService: callingUid 10007, callindPid: 1511
,03-21 16:43:54.950  1511  1511 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 16:43:54.950  1511  1898 E MDM     : [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-21 16:43:54.950  1560  3588 D LocationInitializer: Restart initialization of location
,03-21 16:43:54.968  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:54.988  1511  1615 W GCoreFlp: No location to return for getLastLocation()
03-21 16:43:54.988  1511  3591 W FusedLocationProvider: location=null
,03-21 16:43:55.008  3564  3587 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-21 16:43:55.017  3564  3564 D CAR.SERVICE: Connecting to CarCallService...
,03-21 16:43:55.028  3564  3564 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-21 16:43:55.028  3564  3564 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-21 16:43:55.034  3564  3564 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-21 16:43:55.038  3564  3564 D CAR.TEL.Service: Creating a new CarCallService.
03-21 16:43:55.039  3564  3564 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-21 16:43:55.040   764   780 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-21 16:43:55.041  3564  3564 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@106c1240
03-21 16:43:55.041   764  1278 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-21 16:43:55.042  3564  3564 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-21 16:43:55.042  3564  3564 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-21 16:43:55.105  3564  3582 D CAR.SERVICE: Package validated; name: com.android.vending
,03-21 16:43:55.242  1643  1687 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-21 16:43:55.242  1643  1687 I qtaguid : Untagging socket 38 failed errno=-22
03-21 16:43:55.242  1643  1687 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-21 16:43:55.692  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:55.790  3412  3482 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 16:43:55.790  3412  3482 I jxcore-log: 
03-21 16:43:55.792  3412  3482 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 16:43:55.792  3412  3482 I jxcore-log: 
,03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 16:43:55.795  3412  3482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 16:43:55.797  3412  3482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 16:43:55.798  3412  3482 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 16:43:55.798  3412  3482 I jxcore-log: 
03-21 16:43:55.799  3412  3482 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 16:43:55.799  3412  3482 I jxcore-log: 
,03-21 16:43:56.288  3412  3482 I jxcore-log: Unit Test app is loaded
03-21 16:43:56.288  3412  3482 I jxcore-log: 
,03-21 16:43:56.292  3412  3482 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 16:43:56.292  3412  3482 I jxcore-log: 
,03-21 16:43:56.298  3412  3482 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-21 16:43:56.300  3412  3482 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-21 16:43:56.300  3412  3482 I jxcore-log: 
03-21 16:43:56.300  3412  3412 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 16:43:56.303  3412  3482 I jxcore-log: logCallback not set !!!!
03-21 16:43:56.303  3412  3482 I jxcore-log: 
03-21 16:43:56.305  3412  3482 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-21 16:43:56.305  3412  3482 I jxcore-log:   bluetooth: 'on',
03-21 16:43:56.305  3412  3482 I jxcore-log:   wifi: 'on',
03-21 16:43:56.305  3412  3482 I jxcore-log:   cellular: 'doNotCare',
03-21 16:43:56.305  3412  3482 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-21 16:43:56.305  3412  3482 I jxcore-log: 
03-21 16:43:56.305  3412  3482 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 16:43:56.305  3412  3482 I jxcore-log: 
,03-21 16:43:56.324  1643  1686 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-21 16:43:56.324  1643  1686 I qtaguid : Untagging socket 38 failed errno=-22
03-21 16:43:56.324  1643  1686 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-21 16:43:56.364   764   780 I ActivityManager: Killing 3032:com.google.android.keep/u0a52 (adj 15): empty #17
,03-21 16:43:56.451  1643  1643 I Finsky  : [1] com.google.android.finsky.autoupdate.ReschedulerUsingJobScheduler.b(99): Scheduling auto-update check using JobScheduler.
,03-21 16:43:56.460  1643  1643 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-21 16:43:56.484  1511  2677 D DeviceConnectionService: client connected with version: 8298000
,03-21 16:43:56.504  1643  1643 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-21 16:43:56.504  1643  1643 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-21 16:43:56.541  3606  3606 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-21 16:43:56.543  3606  3606 D AndroidRuntime: CheckJNI is OFF
,03-21 16:43:56.631  3606  3606 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 16:43:56.636   764   828 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
03-21 16:43:56.636   764   828 I ActivityManager: Killing 3412:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,03-21 16:43:56.667   764   867 D WifiService: Client connection lost with reason: 4
,03-21 16:43:56.668   764   779 I WindowState: WIN DEATH: Window{218ace4d u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-21 16:43:56.668   764   992 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1cf82b1)
03-21 16:43:56.668   764   868 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 16:43:56.669   764   868 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-21 16:43:56.688   764   839 W PackageSettings: Skipping PackageSetting{1446d0e6 com.example.hello/10116} due to missing metadata
,03-21 16:43:56.744   764   828 W ActivityManager: Force removing ActivityRecord{6af253e u0 com.test.thalitest/.MainActivity t19}: app died, no saved state
,03-21 16:43:56.749   764   780 W ActivityManager: Spurious death for ProcessRecord{512c396 3412:com.test.thalitest/u0a49}, curProc for 3412: null
,03-21 16:43:56.754   764   839 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,03-21 16:43:56.789   907   907 I art     : Explicit concurrent mark sweep GC freed 39089(1620KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 764us total 26.260ms
,03-21 16:43:56.793   764   885 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
03-21 16:43:56.794   764   856 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 16:43:56.796  1511  1631 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 16:43:56.824  1560  1560 I art     : Explicit concurrent mark sweep GC freed 4899(219KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 23MB/38MB, paused 918us total 67.536ms
,03-21 16:43:56.825  1095  1095 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 16:43:56.833  1095  3622 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 16:43:56.841  2967  3628 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 16:43:56.846  1095  3622 I Decoder : createOrResetDecoder
,03-21 16:43:56.867   764  1198 I ActivityManager: Start proc 3638:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-21 16:43:56.875   764   764 I art     : Explicit concurrent mark sweep GC freed 27557(1545KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 1.270ms total 104.733ms
03-21 16:43:56.875   764   839 I art     : WaitForGcToComplete blocked for 23.889ms for cause Explicit
,03-21 16:43:56.896  1403  1403 I art     : Explicit concurrent mark sweep GC freed 4234(338KB) AllocSpace objects, 7(154KB) LOS objects, 40% free, 21MB/36MB, paused 1.039ms total 118.581ms
,03-21 16:43:56.898  1511  1511 I ConfigService: onCreate
,03-21 16:43:56.917  3638  3638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-21 16:43:56.935  1095  3622 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 16:43:56.947  1560  3659 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-21 16:43:56.947  1560  3659 D AccountUtils: Clearing selected account for com.test.thalitest
,03-21 16:43:56.950  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-21 16:43:56.950  1511  1511 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-21 16:43:56.955   764  1197 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3412 uid 10049
,03-21 16:43:56.958  1095  1095 I Keyboard.Facilitator: onFinishInput()
,03-21 16:43:56.963  1560  3659 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-21 16:43:56.965   764   764 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-21 16:43:56.966   764   764 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 16:43:56.997  1403  1403 W LocationOracle: Best location was null
03-21 16:43:56.997  1403  1403 I MicroDetectionWorker: Micro detection mode: [mDetectionMode: [1]].
,03-21 16:43:57.010  1560  3666 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 16:43:57.011  1403  3668 I MicroRecognitionRunner: Starting detection.
,03-21 16:43:57.013  1403  3670 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.ae@2cb42214
,03-21 16:43:57.019  1247  1247 I art     : Explicit concurrent mark sweep GC freed 3568(239KB) AllocSpace objects, 6(531KB) LOS objects, 38% free, 25MB/41MB, paused 890us total 36.551ms
,03-21 16:43:57.021  1095  3622 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-21 16:43:57.022  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 16:43:57.022  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 16:43:57.030  1560  3666 W BaseAppContext: Using Auth Proxy for data requests.
03-21 16:43:57.030   188  3674 I AudioFlinger: AudioFlinger's thread 0xb4403000 ready to run
03-21 16:43:57.032  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 16:43:57.032  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-21 16:43:57.033  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 16:43:57.033  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-21 16:43:57.033  1095  3622 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 16:43:57.033  1095  3622 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 16:43:57.033  1095  3622 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 16:43:57.034  1095  3622 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 16:43:57.034  1095  3622 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 16:43:57.034  1095  3622 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 16:43:57.035  1560  3659 I GMPM-SVC: App measurement is starting up, version: 8703
03-21 16:43:57.035  1560  3659 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-21 16:43:57.047  1403  3670 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.ae@2cb42214
,03-21 16:43:57.057   188  3674 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-21 16:43:57.057   188  3674 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-21 16:43:57.057   188  3674 D         : Failed to fetch the lookup information of the device 0000003E 
03-21 16:43:57.057   188  3674 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-21 16:43:57.057   188  3674 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-21 16:43:57.062   188  3674 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-21 16:43:57.080  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.087  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.091  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.095  1403  3679 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-21 16:43:57.110  1560  1617 I Icing   : doRemovePackageData com.test.thalitest
,03-21 16:43:57.117  1560  3659 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-21 16:43:57.121  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.144  1560  3687 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,03-21 16:43:57.144  1560  3687 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-21 16:43:57.145  1560  3687 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-21 16:43:57.145   764   839 I art     : Explicit concurrent mark sweep GC freed 17886(1329KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.415ms total 270.002ms
03-21 16:43:57.145  1560  3687 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-21 16:43:57.150  1560  3687 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
03-21 16:43:57.150  1560  3687 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-21 16:43:57.150  1560  3687 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-21 16:43:57.153  1403  1403 I MicroDetectionWorker: onReady
,03-21 16:43:57.158  1560  3687 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
03-21 16:43:57.158  1560  3687 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,03-21 16:43:57.162   764   764 I ActivityManager: Start proc 3688:com.android.documentsui/u0a34 for broadcast com.android.documentsui/.PackageReceiver
,03-21 16:43:57.163  1560  3687 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
03-21 16:43:57.164  1560  3687 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-21 16:43:57.164  1560  3687 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-21 16:43:57.164  1560  3687 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-21 16:43:57.171  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.185  1511  1615 W GCoreFlp: No location to return for getLastLocation()
,03-21 16:43:57.193   764  1270 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-21 16:43:57.193   764   868 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
03-21 16:43:57.193   764   868 D ConnectivityService: apparently satisfied.  currentScore=60
03-21 16:43:57.194  1560  3706 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-21 16:43:57.225  1403  3679 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,03-21 16:43:57.237  1247  1443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 16:43:57.274  3606  3606 I art     : System.exit called, status: 0
03-21 16:43:57.274  3606  3606 I AndroidRuntime: VM exiting with result code 0.
,03-21 16:43:57.288   764  3680 I ActivityManager: Start proc 3711:com.android.externalstorage/u0a6 for content provider com.android.externalstorage/.ExternalStorageProvider
,03-21 16:43:57.338   764   839 I ActivityManager: Start proc 3729:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,03-21 16:43:57.343   764  1278 I ActivityManager: Killing 2648:com.google.android.calendar/u0a28 (adj 15): empty #17
,03-21 16:43:57.382   764  1175 I ActivityManager: Killing 2068:com.android.providers.calendar/u0a1 (adj 15): empty #17
,03-21 16:43:57.421  3711  3711 D ExternalStorage: After updating volumes, found 1 active roots
,03-21 16:43:57.433  1643  3751 I Finsky  : [146] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 16:43:57.438   764  1209 I ActivityManager: Killing 3065:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,03-21 16:43:57.483  1247  1494 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
03-21 16:43:57.483  1247  1494 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,03-21 16:43:57.492  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 16:43:57.503  1403  1403 E LocationReceiver: Received bad location: null
,03-21 16:43:57.507  1560  3665 W DriveInitializer: Awaiting to be initialized
,03-21 16:43:57.507  1560  3753 W DriveInitializer: Background init thread started
,03-21 16:43:57.511  1560  3753 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,03-21 16:43:57.512  1560  3753 E DocListDatabase: Failed to delete from ContentFileDeletionLock163 table
03-21 16:43:57.512  1560  3753 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-21 16:43:57.512  1560  3753 E DocListDatabase: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
03-21 16:43:57.512  1560  3753 W DriveInitializer: Background init thread ended
03-21 16:43:57.513  1560  3665 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-21 16:43:57.514  1560  3665 E DriveAsyncService: disk I/O error (code 3850)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(:com.google.android.gms:486)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(:com.google.android.gms:461)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(:com.google.android.gms:1519)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bl.a(:com.google.android.gms:16)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
03-21 16:43:57.514  1560  3665 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,03-21 16:43:57.517  1560  3753 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-21 16:43:57.517  1560  3753 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
03-21 16:43:57.517  1560  3753 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-21 16:43:57.517  1560  3753 I GCore-Chimera-Crash: ==
03-21 16:43:57.517  1560  3753 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
03-21 16:43:57.517  1560  3753 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
03-21 16:43:57.517  1560  3753 E AndroidRuntime: Process: com.google.android.gms, PID: 1560
03-21 16:43:57.517  1560  3753 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(:com.google.android.gms:330)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(:com.google.android.gms:1065)
03-21 16:43:57.517  1560  3753 E AndroidRuntime: 	at com.google.android.gms.drive.t.run(:com.google.android.gms:62)
,03-21 16:43:57.525   764   828 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 16:43:57.525   764   828 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 16:43:57.525   764  3754 E DropBoxManagerService: Can't write: system_app_crash
03-21 16:43:57.525   764  3754 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-21 16:43:57.525   764  3754 E DropBoxManagerService: 	... 5 more
,03-21 16:43:57.541   764  3758 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-21 16:43:57.541   764   828 D Atlas   : Validating map...
,03-21 16:43:57.557  3688  3707 D Documents: Update found 7 roots in 321ms
,03-21 16:43:57.567   179   179 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
03-21 16:43:57.567   179   179 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
03-21 16:43:57.567   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
03-21 16:43:57.567   179   179 E qdoverlay: MdpData failed to play
03-21 16:43:57.567   179   179 E qdoverlay: == Dump MdpData start ==
03-21 16:43:57.567   179   179 E qdoverlay: == Dump OvFD fd=48 path=/dev/graphics/fb0 start/end ==
03-21 16:43:57.567   179   179 E qdoverlay: mOvData msmfb_overlay_data id=64
03-21 16:43:57.567   179   179 E qdoverlay: data msmfb_data offset=0 memid=45 id=0 flags=0x0 priv=0
03-21 16:43:57.567   179   179 E qdoverlay: == Dump MdpData end ==
03-21 16:43:57.567   179   179 E qdhwcomposer: draw: queueBuffer failed for display:0 
03-21 16:43:57.567   179   179 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
,03-21 16:43:57.567   179   179 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
03-21 16:43:57.567   179   179 E qdhwcomposer: hwc_set_primary: display commit fail!
,03-21 16:43:57.569   764  3758 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,03-21 16:43:57.569   764  3758 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 16:43:57.574   764  3758 D OpenGLRenderer: Enabling debug mode 0
,03-21 16:43:57.600   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-21 16:43:57.600   179   179 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
,03-21 16:43:57.600   179   179 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-21 16:43:57.600   179   179 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-21 16:43:57.600   179   179 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
03-21 16:43:57.600   179   179 E qdoverlay: src msmfb_img w=2432 h=1920 format=5 MDP_RGB_888
03-21 16:43:57.600   179   179 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: Ctrl commit failed set overlay
03-21 16:43:57.600   179   179 E qdhwcomposer: configureLowRes: commit failed for low res panel
03-21 16:43:57.600   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
03-21 16:43:57.600   179   179 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
03-21 16:43:57.600   179   179 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
03-21 16:43:57.600   179   179 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
03-21 16:43:57.600   179   179 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
03-21 16:43:57.600   179   179 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
03-21 16:43:57.600   179   179 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
03-21 16:43:57.600   179   179 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
,03-21 16:43:57.600   179   179 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
03-21 16:43:57.600   179   179 E qdoverlay: Ctrl commit failed set overlay
03-21 16:43:57.600   179   179 E qdhwcomposer: configure: commit fails
03-21 16:43:57.600   179   179 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
03-21 16:43:57.600   179   179 E qdoverlay: MdpCtrl close error in unset

```
