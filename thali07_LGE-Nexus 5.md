#### Test 672996567f6295f_thali07_LGE-Nexus 5 Logs


```
--------- beginning of main
04-21 08:02:11.215  1538  2513 I CheckinService: Done disabling old GoogleServicesFramework version
,04-21 08:02:11.580  3463  3463 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
04-21 08:02:11.582  3463  3463 D AndroidRuntime: CheckJNI is OFF
04-21 08:02:11.690  3463  3463 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
04-21 08:02:11.693   743  1244 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
04-21 08:02:11.700   743  1244 V WindowManager: addAppToken: AppWindowToken{36c94b30 token=Token{17976073 ActivityRecord{1dd544e2 u0 com.test.thalitest/.MainActivity t19}}} to stack=1 task=19 at 0
04-21 08:02:11.705   743   838 V WindowManager: Adding window Window{34ec6aeb u0 Starting com.test.thalitest} at 2 of 7 (after Window{1c1657b5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
04-21 08:02:11.711  1410  1673 W SearchService: Abort, client detached.
04-21 08:02:11.743  3463  3463 D AndroidRuntime: Shutting down VM
04-21 08:02:11.749   743  1242 I ActivityManager: Start proc 3484:com.test.thalitest/u0a49 for activity com.test.thalitest/.MainActivity
04-21 08:02:11.762  1410  1589 I DeviceStateChecker: DeviceStateChecker cancelled
04-21 08:02:11.764  1410  1410 I MicroDetector: Keeping mic open: false
04-21 08:02:11.764  1410  1410 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@3f660bc9
04-21 08:02:11.769   200   200 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 627us total 19.543ms
04-21 08:02:11.780  1410  1537 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
04-21 08:02:11.783   200   200 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 203us total 12.743ms
04-21 08:02:11.793   200   200 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 16MB/26MB, paused 201us total 9.853ms
04-21 08:02:11.813   189  1600 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
04-21 08:02:11.814   189  1600 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
04-21 08:02:11.819  1410  1597 I MicroRecognitionRunner: Detection finished
04-21 08:02:11.820  1410  1588 I MicroRecognitionRunner: Stopping hotword detection.
04-21 08:02:11.885   743  1244 I art     : Explicit concurrent mark sweep GC freed 23411(1151KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.526ms total 77.777ms
,04-21 08:02:11.979  3484  3484 I WebViewFactory: Loading com.google.android.webview version 49.0.2623.105 (code 262310500)
,04-21 08:02:11.987  3484  3484 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 8709-8710)
04-21 08:02:11.988  3484  3484 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
,04-21 08:02:11.996  3484  3484 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {20322332}
04-21 08:02:11.996  3484  3484 I cr_LibraryLoader: Expected native library version number "49.0.2623.105", actual native library version number "49.0.2623.105"
04-21 08:02:11.997  3484  3484 I chromium: [INFO:library_loader_hooks.cc(144)] Chromium logging enabled: level = 0, default verbosity = 0
,04-21 08:02:12.002   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
,04-21 08:02:12.008  3484  3484 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,04-21 08:02:12.022  3484  3484 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-21 08:02:12.075  3484  3484 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
04-21 08:02:12.075  3484  3484 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,04-21 08:02:12.077   743   837 D BluetoothManagerService: Message: 20
04-21 08:02:12.077   743   837 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36c4b251:true
,04-21 08:02:12.113  3484  3484 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
04-21 08:02:12.113  3484  3484 I art     : Rejecting re-init on previously-failed class java.lang.Class<org.chromium.content.browser.FloatingWebActionModeCallback>
,04-21 08:02:12.126  3484  3484 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,04-21 08:02:12.132  3484  3484 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,04-21 08:02:12.133  3484  3484 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,04-21 08:02:12.142  3484  3484 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,04-21 08:02:12.165  3484  3543 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,04-21 08:02:12.171  3484  3484 D Atlas   : Validating map...
,04-21 08:02:12.175   743   759 V WindowManager: Adding window Window{10a83154 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{34ec6aeb u0 Starting com.test.thalitest})
,04-21 08:02:12.183   743   861 D WifiService: New client listening to asynchronous messages
,04-21 08:02:12.192   743  1281 D ConnectivityService: listenForNetwork for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-21 08:02:12.193   743   862 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
04-21 08:02:12.193   743   862 D ConnectivityService: apparently satisfied.  currentScore=60
04-21 08:02:12.194  3484  3545 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
04-21 08:02:12.206  1708  1752 I Finsky  : [139] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,04-21 08:02:12.232  3484  3543 I OpenGLRenderer: Initialized EGL, version 1.4
,04-21 08:02:12.234  3484  3543 D OpenGLRenderer: Enabling debug mode 0
,04-21 08:02:12.288   743   838 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +562ms
,04-21 08:02:12.292  1110  1110 I Keyboard.Facilitator: onFinishInput()
,04-21 08:02:12.320  3484  3552 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,04-21 08:02:12.337  1708  1752 I Finsky  : [139] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,04-21 08:02:12.338  1708  1708 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,04-21 08:02:12.352  3484  3484 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3484
,04-21 08:02:12.513  3484  3484 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,04-21 08:02:12.600  3484  3558 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1362640384
,04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
04-21 08:02:12.603  3484  3558 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12906f24 added. We now have 1 listener(s)
04-21 08:02:12.604   743  1242 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-21 08:02:12.607  3484  3558 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
,04-21 08:02:12.608  3484  3558 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
04-21 08:02:12.608  3484  3558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,04-21 08:02:12.608  3484  3558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
04-21 08:02:12.612  3484  3558 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d552c53 added. We now have 1 listener(s)
04-21 08:02:12.613  3484  3558 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,04-21 08:02:12.617  3484  3558 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,04-21 08:02:12.619  3484  3558 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
04-21 08:02:12.619  3484  3558 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,04-21 08:02:12.623  3484  3558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,04-21 08:02:12.624   743  1244 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,04-21 08:02:12.625  3484  3558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
,04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-21 08:02:12.632  3484  3558 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
04-21 08:02:12.632  3484  3558 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
04-21 08:02:12.632  3484  3558 D io.jxcore.node.ConnectivityMonitor: start: OK
,04-21 08:02:12.633  3484  3558 I io.jxcore.node.LifeCycleMonitor: start: OK
,04-21 08:02:12.634  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-21 08:02:12.636  3484  3484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,04-21 08:02:12.715  3484  3484 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,04-21 08:02:13.530  3484  3559 W jxcore-log: Initializing JXcore engine
04-21 08:02:13.530  3484  3559 W jxcore-log: JXcore engine is ready
,04-21 08:02:13.571  3559  3559 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9772]" dev="sockfs" ino=9772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,04-21 08:02:13.571  3559  3559 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
04-21 08:02:13.571  3559  3559 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[7390]" dev="sockfs" ino=7390 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
04-21 08:02:13.571  3559  3559 W Thread-357: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[14283]" dev="sockfs" ino=14283 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,04-21 08:02:13.598  3484  3559 W jxcore-log: Starting JXcore engine
,04-21 08:02:13.714  3484  3559 W jxcore-log: Platform android
04-21 08:02:13.714  3484  3559 W jxcore-log: 
,04-21 08:02:13.714  3484  3559 W jxcore-log: Process ARCH arm
04-21 08:02:13.714  3484  3559 W jxcore-log: 
,04-21 08:02:13.914  3484  3559 I jxcore-log: JXcore Cordova bridge is ready!
04-21 08:02:13.914  3484  3559 I jxcore-log: 
04-21 08:02:13.915  3484  3559 W jxcore-log: JXcore engine is started
,04-21 08:02:13.920  3484  3558 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,04-21 08:02:13.921  3484  3484 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,04-21 08:02:14.713  3305  3336 W Babel   : aye TOOK TOO LONG! (15022ms > 10000ms)
,04-21 08:02:14.715  3305  3334 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-21 08:02:14.718   743  1108 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-21 08:02:14.722   743  1109 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-21 08:02:14.725  3305  3305 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
04-21 08:02:14.725  3305  3305 W Babel   : BAM#gBA: invalid account id: -1
04-21 08:02:14.726  3305  3305 W Babel   : BAM#gBA: invalid account id: -1
,04-21 08:02:14.727  3305  3305 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,04-21 08:02:14.729   743   934 W Telecom : TelecomServiceImpl: null is not visible for the calling user
,04-21 08:02:14.731   743  1280 W Telecom : TelecomServiceImpl: ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.telephony.TeleConnectionService}, [e44cca915afc0390d8a77c0ff4608152603e7fa3], UserHandle{0} is not visible for the calling user
,04-21 08:02:14.805  3305  3345 W Babel   : aye TOOK TOO LONG! (15040ms > 10000ms)
,04-21 08:02:21.910  1708  1708 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,04-21 08:02:21.952  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:21.957  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:21.958  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:22.616  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:22.724  1708  1708 I Finsky  : [1] com.google.android.finsky.m.e.a(152): Skipping DFE self-update. Local Version [80641200] >= Server Version [-1]
,04-21 08:02:22.773   743  1108 I ActivityManager: Start proc 3609:com.android.providers.calendar/u0a1 for content provider com.android.providers.calendar/.CalendarProvider2
,04-21 08:02:22.799  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:22.815  3609  3609 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,04-21 08:02:22.840   743  1197 I ActivityManager: Start proc 3627:com.google.android.gms:car/u0a7 for service com.google.android.gms/.car.CarService
,04-21 08:02:22.875  3627  3627 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,04-21 08:02:22.875  3627  3627 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,04-21 08:02:22.895  3609  3609 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@21b06f3d(com.android.providers.calendar.CalendarProvider2@20322332)
,04-21 08:02:22.902   743   758 I ActivityManager: Killing 1821:com.android.defcontainer/u0a4 (adj 15): empty #17
,04-21 08:02:22.904  3627  3627 I MultiDex: VM with version 2.1.0 has multidex support
04-21 08:02:22.904  3627  3627 I MultiDex: install
04-21 08:02:22.904  3627  3627 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,04-21 08:02:23.002  3627  3627 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,04-21 08:02:23.038  3627  3627 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,04-21 08:02:23.053  3627  3627 D ChimeraCfgMgr: Reading stored module config
,04-21 08:02:23.055  1626  1626 D WearableService: callingUid 10007, callindPid: 1626
,04-21 08:02:23.059  1626  1945 E MDM     : [187] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,04-21 08:02:23.063  1538  3662 D LocationInitializer: Restart initialization of location
,04-21 08:02:23.066  1626  1626 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,04-21 08:02:23.078  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:23.154  1626  1626 I art     : Explicit concurrent mark sweep GC freed 52141(3MB) AllocSpace objects, 46(736KB) LOS objects, 39% free, 22MB/37MB, paused 1.724ms total 66.193ms
,04-21 08:02:23.164  1626  1663 W GCoreFlp: No location to return for getLastLocation()
04-21 08:02:23.164  1626  3663 W FusedLocationProvider: location=null
,04-21 08:02:23.190  3627  3627 D CAR.SERVICE: Connecting to CarCallService...
,04-21 08:02:23.199  3627  3661 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,04-21 08:02:23.211  3627  3627 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-21 08:02:23.211  3627  3627 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,04-21 08:02:23.217  3627  3627 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,04-21 08:02:23.224  3627  3627 D CAR.TEL.Service: Creating a new CarCallService.
,04-21 08:02:23.225  3627  3627 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,04-21 08:02:23.226   743  1280 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
04-21 08:02:23.226  3627  3627 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@3ad1d043
,04-21 08:02:23.227   743   759 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,04-21 08:02:23.227  3627  3627 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
04-21 08:02:23.227  3627  3627 D CAR.TEL.Service: Starting CarCallService with initial phone null
,04-21 08:02:23.291  3627  3651 D CAR.SERVICE: Package validated; name: com.android.vending
,04-21 08:02:23.662  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:23.698  3484  3559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
04-21 08:02:23.698  3484  3559 I jxcore-log: 
04-21 08:02:23.700  3484  3559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
04-21 08:02:23.700  3484  3559 I jxcore-log: 
,04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
04-21 08:02:23.703  3484  3559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,04-21 08:02:23.705  3484  3559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,04-21 08:02:23.707  3484  3559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
04-21 08:02:23.707  3484  3559 I jxcore-log: 
,04-21 08:02:23.708  3484  3559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
04-21 08:02:23.708  3484  3559 I jxcore-log: 
,04-21 08:02:23.946  1708  1708 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10401): Logging device features
,04-21 08:02:23.973  1626  1642 D DeviceConnectionService: client connected with version: 8486000
,04-21 08:02:23.985  1708  1708 E Finsky  : [1] com.google.android.finsky.wear.bh.a(742): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
04-21 08:02:23.985  1708  1708 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6349): Dropping command=hygiene due to Gms not connected
,04-21 08:02:24.027  3609  3609 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
04-21 08:02:24.027  3609  3609 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,04-21 08:02:24.042  3484  3559 I jxcore-log: Unit Test app is loaded
04-21 08:02:24.042  3484  3559 I jxcore-log: 
,04-21 08:02:24.049  3484  3484 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,04-21 08:02:24.051  3484  3559 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
04-21 08:02:24.051  3484  3559 I jxcore-log: 
,04-21 08:02:24.056  3484  3559 I jxcore-log: My device name is: LGE-Nexus 5
04-21 08:02:24.056  3484  3559 I jxcore-log: 
,04-21 08:02:27.746  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
04-21 08:02:27.746  3484  3559 I jxcore-log: 
,04-21 08:02:27.920  3609  3693 E SQLiteLog: (284) automatic index on view_events(_id)
,04-21 08:02:27.949  1708  3694 I Finsky  : [153] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(162): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,04-21 08:02:27.950  1708  1750 I PlayCommon: [137] com.google.android.play.a.v.a(25540): Starting to flush logs
,04-21 08:02:27.958  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:28.105  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
04-21 08:02:28.105  3484  3559 I jxcore-log: 
,04-21 08:02:28.129  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
04-21 08:02:28.129  3484  3559 I jxcore-log: 
04-21 08:02:28.133  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
04-21 08:02:28.133  3484  3559 I jxcore-log: 
,04-21 08:02:28.150  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
04-21 08:02:28.150  3484  3559 I jxcore-log: 
,04-21 08:02:28.154  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
04-21 08:02:28.154  3484  3559 I jxcore-log: 
,04-21 08:02:28.447  3627  3627 D CAR.SERVICE: mConnectedToCar = false, abort
,04-21 08:02:28.449   743  1197 I ActivityManager: Killing 3063:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,04-21 08:02:28.455  3627  3627 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2fc9a9c1 that was originally bound here
04-21 08:02:28.455  3627  3627 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2fc9a9c1 that was originally bound here
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2761)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:151)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-21 08:02:28.455  3627  3627 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-21 08:02:28.498  1708  1750 I PlayCommon: [137] com.google.android.play.a.v.a(25551): Log flushed by 1 successful uploads
,04-21 08:02:28.554  3627  3627 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@15d751f2 that was originally bound here
04-21 08:02:28.554  3627  3627 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@15d751f2 that was originally bound here
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1077)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:971)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1774)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1757)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:539)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2788)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:151)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1391)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
04-21 08:02:28.554  3627  3627 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,04-21 08:02:28.556   743  1244 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1807e155
,04-21 08:02:29.126   743  1244 I ActivityManager: Killing 3116:com.google.android.apps.docs/u0a35 (adj 15): empty #17
,04-21 08:02:29.207   743  1244 I ActivityManager: Killing 3085:com.android.musicfx/u0a13 (adj 15): empty #18
,04-21 08:02:30.115  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
04-21 08:02:30.115  3484  3559 I jxcore-log: 
,04-21 08:02:30.125  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
04-21 08:02:30.125  3484  3559 I jxcore-log: 
,04-21 08:02:30.134  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
04-21 08:02:30.134  3484  3559 I jxcore-log: 
,04-21 08:02:30.287  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
04-21 08:02:30.287  3484  3559 I jxcore-log: 
,04-21 08:02:31.187  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
04-21 08:02:31.187  3484  3559 I jxcore-log: 
,04-21 08:02:31.245  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
04-21 08:02:31.245  3484  3559 I jxcore-log: 
,04-21 08:02:31.251  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
04-21 08:02:31.251  3484  3559 I jxcore-log: 
,04-21 08:02:31.387  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
04-21 08:02:31.387  3484  3559 I jxcore-log: 
,04-21 08:02:31.407  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
04-21 08:02:31.407  3484  3559 I jxcore-log: 
04-21 08:02:31.411  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
04-21 08:02:31.411  3484  3559 I jxcore-log: 
04-21 08:02:31.416  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
04-21 08:02:31.416  3484  3559 I jxcore-log: 
,04-21 08:02:31.432  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
04-21 08:02:31.432  3484  3559 I jxcore-log: 
,04-21 08:02:31.451  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
04-21 08:02:31.451  3484  3559 I jxcore-log: 
,04-21 08:02:31.535  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
04-21 08:02:31.535  3484  3559 I jxcore-log: 
,04-21 08:02:31.540  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
04-21 08:02:31.540  3484  3559 I jxcore-log: 
,04-21 08:02:31.564  3484  3559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
04-21 08:02:31.564  3484  3559 I jxcore-log: 
,04-21 08:02:31.574  3484  3559 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
04-21 08:02:31.575  3484  3559 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
04-21 08:02:31.575  3484  3559 I jxcore-log: 
,04-21 08:02:32.006   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
04-21 08:02:32.006   743   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-21 08:02:38.745  1708  1752 I Finsky  : [139] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,04-21 08:02:38.841  1708  1752 I Finsky  : [139] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,04-21 08:02:38.841  1708  1708 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,04-21 08:02:52.010   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-48
,04-21 08:02:54.900  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:54.904  1626  3750 I VacuumService: Vacuum at: now=1461218574903 tag=VacuumService
,04-21 08:02:54.999   743  1280 I art     : Explicit concurrent mark sweep GC freed 38847(1825KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 2.010ms total 68.023ms
,04-21 08:02:55.925  1626  3759 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,04-21 08:02:55.928  1626  3759 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,04-21 08:02:57.537  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:02:57.537  1626  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,04-21 08:03:12.014   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
,04-21 08:03:12.014   743   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-21 08:03:12.329  1110  1315 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-21 08:03:12.329  1110  1315 I Keyboard.Facilitator: flushDynamicLanguageModels()
,04-21 08:03:12.380  1626  1626 I ConfigService: onCreate
,04-21 08:03:17.423  1626  1626 I ConfigService: onDestroy
,04-21 08:03:32.018   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-47
04-21 08:03:32.019   743   860 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2447
,04-21 08:03:47.499   743   840 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
04-21 08:03:47.504   743   840 I PowerManagerService: Sleeping (uid 1000)...
,04-21 08:03:47.564   743   840 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 01/14/15, ab0075f, Id3510ff6dc
,04-21 08:03:47.599   189   876 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,04-21 08:03:47.610   743   860 E WifiStateMachine: cancelDelayedScan -> 11
,04-21 08:03:47.616   179   357 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (109 us)
,04-21 08:03:47.625   743   860 E native  : do suspend false
,04-21 08:03:47.772  1970  2037 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-21 08:03:47.790  1970  2037 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,04-21 08:03:47.794   189   189 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,04-21 08:03:47.798  1110  1110 I Keyboard.Facilitator: onFinishInput()
,04-21 08:03:47.803   743   860 E WifiStateMachine: cancelDelayedScan -> 13
,04-21 08:03:47.805   743   860 E native  : do suspend true
,04-21 08:03:48.111   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
04-21 08:03:48.111   743   860 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,04-21 08:03:48.179   743   838 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,04-21 08:03:48.181   179   179 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6082000
04-21 08:03:48.182   179   179 D qdhwcomposer: hwc_blank: Blanking display: 0
04-21 08:03:48.187   743   743 V ActivityManager: Display changed displayId=0
,04-21 08:03:48.315   180   180 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
04-21 08:03:48.315   180   180 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
04-21 08:03:48.315   180   180 I rmt_storage: wakelock acquired: 1, error no: 2
04-21 08:03:48.315   180   565 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236803456)
,04-21 08:03:48.383   180   565 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
04-21 08:03:48.383   180   565 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
04-21 08:03:48.384   180   565 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236803456) wakelock released: 1, error no: 0
04-21 08:03:48.384   180   565 I rmt_storage: 
,04-21 08:03:48.386   180   180 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
,04-21 08:03:48.468   179   179 D qdhwcomposer: hwc_blank: Done blanking display: 0
04-21 08:03:48.469   743   886 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
04-21 08:03:48.469  1925  1927 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
,04-21 08:03:48.492  3484  3484 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
04-21 08:03:48.492  3484  3484 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,04-21 08:03:48.522  3484  3484 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@147a82eb Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e88d287, 16908290=android.view.AbsSavedState$1@e88d287}, android:focusedViewId=100}]}]
04-21 08:03:48.522  3484  3484 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
04-21 08:03:48.522  3484  3484 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
04-21 08:03:48.522  3484  3484 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,04-21 08:03:52.022   743   860 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=f4:f2:6d:22:99:3e RSSI=-46
04-21 08:03:52.023   743   860 E WifiStateMachine: WifiStateMachine L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,04-21 08:03:53.158  1626  1701 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,04-21 08:04:47.833  3484  3559 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
04-21 08:04:47.833  3484  3559 I jxcore-log: 
,04-21 08:04:47.837  1110  1315 I Keyboard.Facilitator.LanguageModelFlusher: run()
04-21 08:04:47.837  1110  1315 I Keyboard.Facilitator: flushDynamicLanguageModels()
04-21 08:04:47.863  1626  1626 I ConfigService: onCreate
,04-21 08:04:48.214  3842  3842 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,04-21 08:04:48.219  3842  3842 D AndroidRuntime: CheckJNI is OFF
,04-21 08:04:48.316  3842  3842 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,04-21 08:04:48.323   743   833 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=-1: uninstall pkg
04-21 08:04:48.324   743   833 I ActivityManager: Killing 3484:com.test.thalitest/u0a49 (adj 0): stop com.test.thalitest
,04-21 08:04:48.368   743   844 W PackageSettings: Skipping PackageSetting{f3330a1 com.example.hello/10116} due to missing metadata
,04-21 08:04:48.389   743   861 D WifiService: Client connection lost with reason: 4
,04-21 08:04:48.389   743  1242 I WindowState: WIN DEATH: Window{10a83154 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,04-21 08:04:48.390   743  1281 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@4112e88)
04-21 08:04:48.390   743   862 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-21 08:04:48.390   743   862 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-21 08:04:48.534   743   833 I ActivityManager:   Force finishing activity 3 ActivityRecord{1dd544e2 u0 com.test.thalitest/.MainActivity t19}
,04-21 08:04:48.537   743   759 W ActivityManager: Spurious death for ProcessRecord{3cae7021 3484:com.test.thalitest/u0a49}, curProc for 3484: null
,04-21 08:04:48.537   743   844 I ActivityManager: Force stopping com.test.thalitest appid=10049 user=0: pkg removed
,04-21 08:04:48.539   743   844 I ActivityManager:   Force finishing activity 3 ActivityRecord{1dd544e2 u0 com.test.thalitest/.MainActivity t19 f}
04-21 08:04:48.539   743   844 W ActivityManager: Duplicate finish request for ActivityRecord{1dd544e2 u0 com.test.thalitest/.MainActivity t19 f}
,04-21 08:04:48.572  1254  1254 I art     : Explicit concurrent mark sweep GC freed 1679(106KB) AllocSpace objects, 8(693KB) LOS objects, 38% free, 25MB/41MB, paused 3.045ms total 27.391ms
,04-21 08:04:48.580   909   909 I art     : Explicit concurrent mark sweep GC freed 9810(430KB) AllocSpace objects, 0(0B) LOS objects, 28% free, 40MB/56MB, paused 1.040ms total 34.148ms
,04-21 08:04:48.608   743   888 D TaskPersister: removeObsoleteFile: deleting file=19_task.xml
04-21 08:04:48.609   743   888 D TaskPersister: removeObsoleteFile: deleting file=19_task_thumbnail.png
,04-21 08:04:48.613   743   852 I InputReader: Reconfiguring input devices.  changes=0x00000010
,04-21 08:04:48.617  1626  1670 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,04-21 08:04:48.620  1538  1538 I art     : Explicit concurrent mark sweep GC freed 2579(152KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 985us total 73.765ms
,04-21 08:04:48.627  1110  1110 I Keyboard.Facilitator: resetDictionaries() : en_US
,04-21 08:04:48.629  1110  3877 I Keyboard.Facilitator.DecoderInitializer: run()
,04-21 08:04:48.631  2767  3878 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,04-21 08:04:48.638  1410  1410 I art     : Explicit concurrent mark sweep GC freed 6990(433KB) AllocSpace objects, 7(154KB) LOS objects, 24% free, 22MB/30MB, paused 510us total 94.887ms
,04-21 08:04:48.639  1110  3877 I Decoder : createOrResetDecoder
,04-21 08:04:48.648   743   743 I art     : Explicit concurrent mark sweep GC freed 39231(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/44MB, paused 5.765ms total 75.948ms
04-21 08:04:48.649   743   844 I art     : WaitForGcToComplete blocked for 13.037ms for cause Explicit
,04-21 08:04:48.669   743  1108 I ActivityManager: Start proc 3879:com.android.musicfx/u0a13 for broadcast com.android.musicfx/.Compatibility$Receiver
,04-21 08:04:48.693  1110  3877 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,04-21 08:04:48.717  1110  3877 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
04-21 08:04:48.719  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
04-21 08:04:48.719  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,04-21 08:04:48.721  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
04-21 08:04:48.721  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,04-21 08:04:48.724   743   743 W ResourcesManager: Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,04-21 08:04:48.727  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
04-21 08:04:48.727  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,04-21 08:04:48.730  1110  3877 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
04-21 08:04:48.730  1110  3877 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
04-21 08:04:48.730  1110  3877 I Keyboard.Facilitator.Delight2FileSweeper: run()
04-21 08:04:48.730  1110  3877 I Keyboard.Facilitator.RecurringTaskScheduler: run()
04-21 08:04:48.730  1110  3877 I StatsUtilsManager: startPeriodStatsRecorder() : Success
04-21 08:04:48.731  1110  3877 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,04-21 08:04:48.738   743  1197 I ActivityManager: Start proc 3901:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,04-21 08:04:48.742   743  1109 I ActivityManager: Killing 3161:com.quickoffice.android/u0a65 (adj 15): empty #17
,04-21 08:04:48.758   743   743 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,04-21 08:04:48.759   743   743 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,04-21 08:04:48.762   743  1281 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3484 uid 10049
,04-21 08:04:48.765  1110  1110 I Keyboard.Facilitator: onFinishInput()
,04-21 08:04:48.773   743   844 I art     : Explicit concurrent mark sweep GC freed 12915(1547KB) AllocSpace objects, 2(1312KB) LOS objects, 33% free, 28MB/42MB, paused 2.181ms total 123.640ms
,04-21 08:04:48.776  1254  1254 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,04-21 08:04:48.798  3901  3901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,04-21 08:04:48.806  1538  3920 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-21 08:04:48.806  1538  3920 D AccountUtils: Clearing selected account for com.test.thalitest
,04-21 08:04:48.816  1538  3920 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,04-21 08:04:48.817  1626  1626 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
04-21 08:04:48.817  1626  1626 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,04-21 08:04:48.821  1708  1708 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(274): Wear auto uninstall disabled for package com.test.thalitest
,04-21 08:04:48.850   743  1108 I ActivityManager: Start proc 3925:com.google.android.apps.docs/u0a35 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,04-21 08:04:48.865  3842  3842 I art     : System.exit called, status: 0
04-21 08:04:48.865  3842  3842 I AndroidRuntime: VM exiting with result code 0.
,04-21 08:04:48.908   743   844 I ActivityManager: Start proc 3944:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
,04-21 08:04:48.945  1538  3920 I GMPM-SVC: App measurement is starting up, version: 8703
04-21 08:04:48.945  1538  3920 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,04-21 08:04:48.948  1538  3938 W BaseAppContext: Using Auth Proxy for data requests.
,04-21 08:04:48.949   743  1281 I ActivityManager: Killing 2707:com.google.android.keep/u0a52 (adj 15): empty #17
,04-21 08:04:49.002  1254  1454 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
04-21 08:04:49.003  1538  3938 W BaseAppContext: Using Auth Proxy for data requests.
,04-21 08:04:49.006   743  1280 D ConnectivityService: listenForNetwork for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,04-21 08:04:49.006   743   862 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,04-21 08:04:49.006   743   862 D ConnectivityService: apparently satisfied.  currentScore=60
,04-21 08:04:49.007  1538  3967 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,04-21 08:04:49.016  1538  3938 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-21 08:04:49.016  1538  3938 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,04-21 08:04:49.017  1538  1625 I Icing   : doRemovePackageData com.test.thalitest
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: Runtime exception while performing operation
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-21 08:04:49.021  1538  3938 E ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at com.google.android.gms.common.k.a.delete(:com.google.android.gms:272)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(:com.google.android.gms:27)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.d.a(:com.google.android.gms:111)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
04-21 08:04:49.022  1538  3938 F ClearPendingStateOp: 	at java.lang.Thread.run(Thread.java:818)
04-21 08:04:49.023  1538  3920 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
04-21 08:04:49.024  1538  3969 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
04-21 08:04:49.034   743  3972 E DropBoxManagerService: Can't write: system_app_wtf
04-21 08:04:49.034   743  3972 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-21 08:04:49.034   743  3972 E DropBoxManagerService: 	... 5 more
04-21 08:04:49.035  1538  1910 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
04-21 08:04:49.035  1538  1910 E Icing   : Failed to open Apps corpus file.
04-21 08:04:49.036  1538  1910 E Icing   : Failed to open Apps corpus file.
04-21 08:04:49.037  1538  1910 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
04-21 08:04:49.042  1538  3969 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
04-21 08:04:49.042  1538  3969 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM4KRjW36UR
04-21 08:04:49.042  1538  3969 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
04-21 08:04:49.042  1538  3969 I GCore-Chimera-Crash: ==
04-21 08:04:49.042  1538  3969 I GCore-Chimera-Crash: GCore-Chimera-Crash
--------- beginning of crash
04-21 08:04:49.046  1538  3969 E AndroidRuntime: FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
04-21 08:04:49.046  1538  3969 E AndroidRuntime: Process: com.google.android.gms, PID: 1538
04-21 08:04:49.046  1538  3969 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at com.google.android.gms.people.c.e.a(:com.google.android.gms:110)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at com.google.android.gms.people.sync.a.b.d(:com.google.android.gms:3165)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.b.a(:com.google.android.gms:245)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(:com.google.android.gms:77)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
04-21 08:04:49.046  1538  3969 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
04-21 08:04:49.048  1538  3969 I Process : Sending signal. PID: 1538 SIG: 9
04-21 08:04:49.050   743  3976 E DropBoxManagerService: Can't write: system_app_crash
04-21 08:04:49.050   743  3976 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
04-21 08:04:49.050   743  3976 E DropBoxManagerService: 	... 5 more
,04-21 08:04:49.072   743  1109 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1dab41c0)
04-21 08:04:49.072   743   862 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
04-21 08:04:49.072   743   861 D WifiService: Client connection lost with reason: 4
04-21 08:04:49.073   743   862 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
